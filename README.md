## Census US 2020

### Data


### Geographical Hierarchies

For more info read the [Geographic Areas Reference Manual](https://www.census.gov/programs-surveys/geography/guidance/geographic-areas-reference-manual.html)

- **Census Block** (`TABBLOCK20`): the smallest geographic census unit, *Census blocks* are bounded either by *visible* features --- such as streets, roads, streams, and railroad tracks --- or by *non-visible* boundaries --- such as selected property lines and city, township, school district, and county limits. Census blocks usually change every decade.

- **Block Group** (`BG`): intermediate census units, with a population size between 600 and 3,000 people, or 250 and 550 housing units.

- **Census Tract** (`TRACT`): population size between 1,200 and 8,000 people, with an optimum size of 4,000. *Census Tracts* are designed to be fairly homogeneous with respect to demographic and economic conditions when they are first established. They provide a stable set of boundaries for statistical comparison from census to census, although they can occasionally either split due to population growth or merge when there is substantial population decline.

- **County** (`US_COUNTY`): the primary division of states providing complete coverage of a state. In most states, counties are the primary legal division, while others also have *equivalent* areas like: parishes, boroughs, cities, municipalities, census subareas, independent cities, municipios, districts, and islands
  - > *Voting District* ()
  - > *County Subdivision* (`COUSUB`)

- **State** (`US_STATE`) States (and equivalent entities) are the primary governmental divisions of the United States. In addition to the 50 states, the Census Bureau treats the District of Columbia, Puerto Rico, American Samoa, the Commonwealth of the Northern Mariana Islands, Guam, and the U.S. Virgin Islands as the statistical equivalents of states for the purpose of data presentation.
  - > *School District*: *Elementary* (`ELSD`), *Secondary* (`SCSD`), and *Unified* (`UNSD`)
  - > *Congressional District* (`US_CD_116`)
  - > *Place* (`PLACE`)
  - > *State Legislative District*: *Lower Chamber* (`SLDL`) and *Upper Chamber* (`SLDU`)

- **Nation** 
  - > *ZIP Code Tabulation Areas* (`ZCTA520`)
  - > *Urban Area* (`US_UAC10`)
  - > *Core Based Statistical Area* (*CBSA*)
        - *Metropolitan/Micropolitan Statistical Area* (`CBSA`)
        - *Combined New England City and Town Area* (`CNECTA`)
        - *Combined Statistical Area* (`CSA`)
        - *Metropolitan Division* (`METDIV`)
        - *New England City and Town Area* (`NECTA`)
        - *New England City and Town Area Division* (`NECTADIV`)

All geography polygons in shapefile format can be downloaded from [this FTP site](ftp2.census.gov) in this folder `/geo/tiger/TIGER2021/` using the coded acronym above as references. For all other formats, please refer to the [TIGER Data Products Guide](https://www.census.gov/programs-surveys/geography/guidance/tiger-data-products-guide.html)
