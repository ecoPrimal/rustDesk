# 🖥️ rustDesk — AMOEBA Mesh

**Agentic Mesh-Overlay with Encrypted Biometric Authentication**

*The love letter to RustDesk. Take what was given. Give back MORE.*

## What This Is

A sovereign remote desktop mesh running across the ecoPrimals organism — 8 gates, 3 architectures, 2 houses connected by 10G fiber.

RustDesk gave us remote access to our own hardware. Their code is AGPL-3.0. Their relay servers carried our packets for free. AMOEBA is the thank-you: we give back a system that is safer (ZK identity), freer (open mesh relays, no DNS dependency), and smarter (AI-native MCP).

## Architecture

```
eastGate (.244) — relay server (hbbs + hbbr)
  ├── ports: 21115 (NAT test), 21116 (signal), 21117 (relay), 21118 (TCP), 21119 (WS)
  ├── key: 6oVQBFyHHNAJqm1OlS+XvpdoJ5plYrPzJoPTTYlgQdg=
  └── LAN-only relay — no cloud required

Clients:
  eastGate   — relay + client (ID: 19091278)
  sporeGate  — client (ID: 1871544996)
  southGate  — client (connected)
  northGate  — client (config via pony express)
  ironGate   — client (pending SSH key)
  frameGate  — client (USB tether, pending APK)
  grapheneGate — pending (RustDesk APK)
```

## Components

| Layer | Technology | Purpose |
|-------|-----------|---------|
| Remote Desktop | RustDesk core | Screen share, input relay, file transfer |
| Identity | ZK (BLAKE2b) | No plaintext IDs, zero-knowledge proof |
| Relay | songBird mesh | Replaces centralized hbbs/hbbr |
| AI | squirrel MCP | AI-native remote assistance |
| Audit | loamSpine chain | Immutable connection log |
| Browser | coralReef WASM | Access from any browser |

## License

**scyBorg Triple License** — AGPL-3.0 (code) · ORC (mechanics) · CC-BY-SA 4.0 (docs)

All three irrevocable. This is the well, not the tollbooth.

## Part of the Organism

- [inkFish](https://github.com/ecoPrimal/inkFish) — cephalopod intelligence
- [octoPus](https://github.com/ecoPrimal/octoPus) — deployment mesh
- [seaFloor](https://github.com/ecoPrimal/seaFloor) — organism cartography
- [atlasHugged](https://primals.eco/sporeprint/philosophy/) — the philosophy

