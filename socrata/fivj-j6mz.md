# Public Assistance Cases Opened by Month: Beginning 2006

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/public-assistance-cases-opened-by-month-beginning-2006) |
| Metadata | [Link](https://data.ny.gov/api/views/fivj-j6mz) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/fivj-j6mz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/fivj-j6mz/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | fivj-j6mz |
| Name | Public Assistance Cases Opened by Month: Beginning 2006 |
| Attribution | New York State Office of Temporary and Disability Assistance (OTDA) |
| Category | Human Services |
| Tags | ta, sna, fa welfare, case openings, pa applications |
| Created | 2016-05-10T18:54:17Z |
| Publication Date | 2017-04-06T22:00:23Z |

## Description

This dataset, from New York State Office of Temporary and Disability Assistance, provides the number of Public Assistance case openings (applications approved) in each month for each Local Social Services District (SSD), similar to data published on an annual basis in the "Statistical Report on the Operations of New York State Public Assistance Programs."

## Columns

```ls
| Included | Schema Type    | Field Name                     | Name                                  | Data Type | Render Type |
| ======== | ============== | ============================== | ===================================== | ========= | =========== |
| No       |                | year                           | Year                                  | number    | number      |
| No       |                | month                          | Month                                 | text      | text        |
| Yes      | series tag     | month_code                     | Month Code                            | text      | number      |
| Yes      | series tag     | district_code                  | District Code                         | text      | text        |
| Yes      | series tag     | district                       | District                              | text      | text        |
| Yes      | numeric metric | total_openings                 | Total Public Assistance Case Openings | number    | number      |
| Yes      | numeric metric | family_assistance_openings     | Family Assistance Case Openings       | number    | number      |
| Yes      | numeric metric | safety_net_assistance_openings | Safety Net Assistance Case Openings   | number    | number      |
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
series e:fivj-j6mz d:2006-01-01T00:00:00.000Z t:district_code=01 t:month_code=1 t:district=Albany m:total_openings=322 m:safety_net_assistance_openings=203 m:family_assistance_openings=119

series e:fivj-j6mz d:2006-01-01T00:00:00.000Z t:district_code=02 t:month_code=1 t:district=Allegany m:total_openings=54 m:safety_net_assistance_openings=34 m:family_assistance_openings=20

series e:fivj-j6mz d:2006-01-01T00:00:00.000Z t:district_code=03 t:month_code=1 t:district=Broome m:total_openings=321 m:safety_net_assistance_openings=192 m:family_assistance_openings=129
```

## Meta Commands

```ls
metric m:total_openings p:integer l:"Total Public Assistance Case Openings" d:"Total Public Assistance case openings (applications approved) in the designated month. Sum of Family Assistance and Safety Net Assistance case openings." t:dataTypeName=number

metric m:family_assistance_openings p:integer l:"Family Assistance Case Openings" d:"Family Assistance case openings (applications approved) in the designated month." t:dataTypeName=number

metric m:safety_net_assistance_openings p:integer l:"Safety Net Assistance Case Openings" d:"Safety Net Assistance case openings (applications approved) in the designated month." t:dataTypeName=number

entity e:fivj-j6mz l:"Public Assistance Cases Opened by Month:  Beginning 2006" t:attribution="New York State Office of Temporary and Disability Assistance (OTDA)" t:url=https://data.ny.gov/api/views/fivj-j6mz

property e:fivj-j6mz t:meta.view v:id=fivj-j6mz v:category="Human Services" v:attributionLink=https://otda.ny.gov/resources/legislative-report/ v:averageRating=0 v:name="Public Assistance Cases Opened by Month:  Beginning 2006" v:attribution="New York State Office of Temporary and Disability Assistance (OTDA)"

property e:fivj-j6mz t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:fivj-j6mz t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"
```

## Top Records

```ls
| year | month   | month_code | district_code | district    | total_openings | family_assistance_openings | safety_net_assistance_openings | 
| ==== | ======= | ========== | ============= | =========== | ============== | ========================== | ============================== | 
| 2006 | January | 1          | 01            | Albany      | 322            | 119                        | 203                            | 
| 2006 | January | 1          | 02            | Allegany    | 54             | 20                         | 34                             | 
| 2006 | January | 1          | 03            | Broome      | 321            | 129                        | 192                            | 
| 2006 | January | 1          | 04            | Cattaraugus | 53             | 19                         | 34                             | 
| 2006 | January | 1          | 05            | Cayuga      | 38             | 13                         | 25                             | 
| 2006 | January | 1          | 06            | Chautauqua  | 155            | 70                         | 85                             | 
| 2006 | January | 1          | 07            | Chemung     | 103            | 39                         | 64                             | 
| 2006 | January | 1          | 08            | Chenango    | 27             | 10                         | 17                             | 
| 2006 | January | 1          | 09            | Clinton     | 103            | 28                         | 75                             | 
| 2006 | January | 1          | 10            | Columbia    | 39             | 12                         | 27                             | 
```