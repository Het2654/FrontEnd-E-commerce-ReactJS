# MERN E-Commerce Frontend

This is the frontend for a MERN stack e-commerce application, built with React and Material-UI. It provides user and admin interfaces for shopping, account management, and analytics.

## Features

- User authentication (register, login, password reset)
- Product browsing and detail pages
- Cart and wishlist management
- Checkout and payment integration (Razorpay)
- Review and rating system
- Admin dashboard for managing users, products, orders, and analytics
- Responsive design for desktop and mobile

## Tech Stack

- **React** (`react`, `react-dom`)
- **Material-UI** (`@mui/material`, `@emotion/react`, `@emotion/styled`)
- **Routing**: `react-router-dom`
- **State Management**: React Context API
- **HTTP Requests**: `axios`
- **Charts**: `recharts`
- **Notifications**: `react-toastify`
- **Icons**: `react-icons`
- **Testing**: `@testing-library/react`, `jest-dom`, `user-event`
- **Styling**: CSS Modules, styled-components

## Project Structure

```
src/
  ├── App.js
  ├── index.js
  ├── Assets/Images/
  ├── Auth/
  ├── Admin/
  ├── Components/
  ├── Context/
  ├── Constants/
  ├── Helpers/
  ├── Navigation/
  ├── Pages/
  ├── service-worker.js
  └── serviceWorkerRegistration.js
public/
  ├── index.html
  ├── manifest.json
  └── favicon.ico
```

## Getting Started

### Prerequisites

- Node.js (v14+ recommended)
- npm

### Installation

```sh
npm install
```

### Running the App

```sh
npm start
```

The app will run at [http://localhost:3000](http://localhost:3000).

### Building for Production

```sh
npm run build
```

## Environment Variables

Create a `.env` file in the root directory and add your API endpoints and keys, for example:

```
REACT_APP_GET_USER_DETAILS=your_api_endpoint
REACT_APP_REGISTER=your_api_endpoint
REACT_APP_GET_CART=your_api_endpoint
REACT_APP_GET_WISHLIST=your_api_endpoint
REACT_APP_GET_CHECKOUT=your_api_endpoint
REACT_APP_GET_PAYMENTVERIFICATION=your_api_endpoint
REACT_APP_ADMIN_GET_ALL_USERS=your_api_endpoint
REACT_APP_ADMIN_GET_CHART_DATA=your_api_endpoint
```

## Testing

```sh
npm test
```

## License

This project is for educational purposes.

---
## Screenshots

### Home Page
![Home Page]("./public/1.png")

### Product Listing
![Product Listing]("./public/2.png")

### Product Details
![Product Details]("./public/7.png")

### Cart
![Cart]("./public/1.png")

### User Information
![Checkout]("./public/4.png")

### Reset Password
![Admin Dashboard]("./public/6.png")
