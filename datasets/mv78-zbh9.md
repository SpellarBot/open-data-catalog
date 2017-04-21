# Aid for Part-Time Study (APTS) Institution Awards Data by College and Sector Group: Beginning 2000

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/aid-for-part-time-study-apts-institution-awards-data-by-college-and-sector-group-beginnin-) |
| Metadata | [Link](https://data.ny.gov/api/views/mv78-zbh9) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/mv78-zbh9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/mv78-zbh9/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | mv78-zbh9 |
| Name | Aid for Part-Time Study (APTS) Institution Awards Data by College and Sector Group: Beginning 2000 |
| Attribution | New York State Higher Education Services Corporation |
| Category | Education |
| Tags | tap, post-secondary schools, education |
| Created | 2013-06-07T18:01:28Z |
| Publication Date | 2017-02-24T19:48:24Z |

## Description

The Aid for Part-Time Study (APTS) program provides grant assistance for eligible part-time students enrolled in approved undergraduate studies.  This data includes APTS award recipients and dollar amounts by college and sector groups beginning with academic year 2000.

## Columns

```ls
| Included | Schema Type    | Field Name                    | Name                          | Data Type | Render Type |
| ======== | ============== | ============================= | ============================= | ========= | =========== |
| Yes      | time           | academic_year                 | Academic Year                 | number    | number      |
| Yes      | series tag     | tap_college_code              | TAP College Code              | text      | number      |
| Yes      | series tag     | federal_school_code           | Federal School Code           | text      | number      |
| Yes      | series tag     | level                         | Level                         | text      | text        |
| Yes      | series tag     | tap_college_name              | TAP College Name              | text      | text        |
| Yes      | series tag     | sector_type                   | Sector Type                   | text      | text        |
| Yes      | series tag     | tap_sector_group              | TAP Sector Group              | text      | text        |
| Yes      | numeric metric | apts_allocation               | APTS Allocation               | money     | money       |
| Yes      | numeric metric | apts_reimbursed_award_dollars | APTS Reimbursed Award Dollars | money     | money       |
| Yes      | numeric metric | apts_number_of_recipients     | APTS Number of Recipients     | number    | number      |
| Yes      | numeric metric | apts_average_award            | APTS Average Award            | money     | money       |
```

## Time Field

```ls
Value = academic_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:mv78-zbh9 d:2015-01-01T00:00:00.000Z t:level=U t:federal_school_code=5208 t:sector_type=PRIVATE t:tap_sector_group="6-BUS. DEGREE" t:tap_college_name="COLL WESTCHESTER 2YR EVE" t:tap_college_code=7121 m:apts_allocation=9508 m:apts_number_of_recipients=0 m:apts_average_award=0 m:apts_reimbursed_award_dollars=0

series e:mv78-zbh9 d:2015-01-01T00:00:00.000Z t:level=U t:federal_school_code=2735 t:sector_type=PRIVATE t:tap_sector_group=5-INDEPENDENT t:tap_college_name="HILBERT COLLEGE" t:tap_college_code=2083 m:apts_allocation=7377 m:apts_number_of_recipients=7 m:apts_average_award=1044 m:apts_reimbursed_award_dollars=7310

series e:mv78-zbh9 d:2015-01-01T00:00:00.000Z t:level=U t:federal_school_code=8611 t:sector_type=PUBLIC t:tap_sector_group="2-CUNY CC" t:tap_college_name="CUNY HOSTOS CC" t:tap_college_code=1401 m:apts_allocation=267000 m:apts_number_of_recipients=374 m:apts_average_award=568 m:apts_reimbursed_award_dollars=212312
```

## Meta Commands

```ls
metric m:apts_allocation p:integer l:"APTS Allocation" d:"APTS Dollars that is allocated to institutions." t:dataTypeName=money

metric m:apts_reimbursed_award_dollars p:integer l:"APTS Reimbursed Award Dollars" d:"APTS Award dollars that are reimbursed to the institutions." t:dataTypeName=money

metric m:apts_number_of_recipients p:integer l:"APTS Number of Recipients" d:"APTS Number of recipients that receive a APTS award." t:dataTypeName=number

metric m:apts_average_award p:integer l:"APTS Average Award" d:"APTS Average award received by each institution." t:dataTypeName=money

entity e:mv78-zbh9 l:"Aid for Part-Time Study (APTS) Institution Awards Data by College and Sector Group:  Beginning 2000" t:attribution="New York State Higher Education Services Corporation" t:url=https://data.ny.gov/api/views/mv78-zbh9

property e:mv78-zbh9 t:meta.view v:id=mv78-zbh9 v:category=Education v:attributionLink=http://www.hesc.ny.gov/content.nsf/SFC/Aid_for_PartTime_Study v:averageRating=0 v:name="Aid for Part-Time Study (APTS) Institution Awards Data by College and Sector Group:  Beginning 2000" v:attribution="New York State Higher Education Services Corporation"

property e:mv78-zbh9 t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:mv78-zbh9 t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:mv78-zbh9 t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| academic_year | tap_college_code | federal_school_code | level | tap_college_name                  | sector_type | tap_sector_group | apts_allocation | apts_reimbursed_award_dollars | apts_number_of_recipients | apts_average_award | 
| ============= | ================ | =================== | ===== | ================================= | =========== | ================ | =============== | ============================= | ========================= | ================== | 
| 2015          | 7121             | 5208                | U     | COLL WESTCHESTER 2YR EVE          | PRIVATE     | 6-BUS. DEGREE    | 9508            | 0                             | 0                         | 0                  | 
| 2015          | 2083             | 2735                | U     | HILBERT COLLEGE                   | PRIVATE     | 5-INDEPENDENT    | 7377            | 7310                          | 7                         | 1044               | 
| 2015          | 1401             | 8611                | U     | CUNY HOSTOS CC                    | PUBLIC      | 2-CUNY CC        | 267000          | 212312                        | 374                       | 568                | 
| 2015          | 905              | 2842                | U     | SUC BUFFALO (UNDERGRAD)           | PUBLIC      | 3-SUNY SO        | 74347           | 68640                         | 85                        | 807                | 
| 2015          | 960              | 2668                | U     | SUC CERAMICS AT ALFRED UNIV 4YR U | PUBLIC      | 3-SUNY SO        | 983             | 0                             | 0                         | 0                  | 
| 2015          | 130              | 2703                | U     | COL OF MT ST VINCENT 4YR SEM      | PRIVATE     | 5-INDEPENDENT    | 16368           | 16368                         | 14                        | 1169               | 
| 2015          | 2050             | 2713                | U     | DOMINICAN COLLEGE BLAUVELT 4YR UG | PRIVATE     | 5-INDEPENDENT    | 16803           | 16664                         | 12                        | 1389               | 
| 2015          | 420              | 2760                | U     | MANHATTANVILLE COLLEGE 4YR UNDERG | PRIVATE     | 5-INDEPENDENT    | 3852            | 0                             | 0                         | 0                  | 
| 2015          | 3010             | 2855                | U     | SUNY COLLEGE OF TECH AT CANTON    | PUBLIC      | 3-SUNY SO        | 28443           | 25350                         | 45                        | 563                | 
| 2015          | 970              | 6791                | U     | SUC PURCHASE (UNDERGRAD)          | PUBLIC      | 3-SUNY SO        | 18935           | 13100                         | 10                        | 1310               | 
```