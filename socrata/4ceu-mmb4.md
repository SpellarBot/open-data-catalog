# SSMMA New Market Tax Credit

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ssmma-new-market-tax-credit-1e817) |
| Metadata | [Link](https://data.illinois.gov/api/views/4ceu-mmb4) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/4ceu-mmb4/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/4ceu-mmb4/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | 4ceu-mmb4 |
| Name | SSMMA New Market Tax Credit |
| Attribution | South Suburban Mayors and Managers Association |
| Category | Municipality |
| Tags | economic development, planning |
| Created | 2012-11-27T17:48:19Z |
| Publication Date | 2012-11-27T19:12:10Z |

## Description

This dataset details 2010 census tracts eligible for New Market Tax Credits.

## Columns

```ls
| Included | Schema Type    | Field Name  | Name       | Data Type | Render Type |
| ======== | ============== | =========== | ========== | ========= | =========== |
| No       | time           | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag     | objectid    | OBJECTID   | text      | number      |
| Yes      | numeric metric | census_tra  | CENSUS_TRA | number    | number      |
| Yes      | series tag     | status      | STATUS     | text      | text        |
| Yes      | series tag     | distressed  | DISTRESSED | text      | text        |
| Yes      | series tag     | distress_1  | DISTRESS_1 | text      | text        |
| Yes      | series tag     | hot_zone    | HOT_ZONE   | text      | text        |
| Yes      | series tag     | type_of_ho  | TYPE_OF_HO | text      | text        |
| Yes      | numeric metric | median_fam  | MEDIAN_FAM | money     | money       |
| Yes      | series tag     | cdi_invest  | CDI_INVEST | text      | text        |
| Yes      | series tag     | distressd   | DISTRESSD_ | text      | text        |
| Yes      | series tag     | municipali  | MUNICIPALI | text      | text        |
| Yes      | series tag     | county      | COUNTY     | text      | text        |
| Yes      | series tag     | editor      | EDITOR     | text      | text        |
| Yes      | numeric metric | propreitar  | PROPREITAR | number    | number      |
| Yes      | series tag     | universal   | UNIVERSAL_ | text      | text        |
| Yes      | numeric metric | shape_leng  | SHAPE_Leng | number    | number      |
| Yes      | numeric metric | shape_area  | SHAPE_Area | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:4ceu-mmb4 d:2012-11-27T09:48:21.000Z t:distressed=Yes-56.3% t:editor=MJR t:type_of_ho="Economic Development and Housing Hot Zone" t:county="Cook County" t:status=Qualified t:cdi_invest=Yes t:hot_zone=Yes t:universal=UR1 t:objectid=1 t:distressd=Qualified t:municipali=Riverdale t:distress_1=Yes-33.5% m:shape_area=57013406.6607 m:shape_leng=39870.3692539 m:census_tra=17031540102 m:propreitar=1 m:median_fam=13979

series e:4ceu-mmb4 d:2012-11-27T09:48:21.000Z t:distressed=Yes-56.3% t:editor=MJR t:type_of_ho="Economic Development and Housing Hot Zone" t:county="Cook County" t:status=Qualified t:cdi_invest=Yes t:hot_zone=Yes t:universal=UR2 t:objectid=2 t:distressd=Qualified t:municipali=Riverdale t:distress_1=Yes-33.5% m:shape_area=41617739.3692 m:shape_leng=34175.1068898 m:census_tra=17031540101 m:propreitar=2 m:median_fam=13979

series e:4ceu-mmb4 d:2012-11-27T09:48:21.000Z t:distressed=Yes-35.8% t:editor=MJR t:type_of_ho="Economic Development and Housing Hot Zone" t:county="Cook County" t:status=Qualified t:cdi_invest=Yes t:hot_zone=Yes t:universal=UR3 t:objectid=3 t:distressd="Meets Some Distressed Community Standards" t:municipali=Riverdale t:distress_1=Yes-17.9% m:shape_area=49704079.7777 m:shape_leng=40643.5486884 m:census_tra=17031821500 m:propreitar=3 m:median_fam=27917
```

## Meta Commands

```ls
metric m:census_tra p:long l:CENSUS_TRA t:dataTypeName=number

metric m:median_fam p:double l:MEDIAN_FAM t:dataTypeName=money

metric m:propreitar p:integer l:PROPREITAR t:dataTypeName=number

metric m:shape_leng p:double l:SHAPE_Leng t:dataTypeName=number

metric m:shape_area p:double l:SHAPE_Area t:dataTypeName=number

entity e:4ceu-mmb4 l:"SSMMA New Market Tax Credit" t:attribution="South Suburban Mayors and Managers Association" t:url=https://data.illinois.gov/api/views/4ceu-mmb4

property e:4ceu-mmb4 t:meta.view v:id=4ceu-mmb4 v:category=Municipality v:attributionLink=http://www.ssmma.org v:averageRating=0 v:name="SSMMA New Market Tax Credit" v:attribution="South Suburban Mayors and Managers Association"

property e:4ceu-mmb4 t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:4ceu-mmb4 t:meta.view.owner v:id=p88s-rkzf v:profileImageUrlMedium=/api/users/p88s-rkzf/profile_images/THUMB v:profileImageUrlLarge=/api/users/p88s-rkzf/profile_images/LARGE v:screenName=mrizzitiello v:profileImageUrlSmall=/api/users/p88s-rkzf/profile_images/TINY v:displayName=mrizzitiello

property e:4ceu-mmb4 t:meta.view.tableauthor v:id=74c3-ka9x v:profileImageUrlMedium=/api/users/74c3-ka9x/profile_images/THUMB v:profileImageUrlLarge=/api/users/74c3-ka9x/profile_images/LARGE v:screenName="Rey de Castro" v:profileImageUrlSmall=/api/users/74c3-ka9x/profile_images/TINY v:roleName=publisher v:displayName="Rey de Castro"
```

## Top Records

```ls
| :updated_at | objectid | census_tra  | status      | distressed | distress_1 | hot_zone | type_of_ho                                | median_fam | cdi_invest | distressd                                 | municipali    | county      | editor | propreitar | universal | shape_leng    | shape_area    | 
| =========== | ======== | =========== | =========== | ========== | ========== | ======== | ========================================= | ========== | ========== | ========================================= | ============= | =========== | ====== | ========== | ========= | ============= | ============= | 
| 1354009701  | 1        | 17031540102 | Qualified   | Yes-56.3%  | Yes-33.5%  | Yes      | Economic Development and Housing Hot Zone | 13979.00   | Yes        | Qualified                                 | Riverdale     | Cook County | MJR    | 1          | UR1       | 39870.3692539 | 57013406.6607 | 
| 1354009701  | 2        | 17031540101 | Qualified   | Yes-56.3%  | Yes-33.5%  | Yes      | Economic Development and Housing Hot Zone | 13979.00   | Yes        | Qualified                                 | Riverdale     | Cook County | MJR    | 2          | UR2       | 34175.1068898 | 41617739.3692 | 
| 1354009701  | 3        | 17031821500 | Qualified   | Yes-35.8%  | Yes-17.9%  | Yes      | Economic Development and Housing Hot Zone | 27917.00   | Yes        | Meets Some Distressed Community Standards | Riverdale     | Cook County | MJR    | 3          | UR3       | 40643.5486884 | 49704079.7777 | 
| 1354009701  | 4        | 17031826800 | Qualified   | No-25.6%   | Yes-16.2%  | Yes      | Economic Development and Housing Hot Zone | 31135.00   | Yes        | Meets Some Distressed Community Standards | Riverdale     | Cook County | MJR    | 4          | UR4       | 48843.0717214 | 85926152.2519 | 
| 1354009701  | 5        | 17031826700 | Qualified   | No-16.6%   | No-15.0%   | Yes      | Housing Hot Zone                          | 40610.00   | Yes        | Not Qualified                             | Riverdale     | Cook County | MJR    | 5          | UR5       | 18319.9352627 | 11997855.9986 | 
| 1354009701  | 6        | 17031826600 | Unqualified | No-11.4%   | No-7.3%    | No       | No                                        | 49776.00   | No         | No                                        | Riverdale     | Cook County | MJR    | 6          | UR6       | 17225.095971  | 16280366.5793 | 
| 1354009701  | 7        | 17031826500 | Unqualified | No-8.9%    | No-7.4%    | No       | No                                        | 51016.00   | No         | No                                        | Dolton        | Cook County | MJR    | 7          | UR7       | 31789.0635252 | 38663805.8992 | 
| 1354009701  | 8        | 17031826401 | Unqualified | No-8.7%    | No-5.1%    | No       | No                                        | 55906.00   | No         | No                                        | Dolton        | Cook County | MJR    | 8          | UR8       | 31174.7358292 | 34969826.6606 | 
| 1354009701  | 9        | 17031826402 | Unqualified | No-8.9%    | No-7.2%    | No       | No                                        | 52500.00   | No         | No                                        | Dolton        | Cook County | MJR    | 9          | UR9       | 25104.4821601 | 21747263.1645 | 
| 1354009701  | 10       | 17031826303 | Unqualified | No-9.4%    | No-7.2%    | No       | No                                        | 58406.00   | No         | No                                        | South Holland | Cook County | MJR    | 10         | UR10      | 18262.7397474 | 16799436.176  | 
```