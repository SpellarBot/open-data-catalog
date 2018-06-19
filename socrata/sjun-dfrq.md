# Pet Data - 2016 Pet Adoptions

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/pet-data-2016-pet-adoptions) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/sjun-dfrq) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/sjun-dfrq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/sjun-dfrq/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | sjun-dfrq |
| Name | Pet Data - 2016 Pet Adoptions |
| Attribution | King County |
| Category | Pets |
| Created | 2015-12-11T16:12:06Z |
| Publication Date | 2017-01-18T16:44:42Z |

## Columns

```ls
| Included | Schema Type    | Field Name   | Name         | Data Type | Render Type |
| ======== | ============== | ============ | ============ | ========= | =========== |
| Yes      | series tag     | month        | Month        | text      | text        |
| Yes      | numeric metric | pets_adopted | Pets Adopted | number    | number      |
```

## Time Field

```ls
Value = 2016
Format & Zone = yyyy
```

## Data Commands

```ls
series e:sjun-dfrq d:2016-01-01T00:00:00.000Z t:month=Jan m:pets_adopted=129

series e:sjun-dfrq d:2016-01-01T00:00:00.000Z t:month=Mar m:pets_adopted=126

series e:sjun-dfrq d:2016-01-01T00:00:00.000Z t:month=Feb m:pets_adopted=151
```

## Meta Commands

```ls
metric m:pets_adopted p:integer l:"Pets Adopted" t:dataTypeName=number

entity e:sjun-dfrq l:"Pet Data - 2016 Pet Adoptions" t:attribution="King County" t:url=https://data.kingcounty.gov/api/views/sjun-dfrq

property e:sjun-dfrq t:meta.view v:id=sjun-dfrq v:category=Pets v:attributionLink=http://www.kingcounty.gov v:averageRating=0 v:name="Pet Data - 2016 Pet Adoptions" v:attribution="King County"

property e:sjun-dfrq t:meta.view.license v:name="Public Domain"

property e:sjun-dfrq t:meta.view.owner v:id=ph9f-eu4i v:screenName=Cameron v:displayName=Cameron

property e:sjun-dfrq t:meta.view.tableauthor v:id=ph9f-eu4i v:screenName=Cameron v:roleName=publisher v:displayName=Cameron
```

## Top Records

```ls
| month | pets_adopted | 
| ===== | ============ | 
| Jan   | 129          | 
| Mar   | 126          | 
| Feb   | 151          | 
| Apr   | 128          | 
| May   | 143          | 
| Jun   | 200          | 
| Jul   | 285          | 
| Aug   | 288          | 
| Sep   | 247          | 
| Oct   | 238          | 
```