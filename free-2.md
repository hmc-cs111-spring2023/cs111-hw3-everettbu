# Free project 2

## The user and a language

This section describes who the project would serve and why a language might be a
good way to meet their needs.

A DSL may he helpful to write smart contracts (the core of applied blockchain technology). Currenlty the programming languages that can interact with the blockchain network are relativly new and not fully built out yet. When learning how to write in these languages, the syntax of writing a smart contract can be confusing at first. I hope to solve this problem by implmenting a DSL that makes writing simple smart contracts an easy task.

### What's the need?

_What need is met by your idea? Who are you helping? What is that person's
experience like now? What would their experience be like if you could help
them?_

This DSL will help people code on the blockchain, simply and visually. Currenly, when writing in a programming language such as Solidity (the primary language with Ethereum), smart contracts are confusing to understand and implement. If I am able to help, this experience will be completly changed as a user will be able to use simple building blocks to implement smart contract code. 

### Why a language?

_Why is a DSL appropriate for your user(s)? How does it address the need?_

From my understanding, many smart contracts have the same general structure in their implementation. Since I belive that this structure should be simplifed for the sake of it users, it would be appropriate to implement a DSL to re-write the way a user views this code. It would address the need of making simple smart contracts able to be read, wrote and understood by all.

### Why you?

_What excites you about this idea? How did you come up with it?_

This idea excites me since I am very enthusiastic about blockchain technology and have personal experience learning and attempting to write simple smart contracts in Solidity. I came up with this idea when reflecting on times that I struggled as a coder. Since this branch of coding is still realtivly new, I believe it would be a great space to introduce a DSL as one like it may not exist yet.

### Domain

_Describe the project's domain in five words._

Solidity smart contracts made simple

### Interface (syntax)

_How might the user interact with the language? What does programming look
like? Why is this the right way to interact with the problem domain?_

The user would interact with the language by specifiying their needs, and choosing from a template to work with. My goal is to make the coding process as cut and paste as possible, with the ability to tweak the blocks that the DSL provides for advanced use. The langage would also prompt the user with questions about the task that they are hoping to complete (names of variables and whatnot) and auto-fill the smart coctract template with these answers. The right way to interact with the language would be to have a clear understanding of the task at hand, and use my DSL as a way to easily get started. This provides a solution for the problem domain as it will allow for smart contract to be written with less difficulty.


### Operation (semantics)

_What might happen when a program runs? How does a program interact with the
user? What kinds of errors might occur, and how might they be communicated to
the user?_

When the program runs, the user will have the ability to tell it that they want to write a smart contract. When prompted, the program will ask what kind of smart contract the user wants to write, and collect the information needed to do so. If the user does not give the program clear instructions, it will throw an error, pointing to the response that it can not complete with the information given. If run properly, the program will return a smart contract written for the user with their specified constraints.

### Expressiveness

_What should be easy to do in this language? What should be possible, but
difficult? What should be impossible or very difficult?_

It should be easy to create simple smart contract within a larger program. It would be possible but harder to create complex smart contracts, or write the outline for enitre Solidity projects. It would be nearly impossible to also automatically connect the user to the blockchain, this will always be a step that they will have to complete and understand how to do.

### Related work

_Are there any other DSLs in this domain? If not, describe how you know there
aren't and conjecture why not. If so, describe them and provide links. How well
do they address the need? Are there any particularly admirable qualities of the
language? Are there parts of the language you think could be improved?_

I just learned this, but apparently Solidity (the host language I hope to build on) is a DSL its self, written in C++. Here's an intresting quote I pulled from a reddit thread; "Solidity is a DSL. DSLs have their purposes and this happened to be a correct purpose. It just also happens to be that Solidity is a terribly designed language." This might not directly answer any of the questions for this section but it does show why this is a problem domain.

To get back on topic, I could not find any DSL's in the domain of making Solidity easier to interact with. The article I linked below is a great resource to understand how smart contracts are written and their current syntactical limitations. It reflects on Solidity and generates suggestions for how it could be improved. One of the points that it covers introduces a debate whether natural languages are the solution.
https://tomassetti.me/domain-specific-languages-for-contacts/

## The Project

This section examines whether the idea makes for a good CS 111 project.

### Suitability

_If someone were to work on this project, what percentage of their time would be
spent directly engaging in the **language** aspects of this project (e.g.,
making language design decisions), as opposed to "systems" aspects of the
project (e.g., implementing a complicated semantics that doesn't require a lot
of language design)?_

From my current understanding, I would say %50/%50 (I might be completely wrong though)

### Scope

_How big an idea is this? How ambitious is this project?_

I would say that this project is a medium big idea with the potential to grow to large if I wanted to take it that far. On a scale from 1-10 I would say that it is 6 ambitious. However, I might just feel this way because it seems like a daunting task at the moment, it maight actually be simple with a little bit of instruction.

### Benefits and drawbacks

_Why might this be a good idea for a project? Why might this not be a good idea
project?_

 There is clearly a need to improve widely used DSLs such as Solidity for a number of reasons. I think it would be a great idea for a project since it addressed an actual need that is expressed by many people online. However, there are reasons that I would be hesitant to chose this project, mainly because it would require me to first become familiar enough with Solidity (which might be hard because it isn't very widespread yet) and it might be an ambitious task to take on.
 
