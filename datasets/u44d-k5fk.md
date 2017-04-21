# Spill Incidents

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/spill-incidents) |
| Metadata | [Link](https://data.ny.gov/api/views/u44d-k5fk) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/u44d-k5fk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/u44d-k5fk/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | u44d-k5fk |
| Name | Spill Incidents |
| Attribution | New York State Department of Environmental Conservation |
| Category | Energy & Environment |
| Tags | spills, petroleum spills, hazardous materials, chemical spills, oil |
| Created | 2015-10-19T16:27:38Z |
| Publication Date | 2017-04-20T15:32:50Z |

## Description

This dataset contains records of spills of petroleum and other hazardous materials. Under State law and regulations, spills that could pollute the lands or waters of the state must be reported by the spiller (and, in some cases, by anyone who has knowledge of the spill). Examples of what may be included in a spill record includes: Administrative information (DEC region and unique seven-digit spill number). Program facility name. Spill date/time. Location. Spill source and cause. Material(s) and material type spilled. Quantity spilled and recovered. Units measured. Surface water bodies affected. Close date (cleanup activity finished and all paperwork completed).

## Columns

```ls
| Included | Schema Type    | Field Name            | Name                  | Data Type     | Render Type   |
| ======== | ============== | ===================== | ===================== | ============= | ============= |
| Yes      | series tag     | spill_number          | Spill Number          | text          | text          |
| Yes      | series tag     | program_facility_name | Program Facility Name | text          | text          |
| Yes      | series tag     | street_1              | Street 1              | text          | text          |
| Yes      | series tag     | street_2              | Street 2              | text          | text          |
| Yes      | series tag     | locality              | Locality              | text          | text          |
| Yes      | series tag     | county                | County                | text          | text          |
| Yes      | series tag     | zip_code              | ZIP Code              | text          | text          |
| Yes      | series tag     | swis_code             | SWIS Code             | text          | text          |
| Yes      | numeric metric | dec_region            | DEC Region            | number        | number        |
| Yes      | time           | spill_date            | Spill Date            | calendar_date | calendar_date |
| No       |                | received_date         | Received Date         | calendar_date | calendar_date |
| Yes      | series tag     | contributing_factor   | Contributing Factor   | text          | text          |
| Yes      | series tag     | waterbody             | Waterbody             | text          | text          |
| Yes      | series tag     | source                | Source                | text          | text          |
| No       |                | close_date            | Close Date            | calendar_date | calendar_date |
| Yes      | series tag     | material_name         | Material Name         | text          | text          |
| Yes      | series tag     | material_family       | Material Family       | text          | text          |
| Yes      | numeric metric | quantity              | Quantity              | number        | number        |
| Yes      | series tag     | units                 | Units                 | text          | text          |
| Yes      | numeric metric | recovered             | Recovered             | number        | number        |
```

## Time Field

```ls
Value = spill_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = received_date,close_date
```

## Data Commands

```ls
series e:u44d-k5fk d:2001-10-10T00:00:00.000Z t:material_name="unknown material" t:street_1="RT 119/MILLWOOD RD" t:source=Unknown t:county=Westchester t:locality=ELMSFORD t:swis_code=6000 t:contributing_factor=Unknown t:material_family=Other t:spill_number=0107132 t:units=Gallons t:program_facility_name="MH 864" m:recovered=0 m:quantity=10 m:dec_region=3

series e:u44d-k5fk d:2004-08-21T00:00:00.000Z t:material_name="raw sewage" t:street_1="WATER POLL CONTROL" t:source=Unknown t:county=Queens t:waterbody="EAST RIVER" t:locality=QUEENS t:swis_code=4101 t:contributing_factor=Other t:material_family=Other t:spill_number=0405586 t:units=Pounds t:program_facility_name="BOWRY BAY" m:recovered=0 m:quantity=0 m:dec_region=2

series e:u44d-k5fk d:2004-08-21T00:00:00.000Z t:material_name="raw sewage" t:street_1="WATER POLL CONTROL" t:source=Unknown t:county=Queens t:waterbody="EAST RIVER" t:locality=QUEENS t:swis_code=4101 t:contributing_factor=Other t:material_family=Other t:spill_number=0405586 t:program_facility_name="BOWRY BAY" m:recovered=0 m:quantity=0 m:dec_region=2
```

## Meta Commands

```ls
metric m:dec_region p:long l:"DEC Region" d:"NYSDEC Region where the spill is located: Region 1: (Long Island) Nassau and Suffolk counties; Region 2: (New York City) Brooklyn, Bronx, Manhattan, Queens and Staten Island; Region 3: (Lower Hudson Valley) Dutchess, Orange, Putnam, Rockland, Sullivan, Ulster and Westchester counties; Region 4: (Capital Region/Northern Catskills) Albany, Columbia, Delaware, Greene, Montgomery, Otsego, Rensselaer, Schenectady and Schoharie counties; Region 5: (Eastern Adirondacks/Lake Champlain) Clinton, Essex, Franklin, Fulton, Hamilton, Saratoga, Warren and Washington counties; Region 6: (Western Adirondacks/Eastern Lake Ontario) Herkimer, Jefferson, Lewis, Oneida and St. Lawrence counties; Region 7: (Central New York) Broome, Cayuga, Chenango, Cortland, Madison, Onondaga, Oswego, Tioga and Tompkins counties; Region 8: (Western Finger Lakes) Chemung, Genesee, Livingston, Monroe, Ontario, Orleans, Schuyler, Seneca, Steuben, Wayne and Yates counties; Region 9: (Western New York) Allegany, Chautauqua, Cattaraugus, Erie, Niagara and Wyoming counties." t:dataTypeName=number

metric m:quantity p:long l:Quantity d:"Amount of substance found/spilled. (If unknown: ?0?) Note that the quantity can include amount of contaminated soil or water that is combined with the spilled material." t:dataTypeName=number

metric m:recovered p:long l:Recovered d:"Amount of material recovered, if applicable. ?Recovered? material units are the same as the ?Quantity? spill units. (If amount recovered is unknown: ?0?). Note that the quantity recovered can be greater than the amount spilled when contaminated soil or water is collected with the spilled material." t:dataTypeName=number

entity e:u44d-k5fk l:"Spill Incidents" t:attribution="New York State Department of Environmental Conservation" t:url=https://data.ny.gov/api/views/u44d-k5fk

property e:u44d-k5fk t:meta.view v:id=u44d-k5fk v:category="Energy & Environment" v:attributionLink=http://www.dec.ny.gov/chemical/8428.html v:averageRating=0 v:name="Spill Incidents" v:attribution="New York State Department of Environmental Conservation"

property e:u44d-k5fk t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:u44d-k5fk t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"
```

## Top Records

```ls
| spill_number | program_facility_name | street_1                  | street_2 | locality  | county      | zip_code | swis_code | dec_region | spill_date          | received_date       | contributing_factor | waterbody  | source                                  | close_date          | material_name    | material_family | quantity | units   | recovered | 
| ============ | ===================== | ========================= | ======== | ========= | =========== | ======== | ========= | ========== | =================== | =================== | =================== | ========== | ======================================= | =================== | ================ | =============== | ======== | ======= | ========= | 
| 0107132      | MH 864                | RT 119/MILLWOOD RD        |          | ELMSFORD  | Westchester |          | 6000      | 3          | 2001-10-10T00:00:00 | 2001-10-10T00:00:00 | Unknown             |            | Unknown                                 | 2001-10-15T00:00:00 | unknown material | Other           | 10.00    | Gallons | 0.00      | 
| 0405586      | BOWRY BAY             | WATER POLL CONTROL        |          | QUEENS    | Queens      |          | 4101      | 2          | 2004-08-21T00:00:00 | 2004-08-21T00:00:00 | Other               | EAST RIVER | Unknown                                 | 2004-09-17T00:00:00 | raw sewage       | Other           | 0.00     | Pounds  | 0.00      | 
| 0405586      | BOWRY BAY             | WATER POLL CONTROL        |          | QUEENS    | Queens      |          | 4101      | 2          | 2004-08-21T00:00:00 | 2004-08-21T00:00:00 | Other               | EAST RIVER | Unknown                                 | 2004-09-17T00:00:00 | raw sewage       | Other           | 0.00     |         | 0.00      | 
| 0204667      | POLE 16091            | GRACE AVE/BURKE AVE       |          | BRONX     | Bronx       |          | 0301      | 2          | 2002-08-02T00:00:00 | 2002-08-02T00:00:00 | Equipment Failure   |            | Commercial/Industrial                   | 2002-10-28T00:00:00 | transformer oil  | Petroleum       | 1.00     | Gallons | 0.00      | 
| 0210559      | POLE ON               | FERDALE LOMIS RD / RT 52  |          | LIBERTY   | Sullivan    |          | 5336      | 3          | 2003-01-20T00:00:00 | 2003-01-20T00:00:00 | Traffic Accident    |            | Commercial/Industrial                   | 2003-01-22T00:00:00 | transformer oil  | Petroleum       | 6.00     | Gallons | 6.00      | 
| 9002315      | PIPING ROCK OIL CO    | 494 SOUTH OCEAN AVENUE    |          | FREEPORT  | Nassau      |          | 3000      | 1          | 1990-05-29T00:00:00 | 1990-05-29T00:00:00 | Unknown             |            | Institutional, Educational, Gov., Other | 1990-07-13T00:00:00 | #2 fuel oil      | Petroleum       | 0.00     | Gallons | 0.00      | 
| 0104307      | 149TH RD              | 183RD ST, 149TH AV& 149RD |          | QUEENS    | Queens      |          | 4101      | 2          | 2001-07-23T00:00:00 | 2001-07-23T00:00:00 | Abandoned Drums     |            | Unknown                                 | 2001-08-01T00:00:00 | unknown material | Other           | 0.00     | Gallons | 0.00      | 
| 0160046      | ABANDONED DRUMS       | BAKER SCHOOL HOUSE ROAD   |          | SOLON     | Cortland    |          | 1200      | 7          | 2001-11-23T00:00:00 | 2001-11-23T00:00:00 | Abandoned Drums     |            | Unknown                                 | 2002-05-14T00:00:00 | unknown material | Other           | 0.00     | Gallons | 0.00      | 
| 9606869      | AMSTERDAM AVE         | WEST 79 TH STREET         |          | NYC       | New York    |          | 3101      | 2          | 1996-08-28T00:00:00 | 1996-08-28T00:00:00 | Traffic Accident    |            | Commercial Vehicle                      | 1996-08-29T00:00:00 | antifreeze       | Other           | 2.00     | Gallons | 2.00      | 
| 0312198      | APARTMENT BUILDING    | 4 SOUTH SIDE TERRACE APAR |          | NEW PALTZ | Ulster      |          | 5638      | 3          | 2004-02-02T00:00:00 | 2004-02-02T00:00:00 | Tank Failure        |            | Commercial/Industrial                   | 2004-04-05T00:00:00 | #2 fuel oil      | Petroleum       | 0.00     | Pounds  | 0.00      | 
```