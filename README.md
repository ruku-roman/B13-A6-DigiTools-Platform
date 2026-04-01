DigiTools — Digital Tools Buying Platform
Overview

DigiTools is a modern web application designed to simplify the process of discovering and purchasing digital tools. It combines efficient frontend architecture with a clean user interface to deliver a smooth and reliable user experience.

The system is built with scalability in mind, separating data, logic, and presentation to allow easy updates and long-term maintainability.

Key Features
Persistent Cart State

The application maintains a consistent cart experience by synchronizing product status with a global state. Once a product is added, it remains marked as “In Cart” even after UI updates or re-renders.

Structured Button Interaction

Each product button follows a clear three-step interaction flow:

Buy Now (initial state)
Added to Cart (temporary feedback)
In Cart (final locked state)

This ensures clarity and improves user confidence during interaction.

Duplicate Prevention Logic

Before adding any product, the system checks whether it already exists in the cart. If a duplicate action is detected, the user receives an immediate notification, ensuring clean and accurate data handling.

Clean UI Design

The interface is built using Tailwind CSS with a custom design system. It features a modern layout with gradient styling and a structured visual hierarchy inspired by SaaS platforms.

Smooth User Interactions

The application includes subtle animations and transitions to improve usability. Hover effects, button feedback, and icon-based cues provide a responsive and interactive experience.

Dynamic Tag System

Products are automatically labeled based on predefined metadata. Tags such as “Best Seller”, “New”, or “Popular” are displayed dynamically with appropriate styling.

Button Locking Mechanism

Once a product is added to the cart, the action button is disabled and visually updated to indicate a successful state. This prevents repeated actions and improves usability.

Real-Time Notifications

The system uses React-Toastify to display instant notifications for user actions, including successful additions and duplicate warnings, without interrupting the workflow.

JSON-Based Data Management

All product information is stored in a structured JSON file. This allows developers to update product details without modifying UI components, making the system flexible and scalable.

Responsive Layout

The platform is built with a mobile-first approach. The layout adapts seamlessly across different screen sizes, ensuring a consistent experience on mobile, tablet, and desktop devices.

Technology Stack
React.js
Tailwind CSS and DaisyUI
JavaScript (ES6+)
React-Toastify
JSON for data storage
Setup Instructions
Requirements
Node.js version 18 or higher
npm or yarn
Installation
git clone https://github.com/ruku-roman/B13-A6-DigiTools-Platform.git
cd B13-A6-DigiTools-Platform
npm install
npm run dev

The application will run at http://localhost:5173

Production Build
npm run build
npm run preview
Project Structure
App.jsx: Manages global state and cart logic
ProductCard.jsx: Handles UI behavior and button state transitions
products.json: Stores product data
tailwind.config.js: Contains theme and styling configuration
Testing Guide

To verify the core functionality:

Click “Buy Now” and observe the state change
The button should temporarily show “Added to Cart”
It should then switch to “In Cart” and remain locked
Clicking again should trigger a duplicate warning
A toast notification should appear for feedback
Contribution Guidelines
Create a new branch for features or fixes
Follow standard commit conventions
Push changes and submit a pull request
Author

Md. Rukunuzzaman
Senior Officer - IT

GitHub: https://github.com/ruku-roman

LinkedIn: https://linkedin.com/in/ruku-roman

Summary

DigiTools demonstrates practical implementation of modern frontend concepts, including state management, user interaction design, and scalable architecture. It reflects a structured and professional approach to building real-world web applications.