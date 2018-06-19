# Comparison of Residential Power and Water Rates

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/comparison-of-residential-power-and-water-rates-c86e9) |
| Metadata | [Link](https://data.lacity.org/api/views/mnrz-a5vv) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/mnrz-a5vv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/mnrz-a5vv/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | mnrz-a5vv |
| Name | Comparison of Residential Power and Water Rates |
| Category | A Well Run City |
| Tags | power, water, rates, residential |
| Created | 2014-05-15T01:26:09Z |
| Publication Date | 2015-12-07T20:30:00Z |

## Description

Comparison of LADWP Residential Power and Water Rates. Bills compare a typical monthly bill (500kWh/month of power and 12 HCF of water). Data is from Summer of 2013.

## Columns

```ls
| Included | Schema Type    | Field Name                       | Name                             | Data Type | Render Type |
| ======== | ============== | ================================ | ================================ | ========= | =========== |
| No       | time           | :updated_at                      | updated_at                       | meta_data | meta_data   |
| Yes      | series tag     | type_of_bill                     | Type of Bill                     | text      | text        |
| Yes      | series tag     | agency                           | Agency                           | text      | text        |
| Yes      | numeric metric | typical_monthly_residential_bill | Typical Monthly Residential Bill | money     | money       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:mnrz-a5vv d:2014-05-14T18:26:12.000Z t:type_of_bill=Power t:agency=LADWP m:typical_monthly_residential_bill=70.43

series e:mnrz-a5vv d:2014-05-14T18:26:12.000Z t:type_of_bill=Power t:agency=Pasadena m:typical_monthly_residential_bill=83.84

series e:mnrz-a5vv d:2014-05-14T18:26:12.000Z t:type_of_bill=Power t:agency=Glendale m:typical_monthly_residential_bill=71.66
```

## Meta Commands

```ls
metric m:typical_monthly_residential_bill p:double l:"Typical Monthly Residential Bill" t:dataTypeName=money

entity e:mnrz-a5vv l:"Comparison of Residential Power and Water Rates" t:url=https://data.lacity.org/api/views/mnrz-a5vv

property e:mnrz-a5vv t:meta.view v:id=mnrz-a5vv v:category="A Well Run City" v:averageRating=0 v:name="Comparison of Residential Power and Water Rates"

property e:mnrz-a5vv t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:mnrz-a5vv t:meta.view.owner v:id=hb8e-gdsp v:profileImageUrlMedium=/api/users/hb8e-gdsp/profile_images/THUMB v:profileImageUrlLarge=/api/users/hb8e-gdsp/profile_images/LARGE v:screenName="LA DWP OpenData" v:profileImageUrlSmall=/api/users/hb8e-gdsp/profile_images/TINY v:displayName="LA DWP OpenData"

property e:mnrz-a5vv t:meta.view.tableauthor v:id=hb8e-gdsp v:profileImageUrlMedium=/api/users/hb8e-gdsp/profile_images/THUMB v:profileImageUrlLarge=/api/users/hb8e-gdsp/profile_images/LARGE v:screenName="LA DWP OpenData" v:profileImageUrlSmall=/api/users/hb8e-gdsp/profile_images/TINY v:roleName=publisher v:displayName="LA DWP OpenData"
```

## Top Records

```ls
| :updated_at | type_of_bill | agency     | typical_monthly_residential_bill | 
| =========== | ============ | ========== | ================================ | 
| 1400091972  | Power        | LADWP      | 70.43                            | 
| 1400091972  | Power        | Pasadena   | 83.84                            | 
| 1400091972  | Power        | Glendale   | 71.66                            | 
| 1400091972  | Power        | Burbank    | 74.78                            | 
| 1400091972  | Power        | SC Edison  | 86.22                            | 
| 1400091972  | Power        | San Diego  | 88.67                            | 
| 1400091972  | Water        | Long Beach | 40.59                            | 
| 1400091972  | Water        | Pasadena   | 41.83                            | 
| 1400091972  | Water        | Glendale   | 43.92                            | 
| 1400091972  | Water        | Oakland    | 45.31                            | 
```