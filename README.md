## AI-Powered Article Scraper & Enhancer

A full‑stack MERN project that scrapes articles from the web, stores them in MongoDB, enhances them using an AI model, and displays both original and AI‑enhanced versions in a modern React frontend.
This project was built in 3 clear phases.


## Live Demo (Frontend)
- 🔗 Deployed Frontend: [https://beyond-chat-task.vercel.app/](https://beyond-chat-task.vercel.app/) <br/>
- 🔗 Deployed Backend: [https://beyondchattask.onrender.com/](https://beyondchattask.onrender.com/) <br/>

## Routes for backend link: <br/>
https://beyondchattask.onrender.com/api/articles <br/>
https://beyondchattask.onrender.com/api/articles?includeAll=true <br/>

## Project Architecture

<p align="center">
  <img src="./assets/Project Architecture.png" alt="BeyondChatTask Architecture" width="800"/>
</p>

## Project Phases
🔹 Phase 1 – Web Scraping & Storage <br/>
            - Scrapes articles using Puppeteer / Cheerio <br/>
            - Stores raw articles in MongoDB <br/>
            - Avoids duplicates <br/>
            - Saves metadata like title, author, URL, content <br/>
            
             
             
             

🔹 Phase 2 – AI Article Enhancement <br/>
            - Uses Groq API (free tier) <br/>
            - Enhances scraped articles <br/>
            - Stores enhanced versions with reference to original article <br/>
            - Triggered via API endpoint <br/>

🔹 Phase 3 – React Frontend <br/>
            - Fetches articles from backend API <br/>
            - Displays: <br/>
                - Original articles <br/>
                - Enhanced (AI‑rewritten) articles <br/>

## Tech Stack
Frontend - React.js, Axios, Tailwind CSS, Deployed on Vercel, Responsive, professional UI using Tailwind CSS <br/>
Backend - Node.js, Express.js, MongoDB + Mongoose, Puppeteer / Cheerio, AI Enhancement via LLM API, Deployed on Render (Free Tier) <br/>
Database - MongoDB Atlas (Cloud) <br/>


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
  


