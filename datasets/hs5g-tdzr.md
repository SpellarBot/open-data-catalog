# IDPH Marriages, by County, 2000-2009

## Dataset

* [Dataset URL](https://data.illinois.gov/api/views/hs5g-tdzr/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/idph-marriages-by-county-2000-2009-dedc9)
* [Metadata URL](https://data.illinois.gov/api/views/hs5g-tdzr)
* Id = hs5g-tdzr
* Name = IDPH Marriages, by County, 2000-2009
* Attribution = Illinois Center for Health Statistics
* [Attribution Link](http://www.idph.state.il.us/health/statshome.htm)
* Category = Public Health
* Tags = [marriage]
* Created = 2012-01-18T21:35:00Z
* Publication Date = 2012-01-23T21:26:10Z
* Rows Updated = 2012-01-18T21:36:56Z

## Description



## Columns

```ls
| Name       | Field Name  | Data Type | Render Type | Schema Type    | Included | 
| ========== | =========== | ========= | =========== | ============== | ======== | 
| updated_at | :updated_at | meta_data | meta_data   | time           | No       | 
| County     | county      | text      | text        | series tag     | Yes      | 
| 2000       | _1          | number    | number      |                | No       | 
| 2001       | _2          | number    | number      |                | No       | 
| 2002       | _3          | number    | number      |                | No       | 
| 2003       | _4          | number    | number      |                | No       | 
| 2004       | _5          | number    | number      |                | No       | 
| 2005       | _6          | number    | number      |                | No       | 
| 2006       | _7          | number    | number      |                | No       | 
| 2007       | _8          | number    | number      |                | No       | 
| 2008       | _9          | number    | number      |                | No       | 
| 2009       | _10         | number    | number      | numeric metric | Yes      | 
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
Excluded Fields = _7,_8,_9,_3,_4,_5,_6,_1,_2
Annotation Fields = 
```

## Data Commands

```ls
series e:hs5g-tdzr d:2012-01-18T13:35:11.000Z t:county=Adams m:_10=503

series e:hs5g-tdzr d:2012-01-18T13:35:11.000Z t:county=Alexander m:_10=44

series e:hs5g-tdzr d:2012-01-18T13:35:11.000Z t:county=Bond m:_10=103
```

## Meta Commands

```ls
metric m:_10 p:integer l:2009 t:dataTypeName=number

entity e:hs5g-tdzr l:"IDPH Marriages, by County, 2000-2009" t:attribution="Illinois Center for Health Statistics" t:url=https://data.illinois.gov/api/views/hs5g-tdzr

property e:hs5g-tdzr t:meta.view d:2017-03-07T16:40:44.174Z v:id=hs5g-tdzr v:category="Public Health" v:attributionLink=http://www.idph.state.il.us/health/statshome.htm v:averageRating=0 v:name="IDPH Marriages, by County, 2000-2009" v:attribution="Illinois Center for Health Statistics"

property e:hs5g-tdzr t:meta.view.owner d:2017-03-07T16:40:44.174Z v:id=vice-rsdw v:profileImageUrlMedium=/api/users/vice-rsdw/profile_images/THUMB v:profileImageUrlLarge=/api/users/vice-rsdw/profile_images/LARGE v:screenName="IDPH Staff" v:profileImageUrlSmall=/api/users/vice-rsdw/profile_images/TINY v:roleName=publisher v:displayName="IDPH Staff"

property e:hs5g-tdzr t:meta.view.tableauthor d:2017-03-07T16:40:44.174Z v:id=vice-rsdw v:profileImageUrlMedium=/api/users/vice-rsdw/profile_images/THUMB v:profileImageUrlLarge=/api/users/vice-rsdw/profile_images/LARGE v:screenName="IDPH Staff" v:profileImageUrlSmall=/api/users/vice-rsdw/profile_images/TINY v:roleName=publisher v:displayName="IDPH Staff"
```