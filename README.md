This project is a modern e-commerce web application built using React, React Router, Bootstrap, and Context API. It demonstrates how to design a functional shopping platform with dynamic product listings, category filters, and detailed product views.

The application uses a custom API hook (useCustomApi) to fetch data from a local JSON server (http://localhost:3000/products), making it easy to switch between categories and fetch product details dynamically. This architecture ensures scalability and reusability across components.

✨ Key Features

Dynamic Routing with React Router – Implemented nested routes with createBrowserRouter, providing a smooth navigation experience.

Navigation Bar – Responsive navbar with links to Home, About, Login, Register, Contact, and Product pages.

Theme Switcher (Light/Dark Mode) – Context API powers a global theme provider, allowing users to toggle between light and dark themes dynamically.

Category-based Filtering – Users can view all products or filter by categories like Smartphone, Smartwatch, Smart TV, Washing Machine.

Product Details Page – Dynamic route /productdetails/:pid fetches and displays detailed product information.

Loading State Handling – Displays a Bootstrap spinner while fetching data, enhancing user experience.

Reusable Components – CardList and ProductDetails ensure modular, maintainable code.

Error Handling – Dedicated Error component handles invalid routes or missing pages gracefully.

🛠️ Tech Stack

Frontend: React.js, React Router DOM, Bootstrap 5, Context API

Backend (Mock API): JSON Server (localhost REST API simulation)

Styling: Bootstrap, Custom CSS (index.css)

Tools: Git, npm, VS Code
