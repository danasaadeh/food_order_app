# Food Order App

A modern React-based food ordering application that allows users to browse meals, add items to their cart, and manage their order with an intuitive user interface.

## Features

- 🍽️ **Browse Available Meals** - View a curated list of delicious meals with descriptions and prices
- 🛒 **Shopping Cart** - Add and remove items from your cart with quantity management
- 💰 **Dynamic Total Calculation** - Automatic calculation of total order amount
- 🎨 **Modern UI** - Clean and responsive design with CSS modules
- 🔄 **State Management** - Efficient cart state management using React Context API and useReducer

## Technologies Used

- **React** 17.0.1 - UI library
- **React Context API** - State management for cart functionality
- **CSS Modules** - Scoped styling for components
- **Create React App** - Build tooling and development environment

## Project Structure

```
food_order_app/
├── public/                 # Static assets
├── src/
│   ├── components/
│   │   ├── Cart/          # Cart modal and cart item components
│   │   ├── Layout/        # Header and navigation components
│   │   ├── Meals/         # Meal listing and meal item components
│   │   └── UI/            # Reusable UI components (Card, Modal, Input)
│   ├── store/             # Context providers and cart state management
│   ├── assets/            # Images and other assets
│   ├── App.js             # Main application component
│   └── index.js           # Application entry point
├── package.json
└── README.md
```

## Getting Started

### Prerequisites

- Node.js (v14 or higher recommended)
- npm or yarn package manager

### Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd food_order_app
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm start
```

The application will open in your browser at [http://localhost:3000](http://localhost:3000).

## Available Scripts

- `npm start` - Runs the app in development mode
- `npm build` - Builds the app for production to the `build` folder
- `npm test` - Launches the test runner
- `npm eject` - Ejects from Create React App (one-way operation)

## Usage

1. **View Meals**: Browse through the available meals displayed on the main page
2. **Add to Cart**: Click the "Add" button on any meal item to add it to your cart
3. **View Cart**: Click the cart icon in the header to view your cart items
4. **Manage Cart**: 
   - Increase quantity using the "+" button
   - Decrease quantity using the "-" button
   - Remove items completely by reducing quantity to zero
5. **Close Cart**: Click the backdrop or close button to hide the cart modal

## Features in Detail

### Cart Management
- Items are automatically grouped by meal type
- Quantity can be incremented or decremented
- Total amount updates dynamically as items are added or removed
- Empty cart state is handled gracefully

### State Management
The application uses React Context API with `useReducer` hook for efficient state management:
- Centralized cart state in `CartProvider`
- Actions for adding and removing items
- Automatic total calculation

## Development

This project was created with [Create React App](https://github.com/facebook/create-react-app). You can learn more about the available scripts and features in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

## License

This project is private and for educational purposes.

