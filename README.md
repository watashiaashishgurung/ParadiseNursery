# Paradise Nursery Shopping Application

## Overview

Welcome to the **Paradise Nursery Shopping Application** project. The goal of this project is to build the front end of a shopping application for houseplants. The application interface allows users to browse various houseplants, add them to a shopping cart, adjust the number of items, and view the total cost before proceeding to checkout.

This project is part of the final assignment, and it will be peer-reviewed. Much of the functionality developed in the practice project can be reused and enhanced here.

## Live Preview

You can preview the **Paradise Nursery Shopping Application** by visiting the following link:

[Live Preview](https://watashiaashishgurung.github.io/ParadiseNursery/)


## Features

The application consists of three main pages:

1. **Landing Page**
2. **Product Listing Page**
3. **Shopping Cart Page**

Each page has its own specific functionality, and the project involves managing the user experience across these pages.

## Pages and Functionality

### 1. Landing Page

The landing page should include the following elements:
- A **background image**.
- A **paragraph about the company**.
- The **company name**.
- A **Get Started** button that links to the product listing page.

### 2. Product Listing Page

The product listing page allows users to browse the available houseplants. It must include:
- At least **six houseplants** organized into three or more **categories**.
- Each plant card should display:
  - A **thumbnail image**.
  - The **plant name**.
  - The **price**.
  - An **Add to Cart** button that adds the plant to the shopping cart.

### 3. Shopping Cart Page

The shopping cart page displays the items added to the cart and provides the user with the ability to adjust the items. It should include:
- A list of items added to the cart, displaying:
  - The **thumbnail image**.
  - The **plant name**.
  - The **unit price**.
  - The **total cost** for each plant type.
- **Buttons to increase or decrease** the number of items in the cart.
- A **delete button** to remove items from the cart.
- A **checkout button** for proceeding with the order.
- A **continue shopping button** to return to the product listing page.

### Header (for both Product Listing and Shopping Cart pages)

The header component should:
- Include a **shopping cart icon** that shows the **number of items** in the cart.
- Provide **navigation** to other pages (e.g., linking from the product listing page back to the landing page).

## Project Setup

1. Clone the repository from GitHub:
    ```bash
    git clone https://github.com/watashiaashishgurung/ParadiseNursery.git
    ```
2. Install the necessary dependencies:
    ```bash
    npm install
    ```
3. Start the development server:
    ```bash
    npm start
    ```

## GitHub Repository

The project should be stored in a public GitHub repository, and the final submission requires the repository link to be shared for peer review.

## Technologies Used

- **React**: Front-end framework for building the UI.
- **Redux**: State management for handling cart items and product data.
- **React Router**: For routing between the landing page, product listing page, and shopping cart page.

## Instructions for Reviewers

Please review the project based on:
- The functionality of each page and interaction with the shopping cart.
- Correct updates to the cart and total item count.
- Proper navigation between pages.
- User experience, including handling of edge cases like removing all items from the cart.

Thank you for reviewing!

## License

This project is licensed under the [MIT License](LICENSE).
