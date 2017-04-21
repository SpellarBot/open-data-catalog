# Pet Data - 2015 Animal Control Officer Service Calls

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/pet-data-2015-animal-control-officer-service-calls) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/ue5x-8ttp) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/ue5x-8ttp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/ue5x-8ttp/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | ue5x-8ttp |
| Name | Pet Data - 2015 Animal Control Officer Service Calls |
| Category | Government |
| Created | 2015-02-06T20:10:11Z |
| Publication Date | 2016-01-06T23:29:18Z |

## Columns

```ls
| Included | Schema Type    | Field Name    | Name          | Data Type | Render Type |
| ======== | ============== | ============= | ============= | ========= | =========== |
| Yes      | series tag     | month         | Month         | text      | text        |
| Yes      | numeric metric | service_calls | Service Calls | number    | number      |
```

## Time Field

```ls
Value = 2015
Format & Zone = yyyy
```

## Data Commands

```ls
series e:ue5x-8ttp d:2015-01-01T00:00:00.000Z t:month=Jan m:service_calls=409

series e:ue5x-8ttp d:2015-01-01T00:00:00.000Z t:month=Feb m:service_calls=379

series e:ue5x-8ttp d:2015-01-01T00:00:00.000Z t:month=Mar m:service_calls=475
```

## Meta Commands

```ls
metric m:service_calls p:integer l:"Service Calls" t:dataTypeName=number

entity e:ue5x-8ttp l:"Pet Data - 2015 Animal Control Officer Service Calls" t:url=https://data.kingcounty.gov/api/views/ue5x-8ttp

property e:ue5x-8ttp t:meta.view v:id=ue5x-8ttp v:category=Government v:averageRating=0 v:name="Pet Data - 2015 Animal Control Officer Service Calls"

property e:ue5x-8ttp t:meta.view.owner v:id=ph9f-eu4i v:screenName=Cameron v:displayName=Cameron

property e:ue5x-8ttp t:meta.view.tableauthor v:id=ph9f-eu4i v:screenName=Cameron v:roleName=publisher v:displayName=Cameron
```

## Top Records

```ls
| month | service_calls | 
| ===== | ============= | 
| Jan   | 409           | 
| Feb   | 379           | 
| Mar   | 475           | 
| Apr   | 430           | 
| May   | 463           | 
| Jun   | 556           | 
| Jul   | 583           | 
| Aug   | 557           | 
| Sep   | 478           | 
| Oct   | 480           | 
```