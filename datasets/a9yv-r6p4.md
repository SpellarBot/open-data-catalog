# Communities potentially eligible for Community Wastewater Management Program funds

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/communities-potentially-eligible-for-community-wastewater-management-program-funds-dd45f) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/a9yv-r6p4) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/a9yv-r6p4/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/a9yv-r6p4/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | a9yv-r6p4 |
| Name | Communities potentially eligible for Community Wastewater Management Program funds |
| Attribution | Department of Environmental Protection (DEP) |
| Category | Environment |
| Tags | dep, department of environmental protection, environment, wastewater, wastewater management, community wastewater management program funds, communities potentially eligible for community wastewate... |
| Created | 2013-02-01T15:18:31Z |
| Publication Date | 2013-06-21T19:45:48Z |

## Description

List of Communities potentially eligible for Community Wastewater Management Program funds in priority order

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type | Render Type |
| ======== | ============== | ============== | ============== | ========= | =========== |
| No       | time           | :updated_at    | updated_at     | meta_data | meta_data   |
| Yes      | numeric metric | priority       | Priority       | number    | number      |
| Yes      | series tag     | community_name | Community Name | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:a9yv-r6p4 d:2013-02-01T07:18:33.000Z t:community_name="Bloomville, Towns of Kortright & Stamford (Delaware County)" m:priority=1

series e:a9yv-r6p4 d:2013-02-01T07:18:33.000Z t:community_name="Boiceville, Town of Olive (Ulster County)" m:priority=2

series e:a9yv-r6p4 d:2013-02-01T07:18:33.000Z t:community_name="Hamden, Town of Hamden (Delaware County)" m:priority=3
```

## Meta Commands

```ls
metric m:priority p:integer l:Priority t:dataTypeName=number

entity e:a9yv-r6p4 l:"Communities potentially eligible for Community Wastewater Management Program funds" t:attribution="Department of Environmental Protection (DEP)" t:url=https://data.cityofnewyork.us/api/views/a9yv-r6p4

property e:a9yv-r6p4 t:meta.view v:id=a9yv-r6p4 v:category=Environment v:attributionLink=http://www.nyc.gov/html/dep/html/watershed_protection/community_wastewater_infrastructure.shtml v:averageRating=0 v:name="Communities potentially eligible for Community Wastewater Management Program funds" v:attribution="Department of Environmental Protection (DEP)"

property e:a9yv-r6p4 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:a9yv-r6p4 t:meta.view.tableauthor v:id=ya7g-926w v:screenName="Aakash Dalwani" v:displayName="Aakash Dalwani"
```

## Top Records

```ls
| :updated_at | priority | community_name                                                   | 
| =========== | ======== | ================================================================ | 
| 1359703113  | 1        | Bloomville, Towns of Kortright & Stamford (Delaware County)      | 
| 1359703113  | 2        | Boiceville, Town of Olive (Ulster County)                        | 
| 1359703113  | 3        | Hamden, Town of Hamden (Delaware County)                         | 
| 1359703113  | 4        | Delancey, Town of Hamden (Delaware County)                       | 
| 1359703113  | 5        | Bovina Center, Town of Bovina (Delaware County)                  | 
| 1359703113  | 6        | Ashland, Town of Ashland (Greene County)                         | 
| 1359703113  | 7        | Haines Falls, Town of Hunter (Greene County)                     | 
| 1359703113  | 8        | Trout Creek, Town of Tomkins (Delaware County)                   | 
| 1359703113  | 9        | Lexington, Town of Lexington (Greene County)                     | 
| 1359703113  | 10       | South Kortright, Towns of Kortright & Stamford (Delaware County) | 
```