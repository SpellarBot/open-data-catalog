# Category Page Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/category-page-data-e863a) |
| Metadata | [Link](https://data.lacity.org/api/views/vq5t-iz3j) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/vq5t-iz3j/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/vq5t-iz3j/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | vq5t-iz3j |
| Name | Category Page Data |
| Tags | socrata, homepage |
| Created | 2014-04-01T22:12:48Z |
| Publication Date | 2014-05-29T22:46:30Z |

## Description

This is one of several datasets used to customize the data.lacity homepage

## Columns

```ls
| Included | Schema Type    | Field Name  | Name       | Data Type | Render Type |
| ======== | ============== | =========== | ========== | ========= | =========== |
| No       | time           | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | numeric metric | sort        | Sort       | number    | number      |
| Yes      | series tag     | text        | Text       | text      | text        |
| Yes      | series tag     | icon        | Icon       | photo     | photo       |
| Yes      | series tag     | link        | Link       | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:vq5t-iz3j d:2014-05-28T14:56:09.000Z t:icon=gKL4PRziRgxILqi-Eb8h-9o8zdTalZnkSCOpfiJoKxY t:text="Economic Data" t:link="/A Prosperous City" m:sort=3

series e:vq5t-iz3j d:2014-05-28T14:56:16.000Z t:icon=0oG_CSNEBSR5QTkHJQRAeyztrbAw383dED_ncFkKVGs t:text="Livability Data" t:link="/A Livable and Sustainable City" m:sort=2

series e:vq5t-iz3j d:2014-05-28T14:56:21.000Z t:icon=IclsUHXI600JVpxNiAEk9l1zh550k63KOgtuSSAfnJ0 t:text="Public Safety Data" t:link="/A Safe City" m:sort=1
```

## Meta Commands

```ls
metric m:sort p:integer l:Sort t:dataTypeName=number

entity e:vq5t-iz3j l:"Category Page Data" t:url=https://data.lacity.org/api/views/vq5t-iz3j

property e:vq5t-iz3j t:meta.view v:id=vq5t-iz3j v:averageRating=0 v:name="Category Page Data"

property e:vq5t-iz3j t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:vq5t-iz3j t:meta.view.owner v:id=vcvp-yass v:profileImageUrlMedium=/api/users/vcvp-yass/profile_images/THUMB v:profileImageUrlLarge=/api/users/vcvp-yass/profile_images/LARGE v:screenName="Dylan Bussone" v:profileImageUrlSmall=/api/users/vcvp-yass/profile_images/TINY v:displayName="Dylan Bussone"

property e:vq5t-iz3j t:meta.view.tableauthor v:id=vcvp-yass v:profileImageUrlMedium=/api/users/vcvp-yass/profile_images/THUMB v:profileImageUrlLarge=/api/users/vcvp-yass/profile_images/LARGE v:screenName="Dylan Bussone" v:profileImageUrlSmall=/api/users/vcvp-yass/profile_images/TINY v:displayName="Dylan Bussone"
```

## Top Records

```ls
| :updated_at | sort | text                       | icon                                        | link                            | 
| =========== | ==== | ========================== | =========================================== | =============================== | 
| 1401288969  | 3    | Economic Data              | gKL4PRziRgxILqi-Eb8h-9o8zdTalZnkSCOpfiJoKxY | /A Prosperous City              | 
| 1401288976  | 2    | Livability Data            | 0oG_CSNEBSR5QTkHJQRAeyztrbAw383dED_ncFkKVGs | /A Livable and Sustainable City | 
| 1401288981  | 1    | Public Safety Data         | IclsUHXI600JVpxNiAEk9l1zh550k63KOgtuSSAfnJ0 | /A Safe City                    | 
| 1401288989  | 4    | Government Efficiency Data | zYWr0zDsQT1XGXZvRLMuW0Pxbhb5Si1rHSv9hPRYQ7E | /A Well Run City                | 
| 1401378379  | 5    | Developer Resources        | hWt8FaxrBzo1QxKVMHrwhmzgLnJw3aVY07vNiPXU-k4 | /developers                     | 
```