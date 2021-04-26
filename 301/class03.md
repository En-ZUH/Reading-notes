# React
![img](https://i.ytimg.com/vi/szmS_M-BMls/mqdefault.jpg)

### There are several ways to make sure functions have access to component attributes like this.props and this.state, depending on which syntax and build steps you are using

## Lifting State Up

### In React, sharing state is accomplished by moving it up to the closest common ancestor of the components that need it. This is called “lifting state up”. We will remove the local state from the TemperatureInput and move it into the Calculator instead.’ Lifting up the State: every component in React has its own state. Because of this sometimes data can be redundant and inconsistent. So, by Lifting up the state we make the state of the parent component as a single source of truth and pass the data of the parent in its children

### Time to use Lift up the State: If the data in “parent and children components” or in “cousin components” is Not in Sync

## Rendering Multiple Components

#### You can build collections of elements and include them in JSX using curly braces {}

Below, we loop through the numbers array using the JavaScript map() function. We return a

element for each item. Finally, we assign the resulting array of elements to listItems:


``` const numbers = [1, 2, 3, 4, 5];
const listItems = numbers.map((number) =>
  <li>{number}</li>
);
```

## Lists and Keys

### First, let’s review how you transform lists in JavaScript. Given the code below, we use the map() function to take an array of numbers and double their values. We assign the new array returned by map

() to the variable doubled and log it:

const numbers = [1, 2, 3, 4, 5]; const doubled = numbers.map((number) => number * 2); console.log(doubled);

This code logs [2, 4, 6, 8, 10] to the console.

In React, transforming arrays into lists of elements is nearly identical.
