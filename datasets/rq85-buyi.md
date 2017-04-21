# Monthly Page Views to CDC.gov

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/monthly-page-views-to-cdc-gov-d1710) |
| Metadata | [Link](https://data.cdc.gov/api/views/rq85-buyi) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/rq85-buyi/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/rq85-buyi/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | rq85-buyi |
| Name | Monthly Page Views to CDC.gov |
| Attribution | Office of the Associate Director for Communication, Division of News and Electronic Media |
| Category | Web Metrics |
| Tags | cdc.gov, web metrics |
| Created | 2013-06-27T19:37:32Z |
| Publication Date | 2017-04-03T13:26:58Z |

## Description

For more information on CDC.gov metrics please see http://www.cdc.gov/metrics/

## Columns

```ls
| Included | Schema Type    | Field Name  | Name        | Data Type | Render Type |
| ======== | ============== | =========== | =========== | ========= | =========== |
| No       |                | month       | Month       | text      | text        |
| Yes      | numeric metric | sort        | Sort        | number    | number      |
| No       |                | year        | Year        | number    | number      |
| Yes      | numeric metric | hits        | Page Views  | number    | number      |
| Yes      | numeric metric | page_visits | Page Visits | number    | text        |
```

## Time Field

```ls
Value = year-month
Format & Zone = yyyy-MMMM
```

## Series Fields

```ls
Excluded Fields = year,month
```

## Data Commands

```ls
series e:rq85-buyi d:2003-07-01T00:00:00.000Z m:hits=4618078 m:sort=7 m:page_visits=1484766

series e:rq85-buyi d:2003-08-01T00:00:00.000Z m:hits=6201906 m:sort=8 m:page_visits=1807820

series e:rq85-buyi d:2003-09-01T00:00:00.000Z m:hits=6212629 m:sort=9 m:page_visits=1926503
```

## Meta Commands

```ls
metric m:sort p:integer l:Sort t:dataTypeName=number

metric m:hits p:integer l:"Page Views" t:dataTypeName=number

metric m:page_visits p:integer l:"Page Visits" t:dataTypeName=number

entity e:rq85-buyi l:"Monthly Page Views to CDC.gov" t:attribution="Office of the Associate Director for Communication, Division of News and Electronic Media" t:url=https://data.cdc.gov/api/views/rq85-buyi

property e:rq85-buyi t:meta.view v:id=rq85-buyi v:category="Web Metrics" v:attributionLink=http://www.cdc.gov/metrics/ v:averageRating=0 v:name="Monthly Page Views to CDC.gov" v:attribution="Office of the Associate Director for Communication, Division of News and Electronic Media"

property e:rq85-buyi t:meta.view.owner v:id=g3fc-zmqn v:profileImageUrlMedium=/api/users/g3fc-zmqn/profile_images/THUMB v:profileImageUrlLarge=/api/users/g3fc-zmqn/profile_images/LARGE v:screenName=CDC v:profileImageUrlSmall=/api/users/g3fc-zmqn/profile_images/TINY v:displayName=CDC

property e:rq85-buyi t:meta.view.tableauthor v:id=g3fc-zmqn v:profileImageUrlMedium=/api/users/g3fc-zmqn/profile_images/THUMB v:profileImageUrlLarge=/api/users/g3fc-zmqn/profile_images/LARGE v:screenName=CDC v:profileImageUrlSmall=/api/users/g3fc-zmqn/profile_images/TINY v:roleName=publisher v:displayName=CDC

property e:rq85-buyi t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:00 v:Program_Code=009:020
```

## Top Records

```ls
| month     | sort | year | hits     | page_visits | 
| ========= | ==== | ==== | ======== | =========== | 
| July      | 7    | 2003 | 4618078  | 1484766     | 
| August    | 8    | 2003 | 6201906  | 1807820     | 
| September | 9    | 2003 | 6212629  | 1926503     | 
| October   | 10   | 2003 | 5623701  | 1896823     | 
| November  | 11   | 2003 | 4770724  | 1677243     | 
| December  | 12   | 2003 | 10635555 | 2738544     | 
| January   | 1    | 2004 | 8626559  | 1484766     | 
| February  | 2    | 2004 | 11362126 | 1807820     | 
| March     | 3    | 2004 | 11866809 | 1926503     | 
| April     | 4    | 2004 | 11632495 | 1896823     | 
```