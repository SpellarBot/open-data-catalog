# Acceptable Reduced Pressure Detector Assemblies

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/acceptable-reduced-pressure-detector-assemblies-f1047) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/4fif-5bmt) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/4fif-5bmt/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/4fif-5bmt/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 4fif-5bmt |
| Name | Acceptable Reduced Pressure Detector Assemblies |
| Attribution | Department of Environmental Protection (DEP) |
| Category | Environment |
| Tags | acceptable reduced pressure detector assemblies, department of environmental protection (dep) |
| Created | 2014-03-06T03:16:56Z |
| Publication Date | 2014-03-06T03:18:18Z |

## Description

Acceptable Reduced Pressure Detector Assemblies. Refer to the following report for additional details http://www.nyc.gov/html/dep/pdf/water_sewer/42_doh_supplement.pdf

## Columns

```ls
| Included | Schema Type | Field Name   | Name         | Data Type | Render Type |
| ======== | =========== | ============ | ============ | ========= | =========== |
| No       | time        | :updated_at  | updated_at   | meta_data | meta_data   |
| Yes      | series tag  | company      | Company      | text      | text        |
| Yes      | series tag  | model_series | Model Series | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:4fif-5bmt d:2014-03-05T19:16:59.000Z t:company=AMES t:model_series=5000CIV m:row_number.4fif-5bmt=1

series e:4fif-5bmt d:2014-03-05T19:16:59.000Z t:company=CLA-VAL t:model_series=18 m:row_number.4fif-5bmt=2

series e:4fif-5bmt d:2014-03-05T19:16:59.000Z t:company=CLA-VAL t:model_series=RD7LY m:row_number.4fif-5bmt=3
```

## Meta Commands

```ls
metric m:row_number.4fif-5bmt p:long l:"Row Number"

entity e:4fif-5bmt l:"Acceptable Reduced Pressure Detector Assemblies" t:attribution="Department of Environmental Protection (DEP)" t:url=https://data.cityofnewyork.us/api/views/4fif-5bmt

property e:4fif-5bmt t:meta.view v:id=4fif-5bmt v:category=Environment v:averageRating=0 v:name="Acceptable Reduced Pressure Detector Assemblies" v:attribution="Department of Environmental Protection (DEP)"

property e:4fif-5bmt t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:4fif-5bmt t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | company        | model_series | 
| =========== | ============== | ============ | 
| 1394047019  | AMES           | 5000CIV      | 
| 1394047019  | CLA-VAL        | 18           | 
| 1394047019  | CLA-VAL        | RD7LY        | 
| 1394047019  | CONBRACO       | 40-700       | 
| 1394047019  | FEBCO          | 826YD        | 
| 1394047019  | HERSEY/GRINNEL | 6CM RPDA     | 
| 1394047019  | WATTS          | 909 RPDA     | 
| 1394047019  | WILKINS        | 375DA        | 
| 1394047019  | WILKINS        | 375ADA       | 
| 1394047019  | WILKINS        | 475DA        | 
```