# Essex County Property Taxes: 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/essex-county-property-taxes-2013) |
| Metadata | [Link](https://data.ny.gov/api/views/u4z3-9gzj) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/u4z3-9gzj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/u4z3-9gzj/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | u4z3-9gzj |
| Name | Essex County Property Taxes: 2013 |
| Attribution | Essex County Information Systems |
| Category | Government & Finance |
| Tags | taxes |
| Created | 2013-03-03T19:27:44Z |
| Publication Date | 2013-03-03T19:31:36Z |

## Description

Essex County 2013 Property Taxes

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                       | Data Type | Render Type |
| ======== | ============== | ========================== | ========================== | ========= | =========== |
| Yes      | series tag     | town                       | Town                       | text      | text        |
| Yes      | series tag     | owner                      | Owner                      | text      | text        |
| Yes      | series tag     | account                    | Account                    | text      | text        |
| Yes      | numeric metric | swis                       | SWIS                       | number    | number      |
| Yes      | series tag     | tax_map                    | Tax Map                    | text      | text        |
| No       |                | address                    | Address                    | text      | text        |
| Yes      | numeric metric | acreage                    | Acreage                    | number    | number      |
| Yes      | series tag     | property_class_description | Property Class Description | text      | text        |
| Yes      | numeric metric | base_tax                   | Base Tax                   | number    | number      |
| Yes      | numeric metric | assessment                 | Assessment                 | number    | number      |
| Yes      | time           | tax_year                   | Tax Year                   | number    | number      |
```

## Time Field

```ls
Value = tax_year
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = address
```

## Data Commands

```ls
series e:u4z3-9gzj d:2013-01-01T00:00:00.000Z t:property_class_description=Supermarket t:owner="4200 Baychester Ave LLC" t:account=571A100302 t:tax_map=4.37-3-28.002 t:town=CHESTERFIELD m:swis=152001 m:acreage=0.01 m:assessment=325500 m:base_tax=2300.35

series e:u4z3-9gzj d:2013-01-01T00:00:00.000Z t:property_class_description="1 Family Res" t:owner="Abair Donna M" t:account=575L108006 t:tax_map=1.76-4-2.002 t:town=CHESTERFIELD m:swis=152089 m:acreage=0 m:assessment=126900 m:base_tax=1222.5

series e:u4z3-9gzj d:2013-01-01T00:00:00.000Z t:property_class_description="Mfg hsing pk" t:owner="ACR Properties LLC" t:account=571A101409 t:tax_map=4.45-4-14.100 t:town=CHESTERFIELD m:swis=152001 m:acreage=0.02 m:assessment=119400 m:base_tax=843.81
```

## Meta Commands

```ls
metric m:swis p:integer l:SWIS t:dataTypeName=number

metric m:acreage p:float l:Acreage t:dataTypeName=number

metric m:base_tax p:double l:"Base Tax" t:dataTypeName=number

metric m:assessment p:integer l:Assessment t:dataTypeName=number

entity e:u4z3-9gzj l:"Essex County Property Taxes: 2013" t:attribution="Essex County Information Systems" t:url=https://data.ny.gov/api/views/u4z3-9gzj

property e:u4z3-9gzj t:meta.view v:id=u4z3-9gzj v:category="Government & Finance" v:attributionLink=http://www.co.essex.ny.us/Treasurer/FileCreate.aspx v:averageRating=0 v:name="Essex County Property Taxes: 2013" v:attribution="Essex County Information Systems"

property e:u4z3-9gzj t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:u4z3-9gzj t:meta.view.tableauthor v:id=mwxm-zess v:profileImageUrlMedium=/api/users/mwxm-zess/profile_images/THUMB v:profileImageUrlLarge=/api/users/mwxm-zess/profile_images/LARGE v:screenName="Lindsey Krough" v:profileImageUrlSmall=/api/users/mwxm-zess/profile_images/TINY v:roleName=administrator v:displayName="Lindsey Krough"

property e:u4z3-9gzj t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| town         | owner                   | account    | swis   | tax_map       | address                                                   | acreage | property_class_description | base_tax | assessment | tax_year | 
| ============ | ======================= | ========== | ====== | ============= | ========================================================= | ======= | ========================== | ======== | ========== | ======== | 
| CHESTERFIELD | 4200 Baychester Ave LLC | 571A100302 | 152001 | 4.37-3-28.002 | 230 Woodward St Waban MA 02168                            | 0.01    | Supermarket                | 2300.35  | 325500     | 2013     | 
| CHESTERFIELD | Abair Donna M           | 575L108006 | 152089 | 1.76-4-2.002  | 66 Lake St Port Kent NY 12975                             | 0       | 1 Family Res               | 1222.50  | 126900     | 2013     | 
| CHESTERFIELD | ACR Properties LLC      | 571A101409 | 152001 | 4.45-4-14.100 | PO Box 735 Plattsburgh NY 12901                           | 0.02    | Mfg hsing pk               | 843.81   | 119400     | 2013     | 
| CHESTERFIELD | Acton Paul R            | 571A102114 | 152001 | 4.37-1-6.000  | Acton Lauren A 5 Beach St Keeseville NY 12944             | 0       | 1 Family Res               | 577.39   | 81700      | 2013     | 
| CHESTERFIELD | Adams D Michael         | 575J109604 | 152089 | 11.9-1-9.000  | 48 Little Sandy Rd Keeseville NY 12944                    | 0.01    | Seasonal res               | 3177.96  | 348700     | 2013     | 
| CHESTERFIELD | Adirondack Farms LLC    | 575J104414 | 152089 | 4.3-1-93.110  | 193 Brown Rd Peru NY 12972                                | 1.31    | Field crops                | 1317.84  | 213400     | 2013     | 
| CHESTERFIELD | Adk Rental Opp Inc      | 571A100206 | 152001 | 4.38-2-13.100 | c/o Clark Forster Pres 14 Chasm Rd Ausable Chasm NY 12911 | 0.02    | 1 use sm bld               | 2451.38  | 155800     | 2013     | 
| CHESTERFIELD | Adk Rental Opp Inc      | 575J108809 | 152089 | 10.8-2-16.000 | 14 Chasm Rd Ausable Chasm NY 12911                        | 0.02    | Res vac land               | 7016.99  | 263700     | 2013     | 
| CHESTERFIELD | Agoney Amos             | 571A100415 | 152001 | 4.38-4-29.000 | Agoney Sandra 30 Church St Keeseville NY 12944-1255       | 0       | 1 Family Res               | 614.84   | 87000      | 2013     | 
| CHESTERFIELD | Agoney Amos J           | 571A189005 | 152001 | 4.37-3-9.200  | Agoney Sandra A 30 Church St Keeseville NY 12944          | 0       | 1 use sm bld               | 325.09   | 46000      | 2013     | 
```