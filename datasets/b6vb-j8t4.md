# Statewide RPI-2

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/statewide-rpi-2-a601c) |
| Metadata | [Link](https://data.wa.gov/api/views/b6vb-j8t4) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/b6vb-j8t4/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/b6vb-j8t4/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | b6vb-j8t4 |
| Name | Statewide RPI-2 |
| Created | 2012-12-26T05:49:19Z |
| Publication Date | 2012-12-26T05:49:39Z |

## Columns

```ls
| Included | Schema Type | Field Name  | Name       | Data Type | Render Type |
| ======== | =========== | =========== | ========== | ========= | =========== |
| No       | time        | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag  | which_h     | Which H?   | text      | text        |
| No       |             | _1          | 2008       | number    | number      |
| No       |             | _2          | 2010       | number    | number      |
| No       |             | _3          | 2012       | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = _1,_2,_3
```

## Data Commands

```ls
series e:b6vb-j8t4 d:2012-12-25T21:49:20.000Z t:which_h=Habitat m:row_number.b6vb-j8t4=1

series e:b6vb-j8t4 d:2012-12-25T21:49:20.000Z t:which_h=Hatchery m:row_number.b6vb-j8t4=2

series e:b6vb-j8t4 d:2012-12-25T21:49:20.000Z t:which_h=Harvest m:row_number.b6vb-j8t4=3
```

## Meta Commands

```ls
metric m:row_number.b6vb-j8t4 p:long l:"Row Number"

entity e:b6vb-j8t4 l:"Statewide RPI-2" t:url=https://data.wa.gov/api/views/b6vb-j8t4

property e:b6vb-j8t4 t:meta.view v:id=b6vb-j8t4 v:averageRating=0 v:name="Statewide RPI-2"

property e:b6vb-j8t4 t:meta.view.owner v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:displayName="Jennifer Johnson"

property e:b6vb-j8t4 t:meta.view.tableauthor v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:roleName=publisher v:displayName="Jennifer Johnson"
```

## Top Records

```ls
| :updated_at | which_h    | _1 | _2 | _3 | 
| =========== | ========== | == | == | == | 
| 1356472160  | Habitat    | 16 | 24 | 31 | 
| 1356472160  | Hatchery   | 52 | 55 | 70 | 
| 1356472160  | Harvest    | 73 | 75 | 52 | 
| 1356472160  | Hydropower | 56 | 52 | 67 | 
```