# Title

Utah Open Sources Places Field Definitions

## ID

ce969f6a-2a36-4485-8594-ff17d7bd82e6

osm_id
The feature ID in the OSM database.
name
The name of the feature in the OSM database.
category
The feature's data class based on the 4-digit code and tags in the OSM database.
county
The county the feature is located in (assigned from UGRC's county boundaries).
city
The city the feature is located in (assigned from UGRC's municipal boundaries).
zip
The zip code of the feature (assigned from UGRC's approximation of zip code boundaries).
block_id
The census block the feature is located in (assigned from UGRC's census block boundaries).
osm_addr
The feature's address in the OSM database, if available.
ugrc_addr
The nearest address (within 25 meters) from the UGRC address point database.
addr_dist
The distance (meters) to the nearest UGRC address point within 25 meters.
disclaimer
A note from UGRC about the ugrc_addr field.
lon
The approximate longitude of the feature, calculated in WGS84 [EPSG:4326] (for the most precision, it is recommended that the feature's geometry is used instead of this field).
lat
The approximate latitude of the feature, calculated in WGS84 [EPSG:4326] (for the most precision, it is recommended that the feature's geometry is used instead of this field).
amenity
The amenity available at the feature (if applicable), often similar to the category.
cuisine
The type of food available (if applicable), multiple types are separated by semicolons (;).
tourism
The type of tourist location, if applicable (zoo, viewpoint, hotel, attraction, etc.).
shop
The type of shop, if applicable
website
The feature's website in the OSM database, if available.
phone
The feature's phone number(s) in the OSM database, if available.
open_hours
The feature's operating hours in the OSM database, if available.
