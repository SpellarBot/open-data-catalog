# 2011 General - Election Results (final daily)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/election-results-final-daily-november-2011-general-be715) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/z3tv-8syp) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/z3tv-8syp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/z3tv-8syp/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | z3tv-8syp |
| Name | 2011 General - Election Results (final daily) |
| Attribution | King County Elections |
| Category | Election results |
| Tags | 2011, 2011 general, general, elections, results |
| Created | 2011-11-05T01:02:34Z |
| Publication Date | 2011-11-29T22:56:45Z |

## Description

November 2011 general election; final daily results report.

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type | Render Type |
| ======== | ============== | ======================= | ======================= | ========= | =========== |
| Yes      | series tag     | race                    | Race                    | text      | text        |
| Yes      | numeric metric | registered_voters       | Registered voters       | number    | number      |
| Yes      | numeric metric | votes_cast_in_this_race | Votes cast in this race | number    | number      |
| Yes      | series tag     | choice                  | Choice                  | text      | text        |
| Yes      | numeric metric | votes                   | Votes                   | number    | number      |
| Yes      | numeric metric | percent                 | Percent                 | percent   | percent     |
```

## Time Field

```ls
Value = 2011
Format & Zone = yyyy
```

## Data Commands

```ls
series e:z3tv-8syp d:2011-01-01T00:00:00.000Z t:choice=YES t:race="Proposed by Initiative Petition Initiative Measure No. 1125" m:registered_voters=1082929 m:percent=36.47 m:votes=200793 m:votes_cast_in_this_race=564331

series e:z3tv-8syp d:2011-01-01T00:00:00.000Z t:choice=NO t:race="Proposed by Initiative Petition Initiative Measure No. 1125" m:registered_voters=1082929 m:percent=63.52 m:votes=349677 m:votes_cast_in_this_race=564331

series e:z3tv-8syp d:2011-01-01T00:00:00.000Z t:choice=YES t:race="Proposed by Initiative Petition Initiative Measure No. 1163" m:registered_voters=1082929 m:percent=63.24 m:votes=345652 m:votes_cast_in_this_race=564331
```

## Meta Commands

```ls
metric m:registered_voters p:float l:"Registered voters" t:dataTypeName=number

metric m:votes_cast_in_this_race p:integer l:"Votes cast in this race" t:dataTypeName=number

metric m:votes p:integer l:Votes t:dataTypeName=number

metric m:percent p:float l:Percent t:dataTypeName=percent

entity e:z3tv-8syp l:"2011 General - Election Results (final daily)" t:attribution="King County Elections" t:url=https://data.kingcounty.gov/api/views/z3tv-8syp

property e:z3tv-8syp t:meta.view v:id=z3tv-8syp v:category="Election results" v:attributionLink=http://www.kingcounty.gov/elections/ v:averageRating=0 v:name="2011 General - Election Results (final daily)" v:attribution="King County Elections"

property e:z3tv-8syp t:meta.view.license v:name="Public Domain"

property e:z3tv-8syp t:meta.view.owner v:id=2gzv-6b6z v:profileImageUrlMedium=/api/users/2gzv-6b6z/profile_images/THUMB v:profileImageUrlLarge=/api/users/2gzv-6b6z/profile_images/LARGE v:screenName="King County Webteam" v:profileImageUrlSmall=/api/users/2gzv-6b6z/profile_images/TINY v:displayName="King County Webteam"

property e:z3tv-8syp t:meta.view.tableauthor v:id=2gzv-6b6z v:profileImageUrlMedium=/api/users/2gzv-6b6z/profile_images/THUMB v:profileImageUrlLarge=/api/users/2gzv-6b6z/profile_images/LARGE v:screenName="King County Webteam" v:profileImageUrlSmall=/api/users/2gzv-6b6z/profile_images/TINY v:roleName=administrator v:displayName="King County Webteam"
```

## Top Records

```ls
| race                                                                                                           | registered_voters | votes_cast_in_this_race | choice   | votes  | percent | 
| ============================================================================================================== | ================= | ======================= | ======== | ====== | ======= | 
| Proposed by Initiative Petition Initiative Measure No. 1125                                                    | 1082929.00        | 564331                  | YES      | 200793 | 36.47   | 
| Proposed by Initiative Petition Initiative Measure No. 1125                                                    | 1082929.00        | 564331                  | NO       | 349677 | 63.52   | 
| Proposed by Initiative Petition Initiative Measure No. 1163                                                    | 1082929.00        | 564331                  | YES      | 345652 | 63.24   | 
| Proposed by Initiative Petition Initiative Measure No. 1163                                                    | 1082929.00        | 564331                  | NO       | 200862 | 36.75   | 
| Proposed by Initiative Petition Initiative Measure No. 1183                                                    | 1082929.00        | 564331                  | YES      | 330611 | 59.01   | 
| Proposed by Initiative Petition Initiative Measure No. 1183                                                    | 1082929.00        | 564331                  | NO       | 229591 | 40.98   | 
| Proposed to the People by the Legislature Amendment to the State Constitution Senate Joint Resolution No. 8205 | 1082929.00        | 564331                  | APPROVED | 427034 | 80.84   | 
| Proposed to the People by the Legislature Amendment to the State Constitution Senate Joint Resolution No. 8205 | 1082929.00        | 564331                  | REJECTED | 101165 | 19.15   | 
| Proposed to the People by the Legislature Amendment to the State Constitution Senate Joint Resolution No. 8206 | 1082929.00        | 564331                  | APPROVED | 339833 | 66.58   | 
| Proposed to the People by the Legislature Amendment to the State Constitution Senate Joint Resolution No. 8206 | 1082929.00        | 564331                  | REJECTED | 170505 | 33.41   | 
```