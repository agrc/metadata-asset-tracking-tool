# Title

Utah H3 Hexes Level 9

## ID

fa32e46f-2f64-4797-915b-153ec92091a0

## Brief Summary

Polygon dataset of H3 Spatial Index hexes for data aggregation and spatial statistics and resolution level 9.

## Summary

The [H3 indexing system](https://h3geo.org/docs) provides a standardized and high-performance grid for aggregating point data at various levels. This layer contains the spatial representation of the hex IDs that cover the state of Utah for resolution level 9.

## Description

### What is the dataset?

The H3 Spatial Index (created by Uber) helps users aggregate point data using a reusable common grid with consistent geometry. H3 uses highly optimized math routines to assign lat/long coordinates an ID corresponding to a polygon (almost always hexes) at a given [resolution level](https://h3geo.org/docs/core-library/restable). The resulting hexes can be used to aggregate data and display spatial statistics.

### What is the purpose of the dataset?

This dataset is suitable for normal GIS point-in-polygon spatial operations. However, UGRC recommends that you use the [H3 API](https://h3geo.org/docs/api/indexing) to assign a hex ID to your points, then aggregate and analyze your points based on those IDs, and finally join your aggregated data table to this layer on the hex IDs to get a spatial representation. This can be much faster for large datasets than spatial point-in-polygon operations.

### What does the dataset represent?

Each hex in this dataset indicates a H3 hex in or around Utah and includes the hex ID.

### How was the dataset created?

The H3 Hexes were created with the H3 API produced by [Uber, Inc](https://www.uber.com/us/en/about/?uclick_id=82b730cd-637d-46eb-9e49-c7da6cd0c21e) and cover the entirety of the state. Once the geometries were created in EPSG 4326 (WGS 84 lon/lat), they were projected to EPSG 26912 (UTM 12N) using the NAD_1983_To_WGS_1984_5 transformation. Our [H3 blog post](https://gis.utah.gov/blog/2022-10-26-using-h3-hexes/) provides an overview of the system, an explanation of how we created these geometries, and an example analysis.

### How reliable and accurate is the dataset?

This dataset reflects the most current and complete version of H3 Level 9 Hexes available in Utah. Please reach out to [our team](https://gis.utah.gov/contact/) with questions or concerns about this dataset.

## Credits

### Data Source

Uber

### Host

UGRC

## Restrictions

## License

The polygons are copyright 2022 Uber Technologies, Inc and licensed under version 2.0 of the [Apache License](https://www.apache.org/licenses/LICENSE-2.0).

## Tags

- Uber
- H3geo
- Hexagons

## Secondary Category

## Data Page Link

## Update

### Update Schedule

Static

### Previous Updates
