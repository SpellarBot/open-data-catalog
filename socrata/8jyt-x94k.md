# Municipal Court Caseload Information **Dataset removal in 2 months on September 1, 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/municipal-court-caseload-information-dataset-removal-in-2-months-on-september-1-2014) |
| Metadata | [Link](https://data.austintexas.gov/api/views/8jyt-x94k) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/8jyt-x94k/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/8jyt-x94k/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | 8jyt-x94k |
| Name | Municipal Court Caseload Information **Dataset removal in 2 months on September 1, 2014 |
| Attribution | City of Austin |
| Category | Public Safety |
| Tags | municipal, court, violation |
| Created | 2012-02-28T22:02:38Z |
| Publication Date | 2014-07-23T22:03:27Z |

## Description

This data is provided to help with analysis of various violations charged throughout the City of Austin. See Fiscal Year datasets for new the new format. 
**Dataset removal in 2 months on September 1, 2014**

## Columns

```ls
| Included | Schema Type | Field Name                 | Name                       | Data Type | Render Type |
| ======== | =========== | ========================== | ========================== | ========= | =========== |
| Yes      | series tag  | offense_case_type          | Offense Case Type          | text      | text        |
| Yes      | time        | offense_date               | Offense Date               | date      | date        |
| No       |             | offense_time               | Offense Time               | number    | text        |
| Yes      | series tag  | offense_charge_description | Offense Charge Description | text      | text        |
| Yes      | series tag  | offense_street_name        | Offense Street Name        | text      | text        |
| Yes      | series tag  | offense_cross_street_check | Offense Cross Street Check | text      | text        |
| Yes      | series tag  | offense_cross_street       | Offense Cross Street       | text      | text        |
| Yes      | series tag  | school_zone                | School Zone                | text      | text        |
| Yes      | series tag  | construction_zone          | Construction Zone          | text      | text        |
| Yes      | series tag  | case_closed                | Case Closed                | text      | text        |
```

## Time Field

```ls
Value = offense_date
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = offense_time
```

## Data Commands

```ls
series e:8jyt-x94k d:2010-04-29T07:00:00.000Z t:school_zone=N t:offense_case_type=TR t:construction_zone=N t:case_closed=Y t:offense_street_name="8000 BLOCK RESEARCH" t:offense_cross_street_check=N t:offense_charge_description="FAILED TO MAINTAIN FINANCIAL RESPONSIBILITY" m:row_number.8jyt-x94k=1

series e:8jyt-x94k d:2010-04-29T07:00:00.000Z t:school_zone=N t:offense_case_type=TR t:construction_zone=N t:case_closed=Y t:offense_street_name="8000 BLOCK RESEARCH" t:offense_cross_street_check=N t:offense_charge_description="FAILURE TO SIGNAL INTENT TO CHANGE LANES" m:row_number.8jyt-x94k=2

series e:8jyt-x94k d:2010-04-29T07:00:00.000Z t:school_zone=N t:offense_case_type=TR t:construction_zone=N t:case_closed=Y t:offense_street_name="1000 BLOCK NORTH U S 183" t:offense_cross_street_check=N t:offense_charge_description="SPEEDING-STATE HIGHWAYS" m:row_number.8jyt-x94k=3
```

## Meta Commands

```ls
metric m:row_number.8jyt-x94k p:long l:"Row Number"

entity e:8jyt-x94k l:"Municipal Court Caseload Information **Dataset removal in 2 months on September 1, 2014" t:attribution="City of Austin" t:url=https://data.austintexas.gov/api/views/8jyt-x94k

property e:8jyt-x94k t:meta.view v:id=8jyt-x94k v:category="Public Safety" v:attributionLink=http://www.austintexas.gov v:averageRating=0 v:name="Municipal Court Caseload Information **Dataset removal in 2 months on September 1, 2014" v:attribution="City of Austin"

property e:8jyt-x94k t:meta.view.owner v:id=9sae-3e9j v:screenName="Luz Lozano" v:displayName="Luz Lozano"

property e:8jyt-x94k t:meta.view.tableauthor v:id=9sae-3e9j v:screenName="Luz Lozano" v:roleName=publisher v:displayName="Luz Lozano"
```

## Top Records

```ls
| offense_case_type | offense_date | offense_time | offense_charge_description                           | offense_street_name      | offense_cross_street_check | offense_cross_street | school_zone | construction_zone | case_closed | 
| ================= | ============ | ============ | ==================================================== | ======================== | ========================== | ==================== | =========== | ================= | =========== | 
| TR                | 1272524400   | 22.40.00     | FAILED TO MAINTAIN FINANCIAL RESPONSIBILITY          | 8000 BLOCK RESEARCH      | N                          |                      | N           | N                 | Y           | 
| TR                | 1272524400   | 22.40.00     | FAILURE TO SIGNAL INTENT TO CHANGE LANES             | 8000 BLOCK RESEARCH      | N                          |                      | N           | N                 | Y           | 
| TR                | 1272524400   | 20.00.00     | SPEEDING-STATE HIGHWAYS                              | 1000 BLOCK NORTH U S 183 | N                          |                      | N           | N                 | Y           | 
| TR                | 1272524400   | 20.00.00     | NO SEAT BELT-DRIVER/PASSENGER                        | 1000 BLOCK NORTH U S 183 | N                          |                      | N           | N                 | Y           | 
| TR                | 1272524400   | 23.45.00     | SPEEDING - STATE HIGHWAYS - Less than 10% over limit | 1000 BLOCK RESEARCH      | N                          |                      | N           | N                 | Y           | 
| PK                | 1273042800   | 15.28.00     | PAY STATION RECEIPT NOT DISPLAYED                    | 700 10TH ST W            | N                          |                      | N           | N                 | Y           | 
| PK                | 1273042800   | 15.23.00     | EXPIRED PAY STATION RECEIPT                          | 800 RIO GRANDE ST        | N                          |                      | N           | N                 | Y           | 
| PK                | 1273042800   | 15.22.00     | EXPIRED PAY STATION RECEIPT                          | 800 RIO GRANDE ST        | N                          |                      | N           | N                 | Y           | 
| PK                | 1273042800   | 15.18.00     | EXPIRED PAY STATION RECEIPT                          | 900 RIO GRANDE ST        | N                          |                      | N           | N                 | Y           | 
| PK                | 1273042800   | 14.58.00     | PAY STATION RECEIPT NOT DISPLAYED                    | 900 SAN ANT. ST          | N                          |                      | N           | N                 | Y           | 
```