# Title

Utah Housing Unit Inventory

## ID

48f9d241-63fb-4ed9-ae35-58d14a3998a6

## Brief Summary

Polygon dataset of housing units in Utah derived from LIR parcels and county assessor data.

## Summary

This dataset contains polygons representing a wide variety of housing units in Utah, such as single-family homes, apartments, and mobile homes. These data do not include residential units such as assisted living centers or incarceration facilities.

## Description

### What is the dataset?

The Housing Unit Inventory (HUI) is a derivative dataset that, per [UCA 63A-16-S506(4)](https://le.utah.gov/xcode/Title63A/Chapter16/63A-16-S506.html) adds additional housing characteristics to the County Assessors' tax parcel data for Utah's most urban counties. The HUI is a best-effort product of a resource-limited analysis; users are encouraged to do their own quality assessment, share their findings, and cite this metadata describing how the HUI was produced.

Each county in Utah uses a slightly different set of designations when defining residential parcel types. This statewide inventory standardizes these various classifications into the following categories:

- Townhouse
- Condo
- Apartment
- Single family
- Single family with Accessory Dwelling Units (ADUs, currently only for Salt Lake County)
- Duplex
- Mixed use (commercial and residential)
- Mobile home
- Planned Unit Development (PUD) (mixed)
- Group quarters

This inventory does not include the following types of residential properties:

- Nursing, rehabilitation, or assisted living centers
- Extended stay hotels
- Incarceration facilities
- Student housing or dormitories
- ADUs outside Salt Lake County

### What is the purpose of the dataset?

This dataset has been made available for use in state and regional planning and analysis.

### What does the dataset represent?

Each polygon in this dataset represents a housing unit, where some polygons may represent multi-family or single-family units. The inventory applies apartment unit counts to multi-family rental properties that do not have individually-owned and platted units (traditional apartment buildings, quadplexes, triplexes, mixed use buildings etc). These unit counts come from the [Utah Address Points](https://gis.utah.gov/products/sgid/location/address-points/) dataset, with some counts being assigned manually using information from recent aerial photography and other sources.

For cases where individual condos, townhomes, and single family homes have associated common areas, the inventory aggregates and combines the geometries and attributes of the individual units and common areas into a single composite parcel feature called an "owned unit grouping". This sums, averages, and counts the appropriate attributes of the contributing parcels to better characterize the density of these residential land uses (dwelling units per acre or DUA).

### How was the dataset created?

UGRC created this dataset in collaboration with the [Wasatch Front Regional Council](https://wfrc.org/) and [Mountainland Association of Governments](https://magutah.gov/). This combined effort uses Land Information Record(LIR) [parcel datasets](https://gis.utah.gov/products/sgid/cadastre/parcels/) made possible through county-level tax asessment data. The tax roll data are frozen as of January 1 for the specified year, finalized in late May, and typically loaded into the SGID later that summer. These data are maintained by UGRC and many state and regional partners.

### How reliable and accurate is the dataset?

This dataset is not a substitute for the locally maintained datasets from county assessors, but instead presents additional standardized information about the type and number of housing units, associated grounds and common areas, and related short-term and long-term trends. Please reach out to [our team](https://gis.utah.gov/contact/) with questions or concerns about this dataset.

<!--- I feel like there are more caveats I should add here, but I'm not too sure what those caveats should be. --->

## Credits

### Data Source

WFRC

### Host

UGRC

## Restrictions

## License

## Tags

- Housing property
- Private property
- Rental property
- WFRC
- MAG

## Secondary Category

## Data Page Link

[https://gis.utah.gov/products/sgid/planning/housing-unit-inventory/]

## Update

### Update Schedule

<!--- Do we have a specific update schedule for these data? --->

### Previous Updates
