
# 🎬 Movie App

A full-stack movie listing web application that displays popular movies and detailed information using a public movie API. Users can view posters, ratings, and descriptions in a visually appealing interface.

## 🧠 Features

- Fetches and displays trending/popular movies
- Movie cards with poster, title, release date, and rating
- Detailed view with full overview and backdrop
- Responsive UI using React
- Backend API built using Express.js and Node.js

## 🛠️ Tech Stack

- **Frontend:** React, HTML, CSS, JavaScript
- **Backend:** Node.js, Express
- **API Source:** TMDb API (or similar movie database)
- **Hosting (Optional):** Vercel (with `vercel.json` config)

## 🗂️ Project Structure

Movie-App-master/
├── client/ # React frontend
│ ├── src/ # React components
│ └── public/ # Static files and HTML template
├── server/ # Node.js backend
│ └── src/ # Backend logic and routes
├── README.md



## 🔧 Requirements

- Node.js (v14+ recommended)
- TMDb API key (get from https://www.themoviedb.org/)
- Vercel CLI (if deploying)

## 🚀 How to Run Locally

### 1. Clone the repo

git clone https://github.com/yourusername/movie-app.git
cd movie-app
2. Set up the backend

cd server
npm install
# (Optional) Set your TMDb API key in a `.env` file
node index.js
3. Set up the frontend

cd ../client
npm install
npm start
The app will run at http://localhost:3000
