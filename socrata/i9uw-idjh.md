# Performance Metrics - Ethics - Lobbyists Completing Ethics Training

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/performance-metrics-ethics-lobbyists-completing-ethics-training-cd559) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/i9uw-idjh) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/i9uw-idjh/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/i9uw-idjh/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | i9uw-idjh |
| Name | Performance Metrics - Ethics - Lobbyists Completing Ethics Training |
| Attribution | City of Chicago |
| Category | Administration & Finance |
| Tags | performance metrics, ethics, lobbyists |
| Created | 2011-09-21T21:33:59Z |
| Publication Date | 2012-02-17T17:01:35Z |

## Description

Number Of Lobbyists Completing Other Mandatory Or Voluntary Ethics Training

## Columns

```ls
| Included | Schema Type    | Field Name                                         | Name                                                  | Data Type | Render Type |
| ======== | ============== | ================================================== | ===================================================== | ========= | =========== |
| Yes      | time           | week                                               | Week                                                  | text      | text        |
| Yes      | numeric metric | number_of_lobbyists_trained                        | Number of Lobbyists Trained                           | number    | number      |
| Yes      | numeric metric | percent_of_lobbyists_trained_target_100_by_july_1_ | Percent of Lobbyists Trained (Target: 100% by July 1) | percent   | percent     |
| Yes      | series tag     | target                                             | Target                                                | text      | text        |
```

## Time Field

```ls
Value = week
Format & Zone = ww,yyyy
```

## Data Commands

```ls
series e:i9uw-idjh d:2011-05-26T00:00:00.000Z t:target="100% by July 1" m:percent_of_lobbyists_trained_target_100_by_july_1_=59 m:number_of_lobbyists_trained=21

series e:i9uw-idjh d:2011-06-02T00:00:00.000Z t:target="100% by July 1" m:percent_of_lobbyists_trained_target_100_by_july_1_=70 m:number_of_lobbyists_trained=109

series e:i9uw-idjh d:2011-06-09T00:00:00.000Z t:target="100% by July 1" m:percent_of_lobbyists_trained_target_100_by_july_1_=75 m:number_of_lobbyists_trained=25
```

## Meta Commands

```ls
metric m:number_of_lobbyists_trained p:integer l:"Number of Lobbyists Trained" t:dataTypeName=number

metric m:percent_of_lobbyists_trained_target_100_by_july_1_ p:float l:"Percent of Lobbyists Trained (Target: 100% by July 1)" t:dataTypeName=percent

entity e:i9uw-idjh l:"Performance Metrics - Ethics - Lobbyists Completing Ethics Training" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/i9uw-idjh

property e:i9uw-idjh t:meta.view v:id=i9uw-idjh v:category="Administration & Finance" v:attributionLink=http://www.cityofchicago.org/performance v:averageRating=0 v:name="Performance Metrics - Ethics - Lobbyists Completing Ethics Training" v:attribution="City of Chicago"

property e:i9uw-idjh t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:i9uw-idjh t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```

## Top Records

```ls
| week                | number_of_lobbyists_trained | percent_of_lobbyists_trained_target_100_by_july_1_ | target         | 
| =================== | =========================== | ================================================== | ============== | 
| May 26-Jun 1, 2011  | 21                          | 59                                                 | 100% by July 1 | 
| Jun 2-8, 2011       | 109                         | 70                                                 | 100% by July 1 | 
| Jun 9-15, 2011      | 25                          | 75                                                 | 100% by July 1 | 
| Jun 16-22, 2011     | 47                          | 82                                                 | 100% by July 1 | 
| Jun 23-29, 2011     | 40                          | 89                                                 | 100% by July 1 | 
| Jun 30-Jul 6, 2011  | 10                          | 93                                                 | 100% by July 1 | 
| Jul 7-Jul 13, 2011  | 20                          | 96                                                 | 100% by July 1 | 
| Jul 14-Jul 20, 2011 | 19                          | 96.6                                               | 100% by July 1 | 
| Jul 21-Jul 28, 2011 | 8                           | 97.2                                               | 100% by July 1 | 
| Jul 29-Aug 3, 2011  | 14                          | 98.2                                               | 100% by July 1 | 
```