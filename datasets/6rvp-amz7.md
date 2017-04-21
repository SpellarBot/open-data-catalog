# Cases Filed 2015

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cases-filed-2015) |
| Metadata | [Link](https://data.lacity.org/api/views/6rvp-amz7) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/6rvp-amz7/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/6rvp-amz7/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | 6rvp-amz7 |
| Name | Cases Filed 2015 |
| Attribution | City of Los Angeles, Department of City Planning |
| Category | A Livable and Sustainable City |
| Tags | planning, cases filed, entitlement, environmental, development |
| Created | 2016-06-07T22:36:45Z |
| Publication Date | 2016-06-07T22:41:18Z |

## Description

Total Cases Filed with the Department of City Planning for the Year 2015.

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
series e:6rvp-amz7 d:2015-01-01T00:00:00.000Z t:case_number=DIR-2015-1272-CWC t:cpa=Wilshire t:apc=C t:case_type=DIR t:geographic_area=WILSHIRE m:row_number.6rvp-amz7=1

series e:6rvp-amz7 d:2015-01-01T00:00:00.000Z t:case_number=DIR-2015-225-CWC t:cpa="Silver Lake - Echo Park - Elysian Valley" t:apc=E t:case_type=DIR t:geographic_area=EAST m:row_number.6rvp-amz7=2

series e:6rvp-amz7 d:2015-01-01T00:00:00.000Z t:case_number=APCW-2014-364-SPE-SPP-CDP-1A t:cpa=Venice t:apc=W t:case_type=APC t:geographic_area=WEST m:row_number.6rvp-amz7=3
```

## Meta Commands

```ls
metric m:row_number.6rvp-amz7 p:long l:"Row Number"

entity e:6rvp-amz7 l:"Cases Filed 2015" t:attribution="City of Los Angeles, Department of City Planning" t:url=https://data.lacity.org/api/views/6rvp-amz7

property e:6rvp-amz7 t:meta.view v:id=6rvp-amz7 v:category="A Livable and Sustainable City" v:attributionLink=http://planning.lacity.org/ v:averageRating=0 v:name="Cases Filed 2015" v:attribution="City of Los Angeles, Department of City Planning"

property e:6rvp-amz7 t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:6rvp-amz7 t:meta.view.owner v:id=9jxz-e3ru v:profileImageUrlMedium=/api/users/9jxz-e3ru/profile_images/THUMB v:profileImageUrlLarge=/api/users/9jxz-e3ru/profile_images/LARGE v:screenName="Planning OpenData" v:profileImageUrlSmall=/api/users/9jxz-e3ru/profile_images/TINY v:displayName="Planning OpenData"

property e:6rvp-amz7 t:meta.view.tableauthor v:id=9jxz-e3ru v:profileImageUrlMedium=/api/users/9jxz-e3ru/profile_images/THUMB v:profileImageUrlLarge=/api/users/9jxz-e3ru/profile_images/LARGE v:screenName="Planning OpenData" v:profileImageUrlSmall=/api/users/9jxz-e3ru/profile_images/TINY v:roleName=publisher v:displayName="Planning OpenData"
```

## Top Records

```ls
| apc | cpa                                      | geographic_area     | case_type | case_number                  | date_filed  | date_completed | 
| === | ======================================== | =================== | ========= | ============================ | =========== | ============== | 
| C   | Wilshire                                 | WILSHIRE            | DIR       | DIR-2015-1272-CWC            | 01-Jan-2015 | 07-Apr-2015    | 
| E   | Silver Lake - Echo Park - Elysian Valley | EAST                | DIR       | DIR-2015-225-CWC             | 02-Jan-2015 | 20-Jan-2015    | 
| W   | Venice                                   | WEST                | APC       | APCW-2014-364-SPE-SPP-CDP-1A | 02-Jan-2015 | 02-Jan-2015    | 
| C   | Wilshire                                 | WILSHIRE            | ENV       | ENV-2015-2-CE                | 02-Jan-2015 | 02-Jan-2015    | 
| C   | Wilshire                                 | WILSHIRE            | CHC       | CHC-2015-5-HCM               | 02-Jan-2015 | 02-Jan-2015    | 
| C   | Wilshire                                 | WILSHIRE            | DIR       | DIR-2015-1-CCMP              | 02-Jan-2015 | 01-Apr-2015    | 
| SV  | Hollywood                                |                     | PS        | PS-1407-EXT                  | 02-Jan-2015 | 02-Jan-2015    | 
| C   | Central City                             | DOWNTOWN / WESTLAKE | CHC       | CHC-2015-3-HCM               | 02-Jan-2015 | 02-Jan-2015    | 
| C   | Central City                             | DOWNTOWN / WESTLAKE | ENV       | ENV-2015-4-CE                | 02-Jan-2015 | 02-Jan-2015    | 
| C   | Wilshire                                 | WILSHIRE            | ENV       | ENV-2015-6-CE                | 02-Jan-2015 | 02-Jan-2015    | 
```