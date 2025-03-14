# 🍽️ Restaurant Reservation System

A modern web application that allows customers to make restaurant reservations online. This full-stack application features a beautifully designed React frontend and a robust Express.js backend.

## ✨ Features

- 📱 Responsive design that works on desktop and mobile devices
- 🔄 Real-time form validation
- 📝 Simple reservation form with name, date, time, contact information
- 📊 Database storage of reservation details
- ✉️ Success confirmation page
- 🍴 Interactive restaurant menu display
- 👨‍🍳 Team showcase section
- 📜 About us and restaurant quality information

## 🛠️ Technologies Used

### Frontend
- **React.js** - UI library for building the user interface
- **React Router** - For navigation between pages
- **Axios** - HTTP client for API requests
- **React Hot Toast** - For displaying notifications
- **React Icons** - For beautiful UI icons
- **React Scroll** - For smooth scrolling functionality
- **Vite** - Build tool and development server

### Backend
- **Node.js** - JavaScript runtime environment
- **Express.js** - Web application framework
- **MongoDB** - NoSQL database for storing reservation data
- **Mongoose** - MongoDB object modeling tool
- **Validator** - For data validation
- **Cors** - For handling cross-origin requests
- **Dotenv** - For managing environment variables

## 🚀 Getting Started

### Prerequisites
- Node.js (v14 or later)
- MongoDB (local or Atlas)

### Installation

1. Clone the repository
```bash
git clone https://github.com/Rohand19/restaurant-reservation-system.git
cd restaurant-reservation-system
```

2. Setup Backend
```bash
cd Backend
npm install
```

3. Create a config.env file in Backend/config with the following:
```
PORT=4000
MONGO_URI=your_mongodb_connection_string
FRONTEND_URL=http://localhost:5173
```

4. Setup Frontend
```bash
cd ../frontend
npm install
```

5. Run the application
```bash
# In the Backend directory
npm run dev

# In the frontend directory (in a new terminal)
npm run dev
```

6. Open your browser and navigate to http://localhost:5173


## 📝 How to Use

1. Navigate to the homepage
2. Explore the restaurant information, menu, and team sections
3. Scroll to the reservation section
4. Fill out the form with your details
5. Click "RESERVE NOW" to submit your reservation
6. You'll be redirected to a success page upon successful submission

## 🤝 Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.

## 📄 License

This project is licensed under the ISC License.

## 👏 Acknowledgements
- [React Icons](https://react-icons.github.io/react-icons/) for the beautiful icons
- [React Hot Toast](https://react-hot-toast.com/) for the notification system
- All the open-source libraries that made this project possible 