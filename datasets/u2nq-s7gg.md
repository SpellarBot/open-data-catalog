# Performance Metrics - Ethics - Mandatory Annual Ethics Training

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/performance-metrics-ethics-mandatory-annual-ethics-training-edc6a) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/u2nq-s7gg) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/u2nq-s7gg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/u2nq-s7gg/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | u2nq-s7gg |
| Name | Performance Metrics - Ethics - Mandatory Annual Ethics Training |
| Attribution | City of Chicago |
| Category | Administration & Finance |
| Tags | performance metrics, ethics, personnel |
| Created | 2011-09-21T22:23:04Z |
| Publication Date | 2012-04-04T16:23:59Z |

## Description

Number Of City Employees And Officials Completing Mandatory Annual Ethics Training

## Columns

```ls
| Included | Schema Type    | Field Name                                                                | Name                                                                         | Data Type | Render Type |
| ======== | ============== | ========================================================================= | ============================================================================ | ========= | =========== |
| Yes      | time           | week                                                                      | Week                                                                         | text      | text        |
| Yes      | numeric metric | number_completing_mandatory_annual_ethics_training                        | Number Completing Mandatory Annual Ethics Training                           | number    | number      |
| Yes      | numeric metric | total_trained                                                             | Total Trained                                                                | number    | number      |
| Yes      | numeric metric | percent_completing_mandatory_annual_ethics_training_target_100_by_dec_31_ | Percent Completing Mandatory Annual Ethics Training (Target: 100% by Dec 31) | percent   | percent     |
| Yes      | series tag     | target                                                                    | Target                                                                       | text      | text        |
```

## Time Field

```ls
Value = week
Format & Zone = ww,yyyy
```

## Data Commands

```ls
series e:u2nq-s7gg d:2011-05-26T00:00:00.000Z t:target="100% by Dec 31" m:percent_completing_mandatory_annual_ethics_training_target_100_by_dec_31_=13 m:number_completing_mandatory_annual_ethics_training=0 m:total_trained=4235

series e:u2nq-s7gg d:2011-06-02T00:00:00.000Z t:target="100% by Dec 31" m:percent_completing_mandatory_annual_ethics_training_target_100_by_dec_31_=13 m:number_completing_mandatory_annual_ethics_training=0 m:total_trained=4235

series e:u2nq-s7gg d:2011-06-09T00:00:00.000Z t:target="100% by Dec 31" m:percent_completing_mandatory_annual_ethics_training_target_100_by_dec_31_=13 m:number_completing_mandatory_annual_ethics_training=0 m:total_trained=4235
```

## Meta Commands

```ls
metric m:number_completing_mandatory_annual_ethics_training p:integer l:"Number Completing Mandatory Annual Ethics Training" t:dataTypeName=number

metric m:total_trained p:integer l:"Total Trained" t:dataTypeName=number

metric m:percent_completing_mandatory_annual_ethics_training_target_100_by_dec_31_ p:double l:"Percent Completing Mandatory Annual Ethics Training (Target: 100% by Dec 31)" t:dataTypeName=percent

entity e:u2nq-s7gg l:"Performance Metrics - Ethics - Mandatory Annual Ethics Training" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/u2nq-s7gg

property e:u2nq-s7gg t:meta.view v:id=u2nq-s7gg v:category="Administration & Finance" v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="Performance Metrics - Ethics - Mandatory Annual Ethics Training" v:attribution="City of Chicago"

property e:u2nq-s7gg t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:u2nq-s7gg t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```

## Top Records

```ls
| week                | number_completing_mandatory_annual_ethics_training | total_trained | percent_completing_mandatory_annual_ethics_training_target_100_by_dec_31_ | target         | 
| =================== | ================================================== | ============= | ========================================================================= | ============== | 
| May 26-Jun 1, 2011  | 0                                                  | 4235          | 13                                                                        | 100% by Dec 31 | 
| Jun 2-8, 2011       | 0                                                  | 4235          | 13                                                                        | 100% by Dec 31 | 
| Jun 9-15, 2011      | 0                                                  | 4235          | 13                                                                        | 100% by Dec 31 | 
| Jun 16-22, 2011     | 0                                                  | 4235          | 13                                                                        | 100% by Dec 31 | 
| Jun 23-29, 2011     | 377                                                | 4612          | 14                                                                        | 100% by Dec 31 | 
| Jun 30-Jul 6, 2011  | 515                                                | 5127          | 15.5                                                                      | 100% by Dec 31 | 
| Jul 7-Jul 13, 2011  | 227                                                | 5354          | 15.8                                                                      | 100% by Dec 31 | 
| Jul 14-Jul 20, 2011 | 546                                                | 5900          | 17.1                                                                      | 100% by Dec 31 | 
| Jul 21-Jul 28, 2011 | 259                                                | 6159          | 18.5                                                                      | 100% by Dec 31 | 
| Jul 29-Aug 3, 2011  | 320                                                | 6479          | 19                                                                        | 100% by Dec 31 | 
```