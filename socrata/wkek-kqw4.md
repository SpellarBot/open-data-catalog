# Cases Completed 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cases-completed-2013-f6728) |
| Metadata | [Link](https://data.lacity.org/api/views/wkek-kqw4) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/wkek-kqw4/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/wkek-kqw4/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | wkek-kqw4 |
| Name | Cases Completed 2013 |
| Attribution | City of Los Angeles, Department of City Planning |
| Category | A Livable and Sustainable City |
| Tags | planning, cases completed, entitlement, environmental, development |
| Created | 2014-05-22T21:46:39Z |
| Publication Date | 2014-05-22T21:48:01Z |

## Description

Total Cases Completed by the Department of City Planning for the Year 2013.

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
series e:wkek-kqw4 d:2013-01-01T00:00:00.000Z t:case_number=CPC-2009-1064-GPA-VZC-HD-SP-CUB-ZV-SPR t:cpa="Brentwood - Pacific Palisades" t:apc=W t:case_type=CPC t:geographic_area="IN TRANSITION" m:row_number.wkek-kqw4=1

series e:wkek-kqw4 d:2013-01-01T00:00:00.000Z t:case_number=APCSV-2012-2415-SPE-SPP t:cpa="Encino - Tarzana" t:apc=SV t:case_type=APCSV t:geographic_area="SOUTH VALLEY" m:row_number.wkek-kqw4=2

series e:wkek-kqw4 d:2013-01-01T00:00:00.000Z t:case_number=APCNV-2012-2711-ZC-DB t:cpa="Mission Hills - Panorama City - North Hills" t:apc=NV t:case_type=APCNV t:geographic_area="NORTH VALLEY" m:row_number.wkek-kqw4=3
```

## Meta Commands

```ls
metric m:row_number.wkek-kqw4 p:long l:"Row Number"

entity e:wkek-kqw4 l:"Cases Completed 2013" t:attribution="City of Los Angeles, Department of City Planning" t:url=https://data.lacity.org/api/views/wkek-kqw4

property e:wkek-kqw4 t:meta.view v:id=wkek-kqw4 v:category="A Livable and Sustainable City" v:attributionLink=http://planning.lacity.org/ v:averageRating=0 v:name="Cases Completed 2013" v:attribution="City of Los Angeles, Department of City Planning"

property e:wkek-kqw4 t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:wkek-kqw4 t:meta.view.owner v:id=9jxz-e3ru v:profileImageUrlMedium=/api/users/9jxz-e3ru/profile_images/THUMB v:profileImageUrlLarge=/api/users/9jxz-e3ru/profile_images/LARGE v:screenName="Planning OpenData" v:profileImageUrlSmall=/api/users/9jxz-e3ru/profile_images/TINY v:displayName="Planning OpenData"

property e:wkek-kqw4 t:meta.view.tableauthor v:id=9jxz-e3ru v:profileImageUrlMedium=/api/users/9jxz-e3ru/profile_images/THUMB v:profileImageUrlLarge=/api/users/9jxz-e3ru/profile_images/LARGE v:screenName="Planning OpenData" v:profileImageUrlSmall=/api/users/9jxz-e3ru/profile_images/TINY v:roleName=publisher v:displayName="Planning OpenData"
```

## Top Records

```ls
| apc | cpa                                                                        | geographic_area | case_type | case_number                            | date_filed  | date_completed | 
| === | ========================================================================== | =============== | ========= | ====================================== | =========== | ============== | 
| W   | Brentwood - Pacific Palisades                                              | IN TRANSITION   | CPC       | CPC-2009-1064-GPA-VZC-HD-SP-CUB-ZV-SPR | 06-Apr-2009 | 16-Dec-2013    | 
| SV  | Encino - Tarzana                                                           | SOUTH VALLEY    | APCSV     | APCSV-2012-2415-SPE-SPP                | 07-Sep-2012 | 19-Mar-2013    | 
| NV  | Mission Hills - Panorama City - North Hills                                | NORTH VALLEY    | APCNV     | APCNV-2012-2711-ZC-DB                  | 02-Oct-2012 | 29-Mar-2013    | 
| NV  | Arleta - Pacoima                                                           | NORTH VALLEY    | APCNV     | APCNV-2013-534-ZC-CU-CDO               | 27-Feb-2013 | 15-Oct-2013    | 
| SV  | Reseda - West Van Nuys                                                     | SOUTH VALLEY    | APCSV     | APCSV-2013-846-ZC                      | 22-Mar-2013 | 05-Aug-2013    | 
| CW  | Citywide                                                                   | CITYWIDE        | CPC       | CPC-2013-1318-GPA                      | 02-May-2013 | 09-Oct-2013    | 
| NV  | Sunland - Tujunga - Lake View Terrace - Shadow Hills - East La Tuna Canyon | IN TRANSITION   | CPC       | CPC-2006-4047-CU-PA1                   | 24-Jun-2013 | 25-Sep-2013    | 
| W   | Westchester - Playa del Rey                                                | COASTAL         | CPC       | CPC-2012-3436-DB-SPR                   | 14-Dec-2012 | 09-Oct-2013    | 
| C   | Hollywood                                                                  | HOLLYWOOD       | APCC      | APCC-2012-2091-SPE-SPP-ZV              | 03-Aug-2012 | 10-Jan-2013    | 
| C   | Wilshire                                                                   | WILSHIRE        | CPC       | CPC-2013-190-RFA                       | 22-Jan-2013 | 26-Aug-2013    | 
```