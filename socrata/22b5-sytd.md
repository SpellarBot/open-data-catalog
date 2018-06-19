# Directory of Hospitals with Domestic Violence Coordinators

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/directory-of-hospitals-with-domestic-violence-coordinators-2167c) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/22b5-sytd) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/22b5-sytd/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/22b5-sytd/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 22b5-sytd |
| Name | Directory of Hospitals with Domestic Violence Coordinators |
| Attribution | Mayor's Office to Combat Domestic Violence (OCDV) |
| Category | Social Services |
| Tags | ocdv, combat, domestic violence, jobs, economic mobility, hospital, jobs and economic mobility |
| Created | 2013-03-19T18:37:10Z |
| Publication Date | 2013-03-19T20:43:11Z |

## Description

List of hospitals that have Domestic Violence Coordinators

## Columns

```ls
| Included | Schema Type | Field Name   | Name         | Data Type | Render Type |
| ======== | =========== | ============ | ============ | ========= | =========== |
| No       | time        | :updated_at  | updated_at   | meta_data | meta_data   |
| Yes      | series tag  | borough      | Borough      | text      | text        |
| Yes      | series tag  | hospital     | Hospital     | text      | text        |
| Yes      | series tag  | phone_number | Phone Number | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:22b5-sytd d:2013-03-19T11:37:16.000Z t:phone_number=718-918-5000 t:borough=Bronx t:hospital="Jacobi Medical Center" m:row_number.22b5-sytd=1

series e:22b5-sytd d:2013-03-19T11:37:16.000Z t:phone_number=718-579-5000 t:borough=Bronx t:hospital="Lincoln Hospital & Mental Health Center" m:row_number.22b5-sytd=2

series e:22b5-sytd d:2013-03-19T11:37:16.000Z t:phone_number=718-519-5000 t:borough=Bronx t:hospital="North Central Bronx Hospital" m:row_number.22b5-sytd=3
```

## Meta Commands

```ls
metric m:row_number.22b5-sytd p:long l:"Row Number"

entity e:22b5-sytd l:"Directory of Hospitals with Domestic Violence Coordinators" t:attribution="Mayor's Office to Combat Domestic Violence (OCDV)" t:url=https://data.cityofnewyork.us/api/views/22b5-sytd

property e:22b5-sytd t:meta.view v:id=22b5-sytd v:category="Social Services" v:attributionLink=http://www.nyc.gov/html/ocdv/html/statistics_resources/providers.shtml v:averageRating=0 v:name="Directory of Hospitals with Domestic Violence Coordinators" v:attribution="Mayor's Office to Combat Domestic Violence (OCDV)"

property e:22b5-sytd t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:22b5-sytd t:meta.view.tableauthor v:id=8b43-zkvh v:screenName="Ram S." v:displayName="Ram S."
```

## Top Records

```ls
| :updated_at | borough   | hospital                                  | phone_number | 
| =========== | ========= | ========================================= | ============ | 
| 1363693036  | Bronx     | Jacobi Medical Center                     | 718-918-5000 | 
| 1363693036  | Bronx     | Lincoln Hospital & Mental Health Center   | 718-579-5000 | 
| 1363693036  | Bronx     | North Central Bronx Hospital              | 718-519-5000 | 
| 1363693036  | Brooklyn  | Coney Island Hospital                     | 718-616-3000 | 
| 1363693036  | Brooklyn  | Kings County Hospital Center              | 718-245-3131 | 
| 1363693036  | Brooklyn  | Woodhull Medical and Mental Health Center | 718-963-8000 | 
| 1363693036  | Manhattan | Bellevue Hospital Center                  | 212-562-4141 | 
| 1363693036  | Manhattan | Harlem Hospital                           | 212-939-1000 | 
| 1363693036  | Manhattan | Metropolitan Hospital                     | 212-423-6262 | 
| 1363693036  | Queens    | Elmhurst Hospital Center                  | 718-334-4000 | 
```