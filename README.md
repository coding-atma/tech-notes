# Tech-notes
All tech notes in one place.

------

## General

- TO DO

------

## Software Engineering Principles / Philosophies - NON TECH


| **Principle / Law**          | **Description**                                                                                                                                      | **Comments**                                           |
|------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------|
| Murphy's Law                 | `Anything that can go wrong will go wrong.`                                                                                                          |                                                        |
| YAGNI                        | `You Are Not Going to Need It.`                                                                                                                      | Sometime we engineers' go on to do things not required. |
| Bullshit Asymmetry Principle | `The amount of energy needed to refute bullshit is an order of magnitude bigger than that needed to produce it`                                      ||
| Knuth's Law                  | `Premature optimization is the root of all evil (or at least most of it) in programming.    `                                                        |                                                        |
| Conway's Law                 | `Organizations which design systems ... are constrained to produce designs which are copies of the communication structures of these organizations.` |                                                        |
| Principle of Chaos           | `N/A`                                                                                                                                                |                                                        |
| Project Triple Constrains    | `Fast , Cheap , Good - you will get just 2 - not all 3. https://www.projectsmart.co.uk/understanding-the-project-management-triple-constraint.php`   |                                                        |

-----

## Design

- TO DO


-------


## Distributed Systems

### Theorems

* **CAP** 
* - **C**onsistency **A**vailability **P**artition Tolerance 
. ```No distributed system is safe from network failures, thus network partitioning generally has to be tolerated. In 
    the presence of a partition, one is then left with two options: consistency or availability. When choosing consistency over availability, the system will return an error or a time out if particular information cannot be guaranteed to be up to date due to network partitioning.```
. https://en.wikipedia.org/wiki/CAP_theorem.
* **PIE**
* - **P**attern Access , **I**nfinite Scale , **E**fficiency . You can get two of PIE. PIE is new next after CAP. Given We know what we need in CAP already. 

-------

## Toolbox

- Design Diagrams
  * General
    * [Yed](https://www.yworks.com/products/yed)
    * [Draw.io](https://app.diagrams.net/)
  * Sequence / Use Case Diagrams
    * [PlantUML](https://github.com/plantuml/plantuml)
    * [PlantText](https://www.planttext.com/)
  * Java Specific
    * [MAT](https://community.oracle.com/tech/developers/discussion/4483431/eclipse-mat-titbits) - Headp Dump Analyzer / Memory Analyzer Tool.
    * [YourKit](https://www.yourkit.com/docs/java/help/cpu_flame_graph.jsp) - Flame Graph (or) Profiler.
  * IDE
    * General
      * IntelliJ.
      * Eclipse.
    * Python
      * Pycharm - for python.
    * Typescript / AWS CDK
      * Visual Studio.


-------