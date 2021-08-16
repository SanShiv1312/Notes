# UNIT-1  ✨ SOFTWARE PROCESS AND PROJECT MANAGEMENT ✨
**CONTENTS** : S/W engineering paradigm –Life cycle models – Water fall –
Incremental – Spiral – Evolutionary – Prototyping – Object oriented – System
engineering – Computer based system – Verification – Validation – Life cycle process –
Development process – System engineering hierarchy – Introduction to CMM – Levels
of CMM

#### SOFTWARE PARADIGM
_Software paradigm_ refers to the methods and steps , which are to be taken while designing the software
 It basically consists of three parts.
- Software development paradigm
- Software design paradigm
- Programming paradigm

#### Software development paradigm
_Software development paradigm_ which is also known as `software engineering` is related to all the engineering concepts which
includes Requirements, software design, programming, etc.

#### Software design paradigm
_Software design paradigm_ is a part of software development and it includes design,
programming and  maintenance

#### Programming paradigm
_Programming paradigm_ is a way to classify programming language based on their application and features offered by it.
It in fact concerns about the programming aspect of software development. This includes coding, testing, integration.

### Need for Software Engineering 👀
- Specific software is needed almost everywhere in our life
- To be able to construct trust-worthy and reliable systems efficiently and effectively in less time
- Software engineering fulfills the higher rate of change in user requirement and environment

### Qualities of a good software 🙌
- `Correctness`:
Correctness is important for good software. There shouldn’t be faults with specification, design or implementation.

- `Usability` :
Users should be able to learn and use a system easily.

- `Efficiency` :
The less resource a piece of software uses, the better. Processor, memory and disk space usage should be minimized.

- `Reliability` :
A system that can perform the required functions stably is important. Failures should be as rare as possible.

- `Integrity` :
Security should be taken into account. Our software should let attackers access unauthorized resources.
Also, data validation is important so that bad data can’t be saved into the system.

- `Adaptability` :
A system that can be used without modification for different situations it’s good.

- `Accuracy` :
The accuracy of its outputs is good. This measures if the software outputs the right results for users.

- `Robustness` :
If a system is still working after getting invalid inputs and stressful environmental conditions, then it’s good for our system.

- `Maintainability` :
The ease in which an existing system can be changed is important. The easier that we can make changes, the better.

- `Portability` :
A system that operates in different environments from which it’s originally designed makes it good.

- `Reusability` :
The more reusable parts that a piece of software has, the better.
Using reusable parts means that we don’t have to reuse them from scratch.

- `Readability` :
Easy to read code is easy to change code. If we understand them faster, then we can make changes faster and in a less error-prone way.

- `Testability` :
Making our software system testable is critical. If our code is easy to write unit tests for, then that’s good.

- `Understandability` :
The ability for us to understand our system in a global view or at the detailed code level is important.
Easier to understand systems are more coherent.
With good software, it’s harder for us to create defects, and it’s faster to make changes.

##### Further classification of Qualities
The software product can be judged by what it offer and how well it can be used .
furthermore, the software must satisfied on the following grounds :
- _Operational_
- _Transitional_
- _Maintenance_

- a) `Operational`
Operational defines how well the software works in operations. It can be measure
on budget, usability, efficiency, correctness, functionality, dependability, security, safety.

- b) `Transitional`
This aspect is important if the software is moved from one platform to another.
The key parameters that includes portability, Interoperability, Reusability, Adaptability.

- c) `Maintenance`
Maintenance of the software defines the capabilities to maintain itself in the ever
changing environment. It includes modularity, maintainability, flexibility etc.

### What does the term `'SOFTWARE'` mean !? 🤔
Here's a set of definitions collected from various sources 😉
- **Software** is considered as a _set of programs_, which is designed to perform a well-defined function
-  set of instructions which when executed gives a desired output or function
-  Software is considered to be collection of _executable programming code_, associated libraries and documentations

