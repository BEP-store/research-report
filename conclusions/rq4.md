# What limitations does the existing FeedbackFruits ecosystem impose on the software?

Section 4 describes how to integrate with the current FeedbackFruits platform. The first limitation imposed is the usage of material design [^materialdesign]. Other limitations depend upon the method of extending the platform.

This first method is to provide a new type of activity. As such its scope is limited to activities. Furthermore, the implementation is restricted to be a Rails engine [^railsengine] and/or an Ember addon [^emberaddon] and its API must extend the activity API. These restrictions stem mostly from the current implementation of the FeedbackFruits platform back-end.

The second method circumvents the FeedbackFruits back-end. It limits implementations only on the front-end side to be an Ember addon and does not impose the limition of the activity API.
However, this also takes away the test suite that comes with the activity API. Because of this, it is more difficult to assess if the extension will be able to integrate with the current FeedbackFruits platform properly.

[^materialdesign]: https://www.google.com/design/spec/material-design/introduction.html
[^railsengine]: http://guides.rubyonrails.org/engines.html
[^emberaddon]: https://www.emberaddons.com/
