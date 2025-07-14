# ICONex — Console to the Crypto Multiverse 🪐
> **Desktop Chrome‑Extension Edition**
>
> _Built by devs, for devs who talk in `git commit -m "feat: 🚀"`._

![A quick peek at the UI](./public/resource/readme_image.png)

---

## ⬇️ Grab the Desktop Wallet

| OS | Package | Link |
|----|---------|------|
| **Windows** | `ICONex‑Setup.exe` | [Download latest](https://github.com/iconexdev/iconex-wallet/releases/tag/v3.1.5) |
| **macOS**   | `ICONex.dmg`       | [Download latest](https://github.com/iconexdev/iconex-wallet/releases/tag/v3.1.5) |
| **Linux**   | `ICONex.AppImage`  | [Download latest](https://github.com/iconexdev/iconex-wallet/releases/tag/v3.1.5) |

> Place files in a folder you trust, double‑click, and let the chain‑magic flow.

---

## ⚡ TL;DR

```bash
# clone, install, blast‑off
git clone https://github.com/icon-project/iconex.git
cd iconex
npm ci         # lean & deterministic
npm run dev    # spawns ./build-dev with hot reload
```

> Heads‑up: your terminal is now the command center. Keep it caffeinated ☕.

---

## 🛠️ Bootstrapping the Beast

1. **Node ≥ 18** is your lightsaber. Grab it.
2. `npm ci` — because `install` writes poetry, `ci` writes hashes.
3. `npm run dev` — live‑reloads into `./build-dev/`.
4. _Chrome_ → `chrome://extensions` → **Load unpacked** → point at `./build-dev`.
5. Hack. Save. Watch the wallet morph in real‑time.

> Test Chains wired in by default:  
> • ICX → `https://lisbon.net.solidwallet.io`  
> • ETH → `https://ropsten.infura.io`

---

## 🐞 Debug Like Neo

```bash
npm run remotedev   # spins a redux-devtools tunnel on :8000
```
Browse to `http://localhost:8000` and bend state like spoons.

---

## 🏗️ Production Forge

```bash
npm run build        # emits ./build — battle‑ready
```

Flip the **network switch** inside `src/constants/networks.ts` if you need another dimension:

```
Mainnet ICX → https://ctz.solidwallet.io
Mainnet ETH → https://api.myetherapi.com/eth
```

Ship it, sign it, push it to the masses.

---

## 📚 Command Cheat‑Sheet

| Command               | What it does                                                |
| --------------------- | ----------------------------------------------------------- |
| `npm ci`              | Zero‑based dependency install (faster CI)                  |
| `npm run dev`         | Dev build + hot reload                                     |
| `npm run remotedev`   | Spins standalone Redux DevTools server                     |
| `npm run build`       | Minifies, hashes, lints & drops artifacts in `./build`      |

---

## ⚖️ License

MIT, like most good open‑source caffeine.

> _May the forks be with you._
