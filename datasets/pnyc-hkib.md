# DAS HR Almanac - Executive Branch Employment By Gender

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/das-hr-almanac-executive-branch-employment-by-gender) |
| Metadata | [Link](https://data.ct.gov/api/views/pnyc-hkib) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/pnyc-hkib/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/pnyc-hkib/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | pnyc-hkib |
| Name | DAS HR Almanac - Executive Branch Employment By Gender |
| Attribution | DAS Human Resources |
| Category | Government |
| Tags | hr, personnel, diversity |
| Created | 2016-01-13T20:29:55Z |
| Publication Date | 2016-10-12T16:30:50Z |

## Description

This data is reflective of the State of Connecticut Executive Branch workforce only.  The data does not reflect employees of the University of Connecticut Health Center, University of Connecticut and Board of Regents which includes the state university system and community colleges.  Judicial Branch and Legislative Branch employees are also not reflected in this data.

## Columns

```ls
| Included | Schema Type    | Field Name | Name    | Data Type | Render Type |
| ======== | ============== | ========== | ======= | ========= | =========== |
| Yes      | time           | year       | Year    | number    | number      |
| Yes      | numeric metric | male       | Male    | number    | number      |
| Yes      | numeric metric | female     | Female  | number    | number      |
| Yes      | numeric metric | unknown    | Unknown | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:pnyc-hkib d:2003-01-01T00:00:00.000Z m:female=18438 m:male=19355

series e:pnyc-hkib d:2004-01-01T00:00:00.000Z m:female=19026 m:male=19800

series e:pnyc-hkib d:2005-01-01T00:00:00.000Z m:female=19385 m:male=19880
```

## Meta Commands

```ls
metric m:male p:integer l:Male t:dataTypeName=number

metric m:female p:integer l:Female t:dataTypeName=number

metric m:unknown p:integer l:Unknown t:dataTypeName=number

entity e:pnyc-hkib l:"DAS HR Almanac - Executive Branch Employment By Gender" t:attribution="DAS Human Resources" t:url=https://data.ct.gov/api/views/pnyc-hkib

property e:pnyc-hkib t:meta.view v:id=pnyc-hkib v:category=Government v:averageRating=0 v:name="DAS HR Almanac - Executive Branch Employment By Gender" v:attribution="DAS Human Resources"

property e:pnyc-hkib t:meta.view.license v:name="Public Domain"

property e:pnyc-hkib t:meta.view.owner v:id=ksrh-ut6b v:screenName="Open Data Hub" v:displayName="Open Data Hub"

property e:pnyc-hkib t:meta.view.tableauthor v:id=ksrh-ut6b v:screenName="Open Data Hub" v:roleName=publisher v:displayName="Open Data Hub"
```

## Top Records

```ls
| year | male  | female | unknown | 
| ==== | ===== | ====== | ======= | 
| 2003 | 19355 | 18438  |         | 
| 2004 | 19800 | 19026  |         | 
| 2005 | 19880 | 19385  |         | 
| 2006 | 20316 | 19931  |         | 
| 2007 | 20257 | 19879  |         | 
| 2008 | 20300 | 19935  |         | 
| 2009 | 18592 | 18494  |         | 
| 2010 | 18165 | 18028  |         | 
| 2011 | 16769 | 16864  |         | 
| 2012 | 16967 | 17146  |         | 
```