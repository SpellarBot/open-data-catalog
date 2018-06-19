# Firearms Discharge Report

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/firearms-discharge-report-17206) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/7r8u-zrb7) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/7r8u-zrb7/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/7r8u-zrb7/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 7r8u-zrb7 |
| Name | Firearms Discharge Report |
| Attribution | Police Department (NYPD) |
| Category | Public Safety |
| Tags | nypd, firearms, discharge report |
| Created | 2014-10-23T15:23:56Z |
| Publication Date | 2014-10-23T15:56:25Z |

## Description

Report detailing NYPD occurrence of firearm discharge

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type | Render Type |
| ======== | ============== | ================ | ================ | ========= | =========== |
| No       | time           | :updated_at      | updated_at       | meta_data | meta_data   |
| Yes      | series tag     | discharge_detail | Discharge Detail | text      | text        |
| Yes      | numeric metric | 2002             | 2002             | number    | number      |
| Yes      | numeric metric | 2003             | 2003             | number    | number      |
| Yes      | numeric metric | 2004             | 2004             | number    | number      |
| Yes      | numeric metric | 2005             | 2005             | number    | number      |
| Yes      | numeric metric | 2006             | 2006             | number    | number      |
| Yes      | numeric metric | 2007             | 2007             | number    | number      |
| Yes      | numeric metric | 2008             | 2008             | number    | number      |
| Yes      | numeric metric | 2009             | 2009             | number    | number      |
| Yes      | numeric metric | 2010             | 2010             | number    | number      |
| Yes      | numeric metric | 2011             | 2011             | number    | number      |
| Yes      | numeric metric | 2012             | 2012             | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:7r8u-zrb7 d:2014-10-23T08:23:59.000Z t:discharge_detail="Adversarial  Conflict" m:2008=49 m:2009=47 m:2006=59 m:2007=45 m:2004=51 m:2005=59 m:2002=55 m:2003=61 m:2012=45 m:2011=36 m:2010=33

series e:7r8u-zrb7 d:2014-10-23T08:23:59.000Z t:discharge_detail="Animal  Attack" m:2008=30 m:2009=28 m:2006=30 m:2007=39 m:2004=26 m:2005=32 m:2002=38 m:2003=35 m:2012=24 m:2011=36 m:2010=30

series e:7r8u-zrb7 d:2014-10-23T08:23:59.000Z t:discharge_detail="Unintentional  Discharge" m:2008=15 m:2009=23 m:2006=26 m:2007=15 m:2004=27 m:2005=25 m:2002=24 m:2003=25 m:2012=21 m:2011=15 m:2010=21
```

## Meta Commands

```ls
metric m:2002 p:integer l:2002 t:dataTypeName=number

metric m:2003 p:integer l:2003 t:dataTypeName=number

metric m:2004 p:integer l:2004 t:dataTypeName=number

metric m:2005 p:integer l:2005 t:dataTypeName=number

metric m:2006 p:integer l:2006 t:dataTypeName=number

metric m:2007 p:integer l:2007 t:dataTypeName=number

metric m:2008 p:integer l:2008 t:dataTypeName=number

metric m:2009 p:integer l:2009 t:dataTypeName=number

metric m:2010 p:integer l:2010 t:dataTypeName=number

metric m:2011 p:integer l:2011 t:dataTypeName=number

metric m:2012 p:integer l:2012 t:dataTypeName=number

entity e:7r8u-zrb7 l:"Firearms Discharge Report" t:attribution="Police Department (NYPD)" t:url=https://data.cityofnewyork.us/api/views/7r8u-zrb7

property e:7r8u-zrb7 t:meta.view v:id=7r8u-zrb7 v:category="Public Safety" v:averageRating=0 v:name="Firearms Discharge Report" v:attribution="Police Department (NYPD)"

property e:7r8u-zrb7 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:7r8u-zrb7 t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | discharge_detail              | 2002 | 2003 | 2004 | 2005 | 2006 | 2007 | 2008 | 2009 | 2010 | 2011 | 2012 | 
| =========== | ============================= | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | 
| 1414052639  | Adversarial Conflict          | 55   | 61   | 51   | 59   | 59   | 45   | 49   | 47   | 33   | 36   | 45   | 
| 1414052639  | Animal Attack                 | 38   | 35   | 26   | 32   | 30   | 39   | 30   | 28   | 30   | 36   | 24   | 
| 1414052639  | Unintentional Discharge       | 24   | 25   | 27   | 25   | 26   | 15   | 15   | 23   | 21   | 15   | 21   | 
| 1414052639  | Mistaken Identity             | 0    | 0    | 0    | 0    | 1    | 0    | 0    | 1    | 0    | 0    | 0    | 
| 1414052639  | Unauthorized use of a Firearm | 0    | 2    | 5    | 6    | 8    | 6    | 3    | 4    | 6    | 2    | 6    | 
| 1414052639  | MOS Suicide / Attempt         | 2    | 7    | 5    | 3    | 3    | 6    | 8    | 3    | 2    | 3    | 9    | 
```