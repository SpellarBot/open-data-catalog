# Municipal Court Caseload Information FY 2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/municipal-court-caseload-information-fy-2010) |
| Metadata | [Link](https://data.austintexas.gov/api/views/c69b-fkfx) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/c69b-fkfx/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/c69b-fkfx/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | c69b-fkfx |
| Name | Municipal Court Caseload Information FY 2010 |
| Attribution | City of Austin |
| Category | Public Safety |
| Tags | court, municipal, violation |
| Created | 2013-11-13T23:04:42Z |
| Publication Date | 2015-10-06T14:48:18Z |

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
series e:c69b-fkfx d:2010-04-08T00:00:00.000Z t:officer_code=4813 t:school_zone=N t:offense_case_type=TR t:construction_zone=N t:case_closed=Y t:offense_street_name="300 BLOCK EAST FM 1626" t:agency_code=APD t:offense_charge_description="FAILURE TO MAINTAIN ASSURED CLEAR DIST" m:row_number.c69b-fkfx=1

series e:c69b-fkfx d:2010-04-15T00:00:00.000Z t:officer_code=3763 t:school_zone=Y t:offense_case_type=TR t:construction_zone=N t:case_closed=Y t:offense_street_name="4500 BLOCK MANCHACA ROAD" t:agency_code=APD t:offense_charge_description="SPEEDING - SCHOOL ZONE" m:row_number.c69b-fkfx=2

series e:c69b-fkfx d:2010-04-13T00:00:00.000Z t:officer_code=5914 t:school_zone=N t:offense_case_type=TR t:construction_zone=N t:case_closed=N t:offense_street_name="WEBBERVILLE AT PLEASANT VALLEY" t:agency_code=APD t:offense_charge_description="FAILURE TO YIELD - LEFT TURN INTERSECTION" m:row_number.c69b-fkfx=3
```

## Meta Commands

```ls
metric m:row_number.c69b-fkfx p:long l:"Row Number"

entity e:c69b-fkfx l:"Municipal Court Caseload Information FY 2010" t:attribution="City of Austin" t:url=https://data.austintexas.gov/api/views/c69b-fkfx

property e:c69b-fkfx t:meta.view v:id=c69b-fkfx v:category="Public Safety" v:attributionLink=http://www.austintexas.gov v:averageRating=0 v:name="Municipal Court Caseload Information FY 2010" v:attribution="City of Austin"

property e:c69b-fkfx t:meta.view.owner v:id=rjt7-ysrk v:screenName="Jim Warren" v:displayName="Jim Warren"

property e:c69b-fkfx t:meta.view.tableauthor v:id=rjt7-ysrk v:screenName="Jim Warren" v:roleName=publisher v:displayName="Jim Warren"
```

## Top Records

```ls
| offense_case_type | offense_date        | offense_time | offense_charge_description                  | offense_street_name                     | offense_cross_street_name | school_zone | construction_zone | case_closed | agency_code | officer_code | 
| ================= | =================== | ============ | =========================================== | ======================================= | ========================= | =========== | ================= | =========== | =========== | ============ | 
| TR                | 2010-04-08T00:00:00 | 16.24.00     | FAILURE TO MAINTAIN ASSURED CLEAR DIST      | 300 BLOCK EAST FM 1626                  |                           | N           | N                 | Y           | APD         | 4813         | 
| TR                | 2010-04-15T00:00:00 | 07.30.00     | SPEEDING - SCHOOL ZONE                      | 4500 BLOCK MANCHACA ROAD                |                           | Y           | N                 | Y           | APD         | 3763         | 
| TR                | 2010-04-13T00:00:00 | 22.09.00     | FAILURE TO YIELD - LEFT TURN INTERSECTION   | WEBBERVILLE AT PLEASANT VALLEY          |                           | N           | N                 | N           | APD         | 5914         | 
| RL                | 2010-09-16T00:00:00 | 01.39.00     | Ran Red Light - Photo                       | S/B PLEASANT VALLEY RD AND RIVERSIDE DR |                           |             |                   | Y           | APD         | 4731         | 
| RL                | 2010-09-27T00:00:00 | 09.55.00     | Ran Red Light - Photo                       | HOWARD LN AND BURNET RD                 |                           |             |                   | Y           | APD         | 2356         | 
| RL                | 2010-09-26T00:00:00 | 11.18.00     | Ran Red Light - Photo                       | IH 35 AND 11TH ST                       |                           |             |                   | Y           | APD         | 2356         | 
| TR                | 2010-04-13T00:00:00 | 15.15.00     | FAILED TO MAINTAIN FINANCIAL RESPONSIBILITY | 1000 BLOCK NORTH I H 35                 |                           | N           | N                 | Y           | APD         | 4583         | 
| TR                | 2010-04-13T00:00:00 | 09.45.00     | FAILED TO MAINTAIN FINANCIAL RESPONSIBILITY | 3900 BLOCK SOUTH CONGRESS AVEUNE        |                           | N           | N                 | N           | APD         | 4840         | 
| TR                | 2010-04-13T00:00:00 | 09.45.00     | NO DRIVERS LICENSE                          | 3900 BLOCK SOUTH CONGRESS AVEUNE        |                           | N           | N                 | N           | APD         | 4840         | 
| TR                | 2010-04-13T00:00:00 | 09.45.00     | EXPIRED INSPECTION STICKER                  | 3900 BLOCK SOUTH CONGRESS AVEUNE        |                           | N           | N                 | N           | APD         | 4840         | 
```