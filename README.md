# autonomous-crypto-alpha-bot

Autonomous AI Agent for real-time crypto market sentiment, on-chain analytics & automated alerts 🚀📈

## Key Features
- **Real-Time Sentiment Analysis**: Monitors social media and crypto news feeds.
- **On-Chain Analytics**: Tracks whale movements, liquidity flows, and contract updates.
- **Automated Alpha Alerts**: Instant notifications via Telegram/Discord webhooks.

## System Architecture
- Data Ingestion: APIs & WebSockets (CoinGecko, Etherscan, DexScreener).
- AI Engine: LLM sentiment scoring & anomaly detection.
- Alert Pipeline: Automated multi-channel notification engine.

## Configuration Details
Set your API keys in `.env`:
```env
ETHERSCAN_API_KEY=your_key_here
TELEGRAM_BOT_TOKEN=your_token_here
```
