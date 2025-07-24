# 📰 News Aggregator

A full-stack **MERN (MongoDB, Express, React, Node.js)** application that displays news articles from various categories using the [NewsAPI.org](https://newsapi.org/) API.

Users can browse current headlines from multiple sources in a clean and responsive React UI.

---

## 🚀 Features

- 🌐 Fetches real-time news from NewsAPI
- 📂 Categories like business, sports, technology, health, and more
- 🧭 Browse and read summaries with source links
- ⚙️ Backend built with Express & Node.js
- 💾 MongoDB (optional for saved articles or future expansion)

---

## 🛠 Tech Stack

- **Frontend**: React  
- **Backend**: Node.js, Express  
- **API**: NewsAPI.org  
- **Database**: MongoDB (if storing favorites)  

---

## 📦 Getting Started

These instructions will help you set up the project locally for development and testing.

### ✅ Prerequisites

- Node.js and npm installed
- NewsAPI API key (get one free at [newsapi.org](https://newsapi.org))

---

## ⚙️ Installation Steps

1. **Fork** and **clone** this repository:

   ```bash
   git clone https://github.com/YourUsername/news-aggregator.git
   cd news-aggregator
Set up the backend:

bash
Copy
Edit
cd server
touch .env
Add your NewsAPI key to the .env file like this:

ini
Copy
Edit
API_KEY=your_news_api_key
Then install dependencies and start the server:

bash
Copy
Edit
npm install
node server.js
Set up the frontend:

bash
Copy
Edit
cd ../client
npm install
npm run dev
Open your browser and go to http://localhost:3000 to view the app.

🧪 Usage
Once the server and client are running, you can:

Browse the latest headlines

View news by category

Click through to full articles from the original source

🤝 Contributing
Pull requests are welcome!
For major changes, please open an issue first to discuss what you'd like to improve.

Please make sure to update tests as needed.

👩‍💻 Author
Kotra Srimythri
B.Tech CSE | Bhoj Reddy Engineering College for Women
💡 MERN Stack | 🌐 Web Dev | 📰 APIs

⭐ Show Support
If you found this project helpful, please consider giving it a ⭐ star on GitHub!
