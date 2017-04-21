# Regions -- Hatchery Standards 2014 SOS

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/regions-hatchery-standards-2014-sos-cc63d) |
| Metadata | [Link](https://data.wa.gov/api/views/kju2-r99e) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/kju2-r99e/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/kju2-r99e/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | kju2-r99e |
| Name | Regions -- Hatchery Standards 2014 SOS |
| Created | 2014-09-10T22:47:35Z |
| Publication Date | 2014-09-10T22:49:00Z |

## Columns

```ls
| Included | Schema Type    | Field Name | Name    | Data Type | Render Type |
| ======== | ============== | ========== | ======= | ========= | =========== |
| Yes      | series tag     | region     | Region  | text      | text        |
| Yes      | series tag     | species    | Species | text      | text        |
| Yes      | numeric metric | 2010       | 2010    | percent   | percent     |
| Yes      | numeric metric | 2012       | 2012    | percent   | percent     |
| Yes      | numeric metric | 2014       | 2014    | percent   | percent     |
```

## Time Field

```ls
Value = 2014
Format & Zone = yyyy
```

## Data Commands

```ls
series e:kju2-r99e d:2014-01-01T00:00:00.000Z t:region=Snake t:species=Chinook m:2012=0 m:2010=0

series e:kju2-r99e d:2014-01-01T00:00:00.000Z t:region=Snake t:species=Steelhead m:2012=33 m:2010=33

series e:kju2-r99e d:2014-01-01T00:00:00.000Z t:region="Upper Columbia" t:species=Chinook m:2012=60 m:2010=50
```

## Meta Commands

```ls
metric m:2010 p:integer l:2010 t:dataTypeName=percent

metric m:2012 p:integer l:2012 t:dataTypeName=percent

metric m:2014 p:integer l:2014 t:dataTypeName=percent

entity e:kju2-r99e l:"Regions -- Hatchery Standards 2014 SOS" t:url=https://data.wa.gov/api/views/kju2-r99e

property e:kju2-r99e t:meta.view v:id=kju2-r99e v:averageRating=0 v:name="Regions -- Hatchery Standards 2014 SOS"

property e:kju2-r99e t:meta.view.owner v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:displayName="Jennifer Johnson"

property e:kju2-r99e t:meta.view.tableauthor v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:roleName=publisher v:displayName="Jennifer Johnson"
```

## Top Records

```ls
| region          | species   | 2010 | 2012 | 2014 | 
| =============== | ========= | ==== | ==== | ==== | 
| Snake           | Chinook   | 0    | 0    |      | 
| Snake           | Steelhead | 33   | 33   |      | 
| Upper Columbia  | Chinook   | 50   | 60   |      | 
| Upper Columbia  | Steelhead | 50   | 75   |      | 
| Upper Columbia  | Sockeye   | 0    | 100  |      | 
| Middle Columbia | Chinook   | 0    | 0    |      | 
| Middle Columbia | Steelhead | 33   | 100  |      | 
| Puget Sound     | Chinook   | 44   | 68   | 74   | 
| Puget Sound     | Steelhead | 21   | 29   | 92   | 
| Puget Sound     | Coho      | 78   | 100  | 92   | 
```