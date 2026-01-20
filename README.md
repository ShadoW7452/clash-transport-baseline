# Clash Transport Baseline (Mobile)

Clean, mobile-safe Clash configuration intended for **transport-layer routing**
during penetration testing and bug bounty activities.

This repository provides a **baseline configuration only**.
It is designed to be readable, auditable, and safe for public reference.

---

## Purpose

This project exists to:

- Provide a **stable transport layer** for mobile pentesting
- Standardize outbound routing via Clash on Android
- Avoid DNS leaks and accidental direct connections
- Serve as a **reference baseline**, not an operational secret

---

## What This Is

- A **transport & routing baseline**
- Mobile-safe (Android / Clash for Android)
- Uses conservative defaults
- Suitable for:
  - Bug bounty
  - Web/API testing
  - Red team lab environments

---

## What This Is NOT

- ❌ Not a WAF bypass
- ❌ Not anonymization or OPSEC tooling
- ❌ Not a scanning or exploitation framework
- ❌ Not intended to evade detection or controls

Any bypass techniques belong to **tooling and methodology**, not transport config.

---

## Usage

1. Install **Clash for Android**
2. Import `clash-baseline.yaml`
3. Replace all `CHANGE_ME_*` placeholders with your own proxy details
4. Use **Rule mode**
5. Verify routing before testing

Example verification:
```bash
curl https://ifconfig.me
