# Austin Energy General Fund Transfer

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/austin-energy-general-fund-transfer) |
| Metadata | [Link](https://data.austintexas.gov/api/views/zzix-yxi4) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/zzix-yxi4/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/zzix-yxi4/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | zzix-yxi4 |
| Name | Austin Energy General Fund Transfer |
| Attribution | City of Austin |
| Category | Financial |
| Created | 2011-12-16T13:41:43Z |
| Publication Date | 2016-10-13T16:36:10Z |

## Description

As a community-owned electric utility, Austin Energy returns a dividend to its community. This dividend is comparable to funds distributed to stockholders by investor-owned electric utilities. The dividend (known as the General Fund Transfer) returned by Austin Energy helps fund other City services such as Police, Fire, EMS, Parks, and Libraries. General Fund Transfers are common among municipally-owned utilities. For more detailed information about the General Fund Transfer, visit the City of Austin Finance online page: https://www.austintexas.gov/financeonline/finance/

## Columns

```ls
| Included | Schema Type    | Field Name         | Name        | Data Type     | Render Type   |
| ======== | ============== | ================== | =========== | ============= | ============= |
| Yes      | time           | fiscal_year        | Fiscal Year | calendar_date | calendar_date |
| Yes      | numeric metric | amount_in_millions | Amount      | money         | money         |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:zzix-yxi4 d:2015-01-01T00:00:00.000Z m:amount_in_millions=105000000

series e:zzix-yxi4 d:2014-01-01T00:00:00.000Z m:amount_in_millions=105000000

series e:zzix-yxi4 d:2013-01-01T00:00:00.000Z m:amount_in_millions=105000000
```

## Meta Commands

```ls
metric m:amount_in_millions p:double l:Amount t:dataTypeName=money

entity e:zzix-yxi4 l:"Austin Energy General Fund Transfer" t:attribution="City of Austin" t:url=https://data.austintexas.gov/api/views/zzix-yxi4

property e:zzix-yxi4 t:meta.view v:id=zzix-yxi4 v:category=Financial v:averageRating=0 v:name="Austin Energy General Fund Transfer" v:attribution="City of Austin"

property e:zzix-yxi4 t:meta.view.owner v:id=fxfz-wsmq v:profileImageUrlMedium=/api/users/fxfz-wsmq/profile_images/THUMB v:profileImageUrlLarge=/api/users/fxfz-wsmq/profile_images/LARGE v:screenName="Shannon Wisner" v:profileImageUrlSmall=/api/users/fxfz-wsmq/profile_images/TINY v:displayName="Shannon Wisner"

property e:zzix-yxi4 t:meta.view.tableauthor v:id=fxfz-wsmq v:profileImageUrlMedium=/api/users/fxfz-wsmq/profile_images/THUMB v:profileImageUrlLarge=/api/users/fxfz-wsmq/profile_images/LARGE v:screenName="Shannon Wisner" v:profileImageUrlSmall=/api/users/fxfz-wsmq/profile_images/TINY v:roleName=publisher v:displayName="Shannon Wisner"
```

## Top Records

```ls
| fiscal_year         | amount_in_millions | 
| =================== | ================== | 
| 2015-01-01T00:00:00 | 105000000.00       | 
| 2014-01-01T00:00:00 | 105000000.00       | 
| 2013-01-01T00:00:00 | 105000000.00       | 
| 2012-01-01T00:00:00 | 105000000.00       | 
| 2011-01-01T00:00:00 | 103000000.00       | 
| 2010-01-01T00:00:00 | 101000000.00       | 
| 2009-01-01T00:00:00 | 95000000.00        | 
| 2008-01-01T00:00:00 | 91000000.00        | 
| 2007-01-01T00:00:00 | 84500000.00        | 
| 2006-01-01T00:00:00 | 77400000.00        | 
```