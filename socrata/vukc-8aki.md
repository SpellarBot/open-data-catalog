# 2014 Elections - Top 10 Expenditures

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2014-elections-top-10-expenditures-3c600) |
| Metadata | [Link](https://data.hawaii.gov/api/views/vukc-8aki) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/vukc-8aki/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/vukc-8aki/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | vukc-8aki |
| Name | 2014 Elections - Top 10 Expenditures |
| Category | Community |
| Tags | campaign spending commission |
| Created | 2015-01-13T17:52:23Z |
| Publication Date | 2015-01-13T18:00:40Z |

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type | Render Type |
| ======== | ============== | ============== | ============== | ========= | =========== |
| Yes      | series tag     | candidate_name | Candidate Name | text      | text        |
| Yes      | numeric metric | expenditures   | Expenditures   | money     | money       |
| Yes      | series tag     | office         | Office         | text      | text        |
| Yes      | series tag     | status         | Status         | text      | text        |
| Yes      | series tag     | won            | Won            | text      | text        |
```

## Time Field

```ls
Value = 2014
Format & Zone = yyyy
```

## Data Commands

```ls
series e:vukc-8aki d:2014-01-01T00:00:00.000Z t:office=Governor t:status=Incumbent t:candidate_name="Abercrombie, Neil" t:won=N m:expenditures=5035283.12

series e:vukc-8aki d:2014-01-01T00:00:00.000Z t:office=Governor t:status=Challenger t:candidate_name="Ige, David" t:won=Y m:expenditures=1951059.54

series e:vukc-8aki d:2014-01-01T00:00:00.000Z t:office=Governor t:status=Challenger t:candidate_name="Aiona, James (Duke)" t:won=N m:expenditures=1554229.47
```

## Meta Commands

```ls
metric m:expenditures p:double l:Expenditures t:dataTypeName=money

entity e:vukc-8aki l:"2014 Elections - Top 10 Expenditures" t:url=https://data.hawaii.gov/api/views/vukc-8aki

property e:vukc-8aki t:meta.view v:id=vukc-8aki v:category=Community v:averageRating=0 v:name="2014 Elections - Top 10 Expenditures"

property e:vukc-8aki t:meta.view.license v:name="Public Domain"

property e:vukc-8aki t:meta.view.owner v:id=g6c2-gabj v:profileImageUrlMedium=/api/users/g6c2-gabj/profile_images/THUMB v:profileImageUrlLarge=/api/users/g6c2-gabj/profile_images/LARGE v:screenName="Hawaii Campaign Spending Commission" v:profileImageUrlSmall=/api/users/g6c2-gabj/profile_images/TINY v:displayName="Hawaii Campaign Spending Commission"

property e:vukc-8aki t:meta.view.tableauthor v:id=g6c2-gabj v:profileImageUrlMedium=/api/users/g6c2-gabj/profile_images/THUMB v:profileImageUrlLarge=/api/users/g6c2-gabj/profile_images/LARGE v:screenName="Hawaii Campaign Spending Commission" v:profileImageUrlSmall=/api/users/g6c2-gabj/profile_images/TINY v:roleName=editor v:displayName="Hawaii Campaign Spending Commission"
```

## Top Records

```ls
| candidate_name      | expenditures | office           | status     | won | 
| =================== | ============ | ================ | ========== | === | 
| Abercrombie, Neil   | 5035283.12   | Governor         | Incumbent  | N   | 
| Ige, David          | 1951059.54   | Governor         | Challenger | Y   | 
| Aiona, James (Duke) | 1554229.47   | Governor         | Challenger | N   | 
| Tsutsui, Shan       | 1184286.02   | Lt. Governor     | Incumbent  | Y   | 
| Arakawa, Alan       | 757865.1     | Mayor            | Incumbent  | Y   | 
| Hee, Clayton        | 707310.8     | Lt. Governor     | Challenger | N   | 
| Ahu, Elwin          | 309515.81    | Lt. Governor     | Challenger | N   | 
| Martin, Ernest      | 292377.57    | Honolulu Council | Incumbent  | Y   | 
| Hanneman, Mufi      | 284703.08    | Governor         | Challenger | N   | 
| Carvalho, Bernard   | 261484.11    | Mayor            | Incumbent  | Y   | 
```