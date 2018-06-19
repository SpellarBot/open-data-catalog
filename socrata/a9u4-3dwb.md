# CDPH Environmental Records Lookup Table

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cdph-environmental-records-lookup-table) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/a9u4-3dwb) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/a9u4-3dwb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/a9u4-3dwb/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | a9u4-3dwb |
| Name | CDPH Environmental Records Lookup Table |
| Category | Environment & Sustainable Development |
| Created | 2012-10-10T18:22:22Z |
| Publication Date | 2017-04-19T13:45:45Z |

## Description

This dataset serves as a lookup table to determine if environmental records exist in a Chicago Department of Public Health (CDPH) environmental dataset for a given address.   
Data fields requiring description are detailed below. 
MAPPED LOCATION: Contains the address, city, state and latitude/longitude coordinates of the facility. In instances where the facility address is a range, the lower number (the value in the ?Street Number From? column) is used. For example, for the range address 1000-1005 S Wabash Ave, the Mapped Location would be 1000 S Wabash Ave. The latitude/longitude coordinate is determined through the Chicago Open Data Portal?s geocoding process.  Addresses that fail to geocode are assigned the coordinates 41.88415000022252?, -87.63241000012124?.This coordinate is located approximately just south of the intersection of W Randolph and N LaSalle.
COMPLAINTS:  A ?Y? indicates that one or more records exist in the CDPH Environmental Complaints dataset. 
NESHAPS & DEMOLITON NOTICES:  A ?Y? indicates that one or more records exist in the CDPH Asbestos and Demolition Notification dataset. 
ENFORCEMENT:  A ?Y? indicates that one or more records exist in the CDPH Environmental Enforcement dataset. 
INSPECTIONS:  A ?Y? indicates that one or more records exist in the CDPH Environmental Inspections dataset. 
PERMITS:  A ?Y? indicates that one or more records exist in the CDPH Environmental Permits dataset. 
TANKS:  A ?Y? indicates that one or more records exist in the CDPH Storage Tanks dataset.  Each 'Y' is a clickable link that will download the corresponding records in CSV format.

## Columns

```ls
| Included | Schema Type | Field Name                 | Name                         | Data Type | Render Type |
| ======== | =========== | ========================== | ============================ | ========= | =========== |
| No       | time        | :updated_at                | updated_at                   | meta_data | meta_data   |
| Yes      | series tag  | street_number              | STREET NUMBER FROM           | text      | number      |
| Yes      | series tag  | direction                  | DIRECTION                    | text      | text        |
| Yes      | series tag  | street_name                | STREET NAME                  | text      | text        |
| Yes      | series tag  | street_type                | STREET TYPE                  | text      | text        |
| Yes      | series tag  | complaints                 | COMPLAINTS                   | url       | url         |
| Yes      | series tag  | neshaps_demolition_notices | NESHAPS & DEMOLITION NOTICES | url       | url         |
| Yes      | series tag  | enforcement                | ENFORCEMENT                  | url       | url         |
| Yes      | series tag  | inspections                | INSPECTIONS                  | url       | url         |
| Yes      | series tag  | permits                    | PERMITS                      | url       | url         |
| Yes      | series tag  | tanks                      | TANKS                        | url       | url         |
| Yes      | series tag  | holds                      | HOLDS & LUST NFR             | url       | url         |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:a9u4-3dwb d:2017-04-19T11:30:37.000Z t:direction=DIRECTION t:street_name="STREET NAME" t:street_type="STREET TYPE" m:row_number.a9u4-3dwb=1

series e:a9u4-3dwb d:2017-04-19T12:07:41.000Z t:direction=S t:street_name=EGGLESTON t:neshaps_demolition_notices="https://data.cityofchicago.org/resource/qhb4-qx8k.csv?street_number=11936%20and%20direction=%27S%27%20and%20street_name=%27EGGLESTON%27%20and%20street_type=%27AVE%27" t:street_number=11936 t:street_type=AVE m:row_number.a9u4-3dwb=2

series e:a9u4-3dwb d:2017-04-19T12:07:41.000Z t:direction=E t:street_name=72ND t:neshaps_demolition_notices="https://data.cityofchicago.org/resource/qhb4-qx8k.csv?street_number=1428%20and%20direction=%27E%27%20and%20street_name=%2772ND%27%20and%20street_type=%27ST%27" t:street_number=1428 t:street_type=ST m:row_number.a9u4-3dwb=3
```

## Meta Commands

```ls
metric m:row_number.a9u4-3dwb p:long l:"Row Number"

entity e:a9u4-3dwb l:"CDPH Environmental Records Lookup Table" t:url=https://data.cityofchicago.org/api/views/a9u4-3dwb

property e:a9u4-3dwb t:meta.view v:id=a9u4-3dwb v:category="Environment & Sustainable Development" v:averageRating=0 v:name="CDPH Environmental Records Lookup Table"

property e:a9u4-3dwb t:meta.view.owner v:id=e3v2-km8a v:screenName=Renante v:displayName=Renante

property e:a9u4-3dwb t:meta.view.tableauthor v:id=e3v2-km8a v:screenName=Renante v:roleName=publisher v:displayName=Renante
```

