# Recommendations
No existing solutions were found that solve the specific problem posed in the problem description. However both Wikipedia and GitHub contain various aspects that can be used in a possible solution. Wikipedia is one of the few community based platforms that really is a sustained success. One of the reasons is that Wikipedia consists of three main groups: donators, contributors and moderators [^wikiuserroles]. A shared factor between Wikipedia and GitHub is that subjects can be decomposed in multiple smaller parts. This modularity is something that repeatedly occurs in the previous parts of the research report and thus is likely to be essential for a successful community based platform. For software development GitHub is one of the best and most used tools. The challenge is to extend its philosophies to non-software development.

Based on these success stories and conclusions, a description is given of what an ideal solution looks like. This solution is presented in the form of a platform.

## The ideal platform
The platform converts resources, mainly in the form of time and knowledge, into an extension to the current FeedbackFruits platform. The goal of this extension should be to fulfill a particular need. A goal can be identified as the answer to finishing the phrase: "With FeedbackFruits I would like to ..". Each goal can be divided in challenges, sub-goals that need to be met in order to meet the goal. If these challenges are to large to be solved by one or two pioneers, then the challenges must be divided into sub-challenges in such a way that they can be solved by one or two pioneers. This implies that the whole project can be solved by lots of different people by tackling smaller problems at the same time.

### Use cases
Bob is a teacher, he would like to be able to ask question via the FeedbackFruits-platform. However, this functionality does not exist yet. Luckily for Bob he can request this functionality using the Bepstore. When he visits the bepstore, he sees a button 'create new goal' and clicks it. Bob is then able to fill in the title and description of his request. Afterwards he gets the possibility to share is newly made goal on twitter, facebook and feedbackfruits.  

Esther is a computer science student but is a bit bored and is browsing facebook. She runs into a post by teacher Bob whose course she followed last year. She sees he would like to ask questions on the FeedbackFruits-platform and thinks this is a good idea. She has got some idea about this feature and joins the core team of goal. Then she starts to break down the initial goal into smaller subgoals: multiple choice and open questions. Esther submits these proposals to the platform for review and already starts setting up the development toolset.

Peter is a designer and already actively contributes in the bepstore. In the 'new goals' section he sees that a design for multiple choice and open questions is desired. Peter joins the project and indicates he would like to be responsible for this. After an hour he has finished the initial designs and uploads them to the platform. The platform automatically shares his designs on 'myawesomedesigns.com'. A very experienced designer sees Peters design and comments on it.

After a while Bob checks on his goal and sees that a core team has formed and the initial idea has been broken down into smaller goals. Additionally, designs have been drafted. Bob has some ideas about these designs and comments on them. Esther gets a notification that some designs are ready for implementation and starts to develop them. When she is done, the core team gets a test report. Bob is happy and gives an update to everyone involved.

## Resources
The platform facilitates a structured process to reach a goal. On a high level, this process consists of two parts: the gathering and spending of resources. The most important resources are time and knowledge. Less important resources can include money, servers and licensed materials. Resources can be gathered by creating a hype around the goal. Once enough resources have been acquired a team of pioneers can start implementing an extenions to achieve the goal. This will result in resources being spent.

## Pioneers
Pioneers can be identified according to the resources they contribute. Pioneers can fall into one of three categories:
- Core team (time and knowledge)
- Contributors (knowledge)
- Backers (other resources)

The core team are a select group of pioneers that take the responsibility for a project. Dividing the goal into challenges and sub-challenges is the job of the core members, as such they will provide the structure for the software development process. Contributors can pick up one or multiple of these sub-challenges and implement the goal of those sub-challenges. Reviewing code or designs also is a contribution to a sub-challenge. Backers are pioneers that try to improve the project without implementing or reviewing solutions for a (sub-)challlenge. This can be done with money, teaching material e.g.

## The process
There are four main factors that are essential for the development of an extension: hype, requirements, code and updates. These factors correspond to different types communication between different categories of pioneers. For the development process to be clear, an iterative approach must be used. Each iterative step can be linked to a essential factor of the development. First hype must be created in order to gather necessary resources. When all the necessary resources are gathered, the requirements of the project can be created based on the goal. Code can be created based on the final requirements. The creation of code must also be done in iterations to ensure progres and code quality, where each iteration ends with an update to the contributors and the community.

