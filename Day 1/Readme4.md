# Exercise: Using Dynamic Content with `{}` in JSX

In this exercise, you'll learn how to inject dynamic data into JSX using curly braces `{}`.

---

## Step 1: Create a Greeting Component

1. **Create a New File**  
   - Create a new file called `Greeting.jsx`.

2. **Write the Component**  
   - Inside this file, create a functional component named `Greeting`.
   - The `Greeting` component should return a `<div>` containing:
     - A `<h1>` element that dynamically displays a greeting message.
     - A `<p>` element that dynamically displays the current date.

3. **Use JavaScript Expressions**  
   - Use `{}` to dynamically render:
     - A `name` variable containing a name, such as `"John"`.
     - A `new Date()` object to display the current date.

---

## Step 2: Create a ProductInfo Component

1. **Create a New File**  
   - Create a new file called `ProductInfo.jsx`.

2. **Write the Component**  
   - Inside this file, create a functional component named `ProductInfo`.
   - The `ProductInfo` component should return a `<div>` containing dynamic product details.

3. **Use a Product Object**  
   - Create a `product` object with the following properties:
     ```javascript
     const product = {
       name: "Laptop",
       price: "$1200",
       availability: "In stock"
     };
     ```
   - Use `{}` to display the `product`'s name, price, and availability.

---

## Step 3: Render Components in `App.jsx`

1. **Import Components**  
   - In your `App.jsx` file, import the `Greeting` and `ProductInfo` components:
     ```javascript
     import Greeting from "./Greeting";
     import ProductInfo from "./ProductInfo";
     ```

2. **Render Components**  
   - Inside the `App` component's `return` statement, render both components:
     ```javascript
     function App() {
       return (
         <div>
           <Greeting />
           <ProductInfo />
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
     - A personalized greeting with the current date.
     - Product details including name, price, and availability.

---

Happy Coding! 🚀
