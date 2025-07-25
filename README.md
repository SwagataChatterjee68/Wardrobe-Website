MostlySane Merch Garage 

A clean, responsive e-commerce platform built with React, Redux, Tailwind CSS, and Framer Motion, using JSON Server as a lightweight backend for product and user data management.

🚀 Features

🛒 User Features
Browse products by category.

View detailed product pages.

Add products to cart (only if logged in).

View and update user profile.

Update account details.

Delete account.

Logout securely.

Protected Cart Page: non-logged-in users cannot access the cart.

🛠️ Admin Features
Admin profile page.

Add new products.

Update existing products.

Delete products.

Manage own account (update, delete, logout).

🌈 UI Features
Responsive product grid with Framer Motion animations.

Clean, dark-themed design using Tailwind CSS.

Toast notifications on user actions.

Login state-based UI:

Logged in: shows “Add to Cart” and “Know More” buttons in a single row.

Not logged in: shows only “Know More”.

🗄️ Lightweight Backend with JSON Server
This project uses JSON Server to act as a mock REST API for:

✅ Storing and retrieving products data.
✅ Managing user profiles, cart, and authentication states.
✅ Allowing CRUD operations for products and user management for testing and development.

Advantages:

Fast setup for backend simulation.

Enables real-world development structure with REST API calls.

🛠️ Tech Stack
Frontend: React, Tailwind CSS, Framer Motion

State Management: Redux

Routing: React Router DOM

Notifications: React Toastify

Backend: JSON Server

🧑‍💻 Usage
✅ Product Browsing: All users can browse products.
✅ Add to Cart: Only for logged-in users/admins.
✅ Admin Product Management: Only for admin accounts.
✅ Profile Page: View/update user/admin profiles.
✅ Delete Account: Available for users/admins.
✅ Protected Cart Page: Accessible only when logged in.
✅ Logout: Clears session securely.
