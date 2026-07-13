# 🔐 Two-Factor Authenticator

A secure **Two-Factor Authentication (2FA)** web application that adds an extra layer of security to user authentication. The system verifies users through a second authentication factor, helping protect accounts from unauthorized access.

---

## 📖 Overview

The **Two-Factor Authenticator** enhances traditional username and password authentication by requiring users to complete an additional verification step. This significantly improves account security and reduces the risk of unauthorized access.

---

## ✨ Features

- 🔐 Secure User Authentication
- 👤 User Registration & Login
- 📱 Two-Factor Authentication (2FA)
- 🔑 OTP Verification
- 🛡️ Enhanced Account Security
- ⚡ Fast and Responsive Interface
- 📊 User-Friendly Dashboard

---

## 🛠️ Tech Stack

### Frontend
- React.js
- HTML5
- CSS3
- JavaScript

### Backend
- Node.js
- Express.js

### Database
- MongoDB

### Security
- JWT Authentication
- Two-Factor Authentication (2FA)
- OTP Verification

---

## 📂 Project Structure

```text
Two-Factor-Authenticator/
│
├── frontend/          # React frontend
├── backend/           # Express backend
├── package.json
├── .env.example
└── README.md
```

---

## 🚀 Installation

### 1. Clone the Repository

```bash
git clone https://github.com/Sona-Ahirwar/Two-Factor-Authenticator.git
```

### 2. Navigate to the Project

```bash
cd Two-Factor-Authenticator
```

### 3. Install Dependencies

**Backend**

```bash
cd backend
npm install
```

**Frontend**

```bash
cd frontend
npm install
```

---

## ⚙️ Environment Variables

Create a `.env` file inside the backend directory.

Example:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
OTP_SECRET=your_otp_secret
```

---

## ▶️ Running the Application

### Start Backend

```bash
cd backend
npm start
```

### Start Frontend

```bash
cd frontend
npm start
```

The application will be available at:

```text
Frontend: http://localhost:3000
Backend:  http://localhost:5000
```

---

## 🔄 Workflow

1. Register a new account.
2. Log in using your email/username and password.
3. Receive or generate a One-Time Password (OTP).
4. Enter the OTP for verification.
5. Access your account securely after successful authentication.

---

## 🎯 Future Enhancements

- QR Code Authentication
- Google Authenticator Integration
- Email-Based OTP
- SMS-Based OTP
- Backup Recovery Codes
- Remember Trusted Devices
- Multi-Device Support
- Password Reset with 2FA

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository.
2. Create a feature branch.

```bash
git checkout -b feature-name
```

3. Commit your changes.

```bash
git commit -m "Add new feature"
```

4. Push the branch.

```bash
git push origin feature-name
```

5. Open a Pull Request.

---

## 👩‍💻 Author

**Sona Ahirwar**

GitHub: https://github.com/Sona-Ahirwar

---

## 📄 License

This project is licensed under the MIT License.

---

## ⭐ Support

If you found this project useful, please consider giving it a ⭐ on GitHub.# Two-Factor-Authenticator
