# Utility Base Rate Change - Delivery Rates Beginning 1998

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/utility-base-rate-change-delivery-rates-beginning-1998) |
| Metadata | [Link](https://data.ny.gov/api/views/ddrw-g9a6) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/ddrw-g9a6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/ddrw-g9a6/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | ddrw-g9a6 |
| Name | Utility Base Rate Change - Delivery Rates Beginning 1998 |
| Attribution | New York State Public Service Commission |
| Category | Energy & Environment |
| Tags | utility rates |
| Created | 2013-02-27T20:22:21Z |
| Publication Date | 2016-10-27T18:50:06Z |

## Description

Summary of 15 years worth of utility base rate changes for major NYS utilities.

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                        | Data Type     | Render Type   |
| ======== | ============== | ========================== | =========================== | ============= | ============= |
| Yes      | series tag     | company                    | Company                     | text          | text          |
| Yes      | series tag     | electric_gas               | Electric/Gas                | text          | text          |
| Yes      | series tag     | case                       | Case                        | text          | text          |
| Yes      | time           | date_effective             | Date Effective              | calendar_date | calendar_date |
| Yes      | numeric metric | change_millions_of_dollars | Change, Millions of Dollars | money         | money         |
| Yes      | numeric metric | change_percent             | Change, Percent             | percent       | percent       |
| Yes      | series tag     | comment                    | Comment                     | text          | text          |
```

## Time Field

```ls
Value = date_effective
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:ddrw-g9a6 d:1998-06-30T00:00:00.000Z t:company="Central Hudson" t:electric_gas=Electric t:case="CASE 96-E-0909" t:comment="Decrease in bundled rates (based on actual 1998 and 1999 revenues)" m:change_millions_of_dollars=-3 m:change_percent=-0.7

series e:ddrw-g9a6 d:2001-07-01T00:00:00.000Z t:company="Central Hudson" t:electric_gas=Electric t:case="CASE 00-E-1273" t:comment="Decrease in delivery rates" m:change_millions_of_dollars=-3.1 m:change_percent=-2

series e:ddrw-g9a6 d:2003-07-01T00:00:00.000Z t:company="Central Hudson" t:electric_gas=Electric t:case="CASE 00-E-1274" t:comment="Increase in delivery rates" m:change_millions_of_dollars=3.1 m:change_percent=2
```

## Meta Commands

```ls
metric m:change_millions_of_dollars p:double l:"Change, Millions of Dollars" d:"This is the dollar amount of the rate change, in milions." t:dataTypeName=money

metric m:change_percent p:float l:"Change, Percent" d:"This is the percentage change in rates." t:dataTypeName=percent

entity e:ddrw-g9a6 l:"Utility Base Rate Change  - Delivery Rates Beginning 1998" t:attribution="New York State Public Service Commission" t:url=https://data.ny.gov/api/views/ddrw-g9a6

property e:ddrw-g9a6 t:meta.view v:id=ddrw-g9a6 v:category="Energy & Environment" v:averageRating=0 v:name="Utility Base Rate Change  - Delivery Rates Beginning 1998" v:attribution="New York State Public Service Commission"

property e:ddrw-g9a6 t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:ddrw-g9a6 t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:ddrw-g9a6 t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| company        | electric_gas | case           | date_effective      | change_millions_of_dollars | change_percent | comment                                                            | 
| ============== | ============ | ============== | =================== | ========================== | ============== | ================================================================== | 
| Central Hudson | Electric     | CASE 96-E-0909 | 1998-06-30T00:00:00 | -3.0                       | -0.7           | Decrease in bundled rates (based on actual 1998 and 1999 revenues) | 
| Central Hudson | Electric     | CASE 00-E-1273 | 2001-07-01T00:00:00 | -3.1                       | -2.0           | Decrease in delivery rates                                         | 
| Central Hudson | Electric     | CASE 00-E-1274 | 2003-07-01T00:00:00 | 3.1                        | 2.0            | Increase in delivery rates                                         | 
| Central Hudson | Electric     | CASE 05-E-0934 | 2006-07-01T00:00:00 | 17.9                       | 10.5           | Increase in delivery rates                                         | 
| Central Hudson | Electric     | CASE 05-E-0934 | 2007-07-01T00:00:00 | 17.9                       | 9.3            | Increase in delivery rates                                         | 
| Central Hudson | Electric     | CASE 05-E-0934 | 2008-07-01T00:00:00 | 17.9                       | 8.4            | Increase in delivery rates                                         | 
| Central Hudson | Electric     | CASE 08-E-0887 | 2009-07-01T00:00:00 | 19.6                       | 9.0            | Increase in delivery rates                                         | 
| Central Hudson | Electric     | CASE 09-E-0588 | 2010-07-01T00:00:00 | 11.8                       | 4.6            | Increase in delivery rates                                         | 
| Central Hudson | Electric     | CASE 09-E-0588 | 2011-07-01T00:00:00 | 9.3                        | 3.5            | Increase in delivery rates                                         | 
| Central Hudson | Electric     | CASE 09-E-0588 | 2012-07-01T00:00:00 | 9.1                        | 3.3            | Increase in delivery rates                                         | 
```