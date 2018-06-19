# DEP - Bureau of Wastewater Treatment (BWT) ? 2010 Nuisance Complaints

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dep-bureau-of-wastewater-treatment-bwt-2010-nuisance-complaints-e7e4c) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/rubn-abch) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/rubn-abch/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/rubn-abch/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | rubn-abch |
| Name | DEP - Bureau of Wastewater Treatment (BWT) ? 2010 Nuisance Complaints |
| Attribution | Department of Environmental Protection (DEP) |
| Category | Environment |
| Tags | dep, environment, environmental protection, department of environmental protection, nuisance complaints, 2010, bureau of wastewater treatment, wastewater, nuisance, complaints, healthy living |
| Created | 2011-09-09T18:45:54Z |
| Publication Date | 2013-06-21T19:44:45Z |

## Description

A database of Department of Environmental Protection (DEP) nuisance complaints, by wastewater treatment plants and by monthly totals in the year 2010, assembled by the Bureau of Wastewater Treatment (BWT)

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
Value = 2010
Format & Zone = yyyy
```

## Data Commands

```ls
series e:rubn-abch d:2010-01-01T00:00:00.000Z t:plant=OH t:month=JANUARY m:complaint_not_responded_w_in_24=2 m:complaint_responded=7 m:complaint_rec_d=9

series e:rubn-abch d:2010-01-01T00:00:00.000Z t:plant=BB t:month=JANUARY m:complaint_not_responded_w_in_24=3 m:complaint_responded=2 m:complaint_rec_d=5

series e:rubn-abch d:2010-01-01T00:00:00.000Z t:plant=NR t:month=JANUARY m:complaint_not_responded_w_in_24=0 m:complaint_responded=3 m:complaint_rec_d=3
```

## Meta Commands

```ls
metric m:complaint_responded p:integer l:"# COMPLAINT RESPONDED" t:dataTypeName=number

metric m:complaint_rec_d p:integer l:"# COMPLAINT REC'D" t:dataTypeName=number

metric m:complaint_not_responded_w_in_24 p:integer l:"# COMPLAINT NOT RESPONDED W/IN 24" t:dataTypeName=number

entity e:rubn-abch l:"DEP -  Bureau of Wastewater Treatment (BWT) ? 2010 Nuisance Complaints" t:attribution="Department of Environmental Protection (DEP)" t:url=https://data.cityofnewyork.us/api/views/rubn-abch

property e:rubn-abch t:meta.view v:id=rubn-abch v:category=Environment v:averageRating=0 v:name="DEP -  Bureau of Wastewater Treatment (BWT) ? 2010 Nuisance Complaints" v:attribution="Department of Environmental Protection (DEP)"

property e:rubn-abch t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:rubn-abch t:meta.view.tableauthor v:id=k2fz-tf56 v:screenName="Gary A" v:displayName="Gary A"
```

## Top Records

```ls
| month         | plant    | complaint_responded | complaint_rec_d | complaint_not_responded_w_in_24 | 
| ============= | ======== | =================== | =============== | =============================== | 
| JANUARY       | OH       | 7                   | 9               | 2                               | 
| JANUARY       | BB       | 2                   | 5               | 3                               | 
| JANUARY       | NR       | 3                   | 3               | 0                               | 
| JANUARY       | HP       | 1                   | 1               | 0                               | 
| JANUARY       | RICH P.S | 1                   | 1               | 0                               | 
| JANUARY       | NYOFCO   | 3                   | 3               | 0                               | 
| JANUARY TOTAL |          | 16                  | 21              | 5                               | 
| FEBRUARY      | OH       | 25                  | 28              | 3                               | 
| FEBRUARY      | BB       | 1                   | 2               | 1                               | 
| FEBRUARY      | NR       | 1                   | 1               | 0                               | 
```