# Intro to React Sprint Challenge

**Read these instructions carefully. Understand exactly what is expected _before_ starting this Sprint Challenge.**

This challenge allows you to practice the concepts and techniques learned over the past sprint and apply them in a concrete project. This sprint explored **introductory React**. During this sprint, you studied **React components and advanced styling**. In your challenge this week, you will demonstrate your mastery of these skills by creating **a web page with character components**.

This is an individual assessment. All work must be your own. Your challenge score is a measure of your ability to work independently using the material covered through this sprint. You need to demonstrate proficiency in the concepts and objectives introduced and practiced in preceding days.

You are not allowed to collaborate during the sprint challenge. However, you are encouraged to follow the twenty-minute rule and seek support from your TL if you need direction.

_You have **three hours** to complete this challenge. Plan your time accordingly._

## Introduction

In this challenge, create a web page that presents a styled list of characters obtained from an API. Being able to render out data to a web page is a large part of what JavaScript developers do, this challenge assesses your ability to achieve such a task.

In meeting the minimum viable product (MVP) specifications listed below, your project might look somewhat similar to the solution examples below:

[Example](https://tk-assets.lambdaschool.com/b011a132-0916-4ed2-8955-14192de03a75_sample-screenshot.png)

[Another example](https://tk-assets.lambdaschool.com/3b82c793-2352-4d4d-a81d-e55bf350f7bd_sample-screenshot2.png)

### Commits

Commit your code regularly and meaningfully. This helps both you (in case you ever need to return to old code for any number of reasons) and your team lead as the evaluate your solution.

## Interview Questions

Be prepared to demonstrate your understanding of this week's concepts by answering questions on the following topics. You might prepare by writing down your own answers before hand.

1. What is React JS and what problems does it solve? Support your answer with concepts introduced in class and from your personal research on the web.
_React is a library for building applications, which allows us to alter styling, html and affect the DOM in a significantly easier manner than through using vanilla JS and DOM.  Also, React gives an easy way to keep track of what affects what (styling), since it uses components and you can alter CSS on the same page._

1. Describe component state.
_just like how the state of a soccer game may be 1-1 at any given moment, state lets us set a constant in reference a certain state/status, and change it through a function we create.  Using state tells react to re-render a specified component when the state object changes._

1. Describe props.
_Props (in terms of their syntax) work similarly to parameters/arguments in vanilla JS, and are reminiscent of using callbacks/higher order functions.  In react, we use props to pass properties in a direction to other components._

1. What are side effects, and how do you sync effects in a React component to changes of certain state or props?
_Side effects affect something outside of the scope of the current function.  We can see this when we use them to get API data or affect the DOM.  They are especially beneficial for syncing with components.  Syncing is done by passing a dependency array with .then .catch_

You are expected to be able to answer questions in these areas. Your responses contribute to your Sprint Challenge grade.

## Instructions

### Task 1: Project Set Up

- [x] Create a forked copy of this project
- [x] Add your team lead as collaborator on Github
- [x] Clone your OWN version of the repository (Not Lambda's by mistake!)
- [x] Create a new branch: `git checkout -b <firstName-lastName>`.
- [x] Run `npm install` to retrieve all needed dependencies.
- [x] Once you have installed the _node_modules_, run `npm start` to get your server up and running.
- [x] With the server up and running, open Chrome and head over to `localhost:3000` and view your beautiful app. Maybe it's not _that_ pretty... _yet_, your goal is to ensure this project becomes a thing of beauty.
- [x] Implement the project on your newly created `<firstName-lastName>` branch, committing changes regularly
- [x] Push commits: `git push origin <firstName-lastName>`

### Task 2: Project Requirements

Your finished project must include all of the following requirements:

- [x] Use ONE of the following APIs:
  - [Star Wars API](https://swapi.dev/)
  - [Alternate Star Wars API](https://swapi.py4e.com/)
  - [The Rick and Morty API](https://rickandmortyapi.com/)
  - [The RESTful Pokémon API](https://pokeapi.co/) (**harder**)
- [x] Use the documentation and Google to learn how to fetch characters from your API.
- [x] Obtain a list of characters. One or several requests might be needed, depending on the API.
- [x] Set the list of characters into state.
- [x] Render your characters to the screen:
  -_check_ Build a React component named 'Character' to render an individual character.
  - Map over the list in state, and for each character render a Character to the page.
  - You must display at least one element for each character in the data set.
  - The elements must be styled with **styled-components** - don't rely on browser default styles.

### Required best practices

- [x] Consistent naming. Examples: variables, functions, Components, and file/folder organization.
- [x] Consistent spacing. Examples: line breaks, around arguments and before/after functions.
- [x] Consistent quotation usage.
- [x] Spell-check.
- [x] Schedule time to review, refine and reassess your work.

It is better to submit a challenge that meets [MVP](https://en.wikipedia.org/wiki/Minimum_viable_product) than one that attempts too much and fails.

### Tips and Gotchas

- [x] Test your API and inspect the data in Chrome, Postman or HTTPie _before_ writing the code for the request(s). See screenshots at the root of the project.
- [x] Try not to hammer your API while developing. Infinite loops in your code might trigger hundreds of requests!
- [x] The Pokemon API is a slightly harder challenge because a single network request might not be enough to get all the data you need.
- [x] Running `npm` commands in the wrong folder will not work. **Be aware of what folder you're in** when working in the command line.
- [x] The `start` process can sometimes choke after adding new dependencies and may need to be restarted.

In your solution, it is essential that you follow best practices and produce clean and professional results. You will be scored on your adherence to proper code style and good organization. Schedule time to review, refine, and assess your work and perform basic professional polishing including spell-checking and grammar-checking on your work. It is better to submit a challenge that meets MVP than one that attempts too much and does not.

### Task 3: Stretch Goals

After finishing your required elements, you can push your work further. These goals may or may not be things you have learned in this module but they build on the material you just studied. Time allowing, stretch your limits and see if you can deliver on any the following optional goals:

- [ ] Make the Character component more complex and break it into several subcomponents.
- [ ] Create a helper function in separate module to remove unneeded information from the API data, before putting it in state.
- [ ] Use Promise.all to resolve an array of promises.
- [ ] Create transitions or animations with styled-components.

## Submission format

Follow these steps for completing your project.

- [ ] Submit a Pull-Request to merge `<firstName-lastName>` Branch into `main` branch (student's Repo). **Please don't merge your own pull request**
- [ ] Add your team lead as a reviewer on the pull-request
- [ ] Your team lead will count the project as complete after receiving your pull-request
