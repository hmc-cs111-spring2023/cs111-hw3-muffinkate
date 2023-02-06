# Free project 2

## The user and a language

This section describes who the project would serve and why a language might be a
good way to meet their needs.

### What's the need?

In my first assignment for this class I looked at a knitting domain language, so I wondered if something could similarly be made for creating and visualizing crochet patterns. There are few digital pattern creating aids for crochet, so the only way to test a pattern is to create it yourself, or ask someone else to. This is time consuming and frustrating if the patterns ends up not being correct, as well really difficult for more amateur crochet artists to create their own patterns. If there was a DSL to visualize and prototype crochet patterns, they would be able to see how the pattern looks before they use the time and yarn to test it.

### Why a language?

A DSL is appropriate because, like knitting, the creation of crochet patterns use computational thinking and so it translates well to algorithms. Furthermore, being able to visualize those stitches and how they fit together is super helpful to prototyping a pattern.

### Why you?

It excites me because I like to crochet, and I'd like to come up with my own patterns, but the patterns that I get from online aren't reliable enough for me to learn all the tricks to create my own without messing up terribly. I know I'm not the only with this issue - I also have friends who beta test patterns for other creators, which is how I started thinking about ways to digitize the prototype process.

### Domain

Creating and prototyping crochet patterns

### Interface (syntax)

I think there's a few ways to go about interfacing with the language. My first thought is something similar to Purl, the knitting DSL, where the notation is vaguely similar to knitting notation, and uses modular components. I think that parts of this would maybe work similarly, especially the type of crochet called amigurumi, which works in the round. For 2-d crochet patterns like scarfs, or something that would turn into a bag or shirt, you'd need to take a different approach. For that reason, I would think that the program would be much more like direct instructions for each row and stitch in that row, that would look a little differently if it was a 2-d or 3-d pattern.

### Operation (semantics)

When the program runs, you would be able to see a representation of the pattern as a visualization in a 2-d or 3-d space. You'd want to be able to see the whole pattern, as well as what different stitches looked like. Errors could be that there are holes or mismatches in rows, which would need to be both textually and visually communicated to the user. I would think both an error message and highlighting the offensive area on the design would be the most helpful. Aesthetically, errors are for the user to decide how they feel about them. And then syntacical errors would not create a prototype at all, and instead give an error message.

### Expressiveness

It should be really easy to see a prototype of your crochet pattern, as well as translate different algorithms into a crochet pattern. That being said, not all algorithms are going to be a valid pattern, and so anything that would break laws beyond artistic possibility would not be allowed, nor would any instruction that couldn't be a crochet stitch. Essentially, beyond the types of crochet stitches that there are, there would be very few instructions, so if there isn't a way to map it to a crochet stitch and a valid pattern, it won't be possible in the language.

### Related work

As of this past December, there is a crochet DSL that is in the works. <https://dl-acm-org.ccl.idm.oclc.org/doi/10.1145/3563835.3567657> "Digital Crochet: Toward a Visual Language for Pattern Description" by Seitz, et al. is about this language, which is a DSL that is "first visual" and "graph-based." I think what this does well is that because it is first visual, the users don't have to wade through ambiguities of different notations. That being said, it's then harder to use computation itself as an entry way into crochet patterns, so it begs the question of me as the designer who exactly would use this tool - many artists don't use algorithms in their work and name it as such.

## The Project

This section examines whether the idea makes for a good CS 111 project.

### Suitability

I think there would be a sizable portion of the project on language design choices, since you'd have to figure out how to translate notation to a language or interface. Though there would also be a lot of time implementing the visual prototype part of the project.

### Scope

I think the language design itself is reasonably sized, but implementing a visual way to see crochet patterns that can also communicate information like what stitches it uses, and how the rows connect together could be really difficult. (Though that also may be because I have no idea where to start with that)

### Benefits and drawbacks

This might be a good idea because it's fun to do something that can be practically used. That being said, if only a subset of crochet pattern designers want to think about it algorithmically, it might not lower the bar for entry when creating patterns at all, not to mention the potential difficulty of creating the visual prototyping abilities.
