# Integration with FeedbackFruits

To integrate with the existing FeedbackFruits platform, some requirements have to be met by any solution to the problem. This section lists these requirements, and offers some suggestions for meeting them.

## Current platform structure

FeedbackFruits is an online education platform, built on modern web technologies such as Ruby on Rails [^rubyonrails], Ember.js [^emberjs], MongoDB [^mongodb] and Node.js [^nodejs]. The platform is structured with micro-services in the form of different servers that each serve a single front-end, and are also capable of talking to each other.

The platform is heavily structured around activities, such as videos, documents and assignments. These activities have an API and can be extended to incorporate custom functionality. A Ruby on Rails back-end aggregates the different engines that offer types of activities and serves it as one API.

The activities get requested in an Ember.js front-end and displayed in a material design [^materialdesign] user interface. Each type of activity can optionally be rendered using custom logic for that type, contained within an Ember addon [^emberaddon].

## Extensibility

At the moment of writing this report, there are two ways to integrate with the FeedbackFruits platform in a modular way. The first and simpler way is to add a new type of activity. This can be done by creating a Rails engine [^railsengine] and implementing the activity according to the existing API. This will allow the engine to run within the FeedbackFruits platform. The activity can then be displayed in the frontend with an Ember addon for the new activity type.

The second way to extend the platform is to circumvent the back-end and link the Ember addon to an external back-end in the form of a micro-service. An advantage of this approach is that the service is only restricted by the communication with the Ember addon. effectively removing all restrictions in terms of implementation. One disadvantage is that another source of latency is introduced in the form of a new server.

[^rubyonrails]: http://rubyonrails.org/
[^emberjs]: http://emberjs.com/
[^mongodb]: https://www.mongodb.org/
[^nodejs]: https://nodejs.org/en/
[^materialdesign]: https://www.google.com/design/spec/material-design/introduction.html
[^railsengine]: http://guides.rubyonrails.org/engines.html
[^emberaddon]: https://www.emberaddons.com/
