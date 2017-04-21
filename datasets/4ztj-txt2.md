# Illinois Tuberculosis Cases By County, 1990-2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/illinois-tuberculosis-cases-by-county-1990-2010-a4046) |
| Metadata | [Link](https://data.illinois.gov/api/views/4ztj-txt2) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/4ztj-txt2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/4ztj-txt2/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | 4ztj-txt2 |
| Name | Illinois Tuberculosis Cases By County, 1990-2010 |
| Attribution | Illinois Department of Public Health, Office of Health Protection, Division of Infectious Disease, Tuberculosis Control Section |
| Category | Health |
| Tags | health, disease, tuberculosis, tb, infectious disease |
| Created | 2014-08-12T14:25:43Z |
| Publication Date | 2014-08-12T14:26:51Z |

## Description

Data was provided by the Tuberculosis Control Section of the Office of Health Protection's Division of Infectious Diseases.

## Columns

```ls
| Included | Schema Type    | Field Name | Name   | Data Type | Render Type |
| ======== | ============== | ========== | ====== | ========= | =========== |
| Yes      | series tag     | county     | County | text      | text        |
| Yes      | numeric metric | 1990       | 1990   | number    | number      |
| Yes      | numeric metric | 1991       | 1991   | number    | number      |
| Yes      | numeric metric | 1992       | 1992   | number    | number      |
| Yes      | numeric metric | 1993       | 1993   | number    | number      |
| Yes      | numeric metric | 1994       | 1994   | number    | number      |
| Yes      | numeric metric | 1995       | 1995   | number    | number      |
| Yes      | numeric metric | 1996       | 1996   | number    | number      |
| Yes      | numeric metric | 1997       | 1997   | number    | number      |
| Yes      | numeric metric | 1998       | 1998   | number    | number      |
| Yes      | numeric metric | 1999       | 1999   | number    | number      |
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
| Yes      | numeric metric | 2010       | 2010   | number    | number      |
```

## Time Field

```ls
Value = 1990
Format & Zone = yyyy
```

## Data Commands

```ls
series e:4ztj-txt2 d:1990-01-01T00:00:00.000Z t:county=Adams m:2008=0 m:2009=2 m:2006=2 m:2007=0 m:2004=0 m:2005=0 m:2002=0 m:2003=1 m:1990=0 m:1995=0 m:1996=1 m:1997=3 m:1998=0 m:1991=0 m:1992=0 m:1993=0 m:1994=0 m:2010=0 m:1999=5 m:2001=0 m:2000=1

series e:4ztj-txt2 d:1990-01-01T00:00:00.000Z t:county=Alexander m:2008=0 m:2009=0 m:2006=0 m:2007=0 m:2004=0 m:2005=0 m:2002=0 m:2003=0 m:1990=2 m:1995=2 m:1996=1 m:1997=2 m:1998=2 m:1991=5 m:1992=1 m:1993=1 m:1994=2 m:2010=0 m:1999=0 m:2001=3 m:2000=0

series e:4ztj-txt2 d:1990-01-01T00:00:00.000Z t:county=Bond m:2008=0 m:2009=0 m:2006=0 m:2007=0 m:2004=0 m:2005=0 m:2002=0 m:2003=0 m:1990=0 m:1995=0 m:1996=0 m:1997=1 m:1998=0 m:1991=3 m:1992=2 m:1993=0 m:1994=0 m:2010=0 m:1999=0 m:2001=0 m:2000=0
```

## Meta Commands

```ls
metric m:1990 p:integer l:1990 t:dataTypeName=number

metric m:1991 p:integer l:1991 t:dataTypeName=number

metric m:1992 p:integer l:1992 t:dataTypeName=number

metric m:1993 p:integer l:1993 t:dataTypeName=number

metric m:1994 p:integer l:1994 t:dataTypeName=number

metric m:1995 p:integer l:1995 t:dataTypeName=number

metric m:1996 p:integer l:1996 t:dataTypeName=number

metric m:1997 p:integer l:1997 t:dataTypeName=number

metric m:1998 p:integer l:1998 t:dataTypeName=number

metric m:1999 p:integer l:1999 t:dataTypeName=number

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

metric m:2010 p:integer l:2010 t:dataTypeName=number

entity e:4ztj-txt2 l:"Illinois Tuberculosis Cases By County, 1990-2010" t:attribution="Illinois Department of Public Health, Office of Health Protection, Division of Infectious Disease, Tuberculosis Control Section" t:url=https://data.illinois.gov/api/views/4ztj-txt2

property e:4ztj-txt2 t:meta.view v:id=4ztj-txt2 v:category=Health v:averageRating=0 v:name="Illinois Tuberculosis Cases By County, 1990-2010" v:attribution="Illinois Department of Public Health, Office of Health Protection, Division of Infectious Disease, Tuberculosis Control Section"

property e:4ztj-txt2 t:meta.view.license v:name="Public Domain"

property e:4ztj-txt2 t:meta.view.owner v:id=pf5f-nyht v:screenName="Kathryn M" v:displayName="Kathryn M"

property e:4ztj-txt2 t:meta.view.tableauthor v:id=pf5f-nyht v:screenName="Kathryn M" v:displayName="Kathryn M"
```

## Top Records

```ls
| county    | 1990 | 1991 | 1992 | 1993 | 1994 | 1995 | 1996 | 1997 | 1998 | 1999 | 2000 | 2001 | 2002 | 2003 | 2004 | 2005 | 2006 | 2007 | 2008 | 2009 | 2010 | 
| ========= | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | 
| Adams     | 0    | 0    | 0    | 0    | 0    | 0    | 1    | 3    | 0    | 5    | 1    | 0    | 0    | 1    | 0    | 0    | 2    | 0    | 0    | 2    | 0    | 
| Alexander | 2    | 5    | 1    | 1    | 2    | 2    | 1    | 2    | 2    | 0    | 0    | 3    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 
| Bond      | 0    | 3    | 2    | 0    | 0    | 0    | 0    | 1    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 
| Boone     | 0    | 0    | 0    | 2    | 0    | 1    | 3    | 0    | 0    | 1    | 0    | 0    | 1    | 1    | 2    | 1    | 3    | 0    | 1    | 1    | 0    | 
| Brown     | 0    | 1    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 
| Bureau    | 0    | 2    | 0    | 0    | 2    | 1    | 0    | 0    | 0    | 1    | 0    | 0    | 0    | 0    | 0    | 0    | 1    | 0    | 0    | 0    | 0    | 
| Calhoun   | 0    | 1    | 0    | 0    | 1    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 
| Carroll   | 0    | 0    | 0    | 0    | 0    | 0    | 2    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 1    | 
| Cass      | 1    | 0    | 0    | 1    | 1    | 2    | 0    | 0    | 0    | 1    | 0    | 0    | 0    | 0    | 0    | 2    | 2    | 0    | 2    | 0    | 0    | 
| Champaign | 6    | 4    | 8    | 8    | 6    | 12   | 3    | 14   | 7    | 16   | 4    | 10   | 10   | 4    | 3    | 6    | 1    | 4    | 9    | 9    | 5    | 
```