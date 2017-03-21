# Lottery Daily Numbers/Win-4 Winning Numbers: Beginning 1980

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/lottery-daily-numbers-win-4-winning-numbers-beginning-1980) |
| Metadata | [Link](https://data.ny.gov/api/views/hsys-3def) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/hsys-3def/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/hsys-3def/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | hsys-3def |
| Name | Lottery Daily Numbers/Win-4 Winning Numbers: Beginning 1980 |
| Attribution | New York State Gaming Commission |
| Category | Government & Finance |
| Tags | numbers, win-4, new york lottery, winning, results |
| Created | 2013-02-26T20:21:34Z |
| Publication Date | 2017-03-21T10:03:13Z |
| Rows Updated | 2017-03-21T10:02:25Z |

## Description

Go to http://on.ny.gov/1Cx6zvs or http://on.ny.gov/1KYjE6X on the New York Lottery website for past Daily Numbers/Win-4 results and payouts.

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type     | Render Type   |
| ======== | ============== | ================= | ================= | ============= | ============= |
| Yes      | time           | draw_date         | Draw Date         | calendar_date | calendar_date |
| Yes      | series tag     | midday_daily      | Midday Daily #    | text          | text          |
| Yes      | numeric metric | midday_daily_sum  | Midday Daily Sum  | number        | number        |
| Yes      | series tag     | evening_daily     | Evening Daily #   | text          | text          |
| Yes      | numeric metric | evening_daily_sum | Evening Daily Sum | number        | number        |
| Yes      | series tag     | midday_win_4      | Midday Win 4 #    | text          | text          |
| Yes      | numeric metric | midday_win_4_sum  | Midday Win 4 Sum  | number        | number        |
| Yes      | series tag     | evening_win_4     | Evening Win 4 #   | text          | text          |
| Yes      | numeric metric | evening_win_4_sum | Evening Win 4 Sum | number        | number        |
```

## Time Field

```ls
Value = draw_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
```

## Meta Commands

```ls
metric m:midday_daily_sum p:long l:"Midday Daily Sum" t:dataTypeName=number

metric m:evening_daily_sum p:long l:"Evening Daily Sum" t:dataTypeName=number

metric m:midday_win_4_sum p:long l:"Midday Win 4 Sum" t:dataTypeName=number

metric m:evening_win_4_sum p:long l:"Evening Win 4 Sum" t:dataTypeName=number

entity e:hsys-3def l:"Lottery Daily Numbers/Win-4 Winning Numbers: Beginning 1980" t:attribution="New York State Gaming Commission" t:url=https://data.ny.gov/api/views/hsys-3def

property e:hsys-3def t:meta.view v:id=hsys-3def v:category="Government & Finance" v:attributionLink=http://nylottery.ny.gov/wps/portal/Home/Lottery/Home/YOUR+LOTTERY/Drawing+Results/drawing+results/ v:averageRating=0 v:name="Lottery Daily Numbers/Win-4 Winning Numbers: Beginning 1980" v:attribution="New York State Gaming Commission"

property e:hsys-3def t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:hsys-3def t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:hsys-3def t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```