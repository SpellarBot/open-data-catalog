# Coffee with the Sallys Map

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/coffee-with-the-sallys-map-02359) |
| Metadata | [Link](https://data.seattle.gov/api/views/kdjv-k5qf) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/kdjv-k5qf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/kdjv-k5qf/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | kdjv-k5qf |
| Name | Coffee with the Sallys Map |
| Category | Community |
| Tags | sally clark, sally bagshaw, seattle city council, coffee with the sallys |
| Created | 2013-09-25T17:28:28Z |
| Publication Date | 2015-02-24T21:35:08Z |

## Description

Grab a coffee and join Seattle City Councilmember Sally Bagshaw and Seattle City Council President Sally Clark for conversation and caffeine out in your neighborhood.

## Columns

```ls
| Included | Schema Type | Field Name  | Name                  | Data Type | Render Type |
| ======== | =========== | =========== | ===================== | ========= | =========== |
| No       | time        | :updated_at | updated_at            | meta_data | meta_data   |
| Yes      | series tag  | common_name | Neighborhood Location | text      | text        |
| Yes      | series tag  | icon        | Icon                  | photo     | photo       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:kdjv-k5qf d:2013-09-25T12:07:02.000Z t:icon=b8A8KWV-0VnKTuNP1xsrlk0ySPnigt8p6hMLrQZFMjk t:common_name=Pinehurst m:row_number.kdjv-k5qf=1

series e:kdjv-k5qf d:2013-09-25T12:07:14.000Z t:icon=b8A8KWV-0VnKTuNP1xsrlk0ySPnigt8p6hMLrQZFMjk t:common_name="Madison Valley" m:row_number.kdjv-k5qf=2

series e:kdjv-k5qf d:2013-09-25T12:07:59.000Z t:icon=b8A8KWV-0VnKTuNP1xsrlk0ySPnigt8p6hMLrQZFMjk t:common_name="Caf? Racer" m:row_number.kdjv-k5qf=3
```

## Meta Commands

```ls
metric m:row_number.kdjv-k5qf p:long l:"Row Number"

entity e:kdjv-k5qf l:"Coffee with the Sallys Map" t:url=https://data.seattle.gov/api/views/kdjv-k5qf

property e:kdjv-k5qf t:meta.view v:id=kdjv-k5qf v:category=Community v:averageRating=0 v:name="Coffee with the Sallys Map"

property e:kdjv-k5qf t:meta.view.license v:name="Public Domain"

property e:kdjv-k5qf t:meta.view.owner v:id=gpag-9aag v:screenName="Peha, Joseph" v:displayName="Peha, Joseph"

property e:kdjv-k5qf t:meta.view.tableauthor v:id=gpag-9aag v:screenName="Peha, Joseph" v:roleName=publisher v:displayName="Peha, Joseph"
```

## Top Records

```ls
| :updated_at | common_name                 | icon                                        | 
| =========== | =========================== | =========================================== | 
| 1380110822  | Pinehurst                   | b8A8KWV-0VnKTuNP1xsrlk0ySPnigt8p6hMLrQZFMjk | 
| 1380110834  | Madison Valley              | b8A8KWV-0VnKTuNP1xsrlk0ySPnigt8p6hMLrQZFMjk | 
| 1380110879  | Caf? Racer                  | b8A8KWV-0VnKTuNP1xsrlk0ySPnigt8p6hMLrQZFMjk | 
| 1380110909  | Bitter Lake                 | b8A8KWV-0VnKTuNP1xsrlk0ySPnigt8p6hMLrQZFMjk | 
| 1380110917  | Othello                     | b8A8KWV-0VnKTuNP1xsrlk0ySPnigt8p6hMLrQZFMjk | 
| 1380110925  | Dravus                      | b8A8KWV-0VnKTuNP1xsrlk0ySPnigt8p6hMLrQZFMjk | 
| 1380110933  | West Seattle Farmers Market | b8A8KWV-0VnKTuNP1xsrlk0ySPnigt8p6hMLrQZFMjk | 
| 1380110941  | U-District                  | b8A8KWV-0VnKTuNP1xsrlk0ySPnigt8p6hMLrQZFMjk | 
| 1380111340  | First Hill                  | b8A8KWV-0VnKTuNP1xsrlk0ySPnigt8p6hMLrQZFMjk | 
| 1389688334  | High Point                  | b8A8KWV-0VnKTuNP1xsrlk0ySPnigt8p6hMLrQZFMjk | 
```