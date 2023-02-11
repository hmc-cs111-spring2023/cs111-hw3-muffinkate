# Free project 1

## The user and a language

This section describes who the project would serve and why a language might be a
good way to meet their needs.

### What's the need?

_What need is met by your idea? Who are you helping? What is that person's
experience like now? What would their experience be like if you could help
them?_

This project would help long-arm quilters create pantograph patterns. The existing methods of doing do are by hand using a mechanical pantograph machine, or using the expensive online quilting software EQ8. If they could use a programming language, they could use the computational abilities to draw a shape, and pattern-ify it easily within the constraints of the quilt that they want to make.

### Why a language?

A DSL is approprate because it could leverage the automation of patterns, and quickly propogate an idea to visualize the larger pattern. Drawing one shape is probably easier by hand, but to have it be a pattern and then be the right size to print and then quilt is a more complicated procedure, that could benefit from all of those things being in the same place.

### Why you?

This excites me because I love quilts and quilting, even though I am not a long-arm quilter. I came up with it because I follow other long-arm quilters and have really enjoyed the patterns that they come up with and became interested in the process. I think it would be fun to try and contribute to that community and provide computational skills to such a cool art form. 

### Domain

Digitizing the pantograph creation process

### Interface (syntax)

I imagine the user would interact with the language in a way that's similar to other simulation or visually creative designs, where the user would have some things that are settings, and then the initial design would be more like typing code to create shapes that create the patterns. It's not a traditional way to interact with the problem domain, since long-arm quilters are a niche group, and not all of them create their own pantographs. However, that doesn't mean it's the wrong way to interact with the problem domain, it might just require a learning curve for people to adopt it.

### Operation (semantics)

When the program runs, the user would be able to see the design in a window as a finished pantograph. The types of errors that might occur could be syntactically, but most aesthetically if the shape didn't "pattern" the way they expected, or there were some parameters that were a bit strange, or they just decided they didn't actually care for the design. All those errors could easily be communicated through the design window and the artist can then decide what to do next. Syntactic errors wouldn't compile, and it would show the user where the issue went wrong.

### Expressiveness

It should be really easy to visualize a pattern from a smaller design in this language, and export that in a format ready for quilters to use. It should ideally also be very easy to create said design, though sometimes translating code to art has a learning curve. It should not be able to do anything outside of that function - I think the project would have gotten a little astray if it was also able to create something like a knitting pattern, since those are very different visually. Then again, that might not be impossible, as would creating a design based on some data visualization. That being said, I don't think it should be able to do calculations. I'm imagining something somewhat similar to ContextFree Art in terms of what operations it can do, if not the actual purpose or implementation.

### Related work

There are not really any other DSLs that I could find. There is a software called Electric Quilt 8 (EQ) <https://electricquilt.com/online-shop/category/electric-quilt-8-eq8/> which is an interface for a digital quilting design process, including pantographs, but also including lots of other parts of the quilting process. From what I can tell, it's not a bad tool, but if you just want to create pantographs, it feels hard to justify a several hundred dollar license purchase. I do like in EQ8's pantograph function, they have the ability to both create and import pantograph patterns.

## The Project

This section examines whether the idea makes for a good CS 111 project.

### Suitability

I think this has a lot of really cool language design decision possibilities, especially for the users that would use it, thinking about whether there is code or a different kind of interface is already a really important question, as well as the design all of the capabilities and the best way for a user to implement them.

### Scope

I think this idea is a bit ambitious, but only because creating a whole DSL feels ambitious. I think it could leverage exisiting host language's visualization capabilities and do just fine. The actual scope of the project seems very doable.

### Benefits and drawbacks

I think this might be a good idea for a project because it takes existing DSL ideas for creativity and simulation and art and puts a new twist on it with an otherwise niche domain. That being said, I'm not sure how many people would want to use it, or care that much, and so I feel like I'd want to talk to other quilters besides myself to see if it's worth the trouble, so to speak.