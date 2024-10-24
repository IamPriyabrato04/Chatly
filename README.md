# Chatly

Chatly is a real-time chat application built with the MERN stack (MongoDB, Express.js, React.js, Node.js) and Shadcn UI. It enables users to engage in real-time conversations, create chat rooms, and enjoy a responsive user interface.

## Key Features
- **User Authentication:** Secure signup and login processes.
- **Real-Time Messaging:** Instant communication using Socket.io.
- **Chat Rooms:** Create and join dedicated chat rooms.
- **Responsive Design:** A sleek and adaptable interface using Shadcn UI.

## Technologies Used
- **Backend:** 
  - MongoDB
  - Express.js
  - Node.js
  - Socket.io
- **Frontend:**
  - React.js
  - Shadcn UI
  - Tailwind CSS

## Installation

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/Chatly.git
   cd Chatly
   ```

2. **Set Up the Backend:**
   ```bash
   cd backend
   npm install
   ```

   - Create an `.env` file with your MongoDB connection string and JWT secret:
     ```
     MONGO_URI=your_mongodb_connection_string
     JWT_SECRET=your_jwt_secret
     ```

   - Start the backend server:
     ```bash
     npm run dev
     ```

3. **Set Up the Frontend:**
   ```bash
   cd ../frontend
   npm install
   npm start
   ```

4. **Access the App:** Open `http://localhost:3000` in your browser.

## Contributing
Contributions are welcome! Feel free to submit a pull request or open an issue.

## License
This project is open-source and available under the [MIT License](LICENSE).


