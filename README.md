# Product Catalog (E-Commerce SPA)

## Overview

Welcome to the Product Catalog, a fully responsive, Single Page Application (SPA) e-commerce platform built with React and TypeScript. Designed with a focus on user experience and modern web practices (referencing this [Figma design](https://www.figma.com/design/T5ttF21UnT6RRmCQQaZc6L/Phone-catalog-(V2)-Original?node-id=0-1&t=16O9NND2RWI3jvSp-0)), the project simulates a real-world online store. It features dynamic product catalogs, a persistent shopping cart and favorites functionality, and advanced URL-based state management for filtering and pagination.

## Demo

You can view a live demo of the application here: [Live Preview](https://IvanovvvIhor.github.io/react_phone-catalog/)

## Key Features

- **Dynamic Routing & Navigation**: Seamless transitions between categories (Phones, Tablets, Accessories) and individual product details pages using React Router.
- **URL-Driven State**: Sorting preferences (by age, name, price) and pagination limits are synchronized with URL parameters, allowing users to bookmark or share exact catalog views.
- **Global State Management**: Shopping cart and favorites logic are centralized using React Context, providing instant UI updates across the header and product cards without prop drilling.
- **Data Persistence**: User selections for cart items and favorite products are automatically saved and hydrated from `localStorage` to ensure a continuous user experience across sessions.
- **Optimized UI/UX**: Includes dynamic image sliders, smooth CSS transitions, interactive form elements, and handling of asynchronous states (loading spinners and error boundaries).
- **Modular Architecture**: Strictly typed data models and isolated CSS modules ensure a scalable and maintainable codebase.

## Challenges

Developing the application involved several challenges, particularly around implementing complex features and ensuring a seamless user experience.

### Key Challenges

- **Feature Integration**: Integrating multiple features such as sliders, sorting, pagination, and product details required careful planning and coordination.
- **Responsive Design**: Ensuring that all components and features work well across various devices and screen sizes demanded extensive testing and adjustments.
- **State Management**: Efficiently managing application state for the shopping cart, favorites, and product details—including `localStorage` interactions and URL synchronization—required robust state management strategies.
- **Error Handling**: Handling errors gracefully in various parts of the application, including loading states and API interactions, was crucial for a smooth user experience.
- **Performance Optimization**: Ensuring that the application performs well, with efficient data handling and smooth animations, was essential for maintaining a high-quality user experience.

## Installation & Setup

To install the project and run it locally, follow these steps:

1. Clone the repository:

```bash
   git clone [https://github.com/IvanovvvIhor/react_phone-catalog.git](https://github.com/IvanovvvIhor/react_phone-catalog.git)


```

2. Navigate to the project directory:

```bash
   cd react_phone-catalog


```

3. Install dependencies:

```bash
   npm install


```

4. Start the local development server:

```bash
   npm start


```

## Technologies Used

* **React (Hooks)**: For building the dynamic user interface.
* **TypeScript**: For type safety and a better development experience.
* **React Router v6**: For routing and seamless navigation between pages.
* **Context API & URLSearchParams**: For global and shareable URL-based state management.
* **SCSS (CSS Modules)**: For scoped and modular styling following the BEM methodology.
* **HTML5**: For structuring the content.
* **LocalStorage API**: For persistent data storage of the Cart and Favorites across browser sessions.
* **NPM**: For package management and running scripts.


