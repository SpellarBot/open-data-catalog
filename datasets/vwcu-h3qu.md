# Utility Contact Center Calls Answered

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/utility-contact-center-calls-answered) |
| Metadata | [Link](https://data.austintexas.gov/api/views/vwcu-h3qu) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/vwcu-h3qu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/vwcu-h3qu/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | vwcu-h3qu |
| Name | Utility Contact Center Calls Answered |
| Attribution | City of Austin |
| Created | 2011-12-16T13:37:16Z |
| Publication Date | 2016-09-16T19:53:31Z |

## Description

The City of Austin Utility Contact Center is managed by Austin Energy. This is the place customers call to start, stop, or transfer utility services. The center receives about 6,000 calls per day on average and Online Customer Care handles about 12,000 requests per month.

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type | Render Type |
| ======== | ============== | ============== | ============== | ========= | =========== |
| Yes      | time           | fiscal_year    | Fiscal Year    | number    | text        |
| Yes      | numeric metric | calls_answered | Calls Answered | number    | number      |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:vwcu-h3qu d:2006-01-01T00:00:00.000Z m:calls_answered=1545433

series e:vwcu-h3qu d:2007-01-01T00:00:00.000Z m:calls_answered=1416055

series e:vwcu-h3qu d:2008-01-01T00:00:00.000Z m:calls_answered=1405573
```

## Meta Commands

```ls
metric m:calls_answered p:integer l:"Calls Answered" t:dataTypeName=number

entity e:vwcu-h3qu l:"Utility Contact Center Calls Answered" t:attribution="City of Austin" t:url=https://data.austintexas.gov/api/views/vwcu-h3qu

property e:vwcu-h3qu t:meta.view v:id=vwcu-h3qu v:averageRating=0 v:name="Utility Contact Center Calls Answered" v:attribution="City of Austin"

property e:vwcu-h3qu t:meta.view.owner v:id=fxfz-wsmq v:profileImageUrlMedium=/api/users/fxfz-wsmq/profile_images/THUMB v:profileImageUrlLarge=/api/users/fxfz-wsmq/profile_images/LARGE v:screenName="Shannon Wisner" v:profileImageUrlSmall=/api/users/fxfz-wsmq/profile_images/TINY v:displayName="Shannon Wisner"

property e:vwcu-h3qu t:meta.view.tableauthor v:id=fxfz-wsmq v:profileImageUrlMedium=/api/users/fxfz-wsmq/profile_images/THUMB v:profileImageUrlLarge=/api/users/fxfz-wsmq/profile_images/LARGE v:screenName="Shannon Wisner" v:profileImageUrlSmall=/api/users/fxfz-wsmq/profile_images/TINY v:roleName=publisher v:displayName="Shannon Wisner"
```

## Top Records

```ls
| fiscal_year | calls_answered | 
| =========== | ============== | 
| 2006        | 1545433        | 
| 2007        | 1416055        | 
| 2008        | 1405573        | 
| 2009        | 1435929        | 
| 2010        | 1525739        | 
| 2015        | 1850756        | 
| 2014        | 1727662        | 
| 2013        | 1667361        | 
| 2012        | 1641039        | 
| 2011        | 1377317        | 
```