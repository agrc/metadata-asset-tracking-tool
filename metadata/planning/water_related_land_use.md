# Title

Water Related Land Use

## ID

524ed000-7fae-46b7-b82f-13f4ed655f60

## Brief Summary

## Summary

## Description

Yearly layer of agricultural and other water-related land use and crop types in and around Utah. 2023

Feature Classes are loaded onto tablet PCs and Field crews are sent to label the crop or land cover type and irrigation method for a subset of select fields or polygons. Each tablet PC is attached to a GPS unit for real-time tracking to continuously update the field crew’s location during the field labeling process.

Digitizing is done as Geodatabase feature classes using ArcPro 3.1.0 with Sentinel imagery as a background with other layers added for reference. Updates to existing field boundaries of individual agricultural fields, urban areas and more are precisely digitized. Changes in irrigation type and land use are noted during this process.

Cropland Data Layer (CDL) rasters from the United States Department of Agriculture (USDA) National Agricultural Statistics Service (NASS) are downloaded for the appropriate year. https://nassgeodata.gmu.edu/CropScape/

Zonal Statistics geoprocessing tools are used to attribute the polygons with updated crop types from the CDL. The data is then run through several stages of comparison to historical inventories and quality checking in order to determine and produce the final attributes.

LUID - Unique ID number for each polygon in the final dataset, not consistent between yearly datasets.

Landuse - A general land cover classification differentiating how the land is used.

Agriculture: Land managed for crop or livestock purposes.

Other: A broad classification of wildland.

Riparian/Wetland: Wildland influenced by a high water table, often close to surface water.

Urban: Developed areas, includes urban greenspace such as parks.

Water: Surface water such as wet flats, streams, and lakes.

CropGroup - Groupings of broader crop categories to allow easy access to or query of all orchard or grain types etc.

Description - Attribute that describes/indicates the various crop types and land use types determined by the GIS process.

IRR_Method - Crop Irrigation Method carried over from statewide field surveys ending in 2015 and updated based on imagery and yearly field checks.

Drip: Water is applied through lines that slowly release water onto the surface or subsurface of the crop.

Dry Crop: No irrigation method is applied to this agricultural land, the crop is irrigated via natural processes.

Flood: Water is diverted from ditches or pipes upland from the crop in sufficient quantities to flood the irrigated plot.

None: Associated with non-agricultural landSprinkler: Water is applied above the crop via sprinklers that generally move across the field.

Sub-irrigated: This land does not have irrigation water applied, but due to a high water table receives more water, and is generally closely associated with a riparian area.

Acres - Calculated acreage of the polygon.

State - State where the polygons are found.

Basin - The hydrologic basin where the polygons are found, closely related to HUC 6. These basin boundaries were created by DWRe to include portions of other basins that have inter-basin flows for management purposes.

SubArea - The subarea where the polygons are found, closely related to the HUC 8. Subareas are subdivisions of the larger hydrologic basins created by DWRe.

Label_Class - Combination of Label and Class_Name fields created during processing that indicates the specific crop, irrigation, and whether the CDL classified the land as a similar crop or an “Other” crop.

LABEL - A shorthand descriptive label for each crop description and irrigation type.

Class_Name - The majority pixel value from the USDA CDL Cropscape raster layer within the polygon, may differ from final crop determination (Description).

OldLanduse - Similar to Landuse, but splits the agricultural land further depending on irrigation. Pre-2017 datasets defined this as Landuse.

LU_Group - These codes represent some in-house groupings that are useful for symbology and other summarizing.

Field_Check - Indicates the year the polygon was last field checked. *New for 2019

SURV_YEAR - Indicates which year/growing season the data represents.

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
