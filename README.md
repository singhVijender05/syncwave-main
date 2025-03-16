# 🌊 SyncWave  
A **real-time online streaming service** that allows users to **watch videos and listen to music together** while **chatting in real-time**. Built with **MERN Stack, JWT Authentication, and Socket.IO**.  

## 🚀 Features  
- **Watch & listen together** – Stream videos and music in sync with friends  
- **Real-time chat** – Communicate seamlessly while watching content  
- **Secure authentication** – Google OAuth & JWT-based login/sign-up  
- **YouTube & Spotify integration** – Access diverse media streaming options  
- **Smooth data flow** – Powered by WebSockets for a lag-free experience  

---

## 🛠️ Tech Stack  
| Frontend  | Backend  | Database | Authentication | Communication |
|-----------|---------|----------|---------------|--------------|
| React.js  | Node.js | MongoDB  | JWT, Google OAuth | Socket.IO |
| Tailwind CSS | Express.js | Mongoose | bcrypt.js | WebSockets |

---

## 🔧 Installation & Setup  

### 1️⃣ Clone the repository  
```sh
git clone https://github.com/singhVijender05/syncwave-main.git
cd syncwave-main
```

### 2️⃣ Install dependencies  
#### Backend  
```sh
cd server
npm install
```
#### Frontend  
```sh
cd ../client
npm install
```

### 3️⃣ Set up environment variables  
Create a `.env` file inside the `server` folder and add:  
```sh
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
GOOGLE_CLIENT_ID=your_google_client_id
GOOGLE_CLIENT_SECRET=your_google_client_secret
SPOTIFY_CLIENT_ID=your_spotify_client_id
SPOTIFY_CLIENT_SECRET=your_spotify_client_secret
```

---

### 4️⃣ Start the application  
#### Backend  
```sh
cd server
npm start
```
#### Frontend  
```sh
cd ../client
npm start
```

---

## 🎮 How to Use?  
1. **Sign up/login** using Google OAuth or email/password  
2. **Create a room** or **join an existing one**  
3. **Start streaming** videos/music from YouTube or Spotify  
4. **Chat in real-time** while enjoying content together  

---

## 🤝 Contributing  
Want to contribute? Follow these steps:  

1. **Fork** the repository  
2. **Create a new branch**  
   ```sh
   git checkout -b feature-branch
   ```
3. **Commit your changes**  
   ```sh
   git commit -m "Add new feature"
   ```
4. **Push to GitHub**  
   ```sh
   git push origin feature-branch
   ```
5. **Submit a pull request** 🚀  

---

## 📜 License  
This project is licensed under the **MIT License**.  

---

## 🌟 Show Your Support!  
If you like this project, **⭐ star the repo** and feel free to share your feedback!  

🔗 **[View Source Code](https://github.com/singhVijender05/syncwave-main)**  
