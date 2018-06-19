# DCEO IL Coal Mines

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dceo-il-coal-mines-c2410) |
| Metadata | [Link](https://data.illinois.gov/api/views/ws4h-cuji) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/ws4h-cuji/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/ws4h-cuji/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | ws4h-cuji |
| Name | DCEO IL Coal Mines |
| Category | Economics |
| Tags | coal mines |
| Created | 2012-01-27T21:50:37Z |
| Publication Date | 2012-01-27T21:51:35Z |

## Description

Illinois Coal Mines

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type | Render Type |
| ======== | ============== | ======================= | ======================= | ========= | =========== |
| No       | time           | :updated_at             | updated_at              | meta_data | meta_data   |
| Yes      | series tag     | mine_operating_company  | Mine Operating Company  | text      | text        |
| Yes      | series tag     | mine_name               | Mine Name               | text      | text        |
| Yes      | series tag     | seam_mined              | Seam Mined              | text      | text        |
| Yes      | series tag     | county                  | County                  | text      | text        |
| Yes      | series tag     | year_opened             | Year Opened             | text      | text        |
| Yes      | numeric metric | production              | 2010 Production         | number    | number      |
| Yes      | series tag     | possible_transportation | Possible Transportation | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:ws4h-cuji d:2012-01-27T13:50:46.000Z t:seam_mined="Springfield, Herrin" t:possible_transportation=CN t:county=Saline t:year_opened=1983 t:mine_operating_company="American Coal" t:mine_name="New Era" m:production=5774752

series e:ws4h-cuji d:2012-01-27T13:50:46.000Z t:seam_mined="Springfield, Herrin" t:possible_transportation=CN t:county=Saline t:year_opened=2010 t:mine_operating_company="American Coal" t:mine_name="New Future" m:production=616533

series e:ws4h-cuji d:2012-01-27T13:50:46.000Z t:seam_mined="Springfield, Herrin" t:possible_transportation="UP, CN" t:county=Perry t:year_opened=TBD t:mine_operating_company="Arch Coal" t:mine_name="Lost Prairie" m:production=0
```

## Meta Commands

```ls
metric m:production p:integer l:"2010 Production" t:dataTypeName=number

entity e:ws4h-cuji l:"DCEO IL Coal Mines" t:url=https://data.illinois.gov/api/views/ws4h-cuji

property e:ws4h-cuji t:meta.view v:id=ws4h-cuji v:category=Economics v:averageRating=0 v:name="DCEO IL Coal Mines"

property e:ws4h-cuji t:meta.view.owner v:id=t6h9-hze3 v:screenName=Nicole v:displayName=Nicole

property e:ws4h-cuji t:meta.view.tableauthor v:id=t6h9-hze3 v:screenName=Nicole v:roleName=publisher v:displayName=Nicole
```

## Top Records

```ls
| :updated_at | mine_operating_company | mine_name                       | seam_mined             | county    | year_opened    | production | possible_transportation | 
| =========== | ====================== | =============================== | ====================== | ========= | ============== | ========== | ======================= | 
| 1327672246  | Mine Operating Company | Mine Name                       | Seam Mined             | County    | Year Opened    |            | Possible Transportation | 
| 1327672246  | American Coal          | New Era                         | Springfield, Herrin    | Saline    | 1983           | 5774752    | CN                      | 
| 1327672246  | American Coal          | New Future                      | Springfield, Herrin    | Saline    | 2010           | 616533     | CN                      | 
| 1327672246  | Arch Coal              | Lost Prairie                    | Springfield, Herrin    | Perry     | TBD            | 0          | UP, CN                  | 
| 1327672246  | Arch Coal              | Viper                           | Springfield            | Sangamon  | 1982           | 2475257    | truck                   | 
| 1327672246  | Big Ridge              | Willow Lake Portal              | Springfield            | Saline    | 2002           | 2920225    | UP, BG                  | 
| 1327672246  | Black Nugget           | North Grindstone                | Colchester             | McDonough | 2009           | 194778     | truck                   | 
| 1327672246  | Coulterville Coal      | Mine #11                        | Herrin                 | Christian | in development | 0          |                         | 
| 1327672246  | Illinois Fuels         | Springfield, Herrin, Briar Hill |                        | Gallatin  | 2008           | 117801     | truck                   | 
| 1327672246  | Knight Hawk Coal       | Creek Paum                      | Murphysboro, Mt. Rorah | Jackson   | 1998           | 650211     | CN, BG                  | 
```