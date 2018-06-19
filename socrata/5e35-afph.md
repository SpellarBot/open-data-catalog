# Acceptable Double Check Valve Assemblies

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/acceptable-double-check-valve-assemblies-0d157) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/5e35-afph) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/5e35-afph/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/5e35-afph/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 5e35-afph |
| Name | Acceptable Double Check Valve Assemblies |
| Attribution | Department of Environmental Protection (DEP) |
| Category | Environment |
| Tags | acceptable double check valve assemblies, dep |
| Created | 2014-03-05T23:30:08Z |
| Publication Date | 2014-03-05T23:31:45Z |

## Description

List of acceptable double check valve assemblies. For more information refer to the manual located at the following link http://www.nyc.gov/html/dep/pdf/water_sewer/42_doh_supplement.pdf

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
series e:5e35-afph d:2014-03-05T15:30:10.000Z t:company=AMES t:model_series=2000SS m:row_number.5e35-afph=1

series e:5e35-afph d:2014-03-05T15:30:10.000Z t:company=AMES t:model_series=2000B m:row_number.5e35-afph=2

series e:5e35-afph d:2014-03-05T15:30:10.000Z t:company=AMES t:model_series=COLT200A m:row_number.5e35-afph=3
```

## Meta Commands

```ls
metric m:row_number.5e35-afph p:long l:"Row Number"

entity e:5e35-afph l:"Acceptable Double Check Valve Assemblies" t:attribution="Department of Environmental Protection (DEP)" t:url=https://data.cityofnewyork.us/api/views/5e35-afph

property e:5e35-afph t:meta.view v:id=5e35-afph v:category=Environment v:averageRating=0 v:name="Acceptable Double Check Valve Assemblies" v:attribution="Department of Environmental Protection (DEP)"

property e:5e35-afph t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:5e35-afph t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | company | model_series | 
| =========== | ======= | ============ | 
| 1394033410  | AMES    | 2000SS       | 
| 1394033410  | AMES    | 2000B        | 
| 1394033410  | AMES    | COLT200A     | 
| 1394033410  | AMES    | MAXIM200a    | 
| 1394033410  | AMES    | COLT200Na    | 
| 1394033410  | AMES    | MAXIM200Na   | 
| 1394033410  | BUCKNER | 24100        | 
| 1394033410  | CLA-VAL | D-2          | 
| 1394033410  | CLA-VAL | D-4          | 
| 1394033410  | CLA-VAL | DC6LW        | 
```