![React Intro](http://i.imgur.com/yH3JkIH.png)

Learn React.js for *high performance* JavaScript applications.


## Why?

Deciding which framework/library to adopt for your Web App can be
a *daunting* task. There are *litterally* hundreds of of
Frameworks available




We had a few criteria for choosing a

## *What*?



### Videos:

#### Intro to React

Introduction to React.js (**2 hours**) - A good history lesson of why *Facebook* built React.
[![Introduction to React.js](https://cloud.githubusercontent.com/assets/194400/12367017/f114d87a-bbd6-11e5-9e7d-2510aa66ca57.png)](https://youtu.be/XxVg_s8xAms "Introduction to React.js")

#### Hot Reloading with Time Travel

If you have built web apps and felt the pain of having to
re-start each time a change is made you will identify with this:

[![Live React: Hot Reloading with Time Travel](https://cloud.githubusercontent.com/assets/194400/12371630/f7c3c758-bc30-11e5-949a-7b8c9f957269.png)](https://youtu.be/xsSnOQynTHs "Live React: Hot Reloading with Time Travel")


#### Rethinking Best Practice

**Pete Hunt**'s ***React: Rethinking Best Practices***
gives a good (*although biased*) overview of how React is different:
[![Pete Hunt: React: Rethinking best practices -- JSConf EU 2013](https://cloud.githubusercontent.com/assets/194400/12365803/050e1ff6-bbcf-11e5-8f27-80884b7530c4.png)](https://youtu.be/x7cQ3mrcKaY "Pete Hunt: React: Rethinking best practices -- JSConf EU 2013")

#### Key Takeaways:

+ ***Components***, not Templates
+ Re-render, ***don't mutate***
+ **Virtual DOM** is *simple* and *fast*


### Reading:

- Getting started: http://facebook.github.io/react/docs/getting-started.html
(recommends using [JSX](http://jsx.github.io) which is quite bleeding-edge)
- Tutorial: http://facebook.github.io/react/docs/tutorial.html


## Overview

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

+ *Introduction* to React.js: https://www.youtube.com/watch?v=XxVg_s8xAms (*linked to above*)
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

React Native enables you to build on native platforms using a consistent developer experience based on JavaScript and React.

+ React.js Conf 2015 Keynote: http://youtu.be/KVZ-P-ZI6W4
+ https://facebook.github.io/react-native/
+ Things I wish I were Told About React Native: http://ruoyusun.com/2015/11/01/things-i-wish-i-were-told-about-react-native.html

> Tip: *Ask* [Niki](https://github.com/nikhilaravi),
[Jack](https://github.com/jrans),
[Bes](https://github.com/besarthoxhaj)
& [Izaak](https://github.com/izaakrogan) about their
*experience* using React Native to *ship* their first ***iOS App***!

## Background Reading

+ React vs. Web Components (Polymer):
http://programmers.stackexchange.com/questions/225400/pros-and-cons-of-facebooks-react-vs-web-components-polymer
+ "***React Is A Terrible Idea***":
https://www.pandastrike.com/posts/20150311-react-bad-idea
+ Thinking in React, a step by step screencast tutorial:
https://youtu.be/mFEoarLnnqM + http://tagtree.tv/thinking-in-react
(*note: uses older version of React...*)
+ WebPack Started for Designers:
https://github.com/ArmendGashi/Webpack-starter-for-designers
+ React.js isn’t terrible, but it’s not perfect either:  https://medium.com/@MostlyHarmlessD/react-js-isn-t-terrible-but-it-s-not-perfect-either-8e0065cb2bf8
+ React + Performance = ? (*in-depth article about React vs. Vanilla JS perf): https://aerotwist.com/blog/react-plus-performance-equals-what/
+ ***Slant*** *Comparison* of Web UI Frameworks:
http://www.slant.co/topics/3286/~javascript-libraries-for-building-a-ui (*Riot still beats React!*)

## Good Features

+ Good Developer Tools & Workflow

## The Bad Parts

React was ***not*** our ***first choice*** for
building web applications because it is not built around the
**Web Components** ***Standard*** (*the way Polymer is...*)
and has *several*
conventions which are *traditionally* considered "***anti-patterns***":
+ "in-line styles" (*in markup*)
+ "CSS in JS" (*see below*)
+ "in-line `onClick` event handlers"
+ Use of `this` context object/keyword *everywhere* (*why is this bad?*)
+ Components mix HTML/JSX Templates in JavaScript

We *understand* and *acknowledge* that in Facebook's case
it makes sense to include all the code (HTML/JSX, CSS & JavaScript)
in a *single place* as a *Component*.
When you have *many* (*tens/hundreds*) of people
editing your app it can make sense to have everything in
the same place.

We think React Components *can* (*should*) be written
with [***accessibility***] in mind and that's where our
example code differs from that of other tutorials.


### Inline Styles

[***Inline Styles***](http://facebook.github.io/react/tips/inline-styles.html)
Facebook *officially* recommends that people define their
style as a JavaScript Object e.g:
```js
var divStyle = {
  color: 'white',
  backgroundImage: 'url(' + imgUrl + ')',
  WebkitTransition: 'all', // note the capital 'W' here
  msTransition: 'all' // 'ms' is the only lowercase vendor prefix
};

ReactDOM.render(<div style={divStyle}>Hello World!</div>, mountNode);
```
![react-css-in-js](https://cloud.githubusercontent.com/assets/194400/12389043/5fea3058-bdce-11e5-97ab-d412bc4a40ef.png)

> Read: ***Please, Please Don’t Use “CSS in JS***” *by* [Alex Sharp](https://github.com/ajsharp):
https://medium.com/@ajsharp/please-please-don-t-use-css-in-js-ffeae26f20f
> and: https://speakerdeck.com/vjeux/react-css-in-js

### tl;dr

We consider React to be a "*temporary solution*" to the
problem of building re-useable web components that can be
rendered on the Server and (*Progressively*) Enhanced on the Client.
We *expect* a new *Standards-based* Approach to emerge in the
next 18 months and will adopt it with open arms...
(*if you know where such a framework/library/pattern is
  being developed please share a link with us!*)
