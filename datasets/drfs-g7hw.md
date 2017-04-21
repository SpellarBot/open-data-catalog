# FY14 HSEM Response Time - Open Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/fy14-hsem-response-time-open-data) |
| Metadata | [Link](https://data.austintexas.gov/api/views/drfs-g7hw) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/drfs-g7hw/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/drfs-g7hw/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | drfs-g7hw |
| Name | FY14 HSEM Response Time - Open Data |
| Attribution | austintexas.gov/hsem |
| Category | Public Safety |
| Created | 2015-08-06T20:52:47Z |
| Publication Date | 2015-08-10T17:16:26Z |

## Description

Record of the time coded hours of HSEM staff responding to EOC Activation, EOC standby situations, or recovery phases in FY2014. This data provides a general picture for planning purposes, but does not encompass all times when HSEM staff are in response or recovery activities.

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                       | Data Type     | Render Type   |
| ======== | ============== | ========================== | ========================== | ============= | ============= |
| Yes      | time           | payroll_period_ending_date | Payroll Period Ending Date | calendar_date | calendar_date |
| Yes      | numeric metric | hours                      | Hours                      | number        | number        |
```

## Time Field

```ls
Value = payroll_period_ending_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:drfs-g7hw d:2013-10-19T00:00:00.000Z m:hours=62.5

series e:drfs-g7hw d:2013-11-02T00:00:00.000Z m:hours=42

series e:drfs-g7hw d:2013-11-16T00:00:00.000Z m:hours=1004.5
```

## Meta Commands

```ls
metric m:hours p:float l:Hours t:dataTypeName=number

entity e:drfs-g7hw l:"FY14 HSEM Response Time - Open Data" t:attribution=austintexas.gov/hsem t:url=https://data.austintexas.gov/api/views/drfs-g7hw

property e:drfs-g7hw t:meta.view v:id=drfs-g7hw v:category="Public Safety" v:attributionLink=https://austintexas.gov/department/about-hsem v:averageRating=0 v:name="FY14 HSEM Response Time - Open Data" v:attribution=austintexas.gov/hsem

property e:drfs-g7hw t:meta.view.license v:name="Public Domain"

property e:drfs-g7hw t:meta.view.owner v:id=wnhb-trsd v:profileImageUrlMedium=/api/users/wnhb-trsd/profile_images/THUMB v:profileImageUrlLarge=/api/users/wnhb-trsd/profile_images/LARGE v:screenName="Jake Dirr" v:profileImageUrlSmall=/api/users/wnhb-trsd/profile_images/TINY v:displayName="Jake Dirr"

property e:drfs-g7hw t:meta.view.tableauthor v:id=wnhb-trsd v:profileImageUrlMedium=/api/users/wnhb-trsd/profile_images/THUMB v:profileImageUrlLarge=/api/users/wnhb-trsd/profile_images/LARGE v:screenName="Jake Dirr" v:profileImageUrlSmall=/api/users/wnhb-trsd/profile_images/TINY v:roleName=editor v:displayName="Jake Dirr"
```

## Top Records

```ls
| payroll_period_ending_date | hours   | 
| ========================== | ======= | 
| 2013-10-19T00:00:00        | 62.50   | 
| 2013-11-02T00:00:00        | 42.00   | 
| 2013-11-16T00:00:00        | 1004.50 | 
| 2013-11-30T00:00:00        | 195.75  | 
| 2013-12-14T00:00:00        | 113.50  | 
| 2013-12-28T00:00:00        | 75.00   | 
| 2014-01-25T00:00:00        | 61.50   | 
| 2014-02-08T00:00:00        | 120.50  | 
| 2014-02-22T00:00:00        | 40.00   | 
| 2014-03-08T00:00:00        | 74.50   | 
```