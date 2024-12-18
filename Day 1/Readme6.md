# Exercise: Using Props in React Components

In this exercise, you will learn how to pass and use props in React components to make them dynamic and reusable.

---

## Step 1: Create a `Person` Component

1. Create a new file called **`Person.jsx`**.
2. Inside this file, create a functional component called `Person`.
3. This component should:
   - Accept props as an argument.
   - Render:
     - A `<h2>` element that displays the person's name.
     - A `<p>` element that displays the person's age.
4. Use `props.name` and `props.age` to display the dynamic values passed from the parent component.

---

## Step 2: Create a `Product` Component

1. Create a new file called **`Product.jsx`**.
2. Inside this file, create a functional component called `Product`.
3. This component should:
   - Accept props as an argument.
   - Render:
     - A `<h2>` element that displays the product's name.
     - A `<p>` element that displays the product's price.
4. Use `props.name` and `props.price` to display the values passed from the parent component.

---

## Step 3: Pass Props from `App.jsx`

1. In your **`App.jsx`** file, import the `Person` and `Product` components:
   ```javascript
   import Person from "./Person";
   import Product from "./Product";
