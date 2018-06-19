# Iowa Library for the Blind and Physically Handicapped Usage and Production Stats

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/iowa-library-for-the-blind-and-physically-handicapped-usage-and-production-stats) |
| Metadata | [Link](https://data.iowa.gov/api/views/p2tq-3x3z) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/p2tq-3x3z/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/p2tq-3x3z/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | p2tq-3x3z |
| Name | Iowa Library for the Blind and Physically Handicapped Usage and Production Stats |
| Attribution | Iowa Department for the Blind |
| Category | Communities & People |
| Tags | blind, iowa, library, iowa library for the blind and physically handicapped |
| Created | 2016-07-15T19:06:18Z |
| Publication Date | 2016-07-18T12:55:41Z |

## Description

A collection of stats starting in SFY 2013, expressed in annual totals, provided by the Iowa Library for the Blind and Physically Handicapped. They reflect the amount of usage by patrons related to materials circulation and production of materials to fulfill education and employment-related requests.

## Columns

```ls
| Included | Schema Type    | Field Name  | Name        | Data Type | Render Type |
| ======== | ============== | =========== | =========== | ========= | =========== |
| Yes      | series tag     | measure     | Measure     | text      | text        |
| Yes      | time           | fiscal_year | Fiscal Year | number    | number      |
| Yes      | numeric metric | value       | Value       | number    | number      |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:p2tq-3x3z d:2013-01-01T00:00:00.000Z t:measure="Number of Iowans Using Services" m:value=6617

series e:p2tq-3x3z d:2013-01-01T00:00:00.000Z t:measure="Number of Items Circulated (checked out to patrons)" m:value=297271

series e:p2tq-3x3z d:2013-01-01T00:00:00.000Z t:measure="Number of Items Downloaded from BARD" m:value=43231
```

## Meta Commands

```ls
metric m:value p:integer l:Value t:dataTypeName=number

entity e:p2tq-3x3z l:"Iowa Library for the Blind and Physically Handicapped Usage and Production Stats" t:attribution="Iowa Department for the Blind" t:url=https://data.iowa.gov/api/views/p2tq-3x3z

property e:p2tq-3x3z t:meta.view v:id=p2tq-3x3z v:category="Communities & People" v:attributionLink=http://www.idbonline.org v:averageRating=0 v:name="Iowa Library for the Blind and Physically Handicapped Usage and Production Stats" v:attribution="Iowa Department for the Blind"

property e:p2tq-3x3z t:meta.view.license v:name="Public Domain"

property e:p2tq-3x3z t:meta.view.owner v:id=e8te-6wiw v:profileImageUrlMedium=/api/users/e8te-6wiw/profile_images/THUMB v:profileImageUrlLarge=/api/users/e8te-6wiw/profile_images/LARGE v:screenName="Iowa Department for the Blind" v:profileImageUrlSmall=/api/users/e8te-6wiw/profile_images/TINY v:displayName="Iowa Department for the Blind"

property e:p2tq-3x3z t:meta.view.tableauthor v:id=e8te-6wiw v:profileImageUrlMedium=/api/users/e8te-6wiw/profile_images/THUMB v:profileImageUrlLarge=/api/users/e8te-6wiw/profile_images/LARGE v:screenName="Iowa Department for the Blind" v:profileImageUrlSmall=/api/users/e8te-6wiw/profile_images/TINY v:roleName=editor v:displayName="Iowa Department for the Blind"
```

## Top Records

```ls
| measure                                                                        | fiscal_year | value  | 
| ============================================================================== | =========== | ====== | 
| Number of Iowans Using Services                                                | 2013        | 6617   | 
| Number of Items Circulated (checked out to patrons)                            | 2013        | 297271 | 
| Number of Items Downloaded from BARD                                           | 2013        | 43231  | 
| Number of Items Produced in an Alternative Media by Library                    | 2013        | 1886   | 
| Number Educational and Vocational Atlernative Media Requests Filled by Library | 2013        | 1473   | 
| Number of Iowans Using Services                                                | 2014        | 9158   | 
| Number of Items Circulated (checked out to patrons)                            | 2014        | 319749 | 
| Number of Items Downloaded from BARD                                           | 2014        | 43320  | 
| Number of Items Produced in an Alternative Media by Library                    | 2014        | 1388   | 
| Number Educational and Vocational Atlernative Media Requests Filled by Library | 2014        | 1150   | 
```