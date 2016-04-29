
# Existing Communities

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

# Communities
A community is, according to the Oxford Dictionary,  *a group of people living in the same place or having a particular characteristic in common*{{"ComDef" | cite}}. In traditional research, the study focuses on localy bound communities like neighbourhoods and villages, because they have clear boundaries of who is involved in the community{{"meijering2007constructing" | cite}}{{"meijering2007intentional" | cite}}.  
With the introduction of modern media, like games, social media and messenger-applications, communities are not bound anymore by location and the characteristic becomes the central point of the community. A concequence of this is that boundaries of the community are less clear. Therefore, one of the challenges of doing research on these virtual communities is determining who is and who is not part of a community{{"sundaram2012understanding" | cite}}.  
Virtual communities have four necessary characteristics: interactivity, communicators, a publicly shared mediated (virtual) communication place and a minimum level of sustained membership{{"jones1997virtual" | cite}}. This means that in a virtual community, there must be a longlasting, self-sustaining communication *(interactivity)* about subjects (related to the relating characteristics) by two or more persons *(communicators)* over one ore more platforms like a website or a chat-group *(communication place)* where there is a certain amount of active members *(sustained membership)*.
## Existing Communities
Before we can compare different communities and their structure, we first need to define a few (types of) communities. We will look at two types of real-life communities and two types of virtual communities, such that we can discuss their similarities and differences.
### Ecosystems
An ecosystem can be seen as a natural form of a community. It is bound to a location where a diversity of animals and species interact with eachother{{"EcosysDef" | cite}}. Although there is no real communication, the combination of individual self-interest (the survival of their offspring or themself) creates a network of dependencies and interactions that one can interpret as a community.  
A key factor of an ecosystem is stability. In a stable ecosystem{{"EcosysSDef" | cite}}, each species acts in such a way that they directly enable or inderectly do not interfere with the survival of another species. . An ecosystem will remain stable as long as the system is able to deal with outside disturbances.

### Intentional Communities
Intentional communities are man-made communities, where its members attempt to realise a common alternative way of life outside of mainstream society{{"meijering2007intentional" | cite}}. Although there is no one list of criteria to characterise them, the most cited criteria are:

1. No bonds by familial relationships only.
2. A minimum of three to five adult members.
3. Members join voluntarily
4. Geographical and psychological separation from mainstream society.
5. A common ideology that is adhered to by all members.
6. Sharing of (a part of) one's property.
7. The interest of the group prevails over individual interests.

Not all intentional communities fulfill all of these criteria but they give a good idea of what is and what is not a intentional community. Intentional communities can be quite diverse. To get a better understanding of the different ways an intentional community can work, they can be split into four groups: ecological, communal, religious and practical communities{{"meijering2007intentional" | cite}}.

**Ecological Communities**  
Ecological communities are communities that withdraw to remote locations in an effort to live according to their own ideals. They actively separate themself from society and aim to be self-sufficient. The separation is what identifies this type of intentional communities{{"meijering2007constructing" | cite}}{{"meijering2007intentional" | cite}}.  
Ecological communities can manifest themself on different scales. It can vary from a group living together in a house (cohousing) to a whole village (ecovillages){{"sanguinetti2012design" | cite}}, but all have a support-structure and cooperate to achieve the ideals of the community{"svensson2002ecovillage" | cite}.

**Communal Communities**  
Communal communities center their ideals around the contact between communities members{{"meijering2007intentional" | cite}}. This means that the platform (chat-groups, website, etc.) or place (offices, pub, etc.) plays a central key in this type of community. The place or subject of the platform focuses on the particular characteristic that the members have in common, like a cooking-forum for people who like cooking or a chat-group for parents whos kids are in the same class.

**Religious Communities**  
Religious communities have their ideals centered around a belief or religion. If you look at these communities based on the religions, then there is no boundry to the location of the community. However, there are religious communities that also behave like a communal community, like local church-communities. The ideals of the religion are the ideals of the community.

**Practical Communities**  
Practical communities are special because they don't center around ideals at all. Practical communities arise out of pure convenience, when people are better of sharing information or resources (on a regulare basis). This can be a community of farmers sharing farming equipment, or students sharing a house.

### MMO-RPG Communities
Massive Multiplayer Online Role-Playing Games are, like the name describes, online games where the player explores a virtual world as one of many type of characters and can interact with an enormous amount of other players. Popular MMO-RPG's often have two types of communites: communities outside of the game (fans and forums) and communities inside of the game (parties and guilds). For this research, we will be looking at the communities inside the game, because the dynamics of these communities often require active participation.  
Most MMO-RPG's have two in-game systems that can be seen as communities: parties and guilds. A party is a small group of players that train or do quests (in-game missions) together for a short period of time (possibly one game session). The benefit of forming a party is experience-sharing (to some degree) and players can kill high-level in-game creatures they could kill on their own. If a party is formed for the purpose of doing a quest, the composition of the party (the distribution of roles or functions) may be addapted towards the goal of the quest to ensure optimal performance{{"chen2009communication" | cite}}.  
A guild is a group of players forming a community, for creating a social connection or to make it easier to form a trust-worthy or well-composed party over a longer period of time (longer than one game session){{"rossi2008mmorpg" | cite}}{{"kelly2004play" | cite}}{{"verhagen2009demystifying" | cite}}. Within a guild, members can be classified based on connectivity, type of player, role within the guild and involvement{{"ang2010social" | cite}}.

### Software Communities
Software communities are groups of people involved in the development or improvement of a piece of software, but can also be focussed on a programing language (model). This makes software communities a broad term. For this research, we will be looking at Software Development Communities,  communities centered around software development/improvement, and we won't be looking at Software Engineering Communities,  communities centered around programing language (models), because the first community is our target group.   

A software development communities can be devided into two groups: developers and users. Developers create software, wich is used by the users. The users are able to give feedback about the software, wich the developers can use in the next version of that piece of software.
Users sometimes discuss the (lack of a certain) functionality in a software program on dedicated forums. This creates a feedback loop for the programmers. A smaller feedback loop is the bug-reporter. Organisations, like Apache and Mozilla, often have a part of their software dedicated to enabling the users to submit bugs{{"mockus2002two" | cite}}. This enables the developers to fix problems with the software in a much faster way than searching for feedback.  
One special community is the Opens Source Software community. Open Source means that the source-code of the software program is publicly available on the internet and that everyone can download and use the software for free{{"osterloh2007open" | cite}}. Because the code is publicly available, it enables users who understand the code to look in the code for the source of bugs and failures and give feedback related to a piece of the code. It also enables other programmers to expand the program based on it's source code.
