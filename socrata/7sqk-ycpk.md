# Lottery Quick Draw Winning Numbers: Beginning 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/lottery-quick-draw-winning-numbers-beginning-2013) |
| Metadata | [Link](https://data.ny.gov/api/views/7sqk-ycpk) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/7sqk-ycpk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/7sqk-ycpk/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | 7sqk-ycpk |
| Name | Lottery Quick Draw Winning Numbers: Beginning 2013 |
| Attribution | New York State Gaming Commission |
| Category | Government & Finance |
| Tags | quick draw, new york lottery, winning, results |
| Created | 2014-06-16T18:15:55Z |
| Publication Date | 2017-04-20T10:07:24Z |

## Description

Go to http://on.ny.gov/1BbsWqI on the New York Lottery website for past Quick Draw results and payouts.

## Columns

```ls
| Included | Schema Type | Field Name       | Name            | Data Type     | Render Type   |
| ======== | =========== | ================ | =============== | ============= | ============= |
| Yes      | time        | draw_date        | Draw Date       | calendar_date | calendar_date |
| Yes      | series tag  | draw_number      | Draw Number     | text          | number        |
| No       |             | draw_time        | Draw Time       | text          | text          |
| Yes      | series tag  | winning_numbers  | Winning Numbers | text          | text          |
| Yes      | series tag  | extra_multiplier | Extra           | text          | text          |
```

## Time Field

```ls
Value = draw_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = draw_time
```

## Data Commands

```ls
series e:7sqk-ycpk d:2013-01-01T00:00:00.000Z t:winning_numbers="06 18 20 21 24 32 36 40 44 47 50 52 55 57 60 61 62 68 72 79" t:extra_multiplier=01 t:draw_number=1253842 m:row_number.7sqk-ycpk=1

series e:7sqk-ycpk d:2013-01-01T00:00:00.000Z t:winning_numbers="03 05 12 13 14 16 17 18 24 28 33 34 35 39 44 55 62 63 64 67" t:extra_multiplier=01 t:draw_number=1253843 m:row_number.7sqk-ycpk=2

series e:7sqk-ycpk d:2013-01-01T00:00:00.000Z t:winning_numbers="09 10 12 13 15 25 30 31 36 42 43 44 46 48 51 57 65 69 75 79" t:extra_multiplier=04 t:draw_number=1253844 m:row_number.7sqk-ycpk=3
```

## Meta Commands

```ls
metric m:row_number.7sqk-ycpk p:long l:"Row Number"

entity e:7sqk-ycpk l:"Lottery Quick Draw Winning Numbers: Beginning 2013" t:attribution="New York State Gaming Commission" t:url=https://data.ny.gov/api/views/7sqk-ycpk

property e:7sqk-ycpk t:meta.view v:id=7sqk-ycpk v:category="Government & Finance" v:attributionLink=http://nylottery.ny.gov/wps/portal/Home/Lottery/home/your+lottery/drawing+results/drawingresults_quickdraw v:averageRating=0 v:name="Lottery Quick Draw Winning Numbers: Beginning 2013" v:attribution="New York State Gaming Commission"

property e:7sqk-ycpk t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:7sqk-ycpk t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:7sqk-ycpk t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| draw_date           | draw_number | draw_time | winning_numbers                                             | extra_multiplier | 
| =================== | =========== | ========= | =========================================================== | ================ | 
| 2013-01-01T00:00:00 | 1253842     | 04:04     | 06 18 20 21 24 32 36 40 44 47 50 52 55 57 60 61 62 68 72 79 | 01               | 
| 2013-01-01T00:00:00 | 1253843     | 04:08     | 03 05 12 13 14 16 17 18 24 28 33 34 35 39 44 55 62 63 64 67 | 01               | 
| 2013-01-01T00:00:00 | 1253844     | 04:12     | 09 10 12 13 15 25 30 31 36 42 43 44 46 48 51 57 65 69 75 79 | 04               | 
| 2013-01-01T00:00:00 | 1253845     | 04:16     | 08 12 15 20 27 33 34 37 41 43 44 45 54 55 60 61 66 70 72 76 | 02               | 
| 2013-01-01T00:00:00 | 1253846     | 04:20     | 04 06 07 09 11 12 13 14 18 20 21 26 30 36 37 41 43 48 74 79 | 01               | 
| 2013-01-01T00:00:00 | 1253847     | 04:24     | 01 11 14 15 35 37 38 43 46 48 49 51 53 57 64 65 66 70 76 77 | 02               | 
| 2013-01-01T00:00:00 | 1253848     | 04:28     | 01 03 14 17 20 22 24 25 38 42 46 54 56 57 60 61 66 72 78 80 | 01               | 
| 2013-01-01T00:00:00 | 1253849     | 04:32     | 01 06 11 14 18 19 25 27 30 36 38 49 51 55 58 64 66 69 78 79 | 01               | 
| 2013-01-01T00:00:00 | 1253850     | 04:36     | 07 08 13 21 24 29 30 32 34 42 44 50 56 63 66 70 71 75 76 80 | 01               | 
| 2013-01-01T00:00:00 | 1253851     | 04:40     | 02 07 09 10 13 16 18 20 21 24 34 40 44 45 56 60 61 70 72 76 | 04               | 
```