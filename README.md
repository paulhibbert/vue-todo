# vue-todo

## Basic todo app using Vue.js version 2 from August 2018

Dependencies: [Vue-Draggable](https://github.com/SortableJS/Vue.Draggable) and [SortableJS](https://github.com/RubaXa/Sortable) as well as Vue. Use button styling from [Purecss](https://purecss.io/buttons/).

I found that sortable JS has to be loaded before Vue and then Vue draggable otherwise it does not work.

Icon from [feathericons](feathericons.com).

## Description

I started with [the Todo MVC on the official website](https://v2.vuejs.org/v2/examples/todomvc) but wanted to change the functionality a little bit for personal use. Like the original it uses localStorage to store a list of tasks and if marked as done the text of the task is struck through. The code is not as complex as the original.

Demo no longer hosted online, use node locally.

```bash
npm install -g serve
serve .
```
