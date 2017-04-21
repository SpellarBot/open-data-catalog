# Fire Alarms Periodic Inspection Testing Requirements

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/fire-alarms-periodic-inspection-testing-requirements-24940) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/g84i-fugu) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/g84i-fugu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/g84i-fugu/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | g84i-fugu |
| Name | Fire Alarms Periodic Inspection Testing Requirements |
| Attribution | Fire Department of New York City (FDNY) |
| Category | Public Safety |
| Tags | fdny, fire department, safety, fire safety, fire code, building standards, sprinklers |
| Created | 2013-01-23T22:01:51Z |
| Publication Date | 2013-01-31T21:00:37Z |

## Description

FIRE PROTECTION PERIODIC INSPECTION AND TESTING REQUIREMENTS 
SPRINKLER SYSTEM (Excerpt from NFPA 25 Table 5.1)
STANDPIPE SYSTEM (Excerpt from NFPA 25 Table 6.1)
WATER STORAGE TANK (Excerpt from NFPA 25 Table 9.1)
FIRE ALARM SYSTEM (Excerpt from NFPA 72 Table 10.3.1)

## Columns

```ls
| Included | Schema Type | Field Name                    | Name                          | Data Type | Render Type |
| ======== | =========== | ============================= | ============================= | ========= | =========== |
| No       | time        | :updated_at                   | updated_at                    | meta_data | meta_data   |
| Yes      | series tag  | component_name                | Component Name                | text      | text        |
| Yes      | series tag  | required_inspection_test_type | Required Inspection Test Type | text      | text        |
| Yes      | series tag  | required_inspection_frequency | Required Inspection Frequency | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:g84i-fugu d:2013-01-23T14:01:53.000Z t:required_inspection_test_type=Inspect t:component_name="Gauges (dry, preaction, and deluge systems)" t:required_inspection_frequency=Weekly/monthly m:row_number.g84i-fugu=1

series e:g84i-fugu d:2013-01-23T14:01:53.000Z t:required_inspection_test_type=Inspect t:component_name="Control valves" t:required_inspection_frequency=Weekly/monthly m:row_number.g84i-fugu=2

series e:g84i-fugu d:2013-01-23T14:01:53.000Z t:required_inspection_test_type=Inspect t:component_name="Alarm devices" t:required_inspection_frequency=Quarterly m:row_number.g84i-fugu=3
```

## Meta Commands

```ls
metric m:row_number.g84i-fugu p:long l:"Row Number"

entity e:g84i-fugu l:"Fire Alarms Periodic Inspection Testing Requirements" t:attribution="Fire Department of New York City (FDNY)" t:url=https://data.cityofnewyork.us/api/views/g84i-fugu

property e:g84i-fugu t:meta.view v:id=g84i-fugu v:category="Public Safety" v:attributionLink=http://www.nyc.gov/html/fdny/pdf/firecode/fc_nycsfpe_presentation_10_26_10_draft.pdf v:averageRating=0 v:name="Fire Alarms Periodic Inspection Testing Requirements" v:attribution="Fire Department of New York City (FDNY)"

property e:g84i-fugu t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:g84i-fugu t:meta.view.tableauthor v:id=syvn-4vgv v:screenName="Sudhir Vasudeva" v:displayName="Sudhir Vasudeva"
```

## Top Records

```ls
| :updated_at | component_name                              | required_inspection_test_type | required_inspection_frequency | 
| =========== | =========================================== | ============================= | ============================= | 
| 1358949713  | Gauges (dry, preaction, and deluge systems) | Inspect                       | Weekly/monthly                | 
| 1358949713  | Control valves                              | Inspect                       | Weekly/monthly                | 
| 1358949713  | Alarm devices                               | Inspect                       | Quarterly                     | 
| 1358949713  | Gauges (wet pipe systems)                   | Inspect                       | Monthly                       | 
| 1358949713  | Pipe and fittings                           | Inspect                       | Annually                      | 
| 1358949713  | Sprinklers                                  | Inspect                       | Annually                      | 
| 1358949713  | Fire department connections                 | Inspect                       | Quarterly                     | 
| 1358949713  | Valves (all types)                          | Inspect                       | See NFPA 25 Table 12.1        | 
| 1358949713  | Alarm devices                               | Test                          | Quarterly/semiannually        | 
| 1358949713  | Main drain                                  | Test                          | Annually                      | 
```