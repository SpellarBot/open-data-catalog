# City of Austin Lawsuit Settlements

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/city-of-austin-lawsuit-settlements) |
| Metadata | [Link](https://data.austintexas.gov/api/views/w8rr-4qky) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/w8rr-4qky/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/w8rr-4qky/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | w8rr-4qky |
| Name | City of Austin Lawsuit Settlements |
| Attribution | Law Department |
| Category | Government |
| Tags | lawsuits, law, settle settlement, paid |
| Created | 2015-08-11T21:41:44Z |
| Publication Date | 2015-08-11T21:44:12Z |

## Description

City of Austin Lawsuit Settlements between 10/01/14 and 06/30/15

## Columns

```ls
| Included | Schema Type    | Field Name    | Name          | Data Type     | Render Type   |
| ======== | ============== | ============= | ============= | ============= | ============= |
| Yes      | series tag     | case_name     | Case Name     | text          | text          |
| Yes      | time           | incident_date | Incident Date | calendar_date | calendar_date |
| Yes      | series tag     | department    | Department    | text          | text          |
| Yes      | series tag     | disposition   | Disposition   | text          | text          |
| Yes      | numeric metric | amount        | Amount        | money         | money         |
| Yes      | series tag     | case_type     | Case Type     | text          | text          |
```

## Time Field

```ls
Value = incident_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:w8rr-4qky d:2015-08-11T14:41:50.000Z t:department="Parks and Recreation" t:case_name="McPhail, Jennifer" t:case_type="GL Americans with Disabilities Act (Access)" t:disposition="Settlement (Emp-Lit-ED)" m:amount=19975

series e:w8rr-4qky d:2013-03-26T00:00:00.000Z t:department="Austin Resource Recovery" t:case_name="Government Employees Insurance Company" t:case_type="GL Car Wreck" t:disposition="Settlement (Emp-Lit-ED)" m:amount=1833.94

series e:w8rr-4qky d:2013-03-01T00:00:00.000Z t:department="Austin Police Department" t:case_name="Schaefer, John" t:case_type="GL Mandamus" t:disposition="Settlement (Emp-Lit-ED)" m:amount=1000
```

## Meta Commands

```ls
metric m:amount p:double l:Amount t:dataTypeName=money

entity e:w8rr-4qky l:"City of Austin Lawsuit Settlements" t:attribution="Law Department" t:url=https://data.austintexas.gov/api/views/w8rr-4qky

property e:w8rr-4qky t:meta.view v:id=w8rr-4qky v:category=Government v:averageRating=0 v:name="City of Austin Lawsuit Settlements" v:attribution="Law Department"

property e:w8rr-4qky t:meta.view.owner v:id=kz58-z3ur v:screenName=ledelc v:displayName=ledelc

property e:w8rr-4qky t:meta.view.tableauthor v:id=kz58-z3ur v:screenName=ledelc v:roleName=editor v:displayName=ledelc
```

## Top Records

```ls
| case_name                                    | incident_date       | department               | disposition                 | amount    | case_type                                   | 
| ============================================ | =================== | ======================== | =========================== | ========= | =========================================== | 
| McPhail, Jennifer                            |                     | Parks and Recreation     | Settlement (Emp-Lit-ED)     | 19975.00  | GL Americans with Disabilities Act (Access) | 
| Government Employees Insurance Company       | 2013-03-26T00:00:00 | Austin Resource Recovery | Settlement (Emp-Lit-ED)     | 1833.94   | GL Car Wreck                                | 
| Sanchez, Rodolfo                             | 2011-10-30T00:00:00 | City Council             | Trial - City lost on appeal |           | GL Other                                    | 
| Schaefer, John                               | 2013-03-01T00:00:00 | Austin Police Department | Settlement (Emp-Lit-ED)     | 1000.00   | GL Mandamus                                 | 
| Streetman, James                             | 2012-10-07T00:00:00 | Austin Police Department | Settlement (Emp-Lit-ED)     | 12000.00  | GL Civil Rights (Non-employment)            | 
| Amin-Akbari, Akbar                           | 2011-06-10T00:00:00 | Austin Police Department | Non-suit with settlement    | 3000.00   | GL Civil Rights (Non-employment)            | 
| Castillo Ryley, Laurel                       | 2012-05-30T00:00:00 | Austin Water             | Settlement (Emp-Lit-ED)     | 105000.00 | GL Car Wreck                                | 
| Rodriguez, Jr. Louis v. COA (minor involved) | 2012-08-20T00:00:00 | Austin Resource Recovery | Settlement (Emp-Lit-ED)     | 72311.73  | GL Car Wreck                                | 
```