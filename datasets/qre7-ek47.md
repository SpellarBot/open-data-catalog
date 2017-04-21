# Deed Restricted Affordable Housing Units by Town 2000-2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/deed-restricted-affordable-housing-units-by-town-2000-2013) |
| Metadata | [Link](https://data.ct.gov/api/views/qre7-ek47) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/qre7-ek47/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/qre7-ek47/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | qre7-ek47 |
| Name | Deed Restricted Affordable Housing Units by Town 2000-2013 |
| Attribution | Department of Housing |
| Category | Housing and Development |
| Tags | housing, affordable |
| Created | 2014-12-11T15:38:58Z |
| Publication Date | 2014-12-11T15:54:51Z |

## Description

Deed-restricted properties or properties with deeds containing covenants or restrictions that require such dwelling unit(s) be sold or rented at or below prices that will preserve the unit(s) as affordable housing as defined in C.G.S. Section 8-39a for persons or families whose incomes are less than or equal to 80% of the area median income.

## Columns

```ls
| Included | Schema Type    | Field Name | Name      | Data Type | Render Type |
| ======== | ============== | ========== | ========= | ========= | =========== |
| Yes      | series tag     | town_code  | Town Code | text      | number      |
| Yes      | series tag     | town       | Town      | text      | text        |
| Yes      | numeric metric | 2000       | 2000      | number    | number      |
| Yes      | numeric metric | 2001       | 2001      | number    | number      |
| Yes      | numeric metric | 2002       | 2002      | number    | number      |
| Yes      | numeric metric | 2003       | 2003      | number    | number      |
| Yes      | numeric metric | 2004       | 2004      | number    | number      |
| Yes      | numeric metric | 2005       | 2005      | number    | number      |
| Yes      | numeric metric | 2006       | 2006      | number    | number      |
| Yes      | numeric metric | 2007       | 2007      | number    | number      |
| Yes      | numeric metric | 2008       | 2008      | number    | number      |
| Yes      | numeric metric | 2009       | 2009      | number    | number      |
| Yes      | numeric metric | 2010       | 2010      | number    | number      |
| Yes      | numeric metric | 2011       | 2011      | number    | number      |
| Yes      | numeric metric | 2012       | 2012      | number    | number      |
| Yes      | numeric metric | 2013       | 2013      | number    | number      |
```

## Time Field

```ls
Value = 2000
Format & Zone = yyyy
```

## Data Commands

```ls
series e:qre7-ek47 d:2000-01-01T00:00:00.000Z t:town_code=1 t:town=Andover m:2008=0 m:2009=0 m:2006=0 m:2007=0 m:2004=0 m:2013=0 m:2005=0 m:2002=0 m:2003=0 m:2012=0 m:2011=0 m:2010=0 m:2001=0 m:2000=0

series e:qre7-ek47 d:2000-01-01T00:00:00.000Z t:town_code=2 t:town=Ansonia m:2008=9 m:2009=9 m:2006=9 m:2007=9 m:2004=0 m:2013=9 m:2005=0 m:2002=0 m:2003=0 m:2012=9 m:2011=9 m:2010=9 m:2001=0 m:2000=0

series e:qre7-ek47 d:2000-01-01T00:00:00.000Z t:town_code=3 t:town=Ashford m:2008=0 m:2009=0 m:2006=0 m:2007=0 m:2004=0 m:2013=0 m:2005=0 m:2002=0 m:2003=0 m:2012=0 m:2011=0 m:2010=0 m:2001=0 m:2000=0
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

metric m:2007 p:double l:2007 t:dataTypeName=number

metric m:2008 p:integer l:2008 t:dataTypeName=number

metric m:2009 p:integer l:2009 t:dataTypeName=number

metric m:2010 p:integer l:2010 t:dataTypeName=number

metric m:2011 p:integer l:2011 t:dataTypeName=number

metric m:2012 p:integer l:2012 t:dataTypeName=number

metric m:2013 p:integer l:2013 t:dataTypeName=number

entity e:qre7-ek47 l:"Deed Restricted Affordable Housing Units by Town 2000-2013" t:attribution="Department of Housing" t:url=https://data.ct.gov/api/views/qre7-ek47

property e:qre7-ek47 t:meta.view v:id=qre7-ek47 v:category="Housing and Development" v:attributionLink="http://www.ct.gov/doh/cwp/view.asp?a=4513&q=530486" v:averageRating=0 v:name="Deed Restricted Affordable Housing Units by Town 2000-2013" v:attribution="Department of Housing"

property e:qre7-ek47 t:meta.view.license v:name="Public Domain"

property e:qre7-ek47 t:meta.view.owner v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"

property e:qre7-ek47 t:meta.view.tableauthor v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:roleName=administrator v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"
```

## Top Records

```ls
| town_code | town         | 2000 | 2001 | 2002 | 2003 | 2004 | 2005 | 2006 | 2007 | 2008 | 2009 | 2010 | 2011 | 2012 | 2013 | 
| ========= | ============ | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | 
| 1         | Andover      | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 
| 2         | Ansonia      | 0    | 0    | 0    | 0    | 0    | 0    | 9    | 9    | 9    | 9    | 9    | 9    | 9    | 9    | 
| 3         | Ashford      | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 
| 4         | Avon         | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 
| 5         | Barkhamsted  | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 
| 6         | Beacon Falls | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 
| 7         | Berlin       | 0    | 0    | 21   | 21   | 21   | 21   | 6    | 6    | 6    | 6    | 6    | 6    | 6    | 6    | 
| 8         | Bethany      | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 1    | 1    | 
| 9         | Bethel       | 0    | 0    | 0    | 34   | 46   | 46   | 46   | 46   | 62   | 63   | 63   | 63   | 63   | 63   | 
| 10        | Bethlehem    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 
```