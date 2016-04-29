## What techniques are currently used to involve a community with software development?
There are many projects that are built with the help of an online community. The largest projects include the development of the Linux kernel[^linuxrepo], the Apache project[^apacherepo] and the Mozilla browser[^mozillarepo]. To include the online communities during the development of such online software it is necessary to keep everyone up to date and informed about the current state of the project. In short, the means needed can be divided into five categories: communication, version control, issue tracking, testing and package management `reference needed. orginal source: https://en.wikipedia.org/wiki/Open-source_software_development`. The techniques that are currently being used are specified below for each category. In "Practices in Commercial Projects Using GitHub" by Kalliamvakou et al. the reasons to use GitHub, a popular online Git hosting service, were investigated. Their results yield interesting insights into techniques that can be utilized to enhance the Feedbackfruits platform {{"Kalliamvakou:2015:OSC" | cite}}.

### Communication
Communication is perhaps the most important factor when it comes to collaborative software development. Much communication is traditionally done via e-mail, instant messaging, phone, web meetings and groupware {{"thissen2007communication" | cite}}. However as of late new, more enhanced tools like Slack[^slackwebsite] have emerged. With such new tools, it is possible to integrate updates from other development tools such as GitHub and make the visible to the whole team. A conclusion drawn by Kalliamvakou is that the use of GitHub and its tools reduce the need for communication and coordination needs. However challenges remain in collaborating with non-technical persons because commercial projects still resort to external tools outside GitHub {{"Kalliamvakou:2015:OSC" | cite}}.

### Version control
Many software projects makes use of version control. According to the annual Eclipse Community service this percentage totals to almost eighty percent (Git 43.9%, Subversion 30.7%, Other 5.8%) in 2014 {{"eclipse2014survey" | cite}}. From the statistics in the figure below it can be concluded that the Git has become the most popular version control method. The main reasons for the growing popularity of Git are its feature set and the usage in large projects such as the aformentioned Linux project {{"stephen2015git" | cite}}. Two of the most important features of Git are branching and pull-requests stimulate working together trough independent work {{"Kalliamvakou:2015:OSC" | cite}}.

{% chart format="yaml" %}
padding:
    top: 40
    right: 40
    left: 40
data:
    type: line
    x: "year"
    columns:
        - [year, 2011, 2012, 2013, 2014]
        - [Git, 12.8, 32, 36.3, 43.9]
        - [Subversion, 51.3, 46, 37.8, 30.7]
        - [Mercurial & CVS, 17.9, 11.5, 8.1, 5.8]
title:
    text: "Version control popularity by type"
{% endchart %}

### Issue tracking
The quote "Software does not allow itself to be finished. Software is never finished" by Paul LeBlanc {{"leblanc1993writing" | cite}} shows the need for good issue tracking. There is an enormous list of issue-tracking solutions available {{"multiple2016issuetracking" | cite}}, each with their own strengths and weaknesses. Interviews conducted by Kalliamvakou show that for example the combination of the GitHub issue-tracker enhances self-organization when assiging tasks and resolving conflicts {{"Kalliamvakou:2015:OSC" | cite}}. However the GitHub solution is not optimal because the issue tracker lacks some critcial features such as severity, components and bug report templates {{"Zhou:2015:CAB:2745802.2745808" |  cite}}.

### Testing
The citation from Everett (2007) signifies the need for software testing. An estimated amount of $59.5B has been lost due to poor quality software in the period 2000-2007. With proper testing this amount could have been drastically lower {{"everett2007software" | cite}}. With the software industry being booming, the need for testing will also increase {{"Mohammadoulah2014booming" | cite}}. While testing will not immediately cause users to be involved in the software development proces, it may attract users because they like working on high quality software.

### Package management
Just as testing, package management might not be a primary driver for developers to start working on a project. In the article "Achieving quality in open-source software" by Aberdour (2007), the author identifies several key factors for participation and motivation in open-source software projects. These include code modularity and opportunities to learn new tools {{"aberdour2007achieving" | cite}}. When a project uses package management such new tools are quickly identified. Furthermore the presence of package management mostly indicates modular software.

[^linuxrepo]: https://github.com/torvalds/linux
[^apacherepo]: http://subversion.apache.org/
[^mozillarepo]: https://hg.mozilla.org/
[^slackwebsite]: https://slack.com/