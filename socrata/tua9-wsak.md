# Tuition Assistance Program (TAP) Recipients & Dollars by College and Sector Group: Beginning 2000

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/tuition-assistance-program-tap-recipients-dollars-by-college-and-sector-group-beginning-20) |
| Metadata | [Link](https://data.ny.gov/api/views/tua9-wsak) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/tua9-wsak/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/tua9-wsak/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | tua9-wsak |
| Name | Tuition Assistance Program (TAP) Recipients & Dollars by College and Sector Group: Beginning 2000 |
| Attribution | New York State Higher Education Services Corporation |
| Category | Education |
| Tags | tap, secondary schools, education |
| Created | 2013-02-26T22:29:56Z |
| Publication Date | 2017-01-27T21:38:30Z |

## Description

The Tuition Assistance Program (TAP), New York's largest student financial aid grant program, helps eligible New York residents attending in-state postsecondary institutions pay for tuition. TAP grants are based on the applicant?s and his or her family?s New York State taxable income.  This data includes TAP award recipients and dollar amounts by college and sector groups starting for academic years 2000.

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type | Render Type |
| ======== | ============== | ======================= | ======================= | ========= | =========== |
| Yes      | time           | academic_year           | Academic Year           | number    | number      |
| Yes      | series tag     | tap_college_code        | TAP College Code        | text      | number      |
| Yes      | series tag     | federal_school_code     | Federal School Code     | text      | number      |
| Yes      | series tag     | tap_college_name        | TAP College Name        | text      | text        |
| Yes      | series tag     | sector_type             | Sector Type             | text      | text        |
| Yes      | series tag     | tap_sector_group        | TAP Sector Group        | text      | text        |
| Yes      | numeric metric | tap_recipient_headcount | TAP Recipient Headcount | number    | number      |
| Yes      | numeric metric | tap_recipient_ftes      | TAP Recipient FTEs      | number    | number      |
| Yes      | numeric metric | tap_recipient_dollars   | TAP Recipient Dollars   | money     | money       |
```

## Time Field

```ls
Value = academic_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:tua9-wsak d:2015-01-01T00:00:00.000Z t:federal_school_code=20937 t:sector_type=PRIVATE t:tap_sector_group="6-BUS. DEGREE" t:tap_college_name="LONG ISLAND BUS INST UG SEMESTER" t:tap_college_code=7738 m:tap_recipient_dollars=3097403.39 m:tap_recipient_headcount=1053 m:tap_recipient_ftes=874.11

series e:tua9-wsak d:2015-01-01T00:00:00.000Z t:federal_school_code=9479 t:sector_type=PRIVATE t:tap_sector_group=5-INDEPENDENT t:tap_college_name="ST PAUL'S SCH NURSING SI" t:tap_college_code=836 m:tap_recipient_dollars=306437.92 m:tap_recipient_headcount=119 m:tap_recipient_ftes=89.29

series e:tua9-wsak d:2015-01-01T00:00:00.000Z t:federal_school_code=2713 t:sector_type=PRIVATE t:tap_sector_group=5-INDEPENDENT t:tap_college_name="DOMINICAN COLLEGE-WEEKEND 4YR UG" t:tap_college_code=2051 m:tap_recipient_dollars=15067.48 m:tap_recipient_headcount=9 m:tap_recipient_ftes=4.94
```

## Meta Commands

```ls
metric m:tap_recipient_headcount p:integer l:"TAP Recipient Headcount" d:"Number of recipients as measured by students receiving at least one term award during the academic year." t:dataTypeName=number

metric m:tap_recipient_ftes p:float l:"TAP Recipient FTEs" d:"Full Time Equivalent is a unit that indicates the enrollment of a student in credit-bearing courses in a way that makes it comparable across contexts. An FTE of 1.0 means that the person is equivalent to 1 full-time student, while an FTE of 0.5 signals th" t:dataTypeName=number

metric m:tap_recipient_dollars p:double l:"TAP Recipient Dollars" d:"Total TAP award dollars provided on behalf of TAP recipients attending an Institution." t:dataTypeName=money

entity e:tua9-wsak l:"Tuition Assistance Program (TAP) Recipients & Dollars by College and Sector Group: Beginning 2000" t:attribution="New York State Higher Education Services Corporation" t:url=https://data.ny.gov/api/views/tua9-wsak

property e:tua9-wsak t:meta.view v:id=tua9-wsak v:category=Education v:attributionLink=http://www.hesc.ny.gov/content.nsf/SFC/About_TAP v:averageRating=0 v:name="Tuition Assistance Program (TAP) Recipients & Dollars by College and Sector Group: Beginning 2000" v:attribution="New York State Higher Education Services Corporation"

property e:tua9-wsak t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:tua9-wsak t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:tua9-wsak t:meta.view.metadata.custom_fields.common_core v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| academic_year | tap_college_code | federal_school_code | tap_college_name                 | sector_type | tap_sector_group | tap_recipient_headcount | tap_recipient_ftes | tap_recipient_dollars | 
| ============= | ================ | =================== | ================================ | =========== | ================ | ======================= | ================== | ===================== | 
| 2015          | 7738             | 20937               | LONG ISLAND BUS INST UG SEMESTER | PRIVATE     | 6-BUS. DEGREE    | 1053                    | 874.11             | 3097403.39            | 
| 2015          | 836              | 9479                | ST PAUL'S SCH NURSING SI         | PRIVATE     | 5-INDEPENDENT    | 119                     | 89.29              | 306437.92             | 
| 2015          | 2051             | 2713                | DOMINICAN COLLEGE-WEEKEND 4YR UG | PRIVATE     | 5-INDEPENDENT    | 9                       | 4.94               | 15067.48              | 
| 2015          | 2243             | 6785                | SCHENECTADY COUNTY COMM COLLEGE  | PUBLIC      | 4-SUNY CC        | 1239                    | 904.52             | 2059553.41            | 
| 2015          | 8312             | 41381               | YESHIVA OF MACHZIKAI HADAS       | PRIVATE     | 9-CHAPTER XXII   | 253                     | 230                | 1097074.00            | 
| 2015          | 7262             | 20757               | BRIARCLIFFE COLL WOODBURY 2YR    | PRIVATE     | 6-BUS. DEGREE    | 134                     | 99.36              | 378548.90             | 
| 2015          | 8308             | 11821               | YESHIVATH ZICHRON MOSHE          | PRIVATE     | 9-CHAPTER XXII   | 25                      | 19                 | 74964.50              | 
| 2015          | 90               | 2681                | CANISIUS COLLEGE 4YR UNDERGRAD   | PRIVATE     | 5-INDEPENDENT    | 1092                    | 1025.02            | 2788119.15            | 
| 2015          | 8328             | 13027               | YESHIVATH VIZNITZ                | PRIVATE     | 9-CHAPTER XXII   | 398                     | 394                | 1897197.00            | 
| 2015          | 1418             | 4759                | CUNY YORK COLLEGE                | PUBLIC      | 1-CUNY SR        | 3751                    | 2970.43            | 11512833.12           | 
```