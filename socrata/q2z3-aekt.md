# Austin Energy Regional Science Festival Expenditures

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/austin-energy-regional-science-festival-expenditures) |
| Metadata | [Link](https://data.austintexas.gov/api/views/q2z3-aekt) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/q2z3-aekt/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/q2z3-aekt/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | q2z3-aekt |
| Name | Austin Energy Regional Science Festival Expenditures |
| Attribution | Austin Energy |
| Category | Utility |
| Tags | austin energy, regional science festival, expenditures |
| Created | 2016-09-19T15:37:25Z |
| Publication Date | 2016-10-14T20:06:55Z |

## Description

The Austin Energy Regional Science Festival is one of the largest regional science festivals held in Texas and the nation. Middle and high school students who win at their respective schools compete at the regional festival to advance to the state science fair competition. Five senior level projects receive Best of Fair awards and the winners of those projects have the option to advance directly to the international competition. 

Central Texas middle and high school students have performed very well at past state and international competitions. Between 2004 and 2016, 100 students representing 71 projects advanced to the international level. Of those, 44 students representing 29 projects won 73 category and special awards. Since 2004, more than 1,225 students have advanced to the state level, where about 20% have won awards.

In 2016, the Austin Energy Regional Science Festival showcased 755 middle and high school projects. Unlike most regional events, Austin Energy also hosts elementary school students.  Nearly 4,000 students and their families turn out for the event which includes a public viewing of the science projects as well as educational booths and scientific demonstrations. 

Over 550 judges and 180 volunteers from the City of Austin, local businesses, colleges, and elementary/middle/high schools contribute annually to the event?s success. Revenues to fund the event come from fees paid by participating schools and companies that provide sponsorships.

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type     | Render Type   |
| ======== | ============== | =================== | =================== | ============= | ============= |
| Yes      | time           | fiscal_year         | Fiscal Year         | calendar_date | calendar_date |
| Yes      | numeric metric | expenditures        | Expenditures        | money         | money         |
| Yes      | numeric metric | fee_revenue         | Fee Revenue         | money         | money         |
| Yes      | numeric metric | sponsorship_revenue | Sponsorship Revenue | money         | money         |
| Yes      | numeric metric | total_revenue       | Total Revenue       | money         | money         |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:q2z3-aekt d:2016-01-01T00:00:00.000Z m:total_revenue=246100 m:sponsorship_revenue=123100 m:expenditures=219958 m:fee_revenue=46820

series e:q2z3-aekt d:2015-01-01T00:00:00.000Z m:total_revenue=241740 m:sponsorship_revenue=124500 m:expenditures=222750 m:fee_revenue=40240

series e:q2z3-aekt d:2014-01-01T00:00:00.000Z m:total_revenue=191525 m:sponsorship_revenue=146500 m:expenditures=184282 m:fee_revenue=45025
```

## Meta Commands

```ls
metric m:expenditures p:integer l:Expenditures t:dataTypeName=money

metric m:fee_revenue p:integer l:"Fee Revenue" t:dataTypeName=money

metric m:sponsorship_revenue p:integer l:"Sponsorship Revenue" t:dataTypeName=money

metric m:total_revenue p:integer l:"Total Revenue" t:dataTypeName=money

entity e:q2z3-aekt l:"Austin Energy Regional Science Festival Expenditures" t:attribution="Austin Energy" t:url=https://data.austintexas.gov/api/views/q2z3-aekt

property e:q2z3-aekt t:meta.view v:id=q2z3-aekt v:category=Utility v:averageRating=0 v:name="Austin Energy Regional Science Festival Expenditures" v:attribution="Austin Energy"

property e:q2z3-aekt t:meta.view.license v:name="Public Domain"

property e:q2z3-aekt t:meta.view.owner v:id=c433-zrb5 v:profileImageUrlMedium=/api/users/c433-zrb5/profile_images/THUMB v:profileImageUrlLarge=/api/users/c433-zrb5/profile_images/LARGE v:screenName="Sarah Lambert" v:profileImageUrlSmall=/api/users/c433-zrb5/profile_images/TINY v:displayName="Sarah Lambert"

property e:q2z3-aekt t:meta.view.tableauthor v:id=c433-zrb5 v:profileImageUrlMedium=/api/users/c433-zrb5/profile_images/THUMB v:profileImageUrlLarge=/api/users/c433-zrb5/profile_images/LARGE v:screenName="Sarah Lambert" v:profileImageUrlSmall=/api/users/c433-zrb5/profile_images/TINY v:roleName=publisher v:displayName="Sarah Lambert"
```

## Top Records

```ls
| fiscal_year         | expenditures | fee_revenue | sponsorship_revenue | total_revenue | 
| =================== | ============ | =========== | =================== | ============= | 
| 2016-01-01T00:00:00 | 219958       | 46820       | 123100              | 246100        | 
| 2015-01-01T00:00:00 | 222750       | 40240       | 124500              | 241740        | 
| 2014-01-01T00:00:00 | 184282       | 45025       | 146500              | 191525        | 
| 2013-01-01T00:00:00 | 176927       | 43985       | 77500               | 171485        | 
| 2012-01-01T00:00:00 | 162054       | 43955       | 62000               | 105955        | 
| 2011-01-01T00:00:00 | 146956       | 44305       | 79150               | 123455        | 
| 2010-01-01T00:00:00 | 89720        | 33704       | 54000               | 87704         | 
| 2009-01-01T00:00:00 | 89913        | 36575       | 64000               | 100575        | 
| 2008-01-01T00:00:00 | 97486        | 32971       | 39000               | 71971         | 
| 2007-01-01T00:00:00 | 88976        | 33805       | 28000               | 61805         | 
```