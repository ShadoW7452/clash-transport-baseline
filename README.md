# Clash Transport Baseline

**Purpose:**  
Clean transport-layer Clash configuration for mobile pentesting, bug bounty, and Red Team operations.

**Key Points:**
- Provides stable proxy routing for Android.
- Ensures traffic reaches in-scope targets (e.g., web APIs) safely.
- Helps audit network routing without exposing secrets.
- Does **not bypass WAF logic** — only assists with transport.

**Usage:**
1. Copy the RAW URL of `clash.yaml`.
2. Import it into Clash for Android via **Profiles → Import from URL**.
3. Activate the profile and enable TUN mode + DNS Hijack.

**Disclaimer:**  
- Replace `CHANGE_ME_SERVER` and `CHANGE_ME_PASSWORD` with your own proxy.
- Do **not** include real IPs or credentials in this public repo.
- This config is intended for **educational and authorized pentesting purposes only**.
