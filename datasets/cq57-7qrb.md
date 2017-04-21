# Missouri Monthly Unemployment Claims By Race

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/missouri-monthly-unemployment-claims-by-race-32ab3) |
| Metadata | [Link](https://data.mo.gov/api/views/cq57-7qrb) |
| Data: JSON | [100 Rows](https://data.mo.gov/api/views/cq57-7qrb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.mo.gov/api/views/cq57-7qrb/rows.csv?max_rows=100) |
| Host | data.mo.gov |
| Id | cq57-7qrb |
| Name | Missouri Monthly Unemployment Claims By Race |
| Category | Labor |
| Tags | unemployment, labor, employment |
| Created | 2012-08-30T14:34:39Z |
| Publication Date | 2017-04-10T13:01:13Z |

## Description

Demographic data of Missouri Unemployment claims by race

## Columns

```ls
| Included | Schema Type    | Field Name                                | Name                                      | Data Type     | Render Type   |
| ======== | ============== | ========================================= | ========================================= | ============= | ============= |
| Yes      | series tag     | record_id                                 | Record ID                                 | text          | text          |
| Yes      | time           | date                                      | Date                                      | calendar_date | calendar_date |
| Yes      | numeric metric | ina                                       | INA                                       | number        | number        |
| Yes      | numeric metric | white                                     | White                                     | number        | number        |
| Yes      | numeric metric | asian                                     | Asian                                     | number        | number        |
| Yes      | numeric metric | black_or_african_american                 | Black or African American                 | number        | number        |
| Yes      | numeric metric | american_indian_or_alaskan_native         | American Indian or Alaskan Native         | number        | number        |
| Yes      | numeric metric | native_hawaiian_or_other_pacific_islander | Native Hawaiian or Other Pacific Islander | number        | number        |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:cq57-7qrb d:2011-08-01T00:00:00.000Z t:record_id=08012011 m:black_or_african_american=14546 m:native_hawaiian_or_other_pacific_islander=622 m:ina=3108 m:white=42910 m:american_indian_or_alaskan_native=400 m:asian=478

series e:cq57-7qrb d:2011-07-01T00:00:00.000Z t:record_id=07012011 m:black_or_african_american=15386 m:native_hawaiian_or_other_pacific_islander=612 m:ina=3376 m:white=46437 m:american_indian_or_alaskan_native=454 m:asian=556

series e:cq57-7qrb d:2011-09-01T00:00:00.000Z t:record_id=09012011 m:black_or_african_american=11993 m:native_hawaiian_or_other_pacific_islander=585 m:ina=2693 m:white=37447 m:american_indian_or_alaskan_native=348 m:asian=415
```

## Meta Commands

```ls
metric m:ina p:integer l:INA d:"Information Not Available" t:dataTypeName=number

metric m:white p:integer l:White t:dataTypeName=number

metric m:asian p:integer l:Asian t:dataTypeName=number

metric m:black_or_african_american p:integer l:"Black or African American" t:dataTypeName=number

metric m:american_indian_or_alaskan_native p:integer l:"American Indian or Alaskan Native" t:dataTypeName=number

metric m:native_hawaiian_or_other_pacific_islander p:integer l:"Native Hawaiian or Other Pacific Islander" t:dataTypeName=number

entity e:cq57-7qrb l:"Missouri Monthly Unemployment Claims By Race" t:url=https://data.mo.gov/api/views/cq57-7qrb

property e:cq57-7qrb t:meta.view v:id=cq57-7qrb v:category=Labor v:averageRating=0 v:name="Missouri Monthly Unemployment Claims By Race"

property e:cq57-7qrb t:meta.view.owner v:id=8xqn-4t42 v:profileImageUrlMedium=/api/users/8xqn-4t42/profile_images/THUMB v:profileImageUrlLarge=/api/users/8xqn-4t42/profile_images/LARGE v:screenName="Rodney Distler" v:profileImageUrlSmall=/api/users/8xqn-4t42/profile_images/TINY v:displayName="Rodney Distler"

property e:cq57-7qrb t:meta.view.tableauthor v:id=8xqn-4t42 v:profileImageUrlMedium=/api/users/8xqn-4t42/profile_images/THUMB v:profileImageUrlLarge=/api/users/8xqn-4t42/profile_images/LARGE v:screenName="Rodney Distler" v:profileImageUrlSmall=/api/users/8xqn-4t42/profile_images/TINY v:roleName=publisher v:displayName="Rodney Distler"
```

## Top Records

```ls
| record_id | date                | ina  | white | asian | black_or_african_american | american_indian_or_alaskan_native | native_hawaiian_or_other_pacific_islander | 
| ========= | =================== | ==== | ===== | ===== | ========================= | ================================= | ========================================= | 
| 08012011  | 2011-08-01T00:00:00 | 3108 | 42910 | 478   | 14546                     | 400                               | 622                                       | 
| 07012011  | 2011-07-01T00:00:00 | 3376 | 46437 | 556   | 15386                     | 454                               | 612                                       | 
| 09012011  | 2011-09-01T00:00:00 | 2693 | 37447 | 415   | 11993                     | 348                               | 585                                       | 
| 02012012  | 2012-02-01T00:00:00 | 2958 | 49351 | 383   | 10171                     | 447                               | 655                                       | 
| 10012011  | 2011-10-01T00:00:00 | 2537 | 35216 | 404   | 11331                     | 323                               | 543                                       | 
| 11012011  | 2011-11-01T00:00:00 | 2866 | 41685 | 433   | 12349                     | 425                               | 578                                       | 
| 12012011  | 2011-12-01T00:00:00 | 2913 | 43011 | 398   | 10526                     | 438                               | 639                                       | 
| 01012012  | 2012-01-01T00:00:00 | 3207 | 51999 | 465   | 11051                     | 532                               | 727                                       | 
| 03012012  | 2012-03-01T00:00:00 | 2667 | 41707 | 363   | 9879                      | 417                               | 612                                       | 
| 06012012  | 2012-06-01T00:00:00 | 3532 | 34609 | 386   | 10733                     | 344                               | 556                                       | 
```