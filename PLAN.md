# Market Momentum Heatmap

## Goal
Build an interactive market momentum visualization that displays stocks as a treemap heatmap, color-coded by momentum metrics (price change, volume surge, relative strength).

## Structure Tier
Tier 1 — Single HTML file with embedded CSS/JS. Data included as JSON within the file for standalone operation.

## Files I'll create
- index.html — Main application with treemap visualization using D3.js
- README.md — What it does, how to run it
- inspiration.md — Link to Jeff Sun's tweet

## Steps
1. Create HTML structure with D3.js CDN
2. Generate realistic mock stock data (50+ stocks across sectors)
3. Build treemap layout with d3-hierarchy
4. Color-code by momentum score (price change %)
5. Add interactive filters (sector dropdown, timeframe buttons)
6. Add hover tooltips with stock details
7. Add click-to-expand detail panel
8. Polish visual design (dark theme, finance aesthetic)
