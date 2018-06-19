# ESG Grants 2001 To 2015

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/esg-grants-2001-to-2015) |
| Metadata | [Link](https://data.hartford.gov/api/views/i6uz-rj2n) |
| Data: JSON | [100 Rows](https://data.hartford.gov/api/views/i6uz-rj2n/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hartford.gov/api/views/i6uz-rj2n/rows.csv?max_rows=100) |
| Host | data.hartford.gov |
| Id | i6uz-rj2n |
| Name | ESG Grants 2001 To 2015 |
| Attribution | City of Hartford |
| Category | Financial |
| Tags | community, community development, grant, hartford, ct |
| Created | 2014-10-27T18:04:49Z |
| Publication Date | 2014-10-27T18:08:16Z |

## Description

US Housing and Urban Development - Emergency Solutions Grant. Grant awards by City of Hartford are Updated Yearly

## Columns

```ls
| Included | Schema Type    | Field Name | Name      | Data Type | Render Type |
| ======== | ============== | ========== | ========= | ========= | =========== |
| Yes      | series tag     | agency     | Agency    | text      | text        |
| Yes      | series tag     | program    | Program   | text      | text        |
| Yes      | numeric metric | 2001_2002  | 2001-2002 | money     | money       |
| Yes      | numeric metric | 2002_2003  | 2002-2003 | money     | money       |
| Yes      | numeric metric | 2003_2004  | 2003-2004 | money     | money       |
| Yes      | numeric metric | 2004_2005  | 2004-2005 | money     | money       |
| Yes      | numeric metric | 2005_2006  | 2005-2006 | money     | money       |
| Yes      | numeric metric | 2006_2007  | 2006-2007 | money     | money       |
| Yes      | numeric metric | 2007_2008  | 2007-2008 | money     | money       |
| Yes      | numeric metric | 2008_2009  | 2008-2009 | money     | money       |
| Yes      | numeric metric | 2009_2010  | 2009-2010 | money     | money       |
| Yes      | numeric metric | 2010_2011  | 2010-2011 | money     | money       |
| Yes      | numeric metric | 2011_2012  | 2011-2012 | money     | money       |
| Yes      | numeric metric | 2012_2013  | 2012-2013 | money     | money       |
| Yes      | numeric metric | 2013_2014  | 2013-2014 | money     | money       |
| Yes      | numeric metric | 2014_2015  | 2014-2015 | money     | money       |
```

## Time Field

```ls
Value = 2001
Format & Zone = yyyy
```

## Data Commands

```ls
series e:i6uz-rj2n d:2001-01-01T00:00:00.000Z t:program="Prevention (new-Hearth Act)" t:agency="AIDS, Connecticut" m:2014_2015=119185 m:2013_2014=103502

series e:i6uz-rj2n d:2001-01-01T00:00:00.000Z t:program="Interval House Shelter" t:agency="Hartford Interval House" m:2001_2002=10185 m:2007_2008=10259 m:2004_2005=10655 m:2002_2003=10245 m:2003_2004=10655 m:2008_2009=10259 m:2005_2006=10337 m:2010_2011=11751 m:2009_2010=10441 m:2014_2015=11500 m:2012_2013=12686 m:2011_2012=11571 m:2006_2007=10259 m:2013_2014=11213

series e:i6uz-rj2n d:2001-01-01T00:00:00.000Z t:program="McKinney Shelter" t:agency="Health & Human Services Dept" m:2007_2008=37617 m:2009_2010=38284 m:2014_2015=41283 m:2012_2013=45281 m:2004_2005=39065 m:2011_2012=41302 m:2006_2007=37617 m:2003_2004=39065 m:2013_2014=40042 m:2008_2009=37617 m:2005_2006=37901 m:2010_2011=42500
```

## Meta Commands

```ls
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

entity e:i6uz-rj2n l:"ESG Grants 2001 To 2015" t:attribution="City of Hartford" t:url=https://data.hartford.gov/api/views/i6uz-rj2n

property e:i6uz-rj2n t:meta.view v:id=i6uz-rj2n v:category=Financial v:attributionLink=http://www.hartford.gov v:averageRating=0 v:name="ESG Grants 2001 To 2015" v:attribution="City of Hartford"

property e:i6uz-rj2n t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:i6uz-rj2n t:meta.view.owner v:id=cdqe-xcn5 v:screenName=Brett v:displayName=Brett

property e:i6uz-rj2n t:meta.view.tableauthor v:id=cdqe-xcn5 v:screenName=Brett v:roleName=administrator v:displayName=Brett
```

## Top Records

```ls
| agency                        | program                     | 2001_2002 | 2002_2003 | 2003_2004 | 2004_2005 | 2005_2006 | 2006_2007 | 2007_2008 | 2008_2009 | 2009_2010 | 2010_2011 | 2011_2012 | 2012_2013 | 2013_2014 | 2014_2015 | 
| ============================= | =========================== | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | 
| AIDS, Connecticut             | Prevention (new-Hearth Act) |           |           |           |           |           |           |           |           |           |           |           |           | 103502    | 119185    | 
| Hartford Interval House       | Interval House Shelter      | 10185     | 10245     | 10655     | 10655     | 10337     | 10259     | 10259     | 10259     | 10441     | 11751     | 11571     | 12686     | 11213     | 11500     | 
| Health & Human Services Dept  | McKinney Shelter            |           |           | 39065     | 39065     | 37901     | 37617     | 37617     | 37617     | 38284     | 42500     | 41302     | 45281     | 40042     | 41283     | 
| House of Bread                | House of Bread Soup Kitchen | 4350      | 4375      | 4550      | 4410      | 4272      | 4240      | 4240      | 4240      | 4315      | 4856      | 4856      | 5324      |           |           | 
| Immaculate Conception Shelter | Emergency Shelter           | 12750     | 12805     | 13315     | 13315     | 12920     | 12824     | 12824     | 12824     | 13052     | 13052     | 13052     | 13052     | 11537     | 30580     | 
| Mercy Housing and Shelter     | Friendship Center           | 4350      | 4375      | 4550      | 4410      | 4272      | 4240      | 4240      | 4240      | 4315      | 4315      | 4315      |           |           |           | 
| Mercy Housing and Shelter     | St. Elizabeth House         | 10185     | 10240     | 10650     | 10650     | 10337     | 10249     | 10259     | 10259     | 10441     | 10441     | 10441     | 16178     | 14300     | 14300     | 
| My Sister's Place             | Emergency Shelter           | 8060      | 8110      | 8430      | 8430      | 8183      | 8122      | 8122      | 8122      |           |           |           |           |           |           | 
| Open Hearth                   | Emergency Shelter           | 10610     | 10670     | 11100     | 11100     | 10767     | 10687     | 10687     | 10687     | 10876     | 12241     | 12241     | 13420     | 11862     | 13767     | 
| Salvation Army                | Marshall House              | 13580     | 13660     | 14205     | 14205     | 13782     | 13679     | 13679     | 13679     | 13922     | 15670     | 15669     | 17179     | 15185     | 16028     | 
```