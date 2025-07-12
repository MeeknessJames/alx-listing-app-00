# ALX Listing App

This project is an Airbnb clone focusing on creating a dynamic and responsive listing page. It aims to demonstrate proficiency in building modern web applications using Next.js, TypeScript, and Tailwind CSS.

## Project Structure

* **`components/`**: Contains reusable UI components, broken down into subdirectories like `common/` for general-purpose components (e.g., `Card.tsx`, `Button.tsx`).
* **`interfaces/`**: Defines TypeScript interfaces used throughout the project to ensure type safety and consistent data structures.
* **`constants/`**: Stores global constants such as API URLs, configuration settings, or fixed UI text.
* **`public/assets/`**: Houses all static assets, including images, SVGs, and other media files used in the application.
* **`pages/`**: (Next.js Pages Router) Contains the application's routes. Each file in this directory corresponds to a route.
* **`styles/`**: Global styles and Tailwind CSS configurations.

## How to Run the Project Locally

To set up and run this project on your local machine, follow these steps:

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/your-username/alx-listing-app.git](https://github.com/your-username/alx-listing-app.git)
    cd alx-listing-app
    ```
    *(Note: If you're creating from scratch, you've already done the `create-next-app` and `cd alx-listing-app` steps.)*

2.  **Install dependencies:**
    ```bash
    npm install
    # or yarn install
    ```

3.  **Run the development server:**
    ```bash
    npm run dev
    # or yarn dev
    ```

4.  Open your browser and navigate to `http://localhost:3000` to view the application.