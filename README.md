# StayEase: Vacation Rental Booking and Property Management Platform

StayEase is a comprehensive full-stack web application meticulously designed to simplify and enhance vacation rental booking and property management. Inspired by popular platforms like Airbnb, StayEase provides an intuitive and efficient solution for property owners and seekers to interact, enabling seamless exploration, listing, and booking of accommodations worldwide.

## Features

### 1. **User Authentication**
- Secure user registration and login.
- Password encryption and secure session management.
- Profile management with personalized settings.

### 2. **Listing Management**
- Property owners can create detailed listings with descriptions, photos, and pricing.
- Edit, update, or delete listings as needed.
- Display prices inclusive of GST for better transparency.

### 3. **Search and Filter**
- Advanced search functionality with location, price range, and category filters.
- 
### 4. **Reviews and Ratings**
- Users can leave detailed reviews and ratings for properties.
- Moderated reviews to maintain quality and relevance.

### 5. **Responsive Design**
- Fully responsive for desktops, tablets, and smartphones.
- Smooth and user-friendly navigation across all devices.

---

## Technologies Used

### Frontend
- **HTML**: Structuring web pages.
- **Bootstrap CSS**: Ensuring responsive and visually appealing designs.
- **JavaScript**: Adding interactivity.
- **EJS**: Server-side templating for dynamic content rendering.

### Backend
- **Node.js**: Scalable server-side runtime environment.
- **Express.js**: Web framework for routing and server logic.

### Database
- **MongoDB**: NoSQL database for managing user data, property listings, reviews, and ratings.

### Deployment and Development Tools
- **Version Control**: Git and GitHub for source code management.
- **Hosting Platforms**: MongoDB Atlas, Render, Netlify, AWS.
- **Automated Testing**: GitHub Actions for CI/CD pipelines.
- **Security**: Passport.js for user authentication and encrypted passwords.

---

## Prerequisites

- **Node.js**: Install from [Node.js Official Website](https://nodejs.org).
- **MongoDB**: Use [MongoDB Atlas](https://www.mongodb.com/cloud/atlas) or local MongoDB setup.
- **Git**: For version control.

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/stayease.git
   ```

2. Navigate to the project directory:
   ```bash
   cd stayease
   ```

3. Install dependencies:
   ```bash
   npm install
   ```

4. Set up environment variables:
   - Create a `.env` file in the root directory.
   - Add the following variables:
     ```env
     NODE_ENV=development
     PORT=3000
     DATABASE_URL=your_mongodb_connection_string
     SESSION_SECRET=your_secret_key
     ```

5. Start the application:
   ```bash
   npm start
   ```

6. Open your browser and go to `http://localhost:3000`.

---

## Project Structure
```
Stayease/
├── public/       # Static files (CSS, JS, images)
├── routes/       # Application routes
├── views/        # EJS templates
├── models/       # Mongoose schemas
├── controllers/  # Logic for handling requests
├── app.js        # Main application entry point
└── package.json  # Dependencies and scripts
```

---

## Contributing

1. Fork the repository.
2. Create a new branch for your feature:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add your message here"
   ```
4. Push to the branch:
   ```bash
   git push origin feature-name
   ```
5. Submit a pull request.

---

