# WA Coast Upload 2 09242012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/wa-coast-upload-2-09242012-3efd3) |
| Metadata | [Link](https://data.wa.gov/api/views/d29f-ixy9) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/d29f-ixy9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/d29f-ixy9/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | d29f-ixy9 |
| Name | WA Coast Upload 2 09242012 |
| Created | 2012-09-24T21:36:31Z |
| Publication Date | 2012-09-24T21:37:17Z |

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type | Render Type |
| ======== | ============== | ======================= | ======================= | ========= | =========== |
| Yes      | series tag     | population_stock_number | Population/Stock Number | text      | text        |
| Yes      | time           | year                    | Year                    | number    | number      |
| Yes      | numeric metric | wild                    | Wild                    | number    | number      |
| Yes      | numeric metric | hatchery                | Hatchery                | number    | number      |
| Yes      | numeric metric | total_wild_hatchery     | Total (Wild + Hatchery) | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:d29f-ixy9 d:1976-01-01T00:00:00.000Z t:population_stock_number="Queets Spring Summer Chinook" m:wild=505 m:total_wild_hatchery=505 m:hatchery=0

series e:d29f-ixy9 d:1977-01-01T00:00:00.000Z t:population_stock_number="Queets Spring Summer Chinook" m:wild=732 m:total_wild_hatchery=732 m:hatchery=0

series e:d29f-ixy9 d:1978-01-01T00:00:00.000Z t:population_stock_number="Queets Spring Summer Chinook" m:wild=1110 m:total_wild_hatchery=1110 m:hatchery=0
```

## Meta Commands

```ls
metric m:wild p:integer l:Wild t:dataTypeName=number

metric m:hatchery p:integer l:Hatchery t:dataTypeName=number

metric m:total_wild_hatchery p:integer l:"Total (Wild + Hatchery)" t:dataTypeName=number

entity e:d29f-ixy9 l:"WA Coast Upload 2 09242012" t:url=https://data.wa.gov/api/views/d29f-ixy9

property e:d29f-ixy9 t:meta.view v:id=d29f-ixy9 v:averageRating=0 v:name="WA Coast Upload 2 09242012"

property e:d29f-ixy9 t:meta.view.owner v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:displayName="Jennifer Johnson"

property e:d29f-ixy9 t:meta.view.tableauthor v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:roleName=publisher v:displayName="Jennifer Johnson"
```

## Top Records

```ls
| population_stock_number      | year | wild | hatchery | total_wild_hatchery | 
| ============================ | ==== | ==== | ======== | =================== | 
| Queets Spring Summer Chinook | 1976 | 505  | 0        | 505                 | 
| Queets Spring Summer Chinook | 1977 | 732  | 0        | 732                 | 
| Queets Spring Summer Chinook | 1978 | 1110 | 0        | 1110                | 
| Queets Spring Summer Chinook | 1979 | 870  | 118      | 988                 | 
| Queets Spring Summer Chinook | 1980 | 1038 | 0        | 1038                | 
| Queets Spring Summer Chinook | 1981 | 988  | 0        | 988                 | 
| Queets Spring Summer Chinook | 1982 | 781  | 119      | 900                 | 
| Queets Spring Summer Chinook | 1983 | 1044 | 38       | 1082                | 
| Queets Spring Summer Chinook | 1984 | 958  |          | 958                 | 
| Queets Spring Summer Chinook | 1985 | 677  |          | 677                 | 
```