# Urban Food Accessibility Dashboard

A GIS-grade spatial accessibility dashboard for analysing fast food restaurant access using network-based travel time and multi-criteria scoring.

![Dashboard Preview](preview.png)

## Overview

This browser-based dashboard evaluates urban food accessibility by combining 
real-time business data, network routing, and spatial analysis — no desktop 
GIS software required.

Built as a personal project to explore web GIS development using the 
Google Maps Platform APIs.

## Features

- 📍 **Location Input** — Address search, GPS, or map click
- 🚶 **Travel Mode** — Walk or Drive (real network time, not straight-line)
- 🔵 **Service Area (Isochrone)** — 10, 15, or 20-minute reachability zones
- 🌡️ **Accessibility Heatmap** — Visual travel time surface across the map
- 🏆 **Multi-Criteria Scoring** — Ranked by travel time, rating, price & 
  open status
- 📊 **Score Breakdown** — Transparent scoring with bonuses and penalties
- ⚖️ **Compare Tool** — Side-by-side comparison of two locations
- 📁 **Export** — Download results as CSV or GeoJSON

## Tech Stack

| Layer | Tools |
|-------|-------|
| Frontend | HTML, CSS, Vanilla JavaScript |
| Mapping | Google Maps JavaScript API |
| Data | Google Places API, Google Directions API |
| Spatial Analysis | Custom isochrone generation, heatmap rendering |
| Coordinate System | WGS84 |

## Getting Started

1. Clone this repository
2. Obtain a [Google Maps API Key](https://developers.google.com/maps)
3. Enable the following APIs in your Google Cloud Console:
   - Maps JavaScript API
   - Places API
   - Directions API
   - Geocoding API
4. Open `index.html` in a browser
5. Enter your API key when prompted

> ⚠️ Your API key is stored locally in your browser. Never commit keys 
> to version control.

## Scoring Methodology

Places are ranked using a weighted multi-criteria index:

| Criterion | Weight |
|-----------|--------|
| Travel Time | 35% |
| Rating | 30% |
| Price Level | 20% |
| Open Status | 15% |

Bonuses and penalties are applied for exceptional ratings, closure status, 
and distance thresholds.

## Author

**Shinjita Das**  
PhD Candidate & Research Associate, RMIT University  
[LinkedIn](https://linkedin.com/in/shinjitadas-2365a3185) · 
[Portfolio](https://github.com/Shinjita)

---
*Part of a broader research interest in urban spatial analytics, 
accessibility modelling, and web GIS development.*
