# Vacant Lots Cleaned

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/vacant-lots-cleaned-9c6fc) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/u6gg-xejf) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/u6gg-xejf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/u6gg-xejf/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | u6gg-xejf |
| Name | Vacant Lots Cleaned |
| Attribution | Department of Sanitation (DSNY) |
| Category | Social Services |
| Tags | vacant lots cleaned, lot, clean, dsny, sanitation, garbage, lots, clean web |
| Created | 2012-01-27T16:46:30Z |
| Publication Date | 2012-02-16T17:47:26Z |

## Description

Gives address, Borough-Block-Lot of each vacant lot cleaned by DSNY forces during the report month. Also gives the date cleaned.

## Columns

```ls
| Included | Schema Type | Field Name  | Name        | Data Type     | Render Type   |
| ======== | =========== | =========== | =========== | ============= | ============= |
| Yes      | series tag  | boro        | Boro        | text          | text          |
| Yes      | series tag  | district    | District    | text          | number        |
| Yes      | series tag  | ccu         | CCU         | text          | text          |
| Yes      | series tag  | block       | Block       | text          | number        |
| Yes      | series tag  | lot         | Lot         | text          | number        |
| Yes      | series tag  | ownertype   | OwnerType   | text          | text          |
| Yes      | time        | status_date | Status_Date | calendar_date | calendar_date |
| No       |             | address     | Address     | text          | text          |
```

## Time Field

```ls
Value = status_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = address
```

## Data Commands

```ls
series e:u6gg-xejf d:2012-01-30T00:00:00.000Z t:boro=BRONX t:lot=43 t:block=2294 t:ownertype=City t:district=1 t:ccu=12-05333 m:row_number.u6gg-xejf=1

series e:u6gg-xejf d:2012-01-30T00:00:00.000Z t:boro=BRONX t:lot=55 t:block=2294 t:ownertype=City t:district=1 t:ccu=12-05333 m:row_number.u6gg-xejf=2

series e:u6gg-xejf d:2012-01-30T00:00:00.000Z t:boro=BRONX t:lot=59 t:block=2294 t:ownertype=City t:district=1 t:ccu=12-05333 m:row_number.u6gg-xejf=3
```

## Meta Commands

```ls
metric m:row_number.u6gg-xejf p:long l:"Row Number"

entity e:u6gg-xejf l:"Vacant Lots Cleaned" t:attribution="Department of Sanitation (DSNY)" t:url=https://data.cityofnewyork.us/api/views/u6gg-xejf

property e:u6gg-xejf t:meta.view v:id=u6gg-xejf v:category="Social Services" v:averageRating=0 v:name="Vacant Lots Cleaned" v:attribution="Department of Sanitation (DSNY)"

property e:u6gg-xejf t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:u6gg-xejf t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| boro  | district | ccu      | block | lot | ownertype | status_date         | address                                                       | 
| ===== | ======== | ======== | ===== | === | ========= | =================== | ============================================================= | 
| BRONX | 1        | 12-05333 | 2294  | 43  | City      | 2012-01-30T00:00:00 | AT 460 WESTCHESTER AVENUE betw NYCTA SUBWAY & BERGEN AVENUE   | 
| BRONX | 1        | 12-05333 | 2294  | 55  | City      | 2012-01-30T00:00:00 | AT 460 WESTCHESTER AVENUE betw NYCTA SUBWAY & BERGEN AVENUE   | 
| BRONX | 1        | 12-05333 | 2294  | 59  | City      | 2012-01-30T00:00:00 | AT 460 WESTCHESTER AVENUE betw NYCTA SUBWAY & BERGEN AVENUE   | 
| BRONX | 1        | 11-11869 | 2585  | 19  | Private   | 2012-01-19T00:00:00 | ADJ. 840 EAST 134 STREET betw WALNUT AVENUE & AMTRAK RAILROAD | 
| BRONX | 1        | 12-05386 | 2617  | 20  | City      | 2012-01-31T00:00:00 | AT 672 ST ANNS AVENUE betw EAST 156 STREET & RAE STREET       | 
| BRONX | 1        | 12-05387 | 2624  | 73  | City      | 2012-01-31T00:00:00 | BETWEEN 665 & 669 CAULDWELL AVENUE                            | 
| BRONX | 3        | 12-05385 | 2381  | 43  | City      | 2012-01-31T00:00:00 | AT 451 EAST 159 STREET betw BEND & ELTON AVENUE               | 
| BRONX | 3        | 12-05331 | 2383  | 35  | City      | 2012-01-26T00:00:00 | ADJ. 421 EAST 161 STREET betw ELTON AVENUE & MELROSE AVENUE   | 
| BRONX | 3        | 12-05331 | 2383  | 37  | City      | 2012-01-26T00:00:00 | ADJ. 421 EAST 161 STREET betw ELTON AVENUE & MELROSE AVENUE   | 
| BRONX | 3        | 12-05331 | 2383  | 39  | City      | 2012-01-26T00:00:00 | ADJ. 421 EAST 161 STREET betw ELTON AVENUE & MELROSE AVENUE   | 
```