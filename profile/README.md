# Payload

Programmable revenue infrastructure for the machine economy.

Payload builds the authorization and revenue-evidence layer for paid APIs and agent commerce:

- **Veyline** — the flagship. Non-custodial transaction authorization for customer wallets: authenticated intent → policy evaluation → signed authorization → single-use consumption → settlement verification, with a durable audit trail. Veyline authorizes; it never holds funds.
- **callx402 by Payload — powered by Veyline** — the universal paid action layer. Nine hosted x402 actions your agents can call and pay for per use, with wallet-signed redemption. On npm: [`callx402`](https://www.npmjs.com/package/callx402).
- **RevRule by Payload** — a programmable revenue rules engine: decide who earns what whenever your product makes money, and link verified on-chain payouts back to the entitlement lines that created them, with wallet-signed payout evidence.

## Free tool

**[x402 Manifest Check](https://github.com/marketplace/actions/x402-manifest-check)** — a GitHub Action that validates your `/.well-known/x402` manifest and live 402 challenge, catching the drift that makes paid APIs invisible to buyers. Free; runs in your CI.

## MCP servers

Install any of our MCP servers from its Smithery listing, or from its repo:

- **callx402 by Payload** — pay x402-protected APIs from an AI agent, with free keyless diagnostics (status, check, discover). [Smithery](https://smithery.ai/servers/kyler-simmons-partners/callx402) · [Repo](https://github.com/Payloadhq/callx402)
- **Veyline by Payload** — organization entitlement and usage checks, plus signed, policy-enforced payment preflights (no funds move). Requires a Payload rail API key. [Smithery](https://smithery.ai/servers/kyler-simmons-partners/veyline) · [Repo](https://github.com/Payloadhq/veyline-mcp)
- **RevRule by Payload** — read revenue entitlement graphs, review payout evidence, and dry-run revenue events with zero side effects. Get a free Payload rail access key from the RevRule console at payload-rail.fly.dev, define a graph, and dry-run with simulate. A paid RevRule entitlement is not required to evaluate. [Smithery](https://smithery.ai/servers/kyler-simmons-partners/revrule) · [Repo](https://github.com/Payloadhq/revrule-mcp)

All three are also published in the Official MCP Registry as `io.github.payload-tools/callx402`, `io.github.payload-tools/veyline-mcp`, and `io.github.payload-tools/revrule-mcp`.

## Go deeper

- **Veyline Developer Primer ($79)** — the x402 paid API starter kit: [payloadtools.gumroad.com/l/x402-paid-api-starter-kit](https://payloadtools.gumroad.com/l/x402-paid-api-starter-kit)
- **Hosted API** — https://payload-rail.fly.dev

## Community

Join the Payload Discord, a global community for developers, founders, and operators building with AI agents, payments, and automation: https://discord.gg/Bu9TkvmBxn
