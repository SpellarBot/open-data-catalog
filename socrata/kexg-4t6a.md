# Municipal Court Caseload Information FY 2016

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/municipal-court-caseload-information-fy-2016) |
| Metadata | [Link](https://data.austintexas.gov/api/views/kexg-4t6a) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/kexg-4t6a/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/kexg-4t6a/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | kexg-4t6a |
| Name | Municipal Court Caseload Information FY 2016 |
| Attribution | City of Austin |
| Category | Public Safety |
| Tags | municipal, court, violation |
| Created | 2015-12-02T16:28:58Z |
| Publication Date | 2017-03-15T15:35:36Z |

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
series e:kexg-4t6a d:2016-04-07T00:00:00.000Z t:officer_code=0 t:school_zone=N t:offense_case_type=TR t:construction_zone=N t:agency=OTH t:case_closed=N t:offense_street_name="400 EAST 9TH STREET" t:offense_charge_description="FAILED TO MAINTAIN FINANCIAL RESPONSIBILITY" m:row_number.kexg-4t6a=1

series e:kexg-4t6a d:2015-10-01T00:00:00.000Z t:officer_code=4814 t:school_zone=N t:offense_case_type=CM t:construction_zone=N t:offense_cross_street="AT MOPAC EXPRESSWAY" t:agency=APD t:case_closed=Y t:offense_street_name="CESAR CHAVEZ STREET RAMP" t:offense_charge_description="PUBLIC INTOXICATION" m:row_number.kexg-4t6a=2

series e:kexg-4t6a d:2015-10-01T00:00:00.000Z t:officer_code=7337 t:school_zone=N t:offense_case_type=CM t:construction_zone=N t:agency=APD t:case_closed=Y t:offense_street_name="9900 BLOCK NORTH IH 35 SERVICE ROAD" t:offense_charge_description="POSSESSION OF DRUG PARAPHERNALIA" m:row_number.kexg-4t6a=3
```

## Meta Commands

```ls
metric m:row_number.kexg-4t6a p:long l:"Row Number"

entity e:kexg-4t6a l:"Municipal Court Caseload Information FY 2016" t:attribution="City of Austin" t:url=https://data.austintexas.gov/api/views/kexg-4t6a

property e:kexg-4t6a t:meta.view v:id=kexg-4t6a v:category="Public Safety" v:attributionLink=http://www.austintexas.gov v:averageRating=0 v:name="Municipal Court Caseload Information FY 2016" v:attribution="City of Austin"

property e:kexg-4t6a t:meta.view.license v:name="Public Domain"

property e:kexg-4t6a t:meta.view.owner v:id=rjt7-ysrk v:screenName="Jim Warren" v:displayName="Jim Warren"

property e:kexg-4t6a t:meta.view.tableauthor v:id=rjt7-ysrk v:screenName="Jim Warren" v:roleName=publisher v:displayName="Jim Warren"
```

## Top Records

```ls
| offense_case_type | offense_date        | offense_time | offense_charge_description                  | offense_street_name                 | offense_cross_street | school_zone | construction_zone | case_closed | agency | officer_code | 
| ================= | =================== | ============ | =========================================== | =================================== | ==================== | =========== | ================= | =========== | ====== | ============ | 
| TR                | 2016-04-07T00:00:00 | 00.00.00     | FAILED TO MAINTAIN FINANCIAL RESPONSIBILITY | 400 EAST 9TH STREET                 |                      | N           | N                 | N           | OTH    | 0            | 
| CM                | 2015-10-01T00:00:00 | 00.00.00     | PUBLIC INTOXICATION                         | CESAR CHAVEZ STREET RAMP            | AT MOPAC EXPRESSWAY  | N           | N                 | Y           | APD    | 4814         | 
| CM                | 2015-10-01T00:00:00 | 00.43.00     | POSSESSION OF DRUG PARAPHERNALIA            | 9900 BLOCK NORTH IH 35 SERVICE ROAD |                      | N           | N                 | Y           | APD    | 7337         | 
| PK                | 2015-10-01T00:00:00 | 09.47.00     | PARKING - TOW AWAY ZONE                     | 1100 SAN ANTONIO                    |                      | N           | N                 | Y           | PW     | 105          | 
| PK                | 2015-10-01T00:00:00 | 10.30.00     | Parking - Pay Station Receipt Not Displayed | 2800 NUECES                         |                      | N           | N                 | Y           | PW     | 71           | 
| PK                | 2015-10-01T00:00:00 | 12.19.00     | Parking - Pay Station Receipt Not Displayed | 500 BLOCK SAN JACINTO               |                      | N           | N                 | Y           | PW     | 224          | 
| PK                | 2015-10-01T00:00:00 | 12.25.00     | Parking - Pay Station Receipt Not Displayed | 25200 BLOCK RED RIVER               |                      | N           | N                 | Y           | PW     | 71           | 
| PK                | 2015-10-01T00:00:00 | 14.50.00     | Parking - Expired Pay Station Receipt       | 400 BLOCK WEST 10TH STREET          |                      | N           | N                 | Y           | PW     | 232          | 
| TR                | 2015-10-01T00:00:00 | 14.58.00     | SPEEDING - POSTED CITY STREET               | 1600 BLOCK EAST RIVERSIDE DRIVE     |                      | N           | N                 | Y           | APD    | 5906         | 
| PK                | 2015-10-01T00:00:00 | 15.04.00     | Parking - Pay Station Receipt Not Displayed | 700 EAST DEAN KEETON                |                      | N           | N                 | Y           | PW     | 71           | 
```