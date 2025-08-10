# Reviewizer

AI-Powered Steam Review Viewer
A sleek, modern web app that fetches Steam game reviews and summarizes them using AI—powered by Google Gemini. Perfect for gamers, journalists, and developers who value quick decision insights.

![Reviewizer screenshot](/github/reviewizer.png)

Features
Game Search & Review Fetch

Search games via name or Steam App ID.

Fetch and display up-to-date user reviews from Steam seamlessly.

AI-Powered Summaries

Uses the Google Gemini API to generate concise, human-readable review insights, like performance, bugs, and user sentiment.

Clean & Responsive UI

Built with Next.js and Tailwind CSS for smooth navigation and mobile-friendly layouts.

Live Demo

Hosted on Vercel: (insert your live link here)

Tech Stack
Component	Technologies
Framework & UI	Next.js (React-based)
Language	TypeScript
Styling	Tailwind CSS
AI Integration	Google Gemini API
Review Fetching	Steam Web API / Web Scraping
Deployment	Vercel

Installation
Clone the repo

bash
Copy
Edit
git clone https://github.com/RayanBhatti/AI-Powered-Steam-Review-Viewer.git
cd AI-Powered-Steam-Review-Viewer
Install dependencies

bash
Copy
Edit
npm install
# or
yarn install
Configure Environment

Create a .env.local file based on .env.example

Required variables:

ini
Copy
Edit
NEXT_PUBLIC_GEMINI_API_KEY=your_gemini_key
Run locally

bash
Copy
Edit
npm run dev
# or
yarn dev
Visit http://localhost:3000 to explore the app.

Usage
Start typing a game title or App ID to fetch reviews and summaries.

Click “Summarize” to see AI-enhanced insights into reviews: bug trends, sentiment, strengths, weaknesses.

Easily compare before and after game updates.

Screenshots
(Insert annotated screenshots showing search, review results, AI summary output, etc.)

Folder Structure
bash
Copy
Edit
├── components/         # Reusable React components
├── pages/              # Next.js pages
├── styles/             # Global or modular CSS
├── utils/              # API fetchers, data processing
├── public/             # Static assets (images, icons)
├── .env.example        # Example environment variables
├── README.md
└── package.json
Contributing
Contributions are hugely welcome!

Fork it

Create a feature branch (git checkout -b feature/YourFeature)

Commit your changes (git commit -m 'Add awesome feature')

Push to your branch, submit a pull request

License
MIT License — see LICENSE for details.
