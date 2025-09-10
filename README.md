# Rentify

Rentify is a full-stack web application for listing, discovering, and booking vacation rentals. Inspired by platforms like Airbnb, Rentify allows users to register, create property listings, search and filter available rentals, book stays, and manage their trips and reservations.

## Features

- **User Authentication:** Register and log in with secure password hashing and JWT-based authentication.
- **Profile Management:** Upload and manage user profile photos.
- **Property Listings:** Create, edit, and view detailed property listings with multiple photos, amenities, and descriptions.
- **Search & Categories:** Search for properties by keyword or browse by curated categories (e.g., Beachfront, Castles, Camping).
- **Booking System:** Book properties for specific dates, view trip history, and manage reservations.
- **Wishlist:** Save favorite properties to a personal wishlist.
- **Responsive UI:** Modern, mobile-friendly interface built with React and SCSS.
- **Drag & Drop Photo Upload:** Easily upload and reorder listing photos.

## Tech Stack

- **Frontend:** React, Redux Toolkit, React Router, SCSS, Material UI, React Icons
- **Backend:** Node.js, Express, MongoDB, Mongoose, Multer (for file uploads), JWT, bcryptjs
- **State Persistence:** Redux Persist

## Getting Started

### Prerequisites

- Node.js & npm
- MongoDB

### Installation

1. **Clone the repository:**
   ```sh
   git clone https://github.com/yourusername/rentify.git
   cd rentify
   ```

2. **Install server dependencies:**
   ```sh
   cd server
   npm install
   ```

3. **Install client dependencies:**
   ```sh
   cd ../client
   npm install
   ```

4. **Set up environment variables:**
   - In the `server` directory, create a `.env` file with:
     ```
     MONGO_URI=your_mongodb_connection_string
     JWT_SECRET=your_jwt_secret
     ```

5. **Run the development servers:**
   - In one terminal, start the backend:
     ```sh
     cd server
     npm start
     ```
   - In another terminal, start the frontend:
     ```sh
     cd client
     npm start
     ```

6. **Visit [http://localhost:3000](http://localhost:3000) to use the app.**

## Folder Structure

```
Rentify/
  client/      # React frontend
  server/      # Express backend
```

## License

This project is for educational purposes.

---
