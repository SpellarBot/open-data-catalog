# Lottery Take 5 Winning Numbers

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/lottery-take-5-winning-numbers) |
| Metadata | [Link](https://data.ny.gov/api/views/dg63-4siq) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/dg63-4siq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/dg63-4siq/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | dg63-4siq |
| Name | Lottery Take 5 Winning Numbers |
| Attribution | New York State Gaming Commission |
| Category | Government & Finance |
| Tags | take 5, new york lottery, winning, results |
| Created | 2013-02-26T20:04:57Z |
| Publication Date | 2017-04-20T10:00:25Z |

## Description

Go to http://on.ny.gov/1DYGlWJ on the New York Lottery website for past Take 5 results and payouts.

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type     | Render Type   |
| ======== | ============== | =============== | =============== | ============= | ============= |
| Yes      | time           | draw_date       | Draw Date       | calendar_date | calendar_date |
| Yes      | series tag     | winning_numbers | Winning Numbers | text          | text          |
| Yes      | numeric metric | bonus           | Bonus #         | number        | number        |
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
metric m:bonus p:long l:"Bonus #" t:dataTypeName=number

entity e:dg63-4siq l:"Lottery Take 5 Winning Numbers" t:attribution="New York State Gaming Commission" t:url=https://data.ny.gov/api/views/dg63-4siq

property e:dg63-4siq t:meta.view v:id=dg63-4siq v:category="Government & Finance" v:attributionLink=http://nylottery.ny.gov/wps/portal/Home/Lottery/home/your+lottery/drawing+results/drawingresults_take5 v:averageRating=0 v:name="Lottery Take 5 Winning Numbers" v:attribution="New York State Gaming Commission"

property e:dg63-4siq t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:dg63-4siq t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:dg63-4siq t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| draw_date           | winning_numbers | bonus | 
| =================== | =============== | ===== | 
| 1992-01-17T00:00:00 | 12 15 20 36 39  |       | 
| 1992-01-24T00:00:00 | 03 06 15 27 36  |       | 
| 1992-01-31T00:00:00 | 01 07 08 18 37  |       | 
| 1992-02-07T00:00:00 | 01 30 33 34 39  |       | 
| 1992-02-14T00:00:00 | 26 28 33 35 37  |       | 
| 1992-02-21T00:00:00 | 01 14 16 21 32  |       | 
| 1992-02-28T00:00:00 | 17 22 28 35 37  |       | 
| 1992-03-06T00:00:00 | 06 11 15 16 32  |       | 
| 1992-03-13T00:00:00 | 02 18 23 26 39  |       | 
| 1992-03-20T00:00:00 | 08 12 13 38 39  |       | 
```