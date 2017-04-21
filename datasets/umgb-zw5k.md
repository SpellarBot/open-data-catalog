# IDPH Multiple Births, by County, 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idph-multiple-births-by-county-2009-ac95b) |
| Metadata | [Link](https://data.illinois.gov/api/views/umgb-zw5k) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/umgb-zw5k/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/umgb-zw5k/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | umgb-zw5k |
| Name | IDPH Multiple Births, by County, 2009 |
| Attribution | Illinois Center for Health Statistics |
| Category | Public Health |
| Tags | multiple, birth |
| Created | 2012-01-18T21:44:03Z |
| Publication Date | 2012-01-23T21:25:48Z |

## Columns

```ls
| Included | Schema Type    | Field Name        | Name             | Data Type | Render Type |
| ======== | ============== | ================= | ================ | ========= | =========== |
| Yes      | series tag     | county            | County           | text      | text        |
| Yes      | numeric metric | all_live_births_  | All Live Births  | number    | number      |
| Yes      | numeric metric | singleton_births_ | Singleton Births | number    | number      |
| Yes      | numeric metric | twin_births_      | Twin Births      | number    | number      |
| Yes      | numeric metric | births            | 3+ Births        | number    | number      |
```

## Time Field

```ls
Value = 2009
Format & Zone = yyyy
```

## Data Commands

```ls
series e:umgb-zw5k d:2009-01-01T00:00:00.000Z t:county=Adams m:singleton_births_=780 m:all_live_births_=804 m:twin_births_=24 m:births=0

series e:umgb-zw5k d:2009-01-01T00:00:00.000Z t:county=Alexander m:singleton_births_=110 m:all_live_births_=114 m:twin_births_=4 m:births=0

series e:umgb-zw5k d:2009-01-01T00:00:00.000Z t:county=Bond m:singleton_births_=190 m:all_live_births_=198 m:twin_births_=8 m:births=0
```

## Meta Commands

```ls
metric m:all_live_births_ p:integer l:"All Live Births" t:dataTypeName=number

metric m:singleton_births_ p:integer l:"Singleton Births" t:dataTypeName=number

metric m:twin_births_ p:integer l:"Twin Births" t:dataTypeName=number

metric m:births p:integer l:"3+ Births" t:dataTypeName=number

entity e:umgb-zw5k l:"IDPH Multiple Births, by County, 2009" t:attribution="Illinois Center for Health Statistics" t:url=https://data.illinois.gov/api/views/umgb-zw5k

property e:umgb-zw5k t:meta.view v:id=umgb-zw5k v:category="Public Health" v:attributionLink=http://www.idph.state.il.us/health/statshome.htm v:averageRating=0 v:name="IDPH Multiple Births, by County, 2009" v:attribution="Illinois Center for Health Statistics"

property e:umgb-zw5k t:meta.view.owner v:id=e75b-y6hv v:screenName=Jenny v:displayName=Jenny

property e:umgb-zw5k t:meta.view.tableauthor v:id=ws2v-m6rq v:screenName="jonathan nuttall" v:displayName="jonathan nuttall"
```

## Top Records

```ls
| county    | all_live_births_ | singleton_births_ | twin_births_ | births | 
| ========= | ================ | ================= | ============ | ====== | 
| Adams     | 804              | 780               | 24           | 0      | 
| Alexander | 114              | 110               | 4            | 0      | 
| Bond      | 198              | 190               | 8            | 0      | 
| Boone     | 622              | 601               | 21           | 0      | 
| Brown     | 65               | 63                | 2            | 0      | 
| Bureau    | 381              | 377               | 4            | 0      | 
| Calhoun   | 53               | 51                | 2            | 0      | 
| Carroll   | 123              | 119               | 4            | 0      | 
| Cass      | 164              | 162               | 2            | 0      | 
| Champaign | 2407             | 2302              | 102          | 3      | 
```