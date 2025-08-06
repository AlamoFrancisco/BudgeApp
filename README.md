# BudgeApp

BudgeApp is a React component demonstrating a simple budgeting interface built around the 50/30/20 rule. Enter a monthly salary and track how much you allocate and spend across three spending categories.

## Features

- **Salary-based budgets** – Calculates budgets for Essentials, Priorities and Lifestyle tabs using a 50/30/20 split of your salary.
- **Category management** – Add new categories, update existing amounts, or delete categories within each tab.
- **Progress tracking** – Shows remaining funds and progress bars for each category and tab.
- **Animated UI** – Uses shadcn/ui components and framer-motion for polished interactions.

## Usage

The main component lives in [`budget_app_preview.jsx`](budget_app_preview.jsx). Import and render `BudgetApp` inside a React or Next.js application that provides the required UI components.

## Dependencies

The snippet expects the following packages to be available in your project:

- React
- framer-motion
- shadcn/ui components such as `card`, `tabs`, `dialog`, `progress` and others

Ensure these dependencies and styles are installed and configured in your app before using the component.
