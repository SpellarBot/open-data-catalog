# 2013 Proposed Budget, FTEs, All Funds, By Department

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2013-proposed-budget-ftes-all-funds-by-department-d42bb) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/vra5-hjw9) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/vra5-hjw9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/vra5-hjw9/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | vra5-hjw9 |
| Name | 2013 Proposed Budget, FTEs, All Funds, By Department |
| Attribution | King County Executive |
| Category | Budget |
| Tags | budget, 2013, budget2013 |
| Created | 2012-09-23T21:01:28Z |
| Publication Date | 2012-09-23T21:05:59Z |

## Description

King County budget proposed September 2012 by Executive for 2013, FTEs, all funds, broken down by department. *Dual reporting with Superior Court and Executive See http://www.kingcounty.gov/budget for more.

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                 | Data Type | Render Type |
| ======== | ============== | ==================== | ==================== | ========= | =========== |
| Yes      | series tag     | agency_type          | Agency type          | text      | text        |
| Yes      | series tag     | agency_or_department | Agency or Department | text      | text        |
| Yes      | numeric metric | adopted_1            | 2010 Adopted         | number    | number      |
| Yes      | numeric metric | adopted_2            | 2011 Adopted         | number    | number      |
| Yes      | numeric metric | adopted_3            | 2012 Adopted         | number    | number      |
| Yes      | numeric metric | proposed_1           | 2013 Proposed        | number    | number      |
| Yes      | numeric metric | proposed_2           | 2014 Proposed        | number    | number      |
| Yes      | numeric metric | fte_change_2013_2012 | FTE Change 2013-2012 | number    | number      |
| Yes      | numeric metric | change               | % Change             | percent   | percent     |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Data Commands

```ls
series e:vra5-hjw9 d:2013-01-01T00:00:00.000Z t:agency_or_department=Assessor t:agency_type="Elected Agencies" m:change=0 m:proposed_1=212 m:adopted_1=224 m:proposed_2=212 m:adopted_2=208 m:fte_change_2013_2012=0 m:adopted_3=212

series e:vra5-hjw9 d:2013-01-01T00:00:00.000Z t:agency_or_department="District Court" t:agency_type="Elected Agencies" m:change=2.7 m:proposed_1=259 m:adopted_1=256.75 m:proposed_2=259 m:adopted_2=252.95 m:fte_change_2013_2012=7 m:adopted_3=252

series e:vra5-hjw9 d:2013-01-01T00:00:00.000Z t:agency_or_department=Elections t:agency_type="Elected Agencies" m:change=6.5 m:proposed_1=68.43 m:adopted_1=63 m:proposed_2=68.43 m:adopted_2=62 m:fte_change_2013_2012=4.43 m:adopted_3=64
```

## Meta Commands

```ls
metric m:adopted_1 p:float l:"2010 Adopted" t:dataTypeName=number

metric m:adopted_2 p:float l:"2011 Adopted" t:dataTypeName=number

metric m:adopted_3 p:float l:"2012 Adopted" t:dataTypeName=number

metric m:proposed_1 p:double l:"2013 Proposed" t:dataTypeName=number

metric m:proposed_2 p:float l:"2014 Proposed" t:dataTypeName=number

metric m:fte_change_2013_2012 p:float l:"FTE Change 2013-2012" t:dataTypeName=number

metric m:change p:float l:"% Change" t:dataTypeName=percent

entity e:vra5-hjw9 l:"2013 Proposed Budget, FTEs, All Funds, By Department" t:attribution="King County Executive" t:url=https://data.kingcounty.gov/api/views/vra5-hjw9

property e:vra5-hjw9 t:meta.view v:id=vra5-hjw9 v:category=Budget v:attributionLink=http://www.kingcounty.gov/budget v:averageRating=0 v:name="2013 Proposed Budget, FTEs, All Funds, By Department" v:attribution="King County Executive"

property e:vra5-hjw9 t:meta.view.license v:name="Public Domain"

property e:vra5-hjw9 t:meta.view.owner v:id=7ja6-sv4x v:profileImageUrlMedium=/api/users/7ja6-sv4x/profile_images/THUMB v:profileImageUrlLarge=/api/users/7ja6-sv4x/profile_images/LARGE v:screenName="King County Open Data admin" v:profileImageUrlSmall=/api/users/7ja6-sv4x/profile_images/TINY v:lastNotificationSeenAt=1492197205 v:displayName="King County Open Data admin"

property e:vra5-hjw9 t:meta.view.tableauthor v:id=7ja6-sv4x v:profileImageUrlMedium=/api/users/7ja6-sv4x/profile_images/THUMB v:profileImageUrlLarge=/api/users/7ja6-sv4x/profile_images/LARGE v:screenName="King County Open Data admin" v:profileImageUrlSmall=/api/users/7ja6-sv4x/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1492197205 v:displayName="King County Open Data admin"
```

## Top Records

```ls
| agency_type        | agency_or_department         | adopted_1 | adopted_2 | adopted_3 | proposed_1 | proposed_2 | fte_change_2013_2012 | change | 
| ================== | ============================ | ========= | ========= | ========= | ========== | ========== | ==================== | ====== | 
| Elected Agencies   | Assessor                     | 224       | 208       | 212       | 212        | 212        | 0                    | 0.0    | 
| Elected Agencies   | District Court               | 256.75    | 252.95    | 252       | 259        | 259        | 7                    | 2.7    | 
| Elected Agencies   | Elections                    | 63        | 62        | 64        | 68.43      | 68.43      | 4.43                 | 6.5    | 
| Elected Agencies   | Legislative Agencies         | 153       | 143       | 144       | 144        | 144        | 0                    | 0.0    | 
| Elected Agencies   | Prosecuting Attorney         | 488.05    | 466.65    | 471.15    | 465.15     | 465.15     | -6                   | -1.3   | 
| Elected Agencies   | Sheriff                      | 1119      | 1095.8    | 1059.8    | 1058.25    | 1058.25    | -1.55                | -0.1   | 
| Elected Agencies   | Superior Court               | 387.65    | 384.35    | 376.6     | 372.3      | 372.3      | -4.3                 | -1.2   | 
| Executive Agencies | County Executive             | 81        | 85.5      | 89.5      | 115.6      | 115.6      | 26.1                 | 30.5   | 
| Executive Agencies | Adult and Juvenile Detention | 1007.21   | 951.5     | 939.5     | 891.72     | 891.72     | -47.78               | -5.0   | 
| Executive Agencies | Community & Human Services   | 332.08    | 332.43    | 301.48    | 307.07     | 305.07     | 5.59                 | 1.7    | 
```