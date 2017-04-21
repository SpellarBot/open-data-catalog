# Regions -- Hatchery Standards 2016 SOS 10-18-2016

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/regions-hatchery-standards-2014-sos-12142014-320b5) |
| Metadata | [Link](https://data.wa.gov/api/views/xms2-7pwe) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/xms2-7pwe/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/xms2-7pwe/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | xms2-7pwe |
| Name | Regions -- Hatchery Standards 2016 SOS 10-18-2016 |
| Created | 2014-12-15T12:47:53Z |
| Publication Date | 2016-10-18T19:39:30Z |

## Columns

```ls
| Included | Schema Type    | Field Name | Name    | Data Type | Render Type |
| ======== | ============== | ========== | ======= | ========= | =========== |
| Yes      | series tag     | region     | Region  | text      | text        |
| Yes      | series tag     | species    | Species | text      | text        |
| Yes      | numeric metric | 2010       | 2010    | number    | number      |
| Yes      | numeric metric | 2012       | 2012    | number    | number      |
| Yes      | numeric metric | 2014       | 2014    | number    | number      |
| Yes      | numeric metric | 2016       | 2016    | number    | number      |
```

## Time Field

```ls
Value = 2016
Format & Zone = yyyy
```

## Data Commands

```ls
series e:xms2-7pwe d:2016-01-01T00:00:00.000Z t:region="Hood Canal" t:species="Summer Chum" m:2014=100 m:2016=100 m:2012=100 m:2010=100

series e:xms2-7pwe d:2016-01-01T00:00:00.000Z t:region="Lower Columbia" t:species=Chinook m:2014=80 m:2016=91 m:2012=50 m:2010=56

series e:xms2-7pwe d:2016-01-01T00:00:00.000Z t:region="Lower Columbia" t:species=Chum m:2014=100 m:2016=100 m:2012=100 m:2010=50
```

## Meta Commands

```ls
metric m:2010 p:integer l:2010 t:dataTypeName=number

metric m:2012 p:integer l:2012 t:dataTypeName=number

metric m:2014 p:integer l:2014 t:dataTypeName=number

metric m:2016 p:integer l:2016 t:dataTypeName=number

entity e:xms2-7pwe l:"Regions -- Hatchery Standards 2016 SOS 10-18-2016" t:url=https://data.wa.gov/api/views/xms2-7pwe

property e:xms2-7pwe t:meta.view v:id=xms2-7pwe v:averageRating=0 v:name="Regions -- Hatchery Standards 2016 SOS 10-18-2016"

property e:xms2-7pwe t:meta.view.owner v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:displayName="Jennifer Johnson"

property e:xms2-7pwe t:meta.view.tableauthor v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:roleName=publisher v:displayName="Jennifer Johnson"
```

## Top Records

```ls
| region          | species     | 2010 | 2012 | 2014 | 2016 | 
| =============== | =========== | ==== | ==== | ==== | ==== | 
| Hood Canal      | Summer Chum | 100  | 100  | 100  | 100  | 
| Lower Columbia  | Chinook     | 56   | 50   | 80   | 91   | 
| Lower Columbia  | Chum        | 50   | 100  | 100  | 100  | 
| Lower Columbia  | Coho        | 58   | 64   | 73   | 92   | 
| Lower Columbia  | Steelhead   | 79   | 86   | 94   | 94   | 
| Middle Columbia | Chinook     | 0    | 0    | 0    | 0    | 
| Middle Columbia | Steelhead   | 33   | 100  | 100  | 100  | 
| Puget Sound     | Chinook     | 44   | 68   | 74   | 94   | 
| Puget Sound     | Coho        | 78   | 100  | 92   | 100  | 
| Puget Sound     | Fall Chum   | 0    | 50   | 50   | 50   | 
```