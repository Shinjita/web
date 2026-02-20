# Urban Food Accessibility Dashboard

A GIS-grade spatial accessibility dashboard for analysing fast food restaurant access using network-based travel time and multi-criteria scoring.

![Dashboard Preview](preview.png)

## Overview

This browser-based dashboard evaluates urban food accessibility by combining real-time business data,network routing, and spatial analysis — no desktop GIS software required.

## How to Use

Once the dashboard is loaded with your API key, follow these steps:

**1. Set Your Location**  
Type an address in the search bar and press Enter, click *Use My Location* to detect your position via GPS, or simply click anywhere on the map to set a custom origin point.

**2. Choose Travel Mode**  
Open the Layers panel (top-left of the map) and select *Walk* or *Drive*. All travel times and rankings will update based on real road network distances — not straight lines.

**3. Apply Filters**  
Use the sidebar to filter results by minimum star rating, maximum distance, price level, and open status before searching.

**4. Run the Search**  
Click *Find Restaurants* to load nearby fast food locations. Results are automatically ranked by accessibility score.

**5. Explore the Map**  
- Click any result card to zoom to that location and see its route  
- Toggle the **Service Area** to visualise how far you can travel 
  in 10, 15, or 20 minutes  
- Enable the **Accessibility Heatmap** to see a colour-coded 
  travel time surface across the map  
  *(Green = close, Red = far)*

**6. Understand the Score**  
Each place receives a score out of 100. Click *Explain Score* on any card to see the breakdown across travel time, rating, price, and open status — including any bonuses or penalties applied.

**7. Compare Places**  
Click *Compare* on up to two result cards to view them side by side in the comparison panel.

**8. Export Your Results**  
Use the Export panel (top-left of the map) to download results as a CSV spreadsheet or GeoJSON file for use.

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

## Author

**Shinjita Das**  
PhD Candidate & Research Associate, RMIT University  
[LinkedIn](https://linkedin.com/in/shinjitadas-2365a3185) · 

