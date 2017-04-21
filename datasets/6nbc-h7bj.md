# Lottery NY Lotto Winning Numbers: Beginning 2001

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/lottery-ny-lotto-winning-numbers-beginning-2001) |
| Metadata | [Link](https://data.ny.gov/api/views/6nbc-h7bj) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/6nbc-h7bj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/6nbc-h7bj/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | 6nbc-h7bj |
| Name | Lottery NY Lotto Winning Numbers: Beginning 2001 |
| Attribution | New York State Gaming Commission |
| Category | Government & Finance |
| Tags | lotto, winning, results, drawing, new york lottery |
| Created | 2013-03-01T22:43:18Z |
| Publication Date | 2017-04-20T10:01:47Z |

## Description

Go to http://on.ny.gov/1BbsR6n on the New York Lottery website for past NY Lotto results and payouts.

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type     | Render Type   |
| ======== | ============== | =============== | =============== | ============= | ============= |
| Yes      | time           | draw_date       | Draw Date       | calendar_date | calendar_date |
| Yes      | series tag     | winning_numbers | Winning Numbers | text          | text          |
| Yes      | numeric metric | bonus           | Bonus #         | number        | number        |
| Yes      | numeric metric | extra           | Extra #         | number        | number        |
```

## Time Field

```ls
Value = draw_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:6nbc-h7bj d:2001-09-12T00:00:00.000Z t:winning_numbers="08 13 26 35 45 51" m:bonus=39

series e:6nbc-h7bj d:2001-09-15T00:00:00.000Z t:winning_numbers="01 15 24 31 34 44" m:bonus=57

series e:6nbc-h7bj d:2001-09-19T00:00:00.000Z t:winning_numbers="03 08 29 30 31 49" m:bonus=52
```

## Meta Commands

```ls
metric m:bonus p:long l:"Bonus #" t:dataTypeName=number

metric m:extra p:long l:"Extra #" t:dataTypeName=number

entity e:6nbc-h7bj l:"Lottery NY Lotto Winning Numbers: Beginning 2001" t:attribution="New York State Gaming Commission" t:url=https://data.ny.gov/api/views/6nbc-h7bj

property e:6nbc-h7bj t:meta.view v:id=6nbc-h7bj v:category="Government & Finance" v:attributionLink=http://nylottery.ny.gov/wps/portal/Home/Lottery/home/your+lottery/drawing+results/drawingresults_lotto v:averageRating=0 v:name="Lottery NY Lotto Winning Numbers: Beginning 2001" v:attribution="New York State Gaming Commission"

property e:6nbc-h7bj t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:6nbc-h7bj t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:6nbc-h7bj t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| draw_date           | winning_numbers   | bonus | extra | 
| =================== | ================= | ===== | ===== | 
| 2001-09-12T00:00:00 | 08 13 26 35 45 51 | 39    |       | 
| 2001-09-15T00:00:00 | 01 15 24 31 34 44 | 57    |       | 
| 2001-09-19T00:00:00 | 03 08 29 30 31 49 | 52    |       | 
| 2001-09-22T00:00:00 | 21 25 39 50 54 59 | 53    |       | 
| 2001-09-26T00:00:00 | 15 19 32 38 47 50 | 14    |       | 
| 2001-09-29T00:00:00 | 21 25 27 39 44 56 | 45    |       | 
| 2001-10-03T00:00:00 | 03 08 13 21 33 41 | 9     |       | 
| 2001-10-06T00:00:00 | 08 14 19 35 42 50 | 39    |       | 
| 2001-10-10T00:00:00 | 01 06 23 30 40 51 | 36    |       | 
| 2001-10-13T00:00:00 | 05 17 30 35 41 49 | 52    |       | 
```