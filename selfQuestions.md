# Instructions

Follow the following syntax to add more questions

Use the header notations for topics and sub topics.

Mark your commits with the various topics that you added. If you added to Revision Control, mark it as "RCS - [optional information]". If more than 1 topic, just list the topics, like "RCS, Unit Testing, IDEs".

Good luck! <3

<details> 
  <summary>Q1: Questions go here! </summary>
   A1: Answers go here
</details>
<details>
  <summary>Q2: Questions go here! </summary>
   A2: Answers go here
</details>

<!-- template -->
<details> 
  <summary></summary>
  A: 

  * Explain [optional]
</details>
<!-- template -->

## Revision Control

<details> 
  <summary> What is Revision Control? </summary>
   A: RC is the process of managing multiple version of information
</details>

<details> 
  <summary> What does a commit save?</summary>
  A: Committing saves a SNAPSHOT of the tracked files. Stage the changes -> commit the changes.
</details>


<details> 
  <summary> What can RC help you with?</summary>
  A: Collaboration, recovering from mistakes, manage drift between multiple versions of project, detect incompatible changes to the same file.
</details>

<details> 
  <summary> Which RCS flow does not have branches?</summary>
  A: Centralised flow!

  * There is a distributed RCS and centralised RCS. Distributed has multiple remotes that PR each other.

  * Forking flow is what we did for CS2103, 1 main and everyone forks from there and PR back.

  * Feature Branch Flow is 1 Main, with multiple branches inside with a feature each, and merges back to Main.

  * Centralised Flow is this markdown form. Free For all.
</details>

## IDE


<details> 
  <summary>Debugging is the process of?</summary>
  A: Debugging is the process of discovering defects in the program.


  * 👎 By inserting temporary print statements

  * 👎 By manually tracing through the code

  * 👍 Using a debugger
  * Allows for step wise running of code in real time

</details>

## Testing

<details>
  <summary>How does the Singleton pattern affect the testability of a Java application? </summary>
  A: Singletons reduce testability due to these reasons: 
  
  * They create implicit dependencies that are hard to replace using dependency injection because Java doesn’t allow overriding of static members. 
  
  * Singleton object represents a global ‘state’. If the state of the Singleton affects the test case execution, then the Singleton object needs to be ‘reset’ at the beginning of each test case. 
  </details>


### Mock exam? Just try bah


#### Design

<details> 
  <summary> There are 2 aspects of design, internal and external design.</summary>
  A: True

  * External design, or product design, is to meet the users' requirements. Usually done by product designers

  * Internal, or implementation design, is implemented to meet the required external design/behaviour. Usually done by Software Engineers.
</details>

<details> 
  <summary> External design of the software is usually done by Software Engineers</summary>
  A: False

  * Usually done by product designers
</details>

<details> 
  <summary> A multi level design is used only for large and novel softwares</summary>
  A: False

  * Big enough softwares can use multi level design, such as Addressbook level 4
</details>


<details> 
  <summary> Abstraction is a technique used for dealing with complexicity</summary>
  A: True

  * Used to simplify design by supressing complexicity into lower levels
</details>

<details> 
  <summary> Highly coupled components is easier to integrate due to the high dependency between them</summary>
  A: False

  * Highly coupled components have to be integrated together and is harder to do so at the same time.
</details>


<details> 
  <summary> Strong coupling is discouraged due to the degree of complexicity in implementation</summary>
  A: False

  * Strong coupling does not mean highly complex. It is discouraged due to 
  ** higher maintenance, 
  ** harder integration with other components, and 
  ** harder to test and reuse.
</details>


<details> 
  <summary></summary>
  A: 

  * Explain [optional]
</details>

#### Testing

<details> 
  <summary> Testing how easy it is to use a software is a form of Integration Testing</summary>
  Answer: False

  * this is a form of System testing
</details>

<details> 
  <summary> When a developer tests a SUT, it is called Developer Testing</summary>
  Answer: True

  * this is to start testing as early as possible, before a full product is released.
</details>

<details> 
  <summary> Scripted testing is better than exploratory testing</summary>
  Answer: False

  * A mix of both is better than either.
</details>

<details> 
  <summary> A test driver is a person that tests the SUT for the purpose of testing</summary>
  Answer: False

  * A test driver is the code that ‘drives’ the SUT for the purpose of testing
</details>

<details> 
  <summary> A stub can be used to inject into an object for the purpose of testing in islation</summary>
  Answer: True

  * Dependency injection is the process of 'injecting' objects to replace current dependencies with a different object. This is often used to inject stubs to isolate the SUT from its dependencies so that it can be tested in isolation.
</details>

#### Refactoring


<details> 
  <summary> Refactoring CAN improve performance</summary>
  A: True

  * Simple code can run faster and more efficiently than complex code
</details>


<details> 
  <summary> Refactoring can help discover bugs</summary>
  A: True

  * hidden bugs are surfaced through simpler code
</details>


<details> 
  <summary> The opposite of Refactoring is Unfactoring</summary>
  A: False

  * The are opposite methods in Refactoring, but all forms of changes are called refactoring
</details>


<details> 
  <summary> There is always a reason to refactor the code for better readability</summary>
  A: False

  * Refactoring too much can occer.

  * This is when the benefits of refactoring do not justify the cost of it.
</details>


#### Documentation


<details> 
  <summary> Documentation is for developers to read and thus all documentation are similar</summary>
  A: False

  * The developer can either be a user or a maintainer

  * Developer as user, for example APIs, are easier to document

  * Developer as maintainer, for others to take over the project, is harder as complex internals need to be explained
</details>


<details> 
  <summary> A top-down approach for documentation is preffered as opposed to a bottom up approach</summary>
  A: True

  * Readers are presented with a top level documentation, before being drilled down to the details

  * Readers can read until the documentation is not revelant to them
</details>


<details> 
  <summary> Documentation must be accurate and complete</summary>
  A: False

  * It is not enough to be comprehensive, it must be comprehensible

  * Aim for comprehensibility
</details>


<details> 
  <summary> Minimal documentation is better than complete documentation</summary>
  A: True

  * Aim for JUST ENOUGH documentation, no need to document obvious items
</details>


#### Code Quality
<details> 
  <summary> Improving Code Quality can improve run-time efficiency</summary>
  A: True

  * It can improve efficiency by being simpler, improve security, and improve robustness

  * Improve understandbility
</details>

<details> 
  <summary> Variables can be reused within a function</summary>
  A: False

  * Don't recycle variables or parimeters to improve code quality
  * Minimise the scope of variables
</details>

<details> 
  <summary> Documentation is needed for all code</summary>
  Answer: False

  * Good code is its own best documentation, and self-explainatory code does not need to be documented.
</details>
