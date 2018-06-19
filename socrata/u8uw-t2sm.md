# Municipal Court Caseload Information FY 2011

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/municipal-court-caseload-information-fy-2011) |
| Metadata | [Link](https://data.austintexas.gov/api/views/u8uw-t2sm) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/u8uw-t2sm/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/u8uw-t2sm/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | u8uw-t2sm |
| Name | Municipal Court Caseload Information FY 2011 |
| Attribution | City of Austin |
| Category | Public Safety |
| Tags | municipal, court, violation |
| Created | 2013-11-14T14:49:11Z |
| Publication Date | 2016-09-22T17:19:06Z |

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
series e:u8uw-t2sm d:2010-10-04T00:00:00.000Z t:officer_code=1518 t:school_zone=N t:offense_case_type=TR t:construction_zone=N t:case_closed=Y t:offense_street_name="12300 BLOCK RIATA TRACE" t:agency_code=APD t:offense_charge_description="SPEEDING - POSTED CITY STREET" m:row_number.u8uw-t2sm=1

series e:u8uw-t2sm d:2010-10-01T00:00:00.000Z t:officer_code=6438 t:school_zone=N t:offense_case_type=CM t:construction_zone=N t:case_closed=Y t:offense_street_name="2001 EAST RIVERSIDE DRIVE" t:agency_code=APD t:offense_charge_description="PUBLIC INTOXICATION" m:row_number.u8uw-t2sm=2

series e:u8uw-t2sm d:2010-10-01T00:00:00.000Z t:officer_code=6161 t:school_zone=N t:offense_case_type=TR t:construction_zone=N t:case_closed=Y t:offense_street_name="EAST 17TH STREET AND MAPLE" t:agency_code=APD t:offense_charge_description="RAN STOP SIGN" m:row_number.u8uw-t2sm=3
```

## Meta Commands

```ls
metric m:row_number.u8uw-t2sm p:long l:"Row Number"

entity e:u8uw-t2sm l:"Municipal Court Caseload Information FY 2011" t:attribution="City of Austin" t:url=https://data.austintexas.gov/api/views/u8uw-t2sm

property e:u8uw-t2sm t:meta.view v:id=u8uw-t2sm v:category="Public Safety" v:attributionLink=http://www.austintexas.gov v:averageRating=0 v:name="Municipal Court Caseload Information FY 2011" v:attribution="City of Austin"

property e:u8uw-t2sm t:meta.view.owner v:id=rjt7-ysrk v:screenName="Jim Warren" v:displayName="Jim Warren"

property e:u8uw-t2sm t:meta.view.tableauthor v:id=rjt7-ysrk v:screenName="Jim Warren" v:roleName=publisher v:displayName="Jim Warren"
```

## Top Records

```ls
| offense_case_type | offense_date        | offense_time | offense_charge_description        | offense_street_name               | offense_cross_street_name | school_zone | construction_zone | case_closed | agency_code | officer_code | 
| ================= | =================== | ============ | ================================= | ================================= | ========================= | =========== | ================= | =========== | =========== | ============ | 
| TR                | 2010-10-04T00:00:00 | 14.15.00     | SPEEDING - POSTED CITY STREET     | 12300 BLOCK RIATA TRACE           |                           | N           | N                 | Y           | APD         | 1518         | 
| CM                | 2010-10-01T00:00:00 | 00.00.00     | PUBLIC INTOXICATION               | 2001 EAST RIVERSIDE DRIVE         |                           | N           | N                 | Y           | APD         | 6438         | 
| TR                | 2010-10-01T00:00:00 | 00.45.00     | RAN STOP SIGN                     | EAST 17TH STREET AND MAPLE        |                           | N           | N                 | Y           | APD         | 6161         | 
| TR                | 2010-10-01T00:00:00 | 00.45.00     | FAILED TO DISPLAY DRIVERS LICENSE | EAST 17TH STREET AND MAPLE        |                           | N           | N                 | Y           | APD         | 6161         | 
| CM                | 2010-10-01T00:00:00 | 02.03.00     | PUBLIC INTOXICATION               | 5426 MANCHACA ROAD                |                           | N           | N                 | Y           | APD         | 6287         | 
| CM                | 2010-10-01T00:00:00 | 00.00.00     | PUBLIC INTOXICATION               | 7900 BLOCK BEN WHITE BOULEVARD    |                           | N           | N                 | Y           | APD         | 5193         | 
| TR                | 2010-10-01T00:00:00 | 09.40.00     | RAN STOP SIGN                     | SHILOH AT MANCHACA                |                           | N           | N                 | Y           | APD         | 4669         | 
| PK                | 2010-10-01T00:00:00 | 10.27.00     | PARKING - IN HANDICAPPED SPACE    | 400 W 2ND ST                      |                           | N           | N                 | Y           | PW          | 179          | 
| PK                | 2010-10-01T00:00:00 | 10.48.00     | PARKING - TOW AWAY ZONE           | 600 W 10TH ST                     |                           | N           | N                 | Y           | PW          | 189          | 
| TR                | 2010-10-01T00:00:00 | 08.00.00     | EXPIRED INSPECTION STICKER        | 3600 BLOCK PRESIDENTIAL BOULEVARD |                           | N           | N                 | Y           | APD         | 6671         | 
```