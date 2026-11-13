<div align="center">

<img src="assets/banner.svg" alt="tokenwise" width="100%">

<p>
  <a href="https://cyberloop-dev.github.io/tokenwise/"><img alt="Live demo" src="https://img.shields.io/badge/live%20demo-open-6366f1?style=for-the-badge"></a>
  <img alt="License" src="https://img.shields.io/badge/license-MIT-22c55e?style=for-the-badge">
  <img alt="Dependencies" src="https://img.shields.io/badge/dependencies-zero-22d3ee?style=for-the-badge">
</p>

**Paste a prompt, see what it will cost before you send it.**

</div>

---

## ✨ Features

| | |
|---|---|
| 🪙 **Token estimate** | Instant estimate plus characters, words and lines |
| 💸 **Cost per tier** | Input and output price per 1M tokens, times the number of calls |
| 📏 **Context check** | Tells you when prompt + expected output will not fit a model's window |
| ✏️ **Editable prices** | Rename tiers and set your own prices, saved in your browser |
| 🔒 **Private** | Your text never leaves the page. No server, no tracking |

## 🚀 Quick start

Open the [live demo](https://cyberloop-dev.github.io/tokenwise/), or run it locally:

```bash
git clone https://github.com/CyberLoop-dev/tokenwise.git
cd tokenwise
open index.html   # or just double-click it
```

No build step. No dependencies.

## 🧮 How the estimate works

Real tokenizers differ from model to model, so tokenwise uses a transparent rule of thumb:

- about **4 characters per token** for ASCII text
- about **1.5 characters per token** for everything else (Persian, CJK, emoji, ...)

Treat the number as a good ballpark, not an invoice. For exact counts use your provider's own tokenizer or token-counting endpoint.

## 💰 About the prices

The three tiers that ship with the page are **examples**, not real price lists. Prices change often, so edit them to match your provider's pricing page. Your changes are stored in `localStorage` on your device.

## 📄 License

MIT
