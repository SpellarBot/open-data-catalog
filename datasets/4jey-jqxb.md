# Police - Selected Criminal Incidents

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/police-criminal-incidents) |
| Metadata | [Link](https://data.somervillema.gov/api/views/4jey-jqxb) |
| Data: JSON | [100 Rows](https://data.somervillema.gov/api/views/4jey-jqxb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.somervillema.gov/api/views/4jey-jqxb/rows.csv?max_rows=100) |
| Host | data.somervillema.gov |
| Id | 4jey-jqxb |
| Name | Police - Selected Criminal Incidents |
| Attribution | Police Department |
| Category | Public Safety |
| Tags | police, crime, robbery, burglary, car breaks |
| Created | 2016-02-03T15:29:14Z |
| Publication Date | 2016-02-03T16:15:40Z |

## Description

Robbery, burglary, theft of motor vehicle & theft from motor vehicle since 2005. Exact addresses are not displayed for privacy reasons.

## Columns

```ls
| Included | Schema Type    | Field Name  | Name        | Data Type     | Render Type   |
| ======== | ============== | =========== | =========== | ============= | ============= |
| Yes      | numeric metric | incnum      | incnum      | number        | number        |
| Yes      | time           | dtreported  | dtreported  | calendar_date | calendar_date |
| Yes      | series tag     | stnum       | stnum       | text          | text          |
| Yes      | series tag     | stname1     | stname1     | text          | text          |
| Yes      | series tag     | stname2     | stname2     | text          | text          |
| Yes      | series tag     | loctype     | loctype     | text          | text          |
| No       |                | ra          | ra          | text          | text          |
| Yes      | series tag     | offensecode | offensecode | text          | text          |
| Yes      | series tag     | offense     | offense     | text          | text          |
| No       |                | x           | X           | number        | number        |
| No       |                | y           | Y           | number        | number        |
```

## Time Field

```ls
Value = dtreported
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = ra,x,y
```

## Data Commands

```ls
series e:4jey-jqxb d:2007-07-21T00:50:00.000Z t:offensecode=120 t:loctype=I t:offense=ROBBERY t:stname1="15 TENNYSON STREET" t:stnum=XX m:incnum=7026331

series e:4jey-jqxb d:2008-10-06T09:46:00.000Z t:offensecode=23F t:loctype=S t:offense="THEFT FROM MOTOR VEHICLE" t:stname1="422 MYSTIC AVE" t:stnum=XX m:incnum=8035903

series e:4jey-jqxb d:2005-12-24T04:43:00.000Z t:offensecode=120 t:offense=ROBBERY t:stname1="709 MCGRATH HWY" t:stnum=XX m:incnum=5042153
```

## Meta Commands

```ls
metric m:incnum p:integer l:incnum t:dataTypeName=number

entity e:4jey-jqxb l:"Police - Selected Criminal Incidents" t:attribution="Police Department" t:url=https://data.somervillema.gov/api/views/4jey-jqxb

property e:4jey-jqxb t:meta.view v:id=4jey-jqxb v:category="Public Safety" v:averageRating=0 v:name="Police - Selected Criminal Incidents" v:attribution="Police Department"

property e:4jey-jqxb t:meta.view.license v:name="Open Data Commons Open Database License" v:termsLink=http://opendatacommons.org/licenses/odbl/1.0/

property e:4jey-jqxb t:meta.view.owner v:id=ta4g-utcf v:profileImageUrlMedium=/api/users/ta4g-utcf/profile_images/THUMB v:profileImageUrlLarge=/api/users/ta4g-utcf/profile_images/LARGE v:screenName="Steve Craig" v:profileImageUrlSmall=/api/users/ta4g-utcf/profile_images/TINY v:displayName="Steve Craig"

property e:4jey-jqxb t:meta.view.tableauthor v:id=ta4g-utcf v:profileImageUrlMedium=/api/users/ta4g-utcf/profile_images/THUMB v:profileImageUrlLarge=/api/users/ta4g-utcf/profile_images/LARGE v:screenName="Steve Craig" v:profileImageUrlSmall=/api/users/ta4g-utcf/profile_images/TINY v:roleName=administrator v:displayName="Steve Craig"
```

## Top Records

```ls
| incnum   | dtreported          | stnum | stname1            | stname2 | loctype | ra | offensecode | offense                  | x           | y          | 
| ======== | =================== | ===== | ================== | ======= | ======= | == | =========== | ======================== | =========== | ========== | 
| 7026331  | 2007-07-21T00:50:00 | XX    | 15 TENNYSON STREET |         | I       | NA | 120         | ROBBERY                  | -71.1000258 | 42.3918254 | 
| 8035903  | 2008-10-06T09:46:00 | XX    | 422 MYSTIC AVE     |         | S       | 35 | 23F         | THEFT FROM MOTOR VEHICLE | -71.0890077 | 42.395087  | 
| 5042153  | 2005-12-24T04:43:00 | XX    | 709 MCGRATH HWY    |         |         | NA | 120         | ROBBERY                  | -71.086728  | 42.390629  | 
| 8000319  | 2008-01-03T19:00:00 | XX    | ABERDEEN RD        |         | S       | 97 | 23F         | THEFT FROM MOTOR VEHICLE | -71.1135465 | 42.3920485 | 
| 7017731  | 2007-05-23T11:33:00 | XX    | ACADIA PK          |         | S       | NA | 23F         | THEFT FROM MOTOR VEHICLE | -71.1169224 | 42.3882612 | 
| 8019411  | 2008-06-08T10:14:00 | XX    | ADAMS ST           |         | S       | 64 | 240         | MOTOR VEHICLE THEFT      | -71.0995474 | 42.3956576 | 
| 9016751  | 2009-05-11T23:01:00 | XX    | ADRIAN ST          |         | S       | 58 | 240         | MOTOR VEHICLE THEFT      | -71.0989407 | 42.3773079 | 
| 13000765 | 2013-01-06T08:56:00 | XX    | ALBION PL          |         | S       | 70 | 23F         | THEFT FROM MOTOR VEHICLE | -71.1082782 | 42.3924723 | 
| 13030072 | 2013-08-08T16:42:15 | XX    | ALBION ST E        |         | S       | 33 | 240         | MOTOR VEHICLE THEFT      | -71.1071395 | 42.3913877 | 
| 6023666  | 2006-07-12T12:12:00 | XX    | ALBION ST          |         | S       | NA | 240         | MOTOR VEHICLE THEFT      | -71.1071395 | 42.3913877 | 
```