# PowerNosh Nutrition

![PowerNosh Logo](https://via.placeholder.com/150x50?text=PowerNosh+Logo)

## Technologies Used

### Frontend
- React.js
- Tailwind CSS
- Redux (State Management)
- React Router (Navigation)

### Backend
- Node.js
- Express.js
- MongoDB (Database)
- Mongoose (ODM)

### Other Tools
- Stripe API (Payments)
- Nodemailer (Email notifications)
- JWT (Authentication)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/powernosh.git
   ```

2. Install dependencies for both frontend and backend:
   ```bash
   cd powernosh/client
   npm install
   cd ../server
   npm install
   ```

3. Set up environment variables:
   - Create a `.env` file in the server directory with the following variables:
     ```
     MONGODB_URI=your_mongodb_connection_string
     JWT_SECRET=your_jwt_secret_key
     STRIPE_SECRET_KEY=your_stripe_secret_key
     ```

4. Run the application:
   - Start the backend server:
     ```bash
     cd server
     npm start
     ```
   - Start the frontend development server:
     ```bash
     cd client
     npm start
     ```

## Project Structure

```
powernosh/
├── client/               # Frontend React application
│   ├── public/           # Static files
│   └── src/              # React source files
│       ├── components/   # Reusable components
│       ├── pages/        # Page components
│       ├── store/        # Redux store
│       └── App.js       # Main application component
│
├── server/              # Backend Node.js application
│   ├── config/          # Configuration files
│   ├── controllers/     # Route controllers
│   ├── models/          # MongoDB models
│   ├── routes/          # API routes
│   └── server.js        # Server entry point
│
├── .gitignore           # Git ignore file
└── README.md            # This file
```

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a new branch (`git checkout -b feature-branch`)
3. Commit your changes (`git commit -m 'Add some feature'`)
4. Push to the branch (`git push origin feature-branch`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For any questions or suggestions, please contact:

- Project Lead: [Dhruv Badaya](mailto:mail@dhruvvv.com)
- GitHub: [@lightlessdays](https://github.com/lightlessdays)

---

