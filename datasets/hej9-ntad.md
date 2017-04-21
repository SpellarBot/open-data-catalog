# SSMMA Electrical Aggregation

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ssmma-electrical-aggregation-16347) |
| Metadata | [Link](https://data.illinois.gov/api/views/hej9-ntad) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/hej9-ntad/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/hej9-ntad/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | hej9-ntad |
| Name | SSMMA Electrical Aggregation |
| Attribution | South Suburban Mayors and Managers Association |
| Category | Municipality |
| Tags | electric aggregation, statistical, planning |
| Created | 2012-11-27T20:41:36Z |
| Publication Date | 2012-11-27T20:42:34Z |

## Description

This dataset outlines Chicago Southland communities which adopted electrical aggregation legislation

## Columns

```ls
| Included | Schema Type    | Field Name | Name       | Data Type     | Render Type   |
| ======== | ============== | ========== | ========== | ============= | ============= |
| Yes      | series tag     | objectid   | OBJECTID   | text          | number        |
| Yes      | series tag     | name       | NAME       | text          | text          |
| Yes      | series tag     | type       | TYPE       | text          | text          |
| No       |                | st         | ST         | text          | text          |
| Yes      | numeric metric | shape_area | SHAPE_AREA | number        | number        |
| Yes      | numeric metric | shape_len  | SHAPE_LEN  | number        | number        |
| Yes      | series tag     | status     | Status     | text          | text          |
| Yes      | series tag     | supplier   | Supplier   | text          | text          |
| Yes      | numeric metric | rate       | Rate       | number        | number        |
| No       |                | contracten | ContractEn | calendar_date | calendar_date |
| Yes      | series tag     | serviceare | ServiceAre | text          | text          |
| Yes      | time           | referndumd | ReferndumD | calendar_date | calendar_date |
| Yes      | series tag     | editor     | Editor     | text          | text          |
| Yes      | numeric metric | propreitar | Propreitar | number        | text          |
| Yes      | series tag     | universali | UniversalI | text          | text          |
```

## Time Field

```ls
Value = referndumd
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = st,contracten
```

## Data Commands

```ls
series e:hej9-ntad d:2012-11-14T00:00:00.000Z t:serviceare="Commonwealth Edison" t:status="Referendum On Ballot" t:name="Chicago Heights" t:objectid=1 t:type=city m:shape_area=269948070.311 m:rate=0 m:shape_len=168494.505806

series e:hej9-ntad d:2012-11-14T00:00:00.000Z t:serviceare="Commonwealth Edison" t:status="Referendum On Ballot" t:name="Clarendon Hills" t:objectid=2 t:type=village m:shape_area=48369302.8524 m:rate=0 m:shape_len=33621.4231152

series e:hej9-ntad d:2012-03-14T00:00:00.000Z t:serviceare="Commonwealth Edison" t:editor=MJR t:status="Supplier Chosen" t:name=Bolingbrook t:objectid=14 t:type=village t:supplier="FirstEnergy Solutions" m:shape_area=582185154.008 m:rate=4.83 m:shape_len=331247.532673
```

## Meta Commands

```ls
metric m:shape_area p:double l:SHAPE_AREA t:dataTypeName=number

metric m:shape_len p:double l:SHAPE_LEN t:dataTypeName=number

metric m:rate p:float l:Rate t:dataTypeName=number

metric m:propreitar p:integer l:Propreitar t:dataTypeName=number

entity e:hej9-ntad l:"SSMMA Electrical Aggregation" t:attribution="South Suburban Mayors and Managers Association" t:url=https://data.illinois.gov/api/views/hej9-ntad

property e:hej9-ntad t:meta.view v:id=hej9-ntad v:category=Municipality v:attributionLink=http://www.ssmma.org v:averageRating=0 v:name="SSMMA Electrical Aggregation" v:attribution="South Suburban Mayors and Managers Association"

property e:hej9-ntad t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:hej9-ntad t:meta.view.owner v:id=p88s-rkzf v:profileImageUrlMedium=/api/users/p88s-rkzf/profile_images/THUMB v:profileImageUrlLarge=/api/users/p88s-rkzf/profile_images/LARGE v:screenName=mrizzitiello v:profileImageUrlSmall=/api/users/p88s-rkzf/profile_images/TINY v:displayName=mrizzitiello

property e:hej9-ntad t:meta.view.tableauthor v:id=74c3-ka9x v:profileImageUrlMedium=/api/users/74c3-ka9x/profile_images/THUMB v:profileImageUrlLarge=/api/users/74c3-ka9x/profile_images/LARGE v:screenName="Rey de Castro" v:profileImageUrlSmall=/api/users/74c3-ka9x/profile_images/TINY v:roleName=publisher v:displayName="Rey de Castro"
```

## Top Records

```ls
| objectid | name            | type    | st | shape_area    | shape_len     | status               | supplier              | rate | contracten          | serviceare          | referndumd          | editor | propreitar | universali | 
| ======== | =============== | ======= | == | ============= | ============= | ==================== | ===================== | ==== | =================== | =================== | =================== | ====== | ========== | ========== | 
| 1        | Chicago Heights | city    | IL | 269948070.311 | 168494.505806 | Referendum On Ballot |                       | 0    |                     | Commonwealth Edison | 2012-11-14T00:00:00 |        |            |            | 
| 2        | Clarendon Hills | village | IL | 48369302.8524 | 33621.4231152 | Referendum On Ballot |                       | 0    |                     | Commonwealth Edison | 2012-11-14T00:00:00 |        |            |            | 
| 14       | Bolingbrook     | village | IL | 582185154.008 | 331247.532673 | Supplier Chosen      | FirstEnergy Solutions | 4.83 | 2014-10-15T00:00:00 | Commonwealth Edison | 2012-03-14T00:00:00 | MJR    |            |            | 
| 71       | North Riverside | village | IL | 43179313.6456 | 43124.9829378 | Referendum On Ballot |                       | 0    |                     | Commonwealth Edison | 2012-11-14T00:00:00 |        |            |            | 
| 72       | La Grange Park  | village | IL | 62814296.2346 | 40583.3816057 | Supplier Chosen      | FirstEnergy Solutions | 4.93 | 2014-09-10T00:00:00 | Commonwealth Edison | 2012-03-14T00:00:00 |        |            |            | 
| 73       | Riverside       | village | IL | 55412095.4773 | 36724.1217365 | Supplier Chosen      | Direct Energy         | 4.88 | 2014-07-09T00:00:00 | Commonwealth Edison | 2012-03-14T00:00:00 |        |            |            | 
| 74       | Brookfield      | village | IL | 85699322.9547 | 58695.4420407 | Supplier Chosen      | FirstEnergy Solutions | 4.85 | 2014-07-16T00:00:00 | Commonwealth Edison | 2012-03-14T00:00:00 | MJR    |            |            | 
| 75       | Stickney        | village | IL | 54915283.7569 | 45106.578209  | Referendum On Ballot |                       | 4.67 | 2014-08-13T00:00:00 | Commonwealth Edison | 2012-11-14T00:00:00 |        |            |            | 
| 76       | Lyons           | village | IL | 62938571.6425 | 45899.3769558 | No                   |                       | 0    |                     |                     |                     |        |            |            | 
| 77       | Western Springs | village | IL | 73217150.1974 | 39679.7738619 | No                   |                       | 0    |                     |                     |                     |        |            |            | 
```