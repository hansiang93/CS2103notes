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
  Collaboration, recovering from mistakes, manage drift between multiple versions of project, detect incompatible changes to the same file.
</details>

<details> 
  <summary> Which RCS flow does not have branches?</summary>
  A: Centralised flow!

  There is a distributed RCS and centralised RCS. Distributed has multiple remotes that PR each other.

  Forking flow is what we did for CS2103, 1 main and everyone forks from there and PR back.

  Feature Branch Flow is 1 Main, with multiple branches inside with a feature each, and merges back to Main.

  Centralised Flow is this markdown form. Free For all.
</details>

<details> 
  <summary></summary>
  
</details>

<details> 
  <summary></summary>
  
</details>

<details> 
  <summary></summary>
  
</details>


## IDE


<details> 
  <summary>Debugging is the process of?</summary>
  A: Debugging is the process of discovering defects in the program.


  👎 By inserting temporary print statements

  👎 By manually tracing through the code

  👍 Using a debugger
  Allows for step wise running of code in real time

</details>

## Testing

<details>
  <summary>How does the Singleton pattern affect the testability of a Java application? </summary>
  A: Singletons reduce testability due to these reasons: 
  
  * They create implicit dependencies that are hard to replace using dependency injection because Java doesn’t allow overriding of static members. 
  
  * Singleton object represents a global ‘state’. If the state of the Singleton affects the test case execution, then the Singleton object needs to be ‘reset’ at the beginning of each test case. 
  </details>


### Mock exam? Just try bah


#### Project Management




#### Testing

<details> 
  <summary> Testing how easy it is to use a software is a form of Integration Testing</summary>
  Answer: False

  this is a form of System testing
</details>

<details> 
  <summary> When a developer tests a SUT, it is called Developer Testing</summary>
  Answer: True

  this is to start testing as early as possible, before a full product is released.
</details>

<details> 
  <summary> Scripted testing is better than exploratory testing</summary>
  Answer: False

  A mix of both is better than either.
</details>

<details> 
  <summary> A test driver is a person that tests the SUT for the purpose of testing</summary>
  Answer: False

  A test driver is the code that ‘drives’ the SUT for the purpose of testing
</details>

<details> 
  <summary> A stub can be used to inject into an object for the purpose of testing in islation</summary>
  Answer: True

  Dependency injection is the process of 'injecting' objects to replace current dependencies with a different object. This is often used to inject stubs to isolate the SUT from its dependencies so that it can be tested in isolation.
</details>
