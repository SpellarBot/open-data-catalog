# Safety Net Assistance (SNA) recipients

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/safety-net-assistance-sna-recipients-44c3f) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/ect6-rj3p) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/ect6-rj3p/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/ect6-rj3p/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | ect6-rj3p |
| Name | Safety Net Assistance (SNA) recipients |
| Attribution | Human Resources Administration (HRA) |
| Category | Social Services |
| Tags | safety net assistance (sna) recipients, hra, human resources, trends |
| Created | 2013-05-20T22:13:53Z |
| Publication Date | 2016-11-04T14:09:11Z |

## Description

Monthly trends of people receiving safety net assistance.

## Columns

```ls
| Included | Schema Type    | Field Name  | Name                                   | Data Type | Render Type |
| ======== | ============== | =========== | ====================================== | ========= | =========== |
| No       | time           | :updated_at | updated_at                             | meta_data | meta_data   |
| Yes      | series tag     | month       | Month                                  | text      | text        |
| Yes      | numeric metric | recipients  | Total Safety Net Assistance Recipients | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:ect6-rj3p d:2016-11-04T14:09:07.000Z t:month=Jan-96 m:recipients=218168

series e:ect6-rj3p d:2016-11-04T14:09:07.000Z t:month=Feb-96 m:recipients=214789

series e:ect6-rj3p d:2016-11-04T14:09:07.000Z t:month=Mar-96 m:recipients=214195
```

## Meta Commands

```ls
metric m:recipients p:integer l:"Total Safety Net Assistance Recipients" t:dataTypeName=number

entity e:ect6-rj3p l:"Safety Net Assistance (SNA) recipients" t:attribution="Human Resources Administration (HRA)" t:url=https://data.cityofnewyork.us/api/views/ect6-rj3p

property e:ect6-rj3p t:meta.view v:id=ect6-rj3p v:category="Social Services" v:averageRating=0 v:name="Safety Net Assistance (SNA) recipients" v:attribution="Human Resources Administration (HRA)"

property e:ect6-rj3p t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:ect6-rj3p t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | month  | recipients | 
| =========== | ====== | ========== | 
| 1478268547  | Jan-96 | 218168     | 
| 1478268547  | Feb-96 | 214789     | 
| 1478268547  | Mar-96 | 214195     | 
| 1478268547  | Apr-96 | 212231     | 
| 1478268547  | May-96 | 210202     | 
| 1478268547  | Jun-96 | 206216     | 
| 1478268547  | Jul-96 | 205643     | 
| 1478268547  | Aug-96 | 203776     | 
| 1478268547  | Sep-96 | 198665     | 
| 1478268547  | Oct-96 | 196456     | 
```