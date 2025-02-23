# QuickCart (E-Commerce)

QuickCart is a modern and user-friendly e-commerce platform that allows users to browse products, manage personalized carts, and experience a seamless checkout process. It is built using the MERN (MongoDB, Express.js, React, Node.js) stack with Redux for state management.

## 🚀 Features

- 🔍 **Product Browsing** - Search and filter products by categories.
- 🛒 **Personalized Cart** - Users can add, update, or remove items from their cart.
- 🏷 **Secure Checkout** - Seamless order placement and payment processing.
- 🔐 **User Authentication** - Login and sign-up system using JWT.
- 📦 **Order History** - Users can track their past purchases.
- ⚡ **Fast and Scalable** - Optimized performance with React and efficient API handling.

---

## 🛠 Tech Stack

- **Frontend:** React.js, Redux, Tailwind CSS
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Authentication:** JWT
- **State Management:** Redux
- **API Calls:** Axios

---

## 📦 Installation & Setup

### 🔧 Prerequisites
Ensure you have the following installed:
- [Node.js](https://nodejs.org/)
- [MongoDB](https://www.mongodb.com/)

### 🔹 Clone the Repository
```bash


git clone https://github.com/YashMhetre/QuickCart.git
cd QuickCart



Install Dependencies
Install backend dependencies:
bash
Copy
Edit
cd backend
npm install
Install frontend dependencies:
bash
Copy
Edit
cd ../frontend
npm install
🔹 Set Up Environment Variables
Create a .env file in the backend directory and add the following:

ini
Copy
Edit
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
PORT=5000
🚀 Running the Application
🔹 Start Backend Server
bash
Copy
Edit
cd backend
npm start
🔹 Start Frontend Server
bash
Copy
Edit
cd frontend
npm start
The application will be running at http://localhost:3000/.

🛠 API Endpoints
Method	Endpoint	Description
GET	/api/products	Fetch all products
GET	/api/products/:id	Fetch product details
POST	/api/auth/login	User login
POST	/api/auth/register	User registration
POST	/api/cart	Add item to cart
DELETE	/api/cart/:id	Remove item from cart
🛠 Folder Structure
graphql
Copy
Edit
QuickCart/
│── backend/         # Express.js server
│   ├── models/      # Mongoose models
│   ├── routes/      # API routes
│   ├── controllers/ # Business logic
│   ├── config/      # Database and JWT setup
│── frontend/        # React app
│   ├── src/
│   │   ├── components/  # Reusable UI components
│   │   ├── pages/       # Page components
│   │   ├── redux/       # Redux store setup
🤝 Contribution
Contributions are welcome! Follow these steps to contribute:

Fork the repository
Create a new branch (feature/new-feature)
Commit your changes
Push the changes to your forked repo
Create a Pull Request
📜 License
This project is licensed under the MIT License.

📬 Contact
For any issues or inquiries, contact me via:

📧 Email: mhetreyash242@gmail.com
🔗 GitHub: https://github.com/YashMhetre
🔗 LinkedIn: https://www.linkedin.com/in/yash-mhetre-b775352b6

🌟 Show Support
If you like this project, consider giving it a ⭐ on GitHub!

