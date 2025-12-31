## BeyondChats – AI-Powered Article Scraper & Enhancer

A full‑stack MERN project that scrapes articles from the web, stores them in MongoDB, enhances them using an AI model, and displays both original and AI‑enhanced versions in a modern React frontend.
This project was built in 3 clear phases.


## Live Demo (Frontend)
🔗 Deployed Frontend: [https://beyond-chat-task.vercel.app/](https://beyond-chat-task.vercel.app/)
🔗 Deployed Backend: [https://beyondchattask.onrender.com/](https://beyondchattask.onrender.com/)

## Routes for backend link:
https://beyondchattask.onrender.com/api/articles
https://beyondchattask.onrender.com/api/articles?includeAll=true

## Project Architecture

<p align="center">
  <img src="./assets/Project Architecture.png" alt="BeyondChatTask Architecture" width="800"/>
</p>

## Project Phases
🔹 Phase 1 – Web Scraping & Storage
            - Scrapes articles using Puppeteer / Cheerio
            - Stores raw articles in MongoDB
            - Avoids duplicates
            - Saves metadata like title, author, URL, content
            
             
             
             

🔹 Phase 2 – AI Article Enhancement
            - Uses Groq API (free tier)
            - Enhances scraped articles
            - Stores enhanced versions with reference to original article
            - Triggered via API endpoint

🔹 Phase 3 – React Frontend
            - Fetches articles from backend API
            - Displays:
                - Original articles
                - Enhanced (AI‑rewritten) articles

## Tech Stack
Frontend - React.js, Axios, Tailwind CSS, Deployed on Vercel, Responsive, professional UI using Tailwind CSS
Backend - Node.js, Express.js, MongoDB + Mongoose, Puppeteer / Cheerio, AI Enhancement via LLM API, Deployed on Render (Free Tier)
Database - MongoDB Atlas (Cloud)


## ▶️ For Running Locally

Root folder - BeyondChatTask

## 1) Run Backend
   - From root folder, cd backendTaskPhaseOne
   - run npm install
   - run npm run dev
   - open other terminal for scraping (already articles present in DB)
   - From root folder, cd nodeScriptPhaseTwo
   - run npm install
   - run node scraper.js

## 2) Run Frontend
   - From root folder, cd react-phase-three
   - run npm start


## Author - Nagesh Mali
  


