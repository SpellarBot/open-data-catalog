# BayStat Solutions Reporting - Maryland Dept. of Agriculture

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/baystat-solutions-reporting-maryland-dept-of-agriculture-4cf85) |
| Metadata | [Link](https://data.maryland.gov/api/views/tsya-25ee) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/tsya-25ee/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/tsya-25ee/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | tsya-25ee |
| Name | BayStat Solutions Reporting - Maryland Dept. of Agriculture |
| Attribution | Maryland Department of Agriculture |
| Category | Energy and Environment |
| Tags | chesapeake, bay, baystat, solutions, basin, bmp, best, management, practice |
| Created | 2014-02-07T15:25:47Z |
| Publication Date | 2015-08-17T13:33:30Z |

## Description

Chesapeake Bay restoration solutions, Best Management Practices (BMPs), progress reporting by tributary basin. See the BayStat Solutions Reference table for further definition.

## Columns

```ls
| Included | Schema Type    | Field Name               | Name                     | Data Type | Render Type |
| ======== | ============== | ======================== | ======================== | ========= | =========== |
| No       | time           | :updated_at              | updated_at               | meta_data | meta_data   |
| Yes      | series tag     | basin_name               | Basin Name               | text      | text        |
| Yes      | series tag     | best_management_practice | Best Management Practice | text      | text        |
| Yes      | numeric metric | 2000                     | 2000                     | number    | number      |
| Yes      | numeric metric | 2001                     | 2001                     | number    | number      |
| Yes      | numeric metric | 2002                     | 2002                     | number    | number      |
| Yes      | numeric metric | 2003                     | 2003                     | number    | number      |
| Yes      | numeric metric | 2004                     | 2004                     | number    | number      |
| Yes      | numeric metric | 2005                     | 2005                     | number    | number      |
| Yes      | numeric metric | 2006                     | 2006                     | number    | number      |
| Yes      | numeric metric | 2007                     | 2007                     | number    | number      |
| Yes      | numeric metric | 2008                     | 2008                     | number    | number      |
| Yes      | numeric metric | 2009                     | 2009                     | number    | number      |
| Yes      | numeric metric | 2010                     | 2010                     | number    | number      |
| Yes      | numeric metric | 2011                     | 2011                     | number    | number      |
| Yes      | numeric metric | 2012                     | 2012                     | number    | number      |
| Yes      | numeric metric | 2013                     | 2013                     | number    | number      |
| Yes      | numeric metric | 2014                     | 2014                     | number    | number      |
| Yes      | numeric metric | 2015                     | 2015                     | number    | number      |
| Yes      | numeric metric | 2013_goal                | 2013 Goal                | number    | number      |
| Yes      | numeric metric | 2015_goal                | 2015 Goal                | number    | number      |
| No       |                | footnote                 | Footnote                 | text      | text        |
| Yes      | series tag     | note1                    | Note1                    | text      | text        |
| Yes      | series tag     | note2                    | Note2                    | text      | text        |
| Yes      | series tag     | note3                    | Note3                    | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = footnote
```

## Data Commands

```ls
series e:tsya-25ee d:2014-08-26T12:14:26.000Z t:best_management_practice="Cover Crops" t:note1="Tributary-specific goals have not been established." t:basin_name="Middle Potomac" m:2008=2131 m:2009=1704 m:2006=3946 m:2007=5901 m:2013=8002 m:2004=1035 m:2005=1710 m:2014=8019 m:2002=1 m:2003=1782 m:2012=7518 m:2011=6919 m:2010=2856 m:2001=1 m:2000=4060

series e:tsya-25ee d:2014-08-26T12:16:44.000Z t:best_management_practice="Cover Crops" t:note1="Tributary-specific goals have not been established." t:basin_name="Upper Potomac" m:2008=26625 m:2009=27412 m:2006=16759 m:2007=37306 m:2013=57580 m:2004=3965 m:2005=7048 m:2014=61586 m:2002=9327 m:2003=16622 m:2012=50643 m:2011=60914 m:2010=29096 m:2001=2934 m:2000=32990

series e:tsya-25ee d:2014-08-26T12:58:08.000Z t:best_management_practice="Manure Management Structures" t:note1="Tributary-specific goals have not been established." t:basin_name="Middle Potomac" m:2008=16 m:2009=19 m:2006=15 m:2007=16 m:2013=44 m:2004=13 m:2005=14 m:2014=44 m:2002=12 m:2003=12 m:2012=38 m:2011=34 m:2010=29 m:2001=11 m:2000=9
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

metric m:2011 p:double l:2011 t:dataTypeName=number

metric m:2012 p:double l:2012 t:dataTypeName=number

metric m:2013 p:double l:2013 t:dataTypeName=number

metric m:2014 p:double l:2014 t:dataTypeName=number

metric m:2015 p:integer l:2015 t:dataTypeName=number

metric m:2013_goal p:integer l:"2013 Goal" t:dataTypeName=number

metric m:2015_goal p:integer l:"2015 Goal" t:dataTypeName=number

entity e:tsya-25ee l:"BayStat Solutions Reporting - Maryland Dept. of Agriculture" t:attribution="Maryland Department of Agriculture" t:url=https://data.maryland.gov/api/views/tsya-25ee

property e:tsya-25ee t:meta.view v:id=tsya-25ee v:category="Energy and Environment" v:attributionLink=http://www.mda.state.md.us/ v:averageRating=0 v:name="BayStat Solutions Reporting - Maryland Dept. of Agriculture" v:attribution="Maryland Department of Agriculture"

property e:tsya-25ee t:meta.view.owner v:id=cs6p-bz62 v:profileImageUrlMedium=/api/users/cs6p-bz62/profile_images/THUMB v:profileImageUrlLarge=/api/users/cs6p-bz62/profile_images/LARGE v:screenName="data.maryland.gov Administration" v:profileImageUrlSmall=/api/users/cs6p-bz62/profile_images/TINY v:lastNotificationSeenAt=1491976108 v:displayName="data.maryland.gov Administration"

property e:tsya-25ee t:meta.view.tableauthor v:id=cs6p-bz62 v:profileImageUrlMedium=/api/users/cs6p-bz62/profile_images/THUMB v:profileImageUrlLarge=/api/users/cs6p-bz62/profile_images/LARGE v:screenName="data.maryland.gov Administration" v:profileImageUrlSmall=/api/users/cs6p-bz62/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1491976108 v:displayName="data.maryland.gov Administration"
```

## Top Records

```ls
| :updated_at | basin_name          | best_management_practice     | 2000  | 2001 | 2002 | 2003  | 2004 | 2005 | 2006  | 2007  | 2008  | 2009  | 2010  | 2011  | 2012  | 2013  | 2014  | 2015 | 2013_goal | 2015_goal | footnote                                                                  | note1                                               | note2 | note3 | 
| =========== | =================== | ============================ | ===== | ==== | ==== | ===== | ==== | ==== | ===== | ===== | ===== | ===== | ===== | ===== | ===== | ===== | ===== | ==== | ========= | ========= | ========================================================================= | =================================================== | ===== | ===== | 
| 1409055266  | Middle Potomac      | Cover Crops                  | 4060  | 1    | 1    | 1782  | 1035 | 1710 | 3946  | 5901  | 2131  | 1704  | 2856  | 6919  | 7518  | 8002  | 8019  |      |           |           |                                                                           | Tributary-specific goals have not been established. |       |       | 
| 1409055404  | Upper Potomac       | Cover Crops                  | 32990 | 2934 | 9327 | 16622 | 3965 | 7048 | 16759 | 37306 | 26625 | 27412 | 29096 | 60914 | 50643 | 57580 | 61586 |      |           |           |                                                                           | Tributary-specific goals have not been established. |       |       | 
| 1409057888  | Middle Potomac      | Manure Management Structures | 9     | 11   | 12   | 12    | 13   | 14   | 15    | 16    | 16    | 19    | 29    | 34    | 38    | 44    | 44    |      |           |           |                                                                           | Tributary-specific goals have not been established. |       |       | 
| 1409057911  | Patapsco Back River | Manure Management Structures | 71    | 75   | 80   | 81    | 85   | 92   | 97    | 99    | 102   | 116   | 120   | 123   | 132   | 140   | 140   |      |           |           |                                                                           | Tributary-specific goals have not been established. |       |       | 
| 1409055186  | Lower Potomac       | Cover Crops                  | 7737  | 1    | 1    | 4650  | 852  | 1643 | 4802  | 9340  | 6149  | 7045  | 5608  | 14375 | 12695 | 15177 | 12697 |      |           |           |                                                                           | Tributary-specific goals have not been established. |       |       | 
| 1409055229  | Lower Western Shore | Cover Crops                  | 717   | 1    | 1    | 1185  | 309  | 535  | 108   | 529   | 619   | 621   | 332   | 1081  | 1420  | 1641  | 1552  |      |           |           |                                                                           | Tributary-specific goals have not been established. |       |       | 
| 1409055299  | Patapsco Back River | Cover Crops                  | 3059  | 1    | 1    | 751   | 29   | 556  | 1225  | 5159  | 2152  | 2998  | 4605  | 5513  | 7615  | 5993  | 8024  |      |           |           |                                                                           | Tributary-specific goals have not been established. |       |       | 
| 1409056529  | Choptank            | Stream Protection            |       |      |      |       |      |      |       |       |       | 244   | 294   | 334   | 374   | 478   | 504   |      |           |           | There are limited opportunities for Stream Protection BMPs in this basin. | Tributary-specific goals have not been established. |       |       | 
| 1409057771  | Choptank            | Manure Management Structures | 46    | 189  | 194  | 196   | 204  | 209  | 216   | 233   | 238   | 251   | 258   | 261   | 268   | 270   | 279   |      |           |           |                                                                           | Tributary-specific goals have not been established. |       |       | 
| 1409057803  | Lower Eastern Shore | Manure Management Structures | 19    | 818  | 840  | 864   | 877  | 901  | 924   | 942   | 965   | 997   | 1009  | 1016  | 1033  | 1039  | 1050  |      |           |           |                                                                           | Tributary-specific goals have not been established. |       |       | 
```