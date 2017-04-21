# PRA TRACKING WaTech

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/pra-tracking-watech) |
| Metadata | [Link](https://data.wa.gov/api/views/pqva-awv7) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/pqva-awv7/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/pqva-awv7/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | pqva-awv7 |
| Name | PRA TRACKING WaTech |
| Attribution | WaTech |
| Tags | pra, public records, foia |
| Created | 2016-02-18T22:13:44Z |
| Publication Date | 2017-04-07T16:06:49Z |

## Description

Records requests received by Washington Technology Solutions (WaTech)

## Columns

```ls
| Included | Schema Type | Field Name        | Name              | Data Type     | Render Type   |
| ======== | =========== | ================= | ================= | ============= | ============= |
| Yes      | time        | date_received     | Date Received     | calendar_date | calendar_date |
| Yes      | series tag  | requester         | Requester         | text          | text          |
| Yes      | series tag  | records_requested | Records Requested | text          | text          |
| No       |             | date_closed       | Date Closed       | calendar_date | calendar_date |
| Yes      | series tag  | category          | Category          | text          | text          |
```

## Time Field

```ls
Value = date_received
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = date_closed
```

## Data Commands

```ls
series e:pqva-awv7 d:2017-04-07T16:05:54.000Z m:row_number.pqva-awv7=1

series e:pqva-awv7 d:2011-09-28T00:00:00.000Z t:records_requested="documents relating to DB2PE (Performance Expert)" t:category="law firm" t:requester="Pamela Shultz - Severson & Werson, APC" m:row_number.pqva-awv7=2

series e:pqva-awv7 d:2011-10-05T00:00:00.000Z t:records_requested="DOL Web Logs" t:category="public agency" t:requester="Hillary Weems - Dept. of Licensing" m:row_number.pqva-awv7=3
```

## Meta Commands

```ls
metric m:row_number.pqva-awv7 p:long l:"Row Number"

entity e:pqva-awv7 l:"PRA TRACKING WaTech" t:attribution=WaTech t:url=https://data.wa.gov/api/views/pqva-awv7

property e:pqva-awv7 t:meta.view v:id=pqva-awv7 v:averageRating=0 v:name="PRA TRACKING WaTech" v:attribution=WaTech

property e:pqva-awv7 t:meta.view.owner v:id=8ubg-ebkr v:profileImageUrlMedium=/api/users/8ubg-ebkr/profile_images/THUMB v:profileImageUrlLarge=/api/users/8ubg-ebkr/profile_images/LARGE v:screenName=jeromel v:profileImageUrlSmall=/api/users/8ubg-ebkr/profile_images/TINY v:displayName=jeromel

property e:pqva-awv7 t:meta.view.tableauthor v:id=8ubg-ebkr v:profileImageUrlMedium=/api/users/8ubg-ebkr/profile_images/THUMB v:profileImageUrlLarge=/api/users/8ubg-ebkr/profile_images/LARGE v:screenName=jeromel v:profileImageUrlSmall=/api/users/8ubg-ebkr/profile_images/TINY v:roleName=publisher v:displayName=jeromel
```

## Top Records

```ls
| date_received       | requester                              | records_requested                                                           | date_closed         | category      | 
| =================== | ====================================== | =========================================================================== | =================== | ============= | 
|                     |                                        |                                                                             |                     |               | 
| 2011-09-28T00:00:00 | Pamela Shultz - Severson & Werson, APC | documents relating to DB2PE (Performance Expert)                            | 2011-11-16T00:00:00 | law firm      | 
| 2011-10-05T00:00:00 | Hillary Weems - Dept. of Licensing     | DOL Web Logs                                                                | 2011-10-12T00:00:00 | public agency | 
| 2011-10-05T00:00:00 | David Harper - DOC                     | Blackberry Logs                                                             | 2012-11-02T00:00:00 | public agency | 
| 2011-11-03T00:00:00 | Sandy babcock - WFCA                   | emails                                                                      | 2011-11-14T00:00:00 | public agency | 
| 2011-11-30T00:00:00 | Dave Hunter - Century Link             | electronic copy of all vendor responses for T12-RFQ-011 (Managed Voicemail) | 2011-12-14T00:00:00 | Vendor        | 
| 2011-12-19T00:00:00 | Lem McCleary - DSHS                    | Communicator Logs - Shirley Brown                                           | 2011-12-20T00:00:00 | Public Agency | 
| 2011-12-14T00:00:00 | Wendy Rawling - Century Link           | CTS Ethernet bids for DOC                                                   | 2011-12-19T00:00:00 | Vendor        | 
| 2011-12-27T00:00:00 | Sourcing Advisory Services             | Records re: 2 RFPs                                                          | 2011-12-27T00:00:00 | Private       | 
|                     |                                        |                                                                             |                     |               | 
```