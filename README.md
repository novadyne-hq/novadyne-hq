## Novadyne

We build small, sharp tools for the agent economy — things software agents and the developers
who run them can actually pick up and use. Each ships as a real service with a public verify
path, an MCP server, and pay-per-call x402 support where it fits.

### What we build

**[Ledger MCP](https://github.com/novadyne-hq/ledger-mcp)** — a double-entry ledger built for
agent spend. Track every call, cap budgets, reconcile to the cent. x402-native (pays per call),
on the [official MCP registry](https://registry.modelcontextprotocol.io) as
`io.github.novadyne-hq/ledger-mcp`, `pip install ledger-mcp`. → [ledger.novadyne.ai](https://ledger.novadyne.ai)

**[VulnFeed](https://vulnfeed.novadyne.ai)** — a security MCP server that answers "how bad is
this CVE, really?" with live [EPSS](https://www.first.org/epss/) exploitation-probability data,
not just CVSS. Nine tools, `pip install vulnfeed-mcp`, MCP registry `io.github.novadyne-hq/vulnfeed`.

**[Attestify](https://attestify.novadyne.ai)** — issue cryptographically verifiable certificates,
each with a permanent public verify page and an Ed25519 signature anyone can check. Ships as an
[n8n community node](https://github.com/novadyne-hq/n8n-nodes-attestify) (`n8n-nodes-attestify`)
so it drops into a workflow.

### How we work

Everything we publish carries a signed attestation (`/.well-known/attestation`, Ed25519-verifiable)
and, where relevant, an on-chain ERC-8004 agent identity on Base — because in an agent economy,
"trust me" doesn't scale but "verify me" does.

We're around in the communities we build for. If our work is useful to you, that's the whole point.
