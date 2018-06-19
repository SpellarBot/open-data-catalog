# Jobs By Industry: Beginning 2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/jobs-by-industry) |
| Metadata | [Link](https://data.ny.gov/api/views/pxa9-czw8) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/pxa9-czw8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/pxa9-czw8/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | pxa9-czw8 |
| Name | Jobs By Industry: Beginning 2012 |
| Attribution | Empire State Development |
| Category | Economic Development |
| Tags | job trends |
| Created | 2013-02-27T19:05:42Z |
| Publication Date | 2016-11-04T21:21:07Z |

## Description

This data shows jobs by industry, beginning in 2012, created from a dataset of economic profiles of the 10 Empire State Development (ESD) economic development regions. Refer to the About section for the data dictionary and other information.

## Columns

```ls
| Included | Schema Type    | Field Name | Name       | Data Type | Render Type |
| ======== | ============== | ========== | ========== | ========= | =========== |
| Yes      | time           | year       | Year       | number    | number      |
| Yes      | series tag     | region     | Region     | text      | text        |
| Yes      | series tag     | naics_code | NAICS Code | text      | text        |
| Yes      | series tag     | industry   | Industry   | text      | text        |
| Yes      | numeric metric | jobs       | Jobs       | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:pxa9-czw8 d:2012-01-01T00:00:00.000Z t:region="Capital Region" t:industry="Agriculture, Forestry, Fishing and Hunting" t:naics_code=11 m:jobs=2183

series e:pxa9-czw8 d:2012-01-01T00:00:00.000Z t:region="Capital Region" t:industry="Mining, Quarrying, and Oil and Gas Extraction" t:naics_code=21 m:jobs=733

series e:pxa9-czw8 d:2012-01-01T00:00:00.000Z t:region="Capital Region" t:industry=Utilities t:naics_code=22 m:jobs=1838
```

## Meta Commands

```ls
metric m:jobs p:integer l:Jobs d:"All employees in the industry being reported on." t:dataTypeName=number

entity e:pxa9-czw8 l:"Jobs By Industry:  Beginning 2012" t:attribution="Empire State Development" t:url=https://data.ny.gov/api/views/pxa9-czw8

property e:pxa9-czw8 t:meta.view v:id=pxa9-czw8 v:category="Economic Development" v:averageRating=0 v:name="Jobs By Industry:  Beginning 2012" v:attribution="Empire State Development"

property e:pxa9-czw8 t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:pxa9-czw8 t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:pxa9-czw8 t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| year | region         | naics_code | industry                                      | jobs  | 
| ==== | ============== | ========== | ============================================= | ===== | 
| 2012 | Capital Region | 11         | Agriculture, Forestry, Fishing and Hunting    | 2183  | 
| 2012 | Capital Region | 21         | Mining, Quarrying, and Oil and Gas Extraction | 733   | 
| 2012 | Capital Region | 22         | Utilities                                     | 1838  | 
| 2012 | Capital Region | 23         | Construction                                  | 19514 | 
| 2012 | Capital Region | 31-33      | Manufacturing                                 | 30812 | 
| 2012 | Capital Region | 42         | Wholesale Trade                               | 14606 | 
| 2012 | Capital Region | 44-45      | Retail Trade                                  | 58341 | 
| 2012 | Capital Region | 48-49      | Transportation and Warehousing                | 11041 | 
| 2012 | Capital Region | 51         | Information                                   | 9577  | 
| 2012 | Capital Region | 52         | Finance and Insurance                         | 21556 | 
```