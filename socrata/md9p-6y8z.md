# Municipal Court Caseload Information FY 2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/municipal-court-caseload-information-fy-2012) |
| Metadata | [Link](https://data.austintexas.gov/api/views/md9p-6y8z) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/md9p-6y8z/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/md9p-6y8z/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | md9p-6y8z |
| Name | Municipal Court Caseload Information FY 2012 |
| Attribution | City of Austin |
| Category | Public Safety |
| Tags | municipal, court, violation |
| Created | 2013-11-14T15:00:49Z |
| Publication Date | 2017-03-15T15:03:34Z |

## Description

This data is provided to help with analysis of various violations charged throughout the City of Austin

## Columns

```ls
| Included | Schema Type | Field Name                 | Name                       | Data Type     | Render Type   |
| ======== | =========== | ========================== | ========================== | ============= | ============= |
| Yes      | series tag  | offense_case_type          | Offense Case Type          | text          | text          |
| Yes      | time        | offense_date               | Offense Date               | calendar_date | calendar_date |
| No       |             | offense_time               | Offense Time               | number        | text          |
| Yes      | series tag  | offense_charge_description | Offense Charge Description | text          | text          |
| Yes      | series tag  | offense_street_name        | Offense Street Name        | text          | text          |
| Yes      | series tag  | offense_cross_street_name  | Offense Cross Street Name  | text          | text          |
| Yes      | series tag  | school_zone                | School Zone                | text          | text          |
| Yes      | series tag  | construction_zone          | Construction Zone          | text          | text          |
| Yes      | series tag  | case_closed                | Case Closed                | text          | text          |
| Yes      | series tag  | agency_code                | Agency Code                | text          | text          |
| Yes      | series tag  | officer_code               | Officer Code               | text          | number        |
```

## Time Field

```ls
Value = offense_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = offense_time
```

## Data Commands

```ls
series e:md9p-6y8z d:2011-10-01T00:00:00.000Z t:officer_code=5322 t:school_zone=N t:offense_case_type=CM t:construction_zone=N t:case_closed=N t:offense_street_name="1800 LEONA" t:agency_code=APD t:offense_charge_description="PUBLIC INTOXICATION" m:row_number.md9p-6y8z=1

series e:md9p-6y8z d:2011-10-01T00:00:00.000Z t:officer_code=6798 t:school_zone=N t:offense_case_type=CM t:construction_zone=N t:case_closed=Y t:offense_street_name="739 WEST WILLIAM CANNON DRIVE" t:agency_code=APD t:offense_charge_description="PUBLIC INTOXICATION" m:row_number.md9p-6y8z=2

series e:md9p-6y8z d:2011-10-01T00:00:00.000Z t:officer_code=5344 t:school_zone=N t:offense_case_type=CM t:construction_zone=N t:case_closed=Y t:offense_street_name="3100 BLOCK GOVALLE AVEUNE" t:agency_code=APD t:offense_charge_description="PUBLIC INTOXICATION" m:row_number.md9p-6y8z=3
```

## Meta Commands

```ls
metric m:row_number.md9p-6y8z p:long l:"Row Number"

entity e:md9p-6y8z l:"Municipal Court Caseload Information FY 2012" t:attribution="City of Austin" t:url=https://data.austintexas.gov/api/views/md9p-6y8z

property e:md9p-6y8z t:meta.view v:id=md9p-6y8z v:category="Public Safety" v:attributionLink=http://www.austintexas.gov v:averageRating=0 v:name="Municipal Court Caseload Information FY 2012" v:attribution="City of Austin"

property e:md9p-6y8z t:meta.view.owner v:id=rjt7-ysrk v:screenName="Jim Warren" v:displayName="Jim Warren"

property e:md9p-6y8z t:meta.view.tableauthor v:id=rjt7-ysrk v:screenName="Jim Warren" v:roleName=publisher v:displayName="Jim Warren"
```

## Top Records

```ls
| offense_case_type | offense_date        | offense_time | offense_charge_description | offense_street_name              | offense_cross_street_name | school_zone | construction_zone | case_closed | agency_code | officer_code | 
| ================= | =================== | ============ | ========================== | ================================ | ========================= | =========== | ================= | =========== | =========== | ============ | 
| CM                | 2011-10-01T00:00:00 | 00.00.00     | PUBLIC INTOXICATION        | 1800 LEONA                       |                           | N           | N                 | N           | APD         | 5322         | 
| CM                | 2011-10-01T00:00:00 | 00.00.00     | PUBLIC INTOXICATION        | 739 WEST WILLIAM CANNON DRIVE    |                           | N           | N                 | Y           | APD         | 6798         | 
| CM                | 2011-10-01T00:00:00 | 00.00.00     | PUBLIC INTOXICATION        | 3100 BLOCK GOVALLE AVEUNE        |                           | N           | N                 | Y           | APD         | 5344         | 
| CM                | 2011-10-01T00:00:00 | 03.20.00     | PUBLIC INTOXICATION        | 8900 BLOCK NORTH IH 35           |                           | N           | N                 | Y           | APD         | 6986         | 
| CM                | 2011-10-01T00:00:00 | 00.00.00     | PUBLIC INTOXICATION        | 1054 BLOCK SPRINGDALE            |                           | N           | N                 | N           | APD         | 6424         | 
| CM                | 2011-10-01T00:00:00 | 00.00.00     | PUBLIC INTOXICATION        | 1200 BLOCK E.M FRANKLIN AVENUE   |                           | N           | N                 | N           | APD         | 5879         | 
| CM                | 2011-10-01T00:00:00 | 02.45.00     | PUBLIC INTOXICATION        | 10610 BLOCK MORADO CIRCLE        |                           | N           | N                 | Y           | APD         | 3476         | 
| CM                | 2011-10-01T00:00:00 | 06.00.00     | PUBLIC INTOXICATION        | 11011 BLOCK DOMAIN DRIVE         |                           | N           | N                 | Y           | APD         | 4611         | 
| CM                | 2011-10-01T00:00:00 | 00.00.00     | PUBLIC INTOXICATION        | 9300 BLOCK NORTH LAMAR BOULEVARD |                           | N           | N                 | Y           | APD         | 3759         | 
| CM                | 2011-10-01T00:00:00 | 09.30.00     | THEFT C - LESS THAN $50    | 6009 BLOCK NELSON OAKS DRIVE     |                           | N           | N                 | Y           | APD         | 5959         | 
```