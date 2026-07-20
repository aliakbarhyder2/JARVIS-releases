# J.A.R.V.I.S — MARK XLVIII

**Official downloads for JARVIS, the real-time voice AI assistant by Quad-A Industries.**

This repository contains **compiled Windows binaries only**. Source code is proprietary and not distributed. Every file here is the exact `JARVIS.exe` built by our release CI — nothing else.

---

## Download

**Latest release:** https://github.com/aliakbarhyder2/JARVIS-releases/releases/latest

Grab `JARVIS.exe` from the assets on that page. That's the whole app — no Python, no dependencies, no installer wizard needed. Double-click to run.

Older builds are on the [releases page](https://github.com/aliakbarhyder2/JARVIS-releases/releases). You should always be on the latest — JARVIS auto-updates itself once installed.

**System requirements:**
- Windows 10 or 11, 64-bit
- ~500 MB free disk space
- Internet connection (for the Gemini Live API and updates)
- Microphone
- Google Gemini API key ([free from AI Studio](https://aistudio.google.com/apikey))

---

## Buy a licence

JARVIS requires a valid `.jarvis` licence file to run. Licences are issued personally to you by Quad-A Industries, machine-bound, and non-transferable.

| Plan | Price | Covers |
| --- | --- | --- |
| **Single user - Lifetime Plan** | **75,000 PKR** | 1 computer, 1 user, perpetual |
| **Enterprise - Lifetime Plan** | **700,000 PKR** | 20+ computers, perpetual |

**To buy a licence, email:** **quada.industries@gmail.com**

Include:
- Your name and organisation
- How many computers you need to activate on
- Whether you want single-user or enterprise pricing

We'll reply with the licence file (a `.jarvis` attachment or a paste-friendly code) and payment instructions.

---

## First launch

1. Double-click `JARVIS.exe`
2. Paste your **licence code** (or drop your `.jarvis` file) — sent to you by email
3. Paste your **Gemini API key**
4. Say hello

That's it. JARVIS creates its config folder inside your user profile automatically — no admin rights, no manual setup.

---

## Auto-updates

Once installed, JARVIS silently checks this repository on every launch. When a newer release is published:

- JARVIS says *"Installing an update, sir. I'll be right back."*
- Downloads the new `JARVIS.exe`
- Swaps itself in place and restarts on the new version
- Your licence, API key, memory, and settings all carry over

To disable auto-updates, set `"auto_update": false` in `%LOCALAPPDATA%\JARVIS\config\api_keys.json`.

---

## Legal

Use of `JARVIS.exe` is governed by the [LICENSE](./LICENSE) in this repository. In summary: this is proprietary software. You may use it under a paid licence. You may not modify, redistribute, republish, reverse-engineer, or resell it. **Read the LICENSE file before using the software.**

## Security

See [SECURITY.md](./SECURITY.md) for our vulnerability-reporting policy and what to do if you suspect the `JARVIS.exe` on this repo has been tampered with.

---

## Support & contact

**Email:** quada.industries@gmail.com

This is a downloads-only repository. Issues and pull requests are **not accepted here**.

For sales, licence renewal, activation problems, or bug reports: email us at the address above.

---

© Quad-A Industries. All rights reserved.
