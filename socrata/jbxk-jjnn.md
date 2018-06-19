# Municipal Court Caseload Information FY 2015

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/municipal-court-caseload-information-fy-2015) |
| Metadata | [Link](https://data.austintexas.gov/api/views/jbxk-jjnn) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/jbxk-jjnn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/jbxk-jjnn/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | jbxk-jjnn |
| Name | Municipal Court Caseload Information FY 2015 |
| Attribution | City of Austin |
| Category | Public Safety |
| Tags | municipal, court, violation |
| Created | 2015-03-25T16:48:57Z |
| Publication Date | 2017-03-15T15:30:26Z |

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
| Yes      | series tag  | offense_cross_street       | Offense Cross Street       | text          | text          |
| Yes      | series tag  | school_zone                | School Zone                | text          | text          |
| Yes      | series tag  | construction_zone          | Construction Zone          | text          | text          |
| Yes      | series tag  | case_closed                | Case Closed                | text          | text          |
| Yes      | series tag  | agency                     | Agency                     | text          | text          |
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
series e:jbxk-jjnn d:2014-11-15T00:00:00.000Z t:officer_code=783 t:school_zone=N t:offense_case_type=CO t:construction_zone=N t:agency=APD t:case_closed=N t:offense_street_name="TEST LOCATION" t:offense_charge_description="POSSESSION OF TOBACCO" m:row_number.jbxk-jjnn=1

series e:jbxk-jjnn d:2015-06-30T00:00:00.000Z t:officer_code=270 t:school_zone=N t:offense_case_type=TR t:construction_zone=N t:agency=AIR t:case_closed=Y t:offense_charge_description="NO DRIVER LICENSE - MOTORCYCLE" m:row_number.jbxk-jjnn=2

series e:jbxk-jjnn d:2015-05-25T00:00:00.000Z t:officer_code=783 t:school_zone=N t:offense_case_type=TR t:construction_zone=N t:offense_cross_street="SERVICE ROAD IN THE MIDDLE OF THE" t:agency=APD t:case_closed=N t:offense_street_name="10000 BLOCK WEST BEN WHITE BOULEVARD" t:offense_charge_description="NO DRIVER LICENSE - MOTORCYCLE" m:row_number.jbxk-jjnn=3
```

## Meta Commands

```ls
metric m:row_number.jbxk-jjnn p:long l:"Row Number"

entity e:jbxk-jjnn l:"Municipal Court Caseload Information FY 2015" t:attribution="City of Austin" t:url=https://data.austintexas.gov/api/views/jbxk-jjnn

property e:jbxk-jjnn t:meta.view v:id=jbxk-jjnn v:category="Public Safety" v:attributionLink=http://www.austintexas.gov v:averageRating=0 v:name="Municipal Court Caseload Information FY 2015" v:attribution="City of Austin"

property e:jbxk-jjnn t:meta.view.owner v:id=rjt7-ysrk v:screenName="Jim Warren" v:displayName="Jim Warren"

property e:jbxk-jjnn t:meta.view.tableauthor v:id=rjt7-ysrk v:screenName="Jim Warren" v:roleName=publisher v:displayName="Jim Warren"
```

## Top Records

```ls
| offense_case_type | offense_date        | offense_time | offense_charge_description                  | offense_street_name                  | offense_cross_street              | school_zone | construction_zone | case_closed | agency | officer_code | 
| ================= | =================== | ============ | =========================================== | ==================================== | ================================= | =========== | ================= | =========== | ====== | ============ | 
| CO                | 2014-11-15T00:00:00 | 08.00.00     | POSSESSION OF TOBACCO                       | TEST LOCATION                        |                                   | N           | N                 | N           | APD    | 783          | 
| TR                | 2015-06-30T00:00:00 | 00.00.00     | NO DRIVER LICENSE - MOTORCYCLE              |                                      |                                   | N           | N                 | Y           | AIR    | 270          | 
| TR                | 2015-05-25T00:00:00 | 08.00.00     | NO DRIVER LICENSE - MOTORCYCLE              | 10000 BLOCK WEST BEN WHITE BOULEVARD | SERVICE ROAD IN THE MIDDLE OF THE | N           | N                 | N           | APD    | 783          | 
| CM                | 2014-10-01T00:00:00 | 00.00.00     | PUBLIC INTOXICATION                         | 2101 BURTON DRIVE                    |                                   | N           | N                 | N           | APD    | 7231         | 
| CM                | 2014-10-01T00:00:00 | 01.53.00     | PUBLIC INTOXICATION                         | 11218 CONCHOS TRAIL                  |                                   | N           | N                 | Y           | APD    | 7564         | 
| CM                | 2014-10-01T00:00:00 | 00.45.00     | PUBLIC INTOXICATION                         | 1747 EAST OLTORF STREET              |                                   | N           | N                 | Y           | APD    | 5680         | 
| PK                | 2014-10-01T00:00:00 | 09.44.00     | PARKING - TOW AWAY ZONE                     | 300 BLOCK 8TH STREET                 |                                   | N           | N                 | Y           | PW     | 176          | 
| PK                | 2014-10-01T00:00:00 | 09.44.00     | PARKING - TOW AWAY ZONE                     | 300 BLOCK 8TH STREET                 |                                   | N           | N                 | Y           | PW     | 176          | 
| PK                | 2014-10-01T00:00:00 | 12.36.00     | Parking - Pay Station Receipt Not Displayed | 1900 SAN ANTONIO STREET              |                                   | N           | N                 | Y           | PW     | 189          | 
| PK                | 2014-10-01T00:00:00 | 00.00.00     | Parking - Pay Station Receipt Not Displayed | 600 BLOCK EAST 9TH STREET            |                                   | N           | N                 | Y           | PW     | 64           | 
```