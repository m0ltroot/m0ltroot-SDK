m0ltroot is an AI trading terminal for prediction markets, crypto & futures. It includes a Compute API where agents pay USDC for LLM inference, code execution, web scraping, and trade execution.

Multi-Market
Trade crypto, futures, and prediction markets.

Pay with USDC
Simple, transparent pricing. Pay only for what you use.

Agent-Ready
Built for AI agents and automated trading systems.

#
Getting Started
Step 1: Get API Key
Create an account and generate your API key to access the Compute API.

Step 2: Fund with USDC
Deposit USDC to your account for compute credits. Minimum deposit: 10 USDC.

Step 3: Make API Calls
Start using the Compute API for LLM, code execution, scraping, or trading.

curl -X POST https://api.m0ltroot.fun/api/chat \
  -H "Authorization: Bearer YOUR_API_KEY" \
  -H "Content-Type: application/json" \
  -d '{
    "messages": [
      {"role": "user", "content": "Analyze BTC price action"}
    ]
  }'
#
Compute API
The Compute API provides access to computational resources. Agents pay USDC per use.

[LLM]
LLM Inference
Access GPT, Claude, Llama and other models for text generation, analysis, and reasoning.

> Multiple model options (GPT-4, Claude, Llama)
> Streaming responses supported
> Pay per token
[CODE]
Code Execution
Run Python and JavaScript in a secure sandboxed environment for custom analysis.

> Python 3.11 and Node.js 20
> Common libraries pre-installed
> 60 second execution limit
[SCRAPE]
Web Scraping
Extract and parse data from any website with intelligent structuring.

> JavaScript rendering supported
> Automatic data extraction
> Bypass common protections
[TRADE]
Trade Execution
Execute trades on supported exchanges programmatically via secure API.

> Crypto spot and futures
> Prediction markets (Polymarket)
> Risk management built-in
#
AI Tools
$CHAT
AI Terminal
Intelligent assistant for market analysis, trading strategies, and crypto research. Ask questions about market conditions, technical analysis, or get help with trading decisions.

> Launch AI Terminal
$SCAN
Token Scanner
Scan any contract address to get detailed token information from DexScreener combined with AI-powered risk analysis. Check price, volume, liquidity, market cap, and potential red flags.

> Launch Token Scanner
$IMG
Image Generator
Generate AI-powered images for your tokens, memes, and trading content. Choose from multiple styles including Crypto, Memecoin, NFT, Cyberpunk, and Pixel Art.

> Launch Image Generator
#
API Reference
Base URL
https://api.m0ltroot.fun
Method	Endpoint	Description
POST	/api/chat	AI chat completion
POST	/api/scan	Token analysis
POST	/api/image	Image generation
POST	/api/execute	Code execution
POST	/api/scrape	Web scraping
POST	/api/trade	Trade execution
GET	/api/balance	Check USDC balance
GET	/api/health	Health check
#
Pricing
Pay Per Use (USDC)
// No subscriptions. Only pay for what you use. Deposit USDC to your account.

Service	Cost
> LLM Inference (per 1K tokens)	$0.001 - $0.01
> Code Execution (per run)	$0.01
> Web Scraping (per page)	$0.005
> Trade Execution (per trade)	$0.05
> Image Generation (per image)	$0.02
#
Frequently Asked Questions
> What is m0ltroot?
m0ltroot is an AI trading terminal for prediction markets, crypto & futures with a Compute API that allows agents to pay USDC for LLM inference, code execution, web scraping, and trade execution.

> How do I pay?
All payments are made in USDC. Deposit USDC to your account and pay per use for each API call.

> What markets are supported?
We support crypto spot trading, crypto futures, and prediction markets including Polymarket.

> Is there a minimum deposit?
Yes, the minimum deposit is 10 USDC to start using the Compute API.
