# DPSCS Releasees Returned to Corrections within One, Two, and Three Years of Release

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dpscs-releasees-returned-to-corrections-within-one-two-and-three-years-of-release-9e2d0) |
| Metadata | [Link](https://data.maryland.gov/api/views/h3ax-xbn9) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/h3ax-xbn9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/h3ax-xbn9/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | h3ax-xbn9 |
| Name | DPSCS Releasees Returned to Corrections within One, Two, and Three Years of Release |
| Attribution | DPSCS |
| Category | Public Safety |
| Tags | recidivism, dpscs, crime, re-entry, prisoner re-entry |
| Created | 2014-06-18T19:37:42Z |
| Publication Date | 2016-10-18T18:59:36Z |

## Description

The key metric of recidivism for Maryland and for the Department of Public Safety and Correctional Services (DPSCS) is the cumulative percentage of releasees who return to Corrections within three years. Since the start of the O'Malley-Brown administration we have driven down recidivism rates at a record pace. This dataset shows how many releasees return to Corrections within one, two, and three years of release. DPSCS's Office of Grants Policy and Statistics (GPS) publishes these data annually in their Repeat Incarceration Supervision Cycle (RISC) reports. The newest data were published in August 2013. Data for FY 2012 are scheduled to be released in summer 2014.

## Columns

```ls
| Included | Schema Type    | Field Name                                                                  | Name                                                                              | Data Type | Render Type |
| ======== | ============== | =========================================================================== | ================================================================================= | ========= | =========== |
| Yes      | time           | fiscal_year_of_release                                                      | Fiscal Year of Release                                                            | number    | text        |
| Yes      | numeric metric | cumulative_percenage_of_corrections_releasees_returned_by_end_of_first_year | Cumulative Percentage of Corrections Releasees Returned By End of First Full Year | percent   | percent     |
```

## Time Field

```ls
Value = fiscal_year_of_release
Format & Zone = yyyy
```

## Data Commands

```ls
series e:h3ax-xbn9 d:1999-01-01T00:00:00.000Z m:cumulative_percenage_of_corrections_releasees_returned_by_end_of_first_year=24.8

series e:h3ax-xbn9 d:2000-01-01T00:00:00.000Z m:cumulative_percenage_of_corrections_releasees_returned_by_end_of_first_year=23.9

series e:h3ax-xbn9 d:2001-01-01T00:00:00.000Z m:cumulative_percenage_of_corrections_releasees_returned_by_end_of_first_year=23.2
```

## Meta Commands

```ls
metric m:cumulative_percenage_of_corrections_releasees_returned_by_end_of_first_year p:float l:"Cumulative Percentage of Corrections Releasees Returned By End of First Full Year" t:dataTypeName=percent

entity e:h3ax-xbn9 l:"DPSCS Releasees Returned to Corrections within One, Two, and Three Years of Release" t:attribution=DPSCS t:url=https://data.maryland.gov/api/views/h3ax-xbn9

property e:h3ax-xbn9 t:meta.view v:id=h3ax-xbn9 v:category="Public Safety" v:attributionLink=http://dpscs.state.md.us v:averageRating=0 v:name="DPSCS Releasees Returned to Corrections within One, Two, and Three Years of Release" v:attribution=DPSCS

property e:h3ax-xbn9 t:meta.view.license v:name="Public Domain"

property e:h3ax-xbn9 t:meta.view.owner v:id=cs6p-bz62 v:profileImageUrlMedium=/api/users/cs6p-bz62/profile_images/THUMB v:profileImageUrlLarge=/api/users/cs6p-bz62/profile_images/LARGE v:screenName="data.maryland.gov Administration" v:profileImageUrlSmall=/api/users/cs6p-bz62/profile_images/TINY v:lastNotificationSeenAt=1491976108 v:displayName="data.maryland.gov Administration"

property e:h3ax-xbn9 t:meta.view.tableauthor v:id=cs6p-bz62 v:profileImageUrlMedium=/api/users/cs6p-bz62/profile_images/THUMB v:profileImageUrlLarge=/api/users/cs6p-bz62/profile_images/LARGE v:screenName="data.maryland.gov Administration" v:profileImageUrlSmall=/api/users/cs6p-bz62/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1491976108 v:displayName="data.maryland.gov Administration"
```

## Top Records

```ls
| fiscal_year_of_release | cumulative_percenage_of_corrections_releasees_returned_by_end_of_first_year | 
| ====================== | =========================================================================== | 
| 1999                   | 24.8                                                                        | 
| 2000                   | 23.9                                                                        | 
| 2001                   | 23.2                                                                        | 
| 2002                   | 23.7                                                                        | 
| 2003                   | 23.0                                                                        | 
| 2004                   | 22.6                                                                        | 
| 2005                   | 21.2                                                                        | 
| 2006                   | 21.9                                                                        | 
| 2007                   | 23.3                                                                        | 
| 2008                   | 20.4                                                                        | 
```