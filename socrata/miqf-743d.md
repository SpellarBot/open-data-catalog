# SSMMA Median Home Value

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ssmma-median-home-value-f43db) |
| Metadata | [Link](https://data.illinois.gov/api/views/miqf-743d) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/miqf-743d/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/miqf-743d/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | miqf-743d |
| Name | SSMMA Median Home Value |
| Attribution | South Suburban Mayors and Managers Association |
| Category | Municipality |
| Tags | housing, economic development, planning, statistical |
| Created | 2012-11-27T20:56:12Z |
| Publication Date | 2012-11-27T20:57:02Z |

## Description

This dataset details the median home value in Chicago Southland municipalities. Numerical data reflects an average of sales in zillow. com and trulia.com.

## Columns

```ls
| Included | Schema Type    | Field Name  | Name       | Data Type | Render Type |
| ======== | ============== | =========== | ========== | ========= | =========== |
| No       | time           | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag     | objectid    | OBJECTID   | text      | number      |
| Yes      | series tag     | municipali  | MUNICIPALI | text      | text        |
| Yes      | numeric metric | current_me  | CURRENT_ME | number    | number      |
| Yes      | series tag     | weblink     | WEBLINK    | text      | text        |
| Yes      | series tag     | editor      | EDITOR     | text      | text        |
| Yes      | numeric metric | propreitar  | PROPREITAR | number    | number      |
| Yes      | series tag     | universali  | UNIVERSALI | text      | text        |
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
series e:miqf-743d d:2012-11-27T12:56:14.000Z t:editor=MJR t:weblink=http://www.zillow.com/local-info/IL-Homewood-home-value/r_45795/ t:universali=UR t:objectid=1 t:municipali=Homewood m:shape_area=147228317.032 m:shape_leng=73388.0626195 m:current_me=119500 m:propreitar=1

series e:miqf-743d d:2012-11-27T12:56:14.000Z t:editor=MJR t:weblink=http://www.zillow.com/local-info/IL-Flossmoor-home-value/r_29979/ t:universali=UR t:objectid=2 t:municipali=Flossmoor m:shape_area=101139509.05 m:shape_leng=93368.9037482 m:current_me=171200 m:propreitar=2

series e:miqf-743d d:2012-11-27T12:56:14.000Z t:editor=MJR t:weblink=http://www.zillow.com/local-info/IL-Olympia-Fields-home-value/r_22183/ t:universali=UR t:objectid=3 t:municipali="Olympia Fields" m:shape_area=79538995.9458 m:shape_leng=69537.6219866 m:current_me=182600 m:propreitar=3
```

## Meta Commands

```ls
metric m:current_me p:integer l:CURRENT_ME t:dataTypeName=number

metric m:propreitar p:integer l:PROPREITAR t:dataTypeName=number

metric m:shape_leng p:double l:SHAPE_Leng t:dataTypeName=number

metric m:shape_area p:double l:SHAPE_Area t:dataTypeName=number

entity e:miqf-743d l:"SSMMA Median Home Value" t:attribution="South Suburban Mayors and Managers Association" t:url=https://data.illinois.gov/api/views/miqf-743d

property e:miqf-743d t:meta.view v:id=miqf-743d v:category=Municipality v:attributionLink=http://www.ssmma.org v:averageRating=0 v:name="SSMMA Median Home Value" v:attribution="South Suburban Mayors and Managers Association"

property e:miqf-743d t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:miqf-743d t:meta.view.owner v:id=p88s-rkzf v:profileImageUrlMedium=/api/users/p88s-rkzf/profile_images/THUMB v:profileImageUrlLarge=/api/users/p88s-rkzf/profile_images/LARGE v:screenName=mrizzitiello v:profileImageUrlSmall=/api/users/p88s-rkzf/profile_images/TINY v:displayName=mrizzitiello

property e:miqf-743d t:meta.view.tableauthor v:id=74c3-ka9x v:profileImageUrlMedium=/api/users/74c3-ka9x/profile_images/THUMB v:profileImageUrlLarge=/api/users/74c3-ka9x/profile_images/LARGE v:screenName="Rey de Castro" v:profileImageUrlSmall=/api/users/74c3-ka9x/profile_images/TINY v:roleName=publisher v:displayName="Rey de Castro"
```

## Top Records

```ls
| :updated_at | objectid | municipali         | current_me | weblink                                                                    | editor | propreitar | universali | shape_leng    | shape_area    | 
| =========== | ======== | ================== | ========== | ========================================================================== | ====== | ========== | ========== | ============= | ============= | 
| 1354020974  | 1        | Homewood           | 119500     | http://www.zillow.com/local-info/IL-Homewood-home-value/r_45795/           | MJR    | 1          | UR         | 73388.0626195 | 147228317.032 | 
| 1354020974  | 2        | Flossmoor          | 171200     | http://www.zillow.com/local-info/IL-Flossmoor-home-value/r_29979/          | MJR    | 2          | UR         | 93368.9037482 | 101139509.05  | 
| 1354020974  | 3        | Olympia Fields     | 182600     | http://www.zillow.com/local-info/IL-Olympia-Fields-home-value/r_22183/     | MJR    | 3          | UR         | 69537.6219866 | 79538995.9458 | 
| 1354020974  | 4        | Country Club Hills | 92700      | http://www.zillow.com/local-info/IL-Country-Club-Hills-home-value/r_14849/ | MJR    | 4          | UR         | 77819.513342  | 131526346.171 | 
| 1354020974  | 5        | Thornton           | 73500      | http://www.zillow.com/local-info/IL-Thornton-home-value/r_41227/           | MJR    | 5          | UR         | 47526.0463823 | 66158504.2681 | 
| 1354020974  | 6        | Calumet City       | 68100      | http://www.zillow.com/local-info/IL-Calumet-City-home-value/r_10669/       | MJR    | 6          | UR         | 118855.004397 | 205291311.845 | 
| 1354020974  | 7        | Dixmoor            | 52100      | http://www.zillow.com/local-info/IL-Dixmoor-home-value/r_31236/            | MJR    | 7          | UR         | 25818.0895707 | 35230112.2731 | 
| 1354020974  | 8        | Dolton             | 75300      | http://www.zillow.com/local-info/IL-Dolton-home-value/r_8671/              | MJR    | 8          | UR         | 75222.5152121 | 129177579.301 | 
| 1354020974  | 9        | East Hazel Crest   | 78800      | http://www.zillow.com/local-info/IL-East-Hazel-Crest-home-value/r_17872/   | MJR    | 9          | UR         | 25177.6016821 | 21834493.4708 | 
| 1354020974  | 10       | Richton Park       | 88200      | http://www.zillow.com/local-info/IL-Richton-Park-home-value/r_26755/       | MJR    | 10         | UR         | 85701.3299538 | 102509534.008 | 
```