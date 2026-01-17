# Personal Wallet - Landing Page

A static landing page for [Personal Wallet](https://github.com/h-gilbert/personal-wallet), a self-hosted personal finance application.

## Live Site

[wallet.hamishgilbert.com](https://wallet.hamishgilbert.com)

## Features Highlighted

- **Unified Dashboard** - Track bank accounts, crypto exchanges, and DeFi wallets in one view
- **Multi-Currency Display** - View holdings in NZD, USD, or BTC
- **Asset Allocation** - Interactive donut charts showing portfolio breakdown
- **Net Worth History** - Track wealth over time with daily snapshots
- **Transfer Detection** - Auto-detect internal transfers between accounts
- **Self-Hosted & Private** - Your data stays on your server

## Integrations Shown

- Akahu (NZ Banks)
- Wise
- OKX
- Bybit
- MEXC
- Kucoin
- EVM Wallets (Ethereum, Arbitrum, Optimism, BSC)
- Solana
- THORChain

## Development

This is a static HTML/CSS site with no build step required.

```bash
# Preview locally
open index.html

# Or use a local server
python -m http.server 8000
```

## Deployment

The site auto-deploys to the server via GitHub Actions on push to `main`.

## License

MIT License - see [LICENSE](LICENSE) for details.
