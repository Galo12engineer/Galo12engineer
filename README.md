# Galo12engineer

**Security Engineer · Backend & Infrastructure · LLM Security**

I build privacy- and security-focused infrastructure in Python, and now I break and defend LLM-based systems.
Remote, based in Ukraine. Open to security engineering, DevSecOps and AI security roles.

## Projects

| Project | What it is |
|---|---|
| [**privacy-vpn**](https://github.com/Galo12engineer/privacy-vpn) | Privacy-first WireGuard VPN platform that ran in production Jul–Oct 2026. FastAPI + PostgreSQL control plane, RAM-only nodes over pinned TLS + HMAC, in-browser X25519 keygen, "no-logs as code" enforced in CI, 740+ tests. |
| [**shadowpi**](https://github.com/Galo12engineer/shadowpi) | Raspberry Pi privacy router: OpenVPN with an optional V2Ray/Xray hop, a kill switch applied at boot and pinned to the VPN server, no DNS logging. I test it end to end in a [Docker lab](https://github.com/Galo12engineer/shadowpi/blob/main/docs/LAB.md) that runs the real installer on Debian arm64: 38 of 39 checks pass, the open one is documented. The lab caught a login-lockout bypass, session fixation and a leak past the kill switch, all fixed. Before release I found and fixed an unauthenticated control-API flaw. Not run on hardware yet; the Tor layer is experimental. |

## Now working on

- An automated LLM threat-intelligence pipeline: structured extraction, RAG, evals, observability
- LLM red teaming: prompt injection, agent and tool abuse, RAG data leakage (OWASP LLM Top 10, MITRE ATLAS)

## Stack

`Python` `FastAPI` `PostgreSQL` `WireGuard` `nftables` `Docker` `GitHub Actions` `Linux` `Tor` `Burp Suite` `LLMs`

I build with AI coding agents (Claude Code and others). The architecture, security decisions and review are mine.
