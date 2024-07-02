# Title

Utah Basic Parcels

## ID

cbe4da2a-3edb-4a4a-b082-60f9371c8006

## Brief Summary

Parcel boundaries for all 29 counties in Utah that include basic information such as parcel ID, parcel address, and generalized land ownership.

## Summary

This dataset contains information such as the county FIPS code, parcel ID, parcel address, generalized land ownership type, currency dates, phone number for the county recorder, and the county parcel website if available. Landowners of privately owned parcels are not specified.

## Description

### What is the dataset?

A parcel is a defined area of land that is owned by a public or private entity. Each county provides its individual parcel data to UGRC; thus, users should expect some variation in schema and completeness between counties.

### What is the purpose of the dataset?

These data represent UGRC's ongoing efforts to compile statewide parcels following the passage of [HB113](https://le.utah.gov/~2005/bills/hbillenr/HB0113.htm) in 2005. Parcel data are used in city planning, economic development, transportation, public services, and many other areas.

### What does the dataset represent?

Parcels are represented as polygons and contain attributes unique to each parcel, such as a unique parcel number (PARCEL_ID), address for the parcel (PARCEL_ADD, PARCEL_CITY, PARCEL_ZIP), update information (ParcelsCur, ParcelsRec, ParcelsPub, ParcelYear, ParcelNotes), a generalized land ownership designation (OWN_TYPE), the phone number for the county recorders office (RECORDER), and a link to the county parcel website (CoParcel_URL) if available. Fields and field definitions may vary from county to county.

### How was the dataset created?

UGRC compiled this dataset from digital parcel data submissions provided by county authorities. The owner type field OWN_TYPE is a generalized ownership type (Federal, Private, State, Tribal) and is populated with the value of the OWNER field where the parcel's centroid intersects the [Land Ownership](https://gis.utah.gov/products/sgid/cadastre/land-ownership/) data layer found in the SGID.

UGRC currently maintains this dataset is partnership with local county authorities.

### How reliable and accurate is the dataset?

This dataset is not a substitute for obtaining the most current, legal land records information from county authorities. Parcel boundary data found on our website does not represent exact legal boundaries of parcels in Utah and should be used for general analysis and visualization purposes only.

Additionally, while street addresses are provided with the parcel boundaries, the authoritative source for Utah addresses is the [Utah Address Points](https://gis.utah.gov/products/sgid/location/address-points/) dataset.

## Credits

### Data Source

- UGRC
- Counties

### Host

UGRC

## Restrictions

## License

## Tags

- Land ownership
- Private land
- Public land
- HB113

## Secondary Category

Boundaries

## Data Page Link

[https://gis.utah.gov/products/sgid/cadastre/parcels/]

## Update

### Update Schedule

UGRC updates the parcel datasets for Davis, Salt Lake, Utah, Washington, and Weber counties every month. All other counties are updated on a rotating schedule ranging from a quarterly to an annual basis.

### Previous Updates
