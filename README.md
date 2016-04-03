# Osedea Atom Snippets

All our snippets are conforming to our [eslint configuration](https://www.npmjs.com/package/eslint-config-osedea).

* React snippets using ES6
* React-native snippets using ES6
* [Redux ducks](https://github.com/erikras/ducks-modular-redux) snippets

This repo has been inspired a lot by [Websbushka's atom-react-snippets package](https://github.com/webbushka/atom-react-snippets).

## What is a snippet again?

A snippet is a piece of code linked to a shortcut/alias.

In our case, all our snippets' aliases start by `osd` for Osedea so we have for example:

* osdReactClass : Creates a standard ES6 React Class
* osdDuck : Creates a [Duck](https://github.com/erikras/ducks-modular-redux)

But a snippet is a bit more than just a piece of code, it also specify fields that you can fill.

After inserting a snippet, hitting `Tab` will make your cursor jump from field to field.

## Install

* Press `Command + Shift + p`
* Type `Install P`
* Press `Settings View: Install Packages And Themes` or type `return`
* Type `osd-atom`
* Install `osd-atom-snippets`
* Restart Atom
* Fly off!

## Use

Go in a js file and type `osd` and Atom should propose you all of the possible snippets.

After choosing one, press return and it should insert the snippet with the cursor in the first "field".

Hit `Tab` to go from the current "field" to the next "field" of the snippet.


![A screenshot of your package](https://f.cloud.github.com/assets/69169/2290250/c35d867a-a017-11e3-86be-cd7c5bf3ff9b.gif)
