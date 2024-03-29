![React Intro](https://i.imgur.com/yH3JkIH.png)

Learn React.js for *high performance* JavaScript applications.

## Start

- [Getting started](https://reactjs.org/docs/getting-started.html)
(recommends using [JSX](https://jsx.github.io) which is quite bleeding-edge)
- [Tutorial](https://reactjs.org/tutorial/tutorial.html)


## Background

React is a JavaScript library for building user interfaces.

+ **Just the UI:** Lots of people use React as the V in MVC.
Since React makes no assumptions about the rest of your technology stack,
it's easy to try it out on a small feature in an existing project.
+ **Virtual DOM:** React uses a *virtual DOM* diff implementation
for ultra-high performance. It can also render on the server using
Node.js — no heavy browser DOM required.
  * This means that every time something changes, React creates a _virtual_ DOM tree, checks for the differences between that and the existing DOM and then re-renders **only the differences** to the DOM
+ **Data flow:** React implements one-way reactive data flow which reduces
boilerplate and is easier to reason about than traditional data binding.


### Reading

+ [Main Site](https://reactjs.org/)
+ [Getting started](https://reactjs.org/docs/getting-started.html)
+ [Thinking in React](https://reactjs.org/docs/thinking-in-react.html)
+ [Overview (Flux)](https://facebook.github.io/flux/docs/overview)
+ [GitHub](https://github.com/facebook/react)

### Video

+ *Introduction* to React.js: https://www.youtube.com/watch?v=XxVg_s8xAms
+ *Thinking* in React: https://tagtree.tv/thinking-in-react (click "maybe later" for video to start)
+ Main List: https://facebook.github.io/react/docs/videos.html
+ Building UIs with ReactJS: https://youtu.be/lAn7GVoGlKU?t=51s
+ *High performance* functional programming with **React** *and* **Meteor**:
https://www.youtube.com/watch?v=qqVbr_LaCIo
+ React's Architecture: https://www.youtube.com/watch?v=eCf5CquV_Bw
+ React JS Crash Course: https://www.youtube.com/watch?v=w7ejDZ8SWv8



## What?

react.min.js (minified!) is ***~12kb***!
see: https://github.com/facebook/react/
specifically: https://unpkg.com/react@17.0.2/umd/react.production.min.js

### Resources

- Great list of React.js resources: https://github.com/enaqx/awesome-react

### Components not Templates

> https://css-tricks.com/modular-future-web-components/

### Server-Side Rendering

+ https://www.npmjs.com/package/react-server-example
+ https://www.matthinchliffe.dev/2014/06/30/building-robust-web-apps-with-react-part-4.html


## Testing with JEST

+ GitHub Repo for Jest CLI: https://github.com/facebook/jest
+ [Get Started](https://jestjs.io/docs/getting-started)
+ [API](https://jestjs.io/docs/api)
+ [Testing Flux Apps](https://reactjs.org/blog/2014/09/24/testing-flux-applications.html)

### Test Coverage

+ https://stackoverflow.com/questions/28283371/how-to-get-test-coverage-from-jest-while-testing-react-js-app

## React Native

- React.js Conf 2015 Keynote: https://youtu.be/KVZ-P-ZI6W4
