# Project Overview

This repository contains two separate projects:
1. **Calculator App**
2. **To-Do List App with LocalStorage**

Each project is built with HTML, CSS, and JavaScript, focusing on functionality and user interaction.

## Table of Contents
- [Project Overview](#project-overview)
- [Calculator App](#calculator-app)
  - [Features](#features)
  - [Usage](#usage)
  - [Customization](#customization)
- [To-Do List App with LocalStorage](#to-do-list-app-with-localstorage)
  - [Features](#features-1)
  - [Usage](#usage-1)
  - [Customization](#customization-1)

---

## Calculator App

The Calculator App is a basic arithmetic calculator that allows users to perform simple operations such as addition, subtraction, multiplication, and division.

### Features
- Supports basic arithmetic operations: `+`, `-`, `*`, `/`
- Includes clear (C) and delete (←) functions
- Simple and responsive UI
- Display shows input as it is typed and provides results upon calculation

### Usage
1. Open the `Calculator` HTML file in a browser.
2. Click on the buttons to input numbers and operations.
3. Use the `=` button to calculate the result.
4. Use the `C` button to clear all inputs or the `←` button to delete the last character.

### Customization
- Colors and button styles can be adjusted in the CSS section in the `<style>` tag.  
- For example, changing the `background-color` of `.container` or modifying `#equal`’s style will adjust the overall look.

---

## To-Do List App with LocalStorage

The To-Do List App enables users to add, edit, delete, and categorize to-do items with persistent storage via the browser's LocalStorage.

### Features
- Persistent storage of to-dos with LocalStorage
- Create to-dos with categories (Business or Personal)
- Edit or delete individual to-do items
- Checkbox to mark tasks as completed
- Separate name input that saves user name across sessions

### Usage
1. Open the `To-Do List` HTML file in a browser.
2. Enter your name at the top (stored for future visits).
3. Input your to-do item and choose a category (Business or Personal).
4. Click **Add Todo** to add the item to the list.
5. Use the edit button to modify to-dos or the delete button to remove them.

### Customization
- Colors for categories can be adjusted by changing `--business` and `--personal` in the CSS `<style>` tag.
- To change the styles for completed items, modify `.todo-item.done`.

---

Each project provides a simple example of functional web applications that prioritize user experience and ease of use. Both are great for educational purposes and can be further enhanced with more features or style refinements. 

---

