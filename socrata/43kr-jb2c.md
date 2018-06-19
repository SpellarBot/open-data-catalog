# State of New York Mortgage Agency (SONYMA) Target Areas by Census Tract

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/state-of-new-york-mortgage-agency-sonyma-target-areas-by-census-tract) |
| Metadata | [Link](https://data.ny.gov/api/views/43kr-jb2c) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/43kr-jb2c/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/43kr-jb2c/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | 43kr-jb2c |
| Name | State of New York Mortgage Agency (SONYMA) Target Areas by Census Tract |
| Attribution | NYS Homes & Community Renewal |
| Category | Economic Development |
| Tags | mortgage, fha, hfa, single family, capital program, housing plan |
| Created | 2016-06-17T12:58:08Z |
| Publication Date | 2016-06-20T20:10:06Z |

## Description

Listing of SONYMA target areas by US Census Bureau Census Tract or Block Numbering Area (BNA).
The State of New York Mortgage Agency (SONYMA) targets specific areas designated as ?areas of chronic economic distress? for its homeownership lending programs. Each state designates ?areas of chronic economic distress? with the approval of the US Secretary of Housing and Urban Development (HUD). SONYMA identifies its target areas using US Census Bureau census tracts and block numbering areas. Both census tracts and block numbering areas subdivide individual counties. SONYMA also relates each of its single-family mortgages to a specific census tract or block numbering area.
New York State identifies ?areas of chronic economic distress? using census tract numbers. 26 US Code ? 143 (current through Pub. L. 114-38) defines the criteria that the Secretary of Housing and Urban Development uses in approving designations of ?areas of chronic economic distress? as: i) the condition of the housing stock, including the age of the housing and the number of abandoned and substandard residential units, (ii) the need of area residents for owner-financing under this section, as indicated by low per capita income, a high percentage of families in poverty, a high number of welfare recipients, and high unemployment rates, (iii) the potential for use of owner-financing under this section to improve housing conditions in the area, and (iv) the existence of a housing assistance plan which provides a displacement program and a public improvements and services program.
The US Census Bureau?s decennial census last took place in 2010 and will take place again in 2020. While the state designates ?areas of chronic economic distress,? the US Department of Housing and Urban Development must approve the designation. The designation takes place after the decennial census.

## Columns

```ls
| Included | Schema Type    | Field Name  | Name                | Data Type | Render Type |
| ======== | ============== | =========== | =================== | ========= | =========== |
| No       | time           | :updated_at | updated_at          | meta_data | meta_data   |
| Yes      | series tag     | county      | County              | text      | text        |
| Yes      | series tag     | fips        | FIPS                | text      | number      |
| Yes      | numeric metric | bggeoid10   | Block Group GEOID10 | number    | number      |
| No       |                | latitude    | Latitude            | number    | number      |
| No       |                | longitude   | Longitude           | number    | number      |
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
series e:43kr-jb2c d:2016-06-17T05:58:12.000Z t:county=Albany t:fips=36001 m:bggeoid10=360010001001

series e:43kr-jb2c d:2016-06-17T05:58:12.000Z t:county=Albany t:fips=36001 m:bggeoid10=360010001002

series e:43kr-jb2c d:2016-06-17T05:58:12.000Z t:county=Albany t:fips=36001 m:bggeoid10=360010002001
```

## Meta Commands

```ls
metric m:bggeoid10 p:long l:"Block Group GEOID10" d:"Geographic identifier for the block group; based on 2010 Census." t:dataTypeName=number

entity e:43kr-jb2c l:"State of New York Mortgage Agency (SONYMA) Target Areas by Census Tract" t:attribution="NYS Homes & Community Renewal" t:url=https://data.ny.gov/api/views/43kr-jb2c

property e:43kr-jb2c t:meta.view v:id=43kr-jb2c v:category="Economic Development" v:attributionLink=http://www.nyshcr.org/Topics/Home/Buyers/ v:averageRating=0 v:name="State of New York Mortgage Agency (SONYMA) Target Areas by Census Tract" v:attribution="NYS Homes & Community Renewal"

property e:43kr-jb2c t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:43kr-jb2c t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"
```

## Top Records

```ls
| :updated_at | county | fips  | bggeoid10    | latitude   | longitude   | 
| =========== | ====== | ===== | ============ | ========== | =========== | 
| 1466143092  | Albany | 36001 | 360010001001 | 42.6637001 | -73.7369472 | 
| 1466143092  | Albany | 36001 | 360010001002 | 42.6739886 | -73.7409837 | 
| 1466143092  | Albany | 36001 | 360010002001 | 42.6669773 | -73.7499358 | 
| 1466143092  | Albany | 36001 | 360010002002 | 42.6600676 | -73.7544078 | 
| 1466143092  | Albany | 36001 | 360010002003 | 42.6584451 | -73.7554372 | 
| 1466143092  | Albany | 36001 | 360010002004 | 42.6564868 | -73.7557630 | 
| 1466143092  | Albany | 36001 | 360010006001 | 42.6631036 | -73.7698705 | 
| 1466143092  | Albany | 36001 | 360010006002 | 42.6645485 | -73.7721939 | 
| 1466143092  | Albany | 36001 | 360010006003 | 42.6651756 | -73.7757182 | 
| 1466143092  | Albany | 36001 | 360010007001 | 42.6711145 | -73.7634485 | 
```