# Existing Communities

## What techniques are currently used to involve a community with software development?
There are many projects that are build with the help of an online community. The largest projects include the development of the Linux kernel[^linuxrepo], the Apache project[^apacherepo] and the Mozilla browser[^mozillarepo]. To include the online communities during the development of such online software it is necessary to keep everyone up to date and informed about the current state of the project. In short, the means needed can be divided into five categories: communication, version control, issue tracking, testing and package management `citation? wiki: https://en.wikipedia.org/wiki/Open-source_software_development`. For each of these categories will be invested what techniques are currently used by software development projects.

### Communication
Communication is perhaps the most important factor when it comes to collaborative software development. Much communication is traditionally done via e-mail, instant messaging, phone, web meetings and groupware {{"thissen2007communication" | cite}}. However as of late new, more enhanced tools like Slack[^slackwebsite] have emerged. With for example Slack it is possible to integrate updates from other development tools such as GitHub and make the visible to the whole team.

### Version control
Many software project makes use of software versioning. According to the annual Eclipse Community service this percentage totals to almost eighty percent (Git 43.9%, Subversion 30.7%, Other 5.8%) in 2014 {{"eclipse2014survey" | cite}}. From the statistics in the figure below can be concluded that the Git has become the most popular version control method. The main reasons for the growing popularity of Git is its feature set and the usage in large projects such as the aformentioned Linux project {{"stephen2015git" | cite}}.

{% chart format="yaml" %}
padding: 50
data:
    type: line
    x: 'year'
    columns:
        - [year, 2011, 2012, 2013, 2014]
        - [Git, 12.8, 32, 36.3, 43.9]
        - [Subversion, 51.3, 46, 37.8, 30.7]
        - [Mercurial & CVS, 17.9, 11.5, 8.1, 5.8]
    axes:
        data2: y2
axis:
    y2:
        show: true
title:
    text: "Version control popularity by type"
{% endchart %}

_Onderstaand stukje kan ook haast als intro gebruikt worden_
In "Practices in Commercial Projects Using GitHub" by Kalliamvakou et al. the reasons to use GitHub, a populer online Git hosting service, where investigated. Their results yield interesting insights into techniques that can be utilized to enhance the Feedbackfruits platform {{"Kalliamvakou:2015:OSC" | cite}}. The most important findings by Kalliamvakou are: 
- Working together through independent work 
> "Commercial projects on GitHub use a workflow that builds on branching and pull requests to drive independent work."

- Reduced communication and coordination needs
> "Commercial projects use GitHub’s transparency as OSS projects do; their communication is code-centric and pull requests act as a coordination mechanism."

- A touch of self-organization 
> "Commercial projects use self-organization when assigning tasks and resolving conflicts."

- Challenges in collaborating with non-technical members
> "Commercial projects resort to using external tools when collaborating with non-technical members operating outside GitHub."


### Issue tracking
The quote "Software does not allow itself to be finished. Software is never finished" by Paul LeBlanc {{"leblanc1993writing" | cite}} shows the need for good issue tracking. There is an enormous list of issue-tracking solutions available {{"multiple2016issuetracking" | cite}}.

### Testing
The citation from Everett (2007) signifies the need for software testing. An estimated amount of $59.5B has been lost due to poor quality software in the period 2000-2007. With proper testing this amount could have been drastically lower {{"everett2007software" | cite}}. With the software industry being booming, this number will also increase {{"Mohammadoulah2014booming" | cite}}. 

### Package management
Package management 

### Scrum
In regular software

### Other techniques


[^linuxrepo]: https://github.com/torvalds/linux
[^apacherepo]: http://subversion.apache.org/
[^mozillarepo]: https://hg.mozilla.org/
[^slackwebsite]: https://slack.com/