# TraceEagle

All-platform network capture and debugging tool — low-level packet capture, automatic decryption and traffic debugging in one. Capture out of the box with zero configuration, and it's free on every platform.

**Languages:** [简体中文](README.md) | English

## Repository Contents

| Directory | Description |
| --- | --- |
| [guide/](guide/) | **User guides**: hands-on tutorials that walk you through each step — from installing and launching, picking the right capture mode and setting up certificate decryption, to reading data, rewriting and replaying traffic, and putting the network toolbox to work |
| [introduce/](introduce/) | **Feature introductions**: what each feature is, what it does, and where it goes beyond ordinary tools — with annotated screenshots |

## Quick Start

- **First time here** → [guide/01-快速开始.md](guide/01-快速开始.md) (Getting Started): capture your first flow within minutes, then read your first decrypted request
- **Want the big picture first** → browse [introduce/](introduce/): each article stands alone and comes with screenshots
- **Stuck on something** → look up your symptom in the "Quick Paths" reference inside the guides

## Key Capabilities

- **Low-level full capture**: per-packet capture at the NIC level — DNS, QUIC, ICMP, ARP and any TCP/UDP traffic are all included, down to Wireshark-grade granularity
- **Precision proxy capture**: rule-driven decryption proxy for HTTP/HTTPS/HTTP2/HTTP3/WebSocket/gRPC, with rewrite and replay support
- **In-app plaintext extraction**: bypasses certificate pinning and private encryption protocols by reading plaintext from inside the app — no MITM certificates involved
- **Mobile capture**: iOS without jailbreak, Android without installing certificates — the same interface and views everywhere
- **Automatic decryption on capture**: no proxy setup, no manual key import, no environment tweaks — session keys are matched automatically and ciphertext turns into plaintext
- **Traffic debugging**: breakpoint interception, rule-based rewriting & mocking, request composer & replay, session replay & load testing (latency percentiles down to p99.9), side-by-side request comparison, custom protocol decoding, code generation, and OpenAPI spec export
- **AI integration**: built-in MCP server exposing 40+ tools as an API (stdio / HTTP transport), running loopback-only on your machine

## Related Links

- Project homepage: https://www.traceeagle.com
