# Pet Data - 2015 Spay/Neuter Surgeries

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/pet-data-2015-spay-neuter-surgeries) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/yrh9-psxs) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/yrh9-psxs/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/yrh9-psxs/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | yrh9-psxs |
| Name | Pet Data - 2015 Spay/Neuter Surgeries |
| Category | Government |
| Created | 2015-02-06T20:07:29Z |
| Publication Date | 2016-01-06T23:06:11Z |

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type | Render Type |
| ======== | ============== | ======================= | ======================= | ========= | =========== |
| Yes      | series tag     | month                   | Month                   | text      | text        |
| Yes      | numeric metric | animals_spayed_neutered | Animals Spayed/Neutered | number    | number      |
```

## Time Field

```ls
Value = 2015
Format & Zone = yyyy
```

## Data Commands

```ls
series e:yrh9-psxs d:2015-01-01T00:00:00.000Z t:month=Jan m:animals_spayed_neutered=96

series e:yrh9-psxs d:2015-01-01T00:00:00.000Z t:month=Feb m:animals_spayed_neutered=90

series e:yrh9-psxs d:2015-01-01T00:00:00.000Z t:month=Mar m:animals_spayed_neutered=82
```

## Meta Commands

```ls
metric m:animals_spayed_neutered p:integer l:"Animals Spayed/Neutered" t:dataTypeName=number

entity e:yrh9-psxs l:"Pet Data - 2015 Spay/Neuter Surgeries" t:url=https://data.kingcounty.gov/api/views/yrh9-psxs

property e:yrh9-psxs t:meta.view v:id=yrh9-psxs v:category=Government v:averageRating=0 v:name="Pet Data - 2015 Spay/Neuter Surgeries"

property e:yrh9-psxs t:meta.view.owner v:id=ph9f-eu4i v:screenName=Cameron v:displayName=Cameron

property e:yrh9-psxs t:meta.view.tableauthor v:id=ph9f-eu4i v:screenName=Cameron v:roleName=publisher v:displayName=Cameron
```

## Top Records

```ls
| month | animals_spayed_neutered | 
| ===== | ======================= | 
| Jan   | 96                      | 
| Feb   | 90                      | 
| Mar   | 82                      | 
| Apr   | 82                      | 
| May   | 103                     | 
| Jun   | 194                     | 
| Jul   | 280                     | 
| Aug   | 245                     | 
| Sep   | 285                     | 
| Oct   | 259                     | 
```