[autocad]: https://www.autodesk.com/


# Interview project

## The user and a language

This section describes who the project would serve and why a language might be a
good way to meet their needs.

### What's the need?

I spoke with Felix Murphy, a current engineering junior here at Harvey Mudd. He's been using the software SolidWorks for several of his engineering assignments, which has proved to be a big pain to work with.

SolidWorks is really powerful as a tool, but is lacking in some areas that make using and debugging complicated designs difficult and time-consuming. The largest problem Felix is experiencing with SolidWorks right now is that he doens't know enough about SolidWorks to be able to realize how missteps during one step of the process will affect things later down the line, and when SolidWorks gets "angry" it doesn't have a good way of communicating why. 

I'd hope to help give Felix, and other users, a way of better accessing, seeing, and manipulating the numerical data that SolidWorks uses to create the visual model. This would help debug and track the pieces that fit together to create the larger design.

### Why a language?

I think a DSL is appropriate for my user because it would be a new way of manipulating and accessing data that SolidWorks uses. If there is an API within, or on top of an exisiting CAD software, the user could have a more direct way and numerical way of making and tracking object components, while still maintaining the powerful capabilities of the CAD software itself. Essentially, it would aid in the communication between the user and the data/software SolidWorks is using when it builds the designs.

### Why you?

I came up with this idea in conversation with Felix and thinking about all the things he was struggling with. I also mentioned these high-level ideas about how to potentially solve those problems, and he indicated that it would be helpful. I'm excited about the possibility to ease a major CAD headache, as well as learning new skills.

### Domain

API manipulating numerical CAD data

### Interface (syntax)

Ideally, I would want this language to sit within an existing CAD software. I'm not trying to tackle the computer aided design-ing part of the problem, I just want to see if there's an easier way to access and manipulate the numbers that are underneath a CAD model. I'm not sure if this is the best way to interact with the problem domain, but it feels like a correct way, and one of the more helpful ones. A sidebar or external window where you could see and manipulate the numerical properties and relationships between the different objects, and if something goes wrong you can see where the error is in both the piece itself, and the different pieces that connecct to it to more clearly figure out what went wrong and fix it.

### Operation (semantics)

I think a big part of this idea is that it should be very much in conversation with the other visual aspects of a CAD model - that both are pulling and can edit the same underlying data. So if something changes in the main software, that gets reflected in this API and vice versa. Some tasks seem like they'd be easier in one or the other, so if there's an error it would have to be clear about what caused it. But having an API that keeps more transparent logs will help the user figure out what went wrong, even if the operation was on the visual model.

### Expressiveness

It should be really easy to see straight numerical data about the objects in a design. It should also be really easy to see the pieces that they connect with, and how. That being said, the whole point is that it is not a visual representation of these objects, since the CAD model does that already, so it might be difficult to rely on the more numerical representations of the relationships between objects.

### Related work

This idea builds off of an existing DSL, since CAD software like SolidWorks and AutoCAD are considered DSLs for simulation and prototyping. [autocad] However, because I'm not as familiar with CAD software, I have no idea whether this kind of tool exists in other software besides SolidWorks. My interviewee only has experience with SolidWorks, since that is the best one for the kind of engineering he is trying to do. What this project would do is try to fill in a hole in SolidWorks' capabilities and make it easier to use such a powerful tool.

## The Project

This section examines whether the idea makes for a good CS 111 project.

### Suitability

There are some design choices like what operations the user needs to be able to do, and the best way to interface that access, and how to portray and log actions and errors. However, I think that most of the time that, for example I would need, would be on the implementing and making sure that it interfaced with the CAD software well. 

### Scope

It feels ambitious to do with SolidWorks, but there are other opensource CAD softwares that one could use for the project, and I think that would make it more feasible. That being said, it still feels like a fairly large project - though not so large in scope that it could be impossible.

### Benefits and drawbacks

_Why might this be a good idea for a project? Why might this not be a good idea
project?_

This could be a good idea for a project because I think it could be very useful, if done correctly.However, it does feel a bit ambitious in terms of time and the fact that there would need to be a lot of work done on interfacing the two APIs together correctly and in a manner that made sense, which might take away from the time spent actually designing the language bit.
