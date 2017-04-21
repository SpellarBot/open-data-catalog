# TAX 12 2012 Liquid Fuel Allocations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/tax-12-2012-liquid-fuel-allocations-51fc4) |
| Metadata | [Link](https://data.hawaii.gov/api/views/cbix-g738) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/cbix-g738/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/cbix-g738/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | cbix-g738 |
| Name | TAX 12 2012 Liquid Fuel Allocations |
| Attribution | Department of Twaxation |
| Category | Government-Wide Support |
| Tags | fuel, tax, liquid allocation |
| Created | 2013-02-05T20:13:26Z |
| Publication Date | 2013-02-05T20:16:58Z |

## Description

* Effective July 1, 2010, environmental tax rate increased from $0.05 to $1.05 per barrel. Tax Research & Planning Monthly 01-15-13

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type | Render Type |
| ======== | ============== | ================= | ================= | ========= | =========== |
| Yes      | series tag     | county            | COUNTY            | text      | text        |
| Yes      | series tag     | source_of_revenue | SOURCE OF REVENUE | text      | text        |
| Yes      | numeric metric | amount            | AMOUNT            | money     | money       |
```

## Time Field

```ls
Value = 2012
Format & Zone = yyyy
```

## Data Commands

```ls
series e:cbix-g738 d:2012-01-01T00:00:00.000Z t:county="CITY & COUNTY OF HONOLULU" t:source_of_revenue="State Highway Special Fund" m:amount=4406849.75

series e:cbix-g738 d:2012-01-01T00:00:00.000Z t:county="CITY & COUNTY OF HONOLULU" t:source_of_revenue="State Airports Special Fund" m:amount=166919.5

series e:cbix-g738 d:2012-01-01T00:00:00.000Z t:county="CITY & COUNTY OF HONOLULU" t:source_of_revenue="State Boating Special Fund" m:amount=86439.06
```

## Meta Commands

```ls
metric m:amount p:double l:AMOUNT t:dataTypeName=money

entity e:cbix-g738 l:"TAX 12 2012 Liquid Fuel Allocations" t:attribution="Department of Twaxation" t:url=https://data.hawaii.gov/api/views/cbix-g738

property e:cbix-g738 t:meta.view v:id=cbix-g738 v:category="Government-Wide Support" v:attributionLink=http://www6.hawaii.gov/tax/a5_3txcolrpt.htm v:averageRating=0 v:name="TAX 12 2012 Liquid Fuel Allocations" v:attribution="Department of Twaxation"

property e:cbix-g738 t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:cbix-g738 t:meta.view.owner v:id=a5cm-ukuw v:profileImageUrlMedium=/api/users/a5cm-ukuw/profile_images/THUMB v:profileImageUrlLarge=/api/users/a5cm-ukuw/profile_images/LARGE v:screenName="OIMT Open Data Coordinator" v:profileImageUrlSmall=/api/users/a5cm-ukuw/profile_images/TINY v:displayName="OIMT Open Data Coordinator"

property e:cbix-g738 t:meta.view.tableauthor v:id=a5cm-ukuw v:profileImageUrlMedium=/api/users/a5cm-ukuw/profile_images/THUMB v:profileImageUrlLarge=/api/users/a5cm-ukuw/profile_images/LARGE v:screenName="OIMT Open Data Coordinator" v:profileImageUrlSmall=/api/users/a5cm-ukuw/profile_images/TINY v:roleName=publisher v:displayName="OIMT Open Data Coordinator"
```

## Top Records

```ls
| county                    | source_of_revenue                             | amount     | 
| ========================= | ============================================= | ========== | 
| CITY & COUNTY OF HONOLULU | State Highway Special Fund                    | 4406849.75 | 
| CITY & COUNTY OF HONOLULU | State Airports Special Fund                   | 166919.5   | 
| CITY & COUNTY OF HONOLULU | State Boating Special Fund                    | 86439.06   | 
| CITY & COUNTY OF HONOLULU | County Fuel Tax                               | 4150617.67 | 
| CITY & COUNTY OF HONOLULU | Environmental Response Revolving Fund         | 66125.35   | 
| CITY & COUNTY OF HONOLULU | Energy Security Special Fund                  | 198376.04  | 
| CITY & COUNTY OF HONOLULU | Energy Systems Development Special Fund       | 132250.69  | 
| CITY & COUNTY OF HONOLULU | Agricultural Development & Food Security Fund | 198376.04  | 
| CITY & COUNTY OF HONOLULU | General Fund                                  | 793504.16  | 
| COUNTY OF MAUI            | State Highway Special Fund                    | 945518.16  | 
```