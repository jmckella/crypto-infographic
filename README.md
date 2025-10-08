# 💰 Crypto Titans: A Comparative Analysis

An interactive, single-file web application providing comparative analysis and educational insights into three major cryptocurrencies: Bitcoin (BTC), Ethereum (ETH), and XRP.

**[🚀 Live Demo](https://jmckella.github.io/crypto-infographic/)**

## Overview

This web application combines real-time market data with interactive visualizations to help users understand and compare major cryptocurrencies. Built with modern web technologies, it requires no installation or build process—just open and explore.

## Features

### 📊 Real-Time Market Data
- Live price feeds for BTC, ETH, and XRP via the CoinGecko API
- Automatic data refresh and updates

### 🧮 Interactive Investment Calculator
- Project potential returns based on investment amount
- Toggle between 5-year (2030) and 10-year (2035) horizons
- Support for multiple currency inputs
- High-end projection scenarios based on market maturity assumptions

### 📈 Dynamic Visualizations
Built with Chart.js, featuring:
- **Transaction Speed Comparison**: Bar chart showing confirmation time differences
- **Market Behavior Profile**: Radar chart comparing volatility and Bitcoin correlation
- **Long-Term Projections**: Logarithmic scale comparison of price targets

### 📚 Educational Resources
- Switchable outlook tabs with detailed analysis for each cryptocurrency
- Curated links to reputable sources
- Resources on sound money principles and XRPL documentation

## Tech Stack

| Component | Technology |
|-----------|-----------|
| Structure | HTML5 |
| Styling | Tailwind CSS (CDN) |
| Interactivity | Vanilla JavaScript |
| Data Visualization | Chart.js (CDN) |
| Market Data | CoinGecko API |

## Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- Internet connection (for CDN resources and API calls)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/jmckella/crypto-infographic.git
```

2. Open the file:
```bash
cd crypto-infographic
open index.html  # macOS
# or simply double-click the HTML file
```

That's it! No build process, no dependencies to install.

### Usage

1. **View Real-Time Prices**: Current market prices display automatically on page load
2. **Calculate Projections**: 
   - Enter your investment amount
   - Select your preferred currency
   - Toggle between 5-Year and 10-Year outlooks
   - View projected returns for each cryptocurrency
3. **Explore Charts**: Interact with various data visualizations to understand comparative metrics
4. **Read Analysis**: Switch between coin-specific outlook tabs for detailed insights

## Project Structure

```
crypto-infographic/
├── index.html          # Main application file (self-contained)
└── README.md          # Documentation
```

## Important Disclaimers

⚠️ **Investment Warning**: This tool is for educational and informational purposes only. It is **not financial advice**.

- **Price Projections**: All 5-year and 10-year price targets are high-end qualitative projections based on specific market maturity and adoption assumptions
- **No Guarantees**: Past performance and projections do not guarantee future results
- **Do Your Research**: Always conduct thorough research and consult with financial advisors before making investment decisions
- **Risk**: Cryptocurrency investments carry significant risk, including the potential loss of principal

## API Notes

- Uses CoinGecko's free API for real-time price data
- No API key required for basic functionality
- Rate limits apply per CoinGecko's terms of service

## Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/jmckella/crypto-infographic/issues).

## License

This project is open source and available under the [MIT License](LICENSE).

## Acknowledgments

- [CoinGecko](https://www.coingecko.com/) for providing cryptocurrency market data
- [Chart.js](https://www.chartjs.org/) for visualization capabilities
- [Tailwind CSS](https://tailwindcss.com/) for styling framework

---

**Disclaimer**: Cryptocurrency prices are highly volatile. This application provides information based on current market data and speculative projections. Always invest responsibly and never invest more than you can afford to lose.
