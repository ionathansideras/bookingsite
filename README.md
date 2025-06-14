# bookingSite

**URL**: [https://ionathans-demo-site.com/](https://ionathans-demo-site.com/)

**Proof of Ownership**:  
Ownership of the site can be verified in two ways:
- The URL contains my first name ("Ionathan").
- The footer of the website includes both my first and last name.

**bookingSite** is a full-stack property booking application built with **Next.js 14**, **Material UI**, **MySQL**, **Prisma**, and **i18n**.  
It features a comprehensive booking system with fully separated **client** and **admin** interfaces, designed for demonstration in a development portfolio.

> ⚠️ **Please Note:**  
> This is a **public repository for a private project**. The source code of the actual application is **not publicly available** and cannot be shared due to project confidentiality.  
> However, companies interested in verifying my work during the interview process may request access privately.

## 🚀 Deployment Status

If you don’t see a deployment link, it means the project has either **not been deployed yet** or has been **temporarily taken down**.

## 📸 Screenshots

This repository includes screenshots that showcase various parts of the **website** and the **admin dashboard** to give you an idea of the application’s functionality and design.

## ✨ Features

### Client Features

-   **Multilingual Support**: Available in English and Greek
-   **Property Search**: Search and filter properties by various criteria
-   **User Accounts**: Register, login, and manage profile
-   **Booking Management**: Schedule, view, and cancel bookings
-   **Responsive Design**: Optimized for all device sizes
-   **Newsletter Subscription**: Receive updates via email
-   **Email Notifications**: Automated emails for bookings, account activities, and updates

### Admin Features

-   **User Management**: Create, edit, and manage user accounts
-   **Property Management**: Add, edit, and delete property listings
-   **Booking Control**: View and manage all client bookings
-   **Location Management**: Add and organize property locations
-   **Newsletter Campaign**: Send emails to subscribed users

## 🛠️ Tech Stack

-   **Frontend**: Next.js 14, Material UI, React
-   **Backend**: Next.js API routes
-   **Database**: MySQL with Prisma ORM
-   **Internationalization**: i18n for multilingual support
-   **Design**: Custom UI design created with UIzard
-   **Authentication**: Custom-built authentication system
-   **Email Notifications**: Integrated email feedback system

## 🚀 Deployment

This application is designed to be deployed on a VPS (Virtual Private Server)

## 🌐 Localization

The application supports English and Greek languages. Localization files are located in the `/messages` directory.

To add a new language:

1. Create a new folder in `/messages` with the language code
2. Copy the translation files from an existing language folder
3. Translate the content
4. Add the new language to the language selector component

## 🔐 Authentication System

The application features a custom-built authentication system with:

-   Session management with secure cookies
-   Rate limiting to prevent brute force attacks
-   Email notifications for suspicious login attempts
-   OTP (One-Time Password) system for secure access
-   Password hashing and salting
-   Account locking after multiple failed attempts

## 📨 Email System

The application includes a comprehensive email notification system:

-   Booking confirmations
-   Account registration and verification
-   Login notifications and security alerts
-   Password reset instructions
-   Booking updates and reminders
-   Newsletter distribution
-   Customer feedback requests

## 📝 Development Notes

-   **Payment Processing**: Intentionally omitted as this is a portfolio project
-   **Image Storage**: Uses local **media** folder system storage for property images and user avatars
-   **Authentication**: Custom-built system without third-party providers

## 📄 License

### PROPRIETARY AND CONFIDENTIAL

Copyright (c) Ionathan Sideras 2025. All Rights Reserved.

This software and its accompanying documentation are proprietary and confidential.
Unauthorized copying, distribution, modification, public display, or public performance
of this software and its documentation, via any medium, is strictly prohibited.
This software is for portfolio demonstration purposes only and may not be
used, reproduced, or distributed without the express written permission of Ionathan Sideras.
All designs, code, and other content contained within this project are the
exclusive property of Ionathan Sideras and may not be used for any purpose
without prior written consent.
