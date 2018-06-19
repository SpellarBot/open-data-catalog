# Libraries - 2016 Circulation by Location

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/libraries-2016-circulation-by-location) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/acer-3nmf) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/acer-3nmf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/acer-3nmf/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | acer-3nmf |
| Name | Libraries - 2016 Circulation by Location |
| Tags | libraries, circulation, performance metrics |
| Created | 2016-02-11T21:56:00Z |
| Publication Date | 2017-01-13T17:19:19Z |

## Description

Circulation figures include new checkouts as well as renewals. The Chicago Public Library consists of the Harold Washington Library Center, Sulzer and Woodson regional libraries and over 70 neighborhood branches. Many locations experience sporadic emergency closures due to heating or air conditioning issues, or area power outages. Independence Branch closed due to a fire on 10/30/15.

## Columns

```ls
| Included | Schema Type    | Field Name | Name      | Data Type | Render Type |
| ======== | ============== | ========== | ========= | ========= | =========== |
| Yes      | series tag     | location   | LOCATION  | text      | text        |
| Yes      | numeric metric | january    | JANUARY   | number    | number      |
| Yes      | numeric metric | february   | FEBRUARY  | number    | number      |
| Yes      | numeric metric | march      | MARCH     | number    | number      |
| Yes      | numeric metric | april      | APRIL     | number    | number      |
| Yes      | numeric metric | may        | MAY       | number    | number      |
| Yes      | numeric metric | june       | JUNE      | number    | number      |
| Yes      | numeric metric | july       | JULY      | number    | number      |
| Yes      | numeric metric | august     | AUGUST    | number    | number      |
| Yes      | numeric metric | september  | SEPTEMBER | number    | number      |
| Yes      | numeric metric | october    | OCTOBER   | number    | number      |
| Yes      | numeric metric | november   | NOVEMBER  | number    | number      |
| Yes      | numeric metric | december   | DECEMBER  | number    | number      |
| Yes      | numeric metric | ytd        | YTD       | number    | number      |
```

## Time Field

```ls
Value = 2016
Format & Zone = yyyy
```

## Data Commands

```ls
series e:acer-3nmf d:2016-01-01T00:00:00.000Z t:location="Albany Park" m:december=8933 m:november=11864 m:may=9796 m:march=12333 m:april=11987 m:february=10989 m:june=11707 m:january=10905 m:ytd=135858 m:august=12190 m:july=11878 m:october=12446 m:september=10830

series e:acer-3nmf d:2016-01-01T00:00:00.000Z t:location=Altgeld m:december=388 m:november=389 m:may=405 m:march=509 m:april=525 m:february=568 m:june=400 m:january=678 m:ytd=5864 m:august=600 m:july=333 m:october=537 m:september=532

series e:acer-3nmf d:2016-01-01T00:00:00.000Z t:location="Archer Heights" m:december=5067 m:november=5981 m:may=5728 m:march=7483 m:april=6971 m:february=6788 m:june=6306 m:january=6922 m:ytd=75818 m:august=6057 m:july=5855 m:october=6483 m:september=6177
```

## Meta Commands

```ls
metric m:january p:integer l:JANUARY t:dataTypeName=number

metric m:february p:integer l:FEBRUARY t:dataTypeName=number

metric m:march p:integer l:MARCH t:dataTypeName=number

metric m:april p:integer l:APRIL t:dataTypeName=number

metric m:may p:integer l:MAY t:dataTypeName=number

metric m:june p:integer l:JUNE t:dataTypeName=number

metric m:july p:integer l:JULY t:dataTypeName=number

metric m:august p:integer l:AUGUST t:dataTypeName=number

metric m:september p:integer l:SEPTEMBER t:dataTypeName=number

metric m:october p:integer l:OCTOBER t:dataTypeName=number

metric m:november p:integer l:NOVEMBER t:dataTypeName=number

metric m:december p:integer l:DECEMBER t:dataTypeName=number

metric m:ytd p:integer l:YTD t:dataTypeName=number

entity e:acer-3nmf l:"Libraries -  2016 Circulation by Location" t:url=https://data.cityofchicago.org/api/views/acer-3nmf

property e:acer-3nmf t:meta.view v:id=acer-3nmf v:averageRating=0 v:name="Libraries -  2016 Circulation by Location"

property e:acer-3nmf t:meta.view.owner v:id=vedk-n2zt v:profileImageUrlMedium=/api/users/vedk-n2zt/profile_images/THUMB v:profileImageUrlLarge=/api/users/vedk-n2zt/profile_images/LARGE v:screenName="Marie E. Hardy" v:profileImageUrlSmall=/api/users/vedk-n2zt/profile_images/TINY v:displayName="Marie E. Hardy"

property e:acer-3nmf t:meta.view.tableauthor v:id=vedk-n2zt v:profileImageUrlMedium=/api/users/vedk-n2zt/profile_images/THUMB v:profileImageUrlLarge=/api/users/vedk-n2zt/profile_images/LARGE v:screenName="Marie E. Hardy" v:profileImageUrlSmall=/api/users/vedk-n2zt/profile_images/TINY v:roleName=editor v:displayName="Marie E. Hardy"
```

## Top Records

```ls
| location          | january | february | march | april | may  | june  | july  | august | september | october | november | december | ytd    | 
| ================= | ======= | ======== | ===== | ===== | ==== | ===== | ===== | ====== | ========= | ======= | ======== | ======== | ====== | 
| Albany Park       | 10905   | 10989    | 12333 | 11987 | 9796 | 11707 | 11878 | 12190  | 10830     | 12446   | 11864    | 8933     | 135858 | 
| Altgeld           | 678     | 568      | 509   | 525   | 405  | 400   | 333   | 600    | 532       | 537     | 389      | 388      | 5864   | 
| Archer Heights    | 6922    | 6788     | 7483  | 6971  | 5728 | 6306  | 5855  | 6057   | 6177      | 6483    | 5981     | 5067     | 75818  | 
| Austin            | 1984    | 1901     | 1885  | 1847  | 1566 | 1776  | 1786  | 1919   | 1638      | 1693    | 1772     | 1505     | 21272  | 
| Austin-Irving     | 9778    | 10030    | 11160 | 10556 | 8512 | 10115 | 10368 | 10589  | 9482      | 9949    | 9058     | 8423     | 118020 | 
| Avalon            | 4274    | 3874     | 3986  | 4069  | 3254 | 3725  | 4254  | 4578   | 3816      | 3896    | 4203     | 3773     | 47702  | 
| Back of the Yards | 3222    | 3923     | 4341  | 3711  | 3183 | 3416  | 3457  | 3321   | 2845      | 2950    | 2893     | 2240     | 39502  | 
| Beverly           | 4749    | 5231     | 5429  | 5158  | 4271 | 5559  | 5206  | 5654   | 4742      | 5070    | 6090     | 5105     | 62264  | 
| Bezazian          | 9056    | 9297     | 10222 | 10336 | 8617 | 10093 | 10241 | 10927  | 9605      | 9921    | 8401     | 8461     | 115177 | 
| Blackstone        | 8200    | 7116     | 8998  | 8531  | 7171 | 8662  | 9809  | 9914   | 8035      | 8340    | 8059     | 7585     | 100420 | 
```