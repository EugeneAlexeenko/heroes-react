# Tour of Heroes

This project was created to help represent a fundamental app written with React. The heroes and villains theme is used throughout the app.

by [John Papa](http://twitter.com/john_papa)

Comparative apps written with Vue and Angular can be found at at [github.com/johnpapa/heroes-vue](https://github.com/johnpapa/heroes-vue) and [github.com/johnpapa/heroes-angular](https://github.com/johnpapa/heroes-angular)

## Why

I love JavaScript and the Web! One of the most common questions I hear is "which framework is best?". I like to flip this around and ask you "which is best for you?". The best way to know this is to try it for yourself. I'll follow up with some articles on my experiences with these frameworks but in the meantime, please try it for yourself to gain your own experience with each.

## Live Demos

Hosted in [Azure](https://aka.ms/jp-free)

- [Tour of Heroes with Angular](https://papa-heroes-angular.azurewebsites.net)
- [Tour of Heroes with React](https://papa-heroes-react.azurewebsites.net)
- [Tour of Heroes with Vue](https://papa-heroes-vue.azurewebsites.net)

## Getting Started

1. Clone this repository

   ```bash
   git clone https://github.com/johnpapa/heroes-react.git
   cd heroes-react
   ```

1. Install the npm packages

   ```bash
   npm install
   ```

1. Run the app!

   ```bash
   npm run quick
   ```

## Cypress Tests

1. You can execute all of the UI tests by running the following steps

   ```bash
   npm run cypress
   ```

## What's in the App

Each of these apps contain:

- routing
- lazy loading
- container/presenter components
- redux state management pattern
- The same CSS

### Why Cypress?

Cypress.io makes it easy to run all three apps simultaneously in end to end tests, so you can watch the results while developing.

### Why abstracted CSS?

The goal of the project was to show how each framework can be designed to create the same app. Each uses their own specific techniques in a way that is tuned to each framework. However the one caveat I wanted to achieve was to make sure all of them look the same. While I could have used specific styling for each with scoped and styled components, I chose to create a single global styles file that they all share. This allowed me to provide the same look and feel, run the same cypress tests, and focus more on the HTML and JavaScript/TypeScript.

### Why JSON Server?

The app uses a JSON server for a backend by default. This allows you to run the code without needing any database engines or cloud accounts. Enjoy!

### Why Docker?

You can host the app any way you prefer. I chose Docker because it is familiar to me and makes it easy to run anywhere (local or cloud). You do you though and feel free to run this in yur own way.

## Problems or Suggestions

[Open an issue here](/issues)

## Thank You

Thank you to [Sarah Drasner](https://twitter.com/), [Brian Holt](https://twitter.com/), [Chris Noring](https://twitter.com/), [Craig Shoemaker](https://twitter.com/), and [Ward Bell](https://twitter.com/wardbell) for providing input and reviewing the code in the three repos for the Angular, React, and Vue apps:

- [heroes-angular](https://github.com/johnpapa/heroes-angular)
- [heroes-react](https://github.com/johnpapa/heroes-react)
- [heroes-vue](https://github.com/johnpapa/heroes-vue)

## Resources

- [VS Code](https://aka.ms/codeit)
- [Azure Free Trial](https://aka.ms/jp-free)
- [VS Code Extension for Node on Azure](https://aka.ms/vsc-node)
- [VS Code Extension Marketplace](https://aka.ms/jp-codeext)
- [VS Code - macOS keys](https://aka.ms/jp-code-mackeys)
- [VS Code - Windows keys](https://aka.ms/jp-code-winkeys)

### Debugging Resources

- [Debugging Angular in VS Code](https://aka.ms/debug-angular)
- [Debugging React in VS Code](https://aka.ms/debug-react)
- [Debugging Vue in VS Code](https://aka.ms/debug-vue)
