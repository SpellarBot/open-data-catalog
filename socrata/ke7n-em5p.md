# Loan Forgiveness Awards Administered by Higher Education Services Corp: Beginning 2011

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/loan-forgiveness-awards-administered-by-higher-education-services-corp-beginning-2011) |
| Metadata | [Link](https://data.ny.gov/api/views/ke7n-em5p) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/ke7n-em5p/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/ke7n-em5p/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | ke7n-em5p |
| Name | Loan Forgiveness Awards Administered by Higher Education Services Corp: Beginning 2011 |
| Attribution | New York State Higher Education Services Corporation |
| Category | Education |
| Tags | scholarship, postsecondary schools, education |
| Created | 2014-05-27T13:29:03Z |
| Publication Date | 2014-06-19T16:52:24Z |

## Description

This data includes the number of Loan Forgiveness recipients by program type and the region, as designated by the Department of Labor, in which they are employed beginning award year 2011 (for HESC-administered Loan Forgiveness programs only).  Data has been collated by recipient region of employment.  For this purpose, the current New York State Department of Labor definitions of New York State Regions, as listed on their public web site, were used.

## Columns

```ls
| Included | Schema Type    | Field Name                         | Name                               | Data Type | Render Type |
| ======== | ============== | ================================== | ================================== | ========= | =========== |
| Yes      | time           | award_year                         | Award Year                         | number    | number      |
| Yes      | series tag     | loan_forgiveness_program_name      | Loan Forgiveness Program Name      | text      | text        |
| Yes      | series tag     | region_name                        | Region Name                        | text      | text        |
| Yes      | numeric metric | loan_forgiveness_program_headcount | Loan Forgiveness Program Headcount | number    | number      |
| Yes      | numeric metric | loan_forgiveness_program_dollars   | Loan Forgiveness Program Dollars   | money     | money       |
```

## Time Field

```ls
Value = award_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:ke7n-em5p d:2012-01-01T00:00:00.000Z t:region_name="Capital District" t:loan_forgiveness_program_name="John R. Justice Student Loan Repayment Program" m:loan_forgiveness_program_headcount=8 m:loan_forgiveness_program_dollars=7922.45

series e:ke7n-em5p d:2012-01-01T00:00:00.000Z t:region_name="Central New York" t:loan_forgiveness_program_name="John R. Justice Student Loan Repayment Program" m:loan_forgiveness_program_headcount=3 m:loan_forgiveness_program_dollars=2915.28

series e:ke7n-em5p d:2012-01-01T00:00:00.000Z t:region_name="Finger Lakes" t:loan_forgiveness_program_name="John R. Justice Student Loan Repayment Program" m:loan_forgiveness_program_headcount=8 m:loan_forgiveness_program_dollars=7922.44
```

## Meta Commands

```ls
metric m:loan_forgiveness_program_headcount p:integer l:"Loan Forgiveness Program Headcount" d:"Number of recipients approved for the Loan Forgiveness program." t:dataTypeName=number

metric m:loan_forgiveness_program_dollars p:double l:"Loan Forgiveness Program Dollars" d:"Total program dollars on behalf of Loan Forgiveness recipients." t:dataTypeName=money

entity e:ke7n-em5p l:"Loan Forgiveness Awards Administered by Higher Education Services Corp:  Beginning 2011" t:attribution="New York State Higher Education Services Corporation" t:url=https://data.ny.gov/api/views/ke7n-em5p

property e:ke7n-em5p t:meta.view v:id=ke7n-em5p v:category=Education v:attributionLink=http://www.hesc.ny.gov/content.nsf/SFC/Loan_Forgiveness_and_Cancellation v:averageRating=0 v:name="Loan Forgiveness Awards Administered by Higher Education Services Corp:  Beginning 2011" v:attribution="New York State Higher Education Services Corporation"

property e:ke7n-em5p t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:ke7n-em5p t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:ke7n-em5p t:meta.view.metadata.custom_fields.common_core v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| award_year | loan_forgiveness_program_name                  | region_name      | loan_forgiveness_program_headcount | loan_forgiveness_program_dollars | 
| ========== | ============================================== | ================ | ================================== | ================================ | 
| 2012       | John R. Justice Student Loan Repayment Program | Capital District | 8                                  | 7922.45                          | 
| 2012       | John R. Justice Student Loan Repayment Program | Central New York | 3                                  | 2915.28                          | 
| 2012       | John R. Justice Student Loan Repayment Program | Finger Lakes     | 8                                  | 7922.44                          | 
| 2012       | John R. Justice Student Loan Repayment Program | Hudson Valley    | 8                                  | 7811.17                          | 
| 2012       | John R. Justice Student Loan Repayment Program | Long Island      | 10                                 | 10014.32                         | 
| 2012       | John R. Justice Student Loan Repayment Program | New York City    | 30                                 | 29486.61                         | 
| 2012       | John R. Justice Student Loan Repayment Program | North Country    | 7                                  | 6987.77                          | 
| 2012       | John R. Justice Student Loan Repayment Program | Southern Tier    | 3                                  | 3026.55                          | 
| 2012       | John R. Justice Student Loan Repayment Program | Western New York | 7                                  | 6987.77                          | 
| 2012       | John R. Justice Student Loan Repayment Program | x - unassigned   | 5                                  | 4784.64                          | 
```