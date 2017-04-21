# Monthly Indicators

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/monthly-indicators-3c6be) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/8r6c-ydwk) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/8r6c-ydwk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/8r6c-ydwk/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 8r6c-ydwk |
| Name | Monthly Indicators |
| Attribution | Office of Chief Medical Examiner (OCME) |
| Category | City Government |
| Created | 2016-08-01T21:48:35Z |
| Publication Date | 2016-08-01T22:21:14Z |

## Description

Monthly OCME Indicators

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type     | Render Type   |
| ======== | ============== | =================== | =================== | ============= | ============= |
| Yes      | series tag     | agency_name         | Agency Name         | text          | text          |
| Yes      | series tag     | dataset_title       | Dataset Title       | text          | text          |
| Yes      | series tag     | dataset_description | Dataset Description | text          | text          |
| Yes      | series tag     | update_frequency    | Update Frequency    | text          | text          |
| Yes      | time           | release_date        | Release Date        | calendar_date | calendar_date |
| Yes      | numeric metric | july_2015           | July, 2015          | number        | number        |
| Yes      | numeric metric | august_2015         | August, 2015        | number        | number        |
| Yes      | numeric metric | september_2015      | September, 2015     | number        | number        |
| Yes      | numeric metric | october_2015        | October, 2015       | number        | number        |
| Yes      | numeric metric | november_2015       | November, 2015      | number        | number        |
| Yes      | numeric metric | december_2015       | December, 2015      | number        | number        |
| Yes      | numeric metric | january_2016        | January, 2016       | number        | number        |
| Yes      | numeric metric | february_2016       | February, 2016      | number        | number        |
| Yes      | numeric metric | march_2016          | March, 2016         | number        | number        |
| Yes      | numeric metric | april_2016          | April, 2016         | number        | number        |
| Yes      | numeric metric | may_2016            | May, 2016           | number        | number        |
```

## Time Field

```ls
Value = release_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:8r6c-ydwk d:2016-08-01T00:00:00.000Z t:dataset_title="Scene investigations" t:update_frequency=Monthly t:dataset_description="Cases where a Scene Investigation was conducted by the OCME" t:agency_name="Office of Chief Medical Examiner (OCME)" m:october_2015=434 m:january_2016=527 m:may_2016=508 m:november_2015=349 m:august_2015=426 m:march_2016=541 m:april_2016=499 m:july_2015=414 m:february_2016=472 m:september_2015=401 m:december_2015=448

series e:8r6c-ydwk d:2016-08-01T00:00:00.000Z t:dataset_title="Evidence submissions received for DNA analysis" t:update_frequency=Monthly t:dataset_description="Number of cases received by the OCME for DNA analysis" t:agency_name="Office of Chief Medical Examiner (OCME)" m:october_2015=1356 m:january_2016=1403 m:may_2016=1643 m:november_2015=1281 m:august_2015=1409 m:march_2016=1647 m:april_2016=1973 m:july_2015=1272 m:february_2016=1497 m:september_2015=1402 m:december_2015=1381

series e:8r6c-ydwk d:2016-08-01T00:00:00.000Z t:dataset_title="Cases Where Medical Examiner Takes Jurisdiction" t:update_frequency=Monthly t:dataset_description="Number of cases where OCME took jurisdiction" t:agency_name="Office of Chief Medical Examiner (OCME)" m:october_2015=657 m:january_2016=657 m:may_2016=647 m:november_2015=531 m:august_2015=598 m:march_2016=654 m:april_2016=653 m:july_2015=593 m:february_2016=594 m:september_2015=596 m:december_2015=573
```

## Meta Commands

```ls
metric m:july_2015 p:float l:"July, 2015" t:dataTypeName=number

metric m:august_2015 p:float l:"August, 2015" t:dataTypeName=number

metric m:september_2015 p:float l:"September, 2015" t:dataTypeName=number

metric m:october_2015 p:float l:"October, 2015" t:dataTypeName=number

metric m:november_2015 p:float l:"November, 2015" t:dataTypeName=number

metric m:december_2015 p:float l:"December, 2015" t:dataTypeName=number

metric m:january_2016 p:float l:"January, 2016" t:dataTypeName=number

metric m:february_2016 p:float l:"February, 2016" t:dataTypeName=number

metric m:march_2016 p:float l:"March, 2016" t:dataTypeName=number

metric m:april_2016 p:float l:"April, 2016" t:dataTypeName=number

metric m:may_2016 p:float l:"May, 2016" t:dataTypeName=number

