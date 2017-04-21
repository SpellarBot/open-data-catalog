# Current Plan Programs

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/current-plan-programs) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/bjmk-35w5) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/bjmk-35w5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/bjmk-35w5/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | bjmk-35w5 |
| Name | Current Plan Programs |
| Attribution | NYC School Construction Authority (SCA) |
| Category | Education |
| Tags | sca, construction, schools, projects |
| Created | 2016-05-31T21:48:36Z |
| Publication Date | 2016-05-31T21:58:54Z |

## Description

The below datasets are now merged into a single dataset:

1. Accessibility programs for schools
2. Lighting fixture replacement for schools
3. Science Lab programs for schools
4. Sandy Storm Projects
5. Bathroom Projects

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type | Render Type |
| ======== | ============== | =============== | =============== | ========= | =========== |
| No       | time           | :updated_at     | updated_at      | meta_data | meta_data   |
| Yes      | series tag     | program_name    | Program Name    | text      | text        |
| Yes      | series tag     | district        | District        | text      | number      |
| Yes      | series tag     | building_id     | Building ID     | text      | text        |
| Yes      | series tag     | school_name     | School Name     | text      | text        |
| Yes      | series tag     | borough         | Borough         | text      | text        |
| Yes      | numeric metric | constr_start_fy | Constr.Start FY | number    | number      |
| Yes      | series tag     | description     | Description     | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:bjmk-35w5 d:2016-05-31T14:49:01.000Z t:school_name="P.S. 112 (TANDEM M206)" t:building_id=M112 t:description="Electrical Systems" t:program_name="Sandy Storm" t:borough=Manhattan t:district=4 m:constr_start_fy=2015

series e:bjmk-35w5 d:2016-05-31T14:49:01.000Z t:school_name="P.S. 112 (TANDEM M206)" t:building_id=M112 t:description="Flood Elimination" t:program_name="Sandy Storm" t:borough=Manhattan t:district=4 m:constr_start_fy=2015

series e:bjmk-35w5 d:2016-05-31T14:49:01.000Z t:school_name="P.S. 112 (TANDEM M206)" t:building_id=M112 t:description="Heating Plant Upgrade" t:program_name="Sandy Storm" t:borough=Manhattan t:district=4 m:constr_start_fy=2015
```

## Meta Commands

```ls
metric m:constr_start_fy p:integer l:"Constr.Start FY" t:dataTypeName=number

entity e:bjmk-35w5 l:"Current Plan Programs" t:attribution="NYC School Construction Authority (SCA)" t:url=https://data.cityofnewyork.us/api/views/bjmk-35w5

property e:bjmk-35w5 t:meta.view v:id=bjmk-35w5 v:category=Education v:averageRating=0 v:name="Current Plan Programs" v:attribution="NYC School Construction Authority (SCA)"

property e:bjmk-35w5 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:bjmk-35w5 t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | program_name | district | building_id | school_name            | borough   | constr_start_fy | description           | 
| =========== | ============ | ======== | =========== | ====================== | ========= | =============== | ===================== | 
| 1464706141  | Sandy Storm  | 4        | M112        | P.S. 112 (TANDEM M206) | Manhattan | 2015            | Electrical Systems    | 
| 1464706141  | Sandy Storm  | 4        | M112        | P.S. 112 (TANDEM M206) | Manhattan | 2015            | Flood Elimination     | 
| 1464706141  | Sandy Storm  | 4        | M112        | P.S. 112 (TANDEM M206) | Manhattan | 2015            | Heating Plant Upgrade | 
| 1464706141  | Sandy Storm  | 4        | M112        | P.S. 112 (TANDEM M206) | Manhattan | 2015            | Interior Spaces       | 
| 1464706141  | Sandy Storm  | 15       | K015        | P.S. 15                | Brooklyn  | 2015            | Domestic Piping       | 
| 1464706141  | Sandy Storm  | 15       | K015        | P.S. 15                | Brooklyn  | 2015            | Electrical Systems    | 
| 1464706141  | Sandy Storm  | 15       | K015        | P.S. 15                | Brooklyn  | 2015            | Flood Elimination     | 
| 1464706141  | Sandy Storm  | 15       | K015        | P.S. 15                | Brooklyn  | 2015            | Heating Plant Upgrade | 
| 1464706141  | Sandy Storm  | 15       | K015        | P.S. 15                | Brooklyn  | 2015            | Interior Spaces       | 
| 1464706141  | Sandy Storm  | 15       | K015        | P.S. 15                | Brooklyn  | 2015            | Ventilation           | 
```