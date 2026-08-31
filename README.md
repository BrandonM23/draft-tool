# 2026 Fantasy Draft Model

12-team half-PPR ESPN redraft draft tool. Live board with value signals, tier breaks, injury adjustments, and CLOCK mode.

**Live at:** https://brandonm23.github.io/draft-tool

## Features
- Consensus PPG vs ADP-implied value (UNDERVALUED / FAIR / OVERVALUED with intensity shading)
- Position tier breaks by production dropoff
- Injury-adjusted projections (context-aware, not flat multipliers)
- CLOCK mode — snake-draft-aware rolling window
- DRAFTED / FAV / GONE tracking with reset
- Live data refresh via Claude + web search (password protected)

## Data
Hardcoded: NFLFantasyEdge consensus Aug 24 2026. Refresh pulls live Claude projections with web search.

## Deploy
Hosted via GitHub Pages from `main` branch root.
