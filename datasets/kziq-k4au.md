# Cases Completed 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cases-completed-2014) |
| Metadata | [Link](https://data.lacity.org/api/views/kziq-k4au) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/kziq-k4au/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/kziq-k4au/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | kziq-k4au |
| Name | Cases Completed 2014 |
| Attribution | City of Los Angeles, Department of City Planning |
| Category | A Livable and Sustainable City |
| Tags | planning, cases completed, entitlement, environmental, development |
| Created | 2016-06-07T22:23:46Z |
| Publication Date | 2016-06-07T22:32:09Z |

## Description

Total Cases Completed by the Department of City Planning for the Year 2014.

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
series e:kziq-k4au d:2014-01-01T00:00:00.000Z t:case_number=ZA-2014-1-CEX t:cpa="Brentwood - Pacific Palisades" t:apc=W t:case_type=ZA t:geographic_area=WEST m:row_number.kziq-k4au=1

series e:kziq-k4au d:2014-01-01T00:00:00.000Z t:case_number=ZA-2011-2700-PAB-EXT t:cpa="Central City" t:apc=C t:case_type=ZA m:row_number.kziq-k4au=2

series e:kziq-k4au d:2014-01-01T00:00:00.000Z t:case_number=ENV-2014-3-CE t:cpa=Venice t:apc=W t:case_type=ENV m:row_number.kziq-k4au=3
```

## Meta Commands

```ls
metric m:row_number.kziq-k4au p:long l:"Row Number"

entity e:kziq-k4au l:"Cases Completed 2014" t:attribution="City of Los Angeles, Department of City Planning" t:url=https://data.lacity.org/api/views/kziq-k4au

property e:kziq-k4au t:meta.view v:id=kziq-k4au v:category="A Livable and Sustainable City" v:attributionLink=http://planning.lacity.org/ v:averageRating=0 v:name="Cases Completed 2014" v:attribution="City of Los Angeles, Department of City Planning"

property e:kziq-k4au t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:kziq-k4au t:meta.view.owner v:id=9jxz-e3ru v:profileImageUrlMedium=/api/users/9jxz-e3ru/profile_images/THUMB v:profileImageUrlLarge=/api/users/9jxz-e3ru/profile_images/LARGE v:screenName="Planning OpenData" v:profileImageUrlSmall=/api/users/9jxz-e3ru/profile_images/TINY v:displayName="Planning OpenData"

property e:kziq-k4au t:meta.view.tableauthor v:id=9jxz-e3ru v:profileImageUrlMedium=/api/users/9jxz-e3ru/profile_images/THUMB v:profileImageUrlLarge=/api/users/9jxz-e3ru/profile_images/LARGE v:screenName="Planning OpenData" v:profileImageUrlSmall=/api/users/9jxz-e3ru/profile_images/TINY v:roleName=publisher v:displayName="Planning OpenData"
```

## Top Records

```ls
| apc | cpa                           | geographic_area     | case_type | case_number          | date_filed  | date_completed | 
| === | ============================= | =================== | ========= | ==================== | =========== | ============== | 
| W   | Brentwood - Pacific Palisades | WEST                | ZA        | ZA-2014-1-CEX        | 02-Jan-2014 | 02-Jan-2014    | 
| C   | Central City                  |                     | ZA        | ZA-2011-2700-PAB-EXT | 02-Jan-2014 | 02-Jan-2014    | 
| W   | Venice                        |                     | ENV       | ENV-2014-3-CE        | 02-Jan-2014 | 02-Jan-2014    | 
| C   | Wilshire                      | WILSHIRE            | ENV       | ENV-2014-6-CE        | 02-Jan-2014 | 02-Jan-2014    | 
| W   | Brentwood - Pacific Palisades | WEST                | ENV       | ENV-2014-9-CE        | 02-Jan-2014 | 02-Jan-2014    | 
| SV  | Encino - Tarzana              |                     | ZA        | ZA-2011-1655-ZAA-EXT | 02-Jan-2014 | 02-Jan-2014    | 
| C   | Wilshire                      | WILSHIRE            | ENV       | ENV-2014-14-CE       | 03-Jan-2014 | 03-Jan-2014    | 
| W   | Palms - Mar Vista - Del Rey   | COASTAL             | ENV       | ENV-2014-17-CE       | 03-Jan-2014 | 03-Jan-2014    | 
| W   | Westwood                      | WEST                | ENV       | ENV-2014-19-CE       | 03-Jan-2014 | 03-Jan-2014    | 
| C   | Westlake                      | DOWNTOWN / WESTLAKE | ENV       | ENV-2014-20-CE       | 03-Jan-2014 | 03-Jan-2014    | 
```