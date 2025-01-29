# Title

Utah Buildings

## ID

770a9559-3475-4683-80c0-9dfe1cde94e8

## Brief Summary

Polygon dataset of building footprints in Utah derived from Microsoft.

## Summary

This dataset contains polygons representing the approximate footprint of buildings in Utah. UGRC derived these footprints from Microsoft and made adjustments to provide a Utah-focused dataset that minimizes errors where possible. This dataset contains building polygon geometries only and does not show the ownership or use of the buildings.

## Description

### What is the dataset?

A building footprint is a two-dimensional outline of a three-dimensional, real-world building. These footprints are often digitally represented as polygons and can be used in a number of applications, including city and county planning, construction management, and demographic analysis. This dataset contains building footprints as polygons for physical structures found within Utah.

### What is the purpose of the dataset?

This dataset is used to delineate buildings in several of the statewide base maps available through UGRC's [Discover imagery service](https://gis.utah.gov/products/discover/). These data are also suitable for general cartographic and analytic purposes.

### What does the dataset represent?

Each polygon in this dataset indicates the approximate geographic extent of a building, otherwise known as a footprint. Where possible, features in this dataset include the city, zip code, and county that the building is in.

### How was the dataset created?

[Microsoft Maps](https://www.microsoft.com/en-us/maps) created the polygon geometries found in this dataset using pixel prediction algorithms and satellite imagery. In some cases, these methods may have identified buildings where none existed. To flag these potential errors, UGRC used [2010 Census data](https://gis.utah.gov/products/sgid/demographic/population-block-areas-2010-approx/) and the [Utah Address Points](https://gis.utah.gov/products/sgid/location/address-points/) dataset to designate buildings as either a likely structure or unlikely structure. Those buildings which are more than 750 meters away from known populated areas or more than 500 meters from known physical addresses were marked as unlikely to be a real structure (as indicated in the TYPE field).

### How reliable and accurate is the dataset?

These data were originally developed using computer vision algorithms that have been compared with hand-digitized polygons from [OpenStreetMap](https://www.openstreetmap.org/#map=6/45.49/-109.36) and found to be of similar quality, according to Microsoft. Due to the generated nature of these polygons, some discrepancies in the data may exist. You can learn more about how these data were generated through [official documentation](https://github.com/microsoft/USBuildingFootprints). Please reach out to [our team](https://gis.utah.gov/contact/) with questions or concerns about this dataset.

## Credits

### Data Source

Microsoft

### Host

UGRC

## Restrictions

## License

## Tags

- Microsoft Maps
- Microsoft

## Secondary Category

## Data Page Link

[https://gis.utah.gov/products/sgid/location/building-footprints/]

## Update

### Update Schedule

This dataset is updated as needed.

### Previous Updates
