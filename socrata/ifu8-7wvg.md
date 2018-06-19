# 2014 Elections - Top 10 Surplus (as of November 4, 2014)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2014-elections-top-10-surplus-as-of-november-4-2014-ae958) |
| Metadata | [Link](https://data.hawaii.gov/api/views/ifu8-7wvg) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/ifu8-7wvg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/ifu8-7wvg/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | ifu8-7wvg |
| Name | 2014 Elections - Top 10 Surplus (as of November 4, 2014) |
| Category | Community |
| Tags | campaign spending, elections |
| Created | 2015-01-13T21:55:23Z |
| Publication Date | 2015-01-14T00:58:02Z |

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type | Render Type |
| ======== | ============== | =============== | =============== | ========= | =========== |
| Yes      | series tag     | candidate_name  | Candidate Name  | text      | text        |
| Yes      | numeric metric | closing_cash    | Closing Cash    | money     | money       |
| Yes      | numeric metric | debts           | Debts           | money     | money       |
| Yes      | numeric metric | surplus_deficit | Surplus/Deficit | money     | money       |
| Yes      | series tag     | office          | Office          | text      | text        |
| Yes      | series tag     | status          | Status          | text      | text        |
| Yes      | series tag     | won             | Won             | text      | text        |
```

## Time Field

```ls
Value = 2014
Format & Zone = yyyy
```

## Data Commands

```ls
series e:ifu8-7wvg d:2014-01-01T00:00:00.000Z t:office=Governor t:status=Challenger t:candidate_name="Aiona, James (Duke)" t:won=N m:closing_cash=105199.98 m:debts=0 m:surplus_deficit=105199.98

series e:ifu8-7wvg d:2014-01-01T00:00:00.000Z t:office=Senate t:status=Incumbent t:candidate_name="Green, Josh" t:won=Y m:closing_cash=493438.4 m:debts=0 m:surplus_deficit=493438.4

series e:ifu8-7wvg d:2014-01-01T00:00:00.000Z t:office=Governor t:status=Challenger t:candidate_name="Ige, David" t:won=Y m:closing_cash=435029.95 m:debts=0 m:surplus_deficit=435029.95
```

## Meta Commands

```ls
metric m:closing_cash p:double l:"Closing Cash" t:dataTypeName=money

metric m:debts p:integer l:Debts t:dataTypeName=money

metric m:surplus_deficit p:double l:Surplus/Deficit t:dataTypeName=money

entity e:ifu8-7wvg l:"2014 Elections - Top 10 Surplus (as of November 4, 2014)" t:url=https://data.hawaii.gov/api/views/ifu8-7wvg

property e:ifu8-7wvg t:meta.view v:id=ifu8-7wvg v:category=Community v:averageRating=0 v:name="2014 Elections - Top 10 Surplus (as of November 4, 2014)"

property e:ifu8-7wvg t:meta.view.license v:name="Public Domain"

property e:ifu8-7wvg t:meta.view.owner v:id=g6c2-gabj v:profileImageUrlMedium=/api/users/g6c2-gabj/profile_images/THUMB v:profileImageUrlLarge=/api/users/g6c2-gabj/profile_images/LARGE v:screenName="Hawaii Campaign Spending Commission" v:profileImageUrlSmall=/api/users/g6c2-gabj/profile_images/TINY v:displayName="Hawaii Campaign Spending Commission"

property e:ifu8-7wvg t:meta.view.tableauthor v:id=g6c2-gabj v:profileImageUrlMedium=/api/users/g6c2-gabj/profile_images/THUMB v:profileImageUrlLarge=/api/users/g6c2-gabj/profile_images/LARGE v:screenName="Hawaii Campaign Spending Commission" v:profileImageUrlSmall=/api/users/g6c2-gabj/profile_images/TINY v:roleName=editor v:displayName="Hawaii Campaign Spending Commission"
```

## Top Records

```ls
| candidate_name      | closing_cash | debts | surplus_deficit | office           | status     | won | 
| =================== | ============ | ===== | =============== | ================ | ========== | === | 
| Aiona, James (Duke) | 105199.98    | 0     | 105199.98       | Governor         | Challenger | N   | 
| Green, Josh         | 493438.4     | 0     | 493438.4        | Senate           | Incumbent  | Y   | 
| Ige, David          | 435029.95    | 0     | 435029.95       | Governor         | Challenger | Y   | 
| Kidani, Michelle    | 98812.8      | 0     | 98812.8         | Senate           | Incumbent  | Y   | 
| Martin, Ernest      | 320956.44    | 0     | 320956.44       | Honolulu Council | Incumbent  | Y   | 
| Arakawa, Alan       | 275089.74    | 0     | 275089.74       | Mayor            | Incumbent  | Y   | 
| Cachola, Romy       | 166156.31    | 0     | 166156.31       | House            | Incumbent  | Y   | 
| Shan, Tsutsui       | 165158.47    | 0     | 165158.47       | Lt. Governor     | Incumbent  | Y   | 
| Tsuji, Clifton      | 90627.5      | 56    | 90571.5         | House            | Incumbent  | Y   | 
| Solomon, Malama     | 89066.75     | 0     | 89066.75        | Senate           | Incumbent  | N   | 
```