## Top Records

```ls
| :updated_at | street_number | direction | street_name | street_type | complaints                                                                                                                                                            | neshaps_demolition_notices                                                                                                                                                 | enforcement  | inspections                                                                                                                                                            | permits                                                                                                                                                                  | tanks        | holds        | 
| =========== | ============= | ========= | =========== | =========== | ===================================================================================================================================================================== | ========================================================================================================================================================================== | ============ | ====================================================================================================================================================================== | ======================================================================================================================================================================== | ============ | ============ | 
| 1492601437  |               | DIRECTION | STREET NAME | STREET TYPE | [null, null]                                                                                                                                                          | [null, null]                                                                                                                                                               | [null, null] | [null, null]                                                                                                                                                           | [null, null]                                                                                                                                                             | [null, null] | [null, null] | 
| 1492603661  | 11936         | S         | EGGLESTON   | AVE         | [null, null]                                                                                                                                                          | [https://data.cityofchicago.org/resource/qhb4-qx8k.csv?street_number=11936%20and%20direction=%27S%27%20and%20street_name=%27EGGLESTON%27%20and%20street_type=%27AVE%27, Y] | [null, null] | [null, null]                                                                                                                                                           | [null, null]                                                                                                                                                             | [null, null] | [null, null] | 
| 1492603661  | 1428          | E         | 72ND        | ST          | [null, null]                                                                                                                                                          | [https://data.cityofchicago.org/resource/qhb4-qx8k.csv?street_number=1428%20and%20direction=%27E%27%20and%20street_name=%2772ND%27%20and%20street_type=%27ST%27, Y]        | [null, null] | [null, null]                                                                                                                                                           | [null, null]                                                                                                                                                             | [null, null] | [null, null] | 
| 1492603661  | 1215          | W         | 69TH        | ST          | [null, null]                                                                                                                                                          | [https://data.cityofchicago.org/resource/qhb4-qx8k.csv?street_number=1215%20and%20direction=%27W%27%20and%20street_name=%2769TH%27%20and%20street_type=%27ST%27, Y]        | [null, null] | [null, null]                                                                                                                                                           | [null, null]                                                                                                                                                             | [null, null] | [null, null] | 
| 1492603661  | 13002         | S         | INDIANA     | AVE         | [null, null]                                                                                                                                                          | [null, null]                                                                                                                                                               | [null, null] | [null, null]                                                                                                                                                           | [https://data.cityofchicago.org/resource/ir7v-8mc8.csv?street_number=13002%20and%20direction=%27S%27%20and%20street_name=%27INDIANA%27%20and%20street_type=%27AVE%27, Y] | [null, null] | [null, null] | 
| 1492603661  | 1156          | W         | 95TH        | ST          | [null, null]                                                                                                                                                          | [null, null]                                                                                                                                                               | [null, null] | [https://data.cityofchicago.org/resource/i9rk-duva.csv?street_number=1156%20and%20direction=%27W%27%20and%20street_name=%2795TH%27%20and%20street_type=%27ST%27, Y]    | [null, null]                                                                                                                                                             | [null, null] | [null, null] | 
| 1492603662  | 1354          | S         | MORGAN      | ST          | [null, null]                                                                                                                                                          | [null, null]                                                                                                                                                               | [null, null] | [https://data.cityofchicago.org/resource/i9rk-duva.csv?street_number=1354%20and%20direction=%27S%27%20and%20street_name=%27MORGAN%27%20and%20street_type=%27ST%27, Y]  | [null, null]                                                                                                                                                             | [null, null] | [null, null] | 
| 1492601437  | 1             | S         | FINANCIAL   | PL          | [https://data.cityofchicago.org/resource/fypr-ksnz.csv?street_number=1%20and%20direction=%27S%27%20and%20street_name=%27FINANCIAL%27%20and%20street_type=%27PL%27, Y] | [null, null]                                                                                                                                                               | [null, null] | [null, null]                                                                                                                                                           | [null, null]                                                                                                                                                             | [null, null] | [null, null] | 
| 1492603662  | 1236          | S         | HALSTED     | ST          | [null, null]                                                                                                                                                          | [https://data.cityofchicago.org/resource/qhb4-qx8k.csv?street_number=1236%20and%20direction=%27S%27%20and%20street_name=%27HALSTED%27%20and%20street_type=%27ST%27, Y]     | [null, null] | [https://data.cityofchicago.org/resource/i9rk-duva.csv?street_number=1236%20and%20direction=%27S%27%20and%20street_name=%27HALSTED%27%20and%20street_type=%27ST%27, Y] | [null, null]                                                                                                                                                             | [null, null] | [null, null] | 
| 1492603662  | 1210          | W         | GRAND       | AVE         | [https://data.cityofchicago.org/resource/fypr-ksnz.csv?street_number=1210%20and%20direction=%27W%27%20and%20street_name=%27GRAND%27%20and%20street_type=%27AVE%27, Y] | [null, null]                                                                                                                                                               | [null, null] | [null, null]                                                                                                                                                           | [null, null]                                                                                                                                                             | [null, null] | [null, null] | 
```