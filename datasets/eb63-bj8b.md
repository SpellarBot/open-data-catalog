# Pet Data - 2016 Animal Control Officer Service Calls

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/pet-data-2016-animal-control-officer-service-calls) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/eb63-bj8b) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/eb63-bj8b/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/eb63-bj8b/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | eb63-bj8b |
| Name | Pet Data - 2016 Animal Control Officer Service Calls |
| Attribution | King County |
| Category | Pets |
| Created | 2015-12-11T16:24:33Z |
| Publication Date | 2017-01-18T16:48:20Z |

## Columns

```ls
| Included | Schema Type    | Field Name    | Name          | Data Type | Render Type |
| ======== | ============== | ============= | ============= | ========= | =========== |
| Yes      | series tag     | month         | Month         | text      | text        |
| Yes      | numeric metric | service_calls | Service Calls | number    | number      |
```

## Time Field

```ls
Value = 2016
Format & Zone = yyyy
```

## Data Commands

```ls
series e:eb63-bj8b d:2016-01-01T00:00:00.000Z t:month=Jan m:service_calls=346

series e:eb63-bj8b d:2016-01-01T00:00:00.000Z t:month=Feb m:service_calls=370

series e:eb63-bj8b d:2016-01-01T00:00:00.000Z t:month=Mar m:service_calls=416
```

## Meta Commands

```ls
metric m:service_calls p:integer l:"Service Calls" t:dataTypeName=number

entity e:eb63-bj8b l:"Pet Data - 2016 Animal Control Officer Service Calls" t:attribution="King County" t:url=https://data.kingcounty.gov/api/views/eb63-bj8b

property e:eb63-bj8b t:meta.view v:id=eb63-bj8b v:category=Pets v:averageRating=0 v:name="Pet Data - 2016 Animal Control Officer Service Calls" v:attribution="King County"

property e:eb63-bj8b t:meta.view.owner v:id=ph9f-eu4i v:screenName=Cameron v:displayName=Cameron

property e:eb63-bj8b t:meta.view.tableauthor v:id=ph9f-eu4i v:screenName=Cameron v:roleName=publisher v:displayName=Cameron
```

## Top Records

```ls
| month | service_calls | 
| ===== | ============= | 
| Jan   | 346           | 
| Feb   | 370           | 
| Mar   | 416           | 
| Apr   | 437           | 
| May   | 463           | 
| Jun   | 504           | 
| Jul   | 480           | 
| Aug   | 521           | 
| Sep   | 458           | 
| Oct   | 478           | 
```