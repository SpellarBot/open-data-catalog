# Bills WaTech is Tracking

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/bills-watech-is-tracking) |
| Metadata | [Link](https://data.wa.gov/api/views/qqak-79dr) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/qqak-79dr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/qqak-79dr/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | qqak-79dr |
| Name | Bills WaTech is Tracking |
| Attribution | WaTech (OCIO) |
| Tags | legislation |
| Created | 2016-01-15T01:11:58Z |
| Publication Date | 2017-01-09T04:56:04Z |

## Description

List of bills in the state legislature that are of interest to Washington Technology Solutions (WaTech) for any of a wide variety of reasons.

## Columns

```ls
| Included | Schema Type | Field Name                 | Name                       | Data Type     | Render Type   |
| ======== | =========== | ========================== | ========================== | ============= | ============= |
| Yes      | series tag  | bill_short_title           | Bill Short Title           | text          | text          |
| Yes      | series tag  | bill_id                    | Bill ID                    | text          | text          |
| Yes      | series tag  | link                       | Link                       | url           | url           |
| Yes      | series tag  | bill_status                | Bill Status                | text          | text          |
| Yes      | time        | bill_status_date           | Bill Status Date           | calendar_date | calendar_date |
| Yes      | series tag  | bill_type                  | Bill Type                  | text          | text          |
| No       |             | date_introduced            | Date Introduced            | calendar_date | calendar_date |
| Yes      | series tag  | passed_by_legislature_flag | Passed by Legislature Flag | checkbox      | checkbox      |
```

## Time Field

```ls
Value = bill_status_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = date_introduced
```

## Data Commands

```ls
series e:qqak-79dr d:2017-01-12T00:00:00.000Z t:bill_short_title="1160 - Sunshine committee" t:link="http://apps.leg.wa.gov/billinfo/summary.aspx?bill=1160&year=2017" t:bill_status="HState Governme" t:bill_type="House Bills (HB)" t:bill_id="HB 1160" m:row_number.qqak-79dr=1

series e:qqak-79dr d:2017-01-09T00:00:00.000Z t:bill_short_title="1067 - Operating budget 2017-2019" t:link="http://apps.leg.wa.gov/billinfo/summary.aspx?bill=1067&year=2017" t:bill_status=HApprops t:bill_type="House Bills (HB)" t:bill_id="HB 1067" m:row_number.qqak-79dr=2

series e:qqak-79dr d:2017-01-12T00:00:00.000Z t:bill_short_title="1120 - Regulatory fairness act" t:link="http://apps.leg.wa.gov/billinfo/summary.aspx?bill=1120&year=2017" t:bill_status="HTech &  Econ D" t:bill_type="House Bills (HB)" t:bill_id="HB 1120" m:row_number.qqak-79dr=3
```

## Meta Commands

```ls
metric m:row_number.qqak-79dr p:long l:"Row Number"

entity e:qqak-79dr l:"Bills WaTech is Tracking" t:attribution="WaTech (OCIO)" t:url=https://data.wa.gov/api/views/qqak-79dr

property e:qqak-79dr t:meta.view v:id=qqak-79dr v:averageRating=0 v:name="Bills WaTech is Tracking" v:attribution="WaTech (OCIO)"

property e:qqak-79dr t:meta.view.owner v:id=h2ue-vnnt v:profileImageUrlMedium=/api/users/h2ue-vnnt/profile_images/THUMB v:profileImageUrlLarge=/api/users/h2ue-vnnt/profile_images/LARGE v:screenName="OCIO-Will Saunders" v:profileImageUrlSmall=/api/users/h2ue-vnnt/profile_images/TINY v:displayName="OCIO-Will Saunders"

property e:qqak-79dr t:meta.view.tableauthor v:id=h2ue-vnnt v:profileImageUrlMedium=/api/users/h2ue-vnnt/profile_images/THUMB v:profileImageUrlLarge=/api/users/h2ue-vnnt/profile_images/LARGE v:screenName="OCIO-Will Saunders" v:profileImageUrlSmall=/api/users/h2ue-vnnt/profile_images/TINY v:roleName=publisher v:displayName="OCIO-Will Saunders"
```

## Top Records

```ls
| bill_short_title                    | bill_id | link                                                                     | bill_status     | bill_status_date    | bill_type         | date_introduced     | passed_by_legislature_flag | 
| =================================== | ======= | ======================================================================== | =============== | =================== | ================= | =================== | ========================== | 
| 1160 - Sunshine committee           | HB 1160 | [http://apps.leg.wa.gov/billinfo/summary.aspx?bill=1160&year=2017, null] | HState Governme | 2017-01-12T00:00:00 | House Bills (HB)  | 2017-01-12T00:00:00 |                            | 
| 1067 - Operating budget 2017-2019   | HB 1067 | [http://apps.leg.wa.gov/billinfo/summary.aspx?bill=1067&year=2017, null] | HApprops        | 2017-01-09T00:00:00 | House Bills (HB)  | 2017-01-09T00:00:00 |                            | 
| 1120 - Regulatory fairness act      | HB 1120 | [http://apps.leg.wa.gov/billinfo/summary.aspx?bill=1120&year=2017, null] | HTech & Econ D  | 2017-01-12T00:00:00 | House Bills (HB)  | 2017-01-11T00:00:00 |                            | 
| 1031 - UAVs near marine species     | HB 1031 | [http://apps.leg.wa.gov/billinfo/summary.aspx?bill=1031&year=2017, null] | HTech & Econ D  | 2017-01-09T00:00:00 | House Bills (HB)  | 2017-01-09T00:00:00 |                            | 
| 1102 - Govt surveillance technology | HB 1102 | [http://apps.leg.wa.gov/billinfo/summary.aspx?bill=1102&year=2017, null] | HPublic Safety  | 2017-01-11T00:00:00 | House Bills (HB)  | 2017-01-11T00:00:00 |                            | 
| 1108 - Substance trafficking/privcy | HB 1108 | [http://apps.leg.wa.gov/billinfo/summary.aspx?bill=1108&year=2017, null] | HJudiciary      | 2017-01-11T00:00:00 | House Bills (HB)  | 2017-01-11T00:00:00 |                            | 
| 1193 - Fourth amendment/federal gov | HB 1193 | [http://apps.leg.wa.gov/billinfo/summary.aspx?bill=1193&year=2017, null] | HJudiciary      | 2017-01-13T00:00:00 | House Bills (HB)  | 2017-01-13T00:00:00 |                            | 
| 1049 - Unmanned aircraft            | HB 1049 | [http://apps.leg.wa.gov/billinfo/summary.aspx?bill=1049&year=2017, null] | HTech & Econ D  | 2017-01-09T00:00:00 | House Bills (HB)  | 2017-01-09T00:00:00 |                            | 
| 1317 - GPS data disclosure          | HB 1317 | [http://apps.leg.wa.gov/billinfo/summary.aspx?bill=1317&year=2017, null] | HState Governme | 2017-01-17T00:00:00 | House Bills (HB)  | 2017-01-17T00:00:00 |                            | 
| 5048 - Operating budget 2017-2019   | SB 5048 | [http://apps.leg.wa.gov/billinfo/summary.aspx?bill=5048&year=2017, null] | SWays & Means   | 2017-01-11T00:00:00 | Senate Bills (SB) | 2017-01-11T00:00:00 |                            | 
```