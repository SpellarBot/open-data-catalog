# Illinois Tuberculosis Cases By County, 2000-2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/illinois-tuberculosis-cases-by-county-2000-2009-e08cd) |
| Metadata | [Link](https://data.illinois.gov/api/views/mvzj-j8t8) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/mvzj-j8t8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/mvzj-j8t8/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | mvzj-j8t8 |
| Name | Illinois Tuberculosis Cases By County, 2000-2009 |
| Attribution | Illinois Department of Public Health, Office of Health Protection, Division of Infectious Disease, Tuberculosis Control Section |
| Category | Health |
| Tags | health, disease, tuberculosis, tb, infectious disease |
| Created | 2014-08-11T20:32:55Z |
| Publication Date | 2014-08-11T20:34:58Z |

## Description

Data was provided by the Tuberculosis Control Section of the Office of Health Protection's Division of Infectious Diseases.

## Columns

```ls
| Included | Schema Type    | Field Name | Name   | Data Type | Render Type |
| ======== | ============== | ========== | ====== | ========= | =========== |
| Yes      | series tag     | county     | County | text      | text        |
| Yes      | numeric metric | 2000       | 2000   | number    | number      |
| Yes      | numeric metric | 2001       | 2001   | number    | number      |
| Yes      | numeric metric | 2002       | 2002   | number    | number      |
| Yes      | numeric metric | 2003       | 2003   | number    | number      |
| Yes      | numeric metric | 2004       | 2004   | number    | number      |
| Yes      | numeric metric | 2005       | 2005   | number    | number      |
| Yes      | numeric metric | 2006       | 2006   | number    | number      |
| Yes      | numeric metric | 2007       | 2007   | number    | number      |
| Yes      | numeric metric | 2008       | 2008   | number    | number      |
| Yes      | numeric metric | 2009       | 2009   | number    | number      |
```

## Time Field

```ls
Value = 2000
Format & Zone = yyyy
```

## Data Commands

```ls
series e:mvzj-j8t8 d:2000-01-01T00:00:00.000Z t:county=Adams m:2008=0 m:2009=2 m:2006=2 m:2007=0 m:2004=0 m:2005=0 m:2002=0 m:2003=1 m:2001=0 m:2000=1

series e:mvzj-j8t8 d:2000-01-01T00:00:00.000Z t:county=Alexander m:2008=0 m:2009=0 m:2006=0 m:2007=0 m:2004=0 m:2005=0 m:2002=0 m:2003=0 m:2001=3 m:2000=0

series e:mvzj-j8t8 d:2000-01-01T00:00:00.000Z t:county=Bond m:2008=0 m:2009=0 m:2006=0 m:2007=0 m:2004=0 m:2005=0 m:2002=0 m:2003=0 m:2001=0 m:2000=0
```

## Meta Commands

```ls
metric m:2000 p:integer l:2000 t:dataTypeName=number

metric m:2001 p:integer l:2001 t:dataTypeName=number

metric m:2002 p:integer l:2002 t:dataTypeName=number

metric m:2003 p:integer l:2003 t:dataTypeName=number

metric m:2004 p:integer l:2004 t:dataTypeName=number

metric m:2005 p:integer l:2005 t:dataTypeName=number

metric m:2006 p:integer l:2006 t:dataTypeName=number

metric m:2007 p:integer l:2007 t:dataTypeName=number

metric m:2008 p:integer l:2008 t:dataTypeName=number

metric m:2009 p:integer l:2009 t:dataTypeName=number

entity e:mvzj-j8t8 l:"Illinois Tuberculosis Cases By County, 2000-2009" t:attribution="Illinois Department of Public Health, Office of Health Protection, Division of Infectious Disease, Tuberculosis Control Section" t:url=https://data.illinois.gov/api/views/mvzj-j8t8

property e:mvzj-j8t8 t:meta.view v:id=mvzj-j8t8 v:category=Health v:averageRating=0 v:name="Illinois Tuberculosis Cases By County, 2000-2009" v:attribution="Illinois Department of Public Health, Office of Health Protection, Division of Infectious Disease, Tuberculosis Control Section"

property e:mvzj-j8t8 t:meta.view.license v:name="Public Domain"

property e:mvzj-j8t8 t:meta.view.owner v:id=pf5f-nyht v:screenName="Kathryn M" v:displayName="Kathryn M"

property e:mvzj-j8t8 t:meta.view.tableauthor v:id=pf5f-nyht v:screenName="Kathryn M" v:displayName="Kathryn M"
```

## Top Records

```ls
| county    | 2000 | 2001 | 2002 | 2003 | 2004 | 2005 | 2006 | 2007 | 2008 | 2009 | 
| ========= | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | 
| Adams     | 1    | 0    | 0    | 1    | 0    | 0    | 2    | 0    | 0    | 2    | 
| Alexander | 0    | 3    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 
| Bond      | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 
| Boone     | 0    | 0    | 1    | 1    | 2    | 1    | 3    | 0    | 1    | 1    | 
| Brown     | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 
| Bureau    | 0    | 0    | 0    | 0    | 0    | 0    | 1    | 0    | 0    | 0    | 
| Calhoun   | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 
| Carroll   | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 
| Cass      | 0    | 0    | 0    | 0    | 0    | 2    | 2    | 0    | 2    | 0    | 
| Champaign | 4    | 10   | 10   | 4    | 3    | 6    | 1    | 4    | 9    | 9    | 
```