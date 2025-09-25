# WildEats Online Canteen Frontend

A modern React front-end for the WildEats Online Canteen system. This application allows users to place orders, view existing orders, and manage the order lifecycle from preparation to completion.

## Features

- Modern and responsive UI built with React
- Interactive animations using Framer Motion
- Complete order management system
- Real-time status updates
- Clean, intuitive design with maroon, mid-white, and light gray color scheme

## Project Structure

The frontend is organized into the following directories:

- `src/components`: Reusable UI components
- `src/pages`: Main application pages
- `src/contexts`: React Context API providers
- `src/hooks`: Custom React hooks
- `src/styles`: Global styles and theme definitions
- `src/utils`: Utility functions
- `src/assets`: Static assets like images and icons

## Available Pages

- **Home Page**: Landing page with a brief introduction to the canteen
- **Orders Page**: View and manage all orders
- **Order Details Page**: Detailed view of a specific order with status management
- **Create Order Page**: Form to create new orders with interactive menu
- **Not Found Page**: Custom 404 page

## Getting Started

1. Install dependencies:
   ```
   npm install
   ```

2. Start the development server:
   ```
   npm start
   ```

3. Build for production:
   ```
   npm run build
   ```

## Backend Integration

The frontend is configured to communicate with the backend API at `http://localhost:8080`. Make sure the backend server is running before using the application.

## Technologies Used

- React 18
- React Router 6
- Styled Components
- Framer Motion
- React Toastify
- Axios
- React Icons
