# Annual Population Estimates for New York State and Counties: Beginning 1970

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/annual-population-estimates-for-new-york-state-and-counties-beginning-1970) |
| Metadata | [Link](https://data.ny.gov/api/views/krt9-ym2k) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/krt9-ym2k/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/krt9-ym2k/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | krt9-ym2k |
| Name | Annual Population Estimates for New York State and Counties: Beginning 1970 |
| Attribution | New York State Department of Labor |
| Category | Government & Finance |
| Tags | annual population, new york state, county |
| Created | 2014-08-14T17:39:35Z |
| Publication Date | 2017-04-04T22:03:16Z |

## Description

Resident population of New York State and counties. Estimates are based on Census counts (base population), intercensal estimates, and postcensal estimates.

## Columns

```ls
| Included | Schema Type    | Field Name   | Name         | Data Type | Render Type |
| ======== | ============== | ============ | ============ | ========= | =========== |
| Yes      | series tag     | fips_code    | FIPS Code    | text      | number      |
| Yes      | series tag     | geography    | Geography    | text      | text        |
| Yes      | time           | year         | Year         | number    | number      |
| Yes      | series tag     | program_type | Program Type | text      | text        |
| Yes      | numeric metric | population   | Population   | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:krt9-ym2k d:2016-01-01T00:00:00.000Z t:program_type="Postcensal Population Estimate" t:geography="New York State" t:fips_code=36000 m:population=19745289

series e:krt9-ym2k d:2016-01-01T00:00:00.000Z t:program_type="Postcensal Population Estimate" t:geography="Albany County" t:fips_code=36001 m:population=308846

series e:krt9-ym2k d:2016-01-01T00:00:00.000Z t:program_type="Postcensal Population Estimate" t:geography="Allegany County" t:fips_code=36003 m:population=47077
```

## Meta Commands

```ls
metric m:population p:integer l:Population d:"Number of residents." t:dataTypeName=number

entity e:krt9-ym2k l:"Annual Population Estimates for New York State and Counties: Beginning 1970" t:attribution="New York State Department of Labor" t:url=https://data.ny.gov/api/views/krt9-ym2k

property e:krt9-ym2k t:meta.view v:id=krt9-ym2k v:category="Government & Finance" v:averageRating=0 v:name="Annual Population Estimates for New York State and Counties: Beginning 1970" v:attribution="New York State Department of Labor"

property e:krt9-ym2k t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:krt9-ym2k t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:krt9-ym2k t:meta.view.metadata.custom_fields.common_core v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| fips_code | geography          | year | program_type                   | population | 
| ========= | ================== | ==== | ============================== | ========== | 
| 36000     | New York State     | 2016 | Postcensal Population Estimate | 19745289   | 
| 36001     | Albany County      | 2016 | Postcensal Population Estimate | 308846     | 
| 36003     | Allegany County    | 2016 | Postcensal Population Estimate | 47077      | 
| 36005     | Bronx County       | 2016 | Postcensal Population Estimate | 1455720    | 
| 36007     | Broome County      | 2016 | Postcensal Population Estimate | 195334     | 
| 36009     | Cattaraugus County | 2016 | Postcensal Population Estimate | 77677      | 
| 36011     | Cayuga County      | 2016 | Postcensal Population Estimate | 77861      | 
| 36013     | Chautauqua County  | 2016 | Postcensal Population Estimate | 129504     | 
| 36015     | Chemung County     | 2016 | Postcensal Population Estimate | 86322      | 
| 36017     | Chenango County    | 2016 | Postcensal Population Estimate | 48579      | 
```