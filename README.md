DigiTools — Digital Tools Buying Platform
Overview

DigiTools is a modern web application that simplifies discovering and purchasing digital tools. It combines a clean, responsive UI with efficient frontend architecture for a smooth user experience.

✅ Built for scalability: separates data, logic, and presentation.
✅ Easy updates and long-term maintainability.
Key Features
Persistent Cart State
🛒 Products added to the cart remain marked as “In Cart”, even after UI updates or re-renders.
✅ Ensures a consistent user experience.
Structured Button Interaction
Each product button follows a three-step flow:
• Buy Now (initial)
• Added to Cart (temporary feedback)
• In Cart (final locked state)
🔹 Improves clarity and user confidence.
Duplicate Prevention Logic
⚠️ Checks if a product already exists in the cart.
🔹 Provides instant notifications for duplicates to keep data clean.
Clean UI Design
🎨 Built with Tailwind CSS and a custom design system.
✅ Modern layouts, gradient styling, and SaaS-inspired hierarchy.
Smooth User Interactions
✨ Subtle animations, hover effects, and icon cues enhance responsiveness.
🔹 Provides feedback without interrupting workflow.
Dynamic Tag System
🏷️ Products are automatically labeled based on metadata: Best Seller, New, Popular.
✅ Tags styled dynamically for clarity.
Button Locking Mechanism
🔒 Once added to cart, buttons are disabled and visually updated.
✅ Prevents repeated actions.
Real-Time Notifications
📢 Uses React-Toastify for instant feedback on actions like:
• Successful addition
• Duplicate warnings
JSON-Based Data Management
📄 Product info stored in a structured JSON file.
🔹 Developers can update product details without touching UI components.
Responsive Layout
📱 Mobile-first design ensures seamless experience on:
• Mobile
• Tablet
• Desktop
Technology Stack
⚛️ Frontend: React.js
🎨 Styling: Tailwind CSS & DaisyUI
💻 Language: JavaScript (ES6+)
🔔 Notifications: React-Toastify
🗂️ Data Storage: JSON
Setup Instructions
Requirements
Node.js v18+
npm or yarn
Installation
git clone https://github.com/ruku-roman/B13-A6-DigiTools-Platform.git
cd B13-A6-DigiTools-Platform
npm install
npm run dev
🌐 Runs at: http://localhost:5173
Production Build
npm run build
npm run preview
Project Structure
App.jsx: Global state & cart logic
ProductCard.jsx: UI behavior & button transitions
products.json: Stores product data
tailwind.config.js: Theme & styling
Testing Guide
🔹 Click Buy Now → observe state change
🔹 Button shows Added to Cart temporarily
🔹 Switches to In Cart → remains locked
⚠️ Clicking again triggers duplicate warning
📢 Toast notifications provide instant feedback
Contribution Guidelines
🌿 Create a new branch for features/fixes
📌 Follow standard commit conventions
🔹 Push changes and submit a pull request
Author

Md. Rukunuzzaman — Senior Officer, IT

GitHub: ruku-roman
LinkedIn: ruku-roman
Summary

DigiTools demonstrates modern frontend practices:

⚡ State management
🎨 User interaction design
🏗️ Scalable architecture

It reflects a professional approach to building real-world web applications.