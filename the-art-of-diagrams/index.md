# Generative AI and the art of diagrams

## tags:

- art
- uml
- vibe
- modelling
- it architecture
- AI

## TL;DR

- Consistency in style and notation increases comprehension and reduces incorrect assumptions about the design
- Using novel notation enables greater expression at the risk of misinterpretation 
- Often established notations (e.g. UML®) are not universally understood by most target audiences
- Always provide a legend or key to guide the audience
- Generative AI also needs consistency in the prompt style to be consistent and predictable in its output.

## In the beginning...

In the world of Information Technology, architecture diagrams are an essential means to communicate the intent of any system design. Today people attempt to communicate their intention to a Generative AI model, hoping that the resulting systhesised content meets their expections. 

As a student of Chemical Engineering I encountered standardised diagramming notations for various aspects of design, such as Process Flow Diagrams (PFD) and Piping & Instrumentation Diagrams (P&ID). The fundamental purpose of diagram standardisation is to faciliate a consistent and accurate means to express the author's intent and for learned audiences to be able interpret and realise the design. All such diagrams are essentially a type of model. They simplify the physical solution and convey specific detail needed to progress the project towards delivery.

Shortly after graduating I moved into IT first as a developer and then trained to become an IT Architect. I was introduced to the Unified Modelling Language® (UML®) which at the time was strong on functional design, but was lacking in operational modelling. IBM at the time had developed the Architecture Description Language, which extended UML with a particular notation for operational and deployment modelling. UML2 has many extensions and enhancements over the original version that also provide features for expressing operational modelling. Despite being published as an open standard, UML never became ubiquitous for many reasons including the steep learning curve and limited tooling. 

## Artistic or Structured?

IT Solution Architecture needed a more flexible and consumable approach. Architects and Systems Engineers typically adopted their own style of diagramming, often incorporating elements of more formal methods in an informal way - the "Wild West" era of IT Architecture! The more abstract the level of design, the greater the variation of expression. The diagrams can become more artistic. This is particularly applicable to the `Architecture Overview` or `Architecture Summary` work product. The intention of the Architecture Overview is to convey the end to end big-picture view of the proposed IT solution, whilst high-lighting the architecturally significant elements or "systems". The notation and presentation style needs to be tailored to the intended audience (who often isn't an IT Architect). Artistry becomes a communication skill at this level. 

## Creating or generating the Architecture Overview

The _Architecture Overview_ can incorporate business and technical elements. It might illustrate aspects of deployment and location (e.g. geographic regions), key business systems (e.g. Core Banking), architecturally significant technologies and constraints (e.g. a particular technology platform, cloud services provider, database or reference services). In some traditional methodologies, the difference in the presentation of these various "stereotypes" is quite limited, often using the same type of box with a stereotype label. A more artistic approach, introducing more colour, shape and even technology icons or characterisation can make the diagram and hence the discussion, more consumable.

Typically this diagram majors on the _static_ view, identifying the significant elements and their relative position to each other. There may be some aspect of the System Context incorporated, usually represented by people and external systems (i.e. actors in UML terms) positioned on the periphery of the diagram. Function and behaviour is usually not illustrated in an overview because that starts to clutter the visual appeal and include too much detail.

System and enterprise boundaries are usually represented. Juduicious use of business iconography can help here to convey concepts that are likely to be recognised by the intended audience. It isn't uncommon to create multiple overview diagrams according to the specific audience.



## Method or Notation?


## Vibe Diagramming?

full circle - need to consistently explain your intent to AI to get the desired output
However, if you can use consistent notation, AI should be able to generate predicatable elaborations based on best practices.


## Generative AI Prompt Engineering for Architecture Overviews

Provide the narrative for an overview, show examples


## Links:

  - [Unified Modelling Language®](https://www.omg.org/spec/UML/2.5.1/)

## Trademarks: 

  - Unified Modeling Language®, UML® are registered trademarks of the Object Management Group, Inc.

## Disclaimer

The postings on this profile are my own and do not necessarily represent my employer's positions, strategies or opinions.
