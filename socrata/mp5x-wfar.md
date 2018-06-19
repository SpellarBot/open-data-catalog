# Road Paving Status

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/road-paving-status) |
| Metadata | [Link](https://data.honolulu.gov/api/views/mp5x-wfar) |
| Data: JSON | [100 Rows](https://data.honolulu.gov/api/views/mp5x-wfar/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.honolulu.gov/api/views/mp5x-wfar/rows.csv?max_rows=100) |
| Host | data.honolulu.gov |
| Id | mp5x-wfar |
| Name | Road Paving Status |
| Category | Transportation |
| Created | 2015-05-13T01:49:38Z |
| Publication Date | 2015-05-13T01:54:05Z |

## Description

As of 5-4-2015

## Columns

```ls
| Included | Schema Type | Field Name  | Name       | Data Type | Render Type |
| ======== | =========== | =========== | ========== | ========= | =========== |
| No       | time        | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag  | section     | Section    | text      | text        |
| Yes      | series tag  | start       | Start      | text      | text        |
| Yes      | series tag  | end         | End        | text      | text        |
| Yes      | series tag  | status      | Status     | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:mp5x-wfar d:2015-05-12T18:49:43.000Z t:status="Construction to Start within a year" t:start="10th Ave" t:end=End t:section="10th Ave" m:row_number.mp5x-wfar=1

series e:mp5x-wfar d:2015-05-12T18:49:43.000Z t:status="Road Paved" t:start="Maunalei Ave" t:end="Alohea Ave" t:section="10th Ave" m:row_number.mp5x-wfar=2

series e:mp5x-wfar d:2015-05-12T18:49:43.000Z t:status="Construction to Start within a year" t:start="Palolo Ave" t:end="Waialae Ave" t:section="10th Ave" m:row_number.mp5x-wfar=3
```

## Meta Commands

```ls
metric m:row_number.mp5x-wfar p:long l:"Row Number"

entity e:mp5x-wfar l:"Road Paving Status" t:url=https://data.honolulu.gov/api/views/mp5x-wfar

property e:mp5x-wfar t:meta.view v:id=mp5x-wfar v:category=Transportation v:averageRating=0 v:name="Road Paving Status"

property e:mp5x-wfar t:meta.view.owner v:id=b4zr-4dtj v:screenName="Karl Sueyoshi" v:displayName="Karl Sueyoshi"

property e:mp5x-wfar t:meta.view.tableauthor v:id=b4zr-4dtj v:screenName="Karl Sueyoshi" v:roleName=administrator v:displayName="Karl Sueyoshi"
```

## Top Records

```ls
| :updated_at | section                           | start                      | end          | status                              | 
| =========== | ================================= | ========================== | ============ | =================================== | 
| 1431456583  | 10th Ave                          | 10th Ave                   | End          | Construction to Start within a year | 
| 1431456583  | 10th Ave                          | Maunalei Ave               | Alohea Ave   | Road Paved                          | 
| 1431456583  | 10th Ave                          | Palolo Ave                 | Waialae Ave  | Construction to Start within a year | 
| 1431456583  | 10th Ave (only Fwy underpass r/w) | Harding Ave                | Pahoa Ave    | Road Paved                          | 
| 1431456583  | 11th Ave                          | Pahoa Ave                  | Kilauea Ave  | Road Paved                          | 
| 1431456583  | 11th Ave                          | Waialae Ave                | Harding Ave  | Road Paved                          | 
| 1431456583  | 12th Ave                          | H1 Fwy                     | Alohea Ave   | Road Paved                          | 
| 1431456583  | 12th Ave                          | Harding Ave                | Lunalilo Fwy | Road Paved                          | 
| 1431456583  | 12th Ave                          | Waialae Ave                | Harding Ave  | Road Paved                          | 
| 1431456583  | 13th Ave                          | 175 feet below Claudine St | Waialae Ave  | Road Paved                          | 
```