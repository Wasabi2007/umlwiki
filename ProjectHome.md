UMLwiki defines a syntax for pure-ASCII language which represents UML diagrams. It is experimental project which is on planning stage already.

The project's goal is to provide the tools which can be adapted to wiki engines (i.e. [MediaWiki](http://www.mediawiki.org/)). This project is inspired by [UMLGraph](http://www.umlgraph.org/) and [UmlSequence plugin for MoinMoin](http://moinmo.in/ParserMarket/UmlSequence) projects.

An example of UML Class Diagram:

```
[               Company
             <<singleton>>
 ===================================
 +give_me_a_rise (employee : Person)
 +please_hire_me (prospect : Person) ]

[        Person
 -----------------------
 -name : String
 -----------------------
 +you_re_fired () : void ]

[Company] 1 employer <@>--- "< works for" employee 1..n [Person] 1 boss --- flunkies 1..* [Person]
```

Graphic representation:

![http://www.holub.com/goodies/uml/images/companyemployee.gif](http://www.holub.com/goodies/uml/images/companyemployee.gif)

See:

  * UmlwikiExamples