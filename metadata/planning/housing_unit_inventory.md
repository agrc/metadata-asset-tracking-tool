# Title

Utah Housing Unit Inventory

## ID

48f9d241-63fb-4ed9-ae35-58d14a3998a6

## Brief Summary

## Summary

## Description

Characteristics of housing units on a per-parcel or per-development (for PUDs, townhomes, condos, etc) basis derived from LIR parcels and county assessor data.

The Housing Unit Inventory (HUI) is a derivative dataset that, per 
UCA 63A-16-S506(4)
, opens in a new tab, adds additional housing characteristics to the County Assessors' tax parcel data for Utah's most urban counties. It is not a substitute for the excellent datasets maintained by the Assessors but instead presents additional, standardized information about the type and number of housing units, associated grounds and common areas, and related short-term and long-term trends. The HUI is a best-effort product of a resource-limited analysis — users are encouraged to do their own quality assessment, share their findings, and cite this metadata describing how the HUI was produced.

WFRC, MAG, and UGRC are creating this dataset from the Land Information Record (LIR) parcel datasets published by UGRC. The LIR datasets are made possible by the county assessors voluntary sharing their annual tax assessment data. The tax roll data are frozen as of midnight Jan 1st for the specified year, finalized in late May, and typically loaded into the SGID later that summer.

WFRC, the metropolitan planning organization for the urban portions of Salt Lake County, Davis County, and Weber county, prepared the initial 2020 Housing Inventory dataset for their counties and defined the inventory process laid out below. MAG will be providing data for their counties, and UGRC is working with other counties to create inventories as requested.

The inventory applies apartment unit counts to multi-family rental properties that do not have individually-owned and platted units (traditional apartment buildings, quadplexes, triplexes, mixed use buildings etc). These unit counts come from the address point data layer, with some counts being assigned manually using information from recent aerial photography and other sources.
For cases where individual condos, townhomes, and single family homes have associated common areas, the inventory aggregates and combines the geometries and attributes of the individual units and common areas into a single composite parcel feature called an "owned unit grouping". This sums, averages, and counts the appropriate attributes of the contributing parcels to better characterize the density of these residential land uses (dwelling units per acre or DUA).
Every county uses a slightly different set of designations when defining residential parcel types. The inventory attempts to standardize all the different classifications into the following categories:
Townhouse
Condo
Apartment
Single family
Single family with Accessory Dwelling Units (ADUs, currently only for Salt Lake County)
Duplex
Mixed use (commercial and residential)
Mobile home
Pud (mixed)
Group quarters
The inventory doesn't include the following types of residential properties:
Nursing, rehabilitation, or assisted living centers
Extended stay hotels
Incarceration facilities
Student housing or dormitories
ADUs outside Salt Lake County
The inventory uses the following fields to provide data on each parcel or owned unit grouping:

TYPE
General housing type, single- or multi-family
SUBTYPE
More detailed housing type classification
IS_OUG
1 or Yes for features that are owned unit groupings (as opposed to a single-parcel home or apartment)
UNIT_COUNT
The number of dwelling units, based on address point data
DUA
Density in dwelling units per acre
ACRES
Total acreage
TOT_BD_FT2
Total building(s) square footage
TOT_VALUE
Total market value
APX_BLT_YR
Approximate year built
BLT_DECADE
The decade the structure(s) were built
CITY
The features' city based on the SGID's municipal boundaries data
COUNTY
The features' county
SUBCOUNTY
If provided in the analysis, this groups the features into predefined areas for later grouping and analysis

### What is the dataset?

### What is the purpose of the dataset?

### What does the dataset represent?

### How was the dataset created?

### How reliable and accurate is the dataset?

## Credits

### Data Source

WFRC

### Host

UGRC

## Restrictions

## License

## Tags

## Secondary Category

## Data Page Link

[https://gis.utah.gov/products/sgid/planning/housing-unit-inventory/]

## Update

### Update Schedule

<!--- Unknown --->

### Previous Updates
