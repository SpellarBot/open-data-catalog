# BayStat Solutions Reporting - Maryland Dept. of Natural Resources

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/baystat-solutions-reporting-maryland-dept-of-natural-resources-36f7f) |
| Metadata | [Link](https://data.maryland.gov/api/views/4zqs-i2t2) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/4zqs-i2t2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/4zqs-i2t2/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | 4zqs-i2t2 |
| Name | BayStat Solutions Reporting - Maryland Dept. of Natural Resources |
| Attribution | Maryland Department of Natural Resources |
| Category | Energy and Environment |
| Tags | chesapeake, bay, baystat, solutions, basin, bmp, best, management, practice |
| Created | 2014-02-07T15:52:45Z |
| Publication Date | 2015-03-27T18:02:46Z |

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
series e:4zqs-i2t2 d:2014-02-25T11:09:36.000Z t:best_management_practice="CREP Permanent Easements" t:note1="Tributary-specific goals have not been established." t:basin_name=Choptank m:2013=297 m:2012=297 m:2011=206

series e:4zqs-i2t2 d:2014-02-25T12:00:20.000Z t:best_management_practice="Rural Legacy" t:note1="Tributary-specific goals have not been established." t:basin_name=Choptank m:2008=2986 m:2009=2986 m:2006=2986 m:2007=2986 m:2004=2774 m:2013=3484 m:2005=2774 m:2002=1158 m:2003=2232 m:2012=3484 m:2011=3484 m:2010=3484 m:2001=417

series e:4zqs-i2t2 d:2014-02-25T12:00:23.000Z t:best_management_practice="Maryland Environmental Trust" t:note1="Tributary-specific goals have not been established." t:basin_name=Choptank m:2008=6880 m:2009=7106 m:2006=5589 m:2007=6178 m:2004=4773 m:2013=7572 m:2005=4950 m:2002=2924 m:2003=4395 m:2012=7140 m:2011=7140 m:2010=7140 m:2001=1596
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

metric m:2009 p:double l:2009 t:dataTypeName=number

metric m:2010 p:double l:2010 t:dataTypeName=number

metric m:2011 p:double l:2011 t:dataTypeName=number

metric m:2012 p:double l:2012 t:dataTypeName=number

metric m:2013 p:double l:2013 t:dataTypeName=number

metric m:2014 p:double l:2014 t:dataTypeName=number

metric m:2015 p:integer l:2015 t:dataTypeName=number

metric m:2013_goal p:integer l:"2013 Goal" t:dataTypeName=number

metric m:2015_goal p:integer l:"2015 Goal" t:dataTypeName=number

entity e:4zqs-i2t2 l:"BayStat Solutions Reporting - Maryland Dept. of Natural Resources" t:attribution="Maryland Department of Natural Resources" t:url=https://data.maryland.gov/api/views/4zqs-i2t2

property e:4zqs-i2t2 t:meta.view v:id=4zqs-i2t2 v:category="Energy and Environment" v:attributionLink=http://www.dnr.state.md.us/ v:averageRating=0 v:name="BayStat Solutions Reporting - Maryland Dept. of Natural Resources" v:attribution="Maryland Department of Natural Resources"

property e:4zqs-i2t2 t:meta.view.owner v:id=2ryv-bq8b v:profileImageUrlMedium=/api/users/2ryv-bq8b/profile_images/THUMB v:profileImageUrlLarge=/api/users/2ryv-bq8b/profile_images/LARGE v:screenName=ESRGC v:profileImageUrlSmall=/api/users/2ryv-bq8b/profile_images/TINY v:displayName=ESRGC

property e:4zqs-i2t2 t:meta.view.tableauthor v:id=2ryv-bq8b v:profileImageUrlMedium=/api/users/2ryv-bq8b/profile_images/THUMB v:profileImageUrlLarge=/api/users/2ryv-bq8b/profile_images/LARGE v:screenName=ESRGC v:profileImageUrlSmall=/api/users/2ryv-bq8b/profile_images/TINY v:roleName=editor v:displayName=ESRGC
```

## Top Records

```ls
| :updated_at | basin_name          | best_management_practice       | 2000 | 2001 | 2002 | 2003 | 2004 | 2005 | 2006 | 2007 | 2008 | 2009  | 2010  | 2011  | 2012  | 2013  | 2014  | 2015 | 2013_goal | 2015_goal | footnote                                           | note1                                               | note2 | note3 | 
| =========== | =================== | ============================== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ===== | ===== | ===== | ===== | ===== | ===== | ==== | ========= | ========= | ================================================== | =================================================== | ===== | ===== | 
| 1393326576  | Choptank            | CREP Permanent Easements       |      |      |      |      |      |      |      |      |      |       |       | 206   | 297   | 297   |       |      |           |           | Tributary-specific data is only available to 2011. | Tributary-specific goals have not been established. |       |       | 
| 1393329620  | Choptank            | Rural Legacy                   |      | 417  | 1158 | 2232 | 2774 | 2774 | 2986 | 2986 | 2986 | 2986  | 3484  | 3484  | 3484  | 3484  |       |      |           |           | Tributary-specific data is only available to 2001  | Tributary-specific goals have not been established. |       |       | 
| 1393329623  | Choptank            | Maryland Environmental Trust   |      | 1596 | 2924 | 4395 | 4773 | 4950 | 5589 | 6178 | 6880 | 7106  | 7140  | 7140  | 7140  | 7572  |       |      |           |           | Tributary-specific data is only available to 2001  | Tributary-specific goals have not been established. |       |       | 
| 1393329629  | Choptank            | Natural Filters on Public Land |      |      |      |      |      |      |      |      |      | 4.2   | 4.2   | 4.2   | 74.2  | 84.2  | 91.7  |      |           |           | This is a new program beginning in 2009.           | Tributary-specific goals have not been established. |       |       | 
| 1393329633  | Choptank            | Program Open Space             |      |      |      |      |      |      |      | 67   | 102  | 102   | 102   | 102   | 1052  | 1092  |       |      |           |           | Tributary-specific data is only available to 2005  | Tributary-specific goals have not been established. |       |       | 
| 1393329635  | Lower Eastern Shore | Program Open Space             |      |      |      |      |      | 1485 | 2467 | 4479 | 4755 | 12922 | 15211 | 17345 | 17345 | 19025 |       |      |           |           | Tributary-specific data is only available to 2005  | Tributary-specific goals have not been established. |       |       | 
| 1393329638  | Lower Eastern Shore | CREP Permanent Easements       |      |      |      |      |      |      |      |      |      |       |       | 945   | 1466  | 1567  |       |      |           |           | Tributary-specific data is only available to 2011. | Tributary-specific goals have not been established. |       |       | 
| 1393329641  | Lower Eastern Shore | Rural Legacy                   |      | 846  | 3444 | 5147 | 7580 | 7879 | 8110 | 8288 | 9687 | 10781 | 12252 | 14070 | 15641 | 15767 |       |      |           |           | Tributary-specific data is only available to 2001  | Tributary-specific goals have not been established. |       |       | 
| 1393329643  | Lower Eastern Shore | Maryland Environmental Trust   |      | 674  | 3650 | 5310 | 5688 | 5945 | 6168 | 6887 | 7960 | 8667  | 9312  | 9401  | 9401  | 9627  |       |      |           |           | Tributary-specific data is only available to 2001  | Tributary-specific goals have not been established. |       |       | 
| 1393329651  | Lower Eastern Shore | Natural Filters on Public Land |      |      |      |      |      |      |      |      |      | 773.9 | 874.8 | 909.2 | 910.2 | 975.3 | 975.8 |      |           |           | This is a new program beginning in 2009.           | Tributary-specific goals have not been established. |       |       | 
```