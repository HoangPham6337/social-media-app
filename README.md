# A Social Media Application
> This repository contains the code corresponding to the tutorial available of JavaScript Mastery.

A modern social media application built using cutting-edge technologies, enabling users to connect, share, and interact seamlessly. This project incorporates features such as user authentication, posts, likes, comments, and more.

# Features
- User Authentication
  - Sign up, log in, and log out functionality.
  - Secure user authentication using Appwrite.
- Post Management
  - Create, edit, and delete posts.
  - View a list of posts with pagination.
- User Interaction
  - Like and comment on posts.
  - Save favorite posts.
- Profile Management
  - View and update user profiles.
  - Display user stats, including followers and following.
- Responsive Design
  - Optimized for mobile, tablet, and desktop devices.

# Technologies Used
- Frontend
  - React.js: Component-based UI library for building user interfaces.
  - TypeScript: Typed superset of JavaScript for type safety.
  - jTailwind CSS: Utility-first CSS framework for rapid UI development.
- Backend
  - Appwrite: Backend-as-a-service for authentication, database, and storage.
- State Management
  - React Query: Data-fetching and state management library.
- Other Tools
  - ESLint: JavaScript/TypeScript linting.
  - Prettier: Code formatting.

# Installation
1. Clone the Repository
```bash
git clone https://github.com/HoangPham6337/social-media-app.git
cd social-media-app
```
2. Install Dependencies
```bash
npm install
```
3. Set Up Environment Variables
Create a `.env.local` file in the root directory and add the following vairables:

```.env
REACT_APP_APPWRITE_ENDPOINT=your-appwrite-endpoint
REACT_APP_APPWRITE_PROJECT_ID=your-project-id
REACT_APP_APPWRITE_DATABASE_ID=your-database-id
REACT_APP_APPWRITE_COLLECTION_ID=your-collection-id
```

4. Run the Development Server
```bash
npm run dev
```
# Acknowledgements
All credits goes to [JavaScript Mastery](https://www.youtube.com/@javascriptmastery)
