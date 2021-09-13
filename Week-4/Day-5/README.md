# MERN-TypeScript-7weeks

## Week 4 - Day 5 - Skills Based Assessment (SBA)

*Prerequisite Knowledge: React Redux with TypeScript, JavaScript methods `.map()` `.filter()` `.reduce()`, Test Driven Development*

Coding Challenge: Create React Router Grocery List applicatoin

### MVP

Let's build another version of the grocery app. This time we will have a predefined list of possible grocery items:
```
const fruits = ['apples', 'bananas', 'oranges', 'kiwis', 'strawberries'];
const vegetabes = ['broccoli', carrots', 'zuccini', 'green beans'];
```

Use react-router to create the following pages:
### The main page - it's path is `/`, the base path or root path of our app.
1. This shows a title for the app.
2. A list of all the groceries the user has selected - you should be able to see all the fruits and vegetables that the user checked.

### The fruits page - it's path is `/fruits`
 
1. This page shows a list of all the fruits. There should be a checkbox next to each fruit. 
2. When the user clicks on the checkbox next to a fruit, the fruit is added to the grocery list on the Main Page.
3. If the user navigates away from the Fruits Page to the homepage, and then navigates back, the fruits they have checked should still be checked. 

### The vegetables page - it's path is `/vegetables`
 
 1. This page shows a list of all the vegetables. There should be a checkbox next to each vegetable. 
 2. When the user clicks on the checkbox next to a vegetable, the vegetable is added to the grocery list on the Main Page.
 3. If the user navigates away from the Vegetables Page to the Main Page, and then navigates back, the vegetables they have checked should still be checked. 

### *Optional* Stretch Goal

0. Add JSDoc documentation.
1. Add React PropTypes.
2. Add a Proteins page with `['chicken', 'beef', 'pork', 'tofu', 'fish']`
3. Any other features that you wish to add!

### *Optional* SUPER Stretch Goal
1. Use Typescript
2. Use redux with your project.

3. Incorporate TDD with Jest.
