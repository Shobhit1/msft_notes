# React vs Angular

## What is React

In one line, React is a JavaScript library for building user interfaces. It is maintained by Facebook, instagram and a community of individual developers and corporations.

## What is Angular

`Angular` is a complete framework either for web or mobile with everything you need for building scalable applications available out of the box. It is built and maintained by a Google’s team, as well as by multiple developers’ communities.

## Major differences between React and Angular

### Data-Binding

- `Angular` allows us two way data binding, even though they dont recommend it, Its still possible.
- In React, any changes you make to the model affect the view, but not the other way around. This way, the data only flows in one direction. Its called Unidirectional flow, this helps us in creating good scalable UIs.

### DOM Usage

- `Angular` uses the browser's DOM, while React uses a virtual DOM.
> Understand React's Virtual DOM in this amazing [video](https://www.youtube.com/watch?v=-DX3vJiqxm4).

### Language Used

- `Angular`, as a framework uses Typescript while React (can work with TS) recommends and work better with ES6 Javascript and JSX.

## React in terms of Service Desk

### Responsive Design

- With `ReactJS`, dynamic pages are very fast and responsive. Pages like Insights, Case Tables, Graphs, Knowledge Search Results will perform better. Its use of Virtual DOM and batch updates almost guarantees 4X better performance than current page and better than `Angular`.
- `Angular` has a lot of new checks using `Zone.js` but this doesn't even come close to what Virtual DOM does for React.
> Just a small community answer on SO gives us some insight on Zone / Virtual DOM ([HERE](https://stackoverflow.com/a/45697321/3711475)).

### Offline Architecture

- `ReactJS` offers us strong offline webapp inclinations, which can be achieved through `Angular` as well, using PWA.
- Interesting thing about PWA is the fact that Microsoft Store now supports it and thus makes our life easier in terms of adoption and delivery.

### Flexibility / ReactJS being just a library

- The fact that `ReactJS` is just a library is a positive as well as negative. On one hand, React being a library (and a small one at that - production version), it gives us a lot of room for following things:
  - improve our bundle size and keep our code clean
  - use other awesome open source libraries to acheieve success - Redux, MobX, axios etc.
  - Avoid some pitfalls and boundations that come with using a framework.
- Now, for the disadvantages, since this is not a framework, managing state, HTTP and everything becomes a task in itself. The decisions around other libraries become tough and following standards for each library just increases the complexity of development.

### Easy to master / Learning Curve

- `ReactJS` is just a simple Javascript library and a JS developer should not take much time to get his feet wet. The learning curve includes:
- JSX is an HTML analogue with a full power of JavaScript
> Read more about [JSX](https://reactjs.org/docs/introducing-jsx.html)

- In terms of our App / Team, we are much more aligned to learn and develop Angular stuff quicker and since we are already using `Angular v1.5.6`, `components` and `Typescript`; we are already more than halfway through on learning Angular.

### Why upgrading to Angular suits us better

- Our code is more than halfway close to Angular, we are already using a lot of new concepts like Typescript, Component based UI development etc.
- React is closer to the functional programming paradigm in JavaScript, which may cause difficulties for developers that come from classical language background, like `C#`
- With React, we have to write a lot of boilterplate code and if we involve Redux for state management, it further adds up the boilerplate. This can become a pain when upgrading our codebase, because everything that is written right now needs to be updated.
- The dependency graph and the large number of npm libraries that get involved with `ReactJS` based development can cause a lot of depedency management chaos.

> Video comparing Angular and React Performance - [You Tube](https://www.youtube.com/watch?time_continue=869&v=-DX3vJiqxm4)
>
