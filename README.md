# 🚀 CryptoTracker

## Overview
CryptoTracker is a modern, real-time cryptocurrency tracking application built with React. Monitor cryptocurrency prices, analyze market trends, and stay updated with the latest crypto market movements.

![CryptoTracker Screenshot](screenshots/demo.png)

## ✨ Features

- 📊 Real-time cryptocurrency price updates
- 💱 Multi-currency support (USD, EUR, INR)
- 📈 Interactive price charts with historical data
- 🔍 Advanced search and filtering capabilities
- 📱 Responsive design for desktop and mobile
- ⚡ Fast and efficient data loading
- 🌐 Global market statistics

## 🛠️ Technologies Used

- React 18
- Vite
- CoinGecko API
- React Router DOM
- React Google Charts
- Context API for state management
- CSS Modules

## 📦 Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/cryptotracker.git
```

2. Navigate to the project directory:
```bash
cd cryptotracker
```

3. Install dependencies:
```bash
npm install
```

4. Create a `.env` file in the root directory:
```bash
VITE_COINGECKO_API_KEY=your_api_key_here
```

5. Start the development server:
```bash
npm run dev
```

## 🚀 Usage

1. Access the application at `http://localhost:5173`
2. Select your preferred currency from the dropdown menu
3. Browse through the list of cryptocurrencies
4. Click on any cryptocurrency to view detailed information
5. Use the search bar to find specific cryptocurrencies

## 📁 Project Structure

```
cryptotracker/
├── src/
│   ├── components/
│   ├── context/
│   ├── pages/
│   ├── assets/
│   └── App.jsx
├── public/
├── vite.config.js
└── package.json
```

## 🔧 Configuration

The application uses the CoinGecko API for cryptocurrency data. You can configure the API settings in `src/context/CoinContext.jsx`.

## 🤝 Contributing

1. Fork the repository
2. Create a new branch: `git checkout -b feature-name`
3. Make your changes and commit: `git commit -m 'Add feature'`
4. Push to the branch: `git push origin feature-name`
5. Submit a pull request


## 🙏 Acknowledgments

- [CoinGecko API](https://www.coingecko.com/en/api) for providing cryptocurrency data
- [React](https://reactjs.org/) team for the amazing framework
- [Vite](https://vitejs.dev/) for the build tooling
- [GreatStack] for reference tutorial