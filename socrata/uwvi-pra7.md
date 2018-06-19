# DAS HR Almanac - Executive Branch Employment, Full Time Vs Part Time

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/das-hr-almanac-executive-branch-employment-full-time-vs-part-time) |
| Metadata | [Link](https://data.ct.gov/api/views/uwvi-pra7) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/uwvi-pra7/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/uwvi-pra7/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | uwvi-pra7 |
| Name | DAS HR Almanac - Executive Branch Employment, Full Time Vs Part Time |
| Attribution | DAS HR |
| Category | Government |
| Tags | hr, personnel |
| Created | 2016-01-14T17:38:25Z |
| Publication Date | 2016-10-11T20:45:14Z |

## Description

This data is reflective of the State of Connecticut Executive Branch workforce only.  The data does not reflect employees of the University of Connecticut Health Center, University of Connecticut and Board of Regents which includes the state university system and community colleges.  Judicial Branch and Legislative Branch employees are also not reflected in this data.

## Columns

```ls
| Included | Schema Type | Field Name | Name      | Data Type | Render Type |
| ======== | =========== | ========== | ========= | ========= | =========== |
| Yes      | time        | year       | Year      | number    | number      |
| No       |             | full_time  | Full-Time | number    | number      |
| No       |             | part_time  | Part-Time | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = full_time,part_time
```

## Data Commands

```ls
```

## Meta Commands

```ls
entity e:uwvi-pra7 l:"DAS HR Almanac - Executive Branch Employment, Full Time Vs Part Time" t:attribution="DAS HR" t:url=https://data.ct.gov/api/views/uwvi-pra7

property e:uwvi-pra7 t:meta.view v:id=uwvi-pra7 v:category=Government v:averageRating=0 v:name="DAS HR Almanac - Executive Branch Employment, Full Time Vs Part Time" v:attribution="DAS HR"

property e:uwvi-pra7 t:meta.view.license v:name="Public Domain"

property e:uwvi-pra7 t:meta.view.owner v:id=ksrh-ut6b v:screenName="Open Data Hub" v:displayName="Open Data Hub"

property e:uwvi-pra7 t:meta.view.tableauthor v:id=ksrh-ut6b v:screenName="Open Data Hub" v:roleName=publisher v:displayName="Open Data Hub"
```

## Top Records

```ls
| year | full_time | part_time | 
| ==== | ========= | ========= | 
| 2003 | 33878     | 3918      | 
| 2004 | 34865     | 3963      | 
| 2005 | 35203     | 4062      | 
| 2006 | 35850     | 4397      | 
| 2007 | 35327     | 4809      | 
| 2008 | 35633     | 4602      | 
| 2009 | 32785     | 4301      | 
| 2010 | 32499     | 3694      | 
| 2011 | 30412     | 3221      | 
| 2012 | 31096     | 3017      | 
```