# Dataset Inventory

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dataset-inventory) |
| Metadata | [Link](https://data.sfgov.org/api/views/y8fp-fbf5) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/y8fp-fbf5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/y8fp-fbf5/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | y8fp-fbf5 |
| Name | Dataset Inventory |
| Category | City Management and Ethics |
| Tags | inventory, open data, catalog |
| Created | 2015-03-26T18:22:56Z |
| Publication Date | 2017-03-24T17:15:23Z |

## Description

The dataset inventory provides a list of data maintained by departments that are candidates for open data publishing or have already been published and is collected in accordance with Chapter 22D of the Administrative Code. The inventory will be used in conjunction with department publishing plans to track progress toward meeting plan goals for each department. Department publishing plans are available at https://datasf.org/publishing/plans

## Columns

```ls
| Included | Schema Type    | Field Name               | Name                     | Data Type     | Render Type   |
| ======== | ============== | ======================== | ======================== | ============= | ============= |
| Yes      | series tag     | inventory_id             | Inventory ID             | text          | text          |
| Yes      | series tag     | department_or_division   | Department or Division   | text          | text          |
| Yes      | series tag     | dataset_name             | Dataset Name             | text          | text          |
| Yes      | series tag     | dataset_description      | Dataset Description      | text          | text          |
| Yes      | series tag     | data_classification      | Data Classification      | text          | text          |
| Yes      | series tag     | value                    | Value                    | text          | text          |
| Yes      | series tag     | department_priority      | Department Priority      | text          | text          |
| Yes      | time           | date_added               | Date Added               | calendar_date | calendar_date |
| Yes      | series tag     | publishing_status        | Publishing Status        | text          | text          |
| Yes      | series tag     | dataset_id               | Dataset ID               | text          | text          |
| Yes      | series tag     | dataset_link             | Dataset Link             | url           | url           |
| Yes      | series tag     | status_notes             | Status Notes             | text          | text          |
| No       |                | first_published          | First Published          | calendar_date | calendar_date |
| No       |                | date_published           | Date Published           | calendar_date | calendar_date |
| Yes      | series tag     | category                 | Category                 | text          | text          |
| Yes      | series tag     | required_fields_complete | Required Fields Complete | checkbox      | checkbox      |
| Yes      | series tag     | data_dictionary_attached | Data Dictionary Attached | checkbox      | checkbox      |
| Yes      | series tag     | metadata_complete        | Metadata Complete        | checkbox      | checkbox      |
| Yes      | series tag     | natively_hosted          | Natively Hosted          | checkbox      | checkbox      |
| No       |                | on_time                  | On Time                  | text          | text          |
| Yes      | series tag     | lag                      | Lag                      | checkbox      | checkbox      |
| Yes      | numeric metric | lag_days                 | Lag Days                 | number        | number        |
```

## Time Field

```ls
Value = date_added
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = first_published,date_published,on_time
```

## Data Commands

```ls
```

## Meta Commands

```ls
metric m:lag_days p:integer l:"Lag Days" d:"Number of days that data in the dataset lags the publishing. Only applicable to published datasets with a lag." t:dataTypeName=number

entity e:y8fp-fbf5 l:"Dataset Inventory" t:url=https://data.sfgov.org/api/views/y8fp-fbf5

property e:y8fp-fbf5 t:meta.view v:id=y8fp-fbf5 v:category="City Management and Ethics" v:averageRating=0 v:name="Dataset Inventory"

property e:y8fp-fbf5 t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:y8fp-fbf5 t:meta.view.owner v:id=dbag-6qd9 v:screenName=OpenData v:displayName=OpenData

property e:y8fp-fbf5 t:meta.view.tableauthor v:id=dbag-6qd9 v:screenName=OpenData v:roleName=publisher v:displayName=OpenData
```

## Top Records

```ls
| inventory_id | department_or_division                  | dataset_name                                        | dataset_description                                                                                                                                                                                                                                                                                                                                                                               | data_classification | value  | department_priority | date_added          | publishing_status | dataset_id | dataset_link                              | status_notes | first_published     | date_published      | category                   | required_fields_complete | data_dictionary_attached | metadata_complete | natively_hosted | on_time     | lag   | lag_days | 
| ============ | ======================================= | =================================================== | ================================================================================================================================================================================================================================================================================================================================================================================================= | =================== | ====== | =================== | =================== | ================= | ========== | ========================================= | ============ | =================== | =================== | ========================== | ======================== | ======================== | ================= | =============== | =========== | ===== | ======== | 
| ADM-0068     | GSA - City Administrator's Office       | LBE Certification Tracking Database                 | The LBE certification database is used to track, qualify, and process enrollment of applicants into CMD?s LBE program.                                                                                                                                                                                                                                                                            | Sensitive           | High   | Priority 2          | 2015-06-01T00:00:00 | Not Published     |            | [null, null]                              |              |                     |                     |                            |                          |                          |                   |                 |             |       |          | 
| ADP-0001     | Adult Probation                         | Weekly active clients (ctag)                        | Contains all active probationers, including case information, demographic information, and caseload/unit/officer assignment                                                                                                                                                                                                                                                                       | Protected           | High   | Priority 2          | 2015-04-30T00:00:00 | Not Published     |            | [null, null]                              |              |                     |                     |                            |                          |                          |                   |                 |             |       |          | 
| AIR-0016     | Airport                                 | Permitted ground transportation companies at SFO    |                                                                                                                                                                                                                                                                                                                                                                                                   | Public              | Medium | Priority 2          | 2015-04-30T00:00:00 | Not Published     |            | [null, null]                              |              |                     |                     |                            |                          |                          |                   |                 |             |       |          | 
| AIR-0017     | Airport                                 | Commercial vehicle information                      |                                                                                                                                                                                                                                                                                                                                                                                                   | Public              | Medium | Priority 2          | 2015-04-30T00:00:00 | Not Published     |            | [null, null]                              |              |                     |                     |                            |                          |                          |                   |                 |             |       |          | 
| AIR-0018     | Airport                                 | Commercial vehicle trip counts and locations at SFO |                                                                                                                                                                                                                                                                                                                                                                                                   | Public              | Medium | Priority 2          | 2015-04-30T00:00:00 | Not Published     |            | [null, null]                              |              |                     |                     |                            |                          |                          |                   |                 |             |       |          | 
| AIR-0040     | Airport                                 | SFO Revenues by Categories                          |                                                                                                                                                                                                                                                                                                                                                                                                   | Public              | Medium | Priority 2          | 2015-04-30T00:00:00 | Not Published     |            | [null, null]                              |              |                     |                     |                            |                          |                          |                   |                 |             |       |          | 
| BOS-0007     | Board of Supervisors                    | Meeting Calendar                                    | Report displaying a list of body meetings by month                                                                                                                                                                                                                                                                                                                                                | Public              | Low    | Priority 2          | 2015-04-30T00:00:00 | Not Published     |            | [null, null]                              |              |                     |                     |                            |                          |                          |                   |                 |             |       |          | 
| CII-0001     | Community Investment and Infrastructure | Resolution Index                                    | Commissions and Oversight Board's meetings data: Agenda, Minute, Memo and Resolution.                                                                                                                                                                                                                                                                                                             | Public              | Low    | Priority 2          | 2015-04-30T00:00:00 | Not Published     |            | [null, null]                              |              |                     |                     |                            |                          |                          |                   |                 |             |       |          | 
| CON-0007     | Controller                              | Employee Compensation                               | The San Francisco Controller's Office maintains a database of the salary and benefits paid to City employees since fiscal year 2013. This data is summarized and presented on the Employee Compensation report hosted at http://openbook.sfgov.org, and is also available in this dataset in CSV format. New data is added on a bi-annual basis when available for each fiscal and calendar year. | Public              | High   | Priority 1          | 2015-04-30T00:00:00 | Published         | 88g8-5mnd  | [http://data.sfgov.org/d/88g8-5mnd, null] |              | 2014-08-06T00:00:00 | 2014-08-05T00:00:00 | City Management and Ethics | true                     | true                     | true              | true            | Not on time | false |          | 
| CON-0024     | Controller                              | Scorecard Measures                                  | Departments collect and submit this data to the Controller's Office via the Budget and Performance Measurement System (BPMS). This data is collected to display on the City Performance Scorecard website, a site that provides timely performance information to the public and policy makers by major service area.                                                                             | Public              | High   | Priority 1          | 2016-01-20T00:00:00 | Published         | kc49-udxn  | [http://data.sfgov.org/d/kc49-udxn, null] |              | 2016-01-21T00:00:00 | 2016-01-20T00:00:00 | City Management and Ethics | true                     | true                     | true              | true            | Not on time | false |          | 
```