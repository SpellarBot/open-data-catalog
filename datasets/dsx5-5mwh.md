# Family Support Division Resource Centers

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/family-support-division-resource-centers) |
| Metadata | [Link](https://data.mo.gov/api/views/dsx5-5mwh) |
| Data: JSON | [100 Rows](https://data.mo.gov/api/views/dsx5-5mwh/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.mo.gov/api/views/dsx5-5mwh/rows.csv?max_rows=100) |
| Host | data.mo.gov |
| Id | dsx5-5mwh |
| Name | Family Support Division Resource Centers |
| Attribution | Missouri Dept. of Social Services |
| Category | Social Services |
| Tags | dss, fsd, social service, resource centers, food stamps, health care, child care, child support, mohealthnet |
| Created | 2015-03-24T13:57:29Z |
| Publication Date | 2017-04-20T21:59:16Z |

## Description

The Missouri Dept. of Social Services' Family Support Division can help you or your family with food stamps, health care, child care, child support, and other needs as we support our mission to maintain and strengthen Missouri families.

This dataset lists the locations, contact information and hours of operations for FSD Resource Centers across Missouri.

## Columns

```ls
| Included | Schema Type | Field Name                         | Name                               | Data Type | Render Type |
| ======== | =========== | ================================== | ================================== | ========= | =========== |
| No       | time        | :updated_at                        | updated_at                         | meta_data | meta_data   |
| Yes      | series tag  | resource_center                    | Resource Center                    | text      | text        |
| Yes      | series tag  | complex_name                       | Complex Name                       | text      | text        |
| Yes      | series tag  | hours_of_operation                 | Hours of Operation                 | text      | text        |
| No       |             | additional_address_info            | Additional Address Info            | text      | text        |
| Yes      | series tag  | phone_number                       | FSD Information Center             | phone     | phone       |
| Yes      | series tag  | automated_24_hour_information_line | Automated 24-Hour Information Line | phone     | phone       |
| Yes      | series tag  | fax                                | Fax                                | phone     | phone       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = additional_address_info
```

## Data Commands

```ls
series e:dsx5-5mwh d:2015-07-16T15:14:27.000Z t:phone_number="(314) 416-2934" t:hours_of_operation="Monday-Friday 
8 a.m. - 5 p.m." t:resource_center="Affinia Resource Center" m:row_number.dsx5-5mwh=1

series e:dsx5-5mwh d:2015-07-16T15:14:28.000Z t:phone_number="(660) 425-7382" t:hours_of_operation="Monday-Friday 8:00 a.m. - 5:00 p.m." t:resource_center="Bethany Resource Center" m:row_number.dsx5-5mwh=2

series e:dsx5-5mwh d:2015-07-16T15:14:28.000Z t:complex_name="Burrell Behavioral Health" t:phone_number="(800) 392-1261" t:hours_of_operation="Thursday 
9 a.m. - 11 a.m." t:resource_center="Bill's Place Outreach Center" m:row_number.dsx5-5mwh=3
```

## Meta Commands

```ls
metric m:row_number.dsx5-5mwh p:long l:"Row Number"

entity e:dsx5-5mwh l:"Family Support Division Resource Centers" t:attribution="Missouri Dept. of Social Services" t:url=https://data.mo.gov/api/views/dsx5-5mwh

property e:dsx5-5mwh t:meta.view v:id=dsx5-5mwh v:category="Social Services" v:averageRating=0 v:name="Family Support Division Resource Centers" v:attribution="Missouri Dept. of Social Services"

property e:dsx5-5mwh t:meta.view.owner v:id=jzbz-iqr6 v:screenName=Breanna v:lastNotificationSeenAt=1492723347 v:displayName=Breanna

property e:dsx5-5mwh t:meta.view.tableauthor v:id=jzbz-iqr6 v:screenName=Breanna v:roleName=administrator v:lastNotificationSeenAt=1492723347 v:displayName=Breanna
```

## Top Records

```ls
| :updated_at | resource_center                    | complex_name               | hours_of_operation                  | additional_address_info | phone_number           | automated_24_hour_information_line | fax                    | 
| =========== | ================================== | ========================== | =================================== | ======================= | ====================== | ================================== | ====================== | 
| 1437059667  | Affinia Resource Center            |                            | Monday-Friday 8 a.m. - 5 p.m.       |                         | [(855) 373-4636, null] | [(800) 392-1261, null]             | [(314) 416-2934, null] | 
| 1437059668  | Bethany Resource Center            |                            | Monday-Friday 8:00 a.m. - 5:00 p.m. |                         | [(855) 373-4636, null] | [(800) 392-1261, null]             | [(660) 425-7382, null] | 
| 1437059668  | Bill's Place Outreach Center       | Burrell Behavioral Health  | Thursday 9 a.m. - 11 a.m.           |                         | [(855) 373-4636, null] | [(800) 392-1261, null]             | [null, null]           | 
| 1437059668  | Booneville Resource Center         |                            | Monday-Friday 8 a.m. - 5 p.m.       |                         | [(855) 373-4636, null] | [(800) 392-1261, null]             | [(660) 882-8858, null] | 
| 1437059668  | Brookefield Resource Center        |                            | Monday-Friday 8 a.m. - 5 p.m.       |                         | [(855) 373-4636, null] | [(800) 392-1261, null]             | [(660) 258-2091, null] | 
| 1437059668  | Burrell/TransitionsOutreach Center | Burrelll Behavioral Health | Thursday 8 a.m. - 12 p.m.           |                         | [(855) 373-4636, null] | [(800) 392-1261, null]             | [null, null]           | 
| 1437059668  | Butler Resource Center             |                            | Monday-Friday 8 a.m. - 5 p.m.       |                         | [(855) 373-4636, null] | [(800) 392-1261, null]             | [(660) 679-3894, null] | 
| 1437059668  | Camdenton Resource Center          |                            | Monday-Friday 8 a.m. - 5 p.m.       |                         | [(855) 373-4636, null] | [(800) 392-1261, null]             | [(573) 346-0382, null] | 
| 1438091816  | Branson Resource Center            |                            | Monday-Friday 8 a.m. - 5 p.m.       |                         | [(855) 373-4636, null] | [(800) 392-1261, null]             | [(417) 339-2770, null] | 
| 1438091984  | Buffalo Resource Center            |                            | Monday-Friday 8 a.m. - 5 p.m.       |                         | [(855) 373-4636, null] | [(800) 392-1261, null]             | [(417) 345-8509, null] | 
```