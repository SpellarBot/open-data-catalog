# Equalization Rates: Beginning Rate Year 1954

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/equalization-rates-beginning-rate-year-1954) |
| Metadata | [Link](https://data.ny.gov/api/views/e6pv-77bh) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/e6pv-77bh/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/e6pv-77bh/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | e6pv-77bh |
| Name | Equalization Rates: Beginning Rate Year 1954 |
| Attribution | New York State Department of Taxation and Finance |
| Category | Government & Finance |
| Tags | equalization rate, assessed value, market value, level of assessment |
| Created | 2014-05-19T21:00:05Z |
| Publication Date | 2016-10-07T10:22:45Z |

## Description

The Department of Taxation and Finance annually establishes an equalization rate for assessing taxing jurisdictions to determine at what level of market value those jurisdictions are assessing.

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type | Render Type |
| ======== | ============== | ================= | ================= | ========= | =========== |
| Yes      | time           | rate_year         | RATE YEAR         | number    | number      |
| Yes      | series tag     | swis_code         | SWIS CODE         | text      | text        |
| Yes      | series tag     | type              | TYPE              | text      | text        |
| Yes      | series tag     | county_name       | COUNTY NAME       | text      | text        |
| Yes      | series tag     | municipality_name | MUNICIPALITY NAME | text      | text        |
| Yes      | series tag     | village_name      | VILLAGE NAME      | text      | text        |
| Yes      | numeric metric | equalization_rate | EQUALIZATION RATE | number    | number      |
```

## Time Field

```ls
Value = rate_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:e6pv-77bh d:1954-01-01T00:00:00.000Z t:swis_code=010000 t:type=County t:county_name=Albany m:equalization_rate=48

series e:e6pv-77bh d:1954-01-01T00:00:00.000Z t:municipality_name=Albany t:swis_code=010100 t:type=City t:county_name=Albany m:equalization_rate=63

series e:e6pv-77bh d:1954-01-01T00:00:00.000Z t:municipality_name=Cohoes t:swis_code=010300 t:type=City t:county_name=Albany m:equalization_rate=46
```

## Meta Commands

```ls
metric m:equalization_rate p:double l:"EQUALIZATION RATE" d:"The measurement of the overall ratio of the total assessed value of all property in the municipality compared to the full value of that property Note: A blank value indicates that there is either no applicable or finalized rate for this year." t:dataTypeName=number

entity e:e6pv-77bh l:"Equalization Rates:  Beginning Rate Year 1954" t:attribution="New York State Department of Taxation and Finance" t:url=https://data.ny.gov/api/views/e6pv-77bh

property e:e6pv-77bh t:meta.view v:id=e6pv-77bh v:category="Government & Finance" v:attributionLink=http://orpts.tax.ny.gov/cfapps/MuniPro/ v:averageRating=0 v:name="Equalization Rates:  Beginning Rate Year 1954" v:attribution="New York State Department of Taxation and Finance"

property e:e6pv-77bh t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:e6pv-77bh t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:e6pv-77bh t:meta.view.metadata.custom_fields.common_core v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| rate_year | swis_code | type    | county_name | municipality_name | village_name | equalization_rate | 
| ========= | ========= | ======= | =========== | ================= | ============ | ================= | 
| 1954      | 010000    | County  | Albany      |                   |              | 48                | 
| 1954      | 010100    | City    | Albany      | Albany            |              | 63                | 
| 1954      | 010300    | City    | Albany      | Cohoes            |              | 46                | 
| 1954      | 011800    | City    | Albany      | Watervliet        |              | 48                | 
| 1954      | 012000    | Town    | Albany      | Berne             |              | 27                | 
| 1954      | 012200    | Town    | Albany      | Bethlehem         |              | 33                | 
| 1954      | 012400    | Town    | Albany      | Coeymans          |              | 38                | 
| 1954      | 012401    | Village | Albany      | Coeymans          | Ravena       | 37                | 
| 1954      | 012600    | Town    | Albany      | Colonie           |              | 29                | 
| 1954      | 012601    | Village | Albany      | Colonie           | Colonie      | 25                | 
```