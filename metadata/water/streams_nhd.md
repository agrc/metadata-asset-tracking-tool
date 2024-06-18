# Title

Utah Streams NHD

## ID

eace4ae8-33df-4f3f-b4a7-ed1ca6e0bbc0

## Brief Summary

Statewide polyline dataset of rivers, streams, and other watercourses derived from the National Hydrography Dataset (NHD).

## Summary

This dataset contains river and stream features as well as other watercourses like canals, and ephemeral streams. This dataset is derived from the [National Hydrography Database](https://www.usgs.gov/national-hydrography/national-hydrography-dataset) (NHD) and has been modified by UGRC to provide additional functionality for Utah-based users.

## Description

### What is the dataset?

The NHD provides a nationally consistent framework for addressing and analyzing water-related information. UGRC has modified the source NHD data by adding three fields (InUtah, IsMajor, and Submerged) and splitting features at the state boundary. In addition to the fields we've added, this dataset contains [reach codes](https://enviro.epa.gov/enviro/ef_metadata_html.tri_page?p_column_name=reach_code#:~:text=Description%3A%20A%20reach%20code%20is,National%20Hydrography%20Dataset%20(NHD).) for networked features, flow direction, names, and centerline representations for water bodies. The NHD also incorporates the National Spatial Data Infrastructure framework criteria established by the Federal Geographic Data Committee.

### What is the purpose of the dataset?

The NHD provides a nationally consistent framework for addressing and analyzing water-related information. Watercourse data are also a helpful resource for [cartography](https://19january2021snapshot.epa.gov/sites/static/files/2014-09/documents/utah.pdf), public recreation, and data analysis. NHD-based datasets can be combined with other data layers such as soils, land use, and population to help understand and display their respective effects upon one another. Further water-related data can be found on the SGID [Water Data Index](https://gis.utah.gov/products/sgid/water/).

### What does the dataset represent?

This dataset represents watercourses such as streams, rivers, and canals as polylines that include attributes such as the length in kilometers and [GNIS](https://www.usgs.gov/tools/geographic-names-information-system-gnis) name.

### How was the dataset created?

UGRC has modified the source NHD data to produce this layer. The "IsMajor" field identifies major lakes for coarse scale mapping and display, where 1 = major and 0 = minor. The "InUtah" field identifies whether a given body of water is within the state boundary, where 1 = in Utah and 0 = outside of Utah. Finally, the "Submerged" field can be used to exclude the hydrologic network features that have been added across water bodies for linear water flow modeling. Values are 1 = submerged, and 0 = surface.

The current high-resolution, 1:24,000 scale NHD is an improvement of the original 1:100,000 scale dataset first created in the late 1990s by the USGS in collaboration with the Environmental Protection Agency [(EPA)](https://www.epa.gov/). It was created by the USGS and United States Forest Service [(USFS)](https://www.fs.usda.gov/) in the 2000s while the EPA maintained the original, moderate-scale dataset.

More information on the history of this database can be found in [official publications](https://www.horizon-systems.com/NHDPlusData/NHDPlusV21/Documentation/History/Making_the_Digital_Water_Flow.pdf) from USGS and on the [NHD website](https://www.usgs.gov/national-hydrography/national-hydrography-dataset#:~:text=In%20the%20late%201990s%2C%20the,and%20those%20of%20other%20medium).

### How reliable and accurate is the dataset?

The NHD is the primary source for hydrographic data in the United States. It represents a nationally consistent, interoperable dataset that facilitates accurate data sharing between entities. Questions or concerns about this dataset can be directed to [USGS](https://www.usgs.gov/national-hydrography/nhdplus-high-resolution). Utah-specific inquiries can be directed to [our team](https://gis.utah.gov/contact/) at UGRC.

## Credits

- USGS
- EPA
- UGRC

### Data Source

- USGS
- UGRC

### Host

UGRC

## Restrictions

## License

## Tags

- Hydrography
- Hydrology
- USGS

## Secondary Category

## Data Page Link

[https://gis.utah.gov/products/sgid/water/nhd-streams/]

## Update

### Update Schedule

This layer is updated as needed.

### Previous Updates
