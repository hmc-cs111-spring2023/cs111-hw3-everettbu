# Free project 2 - Re-design ContextFree

## The user and a language

This section describes who the project would serve and why a language might be a
good way to meet their needs.

Recalling helpful insight from the [Steele, 1998] reading, I learned that a good language should start off simple and have the room to grow. This also means that up-front it should simple for its users to learn and understand, but also contain advanced features that can be picked up if desired. I think that ContextFree is already a useful DSL, but it is too complex for it's entry level users.

### What's the need?

_What need is met by your idea? Who are you helping? What is that person's
experience like now? What would their experience be like if you could help
them?_

ContextFree is a powerful tool to create online art. However, its syntax is fairly confusing and hard to pick up. If I am  able to help improve this language, I would re-design the it so that it is easier to create simple art, while keeping its advanced features that many experinced users use and enjoy. 
This includes renamimg some of the functions to make them more clear, include the option to write out colors as a word rather than their hex values, and potentially add starter templates for people to build from. 

### Why a language?

_Why is a DSL appropriate for your user(s)? How does it address the need?_

A DSL would be useful for my users because it would allow for them to work on top of ContextFree, which already exists, and decide whether to use my features or not. A DSL is great for adressing this need because it allows for users within my domain to access simplifed features while still having access to all of the complexities ofContextFree

### Why you?

_What excites you about this idea? How did you come up with it?_

After having conversations with other students in our class, I realized that ContextFree was generally confusing to learn. With this in mind, if the language isn't easy for CS majors to pick up, people without a technical background would likely find it nearly impossible to learn. This project excites me because I felt this way myself and would find it rewarding to solve a problem I experienced first-hand.

### Domain

_Describe the project's domain in five words._

Simplified text generated online art

### Interface (syntax)

_How might the user interact with the language? What does programming look
like? Why is this the right way to interact with the problem domain?_

The user would interact with the language in the same way as they would with ContextFree, with the language on the lefthand side of the external DSL and the output on the right. The right way to interact with the domain would be to write a few lines of code and then test it out repeatedly.

### Operation (semantics)

_What might happen when a program runs? How does a program interact with the
user? What kinds of errors might occur, and how might they be communicated to
the user?_

When the program runs, art will be visually displayed. The program would interact with the user when errors occur. These errors include improper syntax, out of bounds ranges, or unknown colors or shapes. Unlike the original ContextFree, my DSL would provide more detail in communicating error to the user. It would point to the exact location that the error occurred and suggest a solution.

### Expressiveness

_What should be easy to do in this language? What should be possible, but
difficult? What should be impossible or very difficult?_

I think it would be easy to create new built in functions that makes ContextFree read and write more like a regular language. This would be my inital goal as I belive it would have great impact and is very achievable. I think it would be more difficult to create a system that could fix errors for the user. A stretch goal that would be out of my ability during my time in this course would be to re-write the interface and make the whole language far more easy to understand. This would be essentially creating a better version of ContextFree. 

### Related work

_Are there any other DSLs in this domain? If not, describe how you know there
aren't and conjecture why not. If so, describe them and provide links. How well
do they address the need? Are there any particularly admirable qualities of the
language? Are there parts of the language you think could be improved?_

Yes, ContextFree is the primary DSL in this domain. It already does a good job but I definitely think that there are areas in which it could be improved.

## The Project

This section examines whether the idea makes for a good CS 111 project.

### Suitability

_If someone were to work on this project, what percentage of their time would be
spent directly engaging in the **language** aspects of this project (e.g.,
making language design decisions), as opposed to "systems" aspects of the
project (e.g., implementing a complicated semantics that doesn't require a lot
of language design)?_

From my current understanding, 85%/15%

### Scope

_How big an idea is this? How ambitious is this project?_

I would consider this a smaller idea, it seems very achieveable.

### Benefits and drawbacks

_Why might this be a good idea for a project? Why might this not be a good idea
project?_

I think this would be a good project for this class as it would allow me to really engage with a language. Also, since ContectFree is a program that already exists and is used, it may be able to help others beyond myself. It also might be a bad idea because nobody may use it. Do the people who use ContextFree really want this DSL?
