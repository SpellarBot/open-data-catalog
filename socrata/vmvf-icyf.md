# CDBG 1998 to 2015

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cdbg-1998-to-2015) |
| Metadata | [Link](https://data.hartford.gov/api/views/vmvf-icyf) |
| Data: JSON | [100 Rows](https://data.hartford.gov/api/views/vmvf-icyf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hartford.gov/api/views/vmvf-icyf/rows.csv?max_rows=100) |
| Host | data.hartford.gov |
| Id | vmvf-icyf |
| Name | CDBG 1998 to 2015 |
| Attribution | City of Hartford |
| Category | Financial |
| Tags | cdbg, community, community development, grant, hartford, ct |
| Created | 2014-09-18T13:58:54Z |
| Publication Date | 2014-09-18T14:10:06Z |

## Description

Community Development Block Grant awards to community-based agencies FY 1998 to current. Updated on a Yearly basis

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type | Render Type |
| ======== | ============== | ================ | ================ | ========= | =========== |
| Yes      | series tag     | agency           | Agency           | text      | text        |
| Yes      | series tag     | program_activity | Program/Activity | text      | text        |
| Yes      | numeric metric | 1997_1998        | 1997-1998        | money     | money       |
| Yes      | numeric metric | 1998_1999        | 1998-1999        | money     | money       |
| Yes      | numeric metric | 1999_2000        | 1999-2000        | money     | money       |
| Yes      | numeric metric | 2000_2001        | 2000-2001        | money     | money       |
| Yes      | numeric metric | 2001_2002        | 2001-2002        | money     | money       |
| Yes      | numeric metric | 2002_2003        | 2002-2003        | money     | money       |
| Yes      | numeric metric | 2003_2004        | 2003-2004        | money     | money       |
| Yes      | numeric metric | 2004_2005        | 2004-2005        | money     | money       |
| Yes      | numeric metric | 2005_2006        | 2005-2006        | money     | money       |
| Yes      | numeric metric | 2006_2007        | 2006-2007        | money     | money       |
| Yes      | numeric metric | 2007_2008        | 2007-2008        | money     | money       |
| Yes      | numeric metric | 2008_2009        | 2008-2009        | money     | money       |
| Yes      | numeric metric | 2009_2010        | 2009-2010        | money     | money       |
| Yes      | numeric metric | 2010_2011        | 2010-2011        | money     | money       |
| Yes      | numeric metric | 2011_2012        | 2011-2012        | money     | money       |
| Yes      | numeric metric | 2012_2013        | 2012-2013        | money     | money       |
| Yes      | numeric metric | 2013_2014        | 2013-2014        | money     | money       |
| Yes      | numeric metric | 2014_2015        | 2014-2015        | money     | money       |
```

## Time Field

```ls
Value = 1998
Format & Zone = yyyy
```

## Data Commands

```ls
series e:vmvf-icyf d:1998-01-01T00:00:00.000Z t:program_activity=STRIVE t:agency="Career Resources Inc." m:2014_2015=10000

series e:vmvf-icyf d:1998-01-01T00:00:00.000Z t:program_activity="Literacy Program" t:agency="Project HOPE, Inc." m:2001_2002=25000

series e:vmvf-icyf d:1998-01-01T00:00:00.000Z t:program_activity="Public Service" t:agency="Gardner's House" m:2014_2015=5000
```

## Meta Commands

```ls
metric m:1997_1998 p:integer l:1997-1998 t:dataTypeName=money

metric m:1998_1999 p:integer l:1998-1999 t:dataTypeName=money

metric m:1999_2000 p:integer l:1999-2000 t:dataTypeName=money

metric m:2000_2001 p:integer l:2000-2001 t:dataTypeName=money

metric m:2001_2002 p:integer l:2001-2002 t:dataTypeName=money

metric m:2002_2003 p:integer l:2002-2003 t:dataTypeName=money

metric m:2003_2004 p:integer l:2003-2004 t:dataTypeName=money

metric m:2004_2005 p:integer l:2004-2005 t:dataTypeName=money

metric m:2005_2006 p:integer l:2005-2006 t:dataTypeName=money

metric m:2006_2007 p:integer l:2006-2007 t:dataTypeName=money

metric m:2007_2008 p:integer l:2007-2008 t:dataTypeName=money

metric m:2008_2009 p:integer l:2008-2009 t:dataTypeName=money

metric m:2009_2010 p:integer l:2009-2010 t:dataTypeName=money

metric m:2010_2011 p:integer l:2010-2011 t:dataTypeName=money

metric m:2011_2012 p:integer l:2011-2012 t:dataTypeName=money

metric m:2012_2013 p:integer l:2012-2013 t:dataTypeName=money

metric m:2013_2014 p:integer l:2013-2014 t:dataTypeName=money

metric m:2014_2015 p:integer l:2014-2015 t:dataTypeName=money

entity e:vmvf-icyf l:"CDBG 1998 to 2015" t:attribution="City of Hartford" t:url=https://data.hartford.gov/api/views/vmvf-icyf

property e:vmvf-icyf t:meta.view v:id=vmvf-icyf v:category=Financial v:attributionLink=http://www.hartford.gov v:averageRating=0 v:name="CDBG 1998 to 2015" v:attribution="City of Hartford"

property e:vmvf-icyf t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:vmvf-icyf t:meta.view.owner v:id=cdqe-xcn5 v:screenName=Brett v:displayName=Brett

property e:vmvf-icyf t:meta.view.tableauthor v:id=cdqe-xcn5 v:screenName=Brett v:roleName=administrator v:displayName=Brett
```

## Top Records

```ls
| agency                          | program_activity                  | 1997_1998 | 1998_1999 | 1999_2000 | 2000_2001 | 2001_2002 | 2002_2003 | 2003_2004 | 2004_2005 | 2005_2006 | 2006_2007 | 2007_2008 | 2008_2009 | 2009_2010 | 2010_2011 | 2011_2012 | 2012_2013 | 2013_2014 | 2014_2015 | 
| =============================== | ================================= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | 
| Career Resources Inc.           | STRIVE                            |           |           |           |           |           |           |           |           |           |           |           |           |           |           |           |           |           | 10000     | 
| Project HOPE, Inc.              | Literacy Program                  |           |           |           |           | 25000     |           |           |           |           |           |           |           |           |           |           |           |           |           | 
| Gardner's House                 | Public Service                    |           |           |           |           |           |           |           |           |           |           |           |           |           |           |           |           |           | 5000      | 
| Hartford Animiation             | Joe Picture This Show             |           |           |           |           |           |           |           |           |           |           |           |           |           |           | 8500      |           |           |           | 
| Connecticut Public Broadcasting | Learning lab                      |           |           |           |           |           |           |           |           |           |           |           |           |           |           |           |           | 50000     |           | 
| Open Hearth Association         | Facility Improvements             |           |           |           |           |           |           |           |           |           |           |           |           |           |           |           |           |           | 244322    | 
| Hartford Community Loan         | Credit Builder Program            |           |           |           |           |           |           |           |           |           |           |           |           |           |           |           |           | 5000      | 4500      | 
| Chrysalis Center, Inc.          | Chrysalis Center Internet Project |           |           | 30000     |           |           |           |           |           |           |           |           |           |           |           |           |           |           |           | 
| Journey Home                    | Job Development Program           |           |           |           |           |           |           |           |           |           |           |           |           |           |           |           |           |           | 35274     | 
| Catholic Charities, Inc.        | Juvenile Review Board             |           |           |           |           |           |           |           |           | 8000      |           |           |           |           |           |           |           |           |           | 
```