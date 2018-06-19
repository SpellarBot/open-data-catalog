# Polling Locations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/polling-locations-acf99) |
| Metadata | [Link](https://data.baltimorecity.gov/api/views/u7bw-gha5) |
| Data: JSON | [100 Rows](https://data.baltimorecity.gov/api/views/u7bw-gha5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.baltimorecity.gov/api/views/u7bw-gha5/rows.csv?max_rows=100) |
| Host | data.baltimorecity.gov |
| Id | u7bw-gha5 |
| Name | Polling Locations |
| Attribution | Baltimore City Elections Board |
| Category | City Government |
| Tags | polls, election |
| Created | 2011-12-14T19:01:43Z |
| Publication Date | 2014-04-03T23:41:21Z |

## Description

City of Baltimore polling locations

## Columns

```ls
| Included | Schema Type    | Field Name    | Name          | Data Type | Render Type |
| ======== | ============== | ============= | ============= | ========= | =========== |
| No       | time           | :updated_at   | updated_at    | meta_data | meta_data   |
| Yes      | series tag     | name          | name          | text      | text        |
| Yes      | series tag     | altname       | altName       | text      | text        |
| Yes      | series tag     | precinct      | precinct      | text      | number      |
| Yes      | series tag     | zipcode       | zipCode       | text      | text        |
| Yes      | numeric metric | legislative   | legislative   | number    | text        |
| Yes      | numeric metric | congressional | congressional | number    | text        |
| Yes      | numeric metric | judicial      | judicial      | number    | text        |
| Yes      | numeric metric | appellate     | appellate     | number    | text        |
| Yes      | numeric metric | councilman    | councilman    | number    | text        |
| Yes      | numeric metric | ispublic      | isPublic      | number    | number      |
| Yes      | series tag     | snowroute     | snowRoute     | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:u7bw-gha5 d:2011-12-14T11:02:00.000Z t:precinct=1 t:snowroute=Primary t:altname="School No. 47" t:zipcode=21224 t:name="Hampstead Hill Academy" m:judicial=8 m:legislative=46 m:ispublic=1 m:congressional=3 m:appellate=6 m:councilman=1

series e:u7bw-gha5 d:2011-12-14T11:02:00.000Z t:precinct=2 t:snowroute=Primary t:altname="Engine House No. 5" t:zipcode=21231 t:name="Engine House No. 5" m:judicial=8 m:legislative=46 m:ispublic=1 m:congressional=3 m:appellate=6 m:councilman=1

series e:u7bw-gha5 d:2011-12-14T11:02:00.000Z t:precinct=3 t:snowroute=Primary t:altname="School No. 47" t:zipcode=21224 t:name="Hampstead Hill Academy" m:judicial=8 m:legislative=46 m:ispublic=1 m:congressional=3 m:appellate=6 m:councilman=1
```

## Meta Commands

```ls
metric m:legislative p:long l:legislative t:dataTypeName=number

metric m:congressional p:long l:congressional t:dataTypeName=number

metric m:judicial p:long l:judicial t:dataTypeName=number

metric m:appellate p:long l:appellate t:dataTypeName=number

metric m:councilman p:long l:councilman t:dataTypeName=number

metric m:ispublic p:integer l:isPublic t:dataTypeName=number

entity e:u7bw-gha5 l:"Polling Locations" t:attribution="Baltimore City Elections Board" t:url=https://data.baltimorecity.gov/api/views/u7bw-gha5

property e:u7bw-gha5 t:meta.view v:id=u7bw-gha5 v:category="City Government" v:attributionLink=http://www.baltimorecity.gov/Government/BoardsandCommissions/ElectionsBoard.aspx v:averageRating=0 v:name="Polling Locations" v:attribution="Baltimore City Elections Board"

property e:u7bw-gha5 t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:u7bw-gha5 t:meta.view.owner v:id=6r9a-dfdj v:screenName="Open Baltimore" v:displayName="Open Baltimore"

property e:u7bw-gha5 t:meta.view.tableauthor v:id=6r9a-dfdj v:screenName="Open Baltimore" v:roleName=administrator v:displayName="Open Baltimore"
```

## Top Records

```ls
| :updated_at | name                          | altname                    | precinct | zipcode | legislative | congressional | judicial | appellate | councilman | ispublic | snowroute | 
| =========== | ============================= | ========================== | ======== | ======= | =========== | ============= | ======== | ========= | ========== | ======== | ========= | 
| 1323860520  | Hampstead Hill Academy        | School No. 47              | 1        | 21224   | 46          | 3             | 8        | 6         | 1          | 1        | Primary   | 
| 1323860520  | Engine House No. 5            | Engine House No. 5         | 2        | 21231   | 46          | 3             | 8        | 6         | 1          | 1        | Primary   | 
| 1323860520  | Hampstead Hill Academy        | School No. 47              | 3        | 21224   | 46          | 3             | 8        | 6         | 1          | 1        | Primary   | 
| 1323860520  | St. Brigid's Church           | St. Brigid's Church        | 4        | 21224   | 46          | 3             | 8        | 6         | 1          | 1        | Primary   | 
| 1323860520  | Hatton Senior Citizens Center | Hatton Senior Citizens Cen | 5        | 21224   | 46          | 3             | 8        | 6         | 1          | 1        | Secondary | 
| 1323860520  | St. Michaels' Church Hall     | St. Michaels' Church Hall  | 1        | 21231   | 46          | 3             | 8        | 6         | 1          | 1        | Primary   | 
| 1323860520  | General Wolfe Elementary      | School No. 23              | 2        | 21231   | 46          | 3             | 8        | 6         | 1          | 1        | Primary   | 
| 1323860520  | Lemko House                   | Lemko House                | 3        | 21231   | 46          | 3             | 8        | 6         | 1          | 1        | Primary   | 
| 1323860520  | Lombard Middle                | School No. 57              | 1        | 21231   | 46          | 7             | 8        | 6         | 1          | 1        | Primary   | 
| 1323860520  | St. Leo's Church Hall         | St. Leo's Church Hall      | 3        | 21202   | 46          | 3             | 8        | 6         | 1          | 1        | Primary   | 
```