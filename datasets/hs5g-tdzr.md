# IDPH Marriages, by County, 2000-2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idph-marriages-by-county-2000-2009-dedc9) |
| Metadata | [Link](https://data.illinois.gov/api/views/hs5g-tdzr) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/hs5g-tdzr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/hs5g-tdzr/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | hs5g-tdzr |
| Name | IDPH Marriages, by County, 2000-2009 |
| Attribution | Illinois Center for Health Statistics |
| Category | Public Health |
| Tags | marriage |
| Created | 2012-01-18T21:35:00Z |
| Publication Date | 2012-01-23T21:26:10Z |
| Rows Updated | 2012-01-18T21:36:56Z |

## Columns

```ls
| Included | Schema Type    | Field Name | Name   | Data Type | Render Type |
| ======== | ============== | ========== | ====== | ========= | =========== |
| Yes      | series tag     | county     | County | text      | text        |
| No       |                | _1         | 2000   | number    | number      |
| No       |                | _2         | 2001   | number    | number      |
| No       |                | _3         | 2002   | number    | number      |
| No       |                | _4         | 2003   | number    | number      |
| No       |                | _5         | 2004   | number    | number      |
| No       |                | _6         | 2005   | number    | number      |
| No       |                | _7         | 2006   | number    | number      |
| No       |                | _8         | 2007   | number    | number      |
| No       |                | _9         | 2008   | number    | number      |
| Yes      | numeric metric | _10        | 2009   | number    | number      |
```

## Time Field

```ls
Value = 
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = _1,_2,_3,_4,_5,_6,_7,_8,_9
```

## Data Commands

```ls
series e:hs5g-tdzr d:2000-01-01T00:00:00.000Z t:county=Adams m:_10=503

series e:hs5g-tdzr d:2000-01-01T00:00:00.000Z t:county=Alexander m:_10=44

series e:hs5g-tdzr d:2000-01-01T00:00:00.000Z t:county=Bond m:_10=103
```

## Meta Commands

```ls
metric m:_10 p:integer l:2009 t:dataTypeName=number

entity e:hs5g-tdzr l:"IDPH Marriages, by County, 2000-2009" t:attribution="Illinois Center for Health Statistics" t:url=https://data.illinois.gov/api/views/hs5g-tdzr

property e:hs5g-tdzr t:meta.view v:id=hs5g-tdzr v:category="Public Health" v:attributionLink=http://www.idph.state.il.us/health/statshome.htm v:averageRating=0 v:name="IDPH Marriages, by County, 2000-2009" v:attribution="Illinois Center for Health Statistics"

property e:hs5g-tdzr t:meta.view.owner v:id=vice-rsdw v:profileImageUrlMedium=/api/users/vice-rsdw/profile_images/THUMB v:profileImageUrlLarge=/api/users/vice-rsdw/profile_images/LARGE v:screenName="IDPH Staff" v:profileImageUrlSmall=/api/users/vice-rsdw/profile_images/TINY v:roleName=publisher v:displayName="IDPH Staff"

property e:hs5g-tdzr t:meta.view.tableauthor v:id=vice-rsdw v:profileImageUrlMedium=/api/users/vice-rsdw/profile_images/THUMB v:profileImageUrlLarge=/api/users/vice-rsdw/profile_images/LARGE v:screenName="IDPH Staff" v:profileImageUrlSmall=/api/users/vice-rsdw/profile_images/TINY v:roleName=publisher v:displayName="IDPH Staff"
```