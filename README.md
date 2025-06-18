# Niko's Stock Predictions

A fun web application that generates AI-powered stock analysis reports with a humorous twist. The app fetches real stock data and uses OpenAI's GPT-4 to create entertaining, personality-driven investment reports.

## Features

- Add up to 3 stock tickers for analysis
- Real-time stock data from Polygon.io API
- AI-generated reports with colorful trading guru personality
- Responsive web interface
- Disclaimer: "Always correct 15% of the time!" (for entertainment purposes)

## Setup

1. Install dependencies:
   ```bash
   npm install
   ```

2. Create a `.env` file with your API keys:
   ```
   VITE_POLYGON_API_KEY=your_polygon_api_key
   VITE_OPENAI_API_KEY=your_openai_api_key
   ```

3. Run the development server:
   ```bash
   npm run dev
   ```

## Usage

1. Enter stock ticker symbols (e.g., TSLA, AAPL, MSFT)
2. Click "Generate Report" to fetch data and create analysis
3. Enjoy the entertaining AI-generated investment advice

## Tech Stack

- Vanilla JavaScript
- Vite (build tool)
- OpenAI API (GPT-4)
- Polygon.io API (stock data)
- HTML/CSS

## Disclaimer

This application is for entertainment purposes only and does not provide real financial advice. Always consult with qualified financial advisors before making investment decisions.