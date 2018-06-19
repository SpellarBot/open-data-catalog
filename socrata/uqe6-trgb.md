# Municipal Court Caseload Information FY 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/municipal-court-caseload-information-fy-2014) |
| Metadata | [Link](https://data.austintexas.gov/api/views/uqe6-trgb) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/uqe6-trgb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/uqe6-trgb/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | uqe6-trgb |
| Name | Municipal Court Caseload Information FY 2014 |
| Attribution | City of Austin |
| Category | Public Safety |
| Tags | municipal, court, violation |
| Created | 2013-11-14T15:37:45Z |
| Publication Date | 2017-03-15T15:24:45Z |

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
series e:uqe6-trgb d:2013-11-18T00:00:00.000Z t:officer_code=5901 t:school_zone=N t:offense_case_type=TR t:construction_zone=N t:case_closed=Y t:offense_street_name="7000 BLOCK GRAND CANYON DRIVE" t:agency_code=APD t:offense_charge_description="DRIVING WHILE LICENSE INVALID - SUSPENDED" m:row_number.uqe6-trgb=1

series e:uqe6-trgb d:2014-09-23T00:00:00.000Z t:officer_code=204 t:school_zone=N t:offense_case_type=PK t:construction_zone=N t:case_closed=Y t:offense_street_name="3100 GROOMS AV" t:agency_code=PW t:offense_charge_description="Duplicate Violation" m:row_number.uqe6-trgb=2

series e:uqe6-trgb d:2014-01-06T00:00:00.000Z t:officer_code=7565 t:school_zone=N t:offense_case_type=TR t:construction_zone=N t:case_closed=N t:offense_street_name="TEST LOCATION" t:agency_code=APD t:offense_charge_description="DRIVING WHILE LICENSE INVALID - SUSPENDED" m:row_number.uqe6-trgb=3
```

## Meta Commands

```ls
metric m:row_number.uqe6-trgb p:long l:"Row Number"

entity e:uqe6-trgb l:"Municipal Court Caseload Information FY 2014" t:attribution="City of Austin" t:url=https://data.austintexas.gov/api/views/uqe6-trgb

property e:uqe6-trgb t:meta.view v:id=uqe6-trgb v:category="Public Safety" v:attributionLink=http://www.austintexas.gov v:averageRating=0 v:name="Municipal Court Caseload Information FY 2014" v:attribution="City of Austin"

property e:uqe6-trgb t:meta.view.owner v:id=rjt7-ysrk v:screenName="Jim Warren" v:displayName="Jim Warren"

property e:uqe6-trgb t:meta.view.tableauthor v:id=rjt7-ysrk v:screenName="Jim Warren" v:roleName=publisher v:displayName="Jim Warren"
```

## Top Records

```ls
| offense_case_type | offense_date        | offense_time | offense_charge_description                  | offense_street_name                    | offense_cross_street_name | school_zone | construction_zone | case_closed | agency_code | officer_code | 
| ================= | =================== | ============ | =========================================== | ====================================== | ========================= | =========== | ================= | =========== | =========== | ============ | 
| TR                | 2013-11-18T00:00:00 | 22.08.00     | DRIVING WHILE LICENSE INVALID - SUSPENDED   | 7000 BLOCK GRAND CANYON DRIVE          |                           | N           | N                 | Y           | APD         | 5901         | 
| PK                | 2014-09-23T00:00:00 | 08.00.00     | Duplicate Violation                         | 3100 GROOMS AV                         |                           | N           | N                 | Y           | PW          | 204          | 
| TR                | 2014-01-06T00:00:00 | 08.00.00     | DRIVING WHILE LICENSE INVALID - SUSPENDED   | TEST LOCATION                          |                           | N           | N                 | N           | APD         | 7565         | 
| TR                | 2013-10-01T00:00:00 | 00.05.00     | FAILED TO MAINTAIN FINANCIAL RESP 2ND CONV  | EAST RIVERSIDE DRIVE AND               | MONTOPOLIS DRIVE          | N           | N                 | Y           | APD         | 7293         | 
| TR                | 2013-10-01T00:00:00 | 00.05.00     | DEFECTIVE LICENSE PLATE LIGHT               | EAST RIVERSIDE DRIVE AND               | MONTOPOLIS DRIVE          | N           | N                 | Y           | APD         | 7293         | 
| CM                | 2013-10-01T00:00:00 | 00.41.00     | PUBLIC INTOXICATION                         | 9409 STONELAKE BOULEVARD               |                           | N           | N                 | Y           | APD         | 7429         | 
| CM                | 2013-10-01T00:00:00 | 01.36.00     | PUBLIC INTOXICATION                         | 6TH STREET AND ROBERT T. MARTINEZ      |                           | N           | N                 | N           | APD         | 7492         | 
| PK                | 2013-10-01T00:00:00 | 11.09.00     | Parking - Pay Station Receipt Not Displayed | 400 BLOCK WEST 5TH STREET              |                           | N           | N                 | Y           | PW          | 176          | 
| PK                | 2013-10-01T00:00:00 | 09.55.00     | PARKING - EXPIRED METER                     | 400 SAN JACINTO                        |                           | N           | N                 | Y           | PW          | 105          | 
| TR                | 2013-10-01T00:00:00 | 08.33.00     | CROSSING PROPERTY TO TURN RIGHT OR LEFT     | 12900 BLOCK RESEARCH BOULEVARD SERVICE | ROAD                      | N           | N                 | Y           | APD         | 4004         | 
```