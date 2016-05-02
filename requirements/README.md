
# Requirements Engineering
The field of requirements engineering is a part of systems and software engineering, and deals with structuring requirements. Requirements are useful in measuring to what degree software solves the problems it was built to solve. Requirements engineering can be viewed in terms of two groups of activities, corresponding with the iterative and incremental nature of the process: requirements development and requirement management {{"pandey2010effective" | cite}}. To consider these activities, first a definition of a software requirement has to be established. Finally, a model for structuring the process of requirements engineering is considered.

## The definition of a software requirement
In the "Guide to the Software Engineering Body of Knowledge" (SWEBOK) the IEEE[^ieee] defines a software requirement as: 'a property that must be exhibited by something in order to solve some problem in the real world' {{"swebok14" | cite}}. Requirements can be imposed on the product as well as the process. An essential property of software requirements is that they are verifiable, either as an individual feature (functional requirement) or at the system level (non-functional requirement). In addition to this behavioral properties, requirements may have attributes such as a priority rating and a progression status.

## Requirements development

Discovering, analyzing, documenting and validating requirements are all part of the process of requirements development {{"pandey2010effective" | cite}}. This process is essential to defining a software architecture that works the way the end user expects it to work. This part of the requirements engineering process takes place before a software implementation is developed. The goal is to end up with a specification of the requirements the software has to adhere to.

One of the main challenges in requirements development in large systems is coordination {{"crowston1998coordination" | cite}}, specifically coordinating dependencies. Dependencies may arise between requirements, resources and software that consumes these resources. To manage this coordination mechanisms are needed, such as standardization, problem decomposition or (third-party) expert counsel. Early dependency detection and analysis is key to determining which coordination mechanism to apply.

## Requirements management

Throughout the software development process a requirement may change. This change may affect other parts of the system and in turn affect other requirements as well. Requirements management consists of activities related to managing these changes and tracing them to the corresponding parts of the system {{"pandey2010effective" | cite}}.
The goals of the this part of the process are {{"hoffmann2004requirements" | cite}}:

- supporting acquisition, specification, grouping and attribution of the raw captured requirements
- supporting their derivation to more detailed levels, keeping and adjusting attributes
- enabling test cases and test environments to be defined and linked
- enabling relationships between requirements, design, realization and test to be tracked and traced
- enable distributed development within the organization

Requirements management facilitates an iterative requirements engineering process {{"pandey2010effective" | cite}}. In "Requirements for Requirements Management Tools", Hoffmann, Kühn, Weber, & Bittner {{"hoffmann2004requirements" | cite}} provide a requirements specification for any tool that attempts requirements management for large scale projects.

## The Twin peaks model

In order to ensure a software implementation adheres to its requirements and keeps doing so, an iterative workflow is required. An example of an iterative model is the Twin Peaks model. Requirements and an architectural specification are developed concurrently, while continually separating problem structure and specification from those of the solution {{"nuseibeh2001weaving" | cite}}. Combining this approach with problem frames {{"hall2002relating" | cite}} allows for a structural decomposition of problems into smaller problems that can be solved with a modular solution. The final workflow looks like this {{"nuseibeh2001weaving" | cite}}:

![Workflow](../images/workflow.png)

[^ieee]: http://www.ieee.org/
