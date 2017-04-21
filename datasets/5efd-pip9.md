# FY2015 Annual Report Expense X Program Table

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/fy2015-annual-report-expense-x-program-table) |
| Metadata | [Link](https://data.austintexas.gov/api/views/5efd-pip9) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/5efd-pip9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/5efd-pip9/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | 5efd-pip9 |
| Name | FY2015 Annual Report Expense X Program Table |
| Tags | atcems, fy2015, annual report, expenses |
| Created | 2016-08-29T16:00:39Z |
| Publication Date | 2016-08-29T16:03:08Z |

## Description

** Static Data Set ** This table shows ATCEMS expenses by program for the past five fiscal years. It has been uploaded to support the ATCEMS FY2015 annual report. THE DATA IN THIS TABLE WILL NOT BE UPDATED.

## Columns

```ls
| Included | Schema Type    | Field Name | Name    | Data Type | Render Type |
| ======== | ============== | ========== | ======= | ========= | =========== |
| Yes      | series tag     | program    | Program | text      | text        |
| Yes      | numeric metric | fy2011     | FY2011  | money     | money       |
| Yes      | numeric metric | fy2012     | FY2012  | money     | money       |
| Yes      | numeric metric | fy2013     | FY2013  | money     | money       |
| Yes      | numeric metric | fy2014     | FY2014  | money     | money       |
| Yes      | numeric metric | fy2015     | FY2015  | money     | money       |
```

## Time Field

```ls
Value = 2015
Format & Zone = yyyy
```

## Data Commands

```ls
series e:5efd-pip9 d:2015-01-01T00:00:00.000Z t:program="Emergency Communications" m:fy2014=4635580 m:fy2015=4905367 m:fy2011=4113549 m:fy2012=4081431 m:fy2013=4217111

series e:5efd-pip9 d:2015-01-01T00:00:00.000Z t:program=Operations m:fy2014=44351286 m:fy2015=46740472 m:fy2011=33856512 m:fy2012=36521573 m:fy2013=39016345

series e:5efd-pip9 d:2015-01-01T00:00:00.000Z t:program="Employee Dev & Wellness" m:fy2014=1548157 m:fy2015=1949544 m:fy2011=2481782 m:fy2012=2081308 m:fy2013=2007812
```

## Meta Commands

```ls
metric m:fy2011 p:integer l:FY2011 t:dataTypeName=money

metric m:fy2012 p:integer l:FY2012 t:dataTypeName=money

metric m:fy2013 p:integer l:FY2013 t:dataTypeName=money

metric m:fy2014 p:integer l:FY2014 t:dataTypeName=money

metric m:fy2015 p:integer l:FY2015 t:dataTypeName=money

entity e:5efd-pip9 l:"FY2015 Annual Report Expense X Program Table" t:url=https://data.austintexas.gov/api/views/5efd-pip9

property e:5efd-pip9 t:meta.view v:id=5efd-pip9 v:averageRating=0 v:name="FY2015 Annual Report Expense X Program Table"

property e:5efd-pip9 t:meta.view.owner v:id=4zcf-8die v:profileImageUrlMedium=/api/users/4zcf-8die/profile_images/THUMB v:profileImageUrlLarge=/api/users/4zcf-8die/profile_images/LARGE v:screenName="Austin-Travis County EMS" v:profileImageUrlSmall=/api/users/4zcf-8die/profile_images/TINY v:displayName="Austin-Travis County EMS"

property e:5efd-pip9 t:meta.view.tableauthor v:id=4zcf-8die v:profileImageUrlMedium=/api/users/4zcf-8die/profile_images/THUMB v:profileImageUrlLarge=/api/users/4zcf-8die/profile_images/LARGE v:screenName="Austin-Travis County EMS" v:profileImageUrlSmall=/api/users/4zcf-8die/profile_images/TINY v:roleName=publisher_stories v:displayName="Austin-Travis County EMS"
```

## Top Records

```ls
| program                                 | fy2011   | fy2012   | fy2013   | fy2014   | fy2015   | 
| ======================================= | ======== | ======== | ======== | ======== | ======== | 
| Emergency Communications                | 4113549  | 4081431  | 4217111  | 4635580  | 4905367  | 
| Operations                              | 33856512 | 36521573 | 39016345 | 44351286 | 46740472 | 
| Employee Dev & Wellness                 | 2481782  | 2081308  | 2007812  | 1548157  | 1949544  | 
| Community Relations & Injury Prevention | 276131   | 508988   | 1239575  | 207639   | 527538   | 
| Safety & Performance Improvement        | 1651654  | 1473156  | 1660853  | 1986079  | 1558983  | 
| Billing Services                        | 1390099  | 1370882  | 1665446  | 1513181  | 1453877  | 
| OMD                                     | 1013165  | 1171283  | 1267720  | 1296002  | 1457433  | 
| Support Services                        | 2142915  | 2440652  | 2582483  | 4033093  | 4169106  | 
| Transfers and Other Requirements        | 127989   | 51445    | 49787    | 92966    | 8418842  | 
| Total                                   | 47053796 | 49700718 | 53707132 | 59663983 | 71181162 | 
```