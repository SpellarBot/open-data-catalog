# New York State Government Building Energy Use Intensity Data: Beginning State Fiscal Year 2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/new-york-state-government-building-energy-use-intensity-data-beginning-state-fiscal-year-2) |
| Metadata | [Link](https://data.ny.gov/api/views/nfvi-5nt4) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/nfvi-5nt4/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/nfvi-5nt4/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | nfvi-5nt4 |
| Name | New York State Government Building Energy Use Intensity Data: Beginning State Fiscal Year 2010 |
| Attribution | New York Power Authority |
| Category | Energy & Environment |
| Tags | energy efficiency, new york state building data, buildsmart ny, executive order 88 |
| Created | 2014-10-06T18:31:54Z |
| Publication Date | 2017-01-17T19:57:07Z |

## Description

The Build Smart NY Program aims to increase energy efficiency of New York State government buildings. Build Smart NY was established by Executive Order 88 and mandates a reduction in energy consumption by 20% in government owned and operated buildings by 2020. Site utility data has been collected for all government buildings larger than 20,000 square feet and this has been converted to Source Energy Use Intensity (EUI) which is a ratio of Source Energy Use to gross square footage.  The Source EUI will be used as a performance metric to achieve the 20% reduction targets. The dataset represents a baseline of Source EUI for New York State government buildings at the baseline year of SFI 2010/2011; subsequent reports will demonstrate a progression to achieving a 20% energy reduction target.

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                   | Data Type | Render Type |
| ======== | ============== | ====================== | ====================== | ========= | =========== |
| Yes      | series tag     | agency_name            | Agency Name            | text      | text        |
| Yes      | series tag     | building_facility_name | Building/Facility Name | text      | text        |
| Yes      | series tag     | zip_code               | ZIP Code               | text      | text        |
| Yes      | time           | year                   | Year                   | text      | text        |
| Yes      | numeric metric | gross_floor_area       | Gross Floor Area       | number    | number      |
| Yes      | numeric metric | source_kbtu            | Source kBtu            | number    | number      |
| Yes      | numeric metric | source_eui             | Source EUI             | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy-MM
```

## Data Commands

```ls
series e:nfvi-5nt4 d:2010-11-01T00:00:00.000Z t:zip_code=12977 t:building_facility_name="Adirondack Park Agency Office" t:agency_name="Adirondack Park Agency" m:source_kbtu=2958380 m:gross_floor_area=22000 m:source_eui=134

series e:nfvi-5nt4 d:2010-11-01T00:00:00.000Z t:zip_code=13209 t:building_facility_name="NY State Fair" t:agency_name="Agriculture and Markets" m:source_kbtu=84508330 m:gross_floor_area=663300 m:source_eui=127

series e:nfvi-5nt4 d:2010-11-01T00:00:00.000Z t:zip_code=10010 t:building_facility_name="Baruch College Campus" t:agency_name=CUNY m:source_kbtu=383849490 m:gross_floor_area=1572632 m:source_eui=244
```

## Meta Commands

```ls
metric m:gross_floor_area p:integer l:"Gross Floor Area" d:"The gross square footage-the sum of all areas on all floors of a building included within the outside faces of its exterior walls, including all vertical penetration areas for circulation and shaft areas that connect one floor to another." t:dataTypeName=number

metric m:source_kbtu p:long l:"Source kBtu" d:"The total kBtu site is converted to Source Energy which takes into account the fuels consumed in the generation, transmission, and distribution of electricity, as well as the energy losses from storage, distribution, and delivery of each unit fuel." t:dataTypeName=number

metric m:source_eui p:double l:"Source EUI" d:"The Source kBtu divided by the gross square footage generates the Energy Use Intensity-which is the standard performance metric used to measure Executive Order 88 goals." t:dataTypeName=number

entity e:nfvi-5nt4 l:"New York State Government Building Energy Use Intensity Data: Beginning State Fiscal Year 2010" t:attribution="New York Power Authority" t:url=https://data.ny.gov/api/views/nfvi-5nt4

property e:nfvi-5nt4 t:meta.view v:id=nfvi-5nt4 v:category="Energy & Environment" v:attributionLink=http://www.buildsmart.ny.gov/ v:averageRating=0 v:name="New York State Government Building Energy Use Intensity Data: Beginning State Fiscal Year 2010" v:attribution="New York Power Authority"

property e:nfvi-5nt4 t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:nfvi-5nt4 t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:nfvi-5nt4 t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| agency_name             | building_facility_name          | zip_code | year    | gross_floor_area | source_kbtu | source_eui | 
| ======================= | =============================== | ======== | ======= | ================ | =========== | ========== | 
| Adirondack Park Agency  | Adirondack Park Agency Office   | 12977    | 2010-11 | 22000            | 2958380     | 134        | 
| Agriculture and Markets | NY State Fair                   | 13209    | 2010-11 | 663300           | 84508330    | 127        | 
| CUNY                    | Baruch College Campus           | 10010    | 2010-11 | 1572632          | 383849490   | 244        | 
| CUNY                    | Brooklyn College Campus         | 11210    | 2010-11 | 2404930          | 786802490   | 327        | 
| CUNY                    | Central Office Campus           | 10075    | 2010-11 | 99594            | 61158590    | 614        | 
| CUNY                    | City College Of New York Campus | 10031    | 2010-11 | 2959867          | 899150690   | 304        | 
| CUNY                    | City Tech College Campus        | 11201    | 2010-11 | 1098248          | 245774100   | 224        | 
| CUNY                    | College Of Staten Island Campus | 10314    | 2010-11 | 1354984          | 416209300   | 307        | 
| CUNY                    | Graduate Center                 | 10016    | 2010-11 | 680546           | 146248920   | 215        | 
| CUNY                    | Honors College                  | 10023    | 2010-11 | 24096            | 7350300     | 305        | 
```