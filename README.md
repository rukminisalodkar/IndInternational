# IndInternational
Full stack web and mobile app designed for Indian students to invest in stocks, ETFs, and bonds in 100+ countries in 27 currencies.


> A brokerage-style investment platform for Indian students and young professionals to invest in global markets — simply, affordably, and transparently.

---

## 🚧 Project Status

This is a **fully designed prototype** — all screens, user flows, and features are functional with mock data. Backend integration with live brokerage and market data APIs is planned for the next phase.

---

## 📸 Screenshots

> _Add screenshots of your app here. Recommended screens to capture:_
> - [ ] Landing / onboarding screen
> - [ ] KYC upload flow
> - [ ] Global portfolio dashboard
> - [ ] Stock detail + order placement screen
> - [ ] Multi-currency wallet
> - [ ] News & AI recommendations feed
> - [ ] Pricing / brokerage comparison page
> - [ ] Alerts & notifications screen

_Replace this section with your actual screenshots once captured:_

```
![Dashboard](screenshots/dashboard.png)
![Trading](screenshots/trading.png)
![News](screenshots/news.png)
```

🎥 **Demo Walkthrough:**

---

## 💡 What is IndInternational?

Most Indian students who want to invest globally face the same problems:

- Traditional banks charge ₹40–₹100 per trade + hidden FX conversion fees
- Existing platforms are designed for experienced investors, not students
- There is no single app that shows a unified INR view of a global portfolio

**IndInternational solves this** by offering:

- Access to stocks, ETFs, and bonds across **100+ countries**
- Support for **27 currencies** with live INR conversion
- Flat, transparent brokerage starting at **₹0–₹20 per trade**
- An **AI-powered news and geopolitics recommendation engine**
- A clean, student-friendly UI with plain-language explanations of finance terms

---

## ✨ Core Features

### 🪪 KYC & Onboarding
- Mobile + email sign-up with OTP verification
- SEBI/FEMA-compliant KYC flow: PAN, Aadhaar, bank account upload
- Encrypted document storage with re-KYC support when regulations change
- Multi-factor authentication (OTP + optional biometrics)

### 📊 Global Portfolio Dashboard
- Holdings broken down by **country**, **asset class** (stocks, ETFs, bonds), and **currency**
- Auto-converted **INR value** for all international holdings
- Total portfolio value, unrealised P&L, sector & country allocation (pie charts)

### 🔍 Universal Search & Watchlists
- Search by ticker (e.g., `AAPL`, `TSLA`), company name, country, or asset class
- Create and manage custom watchlists (e.g., "US Tech", "European ETFs")

### 📈 Trading Workflow
- Buy / Sell with **Market** and **Limit** orders
- **Fractional shares** support for high-priced US stocks
- Pre-trade confirmation screen showing: quantity, price in INR, brokerage fee, FX conversion fee, and net amount
- Real-time price display in local currency + INR equivalent

### 💱 Multi-Currency Wallet
- Fund account in INR; convert to 27 supported currencies in-app
- Separate balances per currency (INR, USD, EUR, GBP, JPY, etc.)
- Live FX rates display (mocked in prototype; designed for live API integration)

### 📰 News & AI Recommendations
- Global macro news: interest rates, inflation, central bank decisions
- Geopolitical news: trade wars, sanctions, elections, regional conflicts
- Sector news: tech, energy, semiconductors, and more
- **AI recommendation engine** that tags insights with:
  - Theme (e.g., "US-China Tensions", "India-EU Tariffs", "Energy Crisis")
  - Risk level (Low / Medium / High)
  - Time horizon (Short-term / Medium-term / Long-term)
- Clickable recommendations: tap "View suggested ETFs" to see 3–5 matching tickers

### 💰 Transparent Pricing
- Flat brokerage: ₹0–₹20 per trade (vs ₹40–₹100 at traditional banks)
- FX conversion fee: 0.3%–0.5%
- No hidden charges — side-by-side comparison with traditional brokers
- Per-trade cost breakdown shown on every order confirmation

### 🔔 Alerts & Notifications
- Set price-level alerts (e.g., "Alert me if AAPL drops below $150")
- Keyword-based news alerts (e.g., "US-China trade", "India-EU tariffs")
- Push notification, email, and in-app alert delivery

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Frontend | React (Web), React Native (Mobile) |
| Backend | Node.js, Express |
| Database | PostgreSQL (planned) |
| Authentication | OTP, JWT, Biometric (planned) |
| Market Data | Mock API (live integration planned) |
| FX Rates | Mock API (live integration planned) |
| News | Mock API — designed for NewsAPI / Bloomberg integration |
| AI Recommendations | Rule-based engine (ML model planned) |
| Storage | Encrypted document storage for KYC |

---

## 🗺️ Planned API Integrations

| Purpose | Provider (planned) |
|---|---|
| Global brokerage & trading | DriveWealth / Alpaca / Interactive Brokers API |
| Real-time stock & ETF quotes | Polygon.io / Yahoo Finance API |
| Live FX rates | Open Exchange Rates / CurrencyLayer |
| Global news | NewsAPI / Bloomberg API |
| KYC / AML verification | Digio / Signzy (India-compliant) |

---

## 🚀 Running Locally

```bash
# Clone the repository
git clone https://github.com/your-username/indinternational.git
cd indinternational

# Install dependencies
npm install

# Start the development server
npm start
```

> The app runs on mock data by default. No API keys are required to run the prototype locally.

---

## 📁 Project Structure

```
indinternational/
├── src/
│   ├── components/        # Reusable UI components
│   ├── screens/           # App screens (Dashboard, Trade, News, etc.)
│   ├── data/              # Mock data (stocks, FX rates, news)
│   ├── utils/             # Helper functions (currency conversion, etc.)
│   └── App.js             # Root component
├── public/
├── screenshots/           # Add your screenshots here
└── README.md
```

---

## ⚠️ Disclaimer

> IndInternational is a **student prototype project** built for learning and portfolio purposes. It is not a registered broker, financial advisor, or SEBI-regulated entity. Investment in foreign securities involves currency risk, geopolitical risk, and regulatory risk. This app does not provide financial advice.

---

## 👩‍💻 Author

Rukmini Salodkar
- 📧 rukmini.salodkar13@gmail.com
- 🔗 [LinkedIn](https://linkedin.com/in/rukmini)
- 🐙 [GitHub](https://github.com/rukminisalodkar)

---

## 📌 Roadmap

- [x] UI prototype with mock data
- [x] KYC onboarding flow
- [x] Portfolio dashboard with INR conversion
- [x] Trading workflow with order confirmation
- [x] News & AI recommendation engine
- [ ] Live brokerage API integration
- [ ] Real-time market data feeds
- [ ] Production KYC/AML verification
- [ ] Mobile app deployment (iOS & Android)
- [ ] Hindi language toggle
