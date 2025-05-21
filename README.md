# Automated-EDA
graph LR
    A[Extract: Data Input] --> B[Transform: Frontage Classification]
    B --> C[Transform: Setback Area Calculation]
    C --> D[Load: Output Generation]
    A --> E[Parcel Data CSV (parcels_abu_ftaira.csv)]
    A --> F[Road Data GeoJSON (abu_ftaira_roads.geojson)]
    D --> G[CSV with Metrics and Obstacle Information]
    D --> H[GeoJSON for Spatial Applications]
    D --> I[Matplotlib Visualizations for Inspection]
