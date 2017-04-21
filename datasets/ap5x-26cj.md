# Statewide Non Tribal Coho And Chinook Comm Rec Harvest 11-07-2016

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/statewide-non-tribal-coho-and-chinook-comm-rec-harvest-11-07-2016) |
| Metadata | [Link](https://data.wa.gov/api/views/ap5x-26cj) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/ap5x-26cj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/ap5x-26cj/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | ap5x-26cj |
| Name | Statewide Non Tribal Coho And Chinook Comm Rec Harvest 11-07-2016 |
| Created | 2016-11-07T12:52:23Z |
| Publication Date | 2016-11-10T23:56:57Z |

## Columns

```ls
| Included | Schema Type    | Field Name | Name    | Data Type | Render Type |
| ======== | ============== | ========== | ======= | ========= | =========== |
| Yes      | time           | year       | Year    | number    | text        |
| Yes      | numeric metric | chinook    | Chinook | number    | number      |
| Yes      | numeric metric | coho       | Coho    | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:ap5x-26cj d:1973-01-01T00:00:00.000Z m:chinook=971791 m:coho=2020668

series e:ap5x-26cj d:1974-01-01T00:00:00.000Z m:chinook=956572 m:coho=2425189

series e:ap5x-26cj d:1975-01-01T00:00:00.000Z m:chinook=1061383 m:coho=2075792
```

## Meta Commands

```ls
metric m:chinook p:integer l:Chinook t:dataTypeName=number

metric m:coho p:integer l:Coho t:dataTypeName=number

entity e:ap5x-26cj l:"Statewide Non Tribal Coho And Chinook Comm Rec Harvest 11-07-2016" t:url=https://data.wa.gov/api/views/ap5x-26cj

property e:ap5x-26cj t:meta.view v:id=ap5x-26cj v:averageRating=0 v:name="Statewide Non Tribal Coho And Chinook Comm Rec Harvest 11-07-2016"

property e:ap5x-26cj t:meta.view.owner v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:displayName="Jennifer Johnson"

property e:ap5x-26cj t:meta.view.tableauthor v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:roleName=publisher v:displayName="Jennifer Johnson"
```

## Top Records

```ls
| year | chinook | coho    | 
| ==== | ======= | ======= | 
| 1969 |         |         | 
| 1970 |         |         | 
| 1971 |         |         | 
| 1972 |         |         | 
| 1973 | 971791  | 2020668 | 
| 1974 | 956572  | 2425189 | 
| 1975 | 1061383 | 2075792 | 
| 1976 | 1011721 | 2998961 | 
| 1977 | 853685  | 1949210 | 
| 1978 | 649361  | 1702034 | 
```