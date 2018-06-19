# IDOT Designated Truck Route List

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idot-designated-truck-route-list-63c1b) |
| Metadata | [Link](https://data.illinois.gov/api/views/fe97-gy9p) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/fe97-gy9p/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/fe97-gy9p/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | fe97-gy9p |
| Name | IDOT Designated Truck Route List |
| Attribution | Illinois Department of Transportation |
| Tags | designated, truck |
| Created | 2012-08-24T19:11:45Z |
| Publication Date | 2017-03-09T14:19:04Z |

## Description

Listing of all Designated Truck Routes under the jurisdiction of the State of Illinois Department of Transportation. Class I, II, and III roadways.

## Columns

```ls
| Included | Schema Type | Field Name           | Name       | Data Type | Render Type |
| ======== | =========== | ==================== | ========== | ========= | =========== |
| No       | time        | :updated_at          | updated_at | meta_data | meta_data   |
| Yes      | series tag  | il_rt_255            | Route      | text      | text        |
| Yes      | series tag  | int_270_to_il_rt_143 | Location   | text      | text        |
| No       |             | i                    | Class      | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = i
```

## Data Commands

```ls
series e:fe97-gy9p d:2012-08-24T12:11:46.000Z t:int_270_to_il_rt_143="INT 270 to IL RT 143" t:il_rt_255="IL RT 255" m:row_number.fe97-gy9p=1

series e:fe97-gy9p d:2012-08-24T12:11:46.000Z t:int_270_to_il_rt_143="INT 180(E. JCT.) TO INT 180(W. JCT.)" t:il_rt_255="IL RT 26" m:row_number.fe97-gy9p=2

series e:fe97-gy9p d:2012-08-24T12:11:46.000Z t:int_270_to_il_rt_143="INT 255(S. JCT.) to INT 255(N. JCT.)" t:il_rt_255="IL RT 3" m:row_number.fe97-gy9p=3
```

## Meta Commands

```ls
metric m:row_number.fe97-gy9p p:long l:"Row Number"

entity e:fe97-gy9p l:"IDOT Designated Truck Route List" t:attribution="Illinois Department of Transportation" t:url=https://data.illinois.gov/api/views/fe97-gy9p

property e:fe97-gy9p t:meta.view v:id=fe97-gy9p v:averageRating=0 v:name="IDOT Designated Truck Route List" v:attribution="Illinois Department of Transportation"

property e:fe97-gy9p t:meta.view.owner v:id=ft5i-c5fm v:screenName="Michael Olson" v:displayName="Michael Olson"

property e:fe97-gy9p t:meta.view.tableauthor v:id=ft5i-c5fm v:screenName="Michael Olson" v:roleName=publisher v:displayName="Michael Olson"
```

## Top Records

```ls
| :updated_at | il_rt_255           | int_270_to_il_rt_143                            | i | 
| =========== | =================== | =============================================== | = | 
| 1345810306  | IL RT 255           | INT 270 to IL RT 143                            | I | 
| 1345810306  | IL RT 26            | INT 180(E. JCT.) TO INT 180(W. JCT.)            | I | 
| 1345810306  | IL RT 3             | INT 255(S. JCT.) to INT 255(N. JCT.)            | I | 
| 1345810306  | IL RT 3             | INT 55(S. JCT) to INT 55(N. JCT.)               | I | 
| 1345810306  | IL RT 394           | IL RT 1 to INT 94                               | I | 
| 1345810306  | IL RT 53            | Biesterfield Rd.(ELK GROVE VILLAGE) to IL RT 68 | I | 
| 1345810306  | IL RT 53 (Extender) | IL RT 68 to Lake Cook Rd (LONG GROVE)           | I | 
| 1345810306  | IL RT 56            | INT 88(W. JCT.) to INT 88(E. JCT.)              | I | 
| 1345810306  | IL RT 6             | INT 74 to IL RT 29                              | I | 
| 1345810306  | IL RT 92            | INT 280 to US RT 67                             | I | 
```