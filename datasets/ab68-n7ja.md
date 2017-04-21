# BayStat Solutions Reporting - Maryland Dept. of the Environment

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/baystat-solutions-reporting-maryland-dept-of-the-environment) |
| Metadata | [Link](https://data.maryland.gov/api/views/ab68-n7ja) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/ab68-n7ja/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/ab68-n7ja/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | ab68-n7ja |
| Name | BayStat Solutions Reporting - Maryland Dept. of the Environment |
| Attribution | Maryland Department of the Environment |
| Category | Energy and Environment |
| Tags | chesapeake, bay, baystat, solutions, basin, bmp, best, management, practice |
| Created | 2014-02-07T16:03:28Z |
| Publication Date | 2015-07-28T21:26:36Z |

## Description

Chesapeake Bay restoration solutions, Best Management Practices (BMPs), progress reporting by tributary basin. See the BayStat Solutions Reference table for further definition.

## Columns

```ls
| Included | Schema Type    | Field Name               | Name                     | Data Type | Render Type |
| ======== | ============== | ======================== | ======================== | ========= | =========== |
| No       | time           | :updated_at              | updated_at               | meta_data | meta_data   |
| Yes      | series tag     | basin_name               | Basin Name               | text      | text        |
| Yes      | series tag     | best_management_practice | Best Management Practice | text      | text        |
| Yes      | series tag     | 2000                     | 2000                     | text      | text        |
| Yes      | series tag     | 2001                     | 2001                     | text      | text        |
| Yes      | series tag     | 2002                     | 2002                     | text      | text        |
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
series e:ab68-n7ja d:2014-02-18T08:27:56.000Z t:best_management_practice="Wastewater Treatment Plants ENR" t:note3="Updated January 2014" t:note1="Tributary-specific goals have not been established." t:note2="2014 progress for each tributary basin will be updated at the end of the calendar year." t:basin_name=Choptank m:2008=1 m:2009=1 m:2007=1 m:2013=2 m:2014=3 m:2012=2 m:2011=1 m:2010=1

series e:ab68-n7ja d:2014-02-18T08:27:56.000Z t:best_management_practice="Stormwater Runoff Management Retrofits" t:note3="Updated January 2014" t:note1="Tributary-specific goals have not been established." t:note2="2014 progress for each tributary basin will be reported at the end of the calendar year." t:basin_name=Choptank m:2008=610 m:2009=2427 m:2006=610 m:2007=610 m:2004=584 m:2013=2562 m:2005=610 m:2003=584 m:2012=2562 m:2011=2562 m:2010=2562

series e:ab68-n7ja d:2014-02-18T08:27:56.000Z t:best_management_practice="Septic Retrofits" t:note3="Updated January 2014" t:note1="Tributary-specific goals have not been established." t:note2="2014 progress for each tributary basin will be reported at the end of the calendar year." t:basin_name=Choptank m:2008=63 m:2009=138 m:2013=379 m:2012=309 m:2011=252 m:2010=193
```

## Meta Commands

```ls
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

metric m:2014 p:integer l:2014 t:dataTypeName=number

metric m:2015 p:integer l:2015 t:dataTypeName=number

metric m:2013_goal p:integer l:"2013 Goal" t:dataTypeName=number

metric m:2015_goal p:integer l:"2015 Goal" t:dataTypeName=number

entity e:ab68-n7ja l:"BayStat Solutions Reporting - Maryland Dept. of the Environment" t:attribution="Maryland Department of the Environment" t:url=https://data.maryland.gov/api/views/ab68-n7ja

property e:ab68-n7ja t:meta.view v:id=ab68-n7ja v:category="Energy and Environment" v:attributionLink=http://www.mde.state.md.us/ v:averageRating=0 v:name="BayStat Solutions Reporting - Maryland Dept. of the Environment" v:attribution="Maryland Department of the Environment"

property e:ab68-n7ja t:meta.view.owner v:id=2ryv-bq8b v:profileImageUrlMedium=/api/users/2ryv-bq8b/profile_images/THUMB v:profileImageUrlLarge=/api/users/2ryv-bq8b/profile_images/LARGE v:screenName=ESRGC v:profileImageUrlSmall=/api/users/2ryv-bq8b/profile_images/TINY v:displayName=ESRGC

property e:ab68-n7ja t:meta.view.tableauthor v:id=2ryv-bq8b v:profileImageUrlMedium=/api/users/2ryv-bq8b/profile_images/THUMB v:profileImageUrlLarge=/api/users/2ryv-bq8b/profile_images/LARGE v:screenName=ESRGC v:profileImageUrlSmall=/api/users/2ryv-bq8b/profile_images/TINY v:roleName=editor v:displayName=ESRGC
```

## Top Records

```ls
| :updated_at | basin_name          | best_management_practice               | 2000 | 2001 | 2002 | 2003 | 2004 | 2005 | 2006 | 2007 | 2008 | 2009 | 2010 | 2011 | 2012 | 2013 | 2014 | 2015 | 2013_goal | 2015_goal | footnote                                               | note1                                               | note2                                                                                    | note3                | 
| =========== | =================== | ====================================== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ========= | ========= | ====================================================== | =================================================== | ======================================================================================== | ==================== | 
| 1392712076  | Choptank            | Wastewater Treatment Plants ENR        |      |      |      |      |      |      |      | 1    | 1    | 1    | 1    | 1    | 2    | 2    | 3    |      |           |           | One WWTP was upgraded to ENR in this basin in 2007.    | Tributary-specific goals have not been established. | 2014 progress for each tributary basin will be updated at the end of the calendar year.  | Updated January 2014 | 
| 1392712076  | Choptank            | Stormwater Runoff Management Retrofits |      |      |      | 584  | 584  | 610  | 610  | 610  | 610  | 2427 | 2562 | 2562 | 2562 | 2562 |      |      |           |           | This is a new program that began in 2003.              | Tributary-specific goals have not been established. | 2014 progress for each tributary basin will be reported at the end of the calendar year. | Updated January 2014 | 
| 1392712076  | Choptank            | Septic Retrofits                       |      |      |      |      |      |      |      |      | 63   | 138  | 193  | 252  | 309  | 379  |      |      |           |           | Maryland's septic retrofit program began in 2008.      | Tributary-specific goals have not been established. | 2014 progress for each tributary basin will be reported at the end of the calendar year. | Updated January 2014 | 
| 1392712076  | Choptank            | Air Pollution Reductions               |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |           |           | Local air pollution reduction goals are not available. | Tributary-specific goals have not been established. | 2014 progress for each tributary basin will be reported at the end of the calendar year. | Updated January 2014 | 
| 1392712076  | Lower Eastern Shore | Wastewater Treatment Plants ENR        |      |      |      |      |      |      | 1    | 1    | 1    | 1    | 1    | 3    | 4    | 5    | 5    |      |           |           | The first WWTPs were upgraded to ENR in 2006.          | Tributary-specific goals have not been established. | 2014 progress for each tributary basin will be updated at the end of the calendar year.  | Updated January 2014 | 
| 1392712076  | Lower Eastern Shore | Stormwater Runoff Management Retrofits |      |      |      | 457  | 607  | 613  | 1050 | 1050 | 1050 | 1053 | 1082 | 1082 | 1082 | 1082 |      |      |           |           | This is a new program that began in 2003.              | Tributary-specific goals have not been established. | 2014 progress for each tributary basin will be reported at the end of the calendar year. | Updated January 2014 | 
| 1392712076  | Lower Eastern Shore | Septic Retrofits                       |      |      |      |      |      |      |      |      | 55   | 408  | 780  | 895  | 1001 | 1092 |      |      |           |           | Maryland's septic retrofit program began in 2008.      | Tributary-specific goals have not been established. | 2014 progress for each tributary basin will be reported at the end of the calendar year. | Updated January 2014 | 
| 1392712076  | Lower Eastern Shore | Air Pollution Reductions               |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |           |           | Local air pollution reduction goals are not available. | Tributary-specific goals have not been established. | 2014 progress for each tributary basin will be reported at the end of the calendar year. | Updated January 2014 | 
| 1392712076  | Lower Potomac       | Wastewater Treatment Plants ENR        |      |      |      |      |      |      |      | 1    | 2    | 3    | 3    | 3    | 3    | 3    | 3    |      |           |           | The first WWTPs were upgraded to ENR in 2006.          | Tributary-specific goals have not been established. | 2014 progress for each tributary basin will be updated at the end of the calendar year.  | Updated January 2014 | 
| 1392712076  | Lower Potomac       | Stormwater Runoff Management Retrofits |      |      |      | 476  | 720  | 963  | 1207 | 1450 | 1694 | 2186 | 2481 | 2492 | 2808 | 2847 |      |      |           |           | This is a new program that began in 2003.              | Tributary-specific goals have not been established. | 2014 progress for each tributary basin will be reported at the end of the calendar year. | Updated January 2014 | 
```