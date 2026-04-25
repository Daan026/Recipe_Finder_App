# Recipe Finder App

## Overview
Recipe Finder App is a full stack web application that allows users to search, discover, and save recipes from around the world.

Users can search recipes by name, ingredients, or categories, view detailed instructions, and save favorites to their account.

---

## Tech Stack
- React (Vite)
- JavaScript
- React Router
- TheMealDB API
- NOVI Educational Backend (authentication)
- CSS (responsive design)

---

## Features
- Search recipes by name, ingredients, or category
- Browse international cuisines
- View detailed recipe instructions
- Save and manage favorite recipes
- User authentication (register / login)
- Responsive design for mobile and desktop

---

## Project Structure
- **Pages** – route-based views (home, details, favorites)
- **Components** – reusable UI components
- **Services** – API calls and data handling
- **Auth** – login and registration logic

---

## API Integration

### TheMealDB API
Provides recipe data such as ingredients, images, and instructions. No API key required.

### NOVI Backend
Handles user authentication and account management.  
Base URL: https://api.datavortex.nl/daanreceptje

---

## Getting Started

### Requirements
- Node.js (18+)
- npm
- Git

### Installation
```bash
git clone [repository-url]
cd recipe-finder-app
npm install