### Hype
Hype is created by promoting the project, either on social media or other means. Anyone, pioneer or not, can create hype for a project. Creating more hype not only stimulates backers to support the project but also motivates contributors. This effectively generates resources that can be consumed in the other parts of the process.

### Requirements
Requirements are needed to structure how resources will be consumed in order to produce code. Good requirements are fundamental to a successful process, so the specification falls on the core team. The requirements need to be formulated clearly and dependencies between requirements need to be identified early on, resulting in communication dictating this part of the process.

### Code
Code is produced by the core team and the contributors as a means of achieving the goal. The requirements should be reflected in the code produced by both the core team and the contributors. For this reason, the means of communicating about the code should facilitate referencing the relevant requirements as well.

### Process update
One of the most important factors in maintaining a successful community is the ability to keep everyone engaged with the common goal. To achieve this, everyone in the community should be kept up-to-date on the current state of the project, as well as future plans. In addition to keeping the community engaged, this part of the process also bridges the current iteration with the next iteration. It ends the current iteration with a summary of the results, and provides an opportunity for hype to be created around the next iteration.

## Integrations
Many of the suggested features already exist as separate tools. If such tools have an API, they could be neatly integrated into the proposed platform which prevents reinventing the wheel. For example GitHub has an extensive API with, among others, support for the creation of teams, pull-request and issues. Other integrations that can be explored are:
- crowdsourcing platforms (eg. Kickstarter, tilt.com, WePay, monster.com, pinterest and gratipay);
- integration testing (eg. Jenkins and Travis-CI);
- chat tools (eg. gitter, slack).

## MVP/EVP
An initial list of requirements can be found below. This list is not exhaustive but should rather be seen as an itererative list. Positive and negative signs (++/+/-/--) correspond with the importance of the feature. The importances can be must have, should have, could have, won't have, which is according the MoSCoW model.

### ToDo
As a user of the platform I would like to:

#### General improvements
- [+] have a general information page (v0.6)
	- [-] get tips on how to use the platform (v0.6)
- [+] goal tags (v0.5)
- [+] search/browse for goals (v0.5)
- [+] see my contributions (v0.6)

#### User engagement
- [++] communicate with other pioneers (v0.5)
	- [+] use different tools per category (v0.5)
	- [+] get updates (push, email, etc.) (v0.5)
- [+] create an account more easily (v0.6)
- [+] hype my goal (v0.5)
- [+] share my goal on social media (v0.5)
- [-] edit a user (v0.4)

#### Requirements engineering
- [++] prioritize sub-challenges (v0.4)
- [++] get additional information about the status of my goal, such as:
	- [++] quality (v0.6)
	- [+] functionality (v0.6)

#### Quality control
- [++] give feedback on someone else's work (v0.5)
- [++] get feedback on my work (v0.5)
	- [++] via peer review (v0.5)
	- [+] via automated testing (v0.5)

#### New
- [+] automatic repository generation (v0.6)
	- [+] boilerplate (v0.6)
	- [+] teams (v0.6)
	- [+] status checks (v0.6)
	- [+] milestones (v0.6)
	- [+] issues (v0.6)

#### Out of Scope
- [-] follow a tutorial on how to use the platform
	- [--] per user type
- [-] be able to join a project as a backer
- [-] view someone's reputation
- [-] get reputation
	- [--] have a ranking system
- [-] have some sort of gamification
- [-] bounty
- [-] available resources
- [-] hype factor
- [--] join a training party
- [--] be matched with an apprentice
- [--] be matched with a senior

### Done
- [++] see a landing page
- [++] create an account
- [++] be able to join a project
	- [+] as a contributor
	- [++] as a core team member
- [++] create a goal
	- [+] set estimated necessary resources (actual results from problem decomposition)
- [+] edit a goal
- [++] view a list of goals
	- [-] view a list of trending goals
	- [+] view a list of newest goals
- [++] see a goal description
- [++] see a list of sub-challenges for a goal
- [++] use GitHub integrated
- [++] be able to decompose a goal into challenges in a structured way as specified in Requirements for Requirements Management Tools (Hoffmann, Matthias et al., 2004)
- [++] get information about the status of my goal, such as:
	- [++] progress
	- [++] milestones
	- [+] timeline
[^wikiuserroles]: https://en.wikipedia.org/wiki/Wikipedia:User_access_levels
