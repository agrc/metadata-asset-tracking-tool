# Title

Utah Lakes NHD

## ID

b0a55056-bdb9-4b7c-8812-8f246b328f88

## Brief Summary

Statewide bodies of water including lakes, reservoirs, and ponds derived from the National Hydrography Dataset (NHD).

## Summary

This dataset comprises bodies of water found in and around the state of Utah. This dataset is derived from the [National Hydrography Dataset](https://www.usgs.gov/national-hydrography/national-hydrography-dataset) (NHD) compiled by the United State Geological Survey [USGS](https://www.usgs.gov/) and modified by UGRC to provide additional functionality for Utah-based users.

## Description

### What is the dataset?

The NHD is a national framework for assigning [reach addresses](https://enviro.epa.gov/enviro/ef_metadata_html.tri_page?p_column_name=reach_code#:~:text=Description%3A%20A%20reach%20code%20is,National%20Hydrography%20Dataset%20(NHD).) to water-related entities, such as industrial discharges, drinking water supplies, and fish habitat areas. Reach addresses establish the locations of these entities relative to one another within the NHD surface water drainage network, much like addresses on streets.

The NHD contains reach codes for networked features, flow direction, names, and centerline representations for water bodies. The NHD also incorporates the National Spatial Data Infrastructure framework criteria established by the Federal Geographic Data Committee.

### What is the purpose of the dataset?

The NHD provides a nationally consistent framework for addressing and analyzing water-related information. Water body data are also a helpful resource for [cartography](https://19january2021snapshot.epa.gov/sites/static/files/2014-09/documents/utah.pdf), public recreation, and data analysis. NHD-based datasets can be combined with other data layers such as soils, land use, and population to help understand and display their respective effects upon one another. Further water-related data can be found on the SGID [Water Data Index](https://gis.utah.gov/products/sgid/water/).

### What does the dataset represent?

This dataset approximates bodies of water as polygons that include attributes such as the area in square kilometers and [GNIS](https://www.usgs.gov/tools/geographic-names-information-system-gnis) name. For a full description of the fields in this dataset, please see the [schema summary](https://docs.google.com/document/d/1QWZKKPe3PWR9XyMYEG6qFmhsK55oBYYLWRQtknbrnD4/edit?usp=sharing) document.

### How was the dataset created?

The NHD was first created in the late 1990s by USGS in collaboration with the Environmental Protection Agency [(EPA)](https://www.epa.gov/). The original product, the National Hydrography Dataset, was created at a 1:100,000 scale for the conterminous United States. The EPA became the primary custodian of this medium resolution dataset in the early 2000s, while USGS and United States Forest Service [(USFS)](https://www.fs.usda.gov/) began the production of what would become the high resolution National Hydrography Database. Today, the high-resolution NHD is available at a nationwide 1:24,000 scale.

More information on the history of this database can be found in [publications](https://www.horizon-systems.com/NHDPlusData/NHDPlusV21/Documentation/History/Making_the_Digital_Water_Flow.pdf) from USGS and on the [NHD website](https://www.usgs.gov/national-hydrography/national-hydrography-dataset#:~:text=In%20the%20late%201990s%2C%20the,and%20those%20of%20other%20medium).

UGRC has modified the source NHD data to produce this layer. Four fields have been added to this feature class (FType_Text, FCode_Text, InUtah and IsMajor) and features have been split at the state boundary.  The "IsMajor" field identifies major lakes for coarse scale mapping and display, where 1 = major and 0 = minor. The "InUtah" field identifies whether a given body of water is within the state boundary, where 1 = in Utah and 0 = outside of Utah.

### How reliable and accurate is the dataset?

The NHD is the primary source for water body data in the United States. It represents a nationally consistent, interoperable dataset that facilitates accurate data sharing between entities. Questions or concerns about this dataset can be directed to [USGS](https://www.usgs.gov/national-hydrography/nhdplus-high-resolution). Utah-specific inquiries can be directed to [our team](https://gis.utah.gov/contact/) at UGRC.

## Credits

- USGS
- EPA
- UGRC

### Data Source

NHD

### Host

UGRC

## Restrictions

## License

## Tags

- Water
- National Hydrography Dataset
- USGS
- EPA
- Hydrology

## Secondary Category

## Data Page Link

[https://gis.utah.gov/products/sgid/water/nhd-lakes/]

## Update

### Update Schedule

This layer is updated as needed.

### Previous Updates
