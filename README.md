PopX Mobile UI (React + Tailwind)
Project Overview

PopX Mobile UI is a responsive mobile-style web application built using React, Vite, Tailwind CSS, and React Router.
The project simulates a mobile app interface with screens for Home, Login, Signup, and Account Settings.

The UI is designed to look like a mobile device frame, allowing users to navigate between screens using client-side routing.

Features

Mobile styled UI layout

React component-based architecture

Page navigation using React Router

Account settings screen

Login screen

Signup screen

Responsive design using Tailwind CSS

Icon integration using Lucide React

Reusable MobileFrame layout component

Tech Stack
Frontend

React

Vite

Tailwind CSS

React Router DOM

Lucide React Icons

Development Tools

ESLint

Node.js

npm

Project Structure
popx-app
│
├── public
│   └── profile-image.webp
│
├── src
│   │
│   ├── components
│   │     └── MobileFrame.jsx
│   │
│   ├── pages
│   │     ├── Home.jsx
│   │     ├── Login.jsx
│   │     ├── Signup.jsx
│   │     └── Account.jsx
│   │
│   ├── App.jsx
│   ├── main.jsx
│   └── index.css
│
├── package.json
└── README.md
Installation

Clone the repository

git clone https://github.com/your-username/popx-app.git

Navigate to the project folder

cd popx-app

Install dependencies

npm install
Run the Project

Start the development server

npm run dev

Open the application in browser

http://localhost:5173
Application Pages
Home Page

Welcome screen

Navigation to Signup or Login

Signup Page

User registration form

Login Page

Email and password login

Account Page

Profile image

User details

Account description

Bottom navigation icons

Libraries Used
React Router DOM

Used for client-side routing between pages.

Tailwind CSS

Used for fast and responsive UI styling.

Lucide React

Provides modern icon components for the UI.

Future Improvements

Form validation

Authentication system

API integration

Profile image upload

Responsive tablet layout