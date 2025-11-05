# Title

Utah Average Annual Precipitation

## ID

cfc3276d-5808-4fe3-9b4b-72924f8b2374

## Brief Summary

Polygon dataset of average annual precipitation (inches) in Utah.

## Summary

This dataset includes polygon boundaries for contours of average annual precipitation, measured in inches.  The data represent the average or normal amount of precipitation, based on the most recent standard 30-year climate period from 1991-2020.

## Description

### What is the dataset?

These data represent average annual precipitation amounts in Utah for the 1991-2020 period.  The dataset was created to provide a generalized polygon alternative to the original raster data that is typically used in the scientific community.  The polygon version makes it easier to work with for GIS users in Utah.

### What is the purpose of the dataset?

The purpose of this dataset is to provide generalized average annual precipitation data for the state of Utah, to be used for general analysis and cartographic purposes.

### What does the dataset represent?

Each polygon feature in this dataset represents a 1-inch range of average annual precipitation. The data has attributes for the minimum (min_inches) and maximum (max_inches) average annual precipitation found within a particularly polygon, along with a generalized attribute (inches), which is equal to min_inches. For example, a polygon with min_inches = 15 and max_inches = 16, has average annual precipitation values between 15 and 16 inches. For more precise data at a given point location, users are encouraged to obtain the original source raster data from the PRISM Group's [30-Year Normals](https://prism.oregonstate.edu/normals/) page.

### How was the dataset created?

UGRC derived this dataset from a nationwide analysis completed by the [PRISM Group](https://prism.oregonstate.edu/overview/) at Oregon State University. The original raster dataset (approximately 800m resolution) was downloaded from the PRISM site, clipped to a buffer around Utah, and converted from millimeters to inches. Then it was contoured for every whole inch as an interval of 1 inch, to create a polygon dataset. The polygon data was then projected into UTM 12N (WKID: 26912), and clipped to the state of Utah boundary.

### How reliable and accurate is the dataset?

This dataset is consistent with the latest [scientific methods](https://prism.oregonstate.edu/methods/) and its creation was supported by the National Oceanic and Atmospheric Administration and the US Department of Agriculture. Please reach out to [our team](https://gis.utah.gov/contact/) with questions or concerns about this dataset.

## Credits

- PRISM Group, Oregon State University, https://prism.oregonstate.edu, data created Dec 2022, accessed 30 Oct 2025.

### Data Source

- PRISM Group, Oregon State University

### Host

UGRC

## Restrictions

## License

## Tags

- Climate
- Meteorology
- Precipitation

## Secondary Category

## Data Page Link

[https://gis.utah.gov/products/sgid/climate/average-annual-precipitation/]

## Update

### Update Schedule

Decennial

### Previous Updates
