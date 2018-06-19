# Local Data Index

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/local-data-index) |
| Metadata | [Link](https://data.ny.gov/api/views/mxu7-dpdx) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/mxu7-dpdx/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/mxu7-dpdx/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | mxu7-dpdx |
| Name | Local Data Index |
| Attribution | Office of Information Technology Services |
| Category | Government & Finance |
| Tags | county, municipality, local |
| Created | 2016-01-07T17:24:54Z |
| Publication Date | 2017-04-17T10:22:39Z |

## Description

Discover the breadth of data collected by the state which is local in nature. Search by county and municipality and discover, explore, and download local data.  With a click, find local data across a broad range of categories from health to transportation, from recreation to economic development; find local farmer?s markets, child care regulated facilities, craft beverages, solar installations, food service establishment inspections, and much more.

## Columns

```ls
| Included | Schema Type    | Field Name   | Name                | Data Type | Render Type |
| ======== | ============== | ============ | =================== | ========= | =========== |
| No       | time           | :updated_at  | updated_at          | meta_data | meta_data   |
| Yes      | series tag     | name         | Dataset Name        | text      | text        |
| Yes      | series tag     | url          | URL                 | url       | url         |
| Yes      | series tag     | agency       | Agency              | text      | text        |
| Yes      | series tag     | category     | Category            | text      | text        |
| Yes      | series tag     | granularity  | Granularity         | text      | text        |
| Yes      | series tag     | filter_value | County/Municipality | text      | text        |
| Yes      | numeric metric | rows         | # Rows              | number    | number      |
| No       |                | latitude     | Latitude            | number    | number      |
| No       |                | longitude    | Longitude           | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = latitude,longitude
```

## Data Commands

```ls
series e:mxu7-dpdx d:2017-04-17T10:21:51.000Z t:category="Economic Development" t:granularity=County t:name="State of New York Mortgage Agency (SONYMA) Loans Purchased: Beginning 2004" t:agency="Homes and Community Renewal" t:url=http://data.ny.gov/d/22ew-dxez t:filter_value=HAMILTON m:rows=3

series e:mxu7-dpdx d:2017-04-17T10:21:51.000Z t:category="Economic Development" t:granularity=County t:name="State of New York Mortgage Agency (SONYMA) Loans Purchased: Beginning 2004" t:agency="Homes and Community Renewal" t:url=http://data.ny.gov/d/22ew-dxez t:filter_value=YATES m:rows=19

series e:mxu7-dpdx d:2017-04-17T10:21:51.000Z t:category="Economic Development" t:granularity=County t:name="State of New York Mortgage Agency (SONYMA) Loans Purchased: Beginning 2004" t:agency="Homes and Community Renewal" t:url=http://data.ny.gov/d/22ew-dxez t:filter_value=LEWIS m:rows=7
```

## Meta Commands

```ls
metric m:rows p:integer l:"# Rows" d:"Number of dataset rows having the specific county or municipality name" t:dataTypeName=number

entity e:mxu7-dpdx l:"Local Data Index" t:attribution="Office of Information Technology Services" t:url=https://data.ny.gov/api/views/mxu7-dpdx

property e:mxu7-dpdx t:meta.view v:id=mxu7-dpdx v:category="Government & Finance" v:attributionLink=https://data.ny.gov v:averageRating=0 v:name="Local Data Index" v:attribution="Office of Information Technology Services"

property e:mxu7-dpdx t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:mxu7-dpdx t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"
```

## Top Records

```ls
| :updated_at | name                                                                       | url                                    | agency                      | category             | granularity | filter_value | rows | latitude   | longitude   | 
| =========== | ========================================================================== | ====================================== | =========================== | ==================== | =========== | ============ | ==== | ========== | =========== | 
| 1492424511  | State of New York Mortgage Agency (SONYMA) Loans Purchased: Beginning 2004 | [http://data.ny.gov/d/22ew-dxez, null] | Homes and Community Renewal | Economic Development | County      | HAMILTON     | 3    | 43.6611216 | -74.4973553 | 
| 1492424511  | State of New York Mortgage Agency (SONYMA) Loans Purchased: Beginning 2004 | [http://data.ny.gov/d/22ew-dxez, null] | Homes and Community Renewal | Economic Development | County      | YATES        | 19   | 42.6334424 | -77.1054589 | 
| 1492424511  | State of New York Mortgage Agency (SONYMA) Loans Purchased: Beginning 2004 | [http://data.ny.gov/d/22ew-dxez, null] | Homes and Community Renewal | Economic Development | County      | LEWIS        | 7    | 43.7846915 | -75.4487945 | 
| 1492424511  | State of New York Mortgage Agency (SONYMA) Loans Purchased: Beginning 2004 | [http://data.ny.gov/d/22ew-dxez, null] | Homes and Community Renewal | Economic Development | County      | JEFFERSON    | 29   | 43.9988484 | -76.0521081 | 
| 1492424511  | State of New York Mortgage Agency (SONYMA) Loans Purchased: Beginning 2004 | [http://data.ny.gov/d/22ew-dxez, null] | Homes and Community Renewal | Economic Development | County      | MADISON      | 70   | 42.9127746 | -75.6696659 | 
| 1492424511  | State of New York Mortgage Agency (SONYMA) Loans Purchased: Beginning 2004 | [http://data.ny.gov/d/22ew-dxez, null] | Homes and Community Renewal | Economic Development | County      | ESSEX        | 36   | 44.1172179 | -73.7727091 | 
| 1492424511  | State of New York Mortgage Agency (SONYMA) Loans Purchased: Beginning 2004 | [http://data.ny.gov/d/22ew-dxez, null] | Homes and Community Renewal | Economic Development | County      | CLINTON      | 155  | 44.7462266 | -73.6781745 | 
| 1492424511  | State of New York Mortgage Agency (SONYMA) Loans Purchased: Beginning 2004 | [http://data.ny.gov/d/22ew-dxez, null] | Homes and Community Renewal | Economic Development | County      | WASHINGTON   | 53   | 43.3137032 | -73.4307589 | 
| 1492424511  | State of New York Mortgage Agency (SONYMA) Loans Purchased: Beginning 2004 | [http://data.ny.gov/d/22ew-dxez, null] | Homes and Community Renewal | Economic Development | County      | FRANKLIN     | 44   | 44.5929338 | -74.3037624 | 
| 1492424511  | State of New York Mortgage Agency (SONYMA) Loans Purchased: Beginning 2004 | [http://data.ny.gov/d/22ew-dxez, null] | Homes and Community Renewal | Economic Development | County      | OSWEGO       | 97   | 43.4638857 | -76.2086833 | 
```