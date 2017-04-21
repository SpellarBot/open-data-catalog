# Certificate of Fitness Schedule of Fees

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/certificate-of-fitness-schedule-of-fees-30479) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/2ghx-qqsj) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/2ghx-qqsj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/2ghx-qqsj/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 2ghx-qqsj |
| Name | Certificate of Fitness Schedule of Fees |
| Attribution | Fire Department of New York City (FDNY) |
| Category | Public Safety |
| Tags | fdny, fire department, safety, fire safety, training, certificate of fitness, cof |
| Created | 2013-01-31T20:36:31Z |
| Publication Date | 2013-01-31T20:38:03Z |

## Description

Certificate of Fitness Schedule of Fees

## Columns

```ls
| Included | Schema Type    | Field Name  | Name        | Data Type | Render Type |
| ======== | ============== | =========== | =========== | ========= | =========== |
| No       | time           | :updated_at | updated_at  | meta_data | meta_data   |
| Yes      | series tag     | coftype     | COFTYPE     | text      | text        |
| Yes      | series tag     | description | DESCRIPTION | text      | text        |
| Yes      | series tag     | premise_flg | PREMISE_FLG | text      | text        |
| Yes      | numeric metric | orig_fee    | ORIG_FEE    | number    | text        |
| Yes      | numeric metric | renewal_fee | RENEWAL_FEE | number    | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:2ghx-qqsj d:2013-01-31T12:36:33.000Z t:coftype=A49 t:description="SUPERVISION OF AEROSOL" t:premise_flg=Y m:orig_fee=25 m:renewal_fee=15

series e:2ghx-qqsj d:2013-01-31T12:36:33.000Z t:coftype=C06 t:description="FULL/SELF SERVE CNG DISPENSIN" t:premise_flg=N m:orig_fee=25 m:renewal_fee=15

series e:2ghx-qqsj d:2013-01-31T12:36:33.000Z t:coftype=C07 t:description="SUP. SELF SERVICE CNG STATION" t:premise_flg=Y m:orig_fee=25 m:renewal_fee=15
```

## Meta Commands

```ls
metric m:orig_fee p:integer l:ORIG_FEE t:dataTypeName=number

metric m:renewal_fee p:integer l:RENEWAL_FEE t:dataTypeName=number

entity e:2ghx-qqsj l:"Certificate of Fitness Schedule of Fees" t:attribution="Fire Department of New York City (FDNY)" t:url=https://data.cityofnewyork.us/api/views/2ghx-qqsj

property e:2ghx-qqsj t:meta.view v:id=2ghx-qqsj v:category="Public Safety" v:attributionLink=http://www.nyc.gov/html/fdny/pdf/cof_study_material/cof_tableinternet.pdf v:averageRating=0 v:name="Certificate of Fitness Schedule of Fees" v:attribution="Fire Department of New York City (FDNY)"

property e:2ghx-qqsj t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:2ghx-qqsj t:meta.view.tableauthor v:id=syvn-4vgv v:screenName="Sudhir Vasudeva" v:displayName="Sudhir Vasudeva"
```

## Top Records

```ls
| :updated_at | coftype | description                    | premise_flg | orig_fee | renewal_fee | 
| =========== | ======= | ============================== | =========== | ======== | =========== | 
| 1359635793  | A49     | SUPERVISION OF AEROSOL         | Y           | 25       | 15          | 
| 1359635793  | C06     | FULL/SELF SERVE CNG DISPENSIN  | N           | 25       | 15          | 
| 1359635793  | C07     | SUP. SELF SERVICE CNG STATION  | Y           | 25       | 15          | 
| 1359635793  | C08     | MAINTENANCE CNG FACILITY       | N           | 25       | 15          | 
| 1359635793  | C09     | SUPERVISE CNG STATION          | Y           | 25       | 15          | 
| 1359635793  | C10     | SUPERVISE LNG PLANT            | Y           | 25       | 15          | 
| 1359635793  | C11     | SUPERVISE SNG PLANT            | Y           | 25       | 15          | 
| 1359635793  | C12     | DIRECT MFG FLAMMABLE MIXTURES  | Y           | 25       | 15          | 
| 1359635793  | C13     | DIRECT WHLSLE DRUG/CHEM SUPPLY | Y           | 25       | 15          | 
| 1359635793  | C14     | SUPERVISING NON?PRODUCTION     | Y           | 25       | 15          | 
```