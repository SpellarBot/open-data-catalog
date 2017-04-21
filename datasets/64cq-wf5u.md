# Austin Fire Stations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/austin-fire-stations) |
| Metadata | [Link](https://data.austintexas.gov/api/views/64cq-wf5u) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/64cq-wf5u/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/64cq-wf5u/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | 64cq-wf5u |
| Name | Austin Fire Stations |
| Attribution | City of Austin |
| Category | Public Safety |
| Tags | fire, afd, stations, fire stations |
| Created | 2012-03-20T15:37:45Z |
| Publication Date | 2012-03-20T15:40:57Z |

## Description

Location information for Austin Fire stations

## Columns

```ls
| Included | Schema Type | Field Name        | Name              | Data Type | Render Type |
| ======== | =========== | ================= | ================= | ========= | =========== |
| No       | time        | :updated_at       | updated_at        | meta_data | meta_data   |
| Yes      | series tag  | name              | Name              | text      | text        |
| Yes      | series tag  | jurisdiction_name | Jurisdiction Name | text      | text        |
| No       |             | y                 | Y                 | number    | number      |
| No       |             | x                 | X                 | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = y,x
```

## Data Commands

```ls
series e:64cq-wf5u d:2012-03-20T08:37:46.000Z t:name=FS0001 t:jurisdiction_name=AFD m:row_number.64cq-wf5u=1

series e:64cq-wf5u d:2012-03-20T08:37:46.000Z t:name=FS0002 t:jurisdiction_name=AFD m:row_number.64cq-wf5u=2

series e:64cq-wf5u d:2012-03-20T08:37:46.000Z t:name=FS0003 t:jurisdiction_name=AFD m:row_number.64cq-wf5u=3
```

## Meta Commands

```ls
metric m:row_number.64cq-wf5u p:long l:"Row Number"

entity e:64cq-wf5u l:"Austin Fire Stations" t:attribution="City of Austin" t:url=https://data.austintexas.gov/api/views/64cq-wf5u

property e:64cq-wf5u t:meta.view v:id=64cq-wf5u v:category="Public Safety" v:averageRating=0 v:name="Austin Fire Stations" v:attribution="City of Austin"

property e:64cq-wf5u t:meta.view.owner v:id=99uc-9byy v:screenName=opendataatx v:displayName=opendataatx

property e:64cq-wf5u t:meta.view.tableauthor v:id=99uc-9byy v:screenName=opendataatx v:roleName=administrator v:displayName=opendataatx
```

## Top Records

```ls
| :updated_at | name   | jurisdiction_name | y         | x          | 
| =========== | ====== | ================= | ========= | ========== | 
| 1332232666  | FS0001 | AFD               | 30.265838 | -97.739591 | 
| 1332232666  | FS0002 | AFD               | 30.282028 | -97.742966 | 
| 1332232666  | FS0003 | AFD               | 30.294741 | -97.738427 | 
| 1332232666  | FS0004 | AFD               | 30.276405 | -97.754818 | 
| 1332232666  | FS0005 | AFD               | 30.278099 | -97.685082 | 
| 1332232666  | FS0006 | AFD               | 30.246986 | -97.750639 | 
| 1332232666  | FS0007 | AFD               | 30.258012 | -97.724202 | 
| 1332232666  | FS0008 | AFD               | 30.372163 | -97.723397 | 
| 1332232666  | FS0009 | AFD               | 30.306461 | -97.729813 | 
| 1332232666  | FS0010 | AFD               | 30.295395 | -97.766826 | 
```