# IDHS MAY 2011 TANF BY COUNTY

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idhs-may-2011-tanf-by-county-0f328) |
| Metadata | [Link](https://data.illinois.gov/api/views/x7xu-qyvz) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/x7xu-qyvz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/x7xu-qyvz/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | x7xu-qyvz |
| Name | IDHS MAY 2011 TANF BY COUNTY |
| Category | Social/Healthcare |
| Created | 2011-11-03T13:14:20Z |
| Publication Date | 2011-11-03T13:16:37Z |

## Description

MAY 2011 TANF BY COUNTY

## Columns

```ls
| Included | Schema Type    | Field Name  | Name        | Data Type | Render Type |
| ======== | ============== | =========== | =========== | ========= | =========== |
| Yes      | numeric metric | county_nr   | COUNTY NR   | number    | number      |
| Yes      | series tag     | county_name | COUNTY NAME | text      | text        |
| Yes      | numeric metric | cases       | CASES       | number    | number      |
| Yes      | numeric metric | persons     | PERSONS     | number    | number      |
```

## Time Field

```ls
Value = 2011
Format & Zone = yyyy
```

## Data Commands

```ls
series e:x7xu-qyvz d:2011-01-01T00:00:00.000Z t:county_name=Adams m:county_nr=10 m:cases=168 m:persons=376

series e:x7xu-qyvz d:2011-01-01T00:00:00.000Z t:county_name=Alexander m:county_nr=11 m:cases=205 m:persons=519

series e:x7xu-qyvz d:2011-01-01T00:00:00.000Z t:county_name=Bond m:county_nr=12 m:cases=71 m:persons=185
```

## Meta Commands

```ls
metric m:county_nr p:integer l:"COUNTY NR" t:dataTypeName=number

metric m:cases p:integer l:CASES t:dataTypeName=number

metric m:persons p:integer l:PERSONS t:dataTypeName=number

entity e:x7xu-qyvz l:"IDHS MAY 2011 TANF BY COUNTY" t:url=https://data.illinois.gov/api/views/x7xu-qyvz

property e:x7xu-qyvz t:meta.view v:id=x7xu-qyvz v:category=Social/Healthcare v:averageRating=0 v:name="IDHS MAY 2011 TANF BY COUNTY"

property e:x7xu-qyvz t:meta.view.owner v:id=e9y5-49nr v:screenName="Carl Awe" v:displayName="Carl Awe"

property e:x7xu-qyvz t:meta.view.tableauthor v:id=e9y5-49nr v:screenName="Carl Awe" v:displayName="Carl Awe"
```

## Top Records

```ls
| county_nr | county_name | cases | persons | 
| ========= | =========== | ===== | ======= | 
| 10        | Adams       | 168   | 376     | 
| 11        | Alexander   | 205   | 519     | 
| 12        | Bond        | 71    | 185     | 
| 13        | Boone       | 35    | 87      | 
| 15        | Bureau      | 43    | 92      | 
| 17        | Carroll     | 27    | 60      | 
| 18        | Cass        | 18    | 33      | 
| 19        | Champaign   | 681   | 1868    | 
| 20        | Christian   | 121   | 288     | 
| 22        | Clay        | 31    | 56      | 
```