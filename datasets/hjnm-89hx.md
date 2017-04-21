# Family Assistance (FA) Recipients

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/odra-family-assistance-8a95c) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/hjnm-89hx) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/hjnm-89hx/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/hjnm-89hx/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | hjnm-89hx |
| Name | Family Assistance (FA) Recipients |
| Attribution | Human Resources Administration (HRA) |
| Category | Social Services |
| Tags | odra family assistance, hra, human resources |
| Created | 2013-05-21T12:22:16Z |
| Publication Date | 2016-11-04T14:08:42Z |

## Description

Statistics from HRA on family assistance.

## Columns

```ls
| Included | Schema Type    | Field Name                   | Name                         | Data Type | Render Type |
| ======== | ============== | ============================ | ============================ | ========= | =========== |
| No       | time           | :updated_at                  | updated_at                   | meta_data | meta_data   |
| Yes      | series tag     | month                        | Month                        | text      | text        |
| Yes      | numeric metric | family_assistance_recipients | Family Assistance Recipients | number    | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:hjnm-89hx d:2016-11-04T14:08:09.000Z t:month=Jan-96 m:family_assistance_recipients=823238

series e:hjnm-89hx d:2016-11-04T14:08:09.000Z t:month=Feb-96 m:family_assistance_recipients=817939

series e:hjnm-89hx d:2016-11-04T14:08:09.000Z t:month=Mar-96 m:family_assistance_recipients=815862
```

## Meta Commands

```ls
metric m:family_assistance_recipients p:integer l:"Family Assistance Recipients" t:dataTypeName=number

entity e:hjnm-89hx l:"Family Assistance (FA) Recipients" t:attribution="Human Resources Administration (HRA)" t:url=https://data.cityofnewyork.us/api/views/hjnm-89hx

property e:hjnm-89hx t:meta.view v:id=hjnm-89hx v:category="Social Services" v:averageRating=0 v:name="Family Assistance (FA) Recipients" v:attribution="Human Resources Administration (HRA)"

property e:hjnm-89hx t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:hjnm-89hx t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | month  | family_assistance_recipients | 
| =========== | ====== | ============================ | 
| 1478268489  | Jan-96 | 823238                       | 
| 1478268489  | Feb-96 | 817939                       | 
| 1478268489  | Mar-96 | 815862                       | 
| 1478268489  | Apr-96 | 814179                       | 
| 1478268489  | May-96 | 804889                       | 
| 1478268489  | Jun-96 | 793381                       | 
| 1478268489  | Jul-96 | 788910                       | 
| 1478268489  | Aug-96 | 779284                       | 
| 1478268489  | Sep-96 | 769707                       | 
| 1478268489  | Oct-96 | 766749                       | 
```