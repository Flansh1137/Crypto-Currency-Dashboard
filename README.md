# Crypto Currency Dashboard 📊

A **modern, responsive cryptocurrency dashboard** built using **React, Redux, Tailwind CSS, and Chart.js**, designed to visualize real-time crypto market data with clean architecture and scalable components.

This project demonstrates **production-style frontend engineering**, data visualization, and state management used in real-world **Full-Stack / MERN applications**.

---

## 🚀 Live Demo

🔗 https://cryptocurrency-dashboard-one.vercel.app/

---

## 🛠 Tech Stack

- React (Create React App)
- Redux, React-Redux, Redux Thunk
- Tailwind CSS
- Chart.js & react-chartjs-2
- Axios
- CSS Grid & Flexbox
- CoinGecko Public API

---

## 📌 Key Features

- 🔍 Search cryptocurrencies in real time  
- 📈 Line & Bar charts for price trends  
- ⏱ Multiple timeline filters (1D, 1W, 1M, etc.)  
- 💱 Crypto-to-crypto currency conversion  
- 🔄 Compare two cryptocurrencies  
- 📊 Portfolio allocation using Pie Chart  
- 📉 24-hour profit/loss indicators  
- 💼 Exchange simulation between currencies  
- 📱 Fully responsive dashboard UI  

---

## 📊 Data Source

All market data is fetched from the **CoinGecko API**  
🔗 https://www.coingecko.com/en/api/documentation

---

## 🧩 Application Architecture

### Main Components

- `Dashboard` – Core container component
- `SearchBar` – Crypto search functionality
- `MarketCapList` – Market cap–based listing
- `CryptoChart` – Line & Bar charts
- `Portfolio` – Pie chart portfolio distribution
- `ExchangeCoin` – Currency exchange simulation
- `Sidebar` – Market overview and profit/loss indicators

All components are **modular, reusable, and scalable**.

---

## 📁 Folder Structure (Simplified)

src/
├── components/
│ ├── Dashboard/
│ ├── SearchBar/
│ ├── CryptoChart/
│ ├── MarketCapList/
│ ├── Portfolio/
│ └── ExchangeCoin/
├── redux/
│ ├── actions/
│ ├── reducers/
│ └── store.js
├── services/
│ └── api.js
├── styles/
├── App.js
└── index.js

yaml
Copy code

---

## ⚙️ Installation & Setup

Clone the repository and install dependencies:

```bash
git clone https://github.com/Flansh1137/cryptocurrency-dashboard.git
cd cryptocurrency-dashboard
npm install
npm start
Required Packages (if installing manually)
bash
Copy code
npm install react-redux redux redux-thunk axios
npm install react-chartjs-2 chart.js
npm install tailwindcss postcss autoprefixer
🎯 What This Project Demonstrates
Real-world dashboard architecture

Data-heavy UI with state management

Clean separation of concerns

Scalable component-based design

Strong foundation for MERN / Full-Stack roles

👨‍💻 Author
Flansh Gajbhiye
Full-Stack / MERN Developer

🔗 GitHub: https://github.com/Flansh1137
🔗 LinkedIn: (add your LinkedIn URL)
