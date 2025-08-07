# State-Level Mortgage Approval Gap Map

Interactive visualization showing Black-White mortgage approval rate gaps by state from 2018-2024.

## 🗺️ Features

- **Interactive US State Map** with hover tooltips
- **Time slider** to navigate through years 2018-2024
- **Color-coded approval gaps** with legend
- **Responsive design** using D3.js and TopoJSON

## 📊 Data

- `state_race_summary.csv` - State-level approval rate data by race and year
- `us_states.json` - US state boundaries (TopoJSON format)

## 🚀 Setup

1. **Start local server:**
   ```bash
   python -m http.server 8000
   ```

2. **Open in browser:**
   ```
   http://localhost:8000/state_map/interactive_state_map.html
   ```

## 🎯 Usage

- **Hover** over states to see approval gap details
- **Drag slider** to change year (2018-2024)
- **View legend** for gap categories

## 📁 Files

- `interactive_state_map.html` - Main visualization
- `state_race_summary.csv` - Data source
- `us_states.json` - Geographic boundaries
- `state_shapefile/` - Alternative shapefile data

## 🎨 Design

- **Color scheme**: Orange for gaps, Blue for no gap/positive
- **Gap categories**: Low (<5%), Medium (5-10%), High (10-15%), Very High (>15%)
- **Responsive**: Works on desktop and mobile devices
