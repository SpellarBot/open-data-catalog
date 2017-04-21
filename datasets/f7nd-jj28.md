# Abortion Demographics, 1995-2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/abortion-demographics-1995-2012-8f496) |
| Metadata | [Link](https://data.illinois.gov/api/views/f7nd-jj28) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/f7nd-jj28/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/f7nd-jj28/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | f7nd-jj28 |
| Name | Abortion Demographics, 1995-2012 |
| Attribution | Illinois Department of Public Health, Office of Finance and Administration, Division of Vital Records |
| Category | Health |
| Tags | health, abortion, demographics, age, marital status, pregnancy |
| Created | 2014-08-19T14:02:49Z |
| Publication Date | 2014-08-19T14:11:21Z |

## Description

The number of induced pregnancy terminations reported in Illinois by county (if in excess of 50), by age and marital status. Note: Marital status and age are only for Illinois residents.

## Columns

```ls
| Included | Schema Type    | Field Name | Name | Data Type | Render Type |
| ======== | ============== | ========== | ==== | ========= | =========== |
| Yes      | series tag     | year       | YEAR | text      | text        |
| Yes      | numeric metric | 1995       | 1995 | number    | number      |
| Yes      | numeric metric | 1996       | 1996 | number    | number      |
| Yes      | numeric metric | 1997       | 1997 | number    | number      |
| Yes      | numeric metric | 1998       | 1998 | number    | number      |
| Yes      | numeric metric | 1999       | 1999 | number    | number      |
| Yes      | numeric metric | 2000       | 2000 | number    | number      |
| Yes      | numeric metric | 2001       | 2001 | number    | number      |
| Yes      | numeric metric | 2002       | 2002 | number    | number      |
| Yes      | numeric metric | 2003       | 2003 | number    | number      |
| Yes      | numeric metric | 2004       | 2004 | number    | number      |
| Yes      | numeric metric | 2005       | 2005 | number    | number      |
| Yes      | numeric metric | 2006       | 2006 | number    | number      |
| Yes      | numeric metric | 2007       | 2007 | number    | number      |
| Yes      | numeric metric | 2008       | 2008 | number    | number      |
| Yes      | numeric metric | 2009       | 2009 | number    | number      |
| Yes      | numeric metric | 2010       | 2010 | number    | number      |
| Yes      | numeric metric | 2011       | 2011 | number    | number      |
| Yes      | numeric metric | 2012       | 2012 | number    | number      |
```

## Time Field

```ls
Value = 1995
Format & Zone = yyyy
```

## Data Commands

```ls
series e:f7nd-jj28 d:1995-01-01T00:00:00.000Z t:year=TOTAL m:2008=47717 m:1995=52300 m:2009=46077 m:1996=53613 m:2006=46467 m:1997=50147 m:2007=45298 m:1998=49403 m:2004=43537 m:2005=43409 m:2002=46945 m:2003=42228 m:2012=43203 m:2011=41324 m:2010=41859 m:1999=45924 m:2001=46546 m:2000=45884

series e:f7nd-jj28 d:1995-01-01T00:00:00.000Z t:year="IL RESIDENTS" m:2008=42703 m:1995=48529 m:2009=41307 m:1996=49457 m:2006=40412 m:1997=46121 m:2007=39291 m:1998=44815 m:2004=40023 m:2005=38409 m:2002=42655 m:2003=38700 m:2012=39849 m:2011=37922 m:2010=38622 m:1999=41509 m:2001=41523 m:2000=40754

series e:f7nd-jj28 d:1995-01-01T00:00:00.000Z t:year="OUT OF STATE" m:2008=3903 m:1995=3575 m:2009=3624 m:1996=3859 m:2006=3940 m:1997=3916 m:2007=4042 m:1998=4517 m:2004=3400 m:2005=3317 m:2002=4207 m:2003=3497 m:2012=3138 m:2011=3139 m:2010=3050 m:1999=4294 m:2001=4488 m:2000=4852
```

## Meta Commands

```ls
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

metric m:2011 p:integer l:2011 t:dataTypeName=number

metric m:2012 p:integer l:2012 t:dataTypeName=number

entity e:f7nd-jj28 l:"Abortion Demographics, 1995-2012" t:attribution="Illinois Department of Public Health, Office of Finance and Administration, Division of Vital Records" t:url=https://data.illinois.gov/api/views/f7nd-jj28

property e:f7nd-jj28 t:meta.view v:id=f7nd-jj28 v:category=Health v:averageRating=0 v:name="Abortion Demographics, 1995-2012" v:attribution="Illinois Department of Public Health, Office of Finance and Administration, Division of Vital Records"

property e:f7nd-jj28 t:meta.view.license v:name="Public Domain"

property e:f7nd-jj28 t:meta.view.owner v:id=pf5f-nyht v:screenName="Kathryn M" v:displayName="Kathryn M"

property e:f7nd-jj28 t:meta.view.tableauthor v:id=pf5f-nyht v:screenName="Kathryn M" v:displayName="Kathryn M"
```

## Top Records

```ls
| year                       | 1995  | 1996  | 1997  | 1998  | 1999  | 2000  | 2001  | 2002  | 2003  | 2004  | 2005  | 2006  | 2007  | 2008  | 2009  | 2010  | 2011  | 2012  | 
| ========================== | ===== | ===== | ===== | ===== | ===== | ===== | ===== | ===== | ===== | ===== | ===== | ===== | ===== | ===== | ===== | ===== | ===== | ===== | 
| TOTAL                      | 52300 | 53613 | 50147 | 49403 | 45924 | 45884 | 46546 | 46945 | 42228 | 43537 | 43409 | 46467 | 45298 | 47717 | 46077 | 41859 | 41324 | 43203 | 
| IL RESIDENTS               | 48529 | 49457 | 46121 | 44815 | 41509 | 40754 | 41523 | 42655 | 38700 | 40023 | 38409 | 40412 | 39291 | 42703 | 41307 | 38622 | 37922 | 39849 | 
| OUT OF STATE               | 3575  | 3859  | 3916  | 4517  | 4294  | 4852  | 4488  | 4207  | 3497  | 3400  | 3317  | 3940  | 4042  | 3903  | 3624  | 3050  | 3139  | 3138  | 
| STATE OF RESIDENCY UNKNOWN | 196   | 297   | 110   | 71    | 121   | 278   | 535   | 83    | 31    | 114   | 1683  | 2115  | 1965  | 1111  | 1146  | 187   | 263   | 216   | 
| MARRIED (IL RESIDENT)      | 8307  | 8643  | 7729  | 7084  | 6880  | 6497  | 7204  | 7138  | 6599  | 6727  | 6341  | 6189  | 5741  | 5074  | 4905  | 4351  | 4538  | 4800  | 
| UNMARRIED (IL RESIDENT)    | 37760 | 39399 | 37192 | 36288 | 32485 | 32735 | 33323 | 34543 | 31129 | 32771 | 31342 | 33473 | 32794 | 35997 | 35035 | 32492 | 32596 | 34599 | 
| MARITAL STATUS UNKNOWN     | 2462  | 1415  | 1200  | 1443  | 2144  | 1522  | 996   | 974   | 972   | 525   | 726   | 750   | 756   | 1632  | 1367  | 1779  | 788   | 450   | 
| Age 0-14                   | 466   | 434   | 345   | 354   | 307   | 295   | 298   | 281   | 287   | 308   | 237   | 282   | 257   | 299   | 257   | 229   | 185   | 218   | 
| Age 15-17                  | 4387  | 4380  | 4224  | 3794  | 3340  | 3267  | 3063  | 2902  | 2820  | 2942  | 2798  | 2875  | 2827  | 2995  | 2734  | 2496  | 2174  | 1995  | 
| Age 18-19                  | 5841  | 5822  | 5397  | 5055  | 4783  | 4755  | 4523  | 4477  | 4042  | 4258  | 3874  | 3959  | 4054  | 4383  | 4221  | 3863  | 3528  | 3442  | 
```