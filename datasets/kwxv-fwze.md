# Lottery Cash 4 Life Winning Numbers: Beginning 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/lottery-cash-4-life-winning-numbers-beginning-2014) |
| Metadata | [Link](https://data.ny.gov/api/views/kwxv-fwze) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/kwxv-fwze/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/kwxv-fwze/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | kwxv-fwze |
| Name | Lottery Cash 4 Life Winning Numbers: Beginning 2014 |
| Attribution | New York State Gaming Commission |
| Category | Government & Finance |
| Tags | cash 4 life, new york lottery, winning, results |
| Created | 2014-06-17T19:47:54Z |
| Publication Date | 2017-04-18T10:01:07Z |

## Description

Go to http://on.ny.gov/1xRIvPz on the New York Lottery website for past Cash 4 Life results and payouts.

## Columns

```ls
| Included | Schema Type | Field Name      | Name            | Data Type     | Render Type   |
| ======== | =========== | =============== | =============== | ============= | ============= |
| Yes      | time        | draw_date       | Draw Date       | calendar_date | calendar_date |
| Yes      | series tag  | winning_numbers | Winning Numbers | text          | text          |
| Yes      | series tag  | cash_ball       | Cash Ball       | text          | text          |
```

## Time Field

```ls
Value = draw_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:kwxv-fwze d:2014-06-16T00:00:00.000Z t:winning_numbers="09 36 44 53 59" t:cash_ball=03 m:row_number.kwxv-fwze=1

series e:kwxv-fwze d:2014-06-19T00:00:00.000Z t:winning_numbers="08 13 43 56 60" t:cash_ball=02 m:row_number.kwxv-fwze=2

series e:kwxv-fwze d:2014-06-23T00:00:00.000Z t:winning_numbers="05 16 21 33 47" t:cash_ball=04 m:row_number.kwxv-fwze=3
```

## Meta Commands

```ls
metric m:row_number.kwxv-fwze p:long l:"Row Number"

entity e:kwxv-fwze l:"Lottery Cash 4 Life Winning Numbers: Beginning 2014" t:attribution="New York State Gaming Commission" t:url=https://data.ny.gov/api/views/kwxv-fwze

property e:kwxv-fwze t:meta.view v:id=kwxv-fwze v:category="Government & Finance" v:attributionLink=http://nylottery.ny.gov/wps/portal/Home/Lottery/home/your+lottery/drawing+results/drawingresults_cash4life v:averageRating=0 v:name="Lottery Cash 4 Life Winning Numbers: Beginning 2014" v:attribution="New York State Gaming Commission"

property e:kwxv-fwze t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:kwxv-fwze t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:kwxv-fwze t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| draw_date           | winning_numbers | cash_ball | 
| =================== | =============== | ========= | 
| 2014-06-16T00:00:00 | 09 36 44 53 59  | 03        | 
| 2014-06-19T00:00:00 | 08 13 43 56 60  | 02        | 
| 2014-06-23T00:00:00 | 05 16 21 33 47  | 04        | 
| 2014-06-26T00:00:00 | 15 22 51 52 58  | 03        | 
| 2014-06-30T00:00:00 | 01 04 10 28 33  | 02        | 
| 2014-07-03T00:00:00 | 08 10 25 28 31  | 02        | 
| 2014-07-07T00:00:00 | 11 13 23 54 55  | 02        | 
| 2014-07-10T00:00:00 | 11 12 31 54 59  | 03        | 
| 2014-07-14T00:00:00 | 09 19 34 37 49  | 02        | 
| 2014-07-17T00:00:00 | 08 09 22 46 51  | 01        | 
```