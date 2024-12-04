# Dell Logistics and Transportation Visualization

This project visualizes Dell's logistics and transportation data, sourced from the **Dell Transportation Database 2024 v2.xlsx**, to analyze city connections and optimize routes. The project highlights the geographical spread of Dell's distribution network and provides insights into its logistics operations.

![City Connections Map](city_connections_map.png)

## Features
- **Map Visualization**: Plots destination cities from Dell's logistics network on a map as green dots.
- **Route Connections**: Connects cities with blue lines to represent transportation routes.
- **Custom Map Styling**: Highlights the USA in light yellow, oceans in light blue, and other land regions in gray.
- **Image Output**: Saves the map visualization as a `.png` file for further analysis.

## Data Source: Dell Transportation Database 2024 v2.xlsx
The data used in this project comes from Dell’s proprietary **Dell Transportation Database 2024 v2.xlsx**, which contains key metrics and details about logistics and transportation activities. This dataset provides insights into Dell’s supply chain efficiency, cost structures, and transportation routes.

### Key Data Features:
- **Logistics Information**:
  - Routes connecting distribution centers and destinations.
  - Freight costs and accessorial charges.
  - Modes of transportation, including ground, air, and sea.

- **Geographical Coverage**:
  - Latitude and longitude data for cities.
  - Distribution centers associated with each route.

- **Performance Metrics**:
  - Lead times (actual vs. expected).
  - Delivery punctuality.
  - Cost-effectiveness indicators.

### Applications:
The dataset enables:
- **Operational Analysis**: Insights into route efficiency and transportation cost structures.
- **Strategic Planning**: Optimization of logistics routes for cost reduction and lead-time improvements.
- **Visualization**: Geographical mapping of distribution networks for decision-making.

## Project Structure
```plaintext
.
├── Dell_Transportation_Database_2024_v2.xlsx  # Input data file
├── map_visualization.py                       # Python script for map generation
├── city_connections_map.png                   # Example output map
└── README.md                                  # Project documentation