# Title

Utah Open Sources Places

## ID

ce969f6a-2a36-4485-8594-ff17d7bd82e6

## Brief Summary

Points dataset of places of interest in Utah that have been derived from OpenStreetMap (OSM).

## Summary

This dataset includes points of interest such as businesses, restaurants, places of worship, airports, parks, schools, and many others that can be found in Utah. The data were derived from OpenStreetMap and are maintained by UGRC.

## Description

### What is the dataset?

OpenStreetMap ([OSM](https://www.openstreetmap.org/#map=6/45.49/-109.36)) is a free, open source mapping application where users can contribute directly to the data. This dataset contains more than 20,000 points of interest in Utah as derived from OSM.

### What is the purpose of the dataset?

This layer serves as a general reference for points of interest in Utah and is suitable for cartographic and analytic purposes. You can learn more about open source data, how it is used, and how you can participate in the process on [our blog](https://gis.utah.gov/blog/2022-03-21-introducing-open-source-places/).

<!--- Does this dataset serve a more specific purpose than this? --->

### What does the dataset represent?

Each point in this dataset represents the approximate location of a place of interest. Points representing buildings are placed on or near the main structure. Points contain the name of the place, generalized category, county, ZIP code, and street address, where applicable.

### How was the dataset created?

UGRC originally developed this layer in March 2022 using data from OpenStreetMap (OSM). Currently, this dataset is maintained using a systematic process to download, filter, and organize the data for Utah-based users. A python script first downloads the OSM data from an archive provided by [Geofabrik](https://www.geofabrik.de/). Then, we filter the data to specific categories set by UGRC and convert polygon features to points using an internal centroid.

UGRC employs spatial filtering methods to ensure the resulting data contains no duplicate points of interest and includes useful fields for the user. We use the [Census Blocks 2020](https://gis.utah.gov/products/sgid/demographic/census-2020-blocks/) layer to ensure that no one Census Block contains two points of interest of the same name. Finally, we include additional fields such as the county, city, ZIP code, and street address using [Near analyses](https://pro.arcgis.com/en/pro-app/latest/tool-reference/analysis/near.htm) and corresponding layers available in the SGID. New points of interest are added to this dataset through this process every month.

<!--- This is a pared-down version of the original description of how this dataset was created. Let me know if there is anything missing or if there are extraneous details that don't need to be included. --->

### How reliable and accurate is the dataset?

This dataset is derived from open source data and reflects user contributions to OSM. Some discrepancies and inaccuracies may exist in the data. Please reach out to [our team](https://gis.utah.gov/contact/) with questions or concerns about this dataset.

## Credits

### Data Source

OSM

### Host

UGRC

## Restrictions

UGRC encourages users to learn more about the Open Database License (ODbL 1.0) this dataset is under and be aware of the regulations prior to using this dataset. You can learn more about ODbL 1.0 on the Open Data Commons [official site](https://opendatacommons.org/licenses/odbl/summary/).

## License

ODbL 1.0

## Tags

- OpenStreetMap
- OSM
- Open Source

## Secondary Category

## Data Page

[https://gis.utah.gov/products/sgid/society/open-source-places/]

## Update

### Update Schedule

This dataset is updated on a monthly basis.

### Previous Updates
