# BSL- Percent Of Streetlight Outages Repaired Within 10 Business Days

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/bsl-percent-of-streetlight-outages-repaired-within-10-business-days) |
| Metadata | [Link](https://data.lacity.org/api/views/fc3u-86zh) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/fc3u-86zh/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/fc3u-86zh/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | fc3u-86zh |
| Name | BSL- Percent Of Streetlight Outages Repaired Within 10 Business Days |
| Category | A Well Run City |
| Tags | street lighting, customer service, streetlight |
| Created | 2014-05-30T22:11:54Z |
| Publication Date | 2017-03-13T21:12:53Z |

## Description

This dataset shows the percentage of streetlight outages that are repaired within 10 business days.

## Columns

```ls
| Included | Schema Type    | Field Name                               | Name                                       | Data Type     | Render Type   |
| ======== | ============== | ======================================== | ========================================== | ============= | ============= |
| No       |                | date_name                                | Date Name                                  | text          | text          |
| Yes      | time           | date_value                               | Date Value                                 | calendar_date | calendar_date |
| Yes      | numeric metric | outages_repaired_within_10_business_days | % outages repaired within 10 business days | percent       | percent       |
```

## Time Field

```ls
Value = date_value
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = date_name
```

## Data Commands

```ls
series e:fc3u-86zh d:2013-08-01T00:00:00.000Z m:outages_repaired_within_10_business_days=96

series e:fc3u-86zh d:2013-09-01T00:00:00.000Z m:outages_repaired_within_10_business_days=96

series e:fc3u-86zh d:2013-10-01T00:00:00.000Z m:outages_repaired_within_10_business_days=91
```

## Meta Commands

```ls
metric m:outages_repaired_within_10_business_days p:integer l:"% outages repaired within 10 business days" d:"Percent of streetlight outages repaired within 10 business days" t:dataTypeName=percent

entity e:fc3u-86zh l:"BSL- Percent Of Streetlight Outages Repaired Within 10 Business Days" t:url=https://data.lacity.org/api/views/fc3u-86zh

property e:fc3u-86zh t:meta.view v:id=fc3u-86zh v:category="A Well Run City" v:averageRating=0 v:name="BSL- Percent Of Streetlight Outages Repaired Within 10 Business Days"

property e:fc3u-86zh t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:fc3u-86zh t:meta.view.owner v:id=kmuv-58sk v:profileImageUrlMedium=/api/users/kmuv-58sk/profile_images/THUMB v:profileImageUrlLarge=/api/users/kmuv-58sk/profile_images/LARGE v:screenName="Public Works: Street Lighting OpenData" v:profileImageUrlSmall=/api/users/kmuv-58sk/profile_images/TINY v:displayName="Public Works: Street Lighting OpenData"

property e:fc3u-86zh t:meta.view.tableauthor v:id=kmuv-58sk v:profileImageUrlMedium=/api/users/kmuv-58sk/profile_images/THUMB v:profileImageUrlLarge=/api/users/kmuv-58sk/profile_images/LARGE v:screenName="Public Works: Street Lighting OpenData" v:profileImageUrlSmall=/api/users/kmuv-58sk/profile_images/TINY v:roleName=publisher v:displayName="Public Works: Street Lighting OpenData"
```

## Top Records

```ls
| date_name | date_value          | outages_repaired_within_10_business_days | 
| ========= | =================== | ======================================== | 
| Aug-13    | 2013-08-01T00:00:00 | 96                                       | 
| Sep-13    | 2013-09-01T00:00:00 | 96                                       | 
| Oct-13    | 2013-10-01T00:00:00 | 91                                       | 
| Nov-13    | 2013-11-01T00:00:00 | 95                                       | 
| Dec-13    | 2013-12-01T00:00:00 | 87                                       | 
| Jan-14    | 2014-01-01T00:00:00 | 93                                       | 
| Feb-14    | 2014-02-01T00:00:00 | 96                                       | 
| Mar-14    | 2014-03-01T00:00:00 | 96                                       | 
| Apr-14    | 2014-04-01T00:00:00 | 91                                       | 
| May-14    | 2014-05-01T00:00:00 | 96                                       | 
```