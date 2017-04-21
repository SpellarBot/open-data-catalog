# Community Sponsorships

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/community-sponsorships) |
| Metadata | [Link](https://data.austintexas.gov/api/views/a3qx-jqyy) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/a3qx-jqyy/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/a3qx-jqyy/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | a3qx-jqyy |
| Name | Community Sponsorships |
| Attribution | Austin Energy |
| Category | Utility |
| Tags | community sponsorships, austin energy, energy, sponsors, support |
| Created | 2016-09-06T16:04:36Z |
| Publication Date | 2016-11-15T16:15:53Z |

## Description

Each year, Austin Energy participates in and sponsors events that support our local community. View the events and organizations that we sponsored, and amounts we contributed annually.

## Columns

```ls
| Included | Schema Type    | Field Name       | Name        | Data Type | Render Type |
| ======== | ============== | ================ | =========== | ========= | =========== |
| Yes      | time           | fiscal_year      | Fiscal Year | number    | number      |
| Yes      | series tag     | item_description | Entity      | text      | text        |
| Yes      | numeric metric | total_ytd        | Total YTD   | number    | number      |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:a3qx-jqyy d:2015-01-01T00:00:00.000Z t:item_description="Misc. Sponsorships" m:total_ytd=245536

series e:a3qx-jqyy d:2015-01-01T00:00:00.000Z t:item_description="Austin Public Library - Summer Reading Program" m:total_ytd=18000

series e:a3qx-jqyy d:2015-01-01T00:00:00.000Z t:item_description="African American Men & Boys Conference - Harvest Foundation" m:total_ytd=75000
```

## Meta Commands

```ls
metric m:total_ytd p:integer l:"Total YTD" t:dataTypeName=number

entity e:a3qx-jqyy l:"Community Sponsorships" t:attribution="Austin Energy" t:url=https://data.austintexas.gov/api/views/a3qx-jqyy

property e:a3qx-jqyy t:meta.view v:id=a3qx-jqyy v:category=Utility v:averageRating=0 v:name="Community Sponsorships" v:attribution="Austin Energy"

property e:a3qx-jqyy t:meta.view.license v:name="Public Domain"

property e:a3qx-jqyy t:meta.view.owner v:id=c433-zrb5 v:profileImageUrlMedium=/api/users/c433-zrb5/profile_images/THUMB v:profileImageUrlLarge=/api/users/c433-zrb5/profile_images/LARGE v:screenName="Sarah Lambert" v:profileImageUrlSmall=/api/users/c433-zrb5/profile_images/TINY v:displayName="Sarah Lambert"

property e:a3qx-jqyy t:meta.view.tableauthor v:id=3qbr-w2gj v:screenName="Elaine Lee" v:roleName=editor v:displayName="Elaine Lee"
```

## Top Records

```ls
| fiscal_year | item_description                                                               | total_ytd | 
| =========== | ============================================================================== | ========= | 
| 2015        | Misc. Sponsorships                                                             | 245536    | 
| 2015        | Austin Public Library - Summer Reading Program                                 | 18000     | 
| 2015        | African American Men & Boys Conference - Harvest Foundation                    | 75000     | 
| 2015        | Christmas Lighting, Service drops for sponsored events and banner installation | 27000     | 
| 2015        | Clean Air Force                                                                | 90000     | 
| 2015        | Grants for Technology Opportunities                                            | 175000    | 
| 2015        | AISD-Hispanic Futures Conference                                               | 45000     | 
| 2015        | Juneteenth                                                                     | 16000     | 
| 2015        | Sickle Cell Sponsorship                                                        | 86000     | 
| 2015        | Science Fest                                                                   | 60000     | 
```