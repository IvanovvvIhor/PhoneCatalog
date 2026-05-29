```markdown
# Product Catalog (E-Commerce SPA)

A fully responsive, Single Page Application (SPA) e-commerce platform built with React and TypeScript. The project simulates a real-world online store featuring dynamic product catalogs, persistent shopping cart and favorites functionality, and advanced URL-based state management for filtering and pagination.

## Demo
[Live Preview](https://IvanovvvIhor.github.io/react_phone-catalog/)

## Technologies Used
* **Frontend:** React (Hooks), TypeScript, HTML5
* **Routing:** React Router v6
* **State Management:** Context API, URLSearchParams (for shareable filtering/pagination state)
* **Styling:** SCSS (CSS Modules for scope isolation), BEM methodology
* **Storage:** Browser LocalStorage API (persistent Cart and Favorites)

```

```markdown
## Getting Started

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/IvanovvvIhor/react_phone-catalog.git](https://github.com/IvanovvvIhor/react_phone-catalog.git)

```
```

2. **Navigate to the project directory:**
```bash
cd react_phone-catalog

```


3. **Install dependencies:**
```bash
npm install

```


4. **Run the project locally:**
```bash
npm start

```



## Key Features

* **Dynamic Routing & Navigation:** Seamless transitions between categories (Phones, Tablets, Accessories) and individual product details pages using React Router.
* **URL-Driven State:** Sorting preferences (by age, name, price) and pagination limits are synchronized with URL parameters, allowing users to bookmark or share exact catalog views.
* **Global State Management:** Shopping cart and favorites logic are centralized using React Context, providing instant UI updates across the header and product cards without prop drilling.
* **Data Persistence:** User selections for cart items and favorite products are automatically saved and hydrated from `localStorage` to ensure a continuous user experience across sessions.
* **Optimized UI/UX:** Includes dynamic image sliders, smooth CSS transitions, interactive form elements, and handling of asynchronous states (loading spinners and error boundaries).
* **Modular Architecture:** Strictly typed data models and isolated CSS modules ensure a scalable and maintainable codebase.

```

```
