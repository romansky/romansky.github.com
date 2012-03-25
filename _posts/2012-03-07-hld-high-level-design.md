---
layout: post
title: "HLD High Level Design"
category: 'code'
tags: []
---
{% include JB/setup %}

### HLD - High Level Design

This post is a follow-up on ["Bootstrapping A New Project"](/code/2012/02/07/bootstrapping-a-new-project/)

#### Previously...

I've written about ["User Stories"](/code/2012/02/25/user-stories/), a tool to helps with expectation setting when working with (mostly) non-technical stakeholders.

#### Designing Toward

 - **database** (schema, tables, indexes..)
 - **application layout**
 - **deployment**
 - **modules**
 - **internal and external APIs**
 - **application infra** (frameworks, tools etc..)

#### Design Tools At Your Disposal

 - **system architecture** - big pieces that make up the system ([example-Lucidchart](http://www.lucidchart.com/publicSegments/view/4f6e3aaf-0798-4bce-97ca-386a0a5a8951/image.png))
 - **activity diagram** - communication between components in the system ([more info](http://www.agilemodeling.com/artifacts/activityDiagram.htm))
 - **sequence diagram** - algorithms / processes high level implementation ([example-Lucidchart](http://www.lucidchart.com/publicSegments/view/4f6e3ae9-8544-46f2-a469-1daf0ac9c29f/image.png), [more info](http://www.agilemodeling.com/artifacts/sequenceDiagram.htm))
 - **state diagram** - state minded processes / algorithms ([more info](http://www.agilemodeling.com/artifacts/stateMachineDiagram.htm))
 - **mock ups / wire frames** - for projects with GUIs ([example-Google Draw](https://docs.google.com/drawings/pub?id=1y-GFJZeIcqSIk2hFcf9SWjWnpemvaBU-ffdPjv1u4hs&w=960&h=720))

#### Audiences

System Architect - mostly interested in the software stack, deployment and the database design

Team Members - mostly interested in the more lower level stuff like modules and API's

Other Teams - mostly interested in API's

Feedback on design is great for everyone involved, setup meetings with relevant parties to do DR (design review)

#### UML and Other Vegetables

UML is complex, you don't need to know it well perfectly, start with what makes sense, and slowly pick up tutorials. Remember, its a visual tool that helps you communicate, not everyone who will look at your designs has the time (or cares for) to read throughly a book about UML and its specifics. In Einstein's words "Make everything as simple as possible, but not simpler." 


##### 

I covered User Stories, which is an important towards being in sync with stakeholders, most probably with whom is not an engineer.
Since the scope of the project is clear, it is a good time to think about the overall implementation, choose a technology stack and think about the design as components each with some defined functionallity.
Writing HLD is especially helpful and important if **other engineers** are going to be working on this project or **an architect** is going to be involved in the process. In other words, compared to User Stories, HLD is mostly for internal engineering use.

#### Disclosure

Design does *not* last. Nobody is going to update the design as the system grows and evolves. Having said that, can still be used a good reference.






