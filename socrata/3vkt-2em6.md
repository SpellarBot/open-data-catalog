# SSMMA Cook County Population Growth By Municiplity And Waste Agency Jurisdiction

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ssmma-cook-county-population-growth-by-municiplity-and-waste-agency-jurisdiction-e3c0a) |
| Metadata | [Link](https://data.illinois.gov/api/views/3vkt-2em6) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/3vkt-2em6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/3vkt-2em6/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | 3vkt-2em6 |
| Name | SSMMA Cook County Population Growth By Municiplity And Waste Agency Jurisdiction |
| Attribution | South Suburban Mayors and Managers Association |
| Category | Municipality |
| Tags | statistical, census, planning, cook county, chicago southland |
| Created | 2012-11-27T18:03:27Z |
| Publication Date | 2012-11-27T19:07:19Z |

## Description

This dataset details the population growth of municipalities in Cook County, Illinois.

## Columns

```ls
| Included | Schema Type    | Field Name                  | Name                        | Data Type | Render Type |
| ======== | ============== | =========================== | =========================== | ========= | =========== |
| No       | time           | :updated_at                 | updated_at                  | meta_data | meta_data   |
| Yes      | series tag     | municipality                | Municipality                | text      | text        |
| Yes      | series tag     | waste_agency                | Waste Agency                | text      | text        |
| Yes      | numeric metric | total_population            | 2000 Total population       | number    | number      |
| Yes      | numeric metric | population                  | 2010 Population             | number    | number      |
| Yes      | numeric metric | population_change_2000_2010 | Population Change 2000-2010 | number    | number      |
| Yes      | numeric metric | percent_change              | Percent Change              | percent   | percent     |
| No       |                | location_1                  | Location 1                  | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = location_1
```

## Data Commands

```ls
series e:3vkt-2em6 d:2012-11-27T10:03:28.000Z t:waste_agency="separate entity" t:municipality=Chicago m:total_population=2895964 m:percent_change=-7.43 m:population_change_2000_2010=-200366 m:population=2695598

series e:3vkt-2em6 d:2012-11-27T10:03:28.000Z t:waste_agency=SSMMA t:municipality="Blue Island" m:total_population=23341 m:percent_change=1.54 m:population_change_2000_2010=365 m:population=23706

series e:3vkt-2em6 d:2012-11-27T10:03:28.000Z t:waste_agency=SSMMA t:municipality=Burnham m:total_population=4170 m:percent_change=0.86 m:population_change_2000_2010=36 m:population=4206
```

## Meta Commands

```ls
metric m:total_population p:integer l:"2000 Total population" t:dataTypeName=number

metric m:population p:integer l:"2010 Population" t:dataTypeName=number

metric m:population_change_2000_2010 p:integer l:"Population Change 2000-2010" t:dataTypeName=number

metric m:percent_change p:float l:"Percent Change" t:dataTypeName=percent

entity e:3vkt-2em6 l:"SSMMA Cook County Population Growth  By Municiplity And Waste Agency Jurisdiction" t:attribution="South Suburban Mayors and Managers Association" t:url=https://data.illinois.gov/api/views/3vkt-2em6

property e:3vkt-2em6 t:meta.view v:id=3vkt-2em6 v:category=Municipality v:attributionLink=http://www.ssmma.org v:averageRating=0 v:name="SSMMA Cook County Population Growth  By Municiplity And Waste Agency Jurisdiction" v:attribution="South Suburban Mayors and Managers Association"

property e:3vkt-2em6 t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:3vkt-2em6 t:meta.view.owner v:id=p88s-rkzf v:profileImageUrlMedium=/api/users/p88s-rkzf/profile_images/THUMB v:profileImageUrlLarge=/api/users/p88s-rkzf/profile_images/LARGE v:screenName=mrizzitiello v:profileImageUrlSmall=/api/users/p88s-rkzf/profile_images/TINY v:displayName=mrizzitiello

property e:3vkt-2em6 t:meta.view.tableauthor v:id=74c3-ka9x v:profileImageUrlMedium=/api/users/74c3-ka9x/profile_images/THUMB v:profileImageUrlLarge=/api/users/74c3-ka9x/profile_images/LARGE v:screenName="Rey de Castro" v:profileImageUrlSmall=/api/users/74c3-ka9x/profile_images/TINY v:roleName=publisher v:displayName="Rey de Castro"
```

## Top Records

```ls
| :updated_at | municipality       | waste_agency    | total_population | population | population_change_2000_2010 | percent_change | location_1                                                           | 
| =========== | ================== | =============== | ================ | ========== | =========================== | ============== | ==================================================================== | 
| 1354010608  | Chicago            | separate entity | 2895964          | 2695598    | -200366                     | -7.43          | Chicago, Illinois (41.88415000022252, -87.63241000012124)            | 
| 1354010608  | Blue Island        | SSMMA           | 23341            | 23706      | 365                         | 1.54           | Blue Island, Illinois (41.65522000020303, -87.68005999956915)        | 
| 1354010608  | Burnham            | SSMMA           | 4170             | 4206       | 36                          | 0.86           | Burnham, Illinois (41.63810000031492, -87.55554000037057)            | 
| 1354010608  | Calumet City       | SSMMA           | 38992            | 37042      | -1950                       | -5.26          | Calumet City, Illinois (41.615520000447816, -87.53108999970357)      | 
| 1354010608  | Calumet Park       | SSMMA           | 8569             | 7835       | -734                        | -9.37          | Calumet Park, Illinois (41.667620000063096, -87.65373999990095)      | 
| 1354010608  | Chicago Heights    | SSMMA           | 33045            | 30276      | -2769                       | -9.15          | Chicago Heights, Illinois (41.50196999991573, -87.64051999999788)    | 
| 1354010608  | Country Club Hills | SSMMA           | 16202            | 16541      | 339                         | 2.05           | Country Club Hills, Illinois (41.55713000034939, -87.71929000013324) | 
| 1354010608  | Dixmoor            | SSMMA           | 4110             | 3644       | -466                        | -12.79         | Dixmoor, Illinois (41.62626000019901, -87.65661999961316)            | 
| 1354010608  | Dolton             | SSMMA           | 25740            | 23153      | -2587                       | -11.17         | Dolton, Illinois (41.639500000125054, -87.60995000039208)            | 
| 1354010608  | East Hazel Crest   | SSMMA           | 1611             | 1543       | -68                         | -4.41          | East Hazel Crest, Illinois (41.5763499999527, -87.64850999973658)    | 
```