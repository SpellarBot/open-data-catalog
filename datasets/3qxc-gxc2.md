# Iowa Aging Services Consumer Counts by Fiscal Year, Age Group, and Service

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/iowa-aging-services-consumer-counts-by-fiscal-year-age-group-and-service) |
| Metadata | [Link](https://data.iowa.gov/api/views/3qxc-gxc2) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/3qxc-gxc2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/3qxc-gxc2/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | 3qxc-gxc2 |
| Name | Iowa Aging Services Consumer Counts by Fiscal Year, Age Group, and Service |
| Attribution | Iowa Department on Aging and Area Agencies on Aging, Iowa Aging Information System |
| Category | Health |
| Tags | aging, services, gender, race, ethnicity, consumers |
| Created | 2014-11-10T20:25:17Z |
| Publication Date | 2016-10-06T13:37:12Z |

## Description

Data provides consumer counts for services provided to aging citizens of Iowa funded through federal and state programs starting in 2009 and is updated annually.  It includes breakdowns for gender, race and ethnicity, those in rural areas and designated as being in poverty.

## Columns

```ls
| Included | Schema Type    | Field Name                          | Name                                | Data Type | Render Type |
| ======== | ============== | =================================== | =================================== | ========= | =========== |
| Yes      | time           | year                                | Fiscal Year                         | number    | number      |
| Yes      | series tag     | age_group                           | Age Group                           | text      | text        |
| Yes      | series tag     | service                             | Service                             | text      | text        |
| Yes      | numeric metric | consumers                           | Consumers                           | number    | number      |
| Yes      | numeric metric | male_consumers                      | Male Consumers                      | number    | number      |
| Yes      | numeric metric | female_consumers                    | Female Consumers                    | number    | number      |
| Yes      | numeric metric | consumers_in_rural_areas            | Consumers in Rural Areas            | number    | number      |
| Yes      | numeric metric | conumsers_living_alone              | Conumsers Living Alone              | number    | number      |
| Yes      | numeric metric | consumers_in_poverty                | Consumers in Poverty                | number    | number      |
| Yes      | numeric metric | hispanic_consumers                  | Hispanic Consumers                  | number    | number      |
| Yes      | numeric metric | non_hispanic_consumers              | Non-Hispanic Consumers              | number    | number      |
| Yes      | numeric metric | white_not_hispanic_consumers        | White, Not Hispanic Consumers       | number    | number      |
| Yes      | numeric metric | white_hispanic_consumers            | White, Hispanic Consumers           | number    | number      |
| Yes      | numeric metric | native_american_consumers           | Native American Consumers           | number    | number      |
| Yes      | numeric metric | asian_consumers                     | Asian Consumers                     | number    | number      |
| Yes      | numeric metric | african_american_consumers          | African American Consumers          | number    | number      |
| Yes      | numeric metric | hawaiian_pacific_islander_consumers | Hawaiian Pacific Islander Consumers | number    | number      |
| Yes      | numeric metric | consumers_other_race                | Consumers - Other Race              | number    | number      |
| Yes      | numeric metric | consumers_two_or_more_races         | Consumers - Two or More Races       | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:3qxc-gxc2 d:2009-01-01T00:00:00.000Z t:age_group="Age 60-74" t:service="Personal Care" m:male_consumers=13 m:consumers_two_or_more_races=1 m:asian_consumers=0 m:consumers=70 m:african_american_consumers=3 m:white_not_hispanic_consumers=59 m:hispanic_consumers=0 m:native_american_consumers=0 m:conumsers_living_alone=53 m:consumers_in_rural_areas=30 m:hawaiian_pacific_islander_consumers=0 m:white_hispanic_consumers=0 m:consumers_in_poverty=45 m:female_consumers=56 m:consumers_other_race=0 m:non_hispanic_consumers=63

series e:3qxc-gxc2 d:2009-01-01T00:00:00.000Z t:age_group="Age 75-84" t:service="Personal Care" m:male_consumers=12 m:consumers_two_or_more_races=0 m:asian_consumers=0 m:consumers=126 m:african_american_consumers=4 m:white_not_hispanic_consumers=111 m:hispanic_consumers=1 m:native_american_consumers=0 m:conumsers_living_alone=80 m:consumers_in_rural_areas=79 m:hawaiian_pacific_islander_consumers=0 m:white_hispanic_consumers=1 m:consumers_in_poverty=49 m:female_consumers=109 m:consumers_other_race=0 m:non_hispanic_consumers=118

series e:3qxc-gxc2 d:2009-01-01T00:00:00.000Z t:age_group="Age 85+" t:service="Personal Care" m:male_consumers=26 m:consumers_two_or_more_races=0 m:asian_consumers=0 m:consumers=188 m:african_american_consumers=3 m:white_not_hispanic_consumers=163 m:hispanic_consumers=1 m:native_american_consumers=0 m:conumsers_living_alone=137 m:consumers_in_rural_areas=144 m:hawaiian_pacific_islander_consumers=0 m:white_hispanic_consumers=1 m:consumers_in_poverty=82 m:female_consumers=160 m:consumers_other_race=0 m:non_hispanic_consumers=167
```

## Meta Commands

```ls
metric m:consumers p:integer l:Consumers t:dataTypeName=number

metric m:male_consumers p:integer l:"Male Consumers" t:dataTypeName=number

metric m:female_consumers p:integer l:"Female Consumers" t:dataTypeName=number

metric m:consumers_in_rural_areas p:integer l:"Consumers in Rural Areas" t:dataTypeName=number

metric m:conumsers_living_alone p:integer l:"Conumsers Living Alone" t:dataTypeName=number

metric m:consumers_in_poverty p:integer l:"Consumers in Poverty" t:dataTypeName=number

metric m:hispanic_consumers p:integer l:"Hispanic Consumers" t:dataTypeName=number

metric m:non_hispanic_consumers p:integer l:"Non-Hispanic Consumers" t:dataTypeName=number

metric m:white_not_hispanic_consumers p:integer l:"White, Not Hispanic Consumers" t:dataTypeName=number

metric m:white_hispanic_consumers p:integer l:"White, Hispanic Consumers" t:dataTypeName=number

metric m:native_american_consumers p:integer l:"Native American Consumers" t:dataTypeName=number

metric m:asian_consumers p:integer l:"Asian Consumers" t:dataTypeName=number

metric m:african_american_consumers p:integer l:"African American Consumers" t:dataTypeName=number

metric m:hawaiian_pacific_islander_consumers p:integer l:"Hawaiian Pacific Islander Consumers" t:dataTypeName=number

metric m:consumers_other_race p:integer l:"Consumers - Other Race" t:dataTypeName=number

metric m:consumers_two_or_more_races p:integer l:"Consumers - Two or More Races" t:dataTypeName=number

entity e:3qxc-gxc2 l:"Iowa Aging Services Consumer Counts by Fiscal Year, Age Group, and Service" t:attribution="Iowa Department on Aging and Area Agencies on Aging, Iowa Aging Information System" t:url=https://data.iowa.gov/api/views/3qxc-gxc2

property e:3qxc-gxc2 t:meta.view v:id=3qxc-gxc2 v:category=Health v:averageRating=0 v:name="Iowa Aging Services Consumer Counts by Fiscal Year, Age Group, and Service" v:attribution="Iowa Department on Aging and Area Agencies on Aging, Iowa Aging Information System"

property e:3qxc-gxc2 t:meta.view.license v:name="Public Domain"

property e:3qxc-gxc2 t:meta.view.owner v:id=nmiv-8f6w v:profileImageUrlMedium=/api/users/nmiv-8f6w/profile_images/THUMB v:profileImageUrlLarge=/api/users/nmiv-8f6w/profile_images/LARGE v:screenName="Iowa Department on Aging" v:profileImageUrlSmall=/api/users/nmiv-8f6w/profile_images/TINY v:displayName="Iowa Department on Aging"

property e:3qxc-gxc2 t:meta.view.tableauthor v:id=nmiv-8f6w v:profileImageUrlMedium=/api/users/nmiv-8f6w/profile_images/THUMB v:profileImageUrlLarge=/api/users/nmiv-8f6w/profile_images/LARGE v:screenName="Iowa Department on Aging" v:profileImageUrlSmall=/api/users/nmiv-8f6w/profile_images/TINY v:roleName=publisher v:displayName="Iowa Department on Aging"
```

## Top Records

```ls
| year | age_group | service              | consumers | male_consumers | female_consumers | consumers_in_rural_areas | conumsers_living_alone | consumers_in_poverty | hispanic_consumers | non_hispanic_consumers | white_not_hispanic_consumers | white_hispanic_consumers | native_american_consumers | asian_consumers | african_american_consumers | hawaiian_pacific_islander_consumers | consumers_other_race | consumers_two_or_more_races | 
| ==== | ========= | ==================== | ========= | ============== | ================ | ======================== | ====================== | ==================== | ================== | ====================== | ============================ | ======================== | ========================= | =============== | ========================== | =================================== | ==================== | =========================== | 
| 2009 | Age 60-74 | Personal Care        | 70        | 13             | 56               | 30                       | 53                     | 45                   | 0                  | 63                     | 59                           | 0                        | 0                         | 0               | 3                          | 0                                   | 0                    | 1                           | 
| 2009 | Age 75-84 | Personal Care        | 126       | 12             | 109              | 79                       | 80                     | 49                   | 1                  | 118                    | 111                          | 1                        | 0                         | 0               | 4                          | 0                                   | 0                    | 0                           | 
| 2009 | Age 85+   | Personal Care        | 188       | 26             | 160              | 144                      | 137                    | 82                   | 1                  | 167                    | 163                          | 1                        | 0                         | 0               | 3                          | 0                                   | 0                    | 0                           | 
| 2009 | Age 60-74 | Homemaker            | 310       | 70             | 240              | 191                      | 250                    | 163                  | 0                  | 276                    | 266                          | 0                        | 0                         | 0               | 8                          | 2                                   | 0                    | 2                           | 
| 2009 | Age 75-84 | Homemaker            | 472       | 92             | 373              | 341                      | 364                    | 180                  | 1                  | 437                    | 424                          | 1                        | 0                         | 2               | 7                          | 1                                   | 0                    | 1                           | 
| 2009 | Age 85+   | Homemaker            | 515       | 79             | 434              | 410                      | 433                    | 218                  | 1                  | 485                    | 475                          | 1                        | 1                         | 0               | 7                          | 1                                   | 0                    | 2                           | 
| 2009 | Age 60-74 | Chore                | 621       | 157            | 464              | 290                      | 455                    | 363                  | 16                 | 577                    | 510                          | 13                       | 2                         | 6               | 56                         | 1                                   | 0                    | 6                           | 
| 2009 | Age 75-84 | Chore                | 589       | 119            | 469              | 373                      | 421                    | 310                  | 12                 | 562                    | 511                          | 10                       | 1                         | 1               | 38                         | 0                                   | 0                    | 9                           | 
| 2009 | Age 85+   | Chore                | 350       | 50             | 296              | 237                      | 275                    | 189                  | 9                  | 333                    | 316                          | 8                        | 0                         | 0               | 17                         | 0                                   | 0                    | 1                           | 
| 2009 | Age 60-74 | Home Delivered Meals | 3061      | 1098           | 1925             | 1733                     | 1894                   | 1038                 | 18                 | 2552                   | 2417                         | 15                       | 14                        | 7               | 77                         | 1                                   | 0                    | 37                          | 
```