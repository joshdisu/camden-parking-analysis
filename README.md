# Camden Parking Analysis

This repository contains geospatial data, analysis, and interactive dashboards for parking resource allocation in Camden, London.

## Data

- **camden_parking.gpkg**: GeoPackage containing processed parking bay data, spatial features, and model results.
- **openroads_uk.gpkg**: Road network data (if included).
- **camden_boundary.geojson**: Camden local authority boundary.
- **traffic_data/**: Optional traffic count data.

## Analysis

- **Notebooks**: Jupyter notebooks for data preprocessing, model training, and dashboard development.
- **src/**: Python modules for reusable code.

## Dashboards

- **Dash**: Interactive dashboard using Plotly and Dash.
- **Streamlit**: Interactive dashboard using Streamlit.

## Getting Started

1. Clone the repository.
2. Install dependencies: `pip install -r requirements.txt`
3. Run notebooks or dashboard scripts.

# Camden Parking GeoPackage Schema

## Tables

- **parking_bays**: Contains parking bay locations, attributes, and model outputs.
  - Fields: `Parking Spaces`, `Restriction Type`, `Times Of Operation`, `Maximum Stay`, `Tariff`, `Road Name`, `Postcode`, `Controlled Parking Zone`, `Valid Parking Permits`, `Parking Bay Length Metres`, `Easting`, `Northing`, `Longitude`, `Latitude`, `geometry`, etc.
- **roads**: road network features.

## License

MIT License. See [LICENSE](LICENSE) for details.
