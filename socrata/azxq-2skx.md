# HPD Rent Affordability Element

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/hpd-rent-affordability-element-a6c1b) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/azxq-2skx) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/azxq-2skx/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/azxq-2skx/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | azxq-2skx |
| Name | HPD Rent Affordability Element |
| Attribution | Department of Housing Preservation and Development (HPD) |
| Category | Housing & Development |
| Tags | department of housing preservation and development, hpd, rent affordability |
| Created | 2014-02-27T15:49:40Z |
| Publication Date | 2014-08-21T14:39:46Z |

## Description

Information on units disaggregated by rent affordability for each building in a project.

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type | Render Type |
| ======== | ============== | ================== | ================== | ========= | =========== |
| No       | time           | :updated_at        | updated_at         | meta_data | meta_data   |
| Yes      | numeric metric | project_dwid_2     | Project DWID       | number    | number      |
| Yes      | series tag     | project_id         | Project ID         | text      | number      |
| Yes      | series tag     | building_id        | Building ID        | text      | number      |
| Yes      | series tag     | affordability_band | Affordability Band | text      | text        |
| Yes      | numeric metric | total_units        | Total Units        | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:azxq-2skx d:2015-11-04T16:06:37.000Z t:building_id=936478 t:project_id=46061 t:affordability_band="Not Applic" m:project_dwid_2=533 m:total_units=576

series e:azxq-2skx d:2015-11-04T16:06:37.000Z t:building_id=63058 t:project_id=47844 t:affordability_band="Low Income" m:project_dwid_2=534 m:total_units=10

series e:azxq-2skx d:2015-11-04T16:06:37.000Z t:building_id=44886 t:project_id=47844 t:affordability_band="Low Income" m:project_dwid_2=535 m:total_units=13
```

## Meta Commands

```ls
metric m:project_dwid_2 p:integer l:"Project DWID" d:"Unique identifier of a Project" t:dataTypeName=number

metric m:total_units p:integer l:"Total Units" t:dataTypeName=number

entity e:azxq-2skx l:"HPD Rent Affordability Element" t:attribution="Department of Housing Preservation and Development (HPD)" t:url=https://data.cityofnewyork.us/api/views/azxq-2skx

property e:azxq-2skx t:meta.view v:id=azxq-2skx v:category="Housing & Development" v:averageRating=0 v:name="HPD Rent Affordability Element" v:attribution="Department of Housing Preservation and Development (HPD)"

property e:azxq-2skx t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:azxq-2skx t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | project_dwid_2 | project_id | building_id | affordability_band | total_units | 
| =========== | ============== | ========== | =========== | ================== | =========== | 
| 1446653197  | 533            | 46061      | 936478      | Not Applic         | 576         | 
| 1446653197  | 534            | 47844      | 63058       | Low Income         | 10          | 
| 1446653197  | 535            | 47844      | 44886       | Low Income         | 13          | 
| 1446653197  | 536            | 47844      | 44886       | Other              | 1           | 
| 1446653197  | 537            | 48683      | 18986       | Low Income         | 36          | 
| 1446653197  | 538            | 48683      | 18990       | Low Income         | 33          | 
| 1446653197  | 539            | 48683      | 18990       | Other              | 1           | 
| 1446653197  | 540            | 48886      | 66855       | Low Income         | 26          | 
| 1446653197  | 541            | 48886      | 66855       | Other              | 1           | 
| 1446653197  | 542            | 48886      | 66882       | Low Income         | 10          | 
```