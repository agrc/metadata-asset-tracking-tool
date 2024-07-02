# Title

Utah PLSS Quarter Quarter Sections GCDB

## ID

4b63af59-da17-40dd-bf40-2996c489fc4d

## Brief Summary

Polygon dataset of the smallest unit of the Public Land Survey System (PLSS), where each unit represents 40 acres of land.

## Summary

This dataset represents the smallest unit of the Public Land Survey System (PLSS). Each polygon represents approximately 40 acres of land and is labelled by its first and second division identifier, otherwise known as township and range. We used Geographic Coordinate Database ([GCDB](https://www.sciencebase.gov/catalog/item/4f4e4a7fe4b07f02db648dce)) base attributes to create the second division class (quarter quarter sections).

## Description

### What is the dataset?

Originally established in 1785 and currently administered by the Bureau of Land Management (BLM), the PLSS is a nationwide framework for surveying, dividing, and quantifying land. PLSS sections are divided into a grid with 640 acres in each square, which is further divided into quarter sections (160 acres per square) and quarter quarter sections (40 acres per square). This dataset represents this final division as polygons.

The polygons in this feature class represent the smallest division that has been defined by the BLM. This data is derived from the [Utah PLSS Fabric](https://gis.utah.gov/products/sgid/cadastre/parcel-fabric/). Other PLSS datasets can be found in the [Cadastre Data Index](https://gis.utah.gov/products/sgid/cadastre/).

### What is the purpose of the dataset?

PLSS data are used in many areas of natural resource management, land ownership designation, and public planning. Though not a substitute for a legal land survey, this dataset is a helpful resource for cartography and general analytic purposes.

### What does the dataset represent?

This dataset represents PLSS quarter quarter sections as polygons spanning 40 acres each. The attributes assigned to PLSS polygons were taken from the BLM's Legal Land Description (LLD) dataset, which can be found in the the Legacy Rehost for the year 2000 (LR2000) automated records system.

### How was the dataset created?

The primary source for the data are cadastral survey records housed by the BLM and supplemented with local records and geographic control coordinates from states, counties, and federal agencies. This data was originally published in January of 2017 and is based on GCDB coordinate data.

<!--- I admit I don't know what this next bit refers to. Is it worth including for those that use this dataset regularly? -->

Lots were dissolved to the section level. Survey_type: B (aliquot parts less than 40 acres) for geopolitical splits were attributed as Survey_type: A. They were added, using information from points collected by county surveyors, that is in the data and extrapolating information from adjoining sections wherever possible. They are still areas that could not be interpreted well enough and they were left empty, beyond the section level. In the future this data will continue to be carried in this feature class but not incorporated into the official PLSS Fabric.

This statewide dataset is maintained by UGRC in partnership with the BLM and local government authorities.

### How reliable and accurate is the dataset?

This dataset represents the most current and complete version of PLSS quarter quarter sections in Utah. Divisions beyond the quarter quarter sections may be included in this feature class, but in most implementations these smaller divisions will be [parcels](https://gis.utah.gov/products/sgid/cadastre/parcels/).

## Credits

### Data Source

- BLM
- Local county authorities

### Host

UGRC

## Restrictions

The geographic coordinates used in this dataset and their associated products are not legal land survey records. The coordinates can not be used as a substitute for a legal land survey. They can be used for record keeping, mapping, graphics and planning purposes only. No warranty is made by the Bureau of Land Management for use of the data for purposes not intended by BLM.

## License

## Tags

- Public Land Survey System
- BLM

## Secondary Category

## Data Page Link

[https://gis.utah.gov/products/sgid/cadastre/plss-quarter-quarter-sections/]

## Update

### Update Schedule

We update this dataset annually as horizontal control positions from published sources and GPS observations become available. Beyond these additions, this dataset is updated as needed.

### Previous Updates
