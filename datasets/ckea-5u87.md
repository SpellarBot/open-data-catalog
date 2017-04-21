# Cases Filed 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cases-filed-2013-df408) |
| Metadata | [Link](https://data.lacity.org/api/views/ckea-5u87) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/ckea-5u87/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/ckea-5u87/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | ckea-5u87 |
| Name | Cases Filed 2013 |
| Attribution | City of Los Angeles, Department of City Planning |
| Category | A Livable and Sustainable City |
| Tags | planning, cases filed, entitlement, environmental, development |
| Created | 2014-05-22T21:41:22Z |
| Publication Date | 2014-05-22T21:45:44Z |

## Description

Total Cases Filed with the Department of City Planning for the Year 2013.

## Columns

```ls
| Included | Schema Type | Field Name      | Name            | Data Type | Render Type |
| ======== | =========== | =============== | =============== | ========= | =========== |
| Yes      | series tag  | apc             | APC             | text      | text        |
| Yes      | series tag  | cpa             | CPA             | text      | text        |
| Yes      | series tag  | geographic_area | Geographic Area | text      | text        |
| Yes      | series tag  | case_type       | Case Type       | text      | text        |
| Yes      | series tag  | case_number     | Case Number     | text      | text        |
| No       |             | date_filed      | Date Filed      | text      | text        |
| No       |             | date_completed  | Date Completed  | text      | text        |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = date_filed,date_completed
```

## Data Commands

```ls
series e:ckea-5u87 d:2013-01-01T00:00:00.000Z t:case_number=CPC-2013-872-SPP-DB-DI t:cpa=Westlake t:apc=C t:case_type=CPC t:geographic_area="DOWNTOWN / WESTLAKE" m:row_number.ckea-5u87=1

series e:ckea-5u87 d:2013-01-01T00:00:00.000Z t:case_number=CPC-2011-927-GPA-ZC-HD-SP-CUB-M1 t:cpa="South Los Angeles" t:apc=S t:case_type=CPC t:geographic_area=SOUTH m:row_number.ckea-5u87=2

series e:ckea-5u87 d:2013-01-01T00:00:00.000Z t:case_number=APCNV-2013-534-ZC-CU-CDO t:cpa="Arleta - Pacoima" t:apc=NV t:case_type=APCNV t:geographic_area="NORTH VALLEY" m:row_number.ckea-5u87=3
```

## Meta Commands

```ls
metric m:row_number.ckea-5u87 p:long l:"Row Number"

entity e:ckea-5u87 l:"Cases Filed 2013" t:attribution="City of Los Angeles, Department of City Planning" t:url=https://data.lacity.org/api/views/ckea-5u87

property e:ckea-5u87 t:meta.view v:id=ckea-5u87 v:category="A Livable and Sustainable City" v:attributionLink=http://planning.lacity.org/ v:averageRating=0 v:name="Cases Filed 2013" v:attribution="City of Los Angeles, Department of City Planning"

property e:ckea-5u87 t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:ckea-5u87 t:meta.view.owner v:id=9jxz-e3ru v:profileImageUrlMedium=/api/users/9jxz-e3ru/profile_images/THUMB v:profileImageUrlLarge=/api/users/9jxz-e3ru/profile_images/LARGE v:screenName="Planning OpenData" v:profileImageUrlSmall=/api/users/9jxz-e3ru/profile_images/TINY v:displayName="Planning OpenData"

property e:ckea-5u87 t:meta.view.tableauthor v:id=9jxz-e3ru v:profileImageUrlMedium=/api/users/9jxz-e3ru/profile_images/THUMB v:profileImageUrlLarge=/api/users/9jxz-e3ru/profile_images/LARGE v:screenName="Planning OpenData" v:profileImageUrlSmall=/api/users/9jxz-e3ru/profile_images/TINY v:roleName=publisher v:displayName="Planning OpenData"
```

## Top Records

```ls
| apc | cpa                                                                        | geographic_area     | case_type | case_number                      | date_filed  | date_completed | 
| === | ========================================================================== | =================== | ========= | ================================ | =========== | ============== | 
| C   | Westlake                                                                   | DOWNTOWN / WESTLAKE | CPC       | CPC-2013-872-SPP-DB-DI           | 27-Mar-2013 | 14-Mar-2014    | 
| S   | South Los Angeles                                                          | SOUTH               | CPC       | CPC-2011-927-GPA-ZC-HD-SP-CUB-M1 | 11-Sep-2013 |                | 
| NV  | Arleta - Pacoima                                                           | NORTH VALLEY        | APCNV     | APCNV-2013-534-ZC-CU-CDO         | 27-Feb-2013 | 15-Oct-2013    | 
| NV  | Mission Hills - Panorama City - North Hills                                | NORTH VALLEY        | APCNV     | APCNV-2013-1276-ZC-ZAA           | 30-Apr-2013 | 19-Feb-2014    | 
| SV  | Reseda - West Van Nuys                                                     | SOUTH VALLEY        | APCSV     | APCSV-2013-846-ZC                | 22-Mar-2013 | 05-Aug-2013    | 
| CW  | Citywide                                                                   | CITYWIDE            | CPC       | CPC-2013-1318-GPA                | 02-May-2013 | 09-Oct-2013    | 
| NV  | Mission Hills - Panorama City - North Hills                                | NORTH VALLEY        | CPC       | CPC-2013-3074-CU-ZAA-SPR         | 02-Oct-2013 |                | 
| C   | Hollywood                                                                  | HOLLYWOOD           | CPC       | CPC-2013-521-DB-SPR              | 26-Feb-2013 |                | 
| SV  | Reseda - West Van Nuys                                                     | SOUTH VALLEY        | APCSV     | APCSV-2013-1388-ZC               | 10-May-2013 | 16-May-2014    | 
| NV  | Sunland - Tujunga - Lake View Terrace - Shadow Hills - East La Tuna Canyon | IN TRANSITION       | CPC       | CPC-2006-4047-CU-PA1             | 24-Jun-2013 | 25-Sep-2013    | 
```