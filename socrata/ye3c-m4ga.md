# Civil List

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/civil-list-2014) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/ye3c-m4ga) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/ye3c-m4ga/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/ye3c-m4ga/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | ye3c-m4ga |
| Name | Civil List |
| Attribution | Department of Citywide Administrative Services (DCAS) |
| Category | City Government |
| Tags | salary, pay, payroll |
| Created | 2015-07-01T18:39:33Z |
| Publication Date | 2016-11-03T19:23:54Z |

## Description

The Civil List reports the agency code (DPT), first initial and last name (NAME), agency name (ADDRESS), title code (TTL #), pay class (PC), and salary (SAL-RATE) of individuals who were employed by the City of New York at any given time during the indicated year.

## Columns

```ls
| Included | Schema Type    | Field Name    | Name          | Data Type | Render Type |
| ======== | ============== | ============= | ============= | ========= | =========== |
| Yes      | time           | calendar_year | CALENDAR YEAR | number    | text        |
| Yes      | numeric metric | dpt           | DPT           | number    | number      |
| Yes      | series tag     | name          | NAME          | text      | text        |
| No       |                | address       | ADDRESS       | text      | text        |
| Yes      | series tag     | ttl           | TTL #         | text      | text        |
| No       |                | pc            | PC            | text      | text        |
| Yes      | numeric metric | sal_rate      | SAL-RATE      | money     | text        |
```

## Time Field

```ls
Value = calendar_year
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = address,pc
```

## Data Commands

```ls
series e:ye3c-m4ga d:2014-01-01T00:00:00.000Z t:name="B J  SANDIFORD" t:ttl=12702 m:sal_rate=5 m:dpt=868

series e:ye3c-m4ga d:2014-01-01T00:00:00.000Z t:name="C A  WIGFALL" t:ttl=12702 m:sal_rate=5 m:dpt=868

series e:ye3c-m4ga d:2014-01-01T00:00:00.000Z t:name="A E A-AWOSOGBA" t:ttl=52311 m:sal_rate=51955 m:dpt=69
```

## Meta Commands

```ls
metric m:dpt p:integer l:DPT d:"The one (1) to three (3) digit number used to identify a City agency (?DPT?)." t:dataTypeName=number

metric m:sal_rate p:long l:SAL-RATE d:"The employee?s regular gross salary rate (?SAL-RATE?) in dollars and cents. The regular gross salaries listed reflect annual, prorated annual, hourly, or daily rates." t:dataTypeName=money

entity e:ye3c-m4ga l:"Civil List" t:attribution="Department of Citywide Administrative Services (DCAS)" t:url=https://data.cityofnewyork.us/api/views/ye3c-m4ga

property e:ye3c-m4ga t:meta.view v:id=ye3c-m4ga v:category="City Government" v:averageRating=0 v:name="Civil List" v:attribution="Department of Citywide Administrative Services (DCAS)"

property e:ye3c-m4ga t:meta.view.license v:name="Public Domain"

property e:ye3c-m4ga t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:ye3c-m4ga t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| calendar_year | dpt | name           | address                    | ttl   | pc | sal_rate    | 
| ============= | === | ============== | ========================== | ===== | == | =========== | 
| 2014          | 868 | B J SANDIFORD  | DEPARTMENT OF CITYWIDE ADM | 12702 | X  | $ 5.00      | 
| 2014          | 868 | C A WIGFALL    | DEPARTMENT OF CITYWIDE ADM | 12702 | X  | $ 5.00      | 
| 2014          | 69  | A E A-AWOSOGBA | HRA/DEPARTMENT OF SOCIAL S | 52311 | A  | $ 51,955.00 | 
| 2014          | 868 | K D AABY       | DEPARTMENT OF CITYWIDE ADM | 10209 | X  | $ 12.00     | 
| 2014          | 56  | I D AADIL      | POLICE DEPARTMENT          | 71012 | A  | $ 46,953.00 | 
| 2014          | 69  | M AAKIRI       | HRA/DEPARTMENT OF SOCIAL S | 56056 | A  | $ 33,000.00 | 
| 2014          | 464 | A AALAI        | CUNY QUEENSBOROUGH COMMUNI | 04607 | N  | $ 73.53     | 
| 2014          | 998 | A V AALEVIK    | N.Y.C. TRANSIT AUTHORITY   | 00402 | 02 | $ 33,280.00 | 
| 2014          | 998 | M AAMIR        | N.Y.C. TRANSIT AUTHORITY   | 00T07 | 04 | $ 60,878.00 | 
| 2014          | 826 | M R AARABI     | DEPARTMENT OF ENVIRONMENTA | 34202 | A  | $ 69,272.00 | 
```