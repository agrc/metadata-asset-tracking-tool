# Title

Utah Open Sources Places

## ID

ce969f6a-2a36-4485-8594-ff17d7bd82e6

## Brief Summary

Point representation of places of interest in Utah that have been derived from OpenStreetMap (OSM)

## Summary

## Description

### What is the dataset?

These data may include businesses, restaurants, places of worship, airports, parks, schools, event centers, apartment complexes, hotels, car dealerships…almost anything that you can find in OSM. There were over 23,000 features in the original dataset (March 2022) and users can directly contribute to it through openstreetmap.org.

### What is the purpose of the dataset?

### What does the dataset represent?

### How was the dataset created?

This point data was generated and filtered from OpenStreetMap (OSM) and is intended to represent places of interest in the state of Utah.

The Open Source Places layer is created by a Python script that downloads statewide OSM data from a nightly archive provided by Geofabrik. The archive data contains nearly 20 shapefiles, some that are relevant to this dataset and some that aren't.

The Open Source Places layer is built by filtering the polygon and point data in those shapefiles down to a single point feature class with specific categories and attributes that UGRC determines would be of widest interest. The polygon features (buildings, areas, complexes, etc.) are converted to points using an internal centroid. Spatial filtering is done as the data from multiple shapefiles is combined into a single layer to minimize the occurrence of duplicate features. For example, a restaurant can be represented in OSM as both a point of interest and as a building polygon, the spatial filtering helps reduce the chances that both of these features are present in the final dataset.

Additional de-duplication is performed by using the 'block_id' field as a spatial index to ensure that no two features of the same name exist within a census block. Then, additional fields are created and assigned from UGRC's SGID data (county, city, zip, nearby address, etc.) via point-in-polygon and near analyses. A numeric check is done on the 'name' field to remove features where the name is less than 3 characters long or more than 50% numeric characters. This eliminates several features derived from the buildings layer where the 'name' is simply an apartment complex building number (ex: 3A) or house number (ex: 1612).

Finally, additional attributes (osm_addr, open_hours, phone, website cuisine, etc.) are pulled from the Overpass API and joined to the filtered data using the 'osm_id' field as the join key.

### How reliable and accurate is the dataset?

## Credits

### Data Source

### Host

## Restrictions

## License

## Tags

## Secondary Category

## Data Page Link

## Update

### Update Schedule

This dataset is updated on a monthly basis.

### Previous Updates
