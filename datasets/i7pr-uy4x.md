# DBEDT Hawaii De Facto Population By County 2000-2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dbedt-hawaii-de-facto-population-by-county-2000-2010-a67b7) |
| Metadata | [Link](https://data.hawaii.gov/api/views/i7pr-uy4x) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/i7pr-uy4x/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/i7pr-uy4x/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | i7pr-uy4x |
| Name | DBEDT Hawaii De Facto Population By County 2000-2010 |
| Attribution | Department of Economic Development and Tourism |
| Category | Economic Development |
| Tags | people, population |
| Created | 2012-08-28T19:43:49Z |
| Publication Date | 2012-08-29T01:28:08Z |

## Columns

```ls
| Included | Schema Type    | Field Name                  | Name                        | Data Type | Render Type |
| ======== | ============== | =========================== | =========================== | ========= | =========== |
| Yes      | numeric metric | x_values                    | X Values                    | number    | number      |
| Yes      | numeric metric | city_and_county_of_honolulu | City and County of Honolulu | number    | number      |
| Yes      | numeric metric | hawaii_county               | Hawaii County               | number    | number      |
| Yes      | numeric metric | kauai_county                | Kauai County                | number    | number      |
| Yes      | numeric metric | maui_county                 | Maui County                 | number    | number      |
```

## Time Field

```ls
Value = 2000
Format & Zone = yyyy
```

## Data Commands

```ls
series e:i7pr-uy4x d:2000-01-01T00:00:00.000Z m:hawaii_county=137103 m:city_and_county_of_honolulu=913268 m:maui_county=138390 m:kauai_county=68558 m:x_values=1990

series e:i7pr-uy4x d:2000-01-01T00:00:00.000Z m:hawaii_county=141240 m:city_and_county_of_honolulu=901717 m:maui_county=139703 m:kauai_county=69605 m:x_values=1991

series e:i7pr-uy4x d:2000-01-01T00:00:00.000Z m:hawaii_county=146421 m:city_and_county_of_honolulu=912514 m:maui_county=146651 m:kauai_county=66076 m:x_values=1992
```

## Meta Commands

```ls
metric m:x_values p:integer l:"X Values" t:dataTypeName=number

metric m:city_and_county_of_honolulu p:integer l:"City and County of Honolulu" t:dataTypeName=number

metric m:hawaii_county p:integer l:"Hawaii County" t:dataTypeName=number

metric m:kauai_county p:integer l:"Kauai County" t:dataTypeName=number

metric m:maui_county p:integer l:"Maui County" t:dataTypeName=number

entity e:i7pr-uy4x l:"DBEDT Hawaii De Facto Population By County 2000-2010" t:attribution="Department of Economic Development and Tourism" t:url=https://data.hawaii.gov/api/views/i7pr-uy4x

property e:i7pr-uy4x t:meta.view d:2017-06-09T13:54:12.830Z v:id=i7pr-uy4x v:category="Economic Development" v:attributionLink=http://hawaii.gov/dbedt v:averageRating=0 v:name="DBEDT Hawaii De Facto Population By County 2000-2010" v:attribution="Department of Economic Development and Tourism"

property e:i7pr-uy4x t:meta.view.license d:2017-06-09T13:54:12.830Z v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:i7pr-uy4x t:meta.view.owner d:2017-06-09T13:54:12.830Z v:id=uaqq-pakk v:screenName="Douglas Oshiro" v:displayName="Douglas Oshiro"

property e:i7pr-uy4x t:meta.view.tableauthor d:2017-06-09T13:54:12.830Z v:id=uaqq-pakk v:screenName="Douglas Oshiro" v:displayName="Douglas Oshiro"
```

## Top Records

```ls
| x_values | city_and_county_of_honolulu | hawaii_county | kauai_county | maui_county | 
| ======== | =========================== | ============= | ============ | =========== | 
| 1990     | 913268                      | 137103        | 68558        | 138390      | 
| 1991     | 901717                      | 141240        | 69605        | 139703      | 
| 1992     | 912514                      | 146421        | 66076        | 146651      | 
| 1993     | 909506                      | 148014        | 61262        | 149067      | 
| 1994     | 919898                      | 150311        | 67161        | 152434      | 
| 1995     | 921626                      | 152482        | 68844        | 155144      | 
| 1996     | 921609                      | 154364        | 70474        | 157468      | 
| 1997     | 932931                      | 161225        | 71763        | 162011      | 
| 1998     | 931439                      | 165205        | 73920        | 163562      | 
| 1999     | 927689                      | 164570        | 74441        | 165743      | 
```