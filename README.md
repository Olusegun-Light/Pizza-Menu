# Fast React Pizza Co.

## Overview

Fast React Pizza Co. is a simple React application showcasing a pizza menu with various pizza options. This project is built using React and demonstrates key concepts such as components, props, conditional rendering, and styling.

## Pizza Menu

The pizza menu includes a variety of pizzas with details such as name, ingredients, price, and availability. The application dynamically renders the pizza menu based on the provided data.

## Concepts Demonstrated

### 1. Components

- **App**: The main component rendering the Header, Menu, and Footer components.
- **Header**: Displays the name of the pizza company.
- **Menu**: Renders the pizza menu based on the provided data.
- **Pizza**: Represents an individual pizza item, showcasing its details.
- **Footer**: Displays operating hours and an order section.

### 2. Props

- The `Pizza` component receives `pizzaObj` as a prop, containing details about each pizza.

### 3. Conditional Rendering

- The `Pizza` component checks if a pizza is sold out and conditionally renders it.
- The `Footer` component displays different content based on whether the store is open or closed.

### 4. Styling

- The application includes basic styling using CSS for a visually appealing layout.

### 5. Strict Mode

- The application is wrapped in `React.StrictMode` for enhanced development mode checks.

### 6. Dynamic Content

- The `Menu` component dynamically displays a message about the authenticity and creativity of the pizza menu.

## Running the Application

To run the application, ensure you have Node.js installed and follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/react-pizza-app.git
   cd react-pizza-app
   ```

2. Start the development server:
    ```bash
    npm start
    ```
