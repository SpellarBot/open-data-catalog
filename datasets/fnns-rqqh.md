# Weatherization Assistance Program

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/weatherization-assistance-program) |
| Metadata | [Link](https://data.austintexas.gov/api/views/fnns-rqqh) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/fnns-rqqh/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/fnns-rqqh/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | fnns-rqqh |
| Name | Weatherization Assistance Program |
| Attribution | Austin Energy |
| Category | Utility |
| Tags | weatherization, assistance, weatherization assistance program, energy, savings |
| Created | 2016-09-06T16:43:36Z |
| Publication Date | 2016-09-30T18:29:51Z |

## Description

Austin Energy offers free home energy improvements to customers with low to moderate incomes who qualify. The improvements reduce energy costs and enhance indoor comfort. Qualifying customers can have their home weatherized and receive home improvements. These improvements include attic insulation, solar screens, compact fluorescent light bulbs, minor duct repair and sealing, caulking and weather stripping and other improvements. Customers participating in the program can realize energy savings from 6 to 21 percent. Find more information at http://austinenergy.com/go/reports.

## Columns

```ls
| Included | Schema Type    | Field Name                     | Name                           | Data Type     | Render Type   |
| ======== | ============== | ============================== | ============================== | ============= | ============= |
| Yes      | time           | fiscal_year_2                  | Fiscal Year                    | calendar_date | calendar_date |
| Yes      | numeric metric | homes_receiving_weatherization | Homes Receiving Weatherization | number        | number        |
```

## Time Field

```ls
Value = fiscal_year_2
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:fnns-rqqh d:2006-09-01T00:00:00.000Z m:homes_receiving_weatherization=720

series e:fnns-rqqh d:2007-09-01T00:00:00.000Z m:homes_receiving_weatherization=632

series e:fnns-rqqh d:2008-09-01T00:00:00.000Z m:homes_receiving_weatherization=505
```

## Meta Commands

```ls
metric m:homes_receiving_weatherization p:integer l:"Homes Receiving Weatherization" t:dataTypeName=number

entity e:fnns-rqqh l:"Weatherization Assistance Program" t:attribution="Austin Energy" t:url=https://data.austintexas.gov/api/views/fnns-rqqh

property e:fnns-rqqh t:meta.view d:2017-06-09T13:55:54.006Z v:id=fnns-rqqh v:category=Utility v:averageRating=0 v:name="Weatherization Assistance Program" v:attribution="Austin Energy"

property e:fnns-rqqh t:meta.view.license d:2017-06-09T13:55:54.006Z v:name="Public Domain"

property e:fnns-rqqh t:meta.view.owner d:2017-06-09T13:55:54.006Z v:id=c433-zrb5 v:profileImageUrlMedium=/api/users/c433-zrb5/profile_images/THUMB v:profileImageUrlLarge=/api/users/c433-zrb5/profile_images/LARGE v:screenName="Sarah Lambert" v:profileImageUrlSmall=/api/users/c433-zrb5/profile_images/TINY v:displayName="Sarah Lambert"

property e:fnns-rqqh t:meta.view.tableauthor d:2017-06-09T13:55:54.006Z v:id=c433-zrb5 v:profileImageUrlMedium=/api/users/c433-zrb5/profile_images/THUMB v:profileImageUrlLarge=/api/users/c433-zrb5/profile_images/LARGE v:screenName="Sarah Lambert" v:profileImageUrlSmall=/api/users/c433-zrb5/profile_images/TINY v:roleName=publisher v:displayName="Sarah Lambert"
```

## Top Records

```ls
| fiscal_year_2       | homes_receiving_weatherization | 
| =================== | ============================== | 
| 2006-09-01T00:00:00 | 720                            | 
| 2007-09-01T00:00:00 | 632                            | 
| 2008-09-01T00:00:00 | 505                            | 
| 2009-09-01T00:00:00 | 538                            | 
| 2010-09-01T00:00:00 | 456                            | 
| 2011-09-01T00:00:00 | 1044                           | 
| 2012-09-01T00:00:00 | 715                            | 
| 2013-09-01T00:00:00 | 155                            | 
| 2014-09-01T00:00:00 | 200                            | 
| 2015-09-01T00:00:00 | 520                            | 
```