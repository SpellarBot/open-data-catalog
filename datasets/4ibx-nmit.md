# Five-Year Program: 2018 Structures

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/five-year-program-2018-structures) |
| Metadata | [Link](https://data.iowa.gov/api/views/4ibx-nmit) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/4ibx-nmit/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/4ibx-nmit/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | 4ibx-nmit |
| Name | Five-Year Program: 2018 Structures |
| Attribution | Iowa Department of Transportation - Office of Program Management |
| Category | Transportation & Utilities |
| Tags | asset, improvement, five year plan, program management, planning, iowa dot, iowa department of transportation |
| Created | 2016-06-15T19:50:57Z |
| Publication Date | 2016-06-15T19:51:47Z |

## Description

FY 2018 Iowa Highway Five Year Improvement Program with amendments for structures only. Created in June 2016.

## Columns

```ls
| Included | Schema Type    | Field Name | Name      | Data Type | Render Type |
| ======== | ============== | ========== | ========= | ========= | =========== |
| Yes      | series tag     | objectid   | OBJECTID  | text      | number      |
| Yes      | series tag     | pin        | PIN       | text      | text        |
| Yes      | numeric metric | county     | COUNTY    | number    | number      |
| Yes      | series tag     | route      | ROUTE     | text      | number      |
| Yes      | series tag     | district   | DISTRICT  | text      | number      |
| Yes      | series tag     | region     | REGION    | text      | number      |
| Yes      | series tag     | work_type  | WORK_TYPE | text      | text        |
| Yes      | time           | year       | YEAR      | number    | number      |
| Yes      | numeric metric | cost       | COST      | number    | number      |
| Yes      | series tag     | location   | LOCATION  | text      | text        |
| Yes      | series tag     | worktype   | WORKTYPE  | text      | number      |
| Yes      | series tag     | workclass  | WORKCLASS | text      | text        |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:4ibx-nmit d:2018-01-01T00:00:00.000Z t:region=26 t:location="IN ANKENY FROM N OF ORALABOR RD TO NE 36TH ST" t:pin=0477035030 t:route=35 t:work_type=Mitigation t:worktype=4551 t:district=1 t:objectid=7 t:workclass=Modernize m:county=77 m:cost=250

series e:4ibx-nmit d:2018-01-01T00:00:00.000Z t:region=26 t:location="IN ANKENY FROM N OF ORALABOR RD TO NE 36TH ST" t:pin=0477035030 t:route=35 t:work_type="Bridge Widening" t:worktype=2512 t:district=1 t:objectid=8 t:workclass=Modernize m:county=77 m:cost=883

series e:4ibx-nmit d:2018-01-01T00:00:00.000Z t:region=26 t:location="IN ANKENY FROM N OF ORALABOR RD TO NE 36TH ST" t:pin=0477035030 t:route=35 t:work_type="Culvert New" t:worktype=3011 t:district=1 t:objectid=9 t:workclass=Modernize m:county=77 m:cost=350
```

## Meta Commands

```ls
metric m:county p:integer l:COUNTY d:County t:dataTypeName=number

metric m:cost p:integer l:COST d:"Cost ($K)" t:dataTypeName=number

entity e:4ibx-nmit l:"Five-Year Program: 2018 Structures" t:attribution="Iowa Department of Transportation - Office of Program Management" t:url=https://data.iowa.gov/api/views/4ibx-nmit

property e:4ibx-nmit t:meta.view v:id=4ibx-nmit v:category="Transportation & Utilities" v:averageRating=0 v:name="Five-Year Program: 2018 Structures" v:attribution="Iowa Department of Transportation - Office of Program Management"

property e:4ibx-nmit t:meta.view.owner v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:displayName="Iowa Department of Transportation"

property e:4ibx-nmit t:meta.view.tableauthor v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:roleName=administrator v:displayName="Iowa Department of Transportation"
```

## Top Records

```ls
| objectid | pin        | county | route | district | region | work_type           | year | cost  | location                                           | worktype | workclass | 
| ======== | ========== | ====== | ===== | ======== | ====== | =================== | ==== | ===== | ================================================== | ======== | ========= | 
| 7        | 0477035030 | 77     | 35    | 1        | 26     | Mitigation          | 2018 | 250   | IN ANKENY FROM N OF ORALABOR RD TO NE 36TH ST      | 4551     | Modernize | 
| 8        | 0477035030 | 77     | 35    | 1        | 26     | Bridge Widening     | 2018 | 883   | IN ANKENY FROM N OF ORALABOR RD TO NE 36TH ST      | 2512     | Modernize | 
| 9        | 0477035030 | 77     | 35    | 1        | 26     | Culvert New         | 2018 | 350   | IN ANKENY FROM N OF ORALABOR RD TO NE 36TH ST      | 3011     | Modernize | 
| 18       | 0882074010 | 82     | 74    | 6        | 25     | Bridge Replacement  | 2018 | 53575 | IN BETTENDORF AND DAVENPORT (CENTRAL SECTION)      | 2021     | Rebuild   | 
| 28       | 1311003010 | 11     | 3     | 3        | 3      | Bridge Replacement  | 2018 | 484   | DITCH 3.3 MI E OF US 71                            | 2021     | Rebuild   | 
| 29       | 1311003020 | 11     | 3     | 3        | 3      | Bridge Replacement  | 2018 | 1366  | NORTH RACCOON RIVER 2.5 MI E OF US 71              | 2021     | Rebuild   | 
| 30       | 1315006010 | 15     | 6     | 4        | 13     | Bridge Deck Overlay | 2018 | 910   | EAST NISHNABOTNA RIVER 2.3 MI S OF I-80            | 2521     | Preserve  | 
| 31       | 1317065010 | 17     | 65    | 2        | 2      | Bridge Deck Overlay | 2018 | 430   | WILLOW CREEK 0.1 MI N OF IA 122 IN MASON CITY (SB) | 2521     | Preserve  | 
| 35       | 1322018020 | 22     | 18    | 2        | 1      | Bridge Deck Overlay | 2018 | 2500  | MISSISSIPPI RIVER IN MARQUETTE (STATE SHARE)       | 2521     | Preserve  | 
| 39       | 1344218010 | 44     | 218   | 5        | 16     | Bridge Replacement  | 2018 | 4072  | SKUNK RIVER 4.7 MI S OF S JCT US 34 (NB)           | 2021     | Rebuild   | 
```