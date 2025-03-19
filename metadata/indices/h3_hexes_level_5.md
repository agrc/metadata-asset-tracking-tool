# Title

Utah H3 Hexes Level 5

## ID

4e8fb736-5e1a-4c84-8683-88b0fcc15768

## Brief Summary

## Summary

## Description

The H3 grid covering the state of Utah at resolution level 5.

The H3 indexing system provides a standardized and high-performance grid for aggregating data at various levels. This layer contains the spatial representation of the IDs that cover the state of Utah. While it can be used for normal GIS point-in-polygon operations, you will get much better performance using the H3 API to assign a hex ID to your points, aggregating/analyzing your points based on ID, and then joining your aggregated data to this layer on the hex IDs.

Our H3 blog post provides an overview of the system, an explanation of how we created these geometries, and an example analysis. Once the geometries were created in EPSG 4326 (WGS 84 lon/lat), they were projected to EPSG 26912 (UTM 12N) using the NAD_1983_To_WGS_1984_5 transformation.

The H3 reference polygons covering the State of Utah at resolutions 5 through 9. These were created with the H3 API produced by Uber, Inc and cover the entirety of the state. You can use these for both a standard hexagon grid for the state and a spatial dataset for points aggregated via the H3 API.

See our H3 blog post for an example usage scenario.

The H3 Spatial Index (created by Uber) helps users aggregate point data using an easily reusable common grid. This allows you to maintain a consistent geometry across all your analyses, which makes them easier to compare. H3 uses highly-optimized math routines to assign lat/long coordinates an ID corresponding to a polygon (almost always hexes) at a given resolution rather than performing a much slower point-in-polygon geometrical operation. Once you've generated IDs for your points, you can use these polygons to aggregate them and display summary statistics on a map.

We used the H3 library to create the index polygons that cover the entire State of Utah at resolutions 5 through 9. You can find more information about how we created them, along with an example of how to use them, in our H3 blog post.

Like the rest of our SGID data, the spatial reference for these polygons is UTM Zone 12N, NAD83. However, remember that your points must be in WGS 84 lat/long in order to use the H3 API to assign them a hex ID. The polygons are copyright 2022 Uber Technologies, Inc and licensed under version 2.0 of the Apache License

### What is the dataset?

### What is the purpose of the dataset?

### What does the dataset represent?

### How was the dataset created?

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

### Previous Updates
