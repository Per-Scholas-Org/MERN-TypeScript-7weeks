# MERN-TypeScript-7weeks

## Week 4 - Day 5 - Skills Based Assessment (SBA)

*Prerequisite Knowledge: React Redux with TypeScript, JavaScript methods `.map()` `.filter()` `.reduce()`, Test Driven Development*

Coding Challenge: Create React Redux application with TypeScript that 

### MVP

Let's build another version of the grocery app. This time we will have a predefined list of possible grocery items:
```
const fruits = ['apples', 'bananas', 'oranges', 'kiwis', 'strawberries'];
const vegetabes = ['broccoli', carrots', 'zuccini', 'green beans'];
```

Use react-router to create the following pages:
1. The main page - it's path is `/`, the base path or root path of our app. This shows a title for the app and list of all the groceries the user has selected. 
2. The fruits page - it's path is `/fruits`
  a) This page shows a list of all the fruits. There should be a checkbox next to each fruit. 
  b) When the user clicks on the checkbox next to a fruit, the fruit is added to the grocery list on the Main Page.
  c) If the user navigates away from the Fruits Page to the homepage, and then navigates back, the fruits they have checked should still be checked. 
3. The vegetables page - it's path is `/vegetables`
  a) This page shows a list of all the vegetables. There should be a checkbox next to each vegetable. 
  b) When the user clicks on the checkbox next to a vegetable, the vegetable is added to the grocery list on the Main Page.
  c) If the user navigates away from the Vegetables Page to the Main Page, and then navigates back, the fruits they have checked should still be checked. 

### *Optional* Stretch Goal

1. Add a Proteins page with `['chicken', 'beef', 'pork', 'tofu', 'fish']`
2. Any other features that you wish to add!

### *Optional* SUPER Stretch Goal
1. Use redux with your project.

2. Incorporate TDD with Jest and JSDoc into your project.
