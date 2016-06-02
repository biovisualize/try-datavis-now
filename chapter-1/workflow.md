# Find your place in the workflow

## Specialties
**What type of designer are you?** Datavis design can mean multiple things. Some focus can be on **graphic design**, **user experience** (UX), **software engineering**, **data science** or some **domain specific** expertise. All these specialties can play a role on different stages of the development process. I saw some designers drawing pixel-perfect mockups to help with product ideation. Their work was only seen by some product managers to help them decide on the features. Then another type of designer would turn these mockups into UIs and assets ready for implementation. Some will design directly in HTML/CSS/SVG, so they are closer to UI implementation. Another type of designer I see less often is UX designer. They know for example how to sketch wireframes, design components and user flow, they understand the human factor. In my opinion, you can succeed with a good UX even if you have a bad UI, but no UI can compensate for a bad UX. So UI, UX and graphic design are different and play different roles. I saw some UX designers stuck doing marketing websites and datavis engineers building plain frontend because they were not able to explain the difference. And, just to make it more complicated, datavis design can be a mix of all those type of design. So it's important for a designer to be clear about the exact skill set he has, to find the place he wants in the workflow.

## Products
It's also important to know about the **workflow** and how a datavis designer can have the most impact. The development workflow will be different if the product is an app, a framework, or an infographics. Some datavis products will be consumer facing applications, but a lot of companies, like service companies, also need datavis for monitoring systems, for taking data-driven decisions, for internal communication, etc. To give a broad categorization, we could say that some products are made for **discovery**, other for **communication** and other for **supporting decision-making**. Skills for communication are very different than mastery of statistics for example. But datavis designers often combine multiple of these seemingly unrelated talents, so they may have to find a weird title for their role and a new way to integrate in the pipeline.

The development workflow also depends on multiple factor like the size of the company, the domain and the business model. A datavis consulting startup is different than a business intelligence software megacompany. So how does a datavis designer finds his place in a development team? Let's first describe a typical development workflow that is generic enough to be useful to describe a lot of cases.

## Workflow

One example of an Agile workflow:
* Product owner: user stories
* Product manager: listing requirements, breaking them down into tasks
* Designer: wireframes and mockups
* Developers: products
* QA: tests

| Stage | Deliverable | Typical Role | Datavis role |
|-------|-------------|--------------|--------------|
| User stories | Prioritized story list | Product owner | Brainstorming |
| User Experience | Wireframes | UX designer | Datavis design |
| Requirements | Spec sheet | Product manager | Choice of tools |
| UI design | Mockup | Graphic designer | Best practices |
| Tasks | Task list | Production manager | Syncing |
| Implementation | MVP | Team members | Syncing |
| QA | Tests, CI, reports | QA | User tests |

### User stories
A typical workflow starts with gathering the user stories, a description of the user needs. They illustrate some user needs as a set of high level requirements. A datavis designer is used to looking at data and functional tasks and see how they relate to use cases and user flows. He is often strong in building communication tools and bringing a set of functional requirements to a meaningful shape. So he can sit down with the product owner and brainstorm with him, sketching some very high level **wireframes**, just to make sure the right needs are identified and that the story list describes a complete minimal viable product. 

### User Experience
The datavis designer strong in user flow and information architecture can play an important role in UX design. The challenge at this stage is to get just enough visuals for designing how the user stories could be turned into a consistent experience, but without getting into graphic design or into functional requirements. We need some sort of **storyboarding** to refine the user stories. Wireframes are better to use at this point than pixel-perfect mockups, so ideas can be iterated on quickly without getting distracted by graphical choices. Wireframes can look sketchy or technical, to make sure they are not confused with what the actual product could look like. **Information architecture** techniques, like card sorting or flow diagrams, are nice ways to abstract the UX tasks from graphical design.

### Requirements
Once UX design gave some kind of storyboarding to the user stories, each story can be translated to technical requirements. Typically, the product manager consult with the team to sort the stories into epics and to choose the **technology stack**. The datavis designer stronger in engineering can help choose the technologies, since he most often has to integrate multiple layers of technologies from database to backend to frontend. It's also useful for every developers to take ownership of some epics. The datavis designer can own any datavis epics but also oversee the whole data pipeline for example.

### UI design
I see a lot of datavis designers focusing on graphical design, most often coming from **graphical design** and specializing in human factor and datavis.

### Tasks
The production manager helps the team to break down the epics into tasks. The datavis designer can help with **syncing** the tasks together as he is often kind of the user of the whole pipeline.

### QA
Datavis typically **exposes** the result of the whole pipeline. If something breaks anywhere in the stack, the datavis will break, if it doesn't gracefully degrade. So it's important to install a QA process to monitor failures, but also to be able to trace back on the layer that broke. If it's impossible to prevent the failure, the UI will need to notify the user in a meaningful and actionable way and stay responsive and as useful as possible. 



---
Example of a datavis design workflow and its deliverables
User stories are very high level. For example, "the user needs to be notified under 5 minutes when electric current goes over a threshold" is more suitable as a story than "the user needs a line graph with a threshold line that blinks if electric current". A datavis developer can get involved at this point for his drawing and mind-mapping skills or UX skills, even if it's not the right stage to think about graphics. He can also get involved because he knows how to tell a story from data. 


---
A data vis designer can combine various skills:

* Looking at data and functional requirements, and seeing use cases and useful tools 
* Brainstorming, mindmapping, wireframing
* User experience, information architecture
* Visual communication
* Choosing and integrating a technology stack
* Designing components, layouts and a consistent set of views
* Designing graphics, assets, communication elements
* Building visual and interactive tools
* QA, user tests, user interviews
* Marketing, outreach, user success


