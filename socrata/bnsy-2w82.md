# Data.wa.dummy

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/data-wa-dummy-0c2a9) |
| Metadata | [Link](https://data.wa.gov/api/views/bnsy-2w82) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/bnsy-2w82/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/bnsy-2w82/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | bnsy-2w82 |
| Name | Data.wa.dummy |
| Tags | state-of-the-salmon |
| Created | 2014-12-10T20:33:10Z |
| Publication Date | 2014-12-10T20:46:00Z |

## Description

test dummy

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                  | Data Type | Render Type |
| ======== | ============== | =================== | ===================== | ========= | =========== |
| Yes      | series tag     | region              | Region                | text      | text        |
| Yes      | time           | year                | Year                  | number    | number      |
| Yes      | numeric metric | est_acres           | Est Acres             | number    | number      |
| Yes      | numeric metric | est_projects        | # Est Projects        | number    | number      |
| Yes      | numeric metric | rip_acres           | Rip Acres             | number    | number      |
| Yes      | numeric metric | rip_a_projects      | #Rip A Projects       | number    | number      |
| Yes      | numeric metric | rip_miles           | Rip Miles             | number    | number      |
| Yes      | numeric metric | rip_miles_projects  | #Rip Miles Projects   | number    | number      |
| Yes      | numeric metric | miles_strm          | Miles Strm            | number    | number      |
| Yes      | numeric metric | strm_miles_projects | # Strm Miles Projects | number    | number      |
| Yes      | numeric metric | barriers            | Barriers              | number    | number      |
| Yes      | numeric metric | barrier_projects    | # Barrier Projects    | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:bnsy-2w82 d:2000-01-01T00:00:00.000Z t:region=Coast m:barriers=9 m:strm_miles_projects=5 m:rip_miles_projects=0 m:rip_miles=0 m:rip_acres=0 m:est_acres=0.02 m:miles_strm=7.15 m:rip_a_projects=0 m:barrier_projects=5 m:est_projects=1

series e:bnsy-2w82 d:2001-01-01T00:00:00.000Z t:region=Coast m:barriers=0 m:strm_miles_projects=0 m:rip_miles_projects=0 m:rip_miles=0 m:rip_acres=0 m:est_acres=0 m:miles_strm=0 m:rip_a_projects=0 m:barrier_projects=0 m:est_projects=0

series e:bnsy-2w82 d:2002-01-01T00:00:00.000Z t:region=Coast m:barriers=1 m:strm_miles_projects=1 m:rip_miles_projects=0 m:rip_miles=0 m:rip_acres=0 m:est_acres=0 m:miles_strm=1.8 m:rip_a_projects=0 m:barrier_projects=1 m:est_projects=0
```

## Meta Commands

```ls
metric m:est_acres p:double l:"Est Acres" t:dataTypeName=number

metric m:est_projects p:integer l:"# Est Projects" t:dataTypeName=number

metric m:rip_acres p:double l:"Rip Acres" t:dataTypeName=number

metric m:rip_a_projects p:integer l:"#Rip A Projects" t:dataTypeName=number

metric m:rip_miles p:float l:"Rip Miles" t:dataTypeName=number

metric m:rip_miles_projects p:integer l:"#Rip Miles Projects" t:dataTypeName=number

metric m:miles_strm p:float l:"Miles Strm" t:dataTypeName=number

metric m:strm_miles_projects p:integer l:"# Strm Miles Projects" t:dataTypeName=number

metric m:barriers p:integer l:Barriers t:dataTypeName=number

metric m:barrier_projects p:integer l:"# Barrier Projects" t:dataTypeName=number

entity e:bnsy-2w82 l:Data.wa.dummy t:url=https://data.wa.gov/api/views/bnsy-2w82

property e:bnsy-2w82 t:meta.view v:id=bnsy-2w82 v:averageRating=0 v:name=Data.wa.dummy

property e:bnsy-2w82 t:meta.view.owner v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:displayName="Jennifer Johnson"

property e:bnsy-2w82 t:meta.view.tableauthor v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:roleName=publisher v:displayName="Jennifer Johnson"
```

## Top Records

```ls
| region | year | est_acres | est_projects | rip_acres          | rip_a_projects | rip_miles | rip_miles_projects | miles_strm | strm_miles_projects | barriers | barrier_projects | 
| ====== | ==== | ========= | ============ | ================== | ============== | ========= | ================== | ========== | =================== | ======== | ================ | 
| Coast  | 2000 | 0.02      | 1            | 0                  | 0              | 0         | 0                  | 7.15       | 5                   | 9        | 5                | 
| Coast  | 2001 | 0         | 0            | 0                  | 0              | 0         | 0                  | 0          | 0                   | 0        | 0                | 
| Coast  | 2002 | 0         | 0            | 0                  | 0              | 0         | 0                  | 1.8        | 1                   | 1        | 1                | 
| Coast  | 2003 | 0         | 0            | 5.0999999999999996 | 2              | 1.55      | 2                  | 1.75       | 3                   | 3        | 3                | 
| Coast  | 2004 | 0         | 0            | 0.7                | 2              | 0.61      | 2                  | 7.25       | 3                   | 2        | 2                | 
| Coast  | 2005 | 35        | 1            | 0                  | 0              | 0         | 0                  | 19.07      | 6                   | 7        | 6                | 
| Coast  | 2006 | 0         | 0            | 30                 | 1              | 1.57      | 1                  | 17         | 3                   | 6        | 3                | 
| Coast  | 2007 | 0         | 0            | 0                  | 0              | 0         | 0                  | 24.55      | 6                   | 6        | 6                | 
| Coast  | 2008 | 0         | 0            | 0                  | 0              | 0         | 0                  | 4.32       | 3                   | 4        | 2                | 
| Coast  | 2009 | 0         | 0            | 0                  | 0              | 0         | 0                  | 0          | 0                   | 0        | 0                | 
```