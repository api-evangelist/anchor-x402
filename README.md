# anchor-x402

anchor-x402 operates a pay-per-call API surface for AI agents, billed with the x402 HTTP payment
protocol instead of API keys or accounts. Eighteen stateless services run behind
https://api.anchor-x402.com; each returns an x402 v2 402 PaymentRequired challenge settled per request
in USDC on Base or Solana (select routes also settle JPYC on Polygon).

- https://anchor-x402.com
