# Title

Utah Bikeways

## ID

3e45150c-bed2-4e6e-95b0-209b91c4d67a

## Brief Summary

Bike-related features derived from Roads and Trails and Pathways.

## Summary

The Utah Bikeways dataset provides a detailed representation of on-street and pathway bikeway features in the state and serves as a comprehensive resource for understanding the state's cycling infrastructure. The data includes various attributes such as the name of the bikeway, the city and county it traverses, and specific details about the facility type (e.g., dedicated bike lanes, shared-use paths). It also includes an estimated Level of Traffic Stress (LTS) score and the source of the data.

## Description

### What is the dataset?

This dataset contains linear segments comprised of road, trail, and pathway features that can be used by bicycles. Each segment includes information about the bikeway name, city, county, type and side of bike facility, level of traffic stress, cartographic code, and data source. Segments that are derived from road data that has no bike-specific attribute information show "Not Available" in the bike facility and side fields.

### What is the purpose of the dataset?

The Utah Bikeways data is intended for planning, analysis, and visualization of cycling routes and infrastructure at various scales within Utah. Users should be aware that while efforts are made to keep the data current, recent changes in infrastructure are not immediately reflected. Data updates are sourced through periodic coordination between transportation agencies (UDOT and Utah's four MPOs), local government GIS and active transportation contacts, and through user submissions with the [bikeways.utah.gov](https://bikeways.utah.gov/) web map.

### What does the dataset represent?

This dataset contains polyline features representing on-street and pathway bike features in Utah.

### How was the dataset created?

The Bikeways data is maintained within two separate statewide editing layers stewarded by UGRC &mdash; [Roads](https://gis.utah.gov/products/sgid/transportation/road-centerlines/) and [Trails and Pathways](https://gis.utah.gov/products/sgid/recreation/trails-pathways/). This more user-friendly dataset is derived by UGRC using a python script that combines bike facilities in the two editing layers. It merges and formats the data into a single schema, determines the best bike feature, and which side of the road the best feature is on. The script also calculates a [Level of Traffic Stress](ttps://docs.google.com/document/d/1eo9BscAbXFHKlw8EONFRi4lntBwvON8JzV6tN2D_j6I/edit?tab=t.0) metric that represents the amount of discomfort people feel when they ride their bicycles near traffic. Finally, the data is split into existing and planned features, for use in the [Utah Bikeways](https://bikeways.utah.gov/) app.

### How reliable and accurate is the dataset?

This is the most authoritative representation of statewide bikeways in Utah. This dataset is updated routinely, but users are advised that the map may not reflect current conditions on the ground, and may contain errors or omissions. Please provide feedback through the [Utah Bikeways](https://bikeways.utah.gov/) app or reach out to [our team](https://gis.utah.gov/contact/) if you notice any issues with this dataset.

## Credits

### Data Source

- Local Data Stewards
- UDOT
- UGRC
- WFRC
- MAG

### Host

UGRC

## Restrictions

## License

## Tags

- UDOT
- Active Transportation
- Recreation

## Secondary Category

## Data Page Link

[https://gis.utah.gov/products/sgid/transportation/bikeways/]

## Update

### Update Schedule

This dataset is updated on a monthly basis.

### Previous Updates
