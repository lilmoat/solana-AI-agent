# Solana AI Meme Agent

A powerful AI-powered meme coin influencer agent built. This agent autonomously manages social media presence, trading strategies, and community engagement for meme tokens on Solana.

## Features

### Social Media Management
- Automated Twitter posts and engagement
- Discord bot with command handling
- AI-powered content generation using Groq
- Sentiment analysis for responses
- Rate-limited message processing queue

### Trading & Token Management 
- Automated trading via Jupiter DEX
- Market analysis and trading signals
- LP position management
- Token deployment and management
- Risk analysis and trade execution

### AI Integration
- Uses Groq for fast inference
- Context-aware responses
- Meme content generation
- Market sentiment analysis
- Trading opportunity analysis

## Technologies Used

- **Blockchain**
  - Solana Web3.js
  - Jupiter DEX Integration  
  - SolanaAgentKit
  - Helius RPC
  - Meteora LP Protocol
  - Crossmint

- **AI/ML**
  - Groq SDK
  - Mixtral 8x7B Model
  - Sentiment Analysis
  - Context Management

- **Social Media**
  - Twitter API v2
  - Discord.js
  - Message Queue System

## Installation

```bash
# Clone the repository
git clone https://github.com/lilmoat/solana-AI-agent.git

# Install dependencies
cd solana-AI-agent
npm install

# Setup environment variables
cp .env.example .env
# Add your API keys and configuration
```

## Configuration

Create a `.env` file with:

```env
SOLANA_PRIVATE_KEY=your_private_key
SOLANA_RPC_URL=your_rpc_url
GROQ_API_KEY=your_groq_api_key
TWITTER_API_KEY=your_twitter_api_key
DISCORD_TOKEN=your_discord_token
```

## Usage

```bash
# Start the agent
npm start

# Run in development mode
npm run dev

# Run tests 
npm test
```

## Commands

### Discord Commands
- `!price` - Get current token price
- `!stats` - View token statistics
- `!trade` - Execute a trade
- `!help` - List available commands

## Architecture

```
src/
├── config/         # Configuration files
├── services/       # Core services
│   ├── ai.ts       # AI service
│   ├── social.ts   # Social media service
│   └── trading.ts  # Trading service
├── utils/          # Utility functions
└── index.ts        # Main entry point
```

## Integration with Hackathon Sponsors

- **ai16z/Eliza** - Multi-agent simulation framework
- **Jito** - MEV and transaction bundling
- **Jupiter** - Token swaps and routing
- **Helius** - RPC and transaction management
- **Crossmint** - Wallet management
- **Meteora** - LP and DeFi integrations

## Security

- Rate limiting for API calls
- Secure key management
- Transaction verification
- Error handling and logging

## Testing

```bash
# Run unit tests
npm run test

# Run integration tests
npm run test:integration
```

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## Contact

Telegram: @lilm0at



