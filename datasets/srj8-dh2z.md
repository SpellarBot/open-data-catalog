# IDHS - License Outpatient Treatment

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idhs-license-outpatient-treatment-7098b) |
| Metadata | [Link](https://data.illinois.gov/api/views/srj8-dh2z) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/srj8-dh2z/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/srj8-dh2z/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | srj8-dh2z |
| Name | IDHS - License Outpatient Treatment |
| Category | Social/Healthcare |
| Created | 2011-11-03T12:50:09Z |
| Publication Date | 2011-11-03T13:00:16Z |

## Description

License Outpatient Treatment

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type | Render Type |
| ======== | ============== | ================== | ================== | ========= | =========== |
| Yes      | series tag     | corpname           | CorpName           | text      | text        |
| Yes      | series tag     | corpcity           | CorpCity           | text      | text        |
| Yes      | series tag     | corpzip1           | CorpZip1           | text      | text        |
| Yes      | series tag     | corpzip2           | CorpZip2           | text      | text        |
| Yes      | series tag     | corpcnty           | CorpCnty           | text      | text        |
| Yes      | series tag     | corpcntycode       | CorpCntyCode       | text      | number      |
| Yes      | series tag     | corpreptitle       | CorpRepTitle       | text      | text        |
| Yes      | series tag     | licensenum         | LicenseNum         | text      | text        |
| Yes      | time           | expdate            | ExpDate            | date      | date        |
| Yes      | series tag     | licname            | LicName            | text      | text        |
| Yes      | series tag     | liczip1            | LicZip1            | text      | text        |
| Yes      | series tag     | liczip2            | LicZip2            | text      | text        |
| Yes      | series tag     | liccounty          | LicCounty          | text      | text        |
| Yes      | series tag     | cntycode           | CntyCode           | text      | number      |
| Yes      | numeric metric | dhsreg             | DHSReg             | number    | number      |
| Yes      | series tag     | license_service_1  | License Service 1  | text      | text        |
| Yes      | series tag     | license_service_2  | License Service 2  | text      | text        |
| Yes      | series tag     | license_service_3  | License Service 3  | text      | text        |
| Yes      | series tag     | license_service_4  | License Service 4  | text      | text        |
| Yes      | series tag     | license_service_5  | License Service 5  | text      | text        |
| Yes      | series tag     | license_service_6  | License Service 6  | text      | text        |
| Yes      | series tag     | license_service_7  | License Service 7  | text      | text        |
| Yes      | series tag     | license_service_8  | License Service 8  | text      | text        |
| Yes      | series tag     | license_service_9  | License Service 9  | text      | text        |
| Yes      | series tag     | license_service_10 | License Service 10 | text      | text        |
| Yes      | series tag     | license_service_11 | License Service 11 | text      | text        |
| Yes      | series tag     | license_service_12 | License Service 12 | text      | text        |
| Yes      | series tag     | license_service_13 | License Service 13 | text      | text        |
| Yes      | series tag     | license_service_14 | License Service 14 | text      | text        |
```

## Time Field

```ls
Value = expdate
Format & Zone = seconds
```

## Data Commands

```ls
series e:srj8-dh2z d:2012-10-31T07:00:00.000Z t:license_service_3="METH ADJ TO TX" t:license_service_2="L2 ADULT IOP" t:corpreptitle=PRESIDENT t:license_service_1="L1 ADULT OUTPT" t:license_service_5="DUI RISK ED" t:license_service_4="DUI EVAL" t:corpzip1=60190 t:corpcntycode=22 t:corpcnty=DUPAGE t:liczip1=60190 t:corpname="STONYBROOK CENTER, INC." t:liccounty=DUPAGE t:corpcity=WINFIELD t:cntycode=22 t:licensenum=A-8645-0001-A t:licname="STONYBROOK CENTER, INC." m:dhsreg=2

series e:srj8-dh2z d:2012-06-30T07:00:00.000Z t:license_service_3="DUI RISK ED" t:license_service_2="DUI EVAL" t:corpreptitle=DIRECTOR t:license_service_1="L1 ADULT OUTPT" t:corpzip2=2289 t:corpzip1=60030 t:corpcntycode=49 t:corpcnty=LAKE t:liczip1=60030 t:liczip2=2289 t:corpname="DUI ASSOCIATES" t:liccounty=LAKE t:corpcity=GRAYSLAKE t:cntycode=49 t:licensenum=A-1020-0001-A t:licname="DUI ASSOCIATES" m:dhsreg=2

series e:srj8-dh2z d:2013-01-31T08:00:00.000Z t:license_service_2="L2 ADULT IOP" t:corpreptitle="EXECUTIVE DIRECTOR" t:license_service_1="L1 ADULT OUTPT" t:corpzip1=62650 t:corpcntycode=69 t:corpcnty=MORGAN t:liczip1=60950 t:liczip2=9645 t:corpname="WELLS CENTER, THE" t:liccounty=WILL t:corpcity=JACKSONVILLE t:cntycode=99 t:licensenum=A-0613-0022-A t:licname="KANKAKEE MINIMUM SECURITY UNIT (KMSU) / WELLS CENTER, INC." m:dhsreg=2
```

## Meta Commands

```ls
metric m:dhsreg p:integer l:DHSReg t:dataTypeName=number

entity e:srj8-dh2z l:"IDHS - License Outpatient Treatment" t:url=https://data.illinois.gov/api/views/srj8-dh2z

property e:srj8-dh2z t:meta.view v:id=srj8-dh2z v:category=Social/Healthcare v:averageRating=0 v:name="IDHS - License Outpatient Treatment"

property e:srj8-dh2z t:meta.view.owner v:id=e9y5-49nr v:screenName="Carl Awe" v:displayName="Carl Awe"

property e:srj8-dh2z t:meta.view.tableauthor v:id=e9y5-49nr v:screenName="Carl Awe" v:displayName="Carl Awe"
```

## Top Records

```ls
| corpname                                     | corpcity     | corpzip1 | corpzip2 | corpcnty     | corpcntycode | corpreptitle       | licensenum    | expdate    | licname                                                    | liczip1 | liczip2 | liccounty    | cntycode | dhsreg | license_service_1 | license_service_2 | license_service_3 | license_service_4 | license_service_5 | license_service_6 | license_service_7 | license_service_8 | license_service_9 | license_service_10 | license_service_11 | license_service_12 | license_service_13 | license_service_14 | 
| ============================================ | ============ | ======== | ======== | ============ | ============ | ================== | ============= | ========== | ========================================================== | ======= | ======= | ============ | ======== | ====== | ================= | ================= | ================= | ================= | ================= | ================= | ================= | ================= | ================= | ================== | ================== | ================== | ================== | ================== | 
| STONYBROOK CENTER, INC.                      | WINFIELD     | 60190    |          | DUPAGE       | 22           | PRESIDENT          | A-8645-0001-A | 1351666800 | STONYBROOK CENTER, INC.                                    | 60190   |         | DUPAGE       | 22       | 2      | L1 ADULT OUTPT    | L2 ADULT IOP      | METH ADJ TO TX    | DUI EVAL          | DUI RISK ED       |                   |                   |                   |                   |                    |                    |                    |                    |                    | 
| DUI ASSOCIATES                               | GRAYSLAKE    | 60030    | 2289     | LAKE         | 49           | DIRECTOR           | A-1020-0001-A | 1341039600 | DUI ASSOCIATES                                             | 60030   | 2289    | LAKE         | 49       | 2      | L1 ADULT OUTPT    | DUI EVAL          | DUI RISK ED       |                   |                   |                   |                   |                   |                   |                    |                    |                    |                    |                    | 
| WELLS CENTER, THE                            | JACKSONVILLE | 62650    |          | MORGAN       | 69           | EXECUTIVE DIRECTOR | A-0613-0022-A | 1359619200 | KANKAKEE MINIMUM SECURITY UNIT (KMSU) / WELLS CENTER, INC. | 60950   | 9645    | WILL         | 99       | 2      | L1 ADULT OUTPT    | L2 ADULT IOP      |                   |                   |                   |                   |                   |                   |                   |                    |                    |                    |                    |                    | 
| KEVIN & ASSOCIATES                           | ELMHURST     | 60126    |          | DUPAGE       | 22           | DIRECTOR           | A-0026-0002-A | 1354262400 | KEVIN & ASSOCIATES, INC.                                   | 60126   |         | DUPAGE       | 22       | 2      | L1 ADULT OUTPT    | L2 ADULT IOP      | DUI EVAL          | DUI RISK ED       |                   |                   |                   |                   |                   |                    |                    |                    |                    |                    | 
| CARBONDALE DUI AND COUNSELING ASSOCIATES     | CARBONDALE   | 62901    |          | JACKSON      | 39           | EXECUTIVE DIRECTOR | A-0051-0001-A | 1333177200 | CARBONDALE DUI AND COUNSELING PROGRAM                      | 62901   |         | JACKSON      | 39       | 5      | L1 ADULT OUTPT    | DUI EVAL          | DUI RISK ED       |                   |                   |                   |                   |                   |                   |                    |                    |                    |                    |                    | 
| HUMAN SERVICE CENTER OF PEORIA               | PEORIA       | 61603    |          | PEORIA       | 72           | COMPTOLLER         | A-0324-0003-A | 1348988400 | WHITE OAKS KNOLLS                                          | 61614   | 1219    | PEORIA       | 72       | 3      | L1 ADULT OUTPT    | L2 ADULT IOP      | L3 ADT INPT SUB   | RECOVERY HOME     |                   |                   |                   |                   |                   |                    |                    |                    |                    |                    | 
| FIRST STEP DUI EVALUATION & COUNSELING, INC. | TROY         | 62294    |          | MADISON      | 57           | VICE PRESIDENT     | A-7129-0001-A | 1372575600 | FIRST STEP DUI EVALUATION & COUNSELING, INC.               | 62294   |         | MADISON      | 57       | 5      | L1 ADULT OUTPT    | L2 ADULT IOP      | DUI EVAL          | DUI RISK ED       |                   |                   |                   |                   |                   |                    |                    |                    |                    |                    | 
| CLYBOURN CONSULTING CORPORATION              | SKOKIE       | 60077    |          | COOK(SUBURB) | 16           | PROGRAM DIRECTOR   | A-8215-0001-A | 1341039600 | CLYBOURN CONSULTING CORPORATION                            | 60077   |         | COOK(SUBURB) | 16       | 1      | L1 ADULT OUTPT    | L2 ADULT IOP      | DUI EVAL          | DUI RISK ED       |                   |                   |                   |                   |                   |                    |                    |                    |                    |                    | 
| ABC DUI SERVICES                             | SALEM        | 62881    |          | MARION       | 58           | DIRECTOR           | A-3846-0002-A | 1320044400 | ABC DUI SERVICES                                           | 62881   |         | MARION       | 58       | 5      | L1 ADULT OUTPT    | L1 YOUTH OUTPT    | L2 ADULT IOP      | L2 YOUTH IOP      | DUI EVAL          | DUI RISK ED       |                   |                   |                   |                    |                    |                    |                    |                    | 
| HUMAN SERVICE CENTER OF PEORIA               | PEORIA       | 61603    |          | PEORIA       | 72           | COMPTOLLER         | A-0324-0001-A | 1348988400 | CENTRAL ILLINOIS CENTER FOR THE TREATMENT OF ADDICTIONS    | 61605   | 2484    | PEORIA       | 72       | 3      | L1 ADULT OUTPT    | L2 ADULT IOP      | L3 ADT INPT SUB   | RECOVERY HOME     |                   |                   |                   |                   |                   |                    |                    |                    |                    |                    | 
```