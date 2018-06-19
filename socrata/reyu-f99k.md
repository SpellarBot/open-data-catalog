# Recovery Plan Progress Indicator 12212012-2

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/recovery-plan-progress-indicator-12212012-2-ad2c7) |
| Metadata | [Link](https://data.wa.gov/api/views/reyu-f99k) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/reyu-f99k/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/reyu-f99k/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | reyu-f99k |
| Name | Recovery Plan Progress Indicator 12212012-2 |
| Created | 2012-12-26T05:37:37Z |
| Publication Date | 2012-12-26T05:38:19Z |

## Columns

```ls
| Included | Schema Type    | Field Name | Name       | Data Type | Render Type |
| ======== | ============== | ========== | ========== | ========= | =========== |
| Yes      | time           | year       | Year       | number    | number      |
| Yes      | series tag     | region     | Region     | text      | text        |
| Yes      | numeric metric | habitat    | Habitat    | number    | number      |
| Yes      | numeric metric | hatchery   | Hatchery   | number    | number      |
| Yes      | numeric metric | harvest    | Harvest    | number    | number      |
| Yes      | numeric metric | hydropower | Hydropower | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:reyu-f99k d:2008-01-01T00:00:00.000Z t:region="Hood Canal" m:habitat=21 m:hydropower=8 m:hatchery=60 m:harvest=100

series e:reyu-f99k d:2010-01-01T00:00:00.000Z t:region="Hood Canal" m:habitat=29 m:hydropower=17 m:hatchery=70 m:harvest=100

series e:reyu-f99k d:2012-01-01T00:00:00.000Z t:region="Hood Canal" m:habitat=34 m:hydropower=25 m:hatchery=80 m:harvest=100
```

## Meta Commands

```ls
metric m:habitat p:integer l:Habitat t:dataTypeName=number

metric m:hatchery p:integer l:Hatchery t:dataTypeName=number

metric m:harvest p:integer l:Harvest t:dataTypeName=number

metric m:hydropower p:integer l:Hydropower t:dataTypeName=number

entity e:reyu-f99k l:"Recovery Plan Progress Indicator 12212012-2" t:url=https://data.wa.gov/api/views/reyu-f99k

property e:reyu-f99k t:meta.view v:id=reyu-f99k v:averageRating=0 v:name="Recovery Plan Progress Indicator 12212012-2"

property e:reyu-f99k t:meta.view.owner v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:displayName="Jennifer Johnson"

property e:reyu-f99k t:meta.view.tableauthor v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:roleName=publisher v:displayName="Jennifer Johnson"
```

## Top Records

```ls
| year | region         | habitat | hatchery | harvest | hydropower | 
| ==== | ============== | ======= | ======== | ======= | ========== | 
| 2008 | Hood Canal     | 21      | 60       | 100     | 8          | 
| 2010 | Hood Canal     | 29      | 70       | 100     | 17         | 
| 2012 | Hood Canal     | 34      | 80       | 100     | 25         | 
| 2008 | Lower Columbia |         |          | 50      |            | 
| 2010 | Lower Columbia | 30      | 35       | 60      | 30         | 
| 2012 | Lower Columbia | 40      | 60       | 70      | 50         | 
| 2008 | Mid-Columbia   | 15      | 70       | 75      | 60         | 
| 2010 | Mid-Columbia   | 30      | 70       | 80      | 70         | 
| 2012 | Mid-Columbia   | 40      | 80       | 85      | 80         | 
| 2008 | Puget Sound    | 2       |          | 88      |            | 
```