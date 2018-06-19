# FY2015 Annual Report Recruiting Field Applicant Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/fy2015-annual-report-recruiting-field-applicant-data) |
| Metadata | [Link](https://data.austintexas.gov/api/views/wzpn-8njw) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/wzpn-8njw/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/wzpn-8njw/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | wzpn-8njw |
| Name | FY2015 Annual Report Recruiting Field Applicant Data |
| Tags | atcems, fy2015, annual report, human resources, recruiting |
| Created | 2016-09-26T16:39:30Z |
| Publication Date | 2016-09-26T16:45:16Z |

## Description

** Static Data Set ** This table shows Recruiting data related to field applicants for the past four fiscal years.  Data regarding applicants for Communications or non-uniformed positions are not included in this table. It has been uploaded to support the ATCEMS FY2015 annual report. THE DATA IN THIS TABLE WILL NOT BE UPDATED.

## Columns

```ls
| Included | Schema Type    | Field Name            | Name                           | Data Type | Render Type |
| ======== | ============== | ===================== | ============================== | ========= | =========== |
| Yes      | series tag     | fiscal_year           | Fiscal Year                    | text      | text        |
| Yes      | numeric metric | total_applications    | Total Applications Received    | number    | number      |
| Yes      | numeric metric | total_tested          | Total Applicants Tested        | number    | number      |
| Yes      | numeric metric | minority_applications | Minority Applications Received | number    | number      |
| Yes      | numeric metric | minority_tested       | Minority Applicants Tested     | number    | number      |
| Yes      | numeric metric | female_applications   | Female Applications Received   | number    | number      |
| Yes      | numeric metric | female_tested         | Female Applicants Tested       | number    | number      |
```

## Time Field

```ls
Value = 2015
Format & Zone = yyyy
```

## Data Commands

```ls
series e:wzpn-8njw d:2015-01-01T00:00:00.000Z t:fiscal_year=FY2012 m:total_applications=528 m:total_tested=191 m:minority_tested=48 m:minority_applications=168 m:female_applications=138 m:female_tested=48

series e:wzpn-8njw d:2015-01-01T00:00:00.000Z t:fiscal_year=FY2013 m:total_applications=406 m:total_tested=200 m:minority_tested=52 m:minority_applications=235 m:female_applications=154 m:female_tested=60

series e:wzpn-8njw d:2015-01-01T00:00:00.000Z t:fiscal_year=FY2014 m:total_applications=521 m:total_tested=243 m:minority_tested=68 m:minority_applications=150 m:female_applications=99 m:female_tested=53
```

## Meta Commands

```ls
metric m:total_applications p:integer l:"Total Applications Received" t:dataTypeName=number

metric m:total_tested p:integer l:"Total Applicants Tested" t:dataTypeName=number

metric m:minority_applications p:integer l:"Minority Applications Received" t:dataTypeName=number

metric m:minority_tested p:integer l:"Minority Applicants Tested" t:dataTypeName=number

metric m:female_applications p:integer l:"Female Applications Received" t:dataTypeName=number

metric m:female_tested p:integer l:"Female Applicants Tested" t:dataTypeName=number

entity e:wzpn-8njw l:"FY2015 Annual Report Recruiting Field Applicant Data" t:url=https://data.austintexas.gov/api/views/wzpn-8njw

property e:wzpn-8njw t:meta.view v:id=wzpn-8njw v:averageRating=0 v:name="FY2015 Annual Report Recruiting Field Applicant Data"

property e:wzpn-8njw t:meta.view.owner v:id=4zcf-8die v:profileImageUrlMedium=/api/users/4zcf-8die/profile_images/THUMB v:profileImageUrlLarge=/api/users/4zcf-8die/profile_images/LARGE v:screenName="Austin-Travis County EMS" v:profileImageUrlSmall=/api/users/4zcf-8die/profile_images/TINY v:displayName="Austin-Travis County EMS"

property e:wzpn-8njw t:meta.view.tableauthor v:id=4zcf-8die v:profileImageUrlMedium=/api/users/4zcf-8die/profile_images/THUMB v:profileImageUrlLarge=/api/users/4zcf-8die/profile_images/LARGE v:screenName="Austin-Travis County EMS" v:profileImageUrlSmall=/api/users/4zcf-8die/profile_images/TINY v:roleName=publisher_stories v:displayName="Austin-Travis County EMS"
```

## Top Records

```ls
| fiscal_year | total_applications | total_tested | minority_applications | minority_tested | female_applications | female_tested | 
| =========== | ================== | ============ | ===================== | =============== | =================== | ============= | 
| FY2012      | 528                | 191          | 168                   | 48              | 138                 | 48            | 
| FY2013      | 406                | 200          | 235                   | 52              | 154                 | 60            | 
| FY2014      | 521                | 243          | 150                   | 68              | 99                  | 53            | 
| FY2015      | 587                | 259          | 208                   | 90              | 103                 | 47            | 
```