
<h1 align="center">
  Ristorante Con Fusion
</h1>

<h4 align="center">React Web App built from the course <a href="https://www.coursera.org/learn/front-end-react" target="_blank">"Front-end Web Development with React"</a>.</h4>

<p align="center">
    <img src="https://img.shields.io/badge/React-JS-61dafb?style=plastic&logo=react">
    <img src="https://img.shields.io/badge/Redux-JS-764abc?style=plastic&logo=redux">
    <img src="https://img.shields.io/badge/HTML-ES6-e34f26?style=plastic&logo=HTML5">
</p>

<p align="center">
  <a href="#Features">Features</a> •
  <a href="#Setup">Setup</a> •
  <a href="#Takeaways">Takeaways</a>
</p>

![screenshot](https://github.com/thejayden/react-app-ristorante-con-fusion/blob/master/demo.gif)
  
## Features

* Single page application view using react router
  - Instantly see what your Markdown documents look like in HTML as you create them.
* Feedback form input validation 
* Fake live server using JSON-Server with API fetching
* Commenting and viewing live comments
* React animations with stagger and fade

## Setup

To clone and run this application, you'll need [Git](https://git-scm.com) and [Node.js](https://nodejs.org/en/download/) (which comes with [npm](http://npmjs.com)) installed on your computer. From your command line:

```bash
# Clone this repository
$ git clone https://github.com/thejayden/react-app-ristorante-con-fusion

#install json-server
$ npm install json-server -g
```

```bash
# Go into the json-server folder
$ cd json-server
$ json-server --watch db.json -p 3001 -d 2000
```

```bash
# On another command prompt, change directory to repository (the folder where you can see the different folders and files like package.json
$ cd <directory url>
```

_Run using [yarn](https://yarnpkg.com/en/docs/install)_
```bash
$ yarn start
```
_or run using npm_

```bash
$ npm start
```

## Takeaways

* Understanding the fundamental structure and purpose of implementing react.js
  - React solely focuses on the user interface design. How we want to implement other aspects such as servers, databases is independent of react. (technology stack agnostic)
  - Components(presentational, container), elements, state, props, render
* Familiarise with JSX and ES6 syntax, such as the arrow function. 
  - Lists and Keys: iterating over items in array and converting into a list uing the map function
* Implementing various node modules to 
* Understanding uncontrolled and controlled forms
  - Changing from controlled to uncontrolled forms which allows for reference to form values instead of having an event handler for each state update (lesser interaction with react component)
* Using Redux and understanding its basic structure
  - Redux used to implement state based storage 
  - Moving state out of components
  - Reducers, configureStore, Action Creators, Action Types
* Understanding how to fetch data from database(REST API Server) using Fetch API
* Implementing React Animations

  
_All in all, this course gave me a good introduction to starting React.js and the different concepts related to it, especially the concept of having a application state as well as the syntax combing HTML and JS. Although I cannot say I fullly understand and grasp the entirety of what has been taught here, I tried my best to reinforce concepts taught by reading the additional documentations such as those of Redux.js. I am optimistic this course can provide me with a foundation to build up upon._

## Credits

README template edited from [https://github.com/amitmerchant1990/electron-markdownify](https://github.com/amitmerchant1990/electron-markdownify)

---

> The original rpository for my progress thorughout the course can be found [here](https://github.com/thejayden/react-web-dev) &nbsp;&middot;&nbsp;
