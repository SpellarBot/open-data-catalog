# Lottery Sweet Million Winning Numbers: 2009 - 2014 (Retired Game)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/lottery-sweet-million-winning-numbers-2009-2014-retired-game) |
| Metadata | [Link](https://data.ny.gov/api/views/xjtd-9p3n) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/xjtd-9p3n/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/xjtd-9p3n/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | xjtd-9p3n |
| Name | Lottery Sweet Million Winning Numbers: 2009 - 2014 (Retired Game) |
| Attribution | New York State Gaming Commission |
| Category | Government & Finance |
| Tags | sweet million, new york lottery, winning, results |
| Created | 2013-02-26T20:02:24Z |
| Publication Date | 2014-06-20T14:36:44Z |

## Description

Go to http://on.ny.gov/1CLzbRT on the New York Lottery website for past Sweet Million results and payouts.

## Columns

```ls
| Included | Schema Type | Field Name      | Name            | Data Type     | Render Type   |
| ======== | =========== | =============== | =============== | ============= | ============= |
| Yes      | time        | draw_date       | Draw Date       | calendar_date | calendar_date |
| Yes      | series tag  | winning_numbers | Winning Numbers | text          | text          |
```

## Time Field

```ls
Value = draw_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:xjtd-9p3n d:2009-09-17T00:00:00.000Z t:winning_numbers="16 19 23 26 36 38" m:row_number.xjtd-9p3n=1

series e:xjtd-9p3n d:2009-09-21T00:00:00.000Z t:winning_numbers="10 13 14 19 26 30" m:row_number.xjtd-9p3n=2

series e:xjtd-9p3n d:2009-09-24T00:00:00.000Z t:winning_numbers="03 04 22 25 36 39" m:row_number.xjtd-9p3n=3
```

## Meta Commands

```ls
metric m:row_number.xjtd-9p3n p:long l:"Row Number"

entity e:xjtd-9p3n l:"Lottery Sweet Million Winning Numbers: 2009 - 2014 (Retired Game)" t:attribution="New York State Gaming Commission" t:url=https://data.ny.gov/api/views/xjtd-9p3n

property e:xjtd-9p3n t:meta.view v:id=xjtd-9p3n v:category="Government & Finance" v:attributionLink=http://nylottery.ny.gov/wps/portal/Home/Lottery/home/your+lottery/drawing+results/drawingresults_sweetmillion v:averageRating=0 v:name="Lottery Sweet Million Winning Numbers: 2009 - 2014 (Retired Game)" v:attribution="New York State Gaming Commission"

property e:xjtd-9p3n t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:xjtd-9p3n t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:xjtd-9p3n t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| draw_date           | winning_numbers   | 
| =================== | ================= | 
| 2009-09-17T00:00:00 | 16 19 23 26 36 38 | 
| 2009-09-21T00:00:00 | 10 13 14 19 26 30 | 
| 2009-09-24T00:00:00 | 03 04 22 25 36 39 | 
| 2009-09-28T00:00:00 | 07 22 32 33 34 36 | 
| 2009-10-01T00:00:00 | 06 12 15 16 32 36 | 
| 2009-10-05T00:00:00 | 07 19 22 24 34 35 | 
| 2009-10-08T00:00:00 | 06 07 21 25 26 29 | 
| 2009-10-12T00:00:00 | 01 04 05 32 34 37 | 
| 2009-10-15T00:00:00 | 01 16 29 35 39 40 | 
| 2009-10-19T00:00:00 | 01 02 16 23 24 25 | 
```