# Built-in Quality Practices

## Lean Startup 

## Walking Skeleton 

## Test-Driven Development (TDD) 

TDD is based on three rules, knows as 'The Three Laws of TDD': 

* You must write a failing test before you write any production code.
* You must not write more of a test than is sufficient to fail, or fail to compile.
* You must not write more production code than is sufficient to make the currently 
  failing test pass.
  
In code, TDD is translated into the cycle Red/Green/Refactor!

[![TDD_Cycle](photos/red_green_refactor.jpg)](photos/red_green_refactor.jpg)

(source: https://blog.cleancoder.com/uncle-bob/2014/12/17/TheCyclesOfTDD.html)

The rules of this cycle are as follows: 
* Create a unit tests that fails
* Write production code that makes that test pass. 
* Clean up the mess you just made.

### Benefits
The top 3 advantages of TDD are: 
* Requires in-depth understanding of the what the code should do
* Increases the confidence in changing parts of the code
* Reduces the debugging time  

### Resources 
1. [CleanCoder](https://blog.cleancoder.com/uncle-bob/2014/12/17/TheCyclesOfTDD.html)
2. [Wikipedia](https://en.wikipedia.org/wiki/Test-driven_development)

## Behavior-Driven Development (BDD)

BDD is the combination of practices from TDD, Domain Driven Design (DDD) and 
Object-Oriented Design to produce software-development collaboration tools and 
processes. Those tools and practices emphasizes that software development should
be managed by business interest and technical insight. 

### Principles 

#### Testing 
In terms of testing, BDD is considered a continuation of TDD as it puts more 
focus on the desired behavior of the unit. The 'Desired Behavior' consists of 
the requirements defined by the business. 

#### Behavioral Specifications 
The second principle defines how the 'desired behavior' should be written. Here, 
BDD uses the terms 'Scenario' & 'Specification' to gather all requirements and 
expected outcome in a single place that is a User Story. 

Although, there is no official format defined in BDD, there is a preference to 
follow the form 'Given-When-Then'

#### Specification as a ubiquitous language
Ubiquitous Language is defined in DDD. It is a 'semi-formal' language that is 
developed and used by team-members to have common understanding of the discussion 
between them. Thus, reducing the risks of having a communication break-down 
between developers and stakeholders.


### Benefits 
The 3 benefits of BDD are: 
* Guides and organizes the conversation between the different parties of the 
 software development team (developers, testers and domain experts)
* The given-when-then canvas is closer to everyday language
* Tools targeting a BDD approach generally afford the automatic generation 
  of technical and end user documentation from BDD “specifications”
  
### Resources
1. [Agile Alliances](https://www.agilealliance.org/glossary/bdd/)
2. [Wikipedia](https://en.wikipedia.org/wiki/Behavior-driven_development) 

## Continuous Integration (CI) 
Continuous Integration is a process that helps developers detect problems faster
through frequent integration of code to a shared repository. The build, 
regression and acceptance tests are automated and executed at each check-in.

### Practices 
* Maintain a single source repository
* Automate the build
* Make your build self-testing
* Every commit should build on an integration machine
* Keep the build fast
* Test in a clone of the production environment
* Make it easy for anyone to get the latest executable version
* Everyone can see what’s happening
* Automate deployment

### Benefits 
The 3 benefits of CI are: 
* Generate deploy-able software at any time and at any place
* Shortens the feedback loop and reduces operational, technical & human risks
* Reduces the debugging time 

### Resources 
[ThoughtWorks](https://www.thoughtworks.com/continuous-integration)
  
## Dev Ops 

## Craftsmanship 

