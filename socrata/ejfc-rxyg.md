# Sentences to Probation by Year: Beginning 1970

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/sentences-to-probation-by-year-beginning-1970) |
| Metadata | [Link](https://data.ny.gov/api/views/ejfc-rxyg) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/ejfc-rxyg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/ejfc-rxyg/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | ejfc-rxyg |
| Name | Sentences to Probation by Year: Beginning 1970 |
| Attribution | Division of Criminal Justice Services |
| Category | Public Safety |
| Tags | public safety, probation, probationers |
| Created | 2013-12-24T18:16:45Z |
| Publication Date | 2016-04-21T22:10:33Z |

## Description

The Division of Criminal Justice Services (DCJS) collects information on sentences to probation from the Office of Court Administration. DCJS publishes annual data on the DCJS public website.

## Columns

```ls
| Included | Schema Type    | Field Name | Name                          | Data Type | Render Type |
| ======== | ============== | ========== | ============================= | ========= | =========== |
| Yes      | series tag     | county     | County                        | text      | text        |
| Yes      | time           | year       | Year                          | number    | number      |
| Yes      | series tag     | conviction | Conviction                    | text      | text        |
| Yes      | numeric metric | vfo        | Violent Felony Offenses (VFO) | number    | number      |
| Yes      | numeric metric | drugs      | Drugs                         | number    | number      |
| Yes      | numeric metric | dwi        | DWI                           | number    | number      |
| Yes      | numeric metric | property   | Property                      | number    | number      |
| Yes      | numeric metric | other      | Other                         | number    | number      |
| Yes      | numeric metric | total      | Total                         | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:ejfc-rxyg d:1970-01-01T00:00:00.000Z t:conviction=Felony t:county=Albany m:dwi=0 m:total=43 m:other=6 m:drugs=13 m:vfo=10 m:property=14

series e:ejfc-rxyg d:1970-01-01T00:00:00.000Z t:conviction=Misdemeanor t:county=Albany m:dwi=1 m:total=107 m:other=30 m:drugs=39 m:vfo=0 m:property=37

series e:ejfc-rxyg d:1971-01-01T00:00:00.000Z t:conviction=Felony t:county=Albany m:dwi=0 m:total=46 m:other=7 m:drugs=1 m:vfo=9 m:property=29
```

## Meta Commands

```ls
metric m:vfo p:integer l:"Violent Felony Offenses (VFO)" t:dataTypeName=number

metric m:drugs p:integer l:Drugs t:dataTypeName=number

metric m:dwi p:integer l:DWI t:dataTypeName=number

metric m:property p:integer l:Property t:dataTypeName=number

metric m:other p:integer l:Other t:dataTypeName=number

metric m:total p:integer l:Total t:dataTypeName=number

entity e:ejfc-rxyg l:"Sentences to Probation by Year: Beginning 1970" t:attribution="Division of Criminal Justice Services" t:url=https://data.ny.gov/api/views/ejfc-rxyg

property e:ejfc-rxyg t:meta.view v:id=ejfc-rxyg v:category="Public Safety" v:attributionLink=http://www.criminaljustice.ny.gov/crimnet/ojsa/stats.htm v:averageRating=0 v:name="Sentences to Probation by Year: Beginning 1970" v:attribution="Division of Criminal Justice Services"

property e:ejfc-rxyg t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:ejfc-rxyg t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:ejfc-rxyg t:meta.view.metadata.custom_fields.common_core v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| county | year | conviction  | vfo | drugs | dwi | property | other | total | 
| ====== | ==== | =========== | === | ===== | === | ======== | ===== | ===== | 
| Albany | 1970 | Felony      | 10  | 13    | 0   | 14       | 6     | 43    | 
| Albany | 1970 | Misdemeanor | 0   | 39    | 1   | 37       | 30    | 107   | 
| Albany | 1971 | Felony      | 9   | 1     | 0   | 29       | 7     | 46    | 
| Albany | 1971 | Misdemeanor | 0   | 18    | 2   | 54       | 35    | 109   | 
| Albany | 1972 | Felony      | 11  | 16    | 0   | 33       | 17    | 77    | 
| Albany | 1972 | Misdemeanor | 0   | 43    | 3   | 111      | 70    | 227   | 
| Albany | 1973 | Felony      | 3   | 21    | 7   | 29       | 14    | 74    | 
| Albany | 1973 | Misdemeanor | 0   | 56    | 23  | 91       | 114   | 284   | 
| Albany | 1974 | Felony      | 4   | 4     | 1   | 12       | 12    | 33    | 
| Albany | 1974 | Misdemeanor | 0   | 49    | 24  | 183      | 116   | 372   | 
```