entity e:8r6c-ydwk l:"Monthly Indicators" t:attribution="Office of Chief Medical Examiner (OCME)" t:url=https://data.cityofnewyork.us/api/views/8r6c-ydwk

property e:8r6c-ydwk t:meta.view v:id=8r6c-ydwk v:category="City Government" v:averageRating=0 v:name="Monthly Indicators" v:attribution="Office of Chief Medical Examiner (OCME)"

property e:8r6c-ydwk t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:8r6c-ydwk t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| agency_name                             | dataset_title                                                           | dataset_description                                                      | update_frequency | release_date        | july_2015 | august_2015 | september_2015 | october_2015 | november_2015 | december_2015 | january_2016 | february_2016 | march_2016 | april_2016 | may_2016 | 
| ======================================= | ======================================================================= | ======================================================================== | ================ | =================== | ========= | =========== | ============== | ============ | ============= | ============= | ============ | ============= | ========== | ========== | ======== | 
| Office of Chief Medical Examiner (OCME) | Scene investigations                                                    | Cases where a Scene Investigation was conducted by the OCME              | Monthly          | 2016-08-01T00:00:00 | 414.00    | 426.00      | 401.00         | 434.00       | 349.00        | 448.00        | 527.00       | 472.00        | 541.00     | 499.00     | 508.00   | 
| Office of Chief Medical Examiner (OCME) | Evidence submissions received for DNA analysis                          | Number of cases received by the OCME for DNA analysis                    | Monthly          | 2016-08-01T00:00:00 | 1272.00   | 1409.00     | 1402.00        | 1356.00      | 1281.00       | 1381.00       | 1403.00      | 1497.00       | 1647.00    | 1973.00    | 1643.00  | 
| Office of Chief Medical Examiner (OCME) | Cases Where Medical Examiner Takes Jurisdiction                         | Number of cases where OCME took jurisdiction                             | Monthly          | 2016-08-01T00:00:00 | 593.00    | 598.00      | 596.00         | 657.00       | 531.00        | 573.00        | 657.00       | 594.00        | 654.00     | 653.00     | 647.00   | 
| Office of Chief Medical Examiner (OCME) | MLI Scene Arrivals in Median time (hours)                               | Time to arrive at the Scene                                              | Monthly          | 2016-08-01T00:00:00 | 2.00      | 2.02        | 2.04           | 2.05         | 1.88          | 1.92          | 2.12         | 2.06          | 2.04       | 2.32       | 2.24     | 
| Office of Chief Medical Examiner (OCME) | Cremation Requests                                                      | Number of Cremation Requests received by the OCME                        | Monthly          | 2016-08-01T00:00:00 | 1280.00   | 1203.00     | 1207.00        | 1321.00      | 1167.00       | 1328.00       | 1363.00      | 1356.00       | 1405.00    | 1295.00    | 1225.00  | 
| Office of Chief Medical Examiner (OCME) | Cremation Requests Processed in Median time (minutes)                   | Cremation request processing time                                        | Monthly          | 2016-08-01T00:00:00 | 174.95    | 196.59      | 166.44         | 152.43       | 157.66        | 170.16        | 154.89       | 142.94        | 175.31     | 225.12     | 177.51   | 
| Office of Chief Medical Examiner (OCME) | Autopsies Performed                                                     | Number of Autopsies performed by the OCME                                | Monthly          | 2016-08-01T00:00:00 | 390.00    | 424.00      | 396.00         | 431.00       | 397.00        | 382.00        | 448.00       | 391.00        | 461.00     | 470.00     | 458.00   | 
| Office of Chief Medical Examiner (OCME) | External Examinations                                                   | Number of External Exams (No-Autopsy) performed by the OCME              | Monthly          | 2016-08-01T00:00:00 | 173.00    | 159.00      | 170.00         | 200.00       | 125.00        | 168.00        | 196.00       | 189.00        | 177.00     | 173.00     | 171.00   | 
| Office of Chief Medical Examiner (OCME) | Autopsy Reports Completed in Median time (median time in calendar days) | Time to finalize autopsy report                                          | Monthly          | 2016-08-01T00:00:00 | 69.00     | 78.00       | 53.00          | 49.00        | 59.00         | 79.00         | 106.00       | 98.00         | 83.50      | 59.50      | 49.00    | 
| Office of Chief Medical Examiner (OCME) | Toxicology Cases Received                                               | Number of Toxicology cases received by the OCME (Medical Examiner Cases) | Monthly          | 2016-08-01T00:00:00 | 406.00    | 417.00      | 402.00         | 400.00       | 409.00        | 378.00        | 427.00       | 407.00        | 510.00     | 460.00     | 459.00   | 
```