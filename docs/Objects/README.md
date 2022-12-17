# Objects

[<-Home](../../README.md)

## Contents
[Component](#component)<br>
[Interface](#interface)<br>
[Rectangle](#rectangle)<br>
[Actor](#actor)<br>
[Artifact](#artifact)<br>

<a name="component"/>

## Component

```plantuml
@startuml
component [component] as myComponent
@enduml
```

![Component](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/alphahm/PlantUML-Examples/master/docs/Objects/source/component.puml)

<a name="interface"/>

## Interface

```plantuml
@startuml
() "This is an interface" as myInterface
@enduml
```

![Interface](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/alphahm/PlantUML-Examples/master/docs/Objects/source/interface.puml)

<a name="rectangle"/>

## Rectangle

```plantuml
@startuml
rectangle "This is a Rectangle"
@enduml
```

![Rectangle](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/alphahm/PlantUML-Examples/master/docs/Objects/source/rectangle.puml)

Rectangles can group other objects:

```plantuml
@startuml
rectangle "This is a Rectangle with things in it" {
    () " " as o1
    () " " as o2
    :Actor:
    [Component]
}
@enduml
```

![Rectangle](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/alphahm/PlantUML-Examples/master/docs/Objects/source/rectangle2.puml)

<a name="actor"/>

## Actor

Note that if you use keyword 'actor', it will assume format of a sequence diagram. Use colons around actor name instead.

```plantuml
@startuml
:"Alice":
@enduml
```

![Actor](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/alphahm/PlantUML-Examples/master/docs/Objects/source/actor.puml)

Can change colour etc with skinparams:

```plantuml
@startuml
skinparam ActorBorderColor black
skinparam ActorBackgroundColor white
:"Alice":
actor "Bob"
@enduml
```

![Actor](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/alphahm/PlantUML-Examples/master/docs/Objects/source/actor2.puml)

<a name="artifact"/>

## Artifact

An artifact in UML is generally a file

```plantuml
@startuml
artifact "config.json"
@enduml
```

![Artifact](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/alphahm/PlantUML-Examples/master/docs/Objects/source/artifact.puml)
