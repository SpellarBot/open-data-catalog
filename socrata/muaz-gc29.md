# Acceptable Double Check Detector Assemblies

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/acceptable-double-check-detector-assemblies-4bc46) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/muaz-gc29) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/muaz-gc29/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/muaz-gc29/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | muaz-gc29 |
| Name | Acceptable Double Check Detector Assemblies |
| Attribution | Department of Environmental Protection (DEP) |
| Category | Environment |
| Tags | acceptable double check detector assemblies, dep, department of environmental protection (dep) |
| Created | 2014-03-06T03:13:22Z |
| Publication Date | 2014-03-06T03:14:31Z |

## Description

List of acceptable double detector assemblies. Refer to the following report for more details http://www.nyc.gov/html/dep/pdf/water_sewer/42_doh_supplement.pdf

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
series e:muaz-gc29 d:2014-03-05T19:13:25.000Z t:company=AMES t:model_series=C300 m:row_number.muaz-gc29=1

series e:muaz-gc29 d:2014-03-05T19:13:25.000Z t:company=AMES t:model_series=3000SE m:row_number.muaz-gc29=2

series e:muaz-gc29 d:2014-03-05T19:13:25.000Z t:company=AMES t:model_series=3000SS m:row_number.muaz-gc29=3
```

## Meta Commands

```ls
metric m:row_number.muaz-gc29 p:long l:"Row Number"

entity e:muaz-gc29 l:"Acceptable Double Check Detector Assemblies" t:attribution="Department of Environmental Protection (DEP)" t:url=https://data.cityofnewyork.us/api/views/muaz-gc29

property e:muaz-gc29 t:meta.view v:id=muaz-gc29 v:category=Environment v:averageRating=0 v:name="Acceptable Double Check Detector Assemblies" v:attribution="Department of Environmental Protection (DEP)"

property e:muaz-gc29 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:muaz-gc29 t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | company  | model_series     | 
| =========== | ======== | ================ | 
| 1394046805  | AMES     | C300             | 
| 1394046805  | AMES     | 3000SE           | 
| 1394046805  | AMES     | 3000SS           | 
| 1394046805  | AMES     | 3000B            | 
| 1394046805  | CLA-VAL  | DD7LY            | 
| 1394046805  | CLA-VAL  | DD8LY            | 
| 1394046805  | CLA-VAL  | DD8NY-N          | 
| 1394046805  | CLA-VAL  | DD8VY-Z          | 
| 1394046805  | CONBRACO | 40-600           | 
| 1394046805  | CONBRACO | DCDA (aka4S-600) | 
```