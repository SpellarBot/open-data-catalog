# Better Brakes - List of Certified Parts

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/better-brakes-list-of-certified-parts-7a1b9) |
| Metadata | [Link](https://data.wa.gov/api/views/bv9x-jtbr) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/bv9x-jtbr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/bv9x-jtbr/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | bv9x-jtbr |
| Name | Better Brakes - List of Certified Parts |
| Attribution | The Washington State Department of Ecology |
| Category | Natural Resources & Environment |
| Tags | better brakes, certification |
| Created | 2013-06-24T17:12:57Z |
| Publication Date | 2014-06-12T23:08:08Z |

## Description

Chapter 70.285 RCW and Chapter 173-901 WAC requires manufacturers to certify brake friction material sold in Washington State by January 1, 2015.  This data set contains a list of all edge codes that have been certified with Ecology.  Manufacturers are required to submit certification forms quarterly.  This dataset will be updated each quarter.

## Columns

```ls
| Included | Schema Type | Field Name             | Name                   | Data Type     | Render Type   |
| ======== | =========== | ====================== | ====================== | ============= | ============= |
| Yes      | series tag  | edgecode               | EdgeCode               | text          | text          |
| Yes      | series tag  | compliancelevelcode    | ComplianceLevelCode    | text          | text          |
| Yes      | time        | certificationstartdate | CertificationStartDate | calendar_date | calendar_date |
| No       |             | certificationenddate   | CertificationEndDate   | calendar_date | calendar_date |
| Yes      | series tag  | manufacturername       | ManufacturerName       | text          | text          |
```

## Time Field

```ls
Value = certificationstartdate
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = certificationenddate
```

## Data Commands

```ls
series e:bv9x-jtbr d:2016-06-15T00:00:00.000Z t:compliancelevelcode=N t:edgecode="CEN 112AA9156" t:manufacturername="CWD, LLC" m:row_number.bv9x-jtbr=1

series e:bv9x-jtbr d:2016-06-15T00:00:00.000Z t:compliancelevelcode=N t:edgecode="CEN 111AB9156" t:manufacturername="CWD, LLC" m:row_number.bv9x-jtbr=2

series e:bv9x-jtbr d:2016-06-10T00:00:00.000Z t:compliancelevelcode=N t:edgecode="CEN 15AE5936" t:manufacturername="CWD, LLC" m:row_number.bv9x-jtbr=3
```

## Meta Commands

```ls
metric m:row_number.bv9x-jtbr p:long l:"Row Number"

entity e:bv9x-jtbr l:"Better Brakes - List of Certified Parts" t:attribution="The Washington State Department of Ecology" t:url=https://data.wa.gov/api/views/bv9x-jtbr

property e:bv9x-jtbr t:meta.view v:id=bv9x-jtbr v:category="Natural Resources & Environment" v:attributionLink=http://www.ecy.wa.gov/programs/hwtr/betterbrakes.html v:averageRating=0 v:name="Better Brakes - List of Certified Parts" v:attribution="The Washington State Department of Ecology"

property e:bv9x-jtbr t:meta.view.license v:name="Public Domain"

property e:bv9x-jtbr t:meta.view.owner v:id=a9ty-dhvu v:screenName="ECY-Wesley, Ian" v:displayName="ECY-Wesley, Ian"

property e:bv9x-jtbr t:meta.view.tableauthor v:id=a9ty-dhvu v:screenName="ECY-Wesley, Ian" v:roleName=publisher v:displayName="ECY-Wesley, Ian"
```

## Top Records

```ls
| edgecode      | compliancelevelcode | certificationstartdate | certificationenddate | manufacturername                    | 
| ============= | =================== | ====================== | ==================== | =================================== | 
| CEN 112AA9156 | N                   | 2016-06-15T00:00:00    | 2019-06-15T23:59:00  | CWD, LLC                            | 
| CEN 111AB9156 | N                   | 2016-06-15T00:00:00    | 2019-06-15T23:59:00  | CWD, LLC                            | 
| CEN 15AE5936  | N                   | 2016-06-10T00:00:00    | 2019-06-10T23:59:00  | CWD, LLC                            | 
| CEN 13AA9101  | B                   | 2016-06-10T00:00:00    | 2019-06-10T23:59:00  | CWD, LLC                            | 
| CEN 111AA9156 | N                   | 2016-06-10T00:00:00    | 2019-06-10T23:59:00  | CWD, LLC                            | 
| CEN 112AB9156 | N                   | 2016-06-08T00:00:00    | 2019-06-08T23:59:00  | CWD, LLC                            | 
| GH 602        | N                   | 2016-05-26T00:00:00    | 2019-05-26T23:59:00  | Qingdao Gihon Auto Parts Co., Ltd   | 
| GH 273        | B                   | 2016-05-26T00:00:00    | 2019-05-26T23:59:00  | Qingdao Gihon Auto Parts Co., Ltd   | 
| GH 122        | N                   | 2016-05-26T00:00:00    | 2019-05-26T23:59:00  | Qingdao Gihon Auto Parts Co., Ltd   | 
| BX430         | N                   | 2016-05-26T00:00:00    | 2019-05-26T23:59:00  | Bendix Spicer Foundation Brake, LLC | 
```