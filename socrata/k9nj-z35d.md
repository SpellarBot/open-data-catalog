# Housing Code Enforcement

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/housing-code-enforcement) |
| Metadata | [Link](https://data.montgomerycountymd.gov/api/views/k9nj-z35d) |
| Data: JSON | [100 Rows](https://data.montgomerycountymd.gov/api/views/k9nj-z35d/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.montgomerycountymd.gov/api/views/k9nj-z35d/rows.csv?max_rows=100) |
| Host | data.montgomerycountymd.gov |
| Id | k9nj-z35d |
| Name | Housing Code Enforcement |
| Category | Consumer/Housing |
| Created | 2015-06-17T00:31:59Z |
| Publication Date | 2015-07-22T15:46:15Z |

## Description

Housing Code Enforcement data from 2013 to the present , including violations identified

## Columns

```ls
| Included | Schema Type | Field Name                   | Name                         | Data Type     | Render Type   |
| ======== | =========== | ============================ | ============================ | ============= | ============= |
| Yes      | series tag  | street_number                | Street Number                | text          | text          |
| Yes      | series tag  | street_name                  | Street Name                  | text          | text          |
| Yes      | series tag  | street_type                  | Street Type                  | text          | text          |
| Yes      | series tag  | unit_number                  | Unit Number                  | text          | text          |
| Yes      | series tag  | city                         | City                         | text          | text          |
| Yes      | series tag  | zip_code                     | Zip Code                     | text          | text          |
| Yes      | time        | date_filed                   | Date Filed                   | calendar_date | calendar_date |
| No       |             | date_assigned                | Date Assigned                | calendar_date | calendar_date |
| No       |             | inspection_date              | Inspection Date              | calendar_date | calendar_date |
| Yes      | series tag  | violation_id                 | Violation ID                 | text          | number        |
| Yes      | series tag  | location_description         | Location Description         | text          | text          |
| Yes      | series tag  | item                         | Item                         | text          | text          |
| Yes      | series tag  | condition                    | Condition                    | text          | text          |
| Yes      | series tag  | action                       | Action                       | text          | text          |
| Yes      | series tag  | code_reference               | Code Reference               | text          | text          |
| Yes      | series tag  | case_number                  | Case Number                  | text          | number        |
| Yes      | series tag  | corrected                    | Corrected                    | text          | text          |
| No       |             | date_closed                  | Date Closed                  | calendar_date | calendar_date |
| Yes      | series tag  | disposition                  | Disposition                  | text          | text          |
| Yes      | series tag  | service_request_number       | Service Request Number       | text          | text          |
| No       |             | service_request_created_date | Service Request Created Date | calendar_date | calendar_date |
| No       |             | service_request_closed_time  | Service Request Closed Time  | calendar_date | calendar_date |
| Yes      | series tag  | service_request_status       | Service Request Status       | text          | text          |
| No       |             | latitude                     | Latitude                     | number        | number        |
| No       |             | longitude                    | Longitude                    | number        | number        |
| Yes      | series tag  | unique_identifier            | Unique Identifier            | text          | text          |
```

## Time Field

```ls
Value = date_filed
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = date_assigned,inspection_date,date_closed,service_request_created_date,service_request_closed_time,latitude,longitude
```

## Data Commands

```ls
series e:k9nj-z35d d:2016-03-28T00:00:00.000Z t:case_number=133535 t:zip_code=20905 t:condition="General Condition" t:corrected=2017-01-05 t:street_name=ANSTED t:code_reference=26-9(b)(5) t:service_request_number=1289478766 t:location_description=Exterior t:city="SILVER SPRING" t:unique_identifier=1335351289478766335924 t:violation_id=335924 t:item="Tree/ Tree Limbs/ Shrubbery" t:action="Remove dead tree - standing" t:service_request_status=Closed t:street_number=14111 t:disposition="no response from complainant" t:street_type=RD m:row_number.k9nj-z35d=1

series e:k9nj-z35d d:2016-04-01T00:00:00.000Z t:case_number=133652 t:unique_identifier=1336520 t:zip_code=20886 t:street_name=CAPEHART t:street_number=19112 t:disposition="HOUSE VACANT-FOR SALE" t:street_type=DR t:city=GAITHERSBURG m:row_number.k9nj-z35d=2

series e:k9nj-z35d d:2016-04-01T00:00:00.000Z t:case_number=133653 t:unique_identifier=1336530 t:zip_code=20886 t:street_name=CAPEHART t:street_number=19116 t:disposition="Inspection Approved" t:street_type=DR t:city=GAITHERSBURG m:row_number.k9nj-z35d=3
```

## Meta Commands

```ls
metric m:row_number.k9nj-z35d p:long l:"Row Number"

entity e:k9nj-z35d l:"Housing Code Enforcement" t:url=https://data.montgomerycountymd.gov/api/views/k9nj-z35d

property e:k9nj-z35d t:meta.view v:id=k9nj-z35d v:category=Consumer/Housing v:averageRating=0 v:name="Housing Code Enforcement"

property e:k9nj-z35d t:meta.view.license v:name="Public Domain"

property e:k9nj-z35d t:meta.view.owner v:id=ajn4-zy65 v:screenName="MCG ESB Service" v:lastNotificationSeenAt=1491401045 v:displayName="MCG ESB Service"

property e:k9nj-z35d t:meta.view.tableauthor v:id=ajn4-zy65 v:screenName="MCG ESB Service" v:roleName=administrator v:lastNotificationSeenAt=1491401045 v:displayName="MCG ESB Service"
```

## Top Records

```ls
| street_number | street_name   | street_type | unit_number | city               | zip_code | date_filed          | date_assigned       | inspection_date     | violation_id | location_description | item                        | condition         | action                      | code_reference | case_number | corrected  | date_closed         | disposition                   | service_request_number | service_request_created_date | service_request_closed_time | service_request_status | latitude           | longitude           | unique_identifier      | 
| ============= | ============= | =========== | =========== | ================== | ======== | =================== | =================== | =================== | ============ | ==================== | =========================== | ================= | =========================== | ============== | =========== | ========== | =================== | ============================= | ====================== | ============================ | =========================== | ====================== | ================== | =================== | ====================== | 
| 14111         | ANSTED        | RD          |             | SILVER SPRING      | 20905    | 2016-03-28T00:00:00 | 2016-03-28T00:00:00 | 2016-05-04T00:00:00 | 335924       | Exterior             | Tree/ Tree Limbs/ Shrubbery | General Condition | Remove dead tree - standing | 26-9(b)(5)     | 133535      | 2017-01-05 | 2017-01-05T00:00:00 | no response from complainant  | 1289478766             | 2016-03-24T00:00:00          | 2017-01-05T00:00:00         | Closed                 | 39.087336267000069 | -76.973093807999987 | 1335351289478766335924 | 
| 19112         | CAPEHART      | DR          |             | GAITHERSBURG       | 20886    | 2016-04-01T00:00:00 | 2016-04-01T00:00:00 |                     |              |                      |                             |                   |                             |                | 133652      |            | 2017-01-03T00:00:00 | HOUSE VACANT-FOR SALE         |                        |                              |                             |                        | 39.170002984000064 | -77.216639675999943 | 1336520                | 
| 19116         | CAPEHART      | DR          |             | GAITHERSBURG       | 20886    | 2016-04-01T00:00:00 | 2016-04-01T00:00:00 |                     |              |                      |                             |                   |                             |                | 133653      |            | 2017-01-05T00:00:00 | Inspection Approved           |                        |                              |                             |                        | 39.170172103000027 | -77.21649660199995  | 1336530                | 
| 19032         | CAPEHART      | DR          |             | GAITHERSBURG       | 20886    | 2016-04-01T00:00:00 | 2016-04-01T00:00:00 |                     |              |                      |                             |                   |                             |                | 133655      |            | 2017-01-05T00:00:00 | Inspection Approved           |                        |                              |                             |                        | 39.167755310000075 | -77.218017663999944 | 1336550                | 
| 19048         | CAPEHART      | DR          |             | MONTGOMERY VILLAGE | 20886    | 2016-04-01T00:00:00 | 2016-04-01T00:00:00 |                     |              |                      |                             |                   |                             |                | 133657      |            | 2017-01-05T00:00:00 | Inspection Approved           |                        |                              |                             |                        | 39.167511403000049 | -77.217729760999987 | 1336570                | 
| 19024         | CAPEHART      | DR          |             | GAITHERSBURG       | 20886    | 2016-04-01T00:00:00 | 2016-04-01T00:00:00 |                     |              |                      |                             |                   |                             |                | 133658      |            | 2017-01-05T00:00:00 | Inspection Approved           |                        |                              |                             |                        | 39.167868730000066 | -77.218098070999986 | 1336580                | 
| 3412          | JANET         | RD          |             | SILVER SPRING      | 20906    | 2016-05-06T00:00:00 | 2016-05-06T00:00:00 |                     |              |                      |                             |                   |                             |                | 134325      |            | 2017-01-05T00:00:00 | Violation Unfounded           | 1292689677             | 2016-05-03T00:00:00          | 2017-01-05T00:00:00         | Closed                 | 39.066214504000072 | -77.068233333999956 | 13432512926896770      | 
| 3412          | JANET         | RD          |             | SILVER SPRING      | 20906    | 2016-05-06T00:00:00 | 2016-05-06T00:00:00 |                     |              |                      |                             |                   |                             |                | 134325      |            | 2017-01-05T00:00:00 | Violation Unfounded           | 1295427792             | 2016-06-15T00:00:00          | 2017-01-05T00:00:00         | Closed                 | 39.066214504000072 | -77.068233333999956 | 13432512954277920      | 
| 919           | BRICK MANOR   | CIR         |             | SILVER SPRING      | 20905    | 2016-05-16T00:00:00 | 2016-05-16T00:00:00 | 2016-07-01T00:00:00 | 339445       | Entire Unit          | Other                       | Other             | Other                       |                | 134549      | 2017-01-04 | 2017-01-04T00:00:00 | Owner Occupied -Refused Entry | 1293444297             | 2016-05-13T00:00:00          | 2017-01-04T00:00:00         |                        | 39.121081549000053 | -77.030115930999955 | 1345491293444297339445 | 
| 14426         | BONIFANT PARK | PL          |             | SILVER SPRING      | 20906    | 2016-06-07T00:00:00 | 2016-06-07T00:00:00 | 2016-07-01T00:00:00 | 339447       | Entire Unit          | Other                       | Other             | Other                       |                | 135022      | 2017-01-04 | 2017-01-04T00:00:00 | Owner Occupied -Refused Entry | 1294612139             | 2016-06-02T00:00:00          | 2017-01-04T00:00:00         |                        | 39.094477116000064 | -77.038663600999939 | 1350221294612139339447 | 
```