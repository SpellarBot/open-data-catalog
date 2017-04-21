# Scholarship Recipients and Dollars by Sector Group: Beginning 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/scholarship-recipients-and-dollars-by-sector-group-beginning-2009) |
| Metadata | [Link](https://data.ny.gov/api/views/d8hf-wqd9) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/d8hf-wqd9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/d8hf-wqd9/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | d8hf-wqd9 |
| Name | Scholarship Recipients and Dollars by Sector Group: Beginning 2009 |
| Attribution | New York State Higher Education Services Corporation |
| Category | Education |
| Tags | scholarship, postsecondary schools, education |
| Created | 2013-12-24T15:33:15Z |
| Publication Date | 2017-02-24T19:47:39Z |

## Description

This data includes the number of Scholarship award recipients and dollar amounts by TAP Sector Group beginning academic year 2009 (for HESC-administered scholarships only)

## Columns

```ls
| Included | Schema Type    | Field Name            | Name                  | Data Type | Render Type |
| ======== | ============== | ===================== | ===================== | ========= | =========== |
| Yes      | time           | academic_year         | Academic Year         | number    | number      |
| Yes      | series tag     | tap_sector_group      | TAP Sector Group      | text      | text        |
| Yes      | series tag     | scholarship_name      | Scholarship Name      | text      | text        |
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
series e:d8hf-wqd9 d:2015-01-01T00:00:00.000Z t:scholarship_name="Flight 3407 Memorial Scholarship" t:tap_sector_group="3-SUNY SO" m:scholarship_dollars=33673 m:scholarship_fte=1.5 m:scholarship_headcount=2

series e:d8hf-wqd9 d:2015-01-01T00:00:00.000Z t:scholarship_name="Flight 3407 Memorial Scholarship" t:tap_sector_group=5-INDEPENDENT m:scholarship_dollars=44876 m:scholarship_fte=3 m:scholarship_headcount=3

series e:d8hf-wqd9 d:2015-01-01T00:00:00.000Z t:scholarship_name="Flight 587 Memorial Scholarship" t:tap_sector_group="2-CUNY CC" m:scholarship_dollars=11978.5 m:scholarship_fte=1 m:scholarship_headcount=2
```

## Meta Commands

```ls
metric m:scholarship_headcount p:integer l:"Scholarship Headcount" d:"Number of recipients as measured by students receiving at least one term award during the academic year." t:dataTypeName=number

metric m:scholarship_fte p:float l:"Scholarship FTE" d:"Number of recipients as measured by academic year Full-Time Equivalents: Full Time Equivalent is a unit that indicates the enrollment of a student in credit-bearing courses in a way that makes it comparable across contexts. An FTE of 1.0 means that the person is equivalent to 1 full-time student, while an FTE of 0.5 signals that a student is enrolled half-time." t:dataTypeName=number

metric m:scholarship_dollars p:double l:"Scholarship Dollars" t:dataTypeName=money

entity e:d8hf-wqd9 l:"Scholarship Recipients and Dollars by Sector Group:  Beginning 2009" t:attribution="New York State Higher Education Services Corporation" t:url=https://data.ny.gov/api/views/d8hf-wqd9

property e:d8hf-wqd9 t:meta.view v:id=d8hf-wqd9 v:category=Education v:attributionLink=http://www.hesc.ny.gov/content.nsf/SFC/Grants_Scholarships_and_Awards v:averageRating=0 v:name="Scholarship Recipients and Dollars by Sector Group:  Beginning 2009" v:attribution="New York State Higher Education Services Corporation"

property e:d8hf-wqd9 t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:d8hf-wqd9 t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:d8hf-wqd9 t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| academic_year | tap_sector_group | scholarship_name                         | scholarship_headcount | scholarship_fte | scholarship_dollars | 
| ============= | ================ | ======================================== | ===================== | =============== | =================== | 
| 2015          | 3-SUNY SO        | Flight 3407 Memorial Scholarship         | 2                     | 1.50            | 33673.00            | 
| 2015          | 5-INDEPENDENT    | Flight 3407 Memorial Scholarship         | 3                     | 3.00            | 44876.00            | 
| 2015          | 2-CUNY CC        | Flight 587 Memorial Scholarship          | 2                     | 1.00            | 11978.50            | 
| 2015          | 4-SUNY CC        | Flight 587 Memorial Scholarship          | 2                     | 1.50            | 19135.00            | 
| 2015          | 3-SUNY SO        | Flight 587 Memorial Scholarship          | 3                     | 3.00            | 62496.00            | 
| 2015          | 1-CUNY SR        | Flight 587 Memorial Scholarship          | 8                     | 6.50            | 76330.60            | 
| 2015          | 6-BUS. DEGREE    | Flight 587 Memorial Scholarship          | 2                     | 0.83            | 12444.17            | 
| 2015          | 5-INDEPENDENT    | Flight 587 Memorial Scholarship          | 6                     | 6.00            | 105566.75           | 
| 2015          | 2-CUNY CC        | Military Service Recognition Scholarship | 2                     | 2.00            | 23774.40            | 
| 2015          | 1-CUNY SR        | Military Service Recognition Scholarship | 8                     | 7.00            | 119207.40           | 
```