# Title

Utah VISTA Ballot Areas

<!--- VISTA or Vista? I've seen it both ways in the metadata and on our blog. Also, I noticed the information on this dataset mostly refers to the polygons as "voting precincts" rather than ballot areas, should we change the title accordingly? -->

## ID

fb485021-1a93-43b3-bd3b-13c68d7e5b3c

## Brief Summary

Official voting precincts used by Utah's VISTA election framework.

## Summary

Statewide polygon layer that depicts voting precinct and subprecinct boundaries. This dataset serves as the baseline for VISTA, Utah's election registration database, as well as many other voter information websites.

## Description

### What is the dataset?

Voting precincts are used to determine a voter's ballot composition and polling location. A number of factors contribute to this, including the boundaries of all political districts covering the voter's address (U.S. Congress, State House and Senate, State School Board, municipal districts, etc.) and the legislatively-mandated maximum limit of voters per precinct.

### What is the purpose of the dataset?

This dataset is actively used in more than 20 counties in Utah. These are counties that have adopted a GIS-based approach to manage precinct-to-residence assignment within VISTA, the statewide voter registration database. This dataset also drives many of the State's voter information pages and helps citizens know [how and where to vote](https://votesearch.utah.gov/voter-search/search/search-by-address/how-and-where-can-i-vote).

<!--- The blog post I got this information from was from 2012. Do all of the counties in Utah use this dataset nowadays? -->

### What does the dataset represent?

This dataset contains polygons representing more than 3000 voting precincts and subprecincts in Utah. Each feature contains attributes such as the date the precinct boundary took effect (effectivedate) and whether the polygon contains a subprecinct boundary (indicated, where applicable, in the subprecinct field).

<!--- This next paragraph is from the original metadata. I haven't seen other data pages explain GIS operations for a dataset in this way, is this something we generally like to include? -->

Precincts can be formed (and subprecinct divisions eliminated) by performing a GIS ‘dissolve’ operation on the precinctid field.

### How was the dataset created?

UGRC aggregates voter precinct data submitted by County Clerk offices. This dataset is updated periodically as municipal and county boundaries change and as voter count grows beyond the maximum number of voters allowed per precinct (currently 1250 voters).

### How reliable and accurate is the dataset?

This dataset represents the most current and complete compilation of precincts and subprecincts in Utah. Please reach out to [our team](https://gis.utah.gov/contact/) with questions concerning this dataset.

## Credits

### Data Source

UGRC

### Host

UGRC

## Restrictions

## License

## Tags

- Voting precincts
- Election
- Ballot composition

## Secondary Category

## Data Page Link

[https://gis.utah.gov/products/sgid/political/voter-precincts/]

## Update

### Update Schedule

This dataset is updated as needed.

### Previous Updates
