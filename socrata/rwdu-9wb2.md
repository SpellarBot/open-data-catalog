# Police Stations (2011)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/police-stations-2011) |
| Metadata | [Link](https://data.sfgov.org/api/views/rwdu-9wb2) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/rwdu-9wb2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/rwdu-9wb2/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | rwdu-9wb2 |
| Name | Police Stations (2011) |
| Category | Public Safety |
| Created | 2016-07-17T20:24:15Z |
| Publication Date | 2016-07-17T20:26:17Z |

## Description

San Francisco Police Stations. As of 2011. Does not reflect recent redistricting.

## Columns

```ls
| Included | Schema Type | Field Name       | Name             | Data Type | Render Type |
| ======== | =========== | ================ | ================ | ========= | =========== |
| Yes      | series tag  | company_name     | Company Name     | text      | text        |
| Yes      | series tag  | district_name    | District Name    | text      | text        |
| No       |             | address          | Address          | text      | text        |
| Yes      | series tag  | telephone_number | Telephone Number | text      | text        |
```

## Time Field

```ls
Value = 2011
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = address
```

## Data Commands

```ls
series e:rwdu-9wb2 d:2011-01-01T00:00:00.000Z t:telephone_number=415-315-2400 t:district_name="CENTRAL STN" t:company_name=A m:row_number.rwdu-9wb2=1

series e:rwdu-9wb2 d:2011-01-01T00:00:00.000Z t:telephone_number=415-553-1373 t:district_name="SOUTHERN STN" t:company_name=B m:row_number.rwdu-9wb2=2

series e:rwdu-9wb2 d:2011-01-01T00:00:00.000Z t:telephone_number=415-671-2300 t:district_name="BAYVIEW STN" t:company_name=C m:row_number.rwdu-9wb2=3
```

## Meta Commands

```ls
metric m:row_number.rwdu-9wb2 p:long l:"Row Number"

entity e:rwdu-9wb2 l:"Police Stations (2011)" t:url=https://data.sfgov.org/api/views/rwdu-9wb2

property e:rwdu-9wb2 t:meta.view v:id=rwdu-9wb2 v:category="Public Safety" v:averageRating=0 v:name="Police Stations (2011)"

property e:rwdu-9wb2 t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:rwdu-9wb2 t:meta.view.owner v:id=dbag-6qd9 v:screenName=OpenData v:displayName=OpenData

property e:rwdu-9wb2 t:meta.view.tableauthor v:id=dbag-6qd9 v:screenName=OpenData v:roleName=publisher v:displayName=OpenData
```

## Top Records

```ls
| company_name | district_name  | address          | telephone_number | 
| ============ | ============== | ================ | ================ | 
| A            | CENTRAL STN    | 766 VALLEJO ST   | 415-315-2400     | 
| B            | SOUTHERN STN   | 850 BRYANT ST    | 415-553-1373     | 
| C            | BAYVIEW STN    | 201 WILLIAMS ST  | 415-671-2300     | 
| D            | MISSION STN    | 630 VALLENCIA ST | 415-558-5400     | 
| E            | NORTHERN STN   | 1125 FILLMORE ST | 415-614-3400     | 
| F            | PARK STN       | 1899 WALLER ST   | 415-242-3000     | 
| G            | RICHMOND STN   | 461 6TH AV       | 415-666-8000     | 
| H            | INGLESIDE STN  | 1 JOHN YOUNG LN  | 415-404-4000     | 
| I            | TARAVAL STN    | 2345 24TH AV     | 415-759-3100     | 
| J            | TENDERLOIN STN | 301 EDDY ST      | 415-345-7300     | 
```