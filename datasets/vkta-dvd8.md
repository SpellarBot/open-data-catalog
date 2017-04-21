# Pet Data - 2014 Spay/Neuter Surgeries

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/pet-data-2014-spay-neuter-surgeries-9fb42) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/vkta-dvd8) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/vkta-dvd8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/vkta-dvd8/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | vkta-dvd8 |
| Name | Pet Data - 2014 Spay/Neuter Surgeries |
| Created | 2014-03-26T16:22:01Z |
| Publication Date | 2015-01-12T16:37:43Z |

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type | Render Type |
| ======== | ============== | ======================= | ======================= | ========= | =========== |
| Yes      | series tag     | month                   | Month                   | text      | text        |
| Yes      | numeric metric | animals_spayed_neutered | Animals Spayed/Neutered | number    | number      |
```

## Time Field

```ls
Value = 2014
Format & Zone = yyyy
```

## Data Commands

```ls
series e:vkta-dvd8 d:2014-01-01T00:00:00.000Z t:month=May m:animals_spayed_neutered=126

series e:vkta-dvd8 d:2014-01-01T00:00:00.000Z t:month=Jan m:animals_spayed_neutered=131

series e:vkta-dvd8 d:2014-01-01T00:00:00.000Z t:month=Feb m:animals_spayed_neutered=80
```

## Meta Commands

```ls
metric m:animals_spayed_neutered p:integer l:"Animals Spayed/Neutered" t:dataTypeName=number

entity e:vkta-dvd8 l:"Pet Data - 2014 Spay/Neuter Surgeries" t:url=https://data.kingcounty.gov/api/views/vkta-dvd8

property e:vkta-dvd8 t:meta.view v:id=vkta-dvd8 v:averageRating=0 v:name="Pet Data - 2014 Spay/Neuter Surgeries"

property e:vkta-dvd8 t:meta.view.license v:name="Public Domain"

property e:vkta-dvd8 t:meta.view.owner v:id=ph9f-eu4i v:screenName=Cameron v:displayName=Cameron

property e:vkta-dvd8 t:meta.view.tableauthor v:id=ph9f-eu4i v:screenName=Cameron v:roleName=publisher v:displayName=Cameron
```

## Top Records

```ls
| month | animals_spayed_neutered | 
| ===== | ======================= | 
| May   | 126                     | 
| Jan   | 131                     | 
| Feb   | 80                      | 
| Mar   | 79                      | 
| Apr   | 68                      | 
| Jun   | 152                     | 
| Jul   | 209                     | 
| Aug   | 192                     | 
| Sep   | 220                     | 
| Oct   | 203                     | 
```