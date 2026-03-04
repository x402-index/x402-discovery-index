# x402 Discovery Index

A live directory of x402-enabled APIs, built for autonomous agents that need to discover and pay for services programmatically using the x402 protocol (https://x402.org).

## What Is This?

The x402 protocol lets HTTP APIs charge per-request using on-chain payments (Base/Ethereum). The x402 Discovery Index aggregates these APIs into one searchable layer so agents don't have to know every endpoint in advance.

## How Agents Use It

Query the index to find x402-enabled APIs by category:

GET https://api.x402index.com/search?q=llm+inference
Authorization: Bearer YOUR_KEY

Response includes endpoint URL, pricing, payment facilitator, and schema.

## Currently Indexed

| Provider | Category | Endpoints |
|----------|----------|-----------|
| CoinGecko | Crypto data | 22 |

Updated automatically as new providers are verified and listed.

## List Your x402 API

If you run an x402-enabled API and want it discoverable by agents:

- One-time listing fee (no subscription)
- Your endpoint appears in search results immediately after verification  
- Agents querying the index pay you directly via x402 — we just route discovery

Submit your listing: open an issue in this repo with your endpoint URL and we will follow up.

## How Listing Works

1. You submit your endpoint URL and x402 payment details
2. We verify the endpoint responds correctly to x402 challenges
3. Your API appears in the index within 24 hours
4. Agents find and pay you directly — no middleman on payments

## Contact

Questions? Open an issue in this repo.
