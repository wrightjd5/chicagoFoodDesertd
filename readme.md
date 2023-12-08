# Washington Poverty and Discount Stores Map

An interactive map showcasing poverty data for children in Washington counties from 2021 along with the locations of discount and charity stores.

## Table of Contents
- [About](#about)
- [How to Use](#how-to-use)
- [Data Sources](#data-sources)
- [Contributing](#contributing)
- [Contact](#contact)

## About

This interactive map visualizes the number of children ages 0-17 in poverty per county in Washington, overlaying the distribution of discount and charity stores. The map provides a comprehensive view of poverty statistics and store locations to aid in understanding the socio-economic landscape.

## How to Use

1. **Hover over a County:** Move your cursor over a county to view the number of people in poverty.

2. **Click on a County:** Click on a county to zoom in and explore more detailed information.

3. **Discount and Charity Stores:** Icons on the map represent the locations of different types of stores. Click on the icons to view store names.

## Data Conversion Process

A shapefile representing counties in Washington State was found on [IGISMap](https://www.igismap.com/download-washington-state-gis-maps-boundary-counties-rail-highway/) and then converted to GeoJSON using [geojson.com](http://geojson.com). Data representing the number of people aged 0-17 experiencing poverty per county in Washington was found from the [U.S. Department of Agriculture - Economic Research Service](https://www.ers.usda.gov/data-products/county-level-data-sets/county-level-data-sets-download-data/) and was joined with the Washington counties GeoJSON file using [geojson.com](http://geojson.com). The point data representing the number of discount and charity stores was found as a shapefile on [IGISMap](https://map.igismap.com/gis-data/129836/united%20states-washington/discount_stores_and_charity_point) and was then converted to GeoJSON format using [geojson.com](http://geojson.com).

## Data Sources

- **Poverty Data:** [U.S. Department of Agriculture - Economic Resesarch Service](https://www.ers.usda.gov/data-products/county-level-data-sets/county-level-data-sets-download-data/)
- **County boundaries:** [IGISMap](https://www.igismap.com/download-washington-state-gis-maps-boundary-counties-rail-highway/)
- **Discount Store Data:** [IGISMap](https://map.igismap.com/gis-data/129836/united%20states-washington/discount_stores_and_charity_point)

## Contributing

If you'd like to contribute to this project, please follow these steps:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/new-feature`)
3. Commit your changes (`git commit -m 'Add new feature'`)
4. Push to the branch (`git push origin feature/new-feature`)
5. Open a pull request

## Contact

For any inquiries or feedback, please contact [Jason Wright](mailto:wrightjd5@appstate.edu).
