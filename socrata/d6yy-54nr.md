# Lottery Powerball Winning Numbers: Beginning 2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/lottery-powerball-winning-numbers-beginning-2010) |
| Metadata | [Link](https://data.ny.gov/api/views/d6yy-54nr) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/d6yy-54nr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/d6yy-54nr/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | d6yy-54nr |
| Name | Lottery Powerball Winning Numbers: Beginning 2010 |
| Attribution | New York State Gaming Commission |
| Category | Government & Finance |
| Tags | powerball, new york lottery, winning, results |
| Created | 2013-03-01T22:46:46Z |
| Publication Date | 2017-04-20T10:01:07Z |

## Description

Go to http://on.ny.gov/1GpWiHD on the New York Lottery website for past Powerball results and payouts.

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type     | Render Type   |
| ======== | ============== | =============== | =============== | ============= | ============= |
| Yes      | time           | draw_date       | Draw Date       | calendar_date | calendar_date |
| Yes      | series tag     | winning_numbers | Winning Numbers | text          | text          |
| Yes      | numeric metric | multiplier      | Multiplier      | number        | number        |
```

## Time Field

```ls
Value = draw_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:d6yy-54nr d:2010-02-03T00:00:00.000Z t:winning_numbers="17 22 36 37 52 24" m:multiplier=2

series e:d6yy-54nr d:2010-02-06T00:00:00.000Z t:winning_numbers="14 22 52 54 59 04" m:multiplier=3

series e:d6yy-54nr d:2010-02-10T00:00:00.000Z t:winning_numbers="05 08 29 37 38 34" m:multiplier=5
```

## Meta Commands

```ls
metric m:multiplier p:long l:Multiplier t:dataTypeName=number

entity e:d6yy-54nr l:"Lottery Powerball Winning Numbers: Beginning 2010" t:attribution="New York State Gaming Commission" t:url=https://data.ny.gov/api/views/d6yy-54nr

property e:d6yy-54nr t:meta.view v:id=d6yy-54nr v:category="Government & Finance" v:attributionLink=http://nylottery.ny.gov/wps/portal/Home/Lottery/home/your+lottery/drawing+results/drawingresults_powerball v:averageRating=0 v:name="Lottery Powerball Winning Numbers: Beginning 2010" v:attribution="New York State Gaming Commission"

property e:d6yy-54nr t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:d6yy-54nr t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:d6yy-54nr t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| draw_date           | winning_numbers   | multiplier | 
| =================== | ================= | ========== | 
| 2010-02-03T00:00:00 | 17 22 36 37 52 24 | 2          | 
| 2010-02-06T00:00:00 | 14 22 52 54 59 04 | 3          | 
| 2010-02-10T00:00:00 | 05 08 29 37 38 34 | 5          | 
| 2010-02-13T00:00:00 | 10 14 30 40 51 01 | 4          | 
| 2010-02-17T00:00:00 | 07 08 19 26 36 15 | 3          | 
| 2010-02-20T00:00:00 | 13 27 37 41 54 32 | 2          | 
| 2010-02-24T00:00:00 | 04 17 35 50 57 12 | 2          | 
| 2010-02-27T00:00:00 | 18 47 51 53 58 30 | 2          | 
| 2010-03-03T00:00:00 | 07 09 14 45 49 23 | 4          | 
| 2010-03-06T00:00:00 | 10 29 33 41 59 15 | 2          | 
```