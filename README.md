# 🍿 Netflix Clone - Fullstack Web Application

![image](https://user-images.githubusercontent.com/23248726/220005380-ede4fb14-0b8d-4582-a063-3cc4beeccfb7.png)

Welcome to the **Netflix Clone** repository! This is a feature-rich, fully responsive web application that replicates the core user interface and functionality of Netflix. It's built with modern web development practices, delivering a premium streaming platform experience.

---

## ✨ Features

- **Authentication System:** Secure credential-based login, along with OAuth integration for Google and GitHub accounts.
- **User Profiles:** Support for multiple user profiles within a single account, just like the real Netflix.
- **Dynamic Content:** Browse, play, and discover movies with dynamic category generation.
- **My List:** Users can add and remove their favorite movies to a personalized "My List".
- **Responsive Design:** A seamless viewing experience across desktops, tablets, and mobile devices, featuring sleek animations and hover effects.
- **Billboard Video Player:** An interactive hero section with an auto-playing trailer.
- **Secure Sessions:** Cookie-based session management ensuring data privacy.

---

## 🛠️ Technology Stack & Purpose

This project leverages a powerful stack to deliver high performance and an exceptional developer experience:

### Frontend
- **[Next.js](https://nextjs.org/) (React Framework):** Used for building the user interface with Server-Side Rendering (SSR) capabilities, optimizing SEO, and providing a robust API routing system.
- **[React](https://reactjs.org/):** The core library for building reusable UI components and managing localized state.
- **[Tailwind CSS](https://tailwindcss.com/):** A utility-first CSS framework utilized for rapid, highly customizable, and responsive styling. It powers the sleek, dark-themed Netflix aesthetic and micro-animations.
- **[SWR](https://swr.vercel.app/):** A React Hooks library for data fetching. It handles caching, revalidation, and state management for API requests, ensuring the UI is always fast and up-to-date.
- **[Zustand](https://github.com/pmndrs/zustand):** A small, fast, and scalable bearbones state-management solution used for managing global app state (like the active movie or modal visibility).
- **[React Icons](https://react-icons.github.io/react-icons/):** Provides a comprehensive library of icons to enhance the visual appeal of the interface.

### Backend & Authentication
- **[NextAuth.js](https://next-auth.js.org/):** A complete open-source authentication solution for Next.js applications. It securely manages user sessions, OAuth providers (Google, GitHub), and custom credential logins.
- **[Prisma](https://www.prisma.io/):** A next-generation Node.js and TypeScript ORM. It provides a type-safe database client for interacting with our MongoDB database, making database queries intuitive and error-free.
- **[MongoDB](https://www.mongodb.com/):** A NoSQL document database used for scalable data storage, managing users, movies, sessions, and favorite lists.
- **[Bcrypt](https://www.npmjs.com/package/bcrypt):** A robust password-hashing function used to securely hash and store user passwords in the database.
