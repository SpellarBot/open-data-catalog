# MVA VEHICLE REGISTRATION-BY-COUNTY-FY-2010-FY2016

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/mva-vehicle-registration-by-county-fy-2010-fy2015) |
| Metadata | [Link](https://data.maryland.gov/api/views/kqkd-4fx8) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/kqkd-4fx8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/kqkd-4fx8/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | kqkd-4fx8 |
| Name | MVA VEHICLE REGISTRATION-BY-COUNTY-FY-2010-FY2016 |
| Attribution | Motor Vehicle Administration |
| Category | Transportation |
| Tags | mva, maryland mva, vehicle registration, fy, fiscal yearend, county |
| Created | 2015-11-05T14:22:50Z |
| Publication Date | 2016-12-23T18:42:16Z |

## Description

MVA Vehicle Registration by County for FY2010-FY2016. Data as of June 30, 2016

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type | Render Type |
| ======== | ============== | =============== | =============== | ========= | =========== |
| Yes      | series tag     | fiscal_year     | Fiscal Year     | text      | text        |
| Yes      | numeric metric | allegany        | ALLEGANY        | number    | number      |
| Yes      | numeric metric | anne_arundel    | ANNE ARUNDEL    | number    | number      |
| Yes      | numeric metric | baltimore       | BALTIMORE       | number    | number      |
| Yes      | numeric metric | baltimore_city  | BALTIMORE CITY  | number    | number      |
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
| Yes      | numeric metric | somerset        | SOMERSET        | number    | number      |
| Yes      | numeric metric | st_mary_s       | ST MARY'S       | number    | number      |
| Yes      | numeric metric | talbot          | TALBOT          | number    | number      |
| Yes      | numeric metric | washington      | WASHINGTON      | number    | number      |
| Yes      | numeric metric | wicomico        | WICOMICO        | number    | number      |
| Yes      | numeric metric | worcester       | WORCESTER       | number    | number      |
```

## Time Field

```ls
Value = 2010
Format & Zone = yyyy
```

## Data Commands

```ls
series e:kqkd-4fx8 d:2010-01-01T00:00:00.000Z t:fiscal_year="FY 2010" m:anne_arundel=513278 m:baltimore_city=280793 m:wicomico=86553 m:montgomery=754641 m:kent=21453 m:harford=235366 m:frederick=226529 m:prince_george_s=626009 m:baltimore=660553 m:carroll=176842 m:calvert=91108 m:charles=138672 m:allegany=62813 m:washington=136894 m:queen_anne_s=53779 m:caroline=36699 m:somerset=20570 m:talbot=42116 m:cecil=94305 m:garrett=33303 m:worcester=57117 m:howard=251713 m:dorchester=31742 m:st_mary_s=104488

series e:kqkd-4fx8 d:2010-01-01T00:00:00.000Z t:fiscal_year="FY 2011" m:anne_arundel=533106 m:baltimore_city=285394 m:wicomico=88153 m:montgomery=752503 m:kent=21397 m:harford=237096 m:frederick=227672 m:prince_george_s=633920 m:baltimore=663514 m:carroll=177125 m:calvert=91768 m:charles=140423 m:allegany=62512 m:washington=137204 m:queen_anne_s=53938 m:caroline=36667 m:somerset=20382 m:talbot=42380 m:cecil=94563 m:garrett=33202 m:worcester=56627 m:howard=255497 m:dorchester=31672 m:st_mary_s=105942

series e:kqkd-4fx8 d:2010-01-01T00:00:00.000Z t:fiscal_year="FY 2012" m:anne_arundel=537670 m:baltimore_city=289229 m:wicomico=87294 m:montgomery=755353 m:kent=21651 m:harford=236024 m:frederick=230727 m:prince_george_s=643710 m:baltimore=669052 m:carroll=177603 m:calvert=93222 m:charles=141965 m:allegany=62574 m:washington=137716 m:queen_anne_s=54159 m:caroline=36728 m:somerset=20021 m:talbot=42344 m:cecil=95254 m:garrett=33459 m:worcester=57767 m:howard=258164 m:dorchester=32416 m:st_mary_s=108276
```

## Meta Commands

```ls
metric m:allegany p:integer l:ALLEGANY t:dataTypeName=number

metric m:anne_arundel p:integer l:"ANNE ARUNDEL" t:dataTypeName=number

metric m:baltimore p:integer l:BALTIMORE t:dataTypeName=number

metric m:baltimore_city p:integer l:"BALTIMORE CITY" t:dataTypeName=number

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

metric m:somerset p:integer l:SOMERSET t:dataTypeName=number

metric m:st_mary_s p:integer l:"ST MARY'S" t:dataTypeName=number

metric m:talbot p:integer l:TALBOT t:dataTypeName=number

metric m:washington p:integer l:WASHINGTON t:dataTypeName=number

metric m:wicomico p:integer l:WICOMICO t:dataTypeName=number

metric m:worcester p:integer l:WORCESTER t:dataTypeName=number

entity e:kqkd-4fx8 l:"MVA VEHICLE REGISTRATION-BY-COUNTY-FY-2010-FY2016" t:attribution="Motor Vehicle Administration" t:url=https://data.maryland.gov/api/views/kqkd-4fx8

property e:kqkd-4fx8 t:meta.view v:id=kqkd-4fx8 v:category=Transportation v:attributionLink=http://www.mva.maryland.gov/ v:averageRating=0 v:name="MVA VEHICLE REGISTRATION-BY-COUNTY-FY-2010-FY2016" v:attribution="Motor Vehicle Administration"

property e:kqkd-4fx8 t:meta.view.owner v:id=pvrd-fajs v:screenName="Juanita Gray" v:displayName="Juanita Gray"

property e:kqkd-4fx8 t:meta.view.tableauthor v:id=pvrd-fajs v:screenName="Juanita Gray" v:roleName=editor v:displayName="Juanita Gray"
```

## Top Records

```ls
| fiscal_year | allegany | anne_arundel | baltimore | baltimore_city | calvert | caroline | carroll | cecil | charles | dorchester | frederick | garrett | harford | howard | kent  | montgomery | prince_george_s | queen_anne_s | somerset | st_mary_s | talbot | washington | wicomico | worcester | 
| =========== | ======== | ============ | ========= | ============== | ======= | ======== | ======= | ===== | ======= | ========== | ========= | ======= | ======= | ====== | ===== | ========== | =============== | ============ | ======== | ========= | ====== | ========== | ======== | ========= | 
| FY 2010     | 62813    | 513278       | 660553    | 280793         | 91108   | 36699    | 176842  | 94305 | 138672  | 31742      | 226529    | 33303   | 235366  | 251713 | 21453 | 754641     | 626009          | 53779        | 20570    | 104488    | 42116  | 136894     | 86553    | 57117     | 
| FY 2011     | 62512    | 533106       | 663514    | 285394         | 91768   | 36667    | 177125  | 94563 | 140423  | 31672      | 227672    | 33202   | 237096  | 255497 | 21397 | 752503     | 633920          | 53938        | 20382    | 105942    | 42380  | 137204     | 88153    | 56627     | 
| FY 2012     | 62574    | 537670       | 669052    | 289229         | 93222   | 36728    | 177603  | 95254 | 141965  | 32416      | 230727    | 33459   | 236024  | 258164 | 21651 | 755353     | 643710          | 54159        | 20021    | 108276    | 42344  | 137716     | 87294    | 57767     | 
| FY 2013     | 61390    | 538501       | 669201    | 297990         | 92699   | 35749    | 176281  | 93408 | 141107  | 32056      | 228442    | 32942   | 234421  | 258498 | 21191 | 758413     | 640226          | 53259        | 19495    | 107802    | 41680  | 135787     | 86735    | 56148     | 
| FY 2014     | 61481    | 542768       | 680074    | 303542         | 93322   | 36019    | 178086  | 94146 | 143729  | 32553      | 231390    | 33231   | 236667  | 261320 | 21397 | 763346     | 653111          | 53842        | 20125    | 108794    | 42110  | 137007     | 87766    | 56655     | 
| FY 2015     | 61522    | 548755       | 692233    | 309611         | 94446   | 36356    | 179479  | 95147 | 146350  | 32439      | 234601    | 33472   | 239775  | 264666 | 21543 | 774968     | 673476          | 54480        | 21721    | 108860    | 42488  | 137203     | 89182    | 57230     | 
| FY 2016     | 61345    | 552968       | 701014    | 293270         | 95636   | 36986    | 179561  | 95495 | 148272  | 32599      | 238409    | 33748   | 243840  | 268452 | 21221 | 787453     | 685700          | 55564        | 19388    | 112179    | 42907  | 138494     | 88464    | 59393     | 
```