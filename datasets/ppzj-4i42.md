# Catch Basin Inspection and Cleaning Activity

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cso-bmp-report-catch-basin-survey-and-cleaning-afa78) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/ppzj-4i42) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/ppzj-4i42/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/ppzj-4i42/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | ppzj-4i42 |
| Name | Catch Basin Inspection and Cleaning Activity |
| Attribution | Department of Environmental Protection (DEP) |
| Category | Environment |
| Tags | cso bmp report - catch basin survey and cleaning, dep, environment |
| Created | 2014-03-05T20:33:56Z |
| Publication Date | 2014-03-05T20:35:06Z |

## Description

Data from tables and charts included in DEP's Combined Sewer Overflow Best Management Practices Annual Report

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                       | Data Type | Render Type |
| ======== | ============== | ========================== | ========================== | ========= | =========== |
| No       | time           | :updated_at                | updated_at                 | meta_data | meta_data   |
| Yes      | series tag     | borough                    | Borough                    | text      | text        |
| Yes      | numeric metric | total_cb_surveyed          | Total CB Surveyed          | number    | number      |
| Yes      | numeric metric | scheduled_cb_cleaned       | Scheduled CB Cleaned       | number    | number      |
| Yes      | numeric metric | complaint_based_cb_cleaned | Complaint based CB Cleaned | number    | number      |
| Yes      | numeric metric | total_cb_cleaned           | Total CB Cleaned           | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:ppzj-4i42 d:2014-03-05T12:33:59.000Z t:borough=Bronx m:total_cb_cleaned=3451 m:scheduled_cb_cleaned=2048 m:complaint_based_cb_cleaned=1403 m:total_cb_surveyed=3524

series e:ppzj-4i42 d:2014-03-05T12:33:59.000Z t:borough=Brooklyn m:total_cb_cleaned=9546 m:scheduled_cb_cleaned=5754 m:complaint_based_cb_cleaned=3792 m:total_cb_surveyed=11170

series e:ppzj-4i42 d:2014-03-05T12:33:59.000Z t:borough=Manhattan m:total_cb_cleaned=2675 m:scheduled_cb_cleaned=1727 m:complaint_based_cb_cleaned=948 m:total_cb_surveyed=3254
```

## Meta Commands

```ls
metric m:total_cb_surveyed p:integer l:"Total CB Surveyed" t:dataTypeName=number

metric m:scheduled_cb_cleaned p:integer l:"Scheduled CB Cleaned" t:dataTypeName=number

metric m:complaint_based_cb_cleaned p:integer l:"Complaint based CB Cleaned" t:dataTypeName=number

metric m:total_cb_cleaned p:integer l:"Total CB Cleaned" t:dataTypeName=number

entity e:ppzj-4i42 l:"Catch Basin Inspection and Cleaning Activity" t:attribution="Department of Environmental Protection (DEP)" t:url=https://data.cityofnewyork.us/api/views/ppzj-4i42

property e:ppzj-4i42 t:meta.view v:id=ppzj-4i42 v:category=Environment v:averageRating=0 v:name="Catch Basin Inspection and Cleaning Activity" v:attribution="Department of Environmental Protection (DEP)"

property e:ppzj-4i42 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:ppzj-4i42 t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | borough       | total_cb_surveyed | scheduled_cb_cleaned | complaint_based_cb_cleaned | total_cb_cleaned | 
| =========== | ============= | ================= | ==================== | ========================== | ================ | 
| 1394022839  | Bronx         | 3524              | 2048                 | 1403                       | 3451             | 
| 1394022839  | Brooklyn      | 11170             | 5754                 | 3792                       | 9546             | 
| 1394022839  | Manhattan     | 3254              | 1727                 | 948                        | 2675             | 
| 1394022839  | Queens        | 13794             | 7986                 | 5576                       | 13562            | 
| 1394022839  | Staten Island | 4394              | 1646                 | 979                        | 2625             | 
| 1394022839  | Total         | 36136             | 19161                | 12698                      | 31859            | 
```