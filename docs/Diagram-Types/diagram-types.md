# Diagram Types

[<-Home](../../README.md)

PlantUML auto-detects the diagram type based on the first unique item in the code.
See https://plantuml.com/commons#6dd346f9babe70c8 for diagram type examples that show what keywords or symbols trigger auto-detection of diagram type.

## Contents

[Activity Diagram](#activity-diagram)<br>
[C4 Model Diagrams](#c4-diagram)<br>
[Class Diagram](#class-diagram)<br>
[Component Diagrams](#component-diagrams)<br>
[Deployment Diagrams](#deployment-diagrams)<br>
[Gantt Charts](#gantt-charts)<br>
[Mind Map](#mindmap-diagram)<br>
[Mind Map of Tasks](#mindmap-diagram-tasks)<br>
[Sequence Diagrams](#sequence-diagram)<br>
[Use Case Diagram](#use-case-diagram)<br>


<a name="activity-diagram"/>

## Activity Diagram

![Activity Diagram](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/alphahm/PlantUML-Examples/master/docs/Diagram-Types/source/activity-diagram.puml)

[(source PlantUML code)](source/activity-diagram.puml)

Note: auto-detect activity diagram type by lines that start with : and end with ;


<a name="c4-diagram"/>

## C4 Model Diagrams

### C4 Model Context Diagram

![C4 Model Context Diagram](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/alphahm/PlantUML-Examples/master/docs/Diagram-Types/source/c4-model-context-diagram.puml)

[(source PlantUML code)](source/c4-model-context-diagram.puml)

### C4 Model Container Diagram

![C4 Model Container Diagram](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/alphahm/PlantUML-Examples/master/docs/Diagram-Types/source/c4-model-container-diagram.puml)

[(source PlantUML code)](source/c4-model-container-diagram.puml)

### C4 Model Component Diagram

![C4 Model Component Diagram](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/alphahm/PlantUML-Examples/master/docs/Diagram-Types/source/c4-model-component-diagram.puml)

[(source PlantUML code)](source/c4-model-component-diagram.puml)


<a name="class-diagram"/>

## Class Diagram

![Class Diagram](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/alphahm/PlantUML-Examples/master/docs/Diagram-Types/source/class-diagram.puml)

[(source PlantUML code)](source/class-diagram.puml)

Note: auto-detect of class diagram type by use of line type:
* <|--
* *--
* o--
* ..
* --


<a name="component-diagrams"/>

## Component Diagrams

![Component Diagram](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/alphahm/PlantUML-Examples/master/docs/Diagram-Types/source/component-diagram.puml)

[(source PlantUML code)](source/component-diagram.puml)


<a name="deployment-diagrams"/>

## Deployment Diagrams

This isn't strictly a UML Deployment Diagram, but is similar:

![Deployment-Like Diagram](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/alphahm/PlantUML-Examples/master/docs/Diagram-Types/source/deployment-like-diagram.puml)

[(source PlantUML code)](source/deployment-like-diagram.puml)


<a name="gantt-charts"/>

## Gantt Charts

Example Gantt chart:

![Gantt Chart](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/alphahm/PlantUML-Examples/master/docs/Diagram-Types/source/gantt.puml)

[(source PlantUML code)](source/gantt.puml)


<a name="mindmap-diagram"/>

## Mind Map Diagram

Mind map diagrams are a great way to quickly break a problem or concept down into smaller parts.

Here is a simple example:

![Mind Map Simple](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/alphahm/PlantUML-Examples/master/docs/Diagram-Types/source/mindmap.puml)

[(source PlantUML code)](source/mindmap.puml)

<a name="mindmap-diagram-tasks"/>

## Mind Map Diagram of Tasks

Here we create a Mind Map to track tasks, with visual tags for urgent and completed:

![Mind Map of Tasks ](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/alphahm/PlantUML-Examples/master/docs/Diagram-Types/source/mindmap-tasks.puml)

[(source PlantUML code)](source/mindmap-tasks.puml)


<a name="sequence-diagram"/>

## Sequence Diagrams

Sequence diagrams present ordered events that occur between participants (actors) over time (which runs top-to-bottom)

Here is a simple example:

![Sequence Simple](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/alphahm/PlantUML-Examples/master/docs/Diagram-Types/source/sequence-simple.puml)

[(source PlantUML code)](source/sequence-simple.puml)

There are multiple types of participant that can be used to trigger a sequence diagram, as per the types in the example below:

![Sequence Participants](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/alphahm/PlantUML-Examples/master/docs/Diagram-Types/source/sequence-participants.puml)

[(source PlantUML code)](source/sequence-participants.puml)

The order that that participants is declared determines their order left to right in the diagram, and the order of the events is the order top to bottom

Here is the same diagram, but with simpler set-up code, thanks to use of a theme:

![Sequence Participants](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/alphahm/PlantUML-Examples/master/docs/Diagram-Types/source/sequence-participants-theme.puml)

[(source PlantUML code)](source/sequence-participants-theme.puml)

Another example showing setting colours etc:

![Sequence Another Example](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/alphahm/PlantUML-Examples/master/docs/Diagram-Types/source/sequence-another-example.puml)

[(source PlantUML code)](source/sequence-another-example.puml)

<a name="use-case-diagram"/>


## Use Case Diagram

![Use Case Diagram Example](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/alphahm/PlantUML-Examples/master/docs/Diagram-Types/source/use-case-diagram.puml)

[(source PlantUML code)](source/use-case-diagram.puml)

