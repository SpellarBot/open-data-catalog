# MVA Driver's Licenses: Age Stratification by County FY2010 - FY2016

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/mva-drivers-licenses-age-stratification-by-county-fy2010-fy2016) |
| Metadata | [Link](https://data.maryland.gov/api/views/hyut-sfvk) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/hyut-sfvk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/hyut-sfvk/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | hyut-sfvk |
| Name | MVA Driver's Licenses: Age Stratification by County FY2010 - FY2016 |
| Attribution | Motor Vehicle Administration |
| Category | Transportation |
| Tags | driver's, driver, licenses, age, license, county, mva, motor vehicle administration |
| Created | 2015-07-13T15:58:55Z |
| Publication Date | 2016-10-11T15:05:11Z |

## Description

MVA Driver's Licenses by Age and County for FY2010-FY2016. Data as of June 30, 2016

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type | Render Type |
| ======== | ============== | =============== | =============== | ========= | =========== |
| Yes      | time           | fiscal_year     | Fiscal Year     | number    | number      |
| Yes      | series tag     | age             | AGE             | text      | text        |
| Yes      | numeric metric | baltimore_city  | BALTIMORE CITY  | number    | number      |
| Yes      | numeric metric | allegany        | ALLEGANY        | number    | number      |
| Yes      | numeric metric | anne_arundel    | ANNE ARUNDEL    | number    | number      |
| Yes      | numeric metric | baltimore       | BALTIMORE       | number    | number      |
| Yes      | numeric metric | calvert         | CALVERT         | number    | number      |
| Yes      | numeric metric | caroline        | CAROLINE        | number    | number      |
| Yes      | numeric metric | carroll         | CARROLL         | number    | number      |
| Yes      | numeric metric | cecil           | CECIL           | number    | number      |
| Yes      | numeric metric | charles         | CHARLES         | number    | number      |
| Yes      | numeric metric | dorchester      | DORCHESTER      | number    | number      |
| Yes      | numeric metric | frederick       | FREDERICK       | number    | number      |
| Yes      | numeric metric | garrett         | GARRETT         | number    | number      |
| Yes      | numeric metric | harford         | HARFORD         | number    | number      |
| Yes      | numeric metric | howard          | HOWARD          | number    | number      |
| Yes      | numeric metric | kent            | KENT            | number    | number      |
| Yes      | numeric metric | montgomery      | MONTGOMERY      | number    | number      |
| Yes      | numeric metric | prince_george_s | PRINCE GEORGE'S | number    | number      |
| Yes      | numeric metric | queen_anne_s    | QUEEN ANNE'S    | number    | number      |
| Yes      | numeric metric | st_mary_s       | ST MARY'S       | number    | number      |
| Yes      | numeric metric | somerset        | SOMERSET        | number    | number      |
| Yes      | numeric metric | talbot          | TALBOT          | number    | number      |
| Yes      | numeric metric | washington      | WASHINGTON      | number    | number      |
| Yes      | numeric metric | wicomico        | WICOMICO        | number    | number      |
| Yes      | numeric metric | worcester       | WORCESTER       | number    | number      |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:hyut-sfvk d:2010-01-01T00:00:00.000Z t:age=16 m:anne_arundel=882 m:baltimore_city=134 m:wicomico=189 m:harford=470 m:kent=39 m:montgomery=1074 m:frederick=461 m:prince_george_s=273 m:baltimore=960 m:carroll=447 m:calvert=217 m:charles=212 m:allegany=120 m:queen_anne_s=122 m:washington=259 m:caroline=88 m:somerset=35 m:talbot=95 m:cecil=192 m:garrett=114 m:worcester=112 m:dorchester=47 m:howard=639 m:st_mary_s=212

series e:hyut-sfvk d:2010-01-01T00:00:00.000Z t:age=17 m:anne_arundel=3566 m:baltimore_city=904 m:wicomico=646 m:harford=1824 m:kent=136 m:montgomery=5420 m:frederick=1985 m:prince_george_s=2208 m:baltimore=4312 m:carroll=1724 m:calvert=875 m:charles=978 m:allegany=428 m:queen_anne_s=457 m:washington=990 m:caroline=274 m:somerset=117 m:talbot=260 m:cecil=793 m:garrett=283 m:worcester=393 m:dorchester=164 m:howard=2577 m:st_mary_s=815

series e:hyut-sfvk d:2010-01-01T00:00:00.000Z t:age=18 m:anne_arundel=4949 m:baltimore_city=1789 m:wicomico=843 m:harford=2766 m:kent=182 m:montgomery=8053 m:frederick=2612 m:prince_george_s=4345 m:baltimore=6497 m:carroll=2276 m:calvert=1203 m:charles=1572 m:allegany=590 m:queen_anne_s=550 m:washington=1341 m:caroline=326 m:somerset=158 m:talbot=349 m:cecil=1041 m:garrett=334 m:worcester=452 m:dorchester=272 m:howard=3440 m:st_mary_s=1141
```

## Meta Commands

```ls
metric m:baltimore_city p:integer l:"BALTIMORE CITY" t:dataTypeName=number

metric m:allegany p:integer l:ALLEGANY t:dataTypeName=number

metric m:anne_arundel p:integer l:"ANNE ARUNDEL" t:dataTypeName=number

metric m:baltimore p:integer l:BALTIMORE t:dataTypeName=number

metric m:calvert p:integer l:CALVERT t:dataTypeName=number

metric m:caroline p:integer l:CAROLINE t:dataTypeName=number

metric m:carroll p:integer l:CARROLL t:dataTypeName=number

metric m:cecil p:integer l:CECIL t:dataTypeName=number

metric m:charles p:integer l:CHARLES t:dataTypeName=number

metric m:dorchester p:integer l:DORCHESTER t:dataTypeName=number

metric m:frederick p:integer l:FREDERICK t:dataTypeName=number

metric m:garrett p:integer l:GARRETT t:dataTypeName=number

metric m:harford p:integer l:HARFORD t:dataTypeName=number

metric m:howard p:integer l:HOWARD t:dataTypeName=number

metric m:kent p:integer l:KENT t:dataTypeName=number

metric m:montgomery p:integer l:MONTGOMERY t:dataTypeName=number

metric m:prince_george_s p:integer l:"PRINCE GEORGE'S" t:dataTypeName=number

metric m:queen_anne_s p:integer l:"QUEEN ANNE'S" t:dataTypeName=number

metric m:st_mary_s p:integer l:"ST MARY'S" t:dataTypeName=number

metric m:somerset p:integer l:SOMERSET t:dataTypeName=number

metric m:talbot p:integer l:TALBOT t:dataTypeName=number

metric m:washington p:integer l:WASHINGTON t:dataTypeName=number

metric m:wicomico p:integer l:WICOMICO t:dataTypeName=number

metric m:worcester p:integer l:WORCESTER t:dataTypeName=number

entity e:hyut-sfvk l:"MVA Driver's Licenses: Age Stratification by County FY2010 - FY2016" t:attribution="Motor Vehicle Administration" t:url=https://data.maryland.gov/api/views/hyut-sfvk

property e:hyut-sfvk t:meta.view v:id=hyut-sfvk v:category=Transportation v:attributionLink=http://www.mva.maryland.gov/ v:averageRating=0 v:name="MVA Driver's Licenses: Age Stratification by County FY2010 - FY2016" v:attribution="Motor Vehicle Administration"

property e:hyut-sfvk t:meta.view.owner v:id=pvrd-fajs v:screenName="Juanita Gray" v:displayName="Juanita Gray"

property e:hyut-sfvk t:meta.view.tableauthor v:id=pvrd-fajs v:screenName="Juanita Gray" v:roleName=editor v:displayName="Juanita Gray"
```

## Top Records

```ls
| fiscal_year | age     | baltimore_city | allegany | anne_arundel | baltimore | calvert | caroline | carroll | cecil | charles | dorchester | frederick | garrett | harford | howard | kent | montgomery | prince_george_s | queen_anne_s | st_mary_s | somerset | talbot | washington | wicomico | worcester | 
| =========== | ======= | ============== | ======== | ============ | ========= | ======= | ======== | ======= | ===== | ======= | ========== | ========= | ======= | ======= | ====== | ==== | ========== | =============== | ============ | ========= | ======== | ====== | ========== | ======== | ========= | 
| 2010        | 16      | 134            | 120      | 882          | 960       | 217     | 88       | 447     | 192   | 212     | 47         | 461       | 114     | 470     | 639    | 39   | 1074       | 273             | 122          | 212       | 35       | 95     | 259        | 189      | 112       | 
| 2010        | 17      | 904            | 428      | 3566         | 4312      | 875     | 274      | 1724    | 793   | 978     | 164        | 1985      | 283     | 1824    | 2577   | 136  | 5420       | 2208            | 457          | 815       | 117      | 260    | 990        | 646      | 393       | 
| 2010        | 18      | 1789           | 590      | 4949         | 6497      | 1203    | 326      | 2276    | 1041  | 1572    | 272        | 2612      | 334     | 2766    | 3440   | 182  | 8053       | 4345            | 550          | 1141      | 158      | 349    | 1341       | 843      | 452       | 
| 2010        | 19      | 2840           | 661      | 5778         | 7834      | 1334    | 407      | 2477    | 1226  | 1897    | 327        | 3029      | 374     | 3057    | 3823   | 221  | 9725       | 6131            | 601          | 1242      | 168      | 406    | 1570       | 910      | 532       | 
| 2010        | 20      | 3801           | 756      | 6391         | 8858      | 1400    | 439      | 2580    | 1316  | 2017    | 342        | 3136      | 378     | 3413    | 4081   | 220  | 11032      | 7747            | 626          | 1385      | 207      | 442    | 1645       | 1038     | 589       | 
| 2010        | 21      | 4061           | 764      | 6508         | 9589      | 1368    | 433      | 2536    | 1300  | 2034    | 369        | 3192      | 356     | 3326    | 3937   | 233  | 11621      | 8553            | 577          | 1364      | 210      | 405    | 1737       | 1145     | 607       | 
| 2010        | 22      | 4598           | 759      | 6309         | 9877      | 1210    | 403      | 2350    | 1250  | 1830    | 329        | 2933      | 347     | 3173    | 3809   | 218  | 11990      | 9033            | 525          | 1308      | 184      | 425    | 1685       | 1142     | 549       | 
| 2010        | 23      | 5645           | 794      | 6649         | 10155     | 1202    | 395      | 2182    | 1238  | 1804    | 330        | 2854      | 331     | 3119    | 3697   | 227  | 12174      | 9722            | 508          | 1284      | 215      | 393    | 1718       | 1199     | 633       | 
| 2010        | 24      | 6672           | 775      | 6785         | 10491     | 1124    | 405      | 2116    | 1219  | 1733    | 363        | 2993      | 322     | 3184    | 3684   | 221  | 12875      | 10506           | 496          | 1392      | 231      | 420    | 1766       | 1346     | 643       | 
| 2010        | 25 - 29 | 40307          | 3835     | 36057        | 54624     | 4872    | 2105     | 9017    | 5764  | 8709    | 1788       | 15002     | 1642    | 15387   | 19115  | 1039 | 70933      | 59295           | 2273         | 6860      | 1083     | 1955   | 8772       | 6858     | 3117      | 
```