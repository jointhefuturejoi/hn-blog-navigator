# Market Momentum Heatmap

An interactive market visualization tool that displays stocks as a treemap heatmap, color-coded by momentum metrics. Built as an overnight project inspired by Jeff Sun's "Hottest Stock" momentum screener concept.

## Features

- **Treemap Visualization**: Stocks sized by market cap, colored by momentum
- **59 Stocks**: Large-cap and growth stocks across 6 sectors
- **Interactive Search**: Find stocks by symbol or name with "/" keyboard shortcut
- **Top Movers**: Quick view of top 5 gainers and losers
- **Detail Panel**: Click any stock for detailed metrics + 30-day sparkline
- **Multiple Timeframes**: 1D, 1W, 1M momentum views
- **Sector Filtering**: Focus on specific sectors
- **Sort Options**: Sort by market cap, momentum, or volume

## How to Run

Simply open `index.html` in any modern web browser:

```bash
open index.html
```

Or serve with a local server:

```bash
python -m http.server 8000
# Then visit http://localhost:8000
```

No build step required. All dependencies are loaded via CDN (D3.js).

## Keyboard Shortcuts

- `/` - Focus search box
- `Esc` - Close detail panel / clear search

## Data

Stock data is simulated for demonstration purposes, including:
- Price and price changes (1D, 1W, 1M)
- Volume and volume vs average
- RSI (14)
- Market cap
- Sector classification

## Tech Stack

- Vanilla HTML/CSS/JavaScript
- D3.js v7 for visualization
- No build tools or dependencies required

## Browser Support

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)

## License

MIT
