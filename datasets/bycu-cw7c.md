# Lottery Pick 10 Winning Numbers: Beginning 1987

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/lottery-pick-10-winning-numbers-beginning-1987) |
| Metadata | [Link](https://data.ny.gov/api/views/bycu-cw7c) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/bycu-cw7c/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/bycu-cw7c/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | bycu-cw7c |
| Name | Lottery Pick 10 Winning Numbers: Beginning 1987 |
| Attribution | New York State Gaming Commission |
| Category | Government & Finance |
| Tags | pick 10, new york lottery, winning, results |
| Created | 2013-02-26T19:37:05Z |
| Publication Date | 2017-04-20T10:02:47Z |

## Description

Go to http://on.ny.gov/1Cx6Zls on the New York Lottery website for past Pick 10 results and payouts.

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
series e:bycu-cw7c d:1987-01-12T00:00:00.000Z t:winning_numbers="05 12 15 18 20 25 26 33 34 35 48 49 52 54 57 62 65 69 71 76" m:row_number.bycu-cw7c=1

series e:bycu-cw7c d:1987-01-13T00:00:00.000Z t:winning_numbers="04 11 14 19 22 23 26 34 40 42 43 45 58 60 63 64 72 74 77 79" m:row_number.bycu-cw7c=2

series e:bycu-cw7c d:1987-01-14T00:00:00.000Z t:winning_numbers="05 07 08 25 27 28 32 36 38 47 51 52 53 55 58 59 60 72 74 77" m:row_number.bycu-cw7c=3
```

## Meta Commands

```ls
metric m:row_number.bycu-cw7c p:long l:"Row Number"

entity e:bycu-cw7c l:"Lottery Pick 10 Winning Numbers: Beginning 1987" t:attribution="New York State Gaming Commission" t:url=https://data.ny.gov/api/views/bycu-cw7c

property e:bycu-cw7c t:meta.view v:id=bycu-cw7c v:category="Government & Finance" v:attributionLink=http://nylottery.ny.gov/wps/portal/Home/Lottery/home/your+lottery/drawing+results/drawingresults_pick10 v:averageRating=0 v:name="Lottery Pick 10 Winning Numbers: Beginning 1987" v:attribution="New York State Gaming Commission"

property e:bycu-cw7c t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:bycu-cw7c t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:bycu-cw7c t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| draw_date           | winning_numbers                                             | 
| =================== | =========================================================== | 
| 1987-01-12T00:00:00 | 05 12 15 18 20 25 26 33 34 35 48 49 52 54 57 62 65 69 71 76 | 
| 1987-01-13T00:00:00 | 04 11 14 19 22 23 26 34 40 42 43 45 58 60 63 64 72 74 77 79 | 
| 1987-01-14T00:00:00 | 05 07 08 25 27 28 32 36 38 47 51 52 53 55 58 59 60 72 74 77 | 
| 1987-01-15T00:00:00 | 02 04 08 10 15 23 25 26 28 31 36 38 49 51 57 59 72 74 78 80 | 
| 1987-01-16T00:00:00 | 02 07 10 12 24 27 30 32 36 37 41 43 47 60 61 62 64 69 72 78 | 
| 1987-01-19T00:00:00 | 01 07 10 14 16 17 20 25 31 33 37 39 43 45 46 60 70 72 77 80 | 
| 1987-01-20T00:00:00 | 01 14 16 22 23 27 29 30 34 36 39 40 43 44 62 64 67 71 73 76 | 
| 1987-01-21T00:00:00 | 02 04 08 13 14 16 18 19 26 30 31 35 44 51 53 61 68 73 79 80 | 
| 1987-01-22T00:00:00 | 02 07 14 18 19 23 26 29 32 35 40 41 43 46 52 62 68 70 76 80 | 
| 1987-01-23T00:00:00 | 02 05 06 08 11 13 28 29 43 44 48 52 53 58 59 61 62 77 79 80 | 
```