### TrenchyTools — one API key to launch and trade memecoins

No RPC node, no Jito client, no IPFS keys. Launch and trade on **pump.fun** and **PumpSwap** (Solana) and **pons** (Robinhood Chain) from a single HTTP API. The API builds unsigned transactions, your code signs locally.

**→ [trenchy.tools](https://trenchy.tools)** · [docs](https://trenchy.tools/docs) · [API spec](https://trenchy.tools/openapi.json) · [agent instructions](https://api.trenchy.tools/AGENTS.md) · [X](https://x.com/trenchytools)

```bash
# get a key in one call, then read the agent instructions
curl "https://api.trenchy.tools/api/create-api-key?label=my-agent"
```

**Everything lives in the [Trenchy-Tools](https://github.com/Trenchy-Tools) org:**

- [api](https://github.com/Trenchy-Tools/api) — pitch, quickstart, links
- [pumpfun-starter](https://github.com/Trenchy-Tools/pumpfun-starter) — Solana starter
- [pons-starter](https://github.com/Trenchy-Tools/pons-starter) — Robinhood Chain starter
- [wallet-mover](https://github.com/Trenchy-Tools/wallet-mover) — wallet tooling

Agents: `openclaw skills install trenchytools`

