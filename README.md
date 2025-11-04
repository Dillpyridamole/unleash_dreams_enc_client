# Unleash Dreams - Encrypted Client Files

This repository contains the **encrypted client files** for Unleash Dreams MMORPG.

## 🔐 Security

- All files are encrypted with **XChaCha20-Poly1305**
- Files are served via **GitHub Pages** (CDN)
- Manifest is signed with **RSA-4096**

## 📦 Structure

```
.
├── modules/        # Game modules (.lua.enc)
├── data/           # Game data (sprites, sounds)
├── mods/           # Game modifications (.lua.enc)
└── manifest.json   # File index (CRC32 + SHA256)
```

## 🚀 Deployment

Files are automatically deployed to GitHub Pages via workflow:

```bash
# Trigger deployment
git tag v1.0.0
git push origin v1.0.0
```

Or manually via **Actions** tab → **Deploy Encrypted Client Files**

## 🌐 CDN URL

```
https://dillpyridamole.github.io/unleash_dreams_enc_client/
```

## 📊 Stats

- **Files**: ~2093 encrypted files
- **Size**: ~750 MB
- **Bandwidth**: Unlimited (GitHub Pages)

## 🔗 Main Repository

Launcher: [https://github.com/Dillpyridamole/unleash-dreams-launcher](https://github.com/Dillpyridamole/unleash-dreams-launcher)

---

**⚠️ DO NOT DECRYPT OR SHARE THESE FILES**
