# Scholarship Recipients And Dollars By College Code: Beginning 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/scholarship-recipients-and-dollars-by-college-code-beginning-2009) |
| Metadata | [Link](https://data.ny.gov/api/views/ww7t-w8k9) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/ww7t-w8k9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/ww7t-w8k9/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | ww7t-w8k9 |
| Name | Scholarship Recipients And Dollars By College Code: Beginning 2009 |
| Attribution | New York State Higher Education Services Corporation |
| Category | Education |
| Tags | scholarship, postsecondary schools, education |
| Created | 2013-12-24T15:09:43Z |
| Publication Date | 2017-02-24T19:47:58Z |

## Description

This data includes the number of Scholarship award recipients and dollar amounts by TAP college code beginning academic year 2009 (for HESC-administered scholarships only)

## Columns

```ls
| Included | Schema Type    | Field Name            | Name                  | Data Type | Render Type |
| ======== | ============== | ===================== | ===================== | ========= | =========== |
| Yes      | time           | academic_year         | Academic Year         | number    | number      |
| Yes      | series tag     | tap_college_code      | TAP College Code      | text      | number      |
| Yes      | series tag     | federal_school_code   | Federal School Code   | text      | number      |
| Yes      | series tag     | tap_college_name      | TAP College Name      | text      | text        |
| Yes      | series tag     | tap_sector_group      | TAP Sector Group      | text      | text        |
| Yes      | numeric metric | scholarship_headcount | Scholarship Headcount | number    | number      |
| Yes      | numeric metric | scholarship_fte       | Scholarship FTE       | number    | number      |
| Yes      | numeric metric | scholarship_dollars   | Scholarship Dollars   | money     | money       |
```

## Time Field

```ls
Value = academic_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:ww7t-w8k9 d:2015-01-01T00:00:00.000Z t:federal_school_code=2696 t:tap_sector_group="1-CUNY SR" t:tap_college_name="CUNY NYC COLLEGE OF TECHNOLOGY" t:tap_college_code=1405 m:scholarship_dollars=139119.86 m:scholarship_fte=99.04 m:scholarship_headcount=126

series e:ww7t-w8k9 d:2015-01-01T00:00:00.000Z t:federal_school_code=2803 t:tap_sector_group=5-INDEPENDENT t:tap_college_name="RENSSELAER POLYTECHNIC INST" t:tap_college_code=635 m:scholarship_dollars=331641.5 m:scholarship_fte=299.5 m:scholarship_headcount=310

series e:ww7t-w8k9 d:2015-01-01T00:00:00.000Z t:federal_school_code=20662 t:tap_sector_group=5-INDEPENDENT t:tap_college_name="THE NEW SCHOOL" t:tap_college_code=1100 m:scholarship_dollars=500.01 m:scholarship_fte=1 m:scholarship_headcount=1
```

## Meta Commands

```ls
metric m:scholarship_headcount p:integer l:"Scholarship Headcount" d:"Number of recipients as measured by students receiving at least one term award during the academic year." t:dataTypeName=number

metric m:scholarship_fte p:float l:"Scholarship FTE" d:"Number of recipients as measured by academic year Full-Time Equivalents: Full Time Equivalent is a unit that indicates the enrollment of a student in credit-bearing courses in a way that makes it comparable across contexts. An FTE of 1.0 means that the person is equivalent to 1 full-time student, while an FTE of 0.5 signals that a student is enrolled half-time." t:dataTypeName=number

metric m:scholarship_dollars p:double l:"Scholarship Dollars" t:dataTypeName=money

entity e:ww7t-w8k9 l:"Scholarship Recipients And Dollars By College Code: Beginning 2009" t:attribution="New York State Higher Education Services Corporation" t:url=https://data.ny.gov/api/views/ww7t-w8k9

property e:ww7t-w8k9 t:meta.view v:id=ww7t-w8k9 v:category=Education v:attributionLink=http://www.hesc.ny.gov/content.nsf/SFC/Grants_Scholarships_and_Awards v:averageRating=0 v:name="Scholarship Recipients And Dollars By College Code: Beginning 2009" v:attribution="New York State Higher Education Services Corporation"

property e:ww7t-w8k9 t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:ww7t-w8k9 t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:ww7t-w8k9 t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| academic_year | tap_college_code | federal_school_code | tap_college_name               | tap_sector_group | scholarship_headcount | scholarship_fte | scholarship_dollars | 
| ============= | ================ | =================== | ============================== | ================ | ===================== | =============== | =================== | 
| 2015          | 1405             | 2696                | CUNY NYC COLLEGE OF TECHNOLOGY | 1-CUNY SR        | 126                   | 99.04           | 139119.86           | 
| 2015          | 635              | 2803                | RENSSELAER POLYTECHNIC INST    | 5-INDEPENDENT    | 310                   | 299.50          | 331641.50           | 
| 2015          | 1100             | 20662               | THE NEW SCHOOL                 | 5-INDEPENDENT    | 1                     | 1.00            | 500.01              | 
| 2015          | 1409             | 7273                | CUNY BARUCH COLLEGE            | 1-CUNY SR        | 352                   | 291.79          | 325163.79           | 
| 2015          | 5830             | 2775                | MOLLOY COLLEGE                 | 5-INDEPENDENT    | 4                     | 2.25            | 58885.00            | 
| 2015          | 2265             | 21691               | DAVIS COLLEGE                  | 5-INDEPENDENT    | 3                     | 2.50            | 17867.00            | 
| 2015          | 1407             | 2697                | CUNY QUEENSBOROUGH CC          | 2-CUNY CC        | 29                    | 20.17           | 49131.94            | 
| 2015          | 640              | 2805                | ROBERTS WESLEYAN COLLEGE       | 5-INDEPENDENT    | 57                    | 53.58           | 76969.08            | 
| 2015          | 2147             | 2877                | ROCKLAND COMMUNITY COLLEGE     | 4-SUNY CC        | 19                    | 14.25           | 62715.75            | 
| 2015          | 2321             | 21700               | SWEDISH INST QRTLY PROGRAMS    | 6-BUS. DEGREE    | 4                     | 2.67            | 9326.68             | 
```