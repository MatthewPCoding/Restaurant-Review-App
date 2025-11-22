# Restaurant Reviewer

A full-stack web application that enables users to discover restaurants, submit reviews with ratings, and view aggregated feedback from the community. Built with the MERN stack (MongoDB, Express, React, Node.js).

![Restaurant Reviewer Screenshot](./screenshot.png)
<!-- Add a screenshot of your app here -->

## 🔗 Live Demo

[View Live Application](#) <!-- Add your deployed link here -->

## ✨ Features

- **User Authentication** - Secure signup and login functionality
- **Review Submission** - Dynamic forms for submitting restaurant reviews with ratings
- **Real-time Rating Calculations** - Automatic aggregation and display of average ratings
- **Restaurant Browsing** - View detailed information about restaurants and their reviews
- **Responsive Design** - Optimized for both desktop and mobile devices
- **Data Validation** - Server-side and client-side validation to ensure data integrity
- **Error Handling** - Comprehensive error handling for a reliable user experience

## 🛠️ Built With

**Frontend:**
- React.js
- JavaScript (ES6+)
- React Hooks (useState, useEffect, useContext)
- CSS3

**Backend:**
- Node.js
- Express.js
- MongoDB
- Mongoose

**Tools:**
- Git & GitHub
- Vite (development server)
- npm

## 🚀 Getting Started

### Prerequisites

- Node.js (v14 or higher)
- MongoDB (local installation or MongoDB Atlas account)
- npm or yarn

### Installation

1. Clone the repository
```bash
git clone https://github.com/MatthewPCoding/restaurant-reviewer.git
cd restaurant-reviewer
```

2. Install backend dependencies
```bash
cd backend
npm install
```

3. Install frontend dependencies
```bash
cd ../frontend
npm install
```

4. Create a `.env` file in the backend directory
```env
MONGODB_URI=your_mongodb_connection_string
PORT=5000
JWT_SECRET=your_jwt_secret
```

5. Start the backend server
```bash
cd backend
npm start
```

6. Start the frontend development server
```bash
cd frontend
npm run dev
```

7. Open your browser and navigate to `http://localhost:5173`

## 📁 Project Structure

```
restaurant-reviewer/
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── App.jsx
│   │   └── main.jsx
│   └── package.json
├── backend/
│   ├── models/
│   ├── routes/
│   ├── controllers/
│   ├── middleware/
│   ├── server.js
│   └── package.json
└── README.md
```

## 🔑 Key Technical Implementations

- **State Management:** Utilized React hooks (useState, useEffect, useContext) for efficient state handling across components
- **API Integration:** RESTful API design with proper HTTP methods and status codes
- **Data Persistence:** MongoDB with Mongoose for schema validation and data modeling
- **Authentication:** Secure user authentication with password hashing and JWT tokens
- **Error Handling:** Implemented try-catch blocks and Express error middleware for robust error management
- **Validation:** Client-side and server-side validation to prevent invalid data submission

## 📝 API Endpoints

### Restaurants
- `GET /api/restaurants` - Get all restaurants
- `GET /api/restaurants/:id` - Get a specific restaurant
- `POST /api/restaurants` - Create a new restaurant

### Reviews
- `GET /api/reviews/:restaurantId` - Get all reviews for a restaurant
- `POST /api/reviews` - Submit a new review
- `PUT /api/reviews/:id` - Update a review
- `DELETE /api/reviews/:id` - Delete a review

### Authentication
- `POST /api/auth/signup` - Register a new user
- `POST /api/auth/login` - Login user

## 🔮 Future Enhancements

- Search and filter functionality for restaurants
- User profile pages with review history
- Image uploads for restaurants and reviews
- Sorting options (by rating, date, etc.)
- Google Maps integration for restaurant locations
- Social features (like/helpful buttons for reviews)

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](#).

## 📧 Contact

Matthew Pearcy - [matthewapearcy@gmail.com](mailto:matthewapearcy@gmail.com)

Project Link: [https://github.com/MatthewPCoding/restaurant-reviewer](https://github.com/MatthewPCoding/restaurant-reviewer)

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

⭐ If you found this project helpful, please consider giving it a star!
