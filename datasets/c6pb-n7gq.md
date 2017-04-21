# Typical Utility Bill Information Gas: Beginning 2011

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/typical-utility-bill-information-gas-beginning-2011) |
| Metadata | [Link](https://data.ny.gov/api/views/c6pb-n7gq) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/c6pb-n7gq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/c6pb-n7gq/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | c6pb-n7gq |
| Name | Typical Utility Bill Information Gas: Beginning 2011 |
| Attribution | New York State Public Service Commission |
| Category | Energy & Environment |
| Tags | gas bills, typical gas bills, utility bills, average bills |
| Created | 2013-02-27T21:06:22Z |
| Publication Date | 2013-03-05T20:33:47Z |

## Description

Typical average monthly gas bills for residential, commercial and industrial customers.  Customer usage is in Therms or CCF.  -Residential customer bills are shown for usages of 0, 10, 20, 50, 100, 200, 300, and 400 CCF or Therms.  -Commercial and Industrial customer bills are shown for usages of 10,000, 100,000, and 1,000,000 CCF or Therms.

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type     | Render Type   |
| ======== | ============== | ================ | ================ | ============= | ============= |
| Yes      | time           | effective_date   | Effective Date   | calendar_date | calendar_date |
| Yes      | series tag     | season           | Season           | text          | text          |
| Yes      | series tag     | service_type     | Service Type     | text          | text          |
| Yes      | series tag     | company          | Company          | text          | text          |
| Yes      | series tag     | customer_type    | Customer Type    | text          | text          |
| Yes      | series tag     | customer_details | Customer Details | text          | text          |
| Yes      | numeric metric | usage            | Usage            | number        | number        |
| Yes      | series tag     | units_of_usage   | Units of Usage   | text          | text          |
| Yes      | numeric metric | total_bill       | Total Bill       | money         | money         |
```

## Time Field

```ls
Value = effective_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:c6pb-n7gq d:2011-07-01T00:00:00.000Z t:units_of_usage=THERMS t:customer_details="SPACE HEATING CUSTOMERS" t:season="SUMMER 2011" t:company="THE BROOKLYN UNION GAS COMPANY" t:service_type=GAS t:customer_type=RESIDENTIAL m:usage=0 m:total_bill=16.88

series e:c6pb-n7gq d:2011-07-01T00:00:00.000Z t:units_of_usage=THERMS t:customer_details="SPACE HEATING CUSTOMERS" t:season="SUMMER 2011" t:company="THE BROOKLYN UNION GAS COMPANY" t:service_type=GAS t:customer_type=RESIDENTIAL m:usage=10 m:total_bill=27.05

series e:c6pb-n7gq d:2011-07-01T00:00:00.000Z t:units_of_usage=THERMS t:customer_details="SPACE HEATING CUSTOMERS" t:season="SUMMER 2011" t:company="THE BROOKLYN UNION GAS COMPANY" t:service_type=GAS t:customer_type=RESIDENTIAL m:usage=20 m:total_bill=39.01
```

## Meta Commands

```ls
metric m:usage p:integer l:Usage t:dataTypeName=number

metric m:total_bill p:double l:"Total Bill" t:dataTypeName=money

entity e:c6pb-n7gq l:"Typical Utility Bill Information Gas: Beginning 2011" t:attribution="New York State Public Service Commission" t:url=https://data.ny.gov/api/views/c6pb-n7gq

property e:c6pb-n7gq t:meta.view v:id=c6pb-n7gq v:category="Energy & Environment" v:attributionLink=http://www3.dps.ny.gov/W/PSCWeb.nsf/All/C56A606DB183531F852576A50069A75D?OpenDocument v:averageRating=0 v:name="Typical Utility Bill Information Gas: Beginning 2011" v:attribution="New York State Public Service Commission"

property e:c6pb-n7gq t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:c6pb-n7gq t:meta.view.tableauthor v:id=mwxm-zess v:profileImageUrlMedium=/api/users/mwxm-zess/profile_images/THUMB v:profileImageUrlLarge=/api/users/mwxm-zess/profile_images/LARGE v:screenName="Lindsey Krough" v:profileImageUrlSmall=/api/users/mwxm-zess/profile_images/TINY v:roleName=administrator v:displayName="Lindsey Krough"

property e:c6pb-n7gq t:meta.view.metadata.custom_fields.common_core v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| effective_date      | season      | service_type | company                        | customer_type | customer_details            | usage | units_of_usage | total_bill | 
| =================== | =========== | ============ | ============================== | ============= | =========================== | ===== | ============== | ========== | 
| 2011-07-01T00:00:00 | SUMMER 2011 | GAS          | THE BROOKLYN UNION GAS COMPANY | RESIDENTIAL   | SPACE HEATING CUSTOMERS     | 0     | THERMS         | 16.88      | 
| 2011-07-01T00:00:00 | SUMMER 2011 | GAS          | THE BROOKLYN UNION GAS COMPANY | RESIDENTIAL   | SPACE HEATING CUSTOMERS     | 10    | THERMS         | 27.05      | 
| 2011-07-01T00:00:00 | SUMMER 2011 | GAS          | THE BROOKLYN UNION GAS COMPANY | RESIDENTIAL   | SPACE HEATING CUSTOMERS     | 20    | THERMS         | 39.01      | 
| 2011-07-01T00:00:00 | SUMMER 2011 | GAS          | THE BROOKLYN UNION GAS COMPANY | RESIDENTIAL   | SPACE HEATING CUSTOMERS     | 50    | THERMS         | 74.91      | 
| 2011-07-01T00:00:00 | SUMMER 2011 | GAS          | THE BROOKLYN UNION GAS COMPANY | RESIDENTIAL   | SPACE HEATING CUSTOMERS     | 100   | THERMS         | 118.64     | 
| 2011-07-01T00:00:00 | SUMMER 2011 | GAS          | THE BROOKLYN UNION GAS COMPANY | RESIDENTIAL   | SPACE HEATING CUSTOMERS     | 200   | THERMS         | 206.09     | 
| 2011-07-01T00:00:00 | SUMMER 2011 | GAS          | THE BROOKLYN UNION GAS COMPANY | RESIDENTIAL   | SPACE HEATING CUSTOMERS     | 300   | THERMS         | 293.54     | 
| 2011-07-01T00:00:00 | SUMMER 2011 | GAS          | THE BROOKLYN UNION GAS COMPANY | RESIDENTIAL   | SPACE HEATING CUSTOMERS     | 400   | THERMS         | 380.99     | 
| 2011-07-01T00:00:00 | SUMMER 2011 | GAS          | THE BROOKLYN UNION GAS COMPANY | RESIDENTIAL   | NON-SPACE HEATING CUSTOMERS | 0     | THERMS         | 14.24      | 
| 2011-07-01T00:00:00 | SUMMER 2011 | GAS          | THE BROOKLYN UNION GAS COMPANY | RESIDENTIAL   | NON-SPACE HEATING CUSTOMERS | 10    | THERMS         | 24.33      | 
```