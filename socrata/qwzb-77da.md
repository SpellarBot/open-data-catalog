# Cases Filed 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cases-filed-2014) |
| Metadata | [Link](https://data.lacity.org/api/views/qwzb-77da) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/qwzb-77da/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/qwzb-77da/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | qwzb-77da |
| Name | Cases Filed 2014 |
| Attribution | City of Los Angeles, Department of City Planning |
| Category | A Livable and Sustainable City |
| Tags | planning, cases filed, entitlement, environmental, development |
| Created | 2016-06-07T22:42:26Z |
| Publication Date | 2016-06-07T22:46:47Z |

## Description

Total Cases Filed with the Department of City Planning for the Year 2014.

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
Value = 2014
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = date_filed,date_completed
```

## Data Commands

```ls
series e:qwzb-77da d:2014-01-01T00:00:00.000Z t:case_number=AA-2014-8-WTM t:cpa="Brentwood - Pacific Palisades" t:apc=W t:case_type=AA t:geographic_area=WEST m:row_number.qwzb-77da=1

series e:qwzb-77da d:2014-01-01T00:00:00.000Z t:case_number=DIR-2014-21-CWC t:cpa="West Adams - Baldwin Hills - Leimert" t:apc=S t:case_type=DIR t:geographic_area=SOUTH m:row_number.qwzb-77da=2

series e:qwzb-77da d:2014-01-01T00:00:00.000Z t:case_number=ZA-2014-5-CUB t:cpa=Wilshire t:apc=C t:case_type=ZA t:geographic_area=WILSHIRE m:row_number.qwzb-77da=3
```

## Meta Commands

```ls
metric m:row_number.qwzb-77da p:long l:"Row Number"

entity e:qwzb-77da l:"Cases Filed 2014" t:attribution="City of Los Angeles, Department of City Planning" t:url=https://data.lacity.org/api/views/qwzb-77da

property e:qwzb-77da t:meta.view v:id=qwzb-77da v:category="A Livable and Sustainable City" v:attributionLink=http://planning.lacity.org/ v:averageRating=0 v:name="Cases Filed 2014" v:attribution="City of Los Angeles, Department of City Planning"

property e:qwzb-77da t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:qwzb-77da t:meta.view.owner v:id=9jxz-e3ru v:profileImageUrlMedium=/api/users/9jxz-e3ru/profile_images/THUMB v:profileImageUrlLarge=/api/users/9jxz-e3ru/profile_images/LARGE v:screenName="Planning OpenData" v:profileImageUrlSmall=/api/users/9jxz-e3ru/profile_images/TINY v:displayName="Planning OpenData"

property e:qwzb-77da t:meta.view.tableauthor v:id=9jxz-e3ru v:profileImageUrlMedium=/api/users/9jxz-e3ru/profile_images/THUMB v:profileImageUrlLarge=/api/users/9jxz-e3ru/profile_images/LARGE v:screenName="Planning OpenData" v:profileImageUrlSmall=/api/users/9jxz-e3ru/profile_images/TINY v:roleName=publisher v:displayName="Planning OpenData"
```

## Top Records

```ls
| apc | cpa                                  | geographic_area | case_type | case_number         | date_filed  | date_completed | 
| === | ==================================== | =============== | ========= | =================== | =========== | ============== | 
| W   | Brentwood - Pacific Palisades        | WEST            | AA        | AA-2014-8-WTM       | 02-Jan-2014 | 27-Mar-2014    | 
| S   | West Adams - Baldwin Hills - Leimert | SOUTH           | DIR       | DIR-2014-21-CWC     | 02-Jan-2014 | 03-Jan-2014    | 
| C   | Wilshire                             | WILSHIRE        | ZA        | ZA-2014-5-CUB       | 02-Jan-2014 | 14-Jul-2014    | 
| W   | Brentwood - Pacific Palisades        | WEST            | AA        | AA-2014-10-DPS      | 02-Jan-2014 | 17-Oct-2014    | 
| W   | Brentwood - Pacific Palisades        | WEST            | ZA        | ZA-2014-11-CEX      | 02-Jan-2014 | 02-Jan-2014    | 
| W   | Venice                               | WEST            | ZA        | ZA-2004-7596-CU-PA3 | 02-Jan-2014 | 02-Apr-2015    | 
| E   | Northeast Los Angeles                | EAST            | ENV       | ENV-2014-7-MND      | 02-Jan-2014 | 19-May-2014    | 
| E   | Northeast Los Angeles                | EAST            | VTT       | VTT-72663-SL        | 02-Jan-2014 | 02-Jan-2014    | 
| C   | Wilshire                             | WILSHIRE        | DIR       | DIR-2014-4-CWC      | 02-Jan-2014 | 02-Jan-2014    | 
| W   | Brentwood - Pacific Palisades        | WEST            | ZA        | ZA-2014-1-CEX       | 02-Jan-2014 | 02-Jan-2014    | 
```