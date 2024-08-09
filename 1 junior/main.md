# Junior Education

## Block 1 – Basics der Programmierung 1

### Selbststudium

#### C\#

* C# Kurs (Pluralsight): [C\# Fundamentals](https://www.pluralsight.com/courses/c-sharp-10-fundamentals)
* C# Kurs (MSFT Academy): [Programming in C\# Jump Start](https://learn.microsoft.com/en-us/shows/programming-in-csharp-jump-start/?l=j0iuozsfb_6900115888)
  * Object Oriented Programming, Managed Languages and C#
  * Constructing Complex Types – Object Interfaces and Inheritance
  * Controlling Programmatic Flow – and Manipulating Types and Strings
  * Code Reflection and Information – Working with Garbage Collection
  * Advanced C\#, Type and Value Validation – Encryption Techniques
  * Splitting Assemblies and WinMD – Diagnostics and Instrumentation
  * Interacting with the File System – Leveraging Web Services
  * Using LINQ to Objects and XML – Fundamentals of Serialization
* C# in a Nutshell [1] – Book Chapters:
  * (1) Introducing C# and .NET
  * (2) C# Language Basics
  * (3) Creating Types in C#
  * (5) .NET Overview
  * (6) .NET Fundamentals
* [C# Naming Guidelines](https://learn.microsoft.com/en-us/dotnet/standard/design-guidelines/naming-guidelines)

#### Version Control (Git)

* [What is version control](https://www.atlassian.com/git/tutorials/what-is-version-control)
* [What is Git](https://www.atlassian.com/git/tutorials/what-is-git)
* [Learn Git](https://www.atlassian.com/git/tutorials/learn-git-with-bitbucket-cloud)
* Try to use the console and have a look at the UI Tools [GitExtensions](https://gitextensions.github.io)
* Look at the UI Tool to see what the commands do
* [Branches](https://www.atlassian.com/git/tutorials/using-branches)
* [Pull Requests](https://www.atlassian.com/git/tutorials/making-a-pull-request)

#### Clean Code

* Clean Code [2] – Book Chapters:
  * (1) Clean Code
  * (2) Meaningful Names
  * (3) Functions
  * (4) Comments
  * (5) Formatting
  * (6) Objects and Data Structures
  * (10) Classes
  * (17) Smells and Heuristics

### Coding Dojo

* [Tannenbaum](https://ccd-school.de/coding-dojo/function-katas/tannenbaum/)
* [CSV Tabellieren](http://ccd-school.de/coding-dojo/function-katas/csv-tabellieren/)
* [Zeichen zählen](http://ccd-school.de/coding-dojo/function-katas/zeichen-zaehlen/)
* [Rot-13](http://ccd-school.de/coding-dojo/function-katas/rot-13/)

## Block 2 – Basics der Programmierung 2

### Selbststudium

#### C\#

* C# in a Nutshell [1] – Book Chapter:
  * (7) Collections
* [Exceptions](https://learn.microsoft.com/en-us/dotnet/csharp/fundamentals/exceptions)
* [An introduction to NuGet](https://learn.microsoft.com/en-us/nuget/what-is-nuget)
* [NuGet 101](https://learn.microsoft.com/en-us/shows/nuget-101/?wt.mc_id=educationalnuget-c9-niner)
* [Source Code Analysis (all Chapters)](https://learn.microsoft.com/en-us/visualstudio/code-quality/roslyn-analyzers-overview?view=vs-2022)
  * From now on, use [StyleCop.Analyzers](https://github.com/DotNetAnalyzers/StyleCopAnalyzers) NuGet package for all your projects and set `<AnalysisMode>AllEnabledByDefault</AnalysisMode>` in `.csproj` files or use `Directory.Build.props`, `stylecop.json` and `.editorconfig`.

#### Version Control (Git)

* Pro Git [3] - Book Chapters:
  * (1) Getting Started
  * (2) Git Basics
  * (3) Git Branching
* [Git Tutorial](https://learngitbranching.js.org)
* [How to Write a Git Commit Message](https://chris.beams.io/posts/git-commit)
* [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/)

#### Clean Code

* [Clean Code Developers](https://clean-code-developer.de/)
* [Kevlin Henney – Clean Coders hate when you use these programming tricks](https://www.youtube.com/watch?v=brfqm9k6qzc)
* Principles (Quellen selbst suchen)
  * KISS
  * YAGNI
  * DRY
  * LoD (Law of Demeter)
  * The Boy Scout Rule
  * Favor Composition over Inheritance (FCoI)
  * Root Cause Analysis
  * Premature optimization
  * Single Level of Abstraction (SLA)
  * Separation of Concerns (SoC)
  * Principle of Least Astonishment

### Coding Dojo

* [ToDictionary](https://ccd-school.de/coding-dojo/function-katas/todictionary/)
* [Mail Followup](http://ccd-school.de/coding-dojo/function-katas/mail-followup/)
* [Ringbuffer](https://ccd-school.de/coding-dojo/class-katas/ringpuffer/)

## Block 3 – Unit Tests

### Selbststudium

* [Your first Unit Test](https://learn.microsoft.com/en-us/visualstudio/test/walkthrough-creating-and-running-unit-tests-for-managed-code)
* [Code Coverage Analysis](https://confluence.atlassian.com/clover/about-code-coverage-71599496.html)
* The Art of Unit Testing [4] – all Book Chapters
* Test Driven Development (Research by yourself)

### Coding Dojo

* Bring code coverage to 100% for all your exercises
* Do Kata with Test Last Development (TLD) [Dateidubletten](https://ccd-school.de/coding-dojo/library-katas/dateidubletten-aufspueren/)
* Do Kata with Test Driven Development (TDD) [Stack](https://ccd-school.de/coding-dojo/class-katas/stack/)

## Block 4 – Object Oriented Programming 1

### Selbststudium

#### C\#
* C# in a Nutshell [1] – Book Chapter:
  * (4) Advanced C\#

#### OOP

* Object-Oriented Programming in C# Succinctly [5] - Book Chapters:
  * Introduction to OOP
  * Chapter 1 The Three Pillars of OOP
  * Chapter 2 Interfaces
  * Chapter 3 SOLID ("S" verstehen, "OLID" überfliegen)
  * Chapter 6 Architecture (Nur “DRY” und “Layers and Tiers”)

#### SOLID

* [SOLID – The Five Commandments of Good Software](https://learn.microsoft.com/en-us/shows/visual-studio-live-2017/w19)
* [Bob Martin: SOLID Principles of Object Oriented and Agile Design](https://www.youtube.com/watch?v=TMuno5RZNeE)

### Coding Dojo

* [Verzeichnisstatistik](https://ccd-school.de/coding-dojo/library-katas/verzeichnisstatistik/)
* Solve the C# version of [GildedRose Refactoring Kata](https://github.com/emilybache/GildedRose-Refactoring-Kata)

## Block 5 – Object Oriented Programming 2

### Selbststudium

#### OOP

* Object-Oriented Programming in C# Succinctly [5] – Book Chapters:
  * Chapter 3 SOLID -> Verstehen und Anwenden
  * Chapter 4  Design Patterns -> Verstehen und Anwenden
  * Chapter 5  General Responsibility Assignment Software Patterns or Principles (GRASP) -> Verstehen
  * Chapter 6 Architecture -> Verstehen und Anwenden
  * Chapter 7 Other Paradigms -> Verstehen

#### Design Patterns

* [C# Design Patterns Intro](https://www.dofactory.com/net/design-patterns)
* Design Patterns. Elements of Reusable Object-Oriented Software [6] - Book Chapters:
  * Introduction
  * Verstehen der 3 Arten
* [Design Patterns: Adapter and Facade](https://learn.microsoft.com/en-us/shows/visual-studio-toolbox/design-patterns-adapterfaade)
* Design Patterns. Elements of Reusable Object-Oriented Software [6] - Book Chapters:
  * Abstract Factory
  * Factory Method
  * Singelton
  * Composite
  * Decorater
  * Proxy
  * Command
  * Iterator
  * Strategy
  * Template Method

### Coding Dojo

* [Stadt Land Fluss](https://ccd-school.de/coding-dojo/architecture-katas/stadt-land-fluss/)

## Block 6 – .NET Internals

### Selbststudium

* (1) [Basics of memory structure](http://www.dsibinski.pl/2018/07/net-internals-01-basics-of-memory-structure/)
* (2) [Stack and heap – .NET data structures](http://www.dsibinski.pl/2018/08/net-internals-02-stack-and-heap-net-data-structures/)
* (3) [Boxing and unboxing](http://www.dsibinski.pl/2018/08/net-internals-03-boxing-and-unboxing/)
* (4) [What is Garbage Collection? Memory allocation in .NET](https://www.codejourney.net/net-internals-04-what-is-garbage-collection-memory-allocation-in-net/)
* (5) [Garbage collection: marking, collection and heaps compaction](https://www.codejourney.net/net-internals-05-garbage-collection-marking-collection-and-heaps-compaction/)
* (6) [Generational garbage collection](https://www.codejourney.net/net-internals-06-generational-garbage-collection/)
* (7) [Unmanaged resources: finalization, fReachable queue and dispose pattern](https://www.codejourney.net/net-internals-07-unmanaged-resources-finalization-freachable-queue-and-dispose-pattern/)
* (8) [What about Large Object Heap (LOH)?](https://www.codejourney.net/net-internals-08-what-about-large-object-heap-loh/)
* (9) [Just-In-Time (JIT) compilation](https://www.codejourney.net/net-internals-09-just-in-time-jit-compilation/)
* (10) [Application execution model](https://www.codejourney.net/net-internals-10-application-execution-model/)

### Coding Dojo

* [Leiterspiel](https://ccd-school.de/coding-dojo/application-katas/leiterspiel/)

# Literatur

[1] [C# in a Nutshell (neuste Version)](https://www.amazon.de/C-12-Nutshell-Definitive-Reference/dp/1098147448/ref=sr_1_1?crid=1RS28WQUSIWGQ&dib=eyJ2IjoiMSJ9.xBg5uB0XqNa7Ehlkp1TBAJFC__i0xB1Hmdd5OOQ8qGeQ0ESaqcBUJMfw4v7vTQTlOAuUxDIEN-M2dHsWarjAGlJOhDpX-nH5Te2iwW2MaLqFLS-yRwAPxY3LXePSCuVaedZTVvLQfQjkNNzUP4_2hEHZghMG8FMUXMyy0hSE9MJgAyEfcx6wnIJ7iNEZNXnfahogwT96gEuPC9zcPix2BqV5Jqdts_GQtYRwEt1YC5U.SHwuF-H9t_GDh16GHK-_q63LL2-47EE-ZcCK_LeuZE8&dib_tag=se&keywords=c%23+in+a+nutshell&qid=1723203210&sprefix=c%23+in+a+nut%2Caps%2C90&sr=8-1)

[2] [Clean Code: A Handbook of Agile Software Craftsmanship](https://www.amazon.de/Clean-Code-Handbook-Software-Craftsmanship/dp/0132350882/ref=sr_1_1?ie=UTF8&qid=1503219302&sr=8-1&keywords=Clean+Code)

[3] [Pro Git](https://git-scm.com/book/en/v2)

[4] [The Art of Unit Testing](https://www.amazon.de/Art-Unit-Testing-Roy-Osherove/dp/1617290890/ref=dp_ob_image_bk)

[5] [Object-Oriented Programming in C# Succinctly](https://www.syncfusion.com/succinctly-free-ebooks/oop-csharp)

[6] [Design Patterns. Elements of Reusable Object-Oriented Software](https://www.amazon.de/Patterns-Elements-Reusable-Object-Oriented-Software/dp/0201633612/ref=sr_1_1?s=books-intl-de&ie=UTF8&qid=1503219395&sr=1-1&keywords=Design+Patterns)