# World Trade Center (WTC) Patient Categories

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/world-trade-center-wtc-patient-categories-2a150) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/dgg9-jkx8) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/dgg9-jkx8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/dgg9-jkx8/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | dgg9-jkx8 |
| Name | World Trade Center (WTC) Patient Categories |
| Attribution | Health and Hospitals Corporation (HHC) |
| Category | Health |
| Tags | health, patient, world trade center, wtc, healthy living |
| Created | 2011-09-30T18:35:08Z |
| Publication Date | 2011-10-11T19:25:38Z |

## Description

HHC's WTC Environmental Health Center program, one of three Centers of Excellence in New York City, provides medical and mental healthcare to residents, students, workers, and passersby who may still be sick from 9/11.  This data shows the patient population of the program from 2008 to 2011.
Update Frequency: As needed

## Columns

```ls
| Included | Schema Type    | Field Name  | Name       | Data Type | Render Type |
| ======== | ============== | =========== | ========== | ========= | =========== |
| No       | time           | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag     | categories  | Categories | text      | text        |
| Yes      | numeric metric | total       | Total      | number    | number      |
| Yes      | numeric metric | of_total    | % of Total | percent   | percent     |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:dgg9-jkx8 d:2011-09-30T11:35:15.000Z t:categories=Resident m:total=154 m:of_total=20

series e:dgg9-jkx8 d:2011-09-30T11:35:15.000Z t:categories="Local Worker" m:total=378 m:of_total=50

series e:dgg9-jkx8 d:2011-09-30T11:35:15.000Z t:categories="Resident + Local Worker" m:total=77 m:of_total=10
```

## Meta Commands

```ls
metric m:total p:integer l:Total t:dataTypeName=number

metric m:of_total p:integer l:"% of Total" t:dataTypeName=percent

entity e:dgg9-jkx8 l:"World Trade Center (WTC) Patient Categories" t:attribution="Health and Hospitals Corporation (HHC)" t:url=https://data.cityofnewyork.us/api/views/dgg9-jkx8

property e:dgg9-jkx8 t:meta.view v:id=dgg9-jkx8 v:category=Health v:averageRating=0 v:name="World Trade Center (WTC) Patient Categories" v:attribution="Health and Hospitals Corporation (HHC)"

property e:dgg9-jkx8 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:dgg9-jkx8 t:meta.view.tableauthor v:id=k2fz-tf56 v:screenName="Gary A" v:displayName="Gary A"
```

## Top Records

```ls
| :updated_at | categories                     | total | of_total | 
| =========== | ============================== | ===== | ======== | 
| 1317382515  | Resident                       | 154   | 20       | 
| 1317382515  | Local Worker                   | 378   | 50       | 
| 1317382515  | Resident + Local Worker        | 77    | 10       | 
| 1317382515  | Clean-Up Worker                | 51    | 7        | 
| 1317382515  | Clean-Up Worker + Local Worker | 20    | 3        | 
| 1317382515  | Rescue/Recovery                | 4     | 1        | 
| 1317382515  | Passerby, Commuter             | 32    | 4        | 
| 1317382515  | Student                        | 25    | 3        | 
| 1317382515  | Other                          | 13    | 2        | 
```