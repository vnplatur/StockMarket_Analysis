CryptoTracker
A lightweight JavaScript single-page app for browsing cryptocurrencies — supports pagination, sorting by high/low values, marking favorites, and quick details for each coin.

🔗 Live Demo: CryptoTracker

📌 Features
📊 Browse cryptocurrencies with current price and 24h change.

📄 Pagination — client-side or server-driven depending on API.

↕ Sorting by price, market cap, and 24h change (ascending/descending).

⭐ Favorites — mark/unmark coins; saved in localStorage.

🔍 Search/filter by coin name or symbol.

📱 Responsive UI — works on desktop & mobile.

🔄 Price refresh — manual refresh or optional auto-refresh interval.

🛠 Tech Stack
JavaScript (ES6+) — Core functionality

HTML5 & CSS3 — UI structure & styling

Optional CSS Framework — Tailwind / Bootstrap

Fetch API (or axios) — to call a crypto price API (CoinGecko / CoinMarketCap)

localStorage — favorites & client-side caching

🎯 How It Works
Fetches cryptocurrency data from an API using Fetch API or axios.

Displays the data in a paginated list with sorting & filtering options.

Allows users to mark favorites, which are stored locally.

Updates UI dynamically for a smooth single-page experience.

📂 Project Structure
pgsql
Copy
Edit
crypto-tracker/
│── index.html
│── style.css
│── script.js
│── README.md
│── assets/
🚀 Getting Started
1️⃣ Clone the repository
bash
Copy
Edit
git clone https://github.com/your-username/crypto-tracker.git
2️⃣ Open in browser
Simply open index.html in your favorite browser — no server required!

🤝 Contributing
Contributions are welcome!

Fork the project

Create a feature branch (git checkout -b feature/new-feature)

Commit changes (git commit -m 'Add some feature')

Push to branch (git push origin feature/new-feature)

Open a Pull Request
