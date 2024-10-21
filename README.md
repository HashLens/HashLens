# HashLens

## Overview
HashLens is a comprehensive web application designed to empower Bitcoin (BTC) miners and mining software companies with advanced tools for tracking revenue, analyzing profitability, and forecasting future earnings. By integrating real-time data, historical analysis, and predictive modeling, HashLens enables users to make informed decisions and optimize their mining operations.

## Key Features

### Profitability Calculator
- Input mining power (TH/PH/EH) and operational costs (electricity, hardware, maintenance).
- Calculate real-time profitability, historical revenue, and projected profit trends.
- Convert mining rewards from BTC to USD or local currencies.

### Real-Time Monitoring
- Access up-to-the-minute Bitcoin network metrics:
  - Current Block Height
  - Current Hashrate
  - Difficulty Adjustment Countdown
  - Total BTC Mined Per Day
- Receive alerts for significant changes in network difficulty or hashrate.

### Historical Data Visualization
- Interactive graphs displaying:
  - Hashrate over time (with 2016-block EMA smoothing).
  - BTC rewards per TH/s per day over customizable periods.
  - Mining difficulty and block rewards history.
- Graph customization:
  - Symlog scale for detailed views of low-value changes and large spikes.
  - Zoom in/out on specific timeframes.
  - Export data in CSV, JSON, or PDF formats.

### Wallet Address Revenue Tracking
- Monitor income from specific wallet addresses or mining pools.
- View real-time and historical revenue associated with each address.
- Automatic calculation of revenue generated per miner.

### Projection Tools
- Forecast future revenue using advanced models:
  - Exponential Moving Averages (EMA)
  - Rainbow Charts for BTC price trends
- Simulate profitability scenarios based on varying difficulty and hashrate trends.
- Customize inputs for tailored projections.

### API Access
- Export mining performance and profitability data via a robust API.
- API endpoints include:
  - Real-time BTC block data (block height, difficulty, timestamp).
  - Wallet-specific revenues and miner data.
  - Historical data ranges with customizable queries.
- Data available in JSON format for seamless integration into custom workflows.

## Objectives

### Optimize Mining Operations
- Provide actionable insights to improve efficiency and reduce costs.
- Enable miners to maximize profitability through data-driven strategies.

### Enhance Decision-Making
- Offer detailed analytics and projections to support strategic planning.
- Assist in evaluating the impact of operational changes on revenue.

### Streamline Data Access
- Facilitate easy access to critical mining data through an intuitive dashboard.
- Enable integration with existing systems via API for custom workflows.

## Technologies Used

### Front-End
- **Framework**: Next.js (React)
- **State Management**: Redux Toolkit
- **Charting Library**: Recharts
- **Styling**: Tailwind CSS
- **Data Fetching**: SWR (Stale-While-Revalidate)
- **Real-Time Communication**: Socket.io

### Back-End
- **Environment**: Node.js with TypeScript
- **Framework**: NestJS
- **API Development**: GraphQL with Apollo Server
- **Real-Time Data Handling**: Socket.io Server
- **Authentication**: Supabase Auth
- **External API Integration**: Bitcoin Core RPC or Third-Party APIs
- **Caching**: Redis

### Database
- **Primary Database**: Supabase (PostgreSQL)
- **Time-Series Data Handling**: TimescaleDB Extension
- **ORM**: Prisma

### Deployment and Tools
- **Front-End Hosting**: Vercel
- **Back-End Hosting**: DigitalOcean App Platform
- **Monorepo Management**: Nx
- **CI/CD**: GitHub Actions
- **Testing**: Jest, React Testing Library, Cypress
- **Performance Monitoring**: Sentry

## Getting Started
Detailed instructions for setting up the development environment, installing dependencies, and running HashLens will be provided in the repository's README.

## Contributing
We welcome contributions from the community to enhance HashLens. Please read our Contributing Guidelines for more information on how to get involved.

## License
This project is licensed under the MIT License.

HashLens aims to be the go-to platform for BTC miners seeking to gain deeper insights into their operations and stay ahead in the dynamic world of cryptocurrency mining.
