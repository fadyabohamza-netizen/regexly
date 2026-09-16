# Regexly 🔤

**Describe it. Get the RegEx.** — Describe a pattern in plain English, get a RegEx with explanations.

## What it does

Type a pattern in plain English and Regexly writes the regular expression with a clear explanation. Powered by Pollinations.

- **Connect Pollen** → approve the consent screen → every request is paid from **your own** Pollen balance (default budget 5, valid 7 days, revocable anytime from https://enter.pollinations.ai/keys).
- Free tier: `openai/gpt-5.4-nano` · Premium toggle: `openai/gpt-5.5`.

## Options

- **Regex flavor:** `JavaScript/Python/PCRE`
## Stack

- Static single-file frontend (no build step), deployed on GitHub Pages.
- Pollinations [Connect User Wallets / BYOP](https://github.com/pollinations/pollinations/blob/main/BRING_YOUR_OWN_POLLEN.md) OAuth PKCE flow — the app never touches your secret key.
- Scoped keys live in `sessionStorage` only, never localStorage/logs/URLs.

## Links

- **Live app:** https://fadyabohamza-netizen.github.io/regexly/
- Source: https://github.com/fadyabohamza-netizen/regexly
- App key (publishable, earnings enabled): `pk_dB25Dh5nCjRw12HF`
- Powered by [Pollinations](https://gen.pollinations.ai) · Author: [fadyabohamza-netizen](https://github.com/fadyabohamza-netizen)
