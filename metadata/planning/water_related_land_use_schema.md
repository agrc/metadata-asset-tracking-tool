# Title

Utah Water Related Land Use Field Definitions

## ID

524ed000-7fae-46b7-b82f-13f4ed655f60

### LUID

Unique ID number for each polygon in the final dataset, not consistent between yearly datasets.

### Landuse

A general land cover classification differentiating how the land is used.

Values:

- Agriculture: Land managed for crop or livestock purposes.
- Other: A broad classification of wildland.
- Riparian/Wetland: Wildland influenced by a high water table, often close to surface water.
- Urban: Developed areas, includes urban greenspace such as parks.
- Water: Surface water such as wet flats, streams, and lakes.

### CropGroup

Groupings of broader crop categories to allow easy access to or query of all orchard or grain types etc.

### Description

Attribute that describes/indicates the various crop types and land use types determined by the GIS process.

### IRR_Method

Indicates the primary irrigation method for the area.

Values:

- Crop Irrigation Method carried over from statewide field surveys ending in 2015 and updated based on imagery and yearly field checks.
- Drip: Water is applied through lines that slowly release water onto the surface or subsurface of the crop.
- Dry Crop: No irrigation method is applied to this agricultural land, the crop is irrigated via natural processes.
- Flood: Water is diverted from ditches or pipes upland from the crop in sufficient quantities to flood the irrigated plot.
- None: Associated with non-agricultural landSprinkler: Water is applied above the crop via sprinklers that generally move across the field.
- Sub-irrigated: This land does not have irrigation water applied, but due to a high water table receives more water, and is generally closely associated with a riparian area.

### Acres

Calculated acreage of the polygon.

### State

State where the polygons are found.

### Basin

The hydrologic basin where the polygons are found, closely related to HUC 6. These basin boundaries were created by DWRe to include portions of other basins that have inter-basin flows for management purposes.

### SubArea

The subarea where the polygons are found, closely related to the HUC 8. Subareas are subdivisions of the larger hydrologic basins created by DWRe.

### Label_Class

Combination of Label and Class_Name fields created during processing that indicates the specific crop, irrigation, and whether the CDL classified the land as a similar crop or an “Other” crop.

### Label

A shorthand descriptive label for each crop description and irrigation type.

### Class_Name

The majority pixel value from the USDA [CDL Cropscape](https://www.nass.usda.gov/Research_and_Science/Cropland/SARS1a.php) raster layer within the polygon, may differ from final crop determination (Description).

### OldLanduse

Similar to Landuse, but splits the agricultural land further depending on irrigation. Pre-2017 datasets defined this as Landuse.

### lu_Group

These codes represent some in-house groupings that are useful for symbology and other summarizing.

### Field_Check

Indicates the year the polygon was last field checked.

### SURV_YEAR

Indicates which year/growing season the data represents.
