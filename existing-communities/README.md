# Existing Communities

## What techniques are currently used to involve a community with software development?
There are many projects that are build with the help of an online community. The largest projects include the development of the Linux kernel[^linuxrepo], the Apache project[^apacherepo] and the Mozilla browser[^mozillarepo]. To include the online communities during the development of such online software it is necessary to keep everyone up to date and informed about the current state of the project. In short, the means needed can be divided into five categories: communication, version control, issue tracking, testing and package management {{citation?}}. For each of these categories will be invested what techniques are currently used by software development projects.

### Communication
Communication is perhaps the most important factor when it comes to collaborative software development. Much communication is traditionally done via e-mail, instant messaging, phone, web meetings and groupware {{"thissen2007communication" | cite}}. However as of late new, more enhanced tools like Slack[^slackwebsite] have emerged. With for example Slack it is possible to integrate updates from other development tools such as GitHub and make the visible to the whole team.

### Version control
Many software project makes use of software versioning. According to the annual Eclipse Community service this percentage totals to almost eighty percent (Git 43.9%, Subversion 30.7%, Other 5.8%) in 2014 {{"eclipse2014survey" | cite}}. From the statistics in the figure below can be concluded that the Git has become the most popular version control method. Git offers some tools that are not present with the previous most popular tool Subversion.

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

#### Possibilities of Git
Pull-requests are a pre and issue-trackers such as the implementation by GitHub can be very helpfull (see Linux project).

### Issue tracking
"Software does not allow itself to be finished. Software is never finished" {{"leblanc1993writing" | cite}}.

### Testing
"Software Testing: Testing Across the Entire Lifecycle provides the fundamental concepts and approaches to software testing. The topic is important for two reasons. First, according to US Government surveys there has been an estimated $59.5B in business losses since 2000 due to poor quality software. Second, based on the authors’ inability to find experienced software testers to address some of the estimated $22.2B testing opportunity, the current pool of experienced software testers is already gainfully employed" {{"everett2007software" | cite}}

### Package management
Package management 


### Other
Techniques used:
1. Versioncontrol (Git, SVN, Mercurial)
2. Pull-requests
3. Issue tracker
4. Slack
5. Scrum

### Git, Pull-requests and issue-tracker


### Scrum
In regular software

### Other techniques

#### Slack and equivalents

[^linuxrepo]: https://github.com/torvalds/linux
[^apacherepo]: http://subversion.apache.org/
[^mozillarepo]: https://hg.mozilla.org/
[^slackwebsite]: https://slack.com/