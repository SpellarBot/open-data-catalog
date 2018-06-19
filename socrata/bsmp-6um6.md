# Residential Assessment Ratios: Beginning Rate Year 1982

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/residential-assessment-ratios-beginning-rate-year-1982) |
| Metadata | [Link](https://data.ny.gov/api/views/bsmp-6um6) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/bsmp-6um6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/bsmp-6um6/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | bsmp-6um6 |
| Name | Residential Assessment Ratios: Beginning Rate Year 1982 |
| Attribution | New York State Department of Taxation and Finance |
| Category | Government & Finance |
| Tags | residential assessment ratio, rar, level of assessment |
| Created | 2014-05-19T21:33:43Z |
| Publication Date | 2016-10-05T22:00:46Z |

## Description

The Department of Taxation and Finance annually establishes a residential assessment ratio for assessing taxing jurisdictions to determine at what level of market value those jurisdictions are assessing their residential property.

## Columns

```ls
| Included | Schema Type    | Field Name                   | Name                         | Data Type | Render Type |
| ======== | ============== | ============================ | ============================ | ========= | =========== |
| Yes      | time           | rate_year                    | RATE YEAR                    | number    | number      |
| Yes      | series tag     | swis_code                    | SWIS CODE                    | text      | text        |
| Yes      | series tag     | type                         | TYPE                         | text      | text        |
| Yes      | series tag     | county_name                  | COUNTY NAME                  | text      | text        |
| Yes      | series tag     | municipality_name            | MUNICIPALITY NAME            | text      | text        |
| Yes      | series tag     | village_name                 | VILLAGE NAME                 | text      | text        |
| Yes      | numeric metric | residential_assessment_ratio | RESIDENTIAL ASSESSMENT RATIO | number    | number      |
```

## Time Field

```ls
Value = rate_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:bsmp-6um6 d:2009-01-01T00:00:00.000Z t:swis_code=010100 t:village_name=City t:type=Albany t:county_name=Albany m:residential_assessment_ratio=92.06

series e:bsmp-6um6 d:2009-01-01T00:00:00.000Z t:swis_code=010300 t:village_name=City t:type=Albany t:county_name=Cohoes m:residential_assessment_ratio=53.19

series e:bsmp-6um6 d:2009-01-01T00:00:00.000Z t:swis_code=011800 t:village_name=City t:type=Albany t:county_name=Watervliet m:residential_assessment_ratio=58.03
```

## Meta Commands

```ls
metric m:residential_assessment_ratio p:float l:"RESIDENTIAL ASSESSMENT RATIO" d:"The measurement of the overall ratio of the total assessed value of residential property in the municipality compared to the full value of that residential property" t:dataTypeName=number

entity e:bsmp-6um6 l:"Residential Assessment Ratios:  Beginning Rate Year 1982" t:attribution="New York State Department of Taxation and Finance" t:url=https://data.ny.gov/api/views/bsmp-6um6

property e:bsmp-6um6 t:meta.view v:id=bsmp-6um6 v:category="Government & Finance" v:attributionLink=http://orpts.tax.ny.gov/cfapps/MuniPro/ v:averageRating=0 v:name="Residential Assessment Ratios:  Beginning Rate Year 1982" v:attribution="New York State Department of Taxation and Finance"

property e:bsmp-6um6 t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:bsmp-6um6 t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:bsmp-6um6 t:meta.view.metadata.custom_fields.common_core v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| rate_year | swis_code | type   | county_name | municipality_name | village_name | residential_assessment_ratio | 
| ========= | ========= | ====== | =========== | ================= | ============ | ============================ | 
| 2009      | 010100    | Albany | Albany      |                   | City         | 92.06                        | 
| 2009      | 010300    | Albany | Cohoes      |                   | City         | 53.19                        | 
| 2009      | 011800    | Albany | Watervliet  |                   | City         | 58.03                        | 
| 2009      | 012000    | Albany | Berne       |                   | Town         | 53.17                        | 
| 2009      | 012200    | Albany | Bethlehem   |                   | Town         | 90.62                        | 
| 2009      | 012400    | Albany | Coeymans    |                   | Town         | 92.77                        | 
| 2009      | 012401    | Albany | Coeymans    | Ravena            | Village      |                              | 
| 2009      | 012600    | Albany | Colonie     |                   | Town         | 54.38                        | 
| 2009      | 012601    | Albany | Colonie     | Colonie           | Village      | 3.04                         | 
| 2009      | 012603    | Albany | Colonie     | Menands           | Village      |                              | 
```