# DAS HR Almanac - Executive Branch Employment, Full time and Union Membership

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/das-hr-almanac-executive-branch-employment-full-time-and-union-membership) |
| Metadata | [Link](https://data.ct.gov/api/views/rqu9-nssq) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/rqu9-nssq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/rqu9-nssq/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | rqu9-nssq |
| Name | DAS HR Almanac - Executive Branch Employment, Full time and Union Membership |
| Attribution | DAS HR |
| Category | Government |
| Tags | hr, personne |
| Created | 2016-01-14T14:21:27Z |
| Publication Date | 2016-01-14T14:23:14Z |

## Description

This data is reflective of the State of Connecticut Executive Branch workforce only.  The data does not reflect employees of the University of Connecticut Health Center, University of Connecticut and Board of Regents which includes the state university system and community colleges.  Judicial Branch and Legislative Branch employees are also not reflected in this data.

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                  | Data Type | Render Type |
| ======== | ============== | =================== | ===================== | ========= | =========== |
| Yes      | time           | year                | Year                  | number    | number      |
| Yes      | numeric metric | active_employees    | # Active Employees    | number    | number      |
| Yes      | numeric metric | full_time_employees | # Full Time Employees | number    | number      |
| Yes      | numeric metric | union_members       | Union Members         | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:rqu9-nssq d:2003-01-01T00:00:00.000Z m:active_employees=37796 m:full_time_employees=36149 m:union_members=34333

series e:rqu9-nssq d:2004-01-01T00:00:00.000Z m:active_employees=38828 m:full_time_employees=37020 m:union_members=35164

series e:rqu9-nssq d:2005-01-01T00:00:00.000Z m:active_employees=39265 m:full_time_employees=37298 m:union_members=35590
```

## Meta Commands

```ls
metric m:active_employees p:integer l:"# Active Employees" t:dataTypeName=number

metric m:full_time_employees p:integer l:"# Full Time Employees" t:dataTypeName=number

metric m:union_members p:integer l:"Union Members" t:dataTypeName=number

entity e:rqu9-nssq l:"DAS HR Almanac - Executive Branch Employment, Full time and Union Membership" t:attribution="DAS HR" t:url=https://data.ct.gov/api/views/rqu9-nssq

property e:rqu9-nssq t:meta.view v:id=rqu9-nssq v:category=Government v:averageRating=0 v:name="DAS HR Almanac - Executive Branch Employment, Full time and Union Membership" v:attribution="DAS HR"

property e:rqu9-nssq t:meta.view.license v:name="Public Domain"

property e:rqu9-nssq t:meta.view.owner v:id=ksrh-ut6b v:screenName="Open Data Hub" v:displayName="Open Data Hub"

property e:rqu9-nssq t:meta.view.tableauthor v:id=ksrh-ut6b v:screenName="Open Data Hub" v:roleName=publisher v:displayName="Open Data Hub"
```

## Top Records

```ls
| year | active_employees | full_time_employees | union_members | 
| ==== | ================ | =================== | ============= | 
| 2003 | 37796            | 36149               | 34333         | 
| 2004 | 38828            | 37020               | 35164         | 
| 2005 | 39265            | 37298               | 35590         | 
| 2006 | 40247            | 38239               | 36313         | 
| 2007 | 40136            | 37978               | 36065         | 
| 2008 | 40235            | 38233               | 36182         | 
| 2009 | 37086            | 35169               | 33439         | 
| 2010 | 36223            | 34675               | 32940         | 
| 2011 | 33633            | 32287               | 30959         | 
| 2012 | 34113            | 32859               | 31346         | 
```