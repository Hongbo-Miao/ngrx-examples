# @ngrx examples

[Angular 2](https://angular.io/) + [ngrx](https://github.com/ngrx) examples, inspired by official [redux examples](https://github.com/rackt/redux/tree/master/examples).

##Goal

These examples illustrate how to utilize ngrx within an Angular 2 application. This repository will be actively maintained and updated as new tools and functionality become available and best practices are established.

##Contributions

As Angular 2 and ngrx are relatively new, patterns and best practices are still being established. Examples found in this repository demonstrate how I (or the project author) would structure the solution but discussion and refinement is always encouraged! Please open an issue, submit a pull request, or drop me a message on [twitter](https://twitter.com/btroncone) to present a different approach or idea. This repository will feature the most solid, agreed upon techniques as they evolve.

Please add any additional Angular 2, ngrx, or reactive programming articles, repositories, or code samples you find useful. I will keep this list as up-to-date as possible!


##Additional Resources
Additional Angular 2, ngrx, and reactive programming articles, repositories, and code samples:

### Introduction
* [Comprehensive Introduction to ngrx/store](https://gist.github.com/btroncone/a6e4347326749f938510) - Brian Troncone
* [Reactive Angular 2 with ngrx](https://www.youtube.com/watch?v=mhA7zZ23Odw) - Rob Wormald
* [@ngrx/store in 10 minutes - egghead.io](https://egghead.io/lessons/angular-2-ngrx-store-in-10-minutes) - Brian Troncone

###Articles
* [Build a Better Angular 2 Application with Redux and ngrx](http://onehungrymind.com/build-better-angular-2-application-redux-ngrx/) - Lukas Ruebbelke
* [Reactive Data Flow in Angular 2](http://blog.lambda-it.ch/reactive-data-flow-in-angular-2/) - Wayne Maurer
* [Understand and Utilize the Async Pipe in Angular 2](http://briantroncone.com/?p=623) - Brian Troncone
* [Communication Between Components & Components Design](http://orizens.com/wp/topics/angular-2-communication-between-components-components-design/) - Oren Farhi

### Presentations and Slides
* [Reactive Angular 2 - NG-NL 2016](https://www.youtube.com/watch?v=xAEFTSMEgIQ) - Rob Wormald
* [Introduction to RxJS 5 - NG-NL 2016](http://slides.com/gerardsans/ng-nl-rxjs5) - Gerard Sans
* [Angular 2 Change Detection Explained](http://pascalprecht.github.io/slides/angular-2-change-detection-explained/#/) - Pascal Precht
* [Angular 2 and the Single Immutable State Tree](https://speakerdeck.com/cironunes/angular-2-and-the-single-immutable-state-tree) - Ciro Nunes

### Videos and Lessons
* [Build Redux Style Applications with Angular2, RxJS, and ngrx/store](https://egghead.io/series/building-a-time-machine-with-angular-2-and-rxjs) - John Linquist
* [Step-by-Step Async JavaScript with RxJS](https://egghead.io/series/step-by-step-async-javascript-with-rxjs) - John Lindquist
* [RxJS Lessons from Ben Lesh](https://egghead.io/instructors/ben-lesh) - Ben Lesh
* [RxJS Beyond The Basics - Creating Observables From Scratch](https://egghead.io/series/rxjs-beyond-the-basics-creating-observables-from-scratch) - André Staltz
* [Introduction to Reactive Programming](https://egghead.io/series/introduction-to-reactive-programming) - André Staltz
* [Getting Started With Redux](https://egghead.io/series/getting-started-with-redux) - Dan Abramov
* [Asynchronous Programming - The End of the Loop](https://egghead.io/series/mastering-asynchronous-programming-the-end-of-the-loop) - Jafar Husain

### Repositories and Code Samples
* [Angular 2 Time Machine](https://gist.run/?id=da0af799da468b7ca70e) - John Lindquist
* [NgRx Sample Project Utilizing Immutable and Normalizr](https://github.com/ngrx/angular2-store-example) - Cody Lundquist
* [NgRx Auth Example](https://github.com/SekibOmazic/ngrx-auth-example) - Sekib Omazic
* [Todo with Undo/Redo](http://plnkr.co/edit/UnU1wnFcausVFfEP2RGD?p=preview) - Rob Wormald
* [Angular2 Seed with ngrx-store, store-saga and ngrx-DevTools](https://github.com/Lube/angular2-seed) - Sebastian Luberriaga
* [NgRx Dev Tools First Look](http://plnkr.co/edit/Hb4pJP3jGtOp6b7JubzS?p=preview) - Rob Wormald
* [Tour of Heroes](https://github.com/JonCubed/angular2-ngrx-tour-of-heroes-aspnet-core-vs2015) - Jonathan Kuleff

### Middleware
* [store-saga - Rx implementation of redux-saga for @ngrx/store](https://github.com/MikeRyan52/store-saga) - Mike Ryan
* [ngrx-store-localstorage - Sync local storage with ngrx state slices](https://github.com/btroncone/ngrx-store-localstorage) - Brian Troncone
* [ngrx-store-logger - Advanced action/state logging for @ngrx/store applications](https://github.com/btroncone/ngrx-store-logger) - Brian Troncone
* [ngrx-store-router - Sync between the current Angular 2 Router URL and @ngrx/store](https://github.com/CodeSequence/ngrx-store-router) - Brandon Roberts

##Getting Started
```bash
# clone the repo
git clone https://github.com/btroncone/ngrx-examples.git

# cd into repo
cd ngrx-examples

# cd into project of your choice
cd counter

# install dependencies
npm install

# start the server
npm start
```

##Build

Project builds are a stripped down version of [Angular Class Webpack Starter](https://github.com/AngularClass/angular2-webpack-starter), an exceptional Angular 2 seed project. Tests can be executed with either [WallabyJS](http://wallabyjs.com/) or Karma (soon!).

##Examples

### Counter
([source](https://github.com/btroncone/ngrx-examples/tree/master/counter))
#####Summary
A counter which can be incremented, decremented, with the option to increment or decrement async.
#####Demonstrates
1. Creating a basic reducer
2. Selecting a slice of state 
3. Using the async pipe
4. Dispatching actions from a component

### Todos
([source](https://github.com/btroncone/ngrx-examples/tree/master/todos))
#####Summary
Basic todo application with add, remove, and toggle complete functionality. 
#####Demonstrates
1. Initial reducer state
2. Managing arrays in reducers
3. Multiple reducers
4. Combining data from two reducers to project state for view

### Todos with Undo/Redo
([source](https://github.com/btroncone/ngrx-examples/tree/master/todos-undo-redo) | [plunker](http://plnkr.co/edit/UnU1wnFcausVFfEP2RGD?p=preview))
#####Summary
Same as todos example but with undo/redo functionality.
#####Demonstrates
1. Creating a meta-reducer to add undo/redo capability.

### Async 
([source](https://github.com/btroncone/ngrx-examples/tree/master/async))
#####Summary
Request and display the latest Angular or React reddit posts, utilizing the reddit API.
#####Demonstrates
1. Handling async actions with RxJS
2. Conditionally taking action based on current state

### Shopping Cart 
([source](https://github.com/btroncone/ngrx-examples/tree/master/shopping-cart))
#####Summary
Coming soon...
#####Demonstrates
Coming soon...

### Real World - In Progress!

### More to Come!
