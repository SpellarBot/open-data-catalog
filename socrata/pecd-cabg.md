# List Of Licensed Employment Agencies

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/list-of-licensed-employment-agencies) |
| Metadata | [Link](https://data.illinois.gov/api/views/pecd-cabg) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/pecd-cabg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/pecd-cabg/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | pecd-cabg |
| Name | List Of Licensed Employment Agencies |
| Attribution | Illinois Department of Labor |
| Category | Labor |
| Tags | employment agency |
| Created | 2016-03-18T19:48:14Z |
| Publication Date | 2016-03-18T19:52:22Z |

## Description

List of Licensed Employment Agencies in the State

## Columns

```ls
| Included | Schema Type | Field Name                                     | Name                                            | Data Type | Render Type |
| ======== | =========== | ============================================== | =============================================== | ========= | =========== |
| No       | time        | :updated_at                                    | updated_at                                      | meta_data | meta_data   |
| Yes      | series tag  | licensed_employment_agency_as_of_march_18_2016 | Licensed Employment Agency As of March 18, 2016 | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:pecd-cabg d:2016-03-18T12:48:17.000Z t:licensed_employment_agency_as_of_march_18_2016="1 Stop Homemaker Services, LLC" m:row_number.pecd-cabg=1

series e:pecd-cabg d:2016-03-18T12:48:17.000Z t:licensed_employment_agency_as_of_march_18_2016="10 Management Incorporated, Inc. d/b/a 10 MGMT" m:row_number.pecd-cabg=2

series e:pecd-cabg d:2016-03-18T12:48:17.000Z t:licensed_employment_agency_as_of_march_18_2016="1st Choice Senior Homecare, Inc." m:row_number.pecd-cabg=3
```

## Meta Commands

```ls
metric m:row_number.pecd-cabg p:long l:"Row Number"

entity e:pecd-cabg l:"List Of Licensed Employment Agencies" t:attribution="Illinois Department of Labor" t:url=https://data.illinois.gov/api/views/pecd-cabg

property e:pecd-cabg t:meta.view v:id=pecd-cabg v:category=Labor v:attributionLink=http://www.illinois.gov/idol/Employers/Pages/ApprovedDTLSA.aspx v:averageRating=0 v:name="List Of Licensed Employment Agencies" v:attribution="Illinois Department of Labor"

property e:pecd-cabg t:meta.view.license v:name="Public Domain"

property e:pecd-cabg t:meta.view.owner v:id=qz2n-kjc9 v:screenName="IL Department of Labor" v:displayName="IL Department of Labor"

property e:pecd-cabg t:meta.view.tableauthor v:id=qz2n-kjc9 v:screenName="IL Department of Labor" v:roleName=publisher v:displayName="IL Department of Labor"
```

## Top Records

```ls
| :updated_at | licensed_employment_agency_as_of_march_18_2016 | 
| =========== | ============================================== | 
| 1458305297  | 1 Stop Homemaker Services, LLC                 | 
| 1458305297  | 10 Management Incorporated, Inc. d/b/a 10 MGMT | 
| 1458305297  | 1st Choice Senior Homecare, Inc.               | 
| 1458305297  | A 1 Best Services, Inc.                        | 
| 1458305297  | A Care Home Placement, Inc.                    | 
| 1458305297  | A Gold Coast Domestic Agency, Inc.             | 
| 1458305297  | A+ Cleaning Service                            | 
| 1458305297  | Able Employment Agency                         | 
| 1458305297  | Absolute Model & Talent Management             | 
| 1458305297  | Accessmaids, Inc.                              | 
```