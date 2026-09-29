A Netflix-style streaming UI built with React. It fetches movie and TV data from the TMDB API, supports user authentication with Firebase, and lets users save titles to a personal "My List".

Disclaimer: This project is for educational purposes only. It is not affiliated with or endorsed by Netflix.
Prerequisites
Node.js 18+
A free TMDB API key
A Firebase project with Authentication (Email/Password) and Firestore enabled
Getting Started
1. Clone the repository
bash
git clone https://github.com/<your-username>/netflix-clone.git
cd netflix-clone
2. Install dependencies
bash
npm install
3. Configure environment variables
bash
cp .env.example .env

Fill in .env:

env
VITE_TMDB_API_KEY=your_tmdb_api_key

VITE_FIREBASE_API_KEY=your_firebase_api_key
VITE_FIREBASE_AUTH_DOMAIN=your_project.firebaseapp.com
VITE_FIREBASE_PROJECT_ID=your_project_id
VITE_FIREBASE_STORAGE_BUCKET=your_project.appspot.com
VITE_FIREBASE_MESSAGING_SENDER_ID=your_sender_id
VITE_FIREBASE_APP_ID=your_app_id
4. Run the app
bash
npm run dev

Open http://localhost:5173.
