# Tuition Assistance Program (TAP) Recipients & Dollars by College, Sector Group, and Level of Study: Beginning 2000

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/tuition-assistance-program-tap-recipients-dollars-by-college-sector-group-and-level-of-stu) |
| Metadata | [Link](https://data.ny.gov/api/views/ich7-7ewa) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/ich7-7ewa/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/ich7-7ewa/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | ich7-7ewa |
| Name | Tuition Assistance Program (TAP) Recipients & Dollars by College, Sector Group, and Level of Study: Beginning 2000 |
| Attribution | New York State Higher Education Services Corporation |
| Category | Education |
| Tags | tap, postsecondary schools, education |
| Created | 2013-04-15T18:28:23Z |
| Publication Date | 2017-01-27T21:38:41Z |

## Description

The Tuition Assistance Program (TAP), New York's largest student financial aid grant program, helps eligible New York residents attending in-state postsecondary institutions pay for tuition. TAP grants are based on the applicant?s and his or her family?s New York State taxable income.  This data includes TAP award recipients and dollar amounts by college, sector groups, and Level of Study for academic years 2000-2011.

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type | Render Type |
| ======== | ============== | ======================= | ======================= | ========= | =========== |
| Yes      | time           | academic_year           | Academic Year           | number    | number      |
| Yes      | series tag     | tap_college_code        | TAP College Code        | text      | number      |
| Yes      | series tag     | federal_school_code     | Federal School Code     | text      | number      |
| Yes      | series tag     | level                   | Level                   | text      | text        |
| Yes      | series tag     | tap_level_of_study      | TAP Level of Study      | text      | text        |
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
series e:ich7-7ewa d:2015-01-01T00:00:00.000Z t:tap_level_of_study="4 yr Undergrad" t:level=U t:federal_school_code=8614 t:sector_type=PRIVATE t:tap_sector_group="9-CHAPTER XXII" t:tap_college_name="RABBINCAL COL BOBOVER YESHIV BNEI" t:tap_college_code=8266 m:tap_recipient_dollars=785461.5 m:tap_recipient_headcount=177 m:tap_recipient_ftes=166.5

series e:ich7-7ewa d:2015-01-01T00:00:00.000Z t:tap_level_of_study="5 yr Undergrad" t:level=U t:federal_school_code=38023 t:sector_type=PRIVATE t:tap_sector_group="9-CHAPTER XXII" t:tap_college_name="UTA MESIVTA OF KIRYAS JOEL" t:tap_college_code=8298 m:tap_recipient_dollars=895753.5 m:tap_recipient_headcount=191 m:tap_recipient_ftes=189

series e:ich7-7ewa d:2015-01-01T00:00:00.000Z t:tap_level_of_study="5 yr Undergrad" t:level=U t:federal_school_code=2758 t:sector_type=PRIVATE t:tap_sector_group=5-INDEPENDENT t:tap_college_name="MANHATTAN COLLEGE 4 YR UNDERGRAD" t:tap_college_code=405 m:tap_recipient_dollars=16796.29 m:tap_recipient_headcount=5 m:tap_recipient_ftes=3.52
```

## Meta Commands

```ls
metric m:tap_recipient_headcount p:integer l:"TAP Recipient Headcount" d:"Number of recipients as measured by students receiving at least one term award during the academic year." t:dataTypeName=number

metric m:tap_recipient_ftes p:float l:"TAP Recipient FTEs" d:"An FTE of 1.0 means that the person is equivalent to 1 full-time student, while an FTE of 0.5 signals that a student is enrolled half-time." t:dataTypeName=number

metric m:tap_recipient_dollars p:double l:"TAP Recipient Dollars" d:"Total TAP award dollars provided on behalf of TAP recipients attending an Institution." t:dataTypeName=money

entity e:ich7-7ewa l:"Tuition Assistance Program (TAP) Recipients & Dollars by College, Sector Group, and Level of Study: Beginning 2000" t:attribution="New York State Higher Education Services Corporation" t:url=https://data.ny.gov/api/views/ich7-7ewa

property e:ich7-7ewa t:meta.view v:id=ich7-7ewa v:category=Education v:attributionLink=http://www.hesc.ny.gov/content.nsf/SFC/About_TAP v:averageRating=0 v:name="Tuition Assistance Program (TAP) Recipients & Dollars by College, Sector Group, and Level of Study: Beginning 2000" v:attribution="New York State Higher Education Services Corporation"

property e:ich7-7ewa t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:ich7-7ewa t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:ich7-7ewa t:meta.view.metadata.custom_fields.common_core v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| academic_year | tap_college_code | federal_school_code | level | tap_level_of_study | tap_college_name                  | sector_type | tap_sector_group | tap_recipient_headcount | tap_recipient_ftes | tap_recipient_dollars | 
| ============= | ================ | =================== | ===== | ================== | ================================= | =========== | ================ | ======================= | ================== | ===================== | 
| 2015          | 8266             | 8614                | U     | 4 yr Undergrad     | RABBINCAL COL BOBOVER YESHIV BNEI | PRIVATE     | 9-CHAPTER XXII   | 177                     | 166.5              | 785461.50             | 
| 2015          | 8298             | 38023               | U     | 5 yr Undergrad     | UTA MESIVTA OF KIRYAS JOEL        | PRIVATE     | 9-CHAPTER XXII   | 191                     | 189                | 895753.50             | 
| 2015          | 405              | 2758                | U     | 5 yr Undergrad     | MANHATTAN COLLEGE 4 YR UNDERGRAD  | PRIVATE     | 5-INDEPENDENT    | 5                       | 3.52               | 16796.29              | 
| 2015          | 340              | 2742                | U     | 4 yr Undergrad     | JUILLIARD SCHOOL 4YR UNDERGRAD    | PRIVATE     | 5-INDEPENDENT    | 16                      | 16.08              | 56384.66              | 
| 2015          | 1610             | 11614               | U     | 2 yr Undergrad     | CHAMPLAIN VALLEY SCH XRAY TECH    | PRIVATE     | 8-OTHER          | 12                      | 11.5               | 21296.00              | 
| 2015          | 2243             | 6785                | U     | 2 yr Undergrad     | SCHENECTADY COUNTY COMM COLLEGE   | PUBLIC      | 4-SUNY CC        | 1239                    | 904.52             | 2059553.41            | 
| 2015          | 6445             | 6438                | U     | 2 yr Undergrad     | PHILLIPS BETH ISRAEL NURSING BA   | PRIVATE     | 5-INDEPENDENT    | 1                       | 0.5                | 631.75                | 
| 2015          | 745              | 6443                | U     | 2 yr Undergrad     | ST JOHN'S RIVERSIDE HOSP NURS     | PRIVATE     | 5-INDEPENDENT    | 27                      | 14.45              | 46235.58              | 
| 2015          | 905              | 2842                | U     | 5 yr Undergrad     | SUC BUFFALO (UNDERGRAD)           | PUBLIC      | 3-SUNY SO        | 118                     | 85.85              | 349649.89             | 
| 2015          | 6122             | 5208                | U     | 4 yr Undergrad     | COLL WESTCHESTER EVE BACH ONLINE  | PRIVATE     | 6-BUS. DEGREE    | 17                      | 10.46              | 36828.85              | 
```