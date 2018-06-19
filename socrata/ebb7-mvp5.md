# DSNY Monthly Tonnage Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dsny-monthly-tonnage-data-a0e7a) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/ebb7-mvp5) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/ebb7-mvp5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/ebb7-mvp5/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | ebb7-mvp5 |
| Name | DSNY Monthly Tonnage Data |
| Attribution | Department of Sanitation (DSNY) |
| Category | City Government |
| Tags | dsny monthly tonnage data, dsny |
| Created | 2013-11-22T16:41:29Z |
| Publication Date | 2017-04-08T18:36:24Z |

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type | Render Type |
| ======== | ============== | =================== | =================== | ========= | =========== |
| No       | time           | :updated_at         | updated_at          | meta_data | meta_data   |
| Yes      | series tag     | month               | MONTH               | text      | text        |
| Yes      | series tag     | borough             | BOROUGH             | text      | text        |
| Yes      | series tag     | communitydistrict   | COMMUNITYDISTRICT   | text      | text        |
| Yes      | numeric metric | refusetonscollected | REFUSETONSCOLLECTED | number    | number      |
| Yes      | numeric metric | papertonscollected  | PAPERTONSCOLLECTED  | number    | number      |
| Yes      | numeric metric | mgptonscollected    | MGPTONSCOLLECTED    | number    | number      |
| Yes      | series tag     | borough_id          | BOROUGH_ID          | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:ebb7-mvp5 d:2013-11-22T08:41:32.000Z t:communitydistrict=13 t:month="2013 / 10" t:borough=Queens t:borough_id=4 m:papertonscollected=505.94 m:mgptonscollected=573.44 m:refusetonscollected=5189.25

series e:ebb7-mvp5 d:2013-11-22T08:41:32.000Z t:communitydistrict=07 t:month="2013 / 10" t:borough=Brooklyn t:borough_id=3 m:papertonscollected=414.57 m:mgptonscollected=319.11 m:refusetonscollected=3341.37

series e:ebb7-mvp5 d:2013-11-22T08:41:32.000Z t:communitydistrict=02 t:month="2013 / 10" t:borough=Bronx t:borough_id=2 m:papertonscollected=72.33 m:mgptonscollected=92.12 m:refusetonscollected=1545.83
```

## Meta Commands

```ls
metric m:refusetonscollected p:float l:REFUSETONSCOLLECTED t:dataTypeName=number

metric m:papertonscollected p:float l:PAPERTONSCOLLECTED t:dataTypeName=number

metric m:mgptonscollected p:float l:MGPTONSCOLLECTED t:dataTypeName=number

entity e:ebb7-mvp5 l:"DSNY Monthly Tonnage Data" t:attribution="Department of Sanitation (DSNY)" t:url=https://data.cityofnewyork.us/api/views/ebb7-mvp5

property e:ebb7-mvp5 t:meta.view v:id=ebb7-mvp5 v:category="City Government" v:averageRating=0 v:name="DSNY Monthly Tonnage Data" v:attribution="Department of Sanitation (DSNY)"

property e:ebb7-mvp5 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:ebb7-mvp5 t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | month     | borough   | communitydistrict | refusetonscollected | papertonscollected | mgptonscollected | borough_id | 
| =========== | ========= | ========= | ================= | =================== | ================== | ================ | ========== | 
| 1385109692  | 2013 / 10 | Queens    | 13                | 5189.25             | 505.94             | 573.44           | 4          | 
| 1385109692  | 2013 / 10 | Brooklyn  | 07                | 3341.37             | 414.57             | 319.11           | 3          | 
| 1385109692  | 2013 / 10 | Bronx     | 02                | 1545.83             | 72.33              | 92.12            | 2          | 
| 1385109692  | 2013 / 10 | Queens    | 10                | 3785.36             | 375.29             | 343.98           | 4          | 
| 1385109692  | 2013 / 10 | Manhattan | 02                | 2167.47             | 446.13             | 294.68           | 1          | 
| 1385109692  | 2013 / 10 | Bronx     | 12                | 3690.27             | 339.09             | 381.15           | 2          | 
| 1385109692  | 2013 / 10 | Brooklyn  | 15                | 4670.1              | 617.78             | 379.51           | 3          | 
| 1385109692  | 2013 / 10 | Bronx     | 08                | 2416.36             | 335.21             | 270.49           | 2          | 
| 1385109692  | 2013 / 10 | Queens    | 03                | 4729.29             | 370.45             | 357.43           | 4          | 
| 1385109692  | 2013 / 10 | Queens    | 09                | 4031.75             | 414.4              | 377.57           | 4          | 
```