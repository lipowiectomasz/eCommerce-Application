#  E-Commerce Application

A modern e-commerce platform developed as part of the **Rolling Scopes School** project.  
It offers a responsive, dynamic, and user-friendly online shopping experience.

##  Purpose

This app simulates a full eCommerce experience—from product discovery to checkout.  
It provides users with:

- Product catalog and detail pages
- Shopping basket with checkout
- User authentication (register/login)
- Sorting, filtering, and search functionality
- Responsive design (min. 390px width)
- Real-time interaction and smooth navigation

---

##  Technology Stack

| Layer       | Tools/Tech                            |
|-------------|----------------------------------------|
| Frontend    | React, TypeScript, Vite                |
| Styling     | CSS Modules or SCSS                    |
| API         | CommerceTools SDK                      |
| Testing     | Vitest, Testing Library                |
| Code Quality| ESLint, Prettier, Husky, lint-staged   |
| Versioning  | Git + GitHub                           |

---

##  Project Management

###  Task Board

Our Trello board organizes all project tasks:  
🔗 [Trello Board](https://trello.com/invite/b/682645cdc3926b174cfbce59/ATTI38de715cf2f853418c6eb3a515182df3DE372C23/ecommerce-application)

---

##  CommerceTools Integration

- CommerceTools project created under **"Rs eCommerce"**
- Includes ShopFront API client with necessary scopes

![CommerceTools Project](docs/img.png)  
![API Client](docs/img_1.png)

---

## Key Features

-  User Registration & Login
-  Main Page
-  Catalog Page with filters
-  Product Detail Page
-  Basket Page
-  User Profile
-  About Us

---

## Available Scripts

| Script       | Command                | Description                                      |
|--------------|------------------------|--------------------------------------------------|
| **Dev Server** | `npm run dev`           | Starts Vite development server                   |
| **Build**     | `npm run build`         | Builds the production app                        |
| **Preview**   | `npm run preview`       | Previews the production build                    |
| **Lint**      | `npm run lint`          | Runs ESLint on all source files                  |
| **Format**    | `npm run format`        | Formats codebase using Prettier                  |
| **Test**      | `npm run test`          | Runs tests using Vitest                          |
| **Test (Cov)**| `npm run test:coverage` | Runs tests with coverage reports                 |

---

## Local Setup & Contribution Guide

1. **Clone the repository**

```bash
git clone https://github.com/your-org/ecommerce-application.git
cd ecommerce-application
```
2. **Run the app in development mode**
```bash
npm run dev
```

3. **Run code checks before committing**
```bash
npm run lint
npm run format
npm run test
```

4. **Build for production**
```bash
npm run build
npm run preview
```