# Payload

Programmable revenue infrastructure for the machine economy.

Payload builds the authorization and revenue-evidence layer for paid APIs and agent commerce:

- **Veyline** — the flagship. Non-custodial transaction authorization for customer wallets: authenticated intent → policy evaluation → signed authorization → single-use consumption → settlement verification, with a durable audit trail. Veyline authorizes; it never holds funds.
- **callx402 by Payload — powered by Veyline** — the universal paid action layer. Nine hosted x402 actions your agents can call and pay for per use, with wallet-signed redemption. On npm: [`callx402`](https://www.npmjs.com/package/callx402).
- **RevRule by Payload** — a programmable revenue rules engine: decide who earns what whenever your product makes money, and link verified on-chain payouts back to the entitlement lines that created them, with wallet-signed payout evidence.

## Free tool

**[x402 Manifest Check](https://github.com/marketplace/actions/x402-manifest-check)** — a GitHub Action that validates your `/.well-known/x402` manifest and live 402 challenge, catching the drift that makes paid APIs invisible to buyers. Free; runs in your CI.

## Go deeper

- **Veyline Developer Primer ($79)** — the x402 paid API starter kit: [payloadtools.gumroad.com/l/x402-paid-api-starter-kit](https://payloadtools.gumroad.com/l/x402-paid-api-starter-kit)
- **Hosted API** — https://payload-rail.fly.dev
