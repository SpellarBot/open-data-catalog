# Vashon average ridership by run (dataset)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/vashon-average-ridership-by-run-dataset-2a5bc) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/p4h2-xhh2) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/p4h2-xhh2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/p4h2-xhh2/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | p4h2-xhh2 |
| Name | Vashon average ridership by run (dataset) |
| Attribution | King County Ferry District |
| Category | Transportation |
| Tags | vashon, passenger, ferry |
| Created | 2012-06-18T23:54:56Z |
| Publication Date | 2013-11-15T00:59:55Z |

## Description

King County Ferry District, Vashon Island, average number of passengers per commuter sailing for last month

## Columns

```ls
| Included | Schema Type | Field Name  | Name                        | Data Type | Render Type |
| ======== | =========== | =========== | =========================== | ========= | =========== |
| No       | time        | :updated_at | updated_at                  | meta_data | meta_data   |
| Yes      | series tag  | run         | Run                         | text      | text        |
| No       |             | _1          | 6:10 a.m. Vashon to Seattle | number    | number      |
| No       |             | _2          | 7:10 a.m. Vashon to Seattle | number    | number      |
| No       |             | _3          | 8:15 a.m. Vashon to Seattle | number    | number      |
| No       |             | _4          | 4:30 p.m. Seattle to Vashon | number    | number      |
| No       |             | _5          | 5:30 p.m. Seattle to Vashon | number    | number      |
| No       |             | _6          | 6:30 p.m. Seattle to Vashon | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = _1,_2,_3,_4,_5,_6
```

## Data Commands

```ls
series e:p4h2-xhh2 d:2013-11-14T16:59:40.000Z t:run=Monday m:row_number.p4h2-xhh2=1

series e:p4h2-xhh2 d:2013-11-14T16:59:42.000Z t:run=Tuesday m:row_number.p4h2-xhh2=2

series e:p4h2-xhh2 d:2013-11-14T16:59:46.000Z t:run=Wednesday m:row_number.p4h2-xhh2=3
```

## Meta Commands

```ls
metric m:row_number.p4h2-xhh2 p:long l:"Row Number"

entity e:p4h2-xhh2 l:"Vashon average ridership by run (dataset)" t:attribution="King County Ferry District" t:url=https://data.kingcounty.gov/api/views/p4h2-xhh2

property e:p4h2-xhh2 t:meta.view v:id=p4h2-xhh2 v:category=Transportation v:attributionLink=http://www.kingcounty.gov/transportation/kcdot/WaterTaxi.aspx v:averageRating=0 v:name="Vashon average ridership by run (dataset)" v:attribution="King County Ferry District"

property e:p4h2-xhh2 t:meta.view.license v:name="Public Domain"

property e:p4h2-xhh2 t:meta.view.owner v:id=2gzv-6b6z v:profileImageUrlMedium=/api/users/2gzv-6b6z/profile_images/THUMB v:profileImageUrlLarge=/api/users/2gzv-6b6z/profile_images/LARGE v:screenName="King County Webteam" v:profileImageUrlSmall=/api/users/2gzv-6b6z/profile_images/TINY v:displayName="King County Webteam"

property e:p4h2-xhh2 t:meta.view.tableauthor v:id=2gzv-6b6z v:profileImageUrlMedium=/api/users/2gzv-6b6z/profile_images/THUMB v:profileImageUrlLarge=/api/users/2gzv-6b6z/profile_images/LARGE v:screenName="King County Webteam" v:profileImageUrlSmall=/api/users/2gzv-6b6z/profile_images/TINY v:roleName=administrator v:displayName="King County Webteam"
```

## Top Records

```ls
| :updated_at | run       | _1 | _2  | _3  | _4  | _5  | _6  | 
| =========== | ========= | == | === | === | === | === | === | 
| 1384448380  | Monday    | 76 | 133 | 141 | 163 | 161 | 101 | 
| 1384448382  | Tuesday   | 83 | 130 | 145 | 164 | 158 | 112 | 
| 1384448386  | Wednesday | 79 | 138 | 142 | 147 | 169 | 115 | 
| 1384448388  | Thursday  | 68 | 122 | 142 | 143 | 144 | 111 | 
| 1384448391  | Friday    | 58 | 102 | 115 | 136 | 118 | 72  | 
```