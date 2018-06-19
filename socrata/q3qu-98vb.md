# Building and Safety Code Enforcement Case (Closed)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/building-and-safety-code-enforcement-case-closed-02a67) |
| Metadata | [Link](https://data.lacity.org/api/views/q3qu-98vb) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/q3qu-98vb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/q3qu-98vb/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | q3qu-98vb |
| Name | Building and Safety Code Enforcement Case (Closed) |
| Category | A Safe City |
| Tags | ladbs, department of building and safety, building and safety, building, safety, construction services, construction, code enforcement, case number, case, violation, citation, billboard, sign, aim... |
| Created | 2014-06-06T19:00:49Z |
| Publication Date | 2017-01-06T00:01:12Z |

## Description

The Department of Building and Safety is tasked with the enforcement of the City's building, electrical, mechanical and zoning regulations, which are elements of the Los Angeles Municipal Code. A Code Enforcement Case may originate from a customer service request to investigate a possible Code violation, from a planned and authorized inspection of a neighborhood for the purpose of reducing blight, or from a proactive inspection of a site due to an observed hazardous condition.  A case is closed (indicated by a "C" status) when the site satisfies the requirements for Code compliance, or when no Code violation is found.  A case remains open (indicated by an "O" status) until the site satisfies the requirements for Code compliance.

## Columns

```ls
| Included | Schema Type | Field Name          | Name                               | Data Type     | Render Type   |
| ======== | =========== | =================== | ================================== | ============= | ============= |
| Yes      | series tag  | case_number         | Case Number                        | text          | text          |
| Yes      | series tag  | ladbs_insp_dist     | LADBS Inspection District          | text          | text          |
| No       |             | addr_hse_num        | Address House Number               | text          | text          |
| No       |             | addr_hse_frac_num   | Address House Fraction Number      | text          | text          |
| Yes      | series tag  | addr_str_dir        | Address Street Direction           | text          | text          |
| Yes      | series tag  | addr_str_name       | Address Street Name                | text          | text          |
| Yes      | series tag  | addr_str_suffix     | Address Street Suffix              | text          | text          |
| Yes      | series tag  | addr_str_suffix_dir | Address Street Suffix Direction    | text          | text          |
| No       |             | addr_zip            | Address Zip                        | text          | text          |
| Yes      | time        | date_case_gen       | Date Case Generated                | calendar_date | calendar_date |
| No       |             | date_case_closed    | Date Case Closed                   | calendar_date | calendar_date |
| Yes      | series tag  | pin                 | Parcel Identification Number (PIN) | text          | text          |
| Yes      | series tag  | case_type           | Case Type                          | text          | text          |
| Yes      | series tag  | apc                 | Area Planning Commission (APC)     | text          | text          |
| Yes      | series tag  | status_of_case      | Status of Case                     | text          | text          |
```

## Time Field

```ls
Value = date_case_gen
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = addr_hse_num,addr_hse_frac_num,addr_zip,date_case_closed
```

## Data Commands

```ls
series e:q3qu-98vb d:2016-07-06T00:00:00.000Z t:addr_str_name=OSBORNE t:case_number=725835 t:pin="195B149    97" t:apc="North Valley" t:case_type=PACE t:status_of_case=C t:addr_str_dir=W t:addr_str_suffix=ST t:ladbs_insp_dist=8121 m:row_number.q3qu-98vb=1

series e:q3qu-98vb d:2016-07-07T00:00:00.000Z t:addr_str_name=LEADWELL t:case_number=726167 t:pin="186B141   611" t:apc="South Valley" t:case_type=PACE t:status_of_case=C t:addr_str_dir=W t:addr_str_suffix=ST t:ladbs_insp_dist=8125 m:row_number.q3qu-98vb=2

series e:q3qu-98vb d:2016-07-06T00:00:00.000Z t:addr_str_name="NEW HAMPSHIRE" t:case_number=726033 t:pin="099B197   892" t:apc="South Los Angeles" t:case_type=PACE t:status_of_case=C t:addr_str_dir=S t:addr_str_suffix=AVE t:ladbs_insp_dist=8133 m:row_number.q3qu-98vb=3
```

## Meta Commands

```ls
metric m:row_number.q3qu-98vb p:long l:"Row Number"

entity e:q3qu-98vb l:"Building and Safety Code Enforcement Case (Closed)" t:url=https://data.lacity.org/api/views/q3qu-98vb

property e:q3qu-98vb t:meta.view v:id=q3qu-98vb v:category="A Safe City" v:averageRating=0 v:name="Building and Safety Code Enforcement Case (Closed)"

property e:q3qu-98vb t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:q3qu-98vb t:meta.view.owner v:id=tdwf-cih6 v:profileImageUrlMedium=/api/users/tdwf-cih6/profile_images/THUMB v:profileImageUrlLarge=/api/users/tdwf-cih6/profile_images/LARGE v:screenName="Building and Safety OpenData" v:profileImageUrlSmall=/api/users/tdwf-cih6/profile_images/TINY v:displayName="Building and Safety OpenData"

property e:q3qu-98vb t:meta.view.tableauthor v:id=tdwf-cih6 v:profileImageUrlMedium=/api/users/tdwf-cih6/profile_images/THUMB v:profileImageUrlLarge=/api/users/tdwf-cih6/profile_images/LARGE v:screenName="Building and Safety OpenData" v:profileImageUrlSmall=/api/users/tdwf-cih6/profile_images/TINY v:roleName=publisher v:displayName="Building and Safety OpenData"
```

## Top Records

```ls
| case_number | ladbs_insp_dist | addr_hse_num | addr_hse_frac_num | addr_str_dir | addr_str_name | addr_str_suffix | addr_str_suffix_dir | addr_zip | date_case_gen       | date_case_closed    | pin           | case_type | apc               | status_of_case | 
| =========== | =============== | ============ | ================= | ============ | ============= | =============== | =================== | ======== | =================== | =================== | ============= | ========= | ================= | ============== | 
| 725835      | 8121            | 14531        |                   | W            | OSBORNE       | ST              |                     | 91402    | 2016-07-06T00:00:00 | 2016-07-06T00:00:00 | 195B149 97    | PACE      | North Valley      | C              | 
| 726167      | 8125            | 16027        |                   | W            | LEADWELL      | ST              |                     | 91406    | 2016-07-07T00:00:00 | 2016-07-07T00:00:00 | 186B141 611   | PACE      | South Valley      | C              | 
| 726033      | 8133            | 8012         |                   | S            | NEW HAMPSHIRE | AVE             |                     | 90044    | 2016-07-06T00:00:00 | 2016-07-06T00:00:00 | 099B197 892   | PACE      | South Los Angeles | C              | 
| 725934      | 8132            | 2111         |                   | W            | 79TH          | ST              |                     | 90047    | 2016-07-06T00:00:00 | 2016-07-06T00:00:00 | 099B189 482   | PACE      | South Los Angeles | C              | 
| 726362      | 8132            | 2018         |                   | W            | 79TH          | ST              |                     | 90047    | 2016-07-07T00:00:00 | 2016-07-07T00:00:00 | 099B189 522   | PACE      | South Los Angeles | C              | 
| 719323      | 2142            | 2001         |                   | W            | BAXTER        | ST              |                     | 90039    | 2016-05-06T00:00:00 | 2016-07-07T00:00:00 | 145-5A211 396 | GENERAL   | East Los Angeles  | C              | 
| 726100      | 8120            | 15938        |                   | W            | WYANDOTTE     | ST              |                     | 91406    | 2016-07-07T00:00:00 | 2016-07-07T00:00:00 | 186B141 789   | PACE      | South Valley      | C              | 
| 721740      | 8121            | 8352         |                   | N            | MURIETTA      | AVE             |                     | 91402    | 2016-05-24T00:00:00 | 2016-07-05T00:00:00 | 192B153 601   | PACE      | North Valley      | C              | 
| 725814      | 8121            | 14224        |                   | W            | OSBORNE       | ST              |                     | 91402    | 2016-07-06T00:00:00 | 2016-07-06T00:00:00 | 195B153 305   | PACE      | North Valley      | C              | 
| 726326      | 8132            | 319          |                   | N            | MESA          | ST              |                     | 90731    | 2016-07-07T00:00:00 | 2016-07-07T00:00:00 | 018B201 421   | PACE      | Harbor            | C              | 
```