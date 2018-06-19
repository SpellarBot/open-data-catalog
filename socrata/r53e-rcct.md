# Leaf Collection Posting Log

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/leaf-collection-posting-log-544f5) |
| Metadata | [Link](https://data.montgomerycountymd.gov/api/views/r53e-rcct) |
| Data: JSON | [100 Rows](https://data.montgomerycountymd.gov/api/views/r53e-rcct/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.montgomerycountymd.gov/api/views/r53e-rcct/rows.csv?max_rows=100) |
| Host | data.montgomerycountymd.gov |
| Id | r53e-rcct |
| Name | Leaf Collection Posting Log |
| Category | Environment |
| Tags | leaf collection, log, schedule, department of transportation |
| Created | 2014-09-02T18:26:07Z |
| Publication Date | 2014-11-05T19:20:16Z |

## Description

This dataset contains leaf collection dates for area and subarea where leaf collection service is provided by Montgomery County Department of Transportation. Update Frequency - Daily (September through December).  Monthly update (January through August) on the first day of each month.

## Columns

```ls
| Included | Schema Type    | Field Name                | Name                        | Data Type     | Render Type   |
| ======== | ============== | ========================= | =========================== | ============= | ============= |
| Yes      | numeric metric | area                      | Area                        | number        | number        |
| Yes      | series tag     | sub_area                  | Sub Area                    | text          | text          |
| Yes      | numeric metric | collection_sequence       | Collection Sequence         | number        | number        |
| Yes      | time           | date_sign_posted_round_1  | Date Sign Posted (Round 1)  | calendar_date | calendar_date |
| No       |                | date_on_sign_round_1      | Planned Start (Round 1)     | calendar_date | calendar_date |
| No       |                | date_area_started_round_1 | Date Area Started (Round 1) | calendar_date | calendar_date |
| No       |                | date_area_ended_round_1   | Date Area Ended (Round 1)   | calendar_date | calendar_date |
| No       |                | date_sign_posted_round_2  | Date Sign Posted (Round 2)  | calendar_date | calendar_date |
| No       |                | date_on_sign_round_2      | Planned Start (Round 2)     | calendar_date | calendar_date |
| No       |                | date_area_started_round_2 | Date Area Started (Round 2) | calendar_date | calendar_date |
| No       |                | date_area_ended_round_2   | Date Area Ended (Round 2)   | calendar_date | calendar_date |
```

## Time Field

```ls
Value = date_sign_posted_round_1
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = date_on_sign_round_1,date_area_started_round_1,date_area_ended_round_1,date_sign_posted_round_2,date_on_sign_round_2,date_area_started_round_2,date_area_ended_round_2
```

## Data Commands

```ls
series e:r53e-rcct d:2015-12-16T19:00:22.000Z t:sub_area=A m:area=99 m:collection_sequence=1

series e:r53e-rcct d:2016-10-26T00:00:00.000Z t:sub_area=G m:area=1 m:collection_sequence=1

series e:r53e-rcct d:2016-10-24T00:00:00.000Z t:sub_area=A m:area=3 m:collection_sequence=1
```

## Meta Commands

```ls
metric m:area p:integer l:Area d:"Single numerical digit representing a leaf collection area" t:dataTypeName=number

metric m:collection_sequence p:integer l:"Collection Sequence" d:"The sequence of leaf collection ordered by Sub Area per Area" t:dataTypeName=number

entity e:r53e-rcct l:"Leaf Collection Posting Log" t:url=https://data.montgomerycountymd.gov/api/views/r53e-rcct

property e:r53e-rcct t:meta.view v:id=r53e-rcct v:category=Environment v:averageRating=0 v:name="Leaf Collection Posting Log"

property e:r53e-rcct t:meta.view.owner v:id=ajn4-zy65 v:screenName="MCG ESB Service" v:lastNotificationSeenAt=1491401045 v:displayName="MCG ESB Service"

property e:r53e-rcct t:meta.view.tableauthor v:id=ajn4-zy65 v:screenName="MCG ESB Service" v:roleName=administrator v:lastNotificationSeenAt=1491401045 v:displayName="MCG ESB Service"
```

## Top Records

```ls
| area | sub_area | collection_sequence | date_sign_posted_round_1 | date_on_sign_round_1 | date_area_started_round_1 | date_area_ended_round_1 | date_sign_posted_round_2 | date_on_sign_round_2 | date_area_started_round_2 | date_area_ended_round_2 | 
| ==== | ======== | =================== | ======================== | ==================== | ========================= | ======================= | ======================== | ==================== | ========================= | ======================= | 
| 99   | A        | 1                   |                          |                      |                           |                         |                          |                      |                           |                         | 
| 1    | G        | 1                   | 2016-10-26T00:00:00      | 2016-11-07T00:00:00  | 2016-11-07T00:00:00       | 2016-11-07T00:00:00     | 2016-11-16T00:00:00      | 2016-11-25T00:00:00  | 2016-11-25T00:00:00       | 2016-11-25T00:00:00     | 
| 3    | A        | 1                   | 2016-10-24T00:00:00      | 2016-11-07T00:00:00  | 2016-11-07T00:00:00       | 2016-11-07T00:00:00     | 2016-11-15T00:00:00      | 2016-11-25T00:00:00  | 2016-11-25T00:00:00       | 2016-11-25T00:00:00     | 
| 9    | C        | 1                   | 2016-10-24T00:00:00      | 2016-11-07T00:00:00  | 2016-11-07T00:00:00       | 2016-11-07T00:00:00     | 2016-11-10T00:00:00      | 2016-11-25T00:00:00  | 2016-11-25T00:00:00       | 2016-11-25T00:00:00     | 
| 2    | B        | 1                   | 2016-10-24T00:00:00      | 2016-11-07T00:00:00  | 2016-11-07T00:00:00       | 2016-11-07T00:00:00     | 2016-11-16T00:00:00      | 2016-11-25T00:00:00  | 2016-11-25T00:00:00       | 2016-11-25T00:00:00     | 
| 8    | C        | 1                   | 2016-10-24T00:00:00      | 2016-11-07T00:00:00  | 2016-11-07T00:00:00       | 2016-11-08T00:00:00     | 2016-11-15T00:00:00      | 2016-11-25T00:00:00  | 2016-11-25T00:00:00       | 2016-11-26T00:00:00     | 
| 2    | C        | 2                   | 2016-10-24T00:00:00      | 2016-11-07T00:00:00  | 2016-11-07T00:00:00       | 2016-11-08T00:00:00     | 2016-11-16T00:00:00      | 2016-11-26T00:00:00  | 2016-11-26T00:00:00       | 2016-11-26T00:00:00     | 
| 7    | B        | 1                   | 2016-10-24T00:00:00      | 2016-11-07T00:00:00  | 2016-11-07T00:00:00       | 2016-11-08T00:00:00     | 2016-11-14T00:00:00      | 2016-11-25T00:00:00  | 2016-11-25T00:00:00       | 2016-11-26T00:00:00     | 
| 5    | A        | 1                   | 2016-10-24T00:00:00      | 2016-11-07T00:00:00  | 2016-11-07T00:00:00       | 2016-11-09T00:00:00     | 2016-11-16T00:00:00      | 2016-11-25T00:00:00  | 2016-11-25T00:00:00       | 2016-11-26T00:00:00     | 
| 14   | A        | 1                   | 2016-10-24T00:00:00      | 2016-11-07T00:00:00  | 2016-11-07T00:00:00       | 2016-11-07T00:00:00     | 2016-11-10T00:00:00      | 2016-11-25T00:00:00  | 2016-11-25T00:00:00       | 2016-11-26T00:00:00     | 
```