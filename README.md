![React Intro](http://i.imgur.com/yH3JkIH.png)

Learn React.js for *high performance* JavaScript applications.

## Start

- Getting started: http://facebook.github.io/react/docs/getting-started.html
(recommends using [JSX](http://jsx.github.io) which is quite bleeding-edge)
- Tutorial: http://facebook.github.io/react/docs/tutorial.html


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

+ Main Site: http://facebook.github.io/react/
+ Getting Started: http://facebook.github.io/react/docs/getting-started.html
+ Thinking in React: http://facebook.github.io/react/docs/thinking-in-react.html
+ Overview (Flux): http://facebook.github.io/flux/docs/overview.html
+ GitHub: https://github.com/facebook/react

### Video

+ *Introduction* to React.js: https://www.youtube.com/watch?v=XxVg_s8xAms
+ *Thinking* in React: http://tagtree.tv/thinking-in-react (click "maybe later" for video to start)
+ Main List: https://facebook.github.io/react/docs/videos.html
+ Building UIs with ReactJS: http://youtu.be/lAn7GVoGlKU?t=51s
+ *High performance* functional programming with **React** *and* **Meteor**:
https://www.youtube.com/watch?v=qqVbr_LaCIo
+ React's Architecture: https://www.youtube.com/watch?v=eCf5CquV_Bw
+ Getting Started with React.js: ~~ https://www.youtube.com/watch?v=6ho8aOPUYxs ~~
http://code.tutsplus.com/courses/getting-started-with-reactjs
(I Paid the $15 for the course - let me know if you need access)



## What?

react.min.js (minified!) is ***124kb***!
see: http://facebook.github.io/react/downloads.html
specifically: http://fb.me/react-0.11.2.min.js

### Resources

- Great list of React.js resources: https://github.com/enaqx/awesome-react

### Components not Templates

> http://css-tricks.com/modular-future-web-components

### Server-Side Rendering

+ https://www.npmjs.com/package/react-server-example
+ http://maketea.co.uk/2014/06/30/building-robust-web-apps-with-react-part-4.html


## Testing with JEST

+ GitHub Repo for Jest CLI: https://github.com/facebook/jest
+ Get Started: http://facebook.github.io/jest/docs/getting-started.html
+ Tutorial: https://facebook.github.io/jest/docs/tutorial.html
+ API: https://facebook.github.io/jest/docs/api.html
+ Testing Flux Apps: http://facebook.github.io/react/blog/2014/09/24/testing-flux-applications.html

### Test Coverage

+ http://stackoverflow.com/questions/28283371/how-to-get-test-coverage-from-jest-while-testing-react-js-app

## React Native

- React.js Conf 2015 Keynote: http://youtu.be/KVZ-P-ZI6W4
