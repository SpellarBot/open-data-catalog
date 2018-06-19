# Supplemental Security Income (SSI) Recipients and Expenditures: Beginning 2002

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/supplemental-security-income-ssi-recipients-and-expenditures-beginning-2002) |
| Metadata | [Link](https://data.ny.gov/api/views/kym4-b5dg) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/kym4-b5dg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/kym4-b5dg/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | kym4-b5dg |
| Name | Supplemental Security Income (SSI) Recipients and Expenditures: Beginning 2002 |
| Attribution | New York State Office of Temporary and Disability Assistance |
| Category | Human Services |
| Tags | ssi, supplemental security income, disability, disabled, blind, aged, ssi state supplement |
| Created | 2014-01-13T22:31:15Z |
| Publication Date | 2017-03-31T22:01:45Z |

## Description

These data are monthly listings of recipients and expenditures for the Supplemental Security Income Program.

## Columns

```ls
| Included | Schema Type    | Field Name               | Name                     | Data Type | Render Type |
| ======== | ============== | ======================== | ======================== | ========= | =========== |
| No       |                | year                     | Year                     | number    | number      |
| No       |                | month                    | Month                    | text      | text        |
| Yes      | series tag     | monthcode                | Month Code               | text      | number      |
| Yes      | series tag     | districtcode             | District Code            | text      | number      |
| Yes      | series tag     | district                 | District                 | text      | text        |
| Yes      | numeric metric | ssi_recipients           | SSI Recipients           | number    | number      |
| Yes      | numeric metric | total_ssi_expenditures   | Total SSI Expenditures   | money     | money       |
| Yes      | numeric metric | federal_ssi_expenditures | Federal SSI Expenditures | money     | money       |
| Yes      | numeric metric | state_ssi_expenditures   | State SSI Expenditures   | money     | money       |
```

## Time Field

```ls
Value = year-month
Format & Zone = yyyy-MMMM
```

## Series Fields

```ls
Excluded Fields = year,month
```

## Data Commands

```ls
series e:kym4-b5dg d:2014-07-01T00:00:00.000Z t:monthcode=7 t:districtcode=1 t:district=Albany m:federal_ssi_expenditures=3597845 m:ssi_recipients=7339 m:total_ssi_expenditures=4141436 m:state_ssi_expenditures=543591

series e:kym4-b5dg d:2014-07-01T00:00:00.000Z t:monthcode=7 t:districtcode=2 t:district=Allegany m:federal_ssi_expenditures=737591 m:ssi_recipients=1571 m:total_ssi_expenditures=854822 m:state_ssi_expenditures=117231

series e:kym4-b5dg d:2014-07-01T00:00:00.000Z t:monthcode=7 t:districtcode=3 t:district=Broome m:federal_ssi_expenditures=3668600 m:ssi_recipients=7123 m:total_ssi_expenditures=4149212 m:state_ssi_expenditures=480612
```

## Meta Commands

```ls
metric m:ssi_recipients p:integer l:"SSI Recipients" d:"Table 17 Supplemental Security Income Recipients." t:dataTypeName=number

metric m:total_ssi_expenditures p:integer l:"Total SSI Expenditures" d:"Table 17 Supplemental Security Income Total Expenditures." t:dataTypeName=money

metric m:federal_ssi_expenditures p:integer l:"Federal SSI Expenditures" d:"Table 17 Supplemental Security Income Total Federal Expenditures." t:dataTypeName=money

metric m:state_ssi_expenditures p:integer l:"State SSI Expenditures" d:"Table 17 Supplemental Security Income State Expenditures." t:dataTypeName=money

entity e:kym4-b5dg l:"Supplemental Security Income (SSI) Recipients and Expenditures: Beginning 2002" t:attribution="New York State Office of Temporary and Disability Assistance" t:url=https://data.ny.gov/api/views/kym4-b5dg

property e:kym4-b5dg t:meta.view v:id=kym4-b5dg v:category="Human Services" v:attributionLink=http://otda.ny.gov/resources/caseload/ v:averageRating=0 v:name="Supplemental Security Income (SSI) Recipients and Expenditures: Beginning 2002" v:attribution="New York State Office of Temporary and Disability Assistance"

property e:kym4-b5dg t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:kym4-b5dg t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:kym4-b5dg t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| year | month | monthcode | districtcode | district    | ssi_recipients | total_ssi_expenditures | federal_ssi_expenditures | state_ssi_expenditures | 
| ==== | ===== | ========= | ============ | =========== | ============== | ====================== | ======================== | ====================== | 
| 2014 | July  | 7         | 1            | Albany      | 7339           | 4141436                | 3597845                  | 543591                 | 
| 2014 | July  | 7         | 2            | Allegany    | 1571           | 854822                 | 737591                   | 117231                 | 
| 2014 | July  | 7         | 3            | Broome      | 7123           | 4149212                | 3668600                  | 480612                 | 
| 2014 | July  | 7         | 4            | Cattaraugus | 2614           | 1437267                | 1243225                  | 194042                 | 
| 2014 | July  | 7         | 5            | Cayuga      | 1923           | 1113852                | 933935                   | 179917                 | 
| 2014 | July  | 7         | 6            | Chautauqua  | 5087           | 2894245                | 2510754                  | 383491                 | 
| 2014 | July  | 7         | 7            | Chemung     | 3585           | 1973301                | 1712793                  | 260508                 | 
| 2014 | July  | 7         | 8            | Chenango    | 1590           | 860879                 | 759440                   | 101439                 | 
| 2014 | July  | 7         | 9            | Clinton     | 3087           | 1732156                | 1491097                  | 241059                 | 
| 2014 | July  | 7         | 10           | Columbia    | 1704           | 978819                 | 789899                   | 188920                 | 
```