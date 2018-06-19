# MSP Traffic Stops 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/msp-traffic-stops-2014-feb05) |
| Metadata | [Link](https://data.maryland.gov/api/views/nq4v-y7m5) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/nq4v-y7m5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/nq4v-y7m5/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | nq4v-y7m5 |
| Name | MSP Traffic Stops 2014 |
| Attribution | Maryland State Police |
| Category | Public Safety |
| Tags | msp, traffic, citations, total stops, warnings, 2014, public safety |
| Created | 2014-10-19T21:54:10Z |
| Publication Date | 2014-10-19T22:04:22Z |

## Description

This dataset shows the total number of MSP traffic stops for CY 2014.  Also included is the total number of citations and warnings issued by MSP for CY 2014.  The values are provided in monthly increments.

## Columns

```ls
| Included | Schema Type    | Field Name                | Name                      | Data Type | Render Type |
| ======== | ============== | ========================= | ========================= | ========= | =========== |
| Yes      | series tag     | 2014_year_to_dateby_month | 2014 Year to DateBy Month | text      | text        |
| Yes      | numeric metric | total_vehicle_stops       | Total Vehicle Stops       | number    | number      |
| Yes      | numeric metric | citations_issued          | Citations Issued          | number    | number      |
| Yes      | numeric metric | warnings_issued           | Warnings Issued           | number    | number      |
```

## Time Field

```ls
Value = 2014
Format & Zone = yyyy
```

## Data Commands

```ls
series e:nq4v-y7m5 d:2014-01-01T00:00:00.000Z t:2014_year_to_dateby_month=January m:citations_issued=20109 m:total_vehicle_stops=30795 m:warnings_issued=17926

series e:nq4v-y7m5 d:2014-01-01T00:00:00.000Z t:2014_year_to_dateby_month=February m:citations_issued=20597 m:total_vehicle_stops=33223 m:warnings_issued=20271

series e:nq4v-y7m5 d:2014-01-01T00:00:00.000Z t:2014_year_to_dateby_month=March m:citations_issued=24161 m:total_vehicle_stops=38514 m:warnings_issued=22867
```

## Meta Commands

```ls
metric m:total_vehicle_stops p:integer l:"Total Vehicle Stops" t:dataTypeName=number

metric m:citations_issued p:integer l:"Citations Issued" t:dataTypeName=number

metric m:warnings_issued p:integer l:"Warnings Issued" t:dataTypeName=number

entity e:nq4v-y7m5 l:"MSP Traffic Stops 2014" t:attribution="Maryland State Police" t:url=https://data.maryland.gov/api/views/nq4v-y7m5

property e:nq4v-y7m5 t:meta.view v:id=nq4v-y7m5 v:category="Public Safety" v:averageRating=0 v:name="MSP Traffic Stops 2014" v:attribution="Maryland State Police"

property e:nq4v-y7m5 t:meta.view.license v:name="Public Domain"

property e:nq4v-y7m5 t:meta.view.owner v:id=v448-7imn v:screenName=Jimmy v:displayName=Jimmy

property e:nq4v-y7m5 t:meta.view.tableauthor v:id=v448-7imn v:screenName=Jimmy v:roleName=editor v:displayName=Jimmy
```

## Top Records

```ls
| 2014_year_to_dateby_month | total_vehicle_stops | citations_issued | warnings_issued | 
| ========================= | =================== | ================ | =============== | 
| January                   | 30795               | 20109            | 17926           | 
| February                  | 33223               | 20597            | 20271           | 
| March                     | 38514               | 24161            | 22867           | 
| April                     | 40628               | 25829            | 23778           | 
| May                       | 48431               | 33488            | 26056           | 
| June                      | 41988               | 27514            | 23730           | 
| July                      | 44838               | 30126            | 25571           | 
| August                    | 50238               | 33380            | 27916           | 
| September                 | 42925               | 28197            | 24325           | 
| YTD - Total Statewide     | 371580              | 243401           | 212440          | 
```