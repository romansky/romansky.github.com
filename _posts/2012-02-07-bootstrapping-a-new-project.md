---
layout: post
title: "Bootstrapping A New Project"
category: 'code' 
tags: []
---
{% include JB/setup %}
### My opinion on: How to give your new project a good starting point
So, you have a new shiny project on your lap, so now what?  
First post in a series, where I talk about kicking off a new software project, and dive into the details of what you need to know to survive the rough sail in the seas of a new software project, from conception, to beginning of implementation.
#### Waterfall
One (somewhat notorious in the software community) approach is the "waterfall" model, there is allot of information about it on the web, and here are some highlights of why its perceived to be bad:

 - It assumes that the initial requirements will not change
 - There is only one version delivered to the stake holders, at the end of the process
 - After the design stage, the estimates are "set in stone", expectations are to be met on the final day of the project (or the first day of that stage thereof)
#### Agile
Another approach, the craze today in the development community, an industry by itself, is of course the "Agile" methodology.  
It is a world of sub cultures, some of which are: "XP" (eXtreme Programming), "scrum", "Kanban" to name a few.  

The main strengths going for the Agile methodology are

 * Short requirements collection loop, followed by a short design process
 * Iterations, plan for when the iteration ends (usually couple of weeks ahead)
 * Quick turn around with initial results
 * Issues (due to bad requirements / design) are found much earlier in the process

As any UI developer would tell you, there's nothing quite like a quick feedback loop, especially when working on a big complex project  
Still, Agile is a matter of style, some even tie in TDD (Test Driven Development) or BDD (Behavior Driven Development - "TDD 2.0" according to some) 

#### The bare minimum
IMHO, here are the bare minimal things you have to do when starting work on a new development project:

 * A list of "user stories"
 * HLD (High Level Design)
 * System diagram
 * Sequence diagram
 * Mock-ups (in the case of a UI app)

#### Tooling
Here are the tools I personally use to kick start the development process

 * Google Document- User Stories
 * Google Drawing- mockups, system diagrams, HLD
 * Lucidchart- system diagram, sequence diagram

In addition, I use a web based project management tool as a central place to keep reference to important docs and user stories, and manage my progress (and others working on the project). As of late the tool for the job is [Trello.com](http://www.trello.com), a free, super simple and productive web based project management app.

Stay tuned as I go deeper in the rabbit hole and talk about every point in my "bare minimum" list. (an update once a week, will add to this post)  

It goes without saying that there is much more to delivering the actual product, my goal is to tell you about my experience in starting new projects.

Next week I will talk about "user stories", why they are important, and how to write them..
