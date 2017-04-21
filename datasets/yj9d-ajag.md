# Utility Contact Center Average Speed For Answering Calls

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/utility-contact-center-average-speed-for-answering-calls) |
| Metadata | [Link](https://data.austintexas.gov/api/views/yj9d-ajag) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/yj9d-ajag/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/yj9d-ajag/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | yj9d-ajag |
| Name | Utility Contact Center Average Speed For Answering Calls |
| Attribution | City of Austin |
| Created | 2011-12-16T13:34:01Z |
| Publication Date | 2016-09-16T19:49:59Z |

## Description

The average speed for answering calls was up in fiscal years 2009 and 2010 due to Customer Service Representatives focusing on one-call resolutions, thus avoiding repeat calls by customers. In addition, the Utility Contact Center has rolled out several campaign initiatives over the past few years to promote conservation programs. Explaining those products and benefits takes extra time.

## Columns

```ls
| Included | Schema Type    | Field Name  | Name        | Data Type | Render Type |
| ======== | ============== | =========== | =========== | ========= | =========== |
| Yes      | time           | fiscal_year | Fiscal Year | number    | text        |
| Yes      | numeric metric | seconds     | Seconds     | number    | number      |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:yj9d-ajag d:2010-01-01T00:00:00.000Z m:seconds=90

series e:yj9d-ajag d:2009-01-01T00:00:00.000Z m:seconds=92

series e:yj9d-ajag d:2008-01-01T00:00:00.000Z m:seconds=74
```

## Meta Commands

```ls
metric m:seconds p:integer l:Seconds t:dataTypeName=number

entity e:yj9d-ajag l:"Utility Contact Center Average Speed For Answering Calls" t:attribution="City of Austin" t:url=https://data.austintexas.gov/api/views/yj9d-ajag

property e:yj9d-ajag t:meta.view v:id=yj9d-ajag v:averageRating=0 v:name="Utility Contact Center Average Speed For Answering Calls" v:attribution="City of Austin"

property e:yj9d-ajag t:meta.view.owner v:id=fxfz-wsmq v:profileImageUrlMedium=/api/users/fxfz-wsmq/profile_images/THUMB v:profileImageUrlLarge=/api/users/fxfz-wsmq/profile_images/LARGE v:screenName="Shannon Wisner" v:profileImageUrlSmall=/api/users/fxfz-wsmq/profile_images/TINY v:displayName="Shannon Wisner"

property e:yj9d-ajag t:meta.view.tableauthor v:id=fxfz-wsmq v:profileImageUrlMedium=/api/users/fxfz-wsmq/profile_images/THUMB v:profileImageUrlLarge=/api/users/fxfz-wsmq/profile_images/LARGE v:screenName="Shannon Wisner" v:profileImageUrlSmall=/api/users/fxfz-wsmq/profile_images/TINY v:roleName=publisher v:displayName="Shannon Wisner"
```

## Top Records

```ls
| fiscal_year | seconds | 
| =========== | ======= | 
| 2010        | 90      | 
| 2009        | 92      | 
| 2008        | 74      | 
| 2007        | 74      | 
| 2006        | 122     | 
| 2015        | 121     | 
| 2014        | 123     | 
| 2013        | 90      | 
| 2012        | 101     | 
| 2011        | 116     | 
```