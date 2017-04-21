# Lottery Mega Millions Winning Numbers: Beginning 2002

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/lottery-mega-millions-winning-numbers-beginning-2002) |
| Metadata | [Link](https://data.ny.gov/api/views/5xaw-6ayf) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/5xaw-6ayf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/5xaw-6ayf/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | 5xaw-6ayf |
| Name | Lottery Mega Millions Winning Numbers: Beginning 2002 |
| Attribution | New York State Gaming Commission |
| Category | Government & Finance |
| Tags | mega millions, new york lottery, winning, results |
| Created | 2013-03-05T14:09:25Z |
| Publication Date | 2017-04-19T10:01:25Z |

## Description

Go to http://on.ny.gov/1J8tPSN on the New York Lottery website for past Mega Millions results and payouts.

## Columns

```ls
| Included | Schema Type | Field Name      | Name            | Data Type     | Render Type   |
| ======== | =========== | =============== | =============== | ============= | ============= |
| Yes      | time        | draw_date       | Draw Date       | calendar_date | calendar_date |
| Yes      | series tag  | winning_numbers | Winning Numbers | text          | text          |
| Yes      | series tag  | mega_ball       | Mega Ball       | text          | text          |
| Yes      | series tag  | multiplier      | Multiplier      | text          | text          |
```

## Time Field

```ls
Value = draw_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:5xaw-6ayf d:2002-05-17T00:00:00.000Z t:winning_numbers="15 18 25 33 47" t:mega_ball=30 m:row_number.5xaw-6ayf=1

series e:5xaw-6ayf d:2002-05-21T00:00:00.000Z t:winning_numbers="04 28 39 41 44" t:mega_ball=09 m:row_number.5xaw-6ayf=2

series e:5xaw-6ayf d:2002-05-24T00:00:00.000Z t:winning_numbers="02 04 32 44 52" t:mega_ball=36 m:row_number.5xaw-6ayf=3
```

## Meta Commands

```ls
metric m:row_number.5xaw-6ayf p:long l:"Row Number"

entity e:5xaw-6ayf l:"Lottery Mega Millions Winning Numbers: Beginning 2002" t:attribution="New York State Gaming Commission" t:url=https://data.ny.gov/api/views/5xaw-6ayf

property e:5xaw-6ayf t:meta.view v:id=5xaw-6ayf v:category="Government & Finance" v:attributionLink=http://nylottery.ny.gov/wps/portal/Home/Lottery/home/your+lottery/drawing+results/drawingresultsmega v:averageRating=0 v:name="Lottery Mega Millions Winning Numbers: Beginning 2002" v:attribution="New York State Gaming Commission"

property e:5xaw-6ayf t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:5xaw-6ayf t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:5xaw-6ayf t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| draw_date           | winning_numbers | mega_ball | multiplier | 
| =================== | =============== | ========= | ========== | 
| 2002-05-17T00:00:00 | 15 18 25 33 47  | 30        |            | 
| 2002-05-21T00:00:00 | 04 28 39 41 44  | 09        |            | 
| 2002-05-24T00:00:00 | 02 04 32 44 52  | 36        |            | 
| 2002-05-28T00:00:00 | 06 21 22 29 32  | 24        |            | 
| 2002-05-31T00:00:00 | 12 28 45 46 52  | 47        |            | 
| 2002-06-04T00:00:00 | 03 25 29 30 48  | 48        |            | 
| 2002-06-07T00:00:00 | 14 22 27 28 42  | 13        |            | 
| 2002-06-11T00:00:00 | 05 06 09 33 44  | 52        |            | 
| 2002-06-14T00:00:00 | 04 08 32 37 43  | 02        |            | 
| 2002-06-18T00:00:00 | 06 13 18 27 45  | 18        |            | 
```