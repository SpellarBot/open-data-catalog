# Routes by Transportation Sites

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/routes-by-transportation-sites) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/fgqh-vfzz) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/fgqh-vfzz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/fgqh-vfzz/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | fgqh-vfzz |
| Name | Routes by Transportation Sites |
| Category | Transportation |
| Created | 2015-11-13T21:11:32Z |
| Publication Date | 2016-05-03T23:06:00Z |

## Description

This dataset allows users to link the information in the Route dataset to the information in the Transportation Site dataset. 
Please note that because OPT does not design routes for Pre-K service, those routes are not included in this dataset.

## Columns

```ls
| Included | Schema Type | Field Name   | Name         | Data Type | Render Type |
| ======== | =========== | ============ | ============ | ========= | =========== |
| No       | time        | :updated_at  | updated_at   | meta_data | meta_data   |
| Yes      | series tag  | school_year  | School_Year  | text      | text        |
| Yes      | series tag  | route_number | Route_Number | text      | text        |
| Yes      | series tag  | opt_code     | OPT_Code     | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:fgqh-vfzz d:2016-10-01T11:02:53.000Z t:route_number=J698 t:opt_code=75004 t:school_year=2015-2016 m:row_number.fgqh-vfzz=1

series e:fgqh-vfzz d:2016-10-01T11:02:53.000Z t:route_number=J699 t:opt_code=75580 t:school_year=2015-2016 m:row_number.fgqh-vfzz=2

series e:fgqh-vfzz d:2016-10-01T11:02:53.000Z t:route_number=J700 t:opt_code=75003 t:school_year=2015-2016 m:row_number.fgqh-vfzz=3
```

## Meta Commands

```ls
metric m:row_number.fgqh-vfzz p:long l:"Row Number"

entity e:fgqh-vfzz l:"Routes by Transportation Sites" t:url=https://data.cityofnewyork.us/api/views/fgqh-vfzz

property e:fgqh-vfzz t:meta.view v:id=fgqh-vfzz v:category=Transportation v:averageRating=0 v:name="Routes by Transportation Sites"

property e:fgqh-vfzz t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:fgqh-vfzz t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | school_year | route_number | opt_code | 
| =========== | =========== | ============ | ======== | 
| 1475319773  | 2015-2016   | J698         | 75004    | 
| 1475319773  | 2015-2016   | J699         | 75580    | 
| 1475319773  | 2015-2016   | J700         | 75003    | 
| 1475319773  | 2015-2016   | J700         | 75140    | 
| 1475319773  | 2015-2016   | J701         | 75003    | 
| 1475319773  | 2015-2016   | J701         | 75140    | 
| 1475319773  | 2015-2016   | J702         | 75003    | 
| 1475319773  | 2015-2016   | J702         | 75140    | 
| 1475319773  | 2015-2016   | J703         | 75003    | 
| 1475319773  | 2015-2016   | J703         | 75140    | 
```