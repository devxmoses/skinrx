# Skincare E-Commerce Platform

A Next.js full-stack skincare e-commerce platform featuring a lightning fast shopping experience, secure checkout with Paystack payments, headless CMS and intuitive product discovery tailored to individual skin types.

## 🚀 Features

* **User Authentication:** Secure login, signup, and profile management.
* **Product Catalog:** Advanced filtering by skin type, skin concern, and ingredients.
* **Shopping Cart:** Persistent, real-time cart updates and state management.
* **Secure Checkout:** Full payment processing integration.
* **Responsive UI:** Mobile-first, accessible, and modern design.
* **Admin Panel:** Content and inventory management interface.

## 🛠️ Tech Stack

* **Frontend & Backend:** Next.js (App Router)
* **Styling:** Tailwind CSS
* **Database & ORM:** Prisma
* **Payments:** Stripe

## ⚙️ Getting Started

### Prerequisites

Ensure you have Node.js installed on your machine.

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/devxmoses/skinrx
   cd skinrx
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Set up your environment variables. Create a `.env.local` file in the root directory and add your credentials:
   ```env
   DATABASE_URL="your-database-connection-string"
   NEXT_AUTH_SECRET="your-auth-secret"
   STRIPE_SECRET_KEY="your-stripe-secret-key"
   ```

4. Run the development server:
   ```bash
   npm run dev
   ```

Open [http://localhost:3000](http://localhost:3000) in your browser to view the application.
