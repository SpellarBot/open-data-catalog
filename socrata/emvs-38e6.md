# Performance Metrics - Business Affairs & Consumer Protection - Business Licenses

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/performance-metrics-business-affairs-consumer-protection-business-licenses-f810d) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/emvs-38e6) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/emvs-38e6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/emvs-38e6/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | emvs-38e6 |
| Name | Performance Metrics - Business Affairs & Consumer Protection - Business Licenses |
| Attribution | City of Chicago |
| Category | Administration & Finance |
| Tags | performance metrics, service delivery, business, licenses |
| Created | 2011-08-24T15:20:41Z |
| Publication Date | 2017-01-09T12:01:39Z |

## Description

Business licenses and building permits are required to operate a business in Chicago or to ensure that a building construction project conforms to the minimum standards of the Chicago Building Code. Currently the performance target for processing most business license types is approximately 15 days.

## Columns

```ls
| Included | Schema Type    | Field Name                    | Name                          | Data Type | Render Type |
| ======== | ============== | ============================= | ============================= | ========= | =========== |
| Yes      | series tag     | licence_code                  | LICENCE CODE                  | text      | number      |
| Yes      | series tag     | license_description           | LICENSE DESCRIPTION           | text      | text        |
| Yes      | time           | year                          | YEAR                          | number    | number      |
| No       |                | week                          | WEEK                          | text      | text        |
| Yes      | numeric metric | average_days_to_issue_license | AVERAGE DAYS TO ISSUE LICENSE | number    | number      |
| Yes      | numeric metric | median_days_to_issue_license  | MEDIAN DAYS TO ISSUE LICENSE  | number    | number      |
| Yes      | numeric metric | total_licenses_issued         | TOTAL LICENSES ISSUED         | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = week
```

## Data Commands

```ls
series e:emvs-38e6 d:2017-01-01T00:00:00.000Z t:licence_code=1010 t:license_description="Limited Business License" m:median_days_to_issue_license=1 m:average_days_to_issue_license=1.08 m:total_licenses_issued=75

series e:emvs-38e6 d:2017-01-01T00:00:00.000Z t:licence_code=1006 t:license_description="Retail Food Establishment" m:median_days_to_issue_license=34 m:average_days_to_issue_license=68.31 m:total_licenses_issued=13

series e:emvs-38e6 d:2016-01-01T00:00:00.000Z t:licence_code=1010 t:license_description="Limited Business License" m:median_days_to_issue_license=1 m:average_days_to_issue_license=1.12 m:total_licenses_issued=49
```

## Meta Commands

```ls
metric m:average_days_to_issue_license p:float l:"AVERAGE DAYS TO ISSUE LICENSE" t:dataTypeName=number

metric m:median_days_to_issue_license p:integer l:"MEDIAN DAYS TO ISSUE LICENSE" t:dataTypeName=number

metric m:total_licenses_issued p:integer l:"TOTAL LICENSES ISSUED" t:dataTypeName=number

entity e:emvs-38e6 l:"Performance Metrics - Business Affairs & Consumer Protection - Business Licenses" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/emvs-38e6

property e:emvs-38e6 t:meta.view v:id=emvs-38e6 v:category="Administration & Finance" v:attributionLink=http://www.cityofchicago.org/performance v:averageRating=0 v:name="Performance Metrics - Business Affairs & Consumer Protection - Business Licenses" v:attribution="City of Chicago"

property e:emvs-38e6 t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:emvs-38e6 t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```

## Top Records

```ls
| licence_code | license_description       | year | week                    | average_days_to_issue_license | median_days_to_issue_license | total_licenses_issued | 
| ============ | ========================= | ==== | ======================= | ============================= | ============================ | ===================== | 
| 1010         | Limited Business License  | 2017 | 01/02/2017 - 01/08/2017 | 1.08                          | 1                            | 75                    | 
| 1006         | Retail Food Establishment | 2017 | 01/02/2017 - 01/08/2017 | 68.31                         | 34                           | 13                    | 
| 1010         | Limited Business License  | 2016 | 12/26/2016 - 01/01/2017 | 1.12                          | 1                            | 49                    | 
| 1524         | Massage Establishment     | 2016 | 12/26/2016 - 01/01/2017 | 20.0                          | 20                           | 1                     | 
| 1006         | Retail Food Establishment | 2016 | 12/26/2016 - 01/01/2017 | 34.24                         | 13                           | 34                    | 
| 1275         | Filling Station           | 2016 | 12/19/2016 - 12/25/2016 | 87.5                          | 87                           | 2                     | 
| 1010         | Limited Business License  | 2016 | 12/19/2016 - 12/25/2016 | 10.36                         | 1                            | 64                    | 
| 1006         | Retail Food Establishment | 2016 | 12/19/2016 - 12/25/2016 | 38.66                         | 29                           | 32                    | 
| 1275         | Filling Station           | 2016 | 12/12/2016 - 12/18/2016 | 204.0                         | 204                          | 1                     | 
| 1010         | Limited Business License  | 2016 | 12/12/2016 - 12/18/2016 | 1.14                          | 1                            | 43                    | 
```