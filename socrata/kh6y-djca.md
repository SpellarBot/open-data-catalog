# Pet Data - 2016 Spay/Neuter Surgeries

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/pet-data-2016-spay-neuter-surgeries) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/kh6y-djca) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/kh6y-djca/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/kh6y-djca/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | kh6y-djca |
| Name | Pet Data - 2016 Spay/Neuter Surgeries |
| Attribution | King County |
| Category | Pets |
| Created | 2015-12-11T16:22:15Z |
| Publication Date | 2017-01-18T16:47:40Z |

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type | Render Type |
| ======== | ============== | ======================= | ======================= | ========= | =========== |
| Yes      | series tag     | month                   | Month                   | text      | text        |
| Yes      | numeric metric | animals_spayed_neutered | Animals Spayed/Neutered | number    | number      |
```

## Time Field

```ls
Value = 2016
Format & Zone = yyyy
```

## Data Commands

```ls
series e:kh6y-djca d:2016-01-01T00:00:00.000Z t:month=Jan m:animals_spayed_neutered=142

series e:kh6y-djca d:2016-01-01T00:00:00.000Z t:month=Mar m:animals_spayed_neutered=162

series e:kh6y-djca d:2016-01-01T00:00:00.000Z t:month=Feb m:animals_spayed_neutered=146
```

## Meta Commands

```ls
metric m:animals_spayed_neutered p:integer l:"Animals Spayed/Neutered" t:dataTypeName=number

entity e:kh6y-djca l:"Pet Data - 2016 Spay/Neuter Surgeries" t:attribution="King County" t:url=https://data.kingcounty.gov/api/views/kh6y-djca

property e:kh6y-djca t:meta.view v:id=kh6y-djca v:category=Pets v:averageRating=0 v:name="Pet Data - 2016 Spay/Neuter Surgeries" v:attribution="King County"

property e:kh6y-djca t:meta.view.license v:name="Public Domain"

property e:kh6y-djca t:meta.view.owner v:id=ph9f-eu4i v:screenName=Cameron v:displayName=Cameron

property e:kh6y-djca t:meta.view.tableauthor v:id=ph9f-eu4i v:screenName=Cameron v:roleName=publisher v:displayName=Cameron
```

## Top Records

```ls
| month | animals_spayed_neutered | 
| ===== | ======================= | 
| Jan   | 142                     | 
| Mar   | 162                     | 
| Feb   | 146                     | 
| Apr   | 174                     | 
| May   | 163                     | 
| Jun   | 250                     | 
| Jul   | 357                     | 
| Aug   | 360                     | 
| Sep   | 259                     | 
| Oct   | 317                     | 
```