# Chicago Seniors in Food Deserts Map

An interactive map illustrating the number of seniors per census tract in Chicago living in food deserts. The map also displays the locations of grocery stores in the region.

## Table of Contents
- [About](#about)
- [How to Use](#how-to-use)
- [Data Sources](#data-sources)
- [Contributing](#contributing)
- [Contact](#contact)

## About

This interactive map provides insights into the distribution of seniors living in food deserts across different census tracts in Chicago. Additionally, it highlights the locations of grocery stores to facilitate a better understanding of the accessibility of food resources for seniors in the city as Chicago, as the topic of low food access becomes increasingly more relevant in the city.

The inspiration for creating this map came after reading on article on the Chicago times regarding a problem with food deserts in the city, and how the local government plans to respond. 

Article:[ Food Deserts Plague Chicago Neighborhoods. Could the city run it's own grocery stores to fill in the gaps?](https://chicago.suntimes.com/2023/11/2/23882682/mayor-brandon-johnson-city-owned-grocery-south-west-low-food-access-grocery-desert)

The scope of focus is specifically seniors aged 65+ that live more than one mile away from a grocery store. For the purpose of the age demographic and the urban setting, we are defining these areas as food deserts.

This map does not include the portion of the population below 65 in Chicago living in a food desert. 

## How to Use

1. **Hover over a Census Tract:** Move your cursor over a census tract to view the number of seniors living in a food desert.

2. **Click on a Census Tract:** Click on a census tract to zoom in and explore more detailed information.

3. **Grocery Store Information:** Icons on the map represent the locations of grocery stores. Click on the icons to view the names of the grocery stores.

## Data Conversion Process

The shapefile containing the Chicago census tract boundaries was uploaded into ArcGIS Pro and joined with a stand alone table containing low access food data. This file was then converted to a geojson format. The point data for the grocery store locations was an excel spreadsheet that was uploaded into QGIS then converted into a geojson file.


## Data Sources

- **Seniors in Food Deserts Data:** [Your Data Source]
- **Census Tract Boundaries:** [Your Data Source]
- **Grocery Store Data:** [Your Data Source]

## Contributing

If you'd like to contribute to this project, please follow these steps:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/new-feature`)
3. Commit your changes (`git commit -m 'Add new feature'`)
4. Push to the branch (`git push origin feature/new-feature`)
5. Open a pull request

## Contact

For any inquiries or feedback, please contact [Jason Wright](wrightjd5@appstate.edu).
