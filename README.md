# Vesana

**Self-hosted, multi-tenant infrastructure monitoring for MSPs and homelabs.**
Servers, network and services – push-based over outbound HTTPS 443. No open ports, no VPN on the monitored side.

This repository is the community hub: questions, ideas, bug reports and release notes.
The source code is not public – see [below](#is-vesana-open-source).

[Website](https://vesana.org) · [Live demo](https://demo.vesana.org) · [Docs](https://docs.vesana.org/en/) · [Pricing](https://vesana.org/pricing)

## Install

One command on a fresh Debian/Ubuntu VM (4 GB RAM), as root:

```bash
curl -fsSL https://vesana.org/install | bash
```

Then open `https://<your-address>/setup` and follow the wizard. Details: [installation guide](https://docs.vesana.org/en/installation/).

The Community Edition is free for up to 25 hosts and includes the AI/MCP access.

## AI integration (MCP)

Connect Claude or any MCP client and let it read – or, if you allow it, set up – your monitoring.
Every AI user gets its own account with read-only, read+write or full access, optionally limited to single tenants, and every action ends up in the audit log.
→ [AI & API access](https://docs.vesana.org/en/administration/ki-zugang/)

## Getting help

| You want to… | Go to |
|---|---|
| Ask a question | [Discussions → Q&A](../../discussions) |
| Suggest a feature | [Discussions → Ideas](../../discussions) |
| Report a bug | [Issues](../../issues) |
| Report a security issue | **Not** in public – see [SECURITY.md](SECURITY.md) |
| Talk about licenses | hello@vesana.org |

## Is Vesana open source?

No. Vesana is proprietary software. Instead, you get commitments that protect you from the usual risks of closed software:

- **Free Community Edition** – 25 hosts, no time limit.
- **Permanent fallback license** after 12 paid months.
- **Price protection** – capped increases, announced 90 days in advance.
- **No feature clawbacks** – what is in your edition stays in it.
- **Your data stays yours** – in your own PostgreSQL, on your own server.
- **Source code release** to existing customers if development stops for 12 months.

Full details: [vesana.org/fairness](https://vesana.org/fairness)

---

Made in South Tyrol.
