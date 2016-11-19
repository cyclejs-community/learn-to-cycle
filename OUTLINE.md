# Title: Cycle.js
*Build reactive Human-Computer Interaction(HCI) applications that are easy to extend, compose and test, with cleaner code and greater separation of concerns*

***


## Audience
### Reader’s expected knowledge
- General knowledge of front-end development
- Familiarity with HTML, CSS, and JavaScript
- Familiarity with ES2015
- Familiarity with using the terminal to install and run npm packages in a Node.js environment.
- No experience with functional programming
- No previous knowledge about Observables
- No experience with RxJS or any other functional reactive stream library

### Reader’s motivation
Learn how to create reactive Human-Computer Interaction(HCI) applications that are easy to extend, compose and test, with cleaner code and greater separation of concerns.


## Mission
### About the book’s topic
The book focuses on Cycle.js: A functional and reactive JavaScript framework for cleaner code.

#### How Cycle.js works and what makes it different from its alternatives
While most front-end frameworks focus on Graphical User Interfaces, Cycle.js introduce a message passing architecture to model Human-Computer Interaction(HCI) in a more holistic way, making it suitable to create any kind of Human-Computer Interaction like Web Audio components and network requests components just to name a few.

To do so, Cycle.js glue together functional and reactive programming paradigms exposing an architecture for cleaner code and greater separation of concerns. Apps are created as pure functions, making aspects like testing and server-side rendering trivial. Their internals are built around Reactive programming constructs, resulting in greater separation of concerns and cleaner, simplified code related to events, asynchrony, and errors.

Because of its fractal architecture, every Cycle.js app, is simply a function that can be reused in any other Cycle.js app.

#### Why is it important now? 
Observables are here to stay.

Netflix is partly built around them. They are used as primitives in various reactive streams libraries (i.e. RxJS) and can be found in various codebases: from Angular2 to Falcor, from Horizon.io to Mobx. An ECMAScript proposal for Observables is now at stage0. Yet, put aside books focusing on the RxJS library, It’s hard to find written material explaining how to build real applications with such constructs.

Cycle.js is one of the first fully reactive frameworks to suggest best practices and design patterns around those reactive primitives. Pushing the state of unidirectional data-flow architectures further. 

Given the rising popularity of functional reactive programming together with the growing of the Cycle.js community this book represent an important missing piece to help developers master the observable type, easily use functional reactive stream libraries, learn design patterns that can be applied to any Human-Computer Interaction application and write cleaner code that is easier to test and reason about.

### About the book
#### Core issues/challenges this book is going to address
Getting started with Cycle.js and FRP, in general, can scare away developers. Streams can be scary at a first sight, functional programming concepts might sound new and the reactive paradigm forces us to reason in a new way. Furthermore, picturing how to put all this together in order to write better apps can be a non-trivial task adding up developer’s fatigue. Cycle.js and this book address all of this, plus more by taking the readers through a journey aimed to prove those common misconceptions to be wrong.

#### The journey that this book will take the readers on.

- **Basics of Functional and Reactive Programming**: Our journey starts with explaining the Basics of functional and reactive programming, explaining concepts like purity, read/write effects and separation of concerns.
- **Data Streams fundamentals**: In this part we introduce the reader to the Observable Type, explaining what problems it solves and how can we build stream libraries with it. By the end of this part, the reader will have implemented his own toy version of a functional reactive stream library.
- **Cycle.js fundamentals**:  Cycle.js framework come with very few concepts to learn. Similarly to what we did in the “data streams fundamentals” part, we’ll go through implementing a toy version of Cycle.js core API in order to explain the problems it solve. By the end of this part, the reader will be comfortable with concepts, like run, drivers and sources/sinks.
- **Cycle.js core**: Each chapter in this part of the book will go through building a small project with Cycle.js. Each time we’ll focus on a different specific core aspect:
    -  Model View Intent pattern
    -  Building reusable components with isolate
    -  Building your own Cycle.js drivers
- **Cycle.js advanced**: This final part of the book will help the reader mastering Cycle.js by going through advanced and often asked topics 
    - Server Sider Rendering
    - Testing
    - State Management
    - Routing
    - Integrating Cycle.js Apps in current projects 


## Objective and achievements
After reading this book, the reader will be able to:
- Work with observable sequences.
- Implement and use functional reactive stream libraries
- Write clean, pure and maintainable code
- Create reusable Cycle.js components
- Write Cycle.js drivers for handling side effects
- Use server-side rendering to make applications load faster
- Write tests for Cycle.js applications
- Master advanced Cycle.js patterns and best practices
- Integrate Cycle.js alongside current projects


## General Structure

## Detailed outline