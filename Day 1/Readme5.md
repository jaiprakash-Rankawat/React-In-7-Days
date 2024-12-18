# Exercise: Rendering a List of Data with `.map()`

In this exercise, you will learn how to render a list of items using the `.map()` method in JSX.

---

## Step 1: Create a UserList Component

1. **Create a New File**  
   - Create a new file called `UserList.jsx`.

2. **Write the Component**  
   - Inside this file, create a functional component named `UserList`.

3. **Create a Users Array**  
   - Inside the component, create a `users` array with the following objects:
     ```javascript
     const users = [
       { id: 1, name: "Alice", age: 25 },
       { id: 2, name: "Bob", age: 30 },
       { id: 3, name: "Charlie", age: 22 },
     ];
     ```

4. **Render the List**  
   - Use the `.map()` method to render a list of users.
   - Display each user's name and age inside a `<div>` element.
   - Use the `id` property as the unique key for each list item.

---

## Step 2: Create a ProductList Component

1. **Create a New File**  
   - Create a new file called `ProductList.jsx`.

2. **Write the Component**  
   - Inside this file, create a functional component named `ProductList`.

3. **Create a Products Array**  
   - Inside the component, create a `products` array with the following objects:
     ```javascript
     const products = [
       { id: 1, name: "Phone", price: "$699" },
       { id: 2, name: "Laptop", price: "$1200" },
       { id: 3, name: "Headphones", price: "$199" },
     ];
     ```

4. **Render the List**  
   - Use the `.map()` method to render the list of products.
   - Display each product's name and price inside a `<div>` element.
   - Use the `id` property as the key for each product.

---

## Step 3: Render the Components in `App.jsx`

1. **Import Components**  
   - In your `App.jsx` file, import the `UserList` and `ProductList` components:
     ```javascript
     import UserList from "./UserList";
     import ProductList from "./ProductList";
     ```

2. **Render Components**  
   - Inside the `App` component's `return` statement, render both the `UserList` and `ProductList` components:
     ```javascript
     function App() {
       return (
         <div>
           <UserList />
           <ProductList />
         </div>
       );
     }

     export default App;
     ```

---

## Step 4: Run the Application

1. **Start the Development Server**  
   - Run the app in your development environment.

2. **Verify the Output**  
   - You should see:
     - A list of users displaying their names and ages.
     - A list of products displaying their names and prices.

---

Happy Coding! 🚀
