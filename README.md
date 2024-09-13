# WordDePress - SaaS Website Builder, Project Management, and Dashboard with Stripe

<p align="left">
  <img src="https://www.animatedimages.org/data/media/562/animated-line-image-0184.gif" width="1920" 
</p>

This project, `WordDePress`, is a comprehensive SaaS platform built using the latest technologies such as Next.js 14, Bun, Stripe Connect, Prisma, MySQL, and Tailwind. It is designed to provide businesses and agencies with a powerful, all-in-one solution for website building, project management, and real-time analytics. The application integrates advanced features like multi-vendor support, role-based access, and seamless Stripe integration for managing subscriptions, payments, and custom checkouts.

![Screenshot 2024-09-13 at 5 22 57 PM](https://github.com/user-attachments/assets/a19b0865-864e-453f-b12a-4be88fd70a7c)

## Table of Contents
1. [Overview](#overview)
2. [Features](#features)
3. [Technology Stack](#technology-stack)
4. [Installation and Setup](#installation-and-setup)
5. [Usage](#usage)
6. [License](#license)
7. [Community and Support](#community-and-support)
8. [Resources](#resources)

## Overview

The SaaS platform is designed to meet the needs of digital agencies, freelancers, and businesses looking for a versatile solution to create, manage, and scale their online presence. It provides a fully-featured website and funnel builder, project management tools, and custom dashboards to manage various aspects of a business, from customer acquisition to product sales.

Key functionalities include unlimited funnel hosting, media storage, real-time collaborative editing, detailed funnel performance metrics, and role-based access to different parts of the platform. Additionally, it offers integration with Stripe for subscription management, recurring billing, and sales processing through Stripe Connect, allowing businesses to handle payments seamlessly.

![Screenshot 2024-09-13 at 5 24 09 PM](https://github.com/user-attachments/assets/9c026b0c-40e0-48da-afd6-5af49a2fbbae)

## Features

- **Multivendor B2B SaaS**: Supports multiple vendors and businesses, providing a scalable solution for various client needs.
- **Agency and Sub-Accounts**: Facilitates management of multiple accounts under a single agency, including sub-account functionalities.
- **Unlimited Funnel Hosting**: Host an unlimited number of funnels with optimized performance and security.
- **Full Website & Funnel Builder**: Drag-and-drop builder to create websites and funnels, equipped with customizable templates and elements.
- **Role-Based Access Control**: Granular control over user permissions, ensuring secure access to different parts of the application.
- **Stripe Integration**: Supports Stripe Subscription plans, add-on products, and custom checkouts for seamless payment processing.
- **Stripe Connect**: Allows users to connect their Stripe accounts and manage their own transactions, including application fee management per sale.
- **Custom Dashboards**: Real-time analytics and metrics to monitor sales, subscriptions, and overall business performance.
- **Project Management Tools**: Integrated Kanban board and task management system for efficient project handling.
- **Notification System**: Real-time notifications for various events such as new leads, sales, and project updates.
- **Performance Metrics**: Detailed analytics on funnel performance, agency metrics, and more.
- **Graphs and Charts**: Visual representation of data to simplify analysis and decision-making.
- **Light and Dark Mode**: User interface with both light and dark themes to enhance user experience.
- **Landing Page Builder**: Fully functioning landing page builder with customizable components.

![Screenshot 2024-09-13 at 5 23 37 PM](https://github.com/user-attachments/assets/80f92770-674e-415b-a9a1-ab5657a39eec)

## Technology Stack

![Screenshot 2024-09-13 at 5 23 21 PM](https://github.com/user-attachments/assets/b67c35e4-4665-4426-a7c1-40d0b83799b1)

- **Frontend**: Next.js 14, Tailwind CSS
- **Backend**: Bun, Prisma, MySQL
- **Payment Integration**: Stripe, Stripe Connect
- **Real-Time Collaboration**: Supabase, WebSockets
- **ORM**: Drizzle ORM
- **Deployment**: Vercel, Docker

## Installation and Setup

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/themihirmathur/WordDePress.git
   cd WordDePress
   ```

2. **Install Dependencies**:
   Make sure you have [Bun](https://bun.sh/) installed. Then, run:
   ```bash
   bun install
   ```

3. **Setup Environment Variables**:
   Create a `.env` file in the root directory and add your configuration details:
   ```env
   DATABASE_URL=mysql://username:password@localhost:3306/dbname
   STRIPE_SECRET_KEY=your_stripe_secret_key
   NEXT_PUBLIC_STRIPE_PUBLIC_KEY=your_stripe_public_key
   ```

4. **Run Migrations**:
   ```bash
   bun prisma migrate dev
   ```

5. **Start the Application**:
   ```bash
   bun run dev
   ```

## Usage

Once the application is set up, you can access the following modules:

- **Website Builder**: Access the website builder from the dashboard to create new websites or funnels. Use the drag-and-drop interface to customize your designs.
- **Project Management**: Manage projects with the integrated Kanban board and task management tools.
- **Dashboard**: Monitor key performance indicators (KPIs), sales metrics, and funnel performance in real-time.
- **Stripe Integration**: Manage subscriptions, create custom checkouts, and process payments seamlessly through Stripe Connect.

![Screenshot 2024-09-13 at 5 23 10 PM](https://github.com/user-attachments/assets/1c19126b-f571-491d-815d-04df0cf2cad6)

## License

This project is licensed for commercial use.

---

Feel free to reach out with any questions or suggestions. Let's build something amazing together!

<p align="left">
  <img src="https://www.animatedimages.org/data/media/562/animated-line-image-0184.gif" width="1920" 
</p>