### Software Engineering 🤞
-  Software engineering is the establishment and use of sound engineering
principles in order to obtain economically software that is reliable and works
efficiently on real machines
- Software Engineering is the application of a systematic, disciplined, quantifiable
approach to the development, operation, and maintenance of software; that is,
the application of engineering to software.
- Software engineering is a discipline whose aim is the production of fault-free
software, delivered on time and within budget, that satisfies the client’s needs.

####  Layered technology
- Software engineering is a fully layered technology.
- To develop a software, we need to go from one layer to another.
- All these layers are related to each other and each layer demands the fulfillment of the previous layer.

-   `  QUALITY_FOCUS -- PROCESS -- METHODS -- TOOLS `

### LIFE-CYCLE MODELS  
Software Development Life Cycle (SDLC) is a process used by the software industry to design, develop and test high quality softwares. The SDLC aims to produce a high-quality software that meets or exceeds customer expectations, reaches completion within times and cost estimates.
- It consists of a detailed plan describing how to develop, maintain, replace and alter or
enhance specific software
- Life cycles defines a methodology for the betterment of the quality of a software and the overall development processes

#### Process framework: activities
The followings are the key activities of process models:
-  `Communication`: communication and collaboration between developer and
customer or stakeholder.
-  `Planning`: technical task to be conducted, risk analysis, resources required, work
schedule.
-  `Modeling` : creation of model for better understanding
-  `Construction` : combination of code generation and testing.
   Deployment software is delivered to customers and getting feedback

### `WATERFALL-MODEL`
The Waterfall Model was the _first Process Model_ to be introduced. It is also referred to as a _linear-sequential life cycle model_. It is very simple to understand and use and is popularly known as **Traditional System analysis or SDLC**  
#### `Main Objectives` :
- This model suggests a sequential and systematic approach of Software development that begins at the system level and progresses through analysis, design, coding, testing, and support.
- `  COMMUNICATION -> PLANNING -> MODELING -> CONSTRUCTION -> DEPLOYMENT  `
- Any phase in the development process begins only if the previous phase is complete.
- In this waterfall model, the phases do not overlap
- In clear terms , we can state the traditional SDLC's methodology as `the outcome of one phase acts as the input for the next phase sequentially`.
- All the phases are cascaded to each other in which progress is seen as flowing steadily downwards _(like a waterfall)_ through the phases

##### Applications of Waterfall-Model
Every software that is to developed will be different and requires a suitable SDLC approach considering internal and external factors
Appropriate situations where we can use rainfall model are :
- Requirements are `very well documented`, clear and fixed.
- Product definition is `stable`
- Technology is understood and is `not dynamic`
- There are `no ambiguous` requirements
- Ample resources with required expertise are available to support the product
- The project is `short`

##### Advantages of Waterfall-Model
Development moves from concept, through design, implementation, testing, installation, troubleshooting, and ends up at operation and maintenance. Each phase of development proceeds in strict order which is very transparent to have.
- `Easy to understand` and implement.
- Widely used and known
- Reinforces good habits: define-before- design, design-before-code
- Identifies deliverables and milestones
- Document driven
- `Maintenance` is easier
- `Clearly defined stages` of development

##### Disadvantages of Waterfall-Model
 Waterfall development does not allow much reflection or revision. Once an application is in the testing stage, it is very difficult to go back and change something that was not well-documented or thought upon in the concept stage.
- No working software is produced until late during the life cycle.
- `High amounts of risk` and uncertainty.
- Not a good model for `complex` and `object-oriented projects`.
- `Poor model for long` and ongoing projects.
- Not suitable for the projects where `requirements are at a moderate to high`
  risk of changing.
- Delivered product may not meet client needs
- Difficult to `measure the progress` within the stages of development
- Cannot accommodates to `changing requirements`

### `INCREMENTAL-MODEL`
- Incremental Model is a process of software development where requirements divided into multiple standalone modules of the software development cycle.
- Software is constructed step by step, just like a building Construction.
- This model will just combines the elements of waterfall model and then applied iteratively in each increment

#### The various phases of incremental model are as follows :

