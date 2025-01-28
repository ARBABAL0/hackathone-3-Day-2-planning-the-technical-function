#RENTAL E-Commerce Platform

## Objective
To build a scalable, user-friendly e-commerce platform with the following features:
- Product browsing and management via Sanity CMS.
- Authentication using Clerk.
- Order tracking with ShipEngine API.
- Secure payments via Stripe.
- Modern tools like useContext for cart functionality.

## System Architecture

### Frontend
- *Framework*: Next.js, React
- *Components*:
  - Home
  - Product Listing
  - Product Details
  - Cart
  - Checkout
  - Order Confirmation

### Key Features
- *User Sessions*: Manage user sessions without storing data in Sanity CMS.
- *Product Display*: Fetch and display products using GROQ queries.
- *Cart Management*: Use useContext to manage the cart globally.

### Checkout Process
1. *User Details & Payment*: Collect user details and payment via Stripe-hosted checkout.
2. *Order Confirmation*: Display order confirmation after successful payment.
3. *Shipping Label*: Generate a shipping label ID using ShipEngine.
4. *Tracking*: Provide the label ID to users for tracking their orders.

## Getting Started

### Prerequisites
- Node.js
- npm or yarn
- Sanity CMS account
- Clerk

### Notes:
- ARBABAL0


This README.md should provide a comprehensive overview of your project and guide users on how to set it up and contribute.
