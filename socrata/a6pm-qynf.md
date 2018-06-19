# Austin Energy System Peak Demand

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/austin-energy-system-peak-demand) |
| Metadata | [Link](https://data.austintexas.gov/api/views/a6pm-qynf) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/a6pm-qynf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/a6pm-qynf/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | a6pm-qynf |
| Name | Austin Energy System Peak Demand |
| Attribution | City of Austin |
| Created | 2011-12-16T13:55:06Z |
| Publication Date | 2016-10-03T16:21:15Z |

## Description

System peak demand is the most amount of electricity consumed by Austin Energy customers at any given time. A fiscal year begins October 1 and ends September 30 the following year.

## Columns

```ls
| Included | Schema Type | Field Name | Name           | Data Type     | Render Type   |
| ======== | =========== | ========== | ============== | ============= | ============= |
| No       |             | fy         | Fiscal year    | calendar_date | calendar_date |
| No       |             | mw         | Megawatts (MW) | number        | number        |
| Yes      | time        | date_set   | Date           | calendar_date | calendar_date |
```

## Time Field

```ls
Value = date_set
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = fy,mw
```

## Data Commands

```ls
series e:a6pm-qynf d:2007-08-24T00:00:00.000Z m:row_number.a6pm-qynf=1

series e:a6pm-qynf d:2008-08-13T00:00:00.000Z m:row_number.a6pm-qynf=2

series e:a6pm-qynf d:2009-08-04T00:00:00.000Z m:row_number.a6pm-qynf=3
```

## Meta Commands

```ls
metric m:row_number.a6pm-qynf p:long l:"Row Number"

entity e:a6pm-qynf l:"Austin Energy System Peak Demand" t:attribution="City of Austin" t:url=https://data.austintexas.gov/api/views/a6pm-qynf

property e:a6pm-qynf t:meta.view v:id=a6pm-qynf v:averageRating=0 v:name="Austin Energy System Peak Demand" v:attribution="City of Austin"

property e:a6pm-qynf t:meta.view.owner v:id=fxfz-wsmq v:profileImageUrlMedium=/api/users/fxfz-wsmq/profile_images/THUMB v:profileImageUrlLarge=/api/users/fxfz-wsmq/profile_images/LARGE v:screenName="Shannon Wisner" v:profileImageUrlSmall=/api/users/fxfz-wsmq/profile_images/TINY v:displayName="Shannon Wisner"

property e:a6pm-qynf t:meta.view.tableauthor v:id=fxfz-wsmq v:profileImageUrlMedium=/api/users/fxfz-wsmq/profile_images/THUMB v:profileImageUrlLarge=/api/users/fxfz-wsmq/profile_images/LARGE v:screenName="Shannon Wisner" v:profileImageUrlSmall=/api/users/fxfz-wsmq/profile_images/TINY v:roleName=publisher v:displayName="Shannon Wisner"
```

## Top Records

```ls
| fy                  | mw   | date_set            | 
| =================== | ==== | =================== | 
| 2006-01-01T00:00:00 | 2430 | 2007-08-24T00:00:00 | 
| 2007-01-01T00:00:00 | 2391 | 2008-08-13T00:00:00 | 
| 2008-01-01T00:00:00 | 2514 | 2009-08-04T00:00:00 | 
| 2009-01-01T00:00:00 | 2602 | 2010-06-29T00:00:00 | 
| 2010-01-01T00:00:00 | 2628 | 2011-08-23T00:00:00 | 
| 2011-01-01T00:00:00 | 2714 | 2012-08-29T00:00:00 | 
| 2012-01-01T00:00:00 | 2702 | 2013-06-26T00:00:00 | 
| 2013-01-01T00:00:00 | 2512 | 2014-08-07T00:00:00 | 
| 2014-01-01T00:00:00 | 2578 | 2015-08-25T00:00:00 | 
| 2015-01-01T00:00:00 | 2735 | 2016-08-12T00:00:00 | 
```