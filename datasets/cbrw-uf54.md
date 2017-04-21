# Home Page - Quick Links

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/home-page-quick-links-5d6c0) |
| Metadata | [Link](https://data.lacity.org/api/views/cbrw-uf54) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/cbrw-uf54/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/cbrw-uf54/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | cbrw-uf54 |
| Name | Home Page - Quick Links |
| Tags | socrata, homepage |
| Created | 2014-04-01T21:23:06Z |
| Publication Date | 2014-05-30T19:11:14Z |

## Description

This is one of several datasets used to customized the data.lacity homepage

## Columns

```ls
| Included | Schema Type    | Field Name  | Name       | Data Type | Render Type |
| ======== | ============== | =========== | ========== | ========= | =========== |
| No       | time           | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | numeric metric | sort        | Sort       | number    | number      |
| Yes      | series tag     | text        | Text       | text      | text        |
| Yes      | series tag     | image       | Image      | photo     | photo       |
| Yes      | series tag     | link        | Link       | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:cbrw-uf54 d:2014-05-30T10:24:39.000Z t:text="Featured App: City of LA Event Finder" t:link=/event-explorer-list t:image=ck-A9PxwVRYeXy6g6YUhzgMvcq7vE5GiT64gjk36Jzs m:sort=3

series e:cbrw-uf54 d:2014-05-30T10:42:38.000Z t:text="Mayor's Executive Directive on Open Data" t:link=http://www.lamayor.org/garcetti_directs_city_departments_to_collect_data_for_open_data_initiative t:image=4d09GuWBoRWEwBum9ebxLJ9-bAfA6F_psk-d5KdFKfw m:sort=2

series e:cbrw-uf54 d:2014-05-30T12:11:13.000Z t:text="Back to Basics: Performance Metrics" t:link=https://performance.lacity.org t:image=pKwY7LIr4YJAwlNvTYBSDP1wrGnEnikdxQPqDUCimyo m:sort=1
```

## Meta Commands

```ls
metric m:sort p:integer l:Sort t:dataTypeName=number

entity e:cbrw-uf54 l:"Home Page - Quick Links" t:url=https://data.lacity.org/api/views/cbrw-uf54

property e:cbrw-uf54 t:meta.view v:id=cbrw-uf54 v:averageRating=0 v:name="Home Page - Quick Links"

property e:cbrw-uf54 t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:cbrw-uf54 t:meta.view.owner v:id=vcvp-yass v:profileImageUrlMedium=/api/users/vcvp-yass/profile_images/THUMB v:profileImageUrlLarge=/api/users/vcvp-yass/profile_images/LARGE v:screenName="Dylan Bussone" v:profileImageUrlSmall=/api/users/vcvp-yass/profile_images/TINY v:displayName="Dylan Bussone"

property e:cbrw-uf54 t:meta.view.tableauthor v:id=vcvp-yass v:profileImageUrlMedium=/api/users/vcvp-yass/profile_images/THUMB v:profileImageUrlLarge=/api/users/vcvp-yass/profile_images/LARGE v:screenName="Dylan Bussone" v:profileImageUrlSmall=/api/users/vcvp-yass/profile_images/TINY v:displayName="Dylan Bussone"
```

## Top Records

```ls
| :updated_at | sort | text                                     | image                                       | link                                                                                              | 
| =========== | ==== | ======================================== | =========================================== | ================================================================================================= | 
| 1401445479  | 3    | Featured App: City of LA Event Finder    | ck-A9PxwVRYeXy6g6YUhzgMvcq7vE5GiT64gjk36Jzs | /event-explorer-list                                                                              | 
| 1401446558  | 2    | Mayor's Executive Directive on Open Data | 4d09GuWBoRWEwBum9ebxLJ9-bAfA6F_psk-d5KdFKfw | http://www.lamayor.org/garcetti_directs_city_departments_to_collect_data_for_open_data_initiative | 
| 1401451873  | 1    | Back to Basics: Performance Metrics      | pKwY7LIr4YJAwlNvTYBSDP1wrGnEnikdxQPqDUCimyo | https://performance.lacity.org                                                                    | 
```