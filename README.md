# React Authentication with Protected Routes

This is a simple React application demonstrating user authentication with protected routes. The project uses React Router DOM for routing and Vite as the build tool.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Folder Structure](#folder-structure)
- [Components](#components)
- [Context](#context)
- [Contributing](#contributing)
- [License](#license)

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/aliseyedabady/react-router-dom-auth-ts.git
   cd your-repository
   ```

2. **Install dependencies:**

   ```bash
   npm install
   ```

3. **Run the development server:**

   ```bash
   npm run dev
   ```

4. **Build the project for production:**

   ```bash
   npm run build
   ```

5. **Preview the production build:**

   ```bash
   npm run preview
   ```

## Usage

After starting the development server, you can access the application at http://localhost:5173.

### Authentication Flow

- Navigate to /login to log in.
- Upon logging in, you will be redirected to the home page.
- If you are logged in and try to access the login page, you will be redirected to the home page.

## Folder Structure

```
public
src/
├── components/
│ └── protectedRoute.tsx
├── context/
│ └── auth.tsx
├── hooks/
│ └── useAuth.ts
├── layouts/
│ └── main.tsx
├── pages/
│ ├── home
│ └── login
├── router/
│ └── index.tsx
├── App.tsx
├── main.tsx
```

## Components

- protectedRoute.tsx: Component to protect routes.

## Context

- AuthContext.tsx: Provides authentication context to manage login state and protect routes.

## Contributing

1. **Fork the repository:**
2. **Create a new branch (git checkout -b feature/your-feature).**
3. **Commit your changes (git commit -m 'Add your feature').**
4. **Push to the branch (git push origin feature/your-feature).**
5. **Open a pull request.**

## License

This project is licensed under the MIT License. See the LICENSE file for details.