1. `Requirement analysis` : In the first phase of the incremental model, the product analysis expertise identifies the requirements. And the system functional requirements are understood by the requirement analysis team. To develop the software under the incremental model, this phase performs a crucial role.

2. `Design & Development` : In this phase of the Incremental model of SDLC, the design of the system functionality and the development method are finished with success. When software develops new practicality, the incremental model uses style and development phase.

3. `Testing` : In the incremental model, the testing phase checks the performance of each existing function as well as additional functionality. In the testing phase, the various methods are used to test the behavior of each task.

4. `Implementation` : Implementation phase enables the coding phase of the development system. It involves the final coding that design in the designing and development phase and tests the functionality in the testing phase. After completion of this phase, the number of the product working is enhanced and upgraded up to the final system product

#### When to use the **`Incremental`** Model ?
- When the `requirements are superior`.
- A project has a `lengthy development schedule`.
- When Software team are `not very well skilled or trained`.
- When the customer `demands a quick release` of the product.
- You can develop `prioritized requirements` first.

#### Advantage of Incremental Model
- Errors are easy to be recognized.
- Easier to test and debug
- More `flexible`.
- Simple to manage risk because it handled during its iteration.
- The Client gets important `functionality early`.
- With each release a new feature is added to the product.
- Customer can `respond to feature` and `review the product`.
- Risk of changing requirement is reduced
- Work `load is less`

#### Disadvantage of Incremental Model
- Need for `good planning`
- Total `Cost is higher` than the waterfall model
- `Well defined` module interfaces are needed.
- Mostly such model is used in `web applications and product` based companies


### `SPIRAL-MODEL`
- The spiral model combines the idea of iterative development with the systematic, controlled aspects of the waterfall model.
- This Spiral model is a combination of iterative development process model and sequential linear development model
- Like waterfall model with a very high emphasis on risk analysis.
- It allows incremental releases of the product or incremental refinement through each iteration around the spiral.
- Attempts are made to mitigate every potential risk, in some cases by building a prototype.  

#### Phases of Spiral model
- `Identification` :
 This phase starts with gathering the business requirements in the baseline spiral. In the subsequent spirals as the product matures, identification of system requirements, subsystem requirements and unit requirements are all done in this phase.

     This phase also includes understanding the system requirements by continuous communication between the customer and the system analyst. At the end of the spiral, the product is deployed in the identified market.

- `Design` :
The Design phase starts with the conceptual design in the baseline spiral and involves architectural design, logical design of modules, physical product design and the final design in the subsequent spirals.

- `Construct or Build` :
The Construct phase refers to production of the actual software product at every spiral. In the baseline spiral, when the product is just thought of and the design is being developed a POC (Proof of Concept) is developed in this phase to get customer feedback.

     Then in the subsequent spirals with higher clarity on requirements and design details a working model of the software called build is produced with a version number. These builds are sent to the customer for feedback.

- `Evaluation and Risk Analysis` :
Risk Analysis includes identifying, estimating and monitoring the technical feasibility and management risks, such as schedule slippage and cost overrun. After testing the build, at the end of first iteration, the customer evaluates the software and provides feedback.

#### Advantages of Spiral model :
- High amount of risk analysis hence, avoidance of Risk is enhanced.
- Risk handling is major advantage where risk handling and analysis is possible at any phase of the development.
- Good for large and mission-critical projects.
- Strong approval and documentation control.
- Additional Functionality can be added at a later date.
- Software is produced early in the software life cycle.
- Project estimates in terms of schedule, cost etc. become more and more realistic as the project moves forward and loops in spiral get completed.
- It is suitable for high risk projects, where business needs may be unstable.
- A highly customized product can be developed using this.
- Even good for satisfying customer the most  
#### Disadvantages of Spiral model :
- Can be a costly model to use.
- Risk analysis requires highly specific expertise.
- Project’s success is highly dependent on the risk analysis phase.
- Doesn’t work well for smaller projects.
- It is not suitable for low risk projects.
- May be hard to define objective, verifiable milestones.
- Spiral may continue indefinitely.
- End of the project may not be known early.
- Time management and estimation is a little hard thing
