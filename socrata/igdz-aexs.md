# Government Assisted Housing Units by Town 2000-2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/government-assisted-housing-units-by-town-2000-2013) |
| Metadata | [Link](https://data.ct.gov/api/views/igdz-aexs) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/igdz-aexs/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/igdz-aexs/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | igdz-aexs |
| Name | Government Assisted Housing Units by Town 2000-2013 |
| Attribution | Department of Housing |
| Category | Housing and Development |
| Tags | housing, assisted, affordable |
| Created | 2014-12-11T15:55:22Z |
| Publication Date | 2014-12-11T15:57:22Z |

## Description

Assisted housing units or housing receiving financial assistance under any governmental program for the construction or substantial rehabilitation of low and moderate income housing that was occupied or under construction by the end date of the report period for compilation of a given year?s list

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
series e:igdz-aexs d:2000-01-01T00:00:00.000Z t:town_code=1 t:town=Andover m:2008=26 m:2009=26 m:2006=24 m:2007=26 m:2004=24 m:2013=24 m:2005=24 m:2002=24 m:2003=25 m:2012=25 m:2011=25 m:2010=25 m:2001=25 m:2000=0

series e:igdz-aexs d:2000-01-01T00:00:00.000Z t:town_code=2 t:town=Ansonia m:2008=1033 m:2009=889 m:2006=1059 m:2007=1064 m:2004=1053 m:2013=371 m:2005=1489 m:2002=1045 m:2003=1050 m:2012=1071 m:2011=1071 m:2010=1040 m:2001=1173 m:2000=1058

series e:igdz-aexs d:2000-01-01T00:00:00.000Z t:town_code=3 t:town=Ashford m:2008=35 m:2009=38 m:2006=36 m:2007=36 m:2004=37 m:2013=32 m:2005=43 m:2002=36 m:2003=35 m:2012=34 m:2011=33 m:2010=34 m:2001=35 m:2000=37
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

metric m:2010 p:integer l:2010 t:dataTypeName=number

metric m:2011 p:integer l:2011 t:dataTypeName=number

metric m:2012 p:integer l:2012 t:dataTypeName=number

metric m:2013 p:integer l:2013 t:dataTypeName=number

entity e:igdz-aexs l:"Government Assisted Housing Units by Town 2000-2013" t:attribution="Department of Housing" t:url=https://data.ct.gov/api/views/igdz-aexs

property e:igdz-aexs t:meta.view v:id=igdz-aexs v:category="Housing and Development" v:attributionLink="http://www.ct.gov/doh/cwp/view.asp?a=4513&q=530486" v:averageRating=0 v:name="Government Assisted Housing Units by Town 2000-2013" v:attribution="Department of Housing"

property e:igdz-aexs t:meta.view.license v:name="Public Domain"

property e:igdz-aexs t:meta.view.owner v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"

property e:igdz-aexs t:meta.view.tableauthor v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:roleName=administrator v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"
```

## Top Records

```ls
| town_code | town         | 2000 | 2001 | 2002 | 2003 | 2004 | 2005 | 2006 | 2007 | 2008 | 2009 | 2010 | 2011 | 2012 | 2013 | 
| ========= | ============ | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | 
| 1         | Andover      | 0    | 25   | 24   | 25   | 24   | 24   | 24   | 26   | 26   | 26   | 25   | 25   | 25   | 24   | 
| 2         | Ansonia      | 1058 | 1173 | 1045 | 1050 | 1053 | 1489 | 1059 | 1064 | 1033 | 889  | 1040 | 1071 | 1071 | 371  | 
| 3         | Ashford      | 37   | 35   | 36   | 35   | 37   | 43   | 36   | 36   | 35   | 38   | 34   | 33   | 34   | 32   | 
| 4         | Avon         | 90   | 137  | 100  | 91   | 141  | 86   | 142  | 143  | 141  | 142  | 142  | 245  | 247  | 244  | 
| 5         | Barkhamsted  | 9    | 4    | 2    | 3    | 1    | 1    | 1    | 0    | 0    | 3    | 3    | 3    | 1    | 0    | 
| 6         | Beacon Falls | 4    | 4    | 3    | 5    | 6    | 5    | 4    | 5    | 5    | 3    | 7    | 6    | 5    | 0    | 
| 7         | Berlin       | 90   | 76   | 75   | 196  | 210  | 202  | 395  | 400  | 407  | 408  | 495  | 498  | 497  | 556  | 
| 8         | Bethany      | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 1    | 0    | 0    | 0    | 0    | 
| 9         | Bethel       | 168  | 157  | 302  | 279  | 214  | 313  | 219  | 216  | 218  | 222  | 261  | 259  | 260  | 252  | 
| 10        | Bethlehem    | 24   | 24   | 24   | 24   | 24   | 24   | 24   | 24   | 24   | 24   | 24   | 24   | 25   | 24   | 
```