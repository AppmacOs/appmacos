<div align="center">

<br/>

```
░█████╗░██████╗░██████╗░███╗░░░███╗░█████╗░░█████╗░░█████╗░░██████╗
██╔══██╗██╔══██╗██╔══██╗████╗░████║██╔══██╗██╔══██╗██╔══██╗██╔════╝
███████║██████╔╝██████╔╝██╔████╔██║███████║██║░░╚═╝██║░░██║╚█████╗░
██╔══██║██╔═══╝░██╔═══╝░██║╚██╔╝██║██╔══██║██║░░██╗██║░░██║░╚═══██╗
██║░░██║██║░░░░░██║░░░░░██║░╚═╝░██║██║░░██║╚█████╔╝╚█████╔╝██████╔╝
╚═╝░░╚═╝╚═╝░░░░░╚═╝░░░░░╚═╝░░░░░╚═╝╚═╝░░╚═╝░╚════╝░░╚════╝░╚═════╝░
```

### `v2.0` · macOS Software · Open Source · Verified · Free Forever

<br/>

[![](https://img.shields.io/badge/-Visit_appmacos.com-000000?style=for-the-badge&logo=apple&logoColor=white)](https://appmacos.com/)
[![](https://img.shields.io/badge/-Download_Apps-3eb8f0?style=for-the-badge)](https://appmacos.com/)
[![](https://img.shields.io/badge/-MIT_License-7df0b8?style=for-the-badge)](./LICENSE)

<br/>

> **4,800+ apps · 2.1M downloads · 0 malware incidents · 98.7% trust score**

</div>

---

```
WHAT IS THIS?
─────────────
AppMacOS is not another download site.
It is a security-first, community-driven, open-source index
of macOS software — every single entry verified before listing.

No ads. No sponsored results. No bundled garbage.
Just software. Verified. For Mac.
```

---

## `01` · Numbers That Matter

```
┌─────────────────────────────────────────────────────┐
│                                                     │
│   4,800+   apps indexed and verified                │
│   100%     Apple Notarized                          │
│   2.1M+    downloads served                         │
│   0         malware incidents since launch          │
│   48h       max review time for new submissions     │
│                                                     │
└─────────────────────────────────────────────────────┘
```

---

## `02` · How We Verify Every App

No app goes live without passing all 5 stages:

```
STAGE 1  ──  Static analysis
             └─ entitlements, code signing, binary inspection

STAGE 2  ──  Malware scan
             └─ multi-engine scan, spyware + adware detection

STAGE 3  ──  Apple Notarization
             └─ must pass Gatekeeper — no exceptions

STAGE 4  ──  SHA-256 checksum
             └─ generated, stored, published publicly

STAGE 5  ──  Community review
             └─ 7-day open period before stable listing
```

**Check any download yourself in 10 seconds:**

```bash
shasum -a 256 ~/Downloads/your-app.dmg
# paste the output → compare at appmacos.com/verify
```

---

## `03` · Get Apps

Everything lives at the official portal:

```
https://appmacos.com/
```

**Works on:** macOS 12 Monterey · Ventura · Sonoma · Sequoia
**Chips:** Apple Silicon (M1 → M4) · Intel x86_64

---

## `04` · App Categories

```
┌──────────────────────┬──────────────────────┐
│  🛠  Dev Tools        │  🎨  Design           │
│  📊  Productivity     │  🔐  Security         │
│  🎵  Audio & Music    │  🎬  Video & Media    │
│  🖥  System Utils     │  🤖  AI Tools         │
│  ☁️  Cloud & Backup   │  📁  File Management  │
└──────────────────────┴──────────────────────┘
```

---

## `05` · Submit Your App

```bash
# 1. Fork this repo
# 2. Add your entry to /apps/
# 3. Open a PR titled: [NEW APP] AppName vX.X.X
# 4. We review within 48h
```

Your `/apps/your-app.json` must look like this:

```json
{
  "name"              : "Your App",
  "developer"         : "Your Name",
  "version"           : "1.0.0",
  "category"          : "developer-tools",
  "license"           : "free",
  "website"           : "https://yourapp.com",
  "download_url"      : "https://yourapp.com/release.dmg",
  "sha256"            : "abc123...",
  "apple_notarized"   : true,
  "universal_binary"  : true,
  "min_macos"         : "12.0",
  "description"       : "One clear sentence about what it does."
}
```

```
RULE #1  →  apple_notarized must be true. No exceptions.
RULE #2  →  sha256 must be correct. We verify it.
RULE #3  →  description must be original. No copy-paste from App Store.
```

---

## `06` · Run Locally

```bash
git clone https://github.com/appmacos/appmacos.git
cd appmacos
npm install
npm run dev        # → localhost:3000
npm run audit      # → run full security test suite
```

---

## `07` · Contributing

| What | How |
|---|---|
| 🐛 Broken link / outdated version | [Open an issue](https://github.com/appmacos/appmacos/issues) |
| ➕ New app submission | Follow `05` above |
| 📖 Docs improvement | Edit any `.md` → open PR |
| 🔍 Security audit | See `/security/PIPELINE.md` |
| ⭐ Just want to help | Star the repo — it matters |

---

## `08` · License

```
MIT License
Copyright (c) 2025 AppMacOS

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software to use, copy, modify, merge, publish without
restriction — see LICENSE file for full terms.

Apps listed in this repository retain their own individual licenses.
AppMacOS does not claim ownership of any listed software.
```

---

<div align="center">

```
built for mac users · by mac users
─────────────────────────────────
appmacos.com
```

[![](https://img.shields.io/badge/⌘-appmacos.com-000000?style=for-the-badge)](https://appmacos.com/)

</div>
