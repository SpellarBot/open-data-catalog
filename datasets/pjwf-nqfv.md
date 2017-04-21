# SSMMA Precincts

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ssmma-precincts-08354) |
| Metadata | [Link](https://data.illinois.gov/api/views/pjwf-nqfv) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/pjwf-nqfv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/pjwf-nqfv/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | pjwf-nqfv |
| Name | SSMMA Precincts |
| Attribution | South Suburban Mayors and Managers Association |
| Category | Municipality |
| Tags | political, planning |
| Created | 2012-11-27T20:17:49Z |
| Publication Date | 2012-11-27T20:18:47Z |

## Description

This list reflects precincts in the Chicago Southland region. This is reflective of the year 2011.

## Columns

```ls
| Included | Schema Type    | Field Name | Name     | Data Type     | Render Type   |
| ======== | ============== | ========== | ======== | ============= | ============= |
| Yes      | series tag     | name       | NAME     | text          | text          |
| Yes      | series tag     | name_tmp   | NAME_TMP | text          | text          |
| Yes      | time           | num        | Num      | calendar_date | calendar_date |
| Yes      | numeric metric | idpct      | Idpct    | number        | number        |
| No       |                | point_x    | POINT_X  | number        | number        |
| No       |                | point_y    | POINT_Y  | number        | number        |
```

## Time Field

```ls
Value = num
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = point_x,point_y
```

## Data Commands

```ls
series e:pjwf-nqfv d:0008-04-03T00:00:00.000Z t:name=BERWYN t:name_tmp="TOWN OF BERWYN" m:idpct=9908004

series e:pjwf-nqfv d:0008-01-03T00:00:00.000Z t:name=BERWYN t:name_tmp="TOWN OF BERWYN" m:idpct=9908001

series e:pjwf-nqfv d:0008-03-03T00:00:00.000Z t:name=BERWYN t:name_tmp="TOWN OF BERWYN" m:idpct=9908003
```

## Meta Commands

```ls
metric m:idpct p:integer l:Idpct t:dataTypeName=number

entity e:pjwf-nqfv l:"SSMMA Precincts" t:attribution="South Suburban Mayors and Managers Association" t:url=https://data.illinois.gov/api/views/pjwf-nqfv

property e:pjwf-nqfv t:meta.view v:id=pjwf-nqfv v:category=Municipality v:attributionLink=http://www.ssmma.org v:averageRating=0 v:name="SSMMA Precincts" v:attribution="South Suburban Mayors and Managers Association"

property e:pjwf-nqfv t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:pjwf-nqfv t:meta.view.owner v:id=p88s-rkzf v:profileImageUrlMedium=/api/users/p88s-rkzf/profile_images/THUMB v:profileImageUrlLarge=/api/users/p88s-rkzf/profile_images/LARGE v:screenName=mrizzitiello v:profileImageUrlSmall=/api/users/p88s-rkzf/profile_images/TINY v:displayName=mrizzitiello

property e:pjwf-nqfv t:meta.view.tableauthor v:id=2fjt-8tt3 v:screenName=data.il.admin v:displayName=data.il.admin
```

## Top Records

```ls
| name   | name_tmp       | num                 | idpct   | point_x     | point_y     | 
| ====== | ============== | =================== | ======= | =========== | =========== | 
| BERWYN | TOWN OF BERWYN | 0008-04-03T00:00:00 | 9908004 | 1133910.286 | 1893327.059 | 
| BERWYN | TOWN OF BERWYN | 0008-01-03T00:00:00 | 9908001 | 1128400.263 | 1893166.467 | 
| BERWYN | TOWN OF BERWYN | 0008-03-03T00:00:00 | 9908003 | 1131947.272 | 1891941.829 | 
| BERWYN | TOWN OF BERWYN | 0008-02-03T00:00:00 | 9908002 | 1133946.03  | 1891996.386 | 
| BERWYN | TOWN OF BERWYN | 0007-04-03T00:00:00 | 9907004 | 1131300.088 | 1891225.907 | 
| BERWYN | TOWN OF BERWYN | 0006-01-03T00:00:00 | 9906001 | 1133982.224 | 1890664.29  | 
| BERWYN | TOWN OF BERWYN | 0005-04-03T00:00:00 | 9905004 | 1135321.801 | 1890698.48  | 
| BERWYN | TOWN OF BERWYN | 0007-01-03T00:00:00 | 9907001 | 1131316.483 | 1890594.812 | 
| BERWYN | TOWN OF BERWYN | 0006-04-03T00:00:00 | 9906004 | 1132644.561 | 1890793.724 | 
| BERWYN | TOWN OF BERWYN | 0006-03-03T00:00:00 | 9906003 | 1131999.763 | 1889996.642 | 
```