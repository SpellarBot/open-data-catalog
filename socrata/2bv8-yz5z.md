# IDES - Statewide 2011 Q1 Establishment and Employment Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ides-statewide-2011-q1-establishment-and-employment-data-28731) |
| Metadata | [Link](https://data.illinois.gov/api/views/2bv8-yz5z) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/2bv8-yz5z/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/2bv8-yz5z/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | 2bv8-yz5z |
| Name | IDES - Statewide 2011 Q1 Establishment and Employment Data |
| Attribution | IDES - Economic Information and Analysis Division |
| Category | Economics |
| Tags | ides - statewide 2011 q1 establishment and employment data, employment, establishment, ides |
| Created | 2012-04-20T19:34:55Z |
| Publication Date | 2012-04-23T18:53:07Z |

## Columns

```ls
| Included | Schema Type | Field Name | Name       | Data Type | Render Type |
| ======== | =========== | ========== | ========== | ========= | =========== |
| Yes      | series tag  | code       | Code       | text      | text        |
| Yes      | series tag  | title      | Title      | text      | text        |
| Yes      | series tag  | size_class | Size Class | text      | text        |
| Yes      | series tag  | of_firms   | # of Firms | text      | text        |
| Yes      | series tag  | employment | Employment | text      | text        |
```

## Time Field

```ls
Value = 2011
Format & Zone = yyyy
```

## Data Commands

```ls
series e:2bv8-yz5z d:2011-01-01T00:00:00.000Z t:of_firms=*** t:title="Agriculture, Forestry, Fishing & Hunting" t:employment=1,843 t:code=11 t:size_class=0-4 m:row_number.2bv8-yz5z=1

series e:2bv8-yz5z d:2011-01-01T00:00:00.000Z t:of_firms=385 t:employment=2,489 t:size_class=5-9 m:row_number.2bv8-yz5z=2

series e:2bv8-yz5z d:2011-01-01T00:00:00.000Z t:of_firms=180 t:employment=2,466 t:size_class=10-19 m:row_number.2bv8-yz5z=3
```

## Meta Commands

```ls
metric m:row_number.2bv8-yz5z p:long l:"Row Number"

entity e:2bv8-yz5z l:"IDES - Statewide 2011 Q1 Establishment and Employment Data" t:attribution="IDES - Economic Information and Analysis Division" t:url=https://data.illinois.gov/api/views/2bv8-yz5z

property e:2bv8-yz5z t:meta.view v:id=2bv8-yz5z v:category=Economics v:averageRating=0 v:name="IDES - Statewide 2011 Q1 Establishment and Employment Data" v:attribution="IDES - Economic Information and Analysis Division"

property e:2bv8-yz5z t:meta.view.owner v:id=6i42-mskp v:screenName="David Egan" v:displayName="David Egan"

property e:2bv8-yz5z t:meta.view.tableauthor v:id=6i42-mskp v:screenName="David Egan" v:displayName="David Egan"
```

## Top Records

```ls
| code  | title                                    | size_class | of_firms | employment | 
| ===== | ======================================== | ========== | ======== | ========== | 
| 11    | Agriculture, Forestry, Fishing & Hunting | 0-4        | ***      | 1,843      | 
|       |                                          | 5-9        | 385      | 2,489      | 
|       |                                          | 10-19      | 180      | 2,466      | 
|       |                                          | 20-49      | 96       | 2,597      | 
|       |                                          | 50-99      | 27       | 1,765      | 
|       |                                          | 100-249    | 8        | 1,102      | 
|       |                                          | 250-499    | 3        | 1,084      | 
| 21-22 | Mining and Utilities                     | 0-4        | ***      | 1,022      | 
|       |                                          | 5-9        | 180      | 1,180      | 
|       |                                          | 10-19      | 155      | 2,140      | 
```