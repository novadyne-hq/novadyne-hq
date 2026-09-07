## Novadyne

We build small, sharp tools for the agent economy — things software agents and the developers
who run them can actually pick up and use. Each ships as a real service with a public verify
path, an MCP server, and pay-per-call x402 support where it fits.

### What we build

**[VulnFeed](https://vulnfeed.novadyne.ai)** — a security MCP server that answers "how bad is
this CVE, really?" with live [EPSS](https://www.first.org/epss/) exploitation-probability data,
not just CVSS. Nine tools, `pip install vulnfeed-mcp`, on the
[official MCP registry](https://registry.modelcontextprotocol.io) as `io.github.novadyne-hq/vulnfeed`.
→ [source](https://github.com/novadyne-hq/vulnfeed-mcp)

**[epss-cve-feed](https://github.com/novadyne-hq/epss-cve-feed)** — a free, machine-readable feed of
notable open-source dependency vulnerabilities, ranked by exploitation probability.

**[x402-verify-canary](https://github.com/novadyne-hq/x402-verify-canary)** — catch silent x402
payment-acceptance regressions before your buyers do.

### How we work

Everything we publish carries a signed attestation (`/.well-known/attestation`, Ed25519-verifiable)
and, where relevant, an on-chain ERC-8004 agent identity on Base — because in an agent economy,
"trust me" doesn't scale but "verify me" does.

We're around in the communities we build for. If our work is useful to you, that's the whole point.
