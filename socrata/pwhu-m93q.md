# BSL - Cumulative Number Of Streetlights Converted To LED

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/bsl-cumulative-number-of-streetlights-converted-to-led) |
| Metadata | [Link](https://data.lacity.org/api/views/pwhu-m93q) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/pwhu-m93q/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/pwhu-m93q/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | pwhu-m93q |
| Name | BSL - Cumulative Number Of Streetlights Converted To LED |
| Category | A Livable and Sustainable City |
| Tags | streetlight, led |
| Created | 2014-05-30T21:12:32Z |
| Publication Date | 2016-10-17T19:56:37Z |

## Description

Cumulative Number Of Streetlights Converted To LED

## Columns

```ls
| Included | Schema Type    | Field Name                                  | Name                                          | Data Type     | Render Type   |
| ======== | ============== | =========================================== | ============================================= | ============= | ============= |
| No       |                | date_name                                   | Date Name                                     | text          | text          |
| Yes      | time           | date                                        | Date                                          | calendar_date | calendar_date |
| Yes      | numeric metric | cumulative_of_streetlights_converted_to_led | Cumulative # of streetlights converted to LED | number        | number        |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = date_name
```

## Data Commands

```ls
series e:pwhu-m93q d:2009-06-30T00:00:00.000Z m:cumulative_of_streetlights_converted_to_led=20000

series e:pwhu-m93q d:2010-06-30T00:00:00.000Z m:cumulative_of_streetlights_converted_to_led=50000

series e:pwhu-m93q d:2011-06-30T00:00:00.000Z m:cumulative_of_streetlights_converted_to_led=95000
```

## Meta Commands

```ls
metric m:cumulative_of_streetlights_converted_to_led p:integer l:"Cumulative # of streetlights converted to LED" d:"Cumulative number of streetlights that have been converted to LED" t:dataTypeName=number

entity e:pwhu-m93q l:"BSL - Cumulative Number Of Streetlights Converted To LED" t:url=https://data.lacity.org/api/views/pwhu-m93q

property e:pwhu-m93q t:meta.view v:id=pwhu-m93q v:category="A Livable and Sustainable City" v:averageRating=0 v:name="BSL - Cumulative Number Of Streetlights Converted To LED"

property e:pwhu-m93q t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:pwhu-m93q t:meta.view.owner v:id=kmuv-58sk v:profileImageUrlMedium=/api/users/kmuv-58sk/profile_images/THUMB v:profileImageUrlLarge=/api/users/kmuv-58sk/profile_images/LARGE v:screenName="Public Works: Street Lighting OpenData" v:profileImageUrlSmall=/api/users/kmuv-58sk/profile_images/TINY v:displayName="Public Works: Street Lighting OpenData"

property e:pwhu-m93q t:meta.view.tableauthor v:id=kmuv-58sk v:profileImageUrlMedium=/api/users/kmuv-58sk/profile_images/THUMB v:profileImageUrlLarge=/api/users/kmuv-58sk/profile_images/LARGE v:screenName="Public Works: Street Lighting OpenData" v:profileImageUrlSmall=/api/users/kmuv-58sk/profile_images/TINY v:roleName=publisher v:displayName="Public Works: Street Lighting OpenData"
```

## Top Records

```ls
| date_name | date                | cumulative_of_streetlights_converted_to_led | 
| ========= | =================== | =========================================== | 
| FY 2009   | 2009-06-30T00:00:00 | 20000                                       | 
| FY 2010   | 2010-06-30T00:00:00 | 50000                                       | 
| FY 2011   | 2011-06-30T00:00:00 | 95000                                       | 
| FY 2012   | 2012-06-30T00:00:00 | 140000                                      | 
| FY 2013   | 2013-06-30T00:00:00 | 145000                                      | 
| FY 2014   | 2014-06-30T00:00:00 | 154000                                      | 
| FY 2015   | 2015-06-30T00:00:00 | 162000                                      | 
| FY 2016   | 2016-06-30T00:00:00 | 170000                                      | 
```