# DEP - Bureau of Wastewater Treatment (BWT) ? 2011 Nuisance Complaints

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dep-bureau-of-wastewater-treatment-bwt-2011-nuisance-complaints-2af25) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/qiku-f5v3) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/qiku-f5v3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/qiku-f5v3/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | qiku-f5v3 |
| Name | DEP - Bureau of Wastewater Treatment (BWT) ? 2011 Nuisance Complaints |
| Attribution | Department of Environmental Protection (DEP) |
| Category | Environment |
| Tags | dep, environment, environmental protection, department of environmental protection, nuisance complaints, 2011, bureau of wastewater treatment, wastewater, nuisance, complaints, healthy living |
| Created | 2011-09-09T18:21:58Z |
| Publication Date | 2013-06-21T19:43:29Z |

## Description

A database of Department of Environmental Protection (DEP) nuisance complaints, by wastewater treatment plants and by monthly totals in the year 2011, assembled by the Bureau of Wastewater Treatment (BWT)

## Columns

```ls
| Included | Schema Type    | Field Name                      | Name                              | Data Type | Render Type |
| ======== | ============== | =============================== | ================================= | ========= | =========== |
| Yes      | series tag     | month                           | MONTH                             | text      | text        |
| Yes      | series tag     | plant                           | PLANT                             | text      | text        |
| Yes      | numeric metric | complaint_responded             | # COMPLAINT RESPONDED             | number    | number      |
| Yes      | numeric metric | complaint_rec_d                 | # COMPLAINT REC'D                 | number    | number      |
| Yes      | numeric metric | complaint_not_responded_w_in_24 | # COMPLAINT NOT RESPONDED W/IN 24 | number    | number      |
```

## Time Field

```ls
Value = 2011
Format & Zone = yyyy
```

## Data Commands

```ls
series e:qiku-f5v3 d:2011-01-01T00:00:00.000Z t:plant=OH t:month=JANUARY m:complaint_not_responded_w_in_24=0 m:complaint_responded=3 m:complaint_rec_d=3

series e:qiku-f5v3 d:2011-01-01T00:00:00.000Z t:plant=RK t:month=JANUARY m:complaint_not_responded_w_in_24=0 m:complaint_responded=1 m:complaint_rec_d=1

series e:qiku-f5v3 d:2011-01-01T00:00:00.000Z t:plant=NR t:month=JANUARY m:complaint_not_responded_w_in_24=1 m:complaint_responded=0 m:complaint_rec_d=1
```

## Meta Commands

```ls
metric m:complaint_responded p:integer l:"# COMPLAINT RESPONDED" t:dataTypeName=number

metric m:complaint_rec_d p:integer l:"# COMPLAINT REC'D" t:dataTypeName=number

metric m:complaint_not_responded_w_in_24 p:integer l:"# COMPLAINT NOT RESPONDED W/IN 24" t:dataTypeName=number

entity e:qiku-f5v3 l:"DEP -  Bureau of Wastewater Treatment (BWT) ? 2011 Nuisance Complaints" t:attribution="Department of Environmental Protection (DEP)" t:url=https://data.cityofnewyork.us/api/views/qiku-f5v3

property e:qiku-f5v3 t:meta.view v:id=qiku-f5v3 v:category=Environment v:averageRating=0 v:name="DEP -  Bureau of Wastewater Treatment (BWT) ? 2011 Nuisance Complaints" v:attribution="Department of Environmental Protection (DEP)"

property e:qiku-f5v3 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:qiku-f5v3 t:meta.view.tableauthor v:id=k2fz-tf56 v:screenName="Gary A" v:displayName="Gary A"
```

## Top Records

```ls
| month    | plant     | complaint_responded | complaint_rec_d | complaint_not_responded_w_in_24 | 
| ======== | ========= | =================== | =============== | =============================== | 
| JANUARY  | OH        | 3                   | 3               | 0                               | 
| JANUARY  | RK        | 1                   | 1               | 0                               | 
| JANUARY  | NR        | 0                   | 1               | 1                               | 
| JANUARY  | 26th Ward | 1                   | 1               | 0                               | 
| TOTAL    |           | 5                   | 6               | 1                               | 
| FEBRUARY | OH        | 7                   | 9               | 2                               | 
| FEBRUARY | CFN       | 1                   | 1               | 0                               | 
| FEBRUARY | 26th Ward | 0                   | 1               | 1                               | 
| TOTAL    |           | 8                   | 11              | 3                               | 
| MARCH    |           |                     |                 |                                 | 
```