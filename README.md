# Lumière Beauty

**Lumière Beauty** is a digital platform where beauty products can be registered, verified, and managed efficiently. The application helps sellers and users organize product information, verify product authenticity, and access relevant product details in a clear and secure way.

The platform aims to simplify product management and improve the experience for both sellers and users by providing an intuitive, modern, and responsive interface.

<p align="center">
  <img width="269" height="192" alt="Logo" src="https://github.com/user-attachments/assets/b84ca8fc-e083-417b-9954-3f01c90a5cfd" />
</p>
  
## Tech Stack

The Lumière Beauty platform is built using a modern frontend stack focused on performance, scalability, and simplicity.

### React

React is the main library used to build the user interface. It allows the application to be structured using reusable components, making the code easier to maintain and scale.

React enables dynamic and interactive interfaces while keeping the development process organized and efficient.

### Vite

Vite is the development tool used to build and run the application. It provides a fast development environment with features such as **Hot Module Replacement (HMR)**, which allows developers to see changes instantly during development.

It also generates optimized builds for production.

### Static Site Generation (SSG)

The application will be built using **Static Site Generation (SSG)**.

This means that the pages of the website are generated in advance during the build process instead of being created dynamically on a server. This approach improves:

* loading speed
* performance
* security

It also makes the site easier to deploy on static hosting platforms.

### Static Hosting

The project will be deployed using a **static hosting service such as GitHub Pages**.

Static hosting is ideal for applications built with SSG because it allows the website to be served quickly without requiring a backend server.

### Recharts

Recharts will be used to create visual charts and graphs within the platform. These charts will help display relevant information and statistics in a clear and interactive way.

Because it is built specifically for React, it integrates easily with the component structure of the application.

### EmailJS

EmailJS will be used to send emails directly from the web application without requiring a backend server.

It will be used for features such as:

* registration confirmations
* notifications
* user communication

### React Hot Toast

React Hot Toast will be used to display notification messages within the application.

These notifications will inform users about actions such as:

* successful login
* product registration confirmation
* errors or warnings

The alerts appear temporarily and disappear automatically, improving the user experience.

## Code of Conduct

To maintain a clear and organized development process, the team will follow **Conventional Commits**.

All commits, documentation, and code must be written in **English**.

### Allowed commit types

**feat:** Used when adding a new feature.

**fix:** Used when fixing a bug.

**style:** Used for visual or formatting changes that do not affect functionality.

**docs:** Used for documentation updates.

**chore:** Used for maintenance tasks such as dependency updates or configuration changes.

If any issue or question arises during development, it must be documented so the team can review and solve it collaboratively.

## Workflow

To organize development, the project will use a **branch-based workflow**.

The following branches will be used:

* **main**
* **dev**
* **feat/name**
* **fix/name**

### Main Branch

The **main branch** contains the stable version of the project.

Only fully tested and completed updates will be merged into this branch. This represents the production-ready version of the application.

### Dev Branch

The **dev branch** is the main development branch where new features are integrated before being released.

All new features must be merged here first to ensure stability and compatibility with the rest of the project.

### Feature Branches

Feature branches are created from **dev** and are used to develop new features.

They follow the structure:

feat/feature-name

Example:

feat/product-registration
feat/login-page

Once completed and tested, the feature will be merged into the **dev branch**.

### Fix Branches

Fix branches are used to resolve bugs or errors in the project.

They follow the structure:

fix/bug-name

Example:

fix/login-error
fix/product-verification

After fixing the issue, the branch will be merged into **dev**.

## Versioning System

The project uses **Calendar Versioning (CalVer)** instead of semantic versioning.

Calendar versioning uses the date of release as the version number, making it easier to track when updates were made.

The format used will be:

YYYY.MM.DD

Example:

2026.03.05
2026.04.12

Each new release will update the version based on the release date.

## Summary of Project Progress (30%)

During the first **30% of the Lumière Beauty project**, several key parts of the interface and navigation structure were developed.

The focus of this stage was creating the core screens of the application and establishing the main user flow.

### Screens Developed

The following screens have been implemented:

* **Home Page**
* **Products Page**
* **Seller Instructions Page**
* **Login Screen**
* **Sign Up Screen**
* **Product Type Selection Screen**
* **Product Registration Verification Screen**

These pages allow users to explore products, access seller instructions, create accounts, and begin the product registration process.

## Responsiveness and Design

All screens have been designed to be **fully responsive**, ensuring compatibility across different devices including:

* desktop computers
* mobile devices

The interface adapts to different screen sizes to provide a consistent and accessible user experience.

## Styling System

The application styling is implemented using **CSS Modules with the BEM methodology**.

This approach helps maintain:

* better organization of styles
* reusable components
* scalable design structure

It also prevents style conflicts and improves maintainability as the project grows.
