# Title

Utah Address System Quadrants

## ID

ae2b0c31-a204-462d-a799-971f43df6eca

## Brief Summary

Polygon dataset containing the extent of each addressing grid, and its four quadrants (NE, NW, SE, SW), which define how address numbers are assigned in Utah.

## Summary

This dataset contains polygon boundaries for the extent of each addressing grid, and its four quadrants (NE, NW, SE, SW). These grids define which numbers are assigned to physical addresses for homes, buildings, roads, and other structures in Utah. This dataset contains address grids only, for data on individual addresses, please see the [Address Points](https://gis.utah.gov/products/sgid/location/address-points/) dataset available in the SGID.

## Description

### What is the dataset?

These data represent the boundaries of address systems that local government authorities use to assign address numbers. An addressing system consists of an origin coordinate, a north-south axis, an east-west axis, and a boundary within which address numbers are assigned using this particular grid. The originate coordinate (0,0) is typically located at the intersection of Main and Center streets. This convention governs the assignment of addresses and is typically expressed as 100 address ranges per block or 800 address ranges per mile. Many municipalities can be contained within a single address system. For example, the Salt Lake address system includes all municipalities in Salt Lake County.

### What is the purpose of the dataset?

UGRC maintains a statewide dataset of address system quadrants primarily to improve address geocoding with the [UGRC API](https://api.mapserv.utah.gov/docs/). When geocoding an address, the input place name or ZIP code is replaced with the address system to provide the highest match rates. You can learn more about the history of addressing systems and how they are used today in our blog post, [The Western Grid, Explained](https://gis.utah.gov/blog/2019-03-11-the-western-grid/).

### What does the dataset represent?

Each polygon in this dataset represents the geographical area of a given address system and its quadrants. Features in this dataset include the system name, quadrant direction, and county name.

### How was the dataset created?

UGRC created this dataset using data submitted by local government partners. We update this dataset quarterly to account for annexations and the creation of new address systems.

### How reliable and accurate is the dataset?

This dataset is the most current and complete version of address system quadrants available in Utah. Please reach out to [our team](https://gis.utah.gov/contact/) with questions or concerns about this dataset.

## Credits

### Data Source

UGRC

### Host

UGRC

## Restrictions

## License

## Tags

- geocoding
- UGRC API

## Secondary Category

## Data Page Link

[https://gis.utah.gov/products/sgid/location/address-system-quadrants/]

## Update

### Update Schedule

This dataset is updated on a quarterly basis.

### Previous Updates
