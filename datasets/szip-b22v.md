# Statewide Hatchery Rollup

## Dataset

* [Dataset URL](https://data.wa.gov/api/views/szip-b22v/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/statewide-hatchery-rollup-cbaab)
* [Metadata URL](https://data.wa.gov/api/views/szip-b22v)
* Id = szip-b22v
* Name = Statewide Hatchery Rollup
* Created = 2012-12-05T01:33:47Z
* Publication Date = 2012-12-05T02:57:46Z
* Rows Updated = 2012-12-05T02:57:37Z

## Description



## Columns

```ls
| Name                | Field Name    | Data Type | Render Type | Schema Type | Included | 
| =================== | ============= | ========= | =========== | =========== | ======== | 
| updated_at          | :updated_at   | meta_data | meta_data   | time        | No       | 
| WDFW Programs . . . | wdfw_programs | text      | text        | series tag  | Yes      | 
| 1998                | _1            | number    | number      |             | No       | 
| 2008                | _2            | number    | number      |             | No       | 
| 2010                | _3            | number    | number      |             | No       | 
| 2011                | _4            | number    | number      |             | No       | 
| 2012                | _5            | number    | number      |             | No       | 
| 2013                | _6            | number    | number      |             | No       | 
| 2014                | _7            | number    | number      |             | No       | 
| 2015                | _8            | number    | number      |             | No       | 
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = _7,_8,_3,_4,_5,_6,_1,_2
Annotation Fields = 
```

## Data Commands

```ls





```

## Meta Commands

```ls
entity e:szip-b22v l:"Statewide Hatchery Rollup" t:url=https://data.wa.gov/api/views/szip-b22v

property e:szip-b22v t:meta.view d:2017-03-07T17:51:02.389Z v:id=szip-b22v v:averageRating=0 v:name="Statewide Hatchery Rollup"

property e:szip-b22v t:meta.view.owner d:2017-03-07T17:51:02.389Z v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:roleName=publisher v:displayName="Jennifer Johnson"

property e:szip-b22v t:meta.view.tableauthor d:2017-03-07T17:51:02.389Z v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:roleName=publisher v:displayName="Jennifer Johnson"
```