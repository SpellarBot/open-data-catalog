# Cases Completed 2015

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cases-completed-2015) |
| Metadata | [Link](https://data.lacity.org/api/views/c8zs-6yn8) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/c8zs-6yn8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/c8zs-6yn8/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | c8zs-6yn8 |
| Name | Cases Completed 2015 |
| Attribution | City of Los Angeles, Department of City Planning |
| Category | A Livable and Sustainable City |
| Tags | planning, cases completed, entitlement, environmental, development |
| Created | 2016-06-07T22:03:33Z |
| Publication Date | 2016-06-07T22:17:50Z |

## Description

Total Cases Completed by the Department of City Planning for the Year 2015.

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
Value = 2015
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = date_filed,date_completed
```

## Data Commands

```ls
series e:c8zs-6yn8 d:2015-01-01T00:00:00.000Z t:case_number=ZA-2014-1207-ZAA t:cpa="Sherman Oaks - Studio City - Toluca Lake - Cahuenga Pass" t:apc=SV t:case_type=ZA t:geographic_area="SOUTH VALLEY" m:row_number.c8zs-6yn8=1

series e:c8zs-6yn8 d:2015-01-01T00:00:00.000Z t:case_number=ZA-2014-1400-ZAA t:cpa="Encino - Tarzana" t:apc=SV t:case_type=ZA t:geographic_area="SOUTH VALLEY" m:row_number.c8zs-6yn8=2

series e:c8zs-6yn8 d:2015-01-01T00:00:00.000Z t:case_number=ZA-1997-988-PAD-PA3 t:cpa="Encino - Tarzana" t:apc=SV t:case_type=ZA t:geographic_area="SOUTH VALLEY" m:row_number.c8zs-6yn8=3
```

## Meta Commands

```ls
metric m:row_number.c8zs-6yn8 p:long l:"Row Number"

entity e:c8zs-6yn8 l:"Cases Completed 2015" t:attribution="City of Los Angeles, Department of City Planning" t:url=https://data.lacity.org/api/views/c8zs-6yn8

property e:c8zs-6yn8 t:meta.view v:id=c8zs-6yn8 v:category="A Livable and Sustainable City" v:attributionLink=http://planning.lacity.org/ v:averageRating=0 v:name="Cases Completed 2015" v:attribution="City of Los Angeles, Department of City Planning"

property e:c8zs-6yn8 t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:c8zs-6yn8 t:meta.view.owner v:id=9jxz-e3ru v:profileImageUrlMedium=/api/users/9jxz-e3ru/profile_images/THUMB v:profileImageUrlLarge=/api/users/9jxz-e3ru/profile_images/LARGE v:screenName="Planning OpenData" v:profileImageUrlSmall=/api/users/9jxz-e3ru/profile_images/TINY v:displayName="Planning OpenData"

property e:c8zs-6yn8 t:meta.view.tableauthor v:id=9jxz-e3ru v:profileImageUrlMedium=/api/users/9jxz-e3ru/profile_images/THUMB v:profileImageUrlLarge=/api/users/9jxz-e3ru/profile_images/LARGE v:screenName="Planning OpenData" v:profileImageUrlSmall=/api/users/9jxz-e3ru/profile_images/TINY v:roleName=publisher v:displayName="Planning OpenData"
```

## Top Records

```ls
| apc | cpa                                                      | geographic_area     | case_type | case_number         | date_filed  | date_completed | 
| === | ======================================================== | =================== | ========= | =================== | =========== | ============== | 
| SV  | Sherman Oaks - Studio City - Toluca Lake - Cahuenga Pass | SOUTH VALLEY        | ZA        | ZA-2014-1207-ZAA    | 09-Apr-2014 | 02-Jan-2015    | 
| SV  | Encino - Tarzana                                         | SOUTH VALLEY        | ZA        | ZA-2014-1400-ZAA    | 21-Apr-2014 | 02-Jan-2015    | 
| SV  | Encino - Tarzana                                         | SOUTH VALLEY        | ZA        | ZA-1997-988-PAD-PA3 | 06-May-2014 | 02-Jan-2015    | 
| SV  | North Hollywood - Valley Village                         | SOUTH VALLEY        | AA        | AA-2014-3532-PMLA   | 22-Sep-2014 | 02-Jan-2015    | 
| C   | Wilshire                                                 | WILSHIRE            | ENV       | ENV-2015-2-CE       | 02-Jan-2015 | 02-Jan-2015    | 
| SV  | Reseda - West Van Nuys                                   | SOUTH VALLEY        | AA        | AA-2014-1758-PMLA   | 16-May-2014 | 02-Jan-2015    | 
| SV  | North Hollywood - Valley Village                         | SOUTH VALLEY        | VTT       | VTT-72384-SL        | 04-Dec-2013 | 02-Jan-2015    | 
| C   | Central City North                                       | DOWNTOWN / WESTLAKE | VTT       | VTT-72410-SL        | 19-Jul-2013 | 02-Jan-2015    | 
| S   | South Los Angeles                                        | SOUTH               | DIR       | DIR-2011-2771-COA   | 26-Oct-2011 | 02-Jan-2015    | 
| E   | Silver Lake - Echo Park - Elysian Valley                 | EAST                | ZA        | ZA-2014-2720-ZV     | 25-Jul-2014 | 02-Jan-2015    | 
```