# Recommended Fishing Lakes and Ponds

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/recommended-fishing-lakes-and-ponds) |
| Metadata | [Link](https://data.ny.gov/api/views/mw8j-wduf) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/mw8j-wduf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/mw8j-wduf/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | mw8j-wduf |
| Name | Recommended Fishing Lakes and Ponds |
| Attribution | New York State Department of Environmental Conservation |
| Category | Recreation |
| Tags | lake, pond, fish, angler |
| Created | 2013-02-15T16:00:05Z |
| Publication Date | 2013-03-01T22:48:28Z |

## Description

This data displays the locations of top lakes and ponds for fishing in New York State, as determined by fisheries biologists working for the New York State Department of Environmental Conservation. Although every effort has been made to ensure the accuracy of information, errors may be reflected in the data supplied. The user must be aware of data conditions and bear responsibility for the appropriate use of the information with respect to possible errors, original map scale, collection methodology, currency of data, and other conditions.

## Columns

```ls
| Included | Schema Type    | Field Name  | Name                             | Data Type | Render Type |
| ======== | ============== | =========== | ================================ | ========= | =========== |
| No       | time           | :updated_at | updated_at                       | meta_data | meta_data   |
| Yes      | series tag     | water       | Waterbody Name                   | text      | text        |
| Yes      | numeric metric | acres_mile  | Acres_Mile                       | number    | number      |
| Yes      | series tag     | boat_launc  | Boat Launch Type                 | text      | text        |
| Yes      | series tag     | owner       | Boat Launch Owner                | text      | text        |
| Yes      | series tag     | ammenities  | Amenities                        | text      | text        |
| Yes      | series tag     | fish_speci  | Fish Species                     | text      | text        |
| Yes      | series tag     | ice_fishin  | Ice Fishing                      | text      | text        |
| Yes      | series tag     | comments    | Comments                         | text      | text        |
| Yes      | series tag     | bl_weblink  | Boat Launch Information          | url       | url         |
| Yes      | series tag     | weblink     | Waterbody Information            | url       | url         |
| Yes      | series tag     | contourmap  | Contour Map of Waterbody         | url       | url         |
| Yes      | series tag     | spec_regs   | Special Regulations on Waterbody | url       | url         |
| Yes      | series tag     | county      | County                           | text      | text        |
| No       |                | point_x     | Longitude                        | number    | number      |
| No       |                | point_y     | Latitude                         | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = point_x,point_y
```

## Data Commands

```ls
series e:mw8j-wduf d:2013-02-20T18:51:53.000Z t:water="Amawalk Reservoir" t:fish_speci="Brown Trout - Smallmouth Bass - Largemouth Bass - Crappie - Carp" t:county=Westchester t:owner=None t:spec_regs=http://www.dec.ny.gov/outdoor/31504.html t:boat_launc=None t:contourmap=http://www.dec.ny.gov/docs/fish_marine_pdf/amaresmap.pdf t:ice_fishin="Ice Fishing Permitted" t:comments="NYCDEP permit required (1-800-575-LAND)" m:acres_mile=610

series e:mw8j-wduf d:2013-02-20T18:51:53.000Z t:water="Ashokan Reservoir" t:fish_speci="Brown Trout - Rainbow Trout - Smallmouth Bass" t:county=Ulster t:owner=None t:spec_regs=http://www.dec.ny.gov/outdoor/31500.html t:boat_launc=None t:contourmap=http://www.dec.ny.gov/docs/fish_marine_pdf/ashresmap.pdf t:comments="NYCDEP permit required (1-800-575-LAND)" m:acres_mile=8315

series e:mw8j-wduf d:2013-02-20T18:51:53.000Z t:water="Basic Creek Reservoir" t:fish_speci="Smallmouth Bass - Largemouth Bass - Sunfish - Yellow Perch - Crappie - Northern Pike -Walleye - Carp" t:county=Albany t:owner=None t:spec_regs=http://www.dec.ny.gov/outdoor/31479.html t:boat_launc=None t:contourmap=http://www.dec.ny.gov/docs/fish_marine_pdf/bsccrkreslkmap.pdf t:comments="Shore fishing only - City of Albany permit required (518-434-5300)" m:acres_mile=239
```

## Meta Commands

```ls
metric m:acres_mile p:integer l:Acres_Mile d:"How many acres the waterbody is." t:dataTypeName=number

entity e:mw8j-wduf l:"Recommended Fishing Lakes and Ponds" t:attribution="New York State Department of Environmental Conservation" t:url=https://data.ny.gov/api/views/mw8j-wduf

property e:mw8j-wduf t:meta.view v:id=mw8j-wduf v:category=Recreation v:attributionLink=http://www.dec.ny.gov/outdoor/7749.html v:averageRating=0 v:name="Recommended Fishing Lakes and Ponds" v:attribution="New York State Department of Environmental Conservation"

property e:mw8j-wduf t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:mw8j-wduf t:meta.view.tableauthor v:id=jtha-fqbi v:screenName="OPEN DATA NY Admin" v:roleName=publisher v:displayName="OPEN DATA NY Admin"

property e:mw8j-wduf t:meta.view.metadata.custom_fields.common_core v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| :updated_at | water                  | acres_mile | boat_launc         | owner                           | ammenities              | fish_speci                                                                                                                         | ice_fishin            | comments                                                                   | bl_weblink                                       | weblink                                          | contourmap                                                            | spec_regs                                        | county      | point_x       | point_y      | 
| =========== | ====================== | ========== | ================== | =============================== | ======================= | ================================================================================================================================== | ===================== | ========================================================================== | ================================================ | ================================================ | ===================================================================== | ================================================ | =========== | ============= | ============ | 
| 1361386313  | Amawalk Reservoir      | 610        | None               | None                            |                         | Brown Trout - Smallmouth Bass - Largemouth Bass - Crappie - Carp                                                                   | Ice Fishing Permitted | NYCDEP permit required (1-800-575-LAND)                                    | [null, null]                                     | [null, null]                                     | [http://www.dec.ny.gov/docs/fish_marine_pdf/amaresmap.pdf, null]      | [http://www.dec.ny.gov/outdoor/31504.html, null] | Westchester | -73.739604818 | 41.303340314 | 
| 1361386313  | Ashokan Reservoir      | 8315       | None               | None                            |                         | Brown Trout - Rainbow Trout - Smallmouth Bass                                                                                      |                       | NYCDEP permit required (1-800-575-LAND)                                    | [null, null]                                     | [null, null]                                     | [http://www.dec.ny.gov/docs/fish_marine_pdf/ashresmap.pdf, null]      | [http://www.dec.ny.gov/outdoor/31500.html, null] | Ulster      | -74.186644484 | 41.963301654 | 
| 1361386313  | Basic Creek Reservoir  | 239        | None               | None                            |                         | Smallmouth Bass - Largemouth Bass - Sunfish - Yellow Perch - Crappie - Northern Pike -Walleye - Carp                               |                       | Shore fishing only - City of Albany permit required (518-434-5300)         | [null, null]                                     | [null, null]                                     | [http://www.dec.ny.gov/docs/fish_marine_pdf/bsccrkreslkmap.pdf, null] | [http://www.dec.ny.gov/outdoor/31479.html, null] | Albany      | -74.016267601 | 42.483972536 | 
| 1361386313  | Big Pond               | 51         | Hand Launch        | DEC                             | Campsite                | Brown Trout - Rainbow Trout - Smallmouth Bass - Largemouth Bass - Sunfish - Yellow Perch - Chain Pickerel                          | Ice Fishing Permitted | Site includes accessible features                                          | [null, null]                                     | [null, null]                                     | [http://www.dec.ny.gov/docs/fish_marine_pdf/bigpdlkmap.pdf, null]     | [http://www.dec.ny.gov/outdoor/31440.html, null] | Delaware    | -74.723860035 | 42.046838384 | 
| 1361386313  | Bog Brook Reservoir    | 410        | None               | None                            |                         | Brown Trout - Smallmouth Bass - Largemouth Bass - Yellow Perch - Walleye - Carp                                                    | Ice Fishing Permitted | NYCDEP permit required (1-800-575-LAND)                                    | [null, null]                                     | [null, null]                                     | [http://www.dec.ny.gov/docs/fish_marine_pdf/bogresmap.pdf, null]      | [http://www.dec.ny.gov/outdoor/31478.html, null] | Putnam      | -73.585544633 | 41.415831946 | 
| 1361386313  | Boyd Corners Reservoir | 214        | None               | None                            |                         | Largemouth Bass - Walleye                                                                                                          | Ice Fishing Permitted | NYCDEP permit required (1-800-575-LAND)                                    | [null, null]                                     | [http://www.dec.ny.gov/outdoor/68037.html, null] | [http://www.dec.ny.gov/docs/fish_marine_pdf/bydresmap.pdf, null]      | [http://www.dec.ny.gov/outdoor/31478.html, null] | Putnam      | -73.750140815 | 41.459037607 | 
| 1361386313  | Burden Lake            | 366        | Hand Launch        | Municipal                       |                         | Smallmouth Bass - Largemouth Bass - Sunfish - Yellow Perch - Crappie - Chain Pickerel - Carp                                       | Ice Fishing Permitted |                                                                            | [null, null]                                     | [null, null]                                     | [http://www.dec.ny.gov/docs/fish_marine_pdf/burlkmap.pdf, null]       | [null, null]                                     | Rensselear  | -73.561435787 | 42.602095835 | 
| 1361386313  | Canadarago Lake        | 1894       | Trailer Improved   | OPRHP (State Parks) - Municipal | Fishing Pier            | Brown Trout - Smallmouth Bass - Largemouth Bass - Sunfish - Yellow Perch - Crappie - Tiger Musky - Chain Pickerel - Walleye - Carp | Ice Fishing Permitted | OPRHP permit required (Central Region 315-492-1756)                        | [http://www.dec.ny.gov/outdoor/23876.html, null] | [null, null]                                     | [http://www.dec.ny.gov/docs/fish_marine_pdf/canlkmap.pdf, null]       | [http://www.dec.ny.gov/outdoor/31477.html, null] | Otsego      | -75.002993321 | 42.817958147 | 
| 1361386313  | Cannonsville Reservoir | 4800       | None               | None                            |                         | Brown Trout - Smallmouth Bass - Yellow Perch - Crappie - Chain Pickerel - Carp                                                     |                       | NYCDEP permit required (1-800-575-LAND)                                    | [null, null]                                     | [null, null]                                     | [http://www.dec.ny.gov/docs/fish_marine_pdf/cnnresmap.pdf, null]      | [http://www.dec.ny.gov/outdoor/31440.html, null] | Delaware    | -75.318158349 | 42.088851062 | 
| 1361386313  | Canopus Lake           | 100        | Trailer Unimproved | OPRHP (State Parks)             | Boat Rental - Campsites | Largemouth Bass - Chain Pickerel                                                                                                   | Ice Fishing Permitted | Electric motors only - OPRHP permit required (Taconic Region 845-889-4100) | [http://www.dec.ny.gov/outdoor/23875.html, null] | [http://www.dec.ny.gov/outdoor/68032.html, null] | [http://www.dec.ny.gov/docs/fish_marine_pdf/canplkmap.pdf, null]      | [null, null]                                     | Putnam      | -73.832684936 | 41.462142964 | 
```