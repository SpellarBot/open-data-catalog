# Pet Data - 2017 Spay/Neuter Surgeries

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/pet-data-2017-spay-neuter-surgeries) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/mvpx-bvin) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/mvpx-bvin/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/mvpx-bvin/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | mvpx-bvin |
| Name | Pet Data - 2017 Spay/Neuter Surgeries |
| Created | 2017-01-18T21:16:30Z |
| Publication Date | 2017-03-03T19:43:34Z |

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type | Render Type |
| ======== | ============== | ======================= | ======================= | ========= | =========== |
| Yes      | series tag     | month                   | Month                   | text      | text        |
| Yes      | numeric metric | animals_spayed_neutered | Animals Spayed/Neutered | number    | number      |
```

## Time Field

```ls
Value = 2017
Format & Zone = yyyy
```

## Data Commands

```ls
series e:mvpx-bvin d:2017-01-01T00:00:00.000Z t:month=Mar m:animals_spayed_neutered=0

series e:mvpx-bvin d:2017-01-01T00:00:00.000Z t:month=Apr m:animals_spayed_neutered=0

series e:mvpx-bvin d:2017-01-01T00:00:00.000Z t:month=May m:animals_spayed_neutered=0
```

## Meta Commands

```ls
metric m:animals_spayed_neutered p:integer l:"Animals Spayed/Neutered" t:dataTypeName=number

entity e:mvpx-bvin l:"Pet Data - 2017 Spay/Neuter Surgeries" t:url=https://data.kingcounty.gov/api/views/mvpx-bvin

property e:mvpx-bvin t:meta.view v:id=mvpx-bvin v:averageRating=0 v:name="Pet Data - 2017 Spay/Neuter Surgeries"

property e:mvpx-bvin t:meta.view.owner v:id=ph9f-eu4i v:screenName=Cameron v:displayName=Cameron

property e:mvpx-bvin t:meta.view.tableauthor v:id=ph9f-eu4i v:screenName=Cameron v:roleName=publisher v:displayName=Cameron
```

## Top Records

```ls
| month | animals_spayed_neutered | 
| ===== | ======================= | 
| Mar   | 0                       | 
| Apr   | 0                       | 
| May   | 0                       | 
| Jun   | 0                       | 
| Jul   | 0                       | 
| Aug   | 0                       | 
| Sep   | 0                       | 
| Oct   | 0                       | 
| Nov   | 0                       | 
| Dec   | 0                       | 
```