# AI-Powered Steam Review Viewer

A sleek, modern web app that fetches Steam game reviews and summarizes them using AI — powered by Google Gemini. Perfect for gamers, journalists, and developers who value quick decision insights.

## [Live Demo →](https://ai-powered-steam-review-viewer.vercel.app/)

![Reviewizer screenshot](/github/reviewizer.png)

---

## Features

- **Game Search & Review Fetch**
  - Search games via name or Steam App ID.
  - Fetch and display up-to-date user reviews from Steam seamlessly.

- **AI-Powered Summaries**
  - Uses the **Google Gemini** API to generate concise, human-readable review insights like performance, bugs, and user sentiment.

- **Clean & Responsive UI**
  - Built with **Next.js** and **Tailwind CSS** for smooth navigation and mobile-friendly layouts.

- **Live Demo**
  - Hosted on **Vercel**: _[Insert Live Link Here]_

---

## Tech Stack

| Component         | Technologies                     |
|-------------------|-----------------------------------|
| Framework & UI    | Next.js (React-based)            |
| Language          | TypeScript                       |
| Styling           | Tailwind CSS                     |
| AI Integration    | Google Gemini API                |
| Review Fetching   | Steam Web API / Web Scraping      |
| Deployment        | Vercel                           |

---

## Installation

1. **Clone the repo**
   ```bash
   git clone https://github.com/RayanBhatti/AI-Powered-Steam-Review-Viewer.git
   cd AI-Powered-Steam-Review-Viewer
   ```

2. **Install dependencies**
   ```bash
   npm install
   # or
   yarn install
   ```

3. **Configure Environment**
   - Create a `.env.local` file based on `.env.example`
   - Required variables:
     ```env
     GOOGLE_AI_KEY=your_gemini_key
     ```

4. **Run locally**
   ```bash
   npm run dev
   # or
   yarn dev
   ```

5. Visit `http://localhost:3000` to explore the app.

---

## Usage

- Start typing a game title or App ID to fetch reviews and summaries.
- Click **"Summarize"** to see AI-enhanced insights into reviews: bug trends, sentiment, strengths, weaknesses.
- Easily compare before and after game updates.

---

## Folder Structure

```plaintext
├── components/         # Reusable React components
├── pages/              # Next.js pages
├── styles/             # Global or modular CSS
├── utils/              # API fetchers, data processing
├── public/             # Static assets (images, icons)
├── .env.example        # Example environment variables
├── README.md
└── package.json
```

---

## Contributing

Contributions are welcome!

1. Fork the repo
2. Create a feature branch  
   ```bash
   git checkout -b feature/YourFeature
   ```
3. Commit your changes  
   ```bash
   git commit -m "Add awesome feature"
   ```
4. Push to your branch  
   ```bash
   git push origin feature/YourFeature
   ```
5. Submit a pull request 🎉

---