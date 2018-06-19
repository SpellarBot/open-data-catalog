# Performance Metrics - Ethics - Statements Of Financial Interests Filed

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/performance-metrics-ethics-statements-of-financial-interests-filed-6749d) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/xx5x-8bka) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/xx5x-8bka/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/xx5x-8bka/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | xx5x-8bka |
| Name | Performance Metrics - Ethics - Statements Of Financial Interests Filed |
| Attribution | City of Chicago |
| Category | Administration & Finance |
| Tags | performance metrics, ethics, personnel |
| Created | 2011-09-21T21:30:38Z |
| Publication Date | 2012-04-16T19:57:29Z |

## Description

Number Of Annual Statements Of Financial Interests Filed, Reviewed And Posted Online

## Columns

```ls
| Included | Schema Type    | Field Name                         | Name                               | Data Type | Render Type |
| ======== | ============== | ================================== | ================================== | ========= | =========== |
| Yes      | time           | week                               | Week                               | text      | text        |
| Yes      | numeric metric | number_of_employees_who_have_filed | Number of Employees who have Filed | number    | number      |
| Yes      | numeric metric | compliance_percentage              | Compliance Percentage              | percent   | percent     |
| Yes      | series tag     | target                             | Target                             | text      | text        |
```

## Time Field

```ls
Value = week
Format & Zone = ww,yyyy
```

## Data Commands

```ls
series e:xx5x-8bka d:2011-05-26T00:00:00.000Z t:target="100% by Dec 31" m:compliance_percentage=98 m:number_of_employees_who_have_filed=14235

series e:xx5x-8bka d:2011-06-02T00:00:00.000Z t:target="100% by Dec 31" m:compliance_percentage=99.02 m:number_of_employees_who_have_filed=14417

series e:xx5x-8bka d:2011-06-09T00:00:00.000Z t:target="100% by Dec 31" m:compliance_percentage=99.04 m:number_of_employees_who_have_filed=14437
```

## Meta Commands

```ls
metric m:number_of_employees_who_have_filed p:integer l:"Number of Employees who have Filed" t:dataTypeName=number

metric m:compliance_percentage p:float l:"Compliance Percentage" t:dataTypeName=percent

entity e:xx5x-8bka l:"Performance Metrics - Ethics - Statements Of Financial Interests Filed" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/xx5x-8bka

property e:xx5x-8bka t:meta.view v:id=xx5x-8bka v:category="Administration & Finance" v:attributionLink=http://www.cityofchicago.org/performance v:averageRating=0 v:name="Performance Metrics - Ethics - Statements Of Financial Interests Filed" v:attribution="City of Chicago"

property e:xx5x-8bka t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:xx5x-8bka t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```

## Top Records

```ls
| week                | number_of_employees_who_have_filed | compliance_percentage | target         | 
| =================== | ================================== | ===================== | ============== | 
| May 26-Jun 1, 2011  | 14235                              | 98                    | 100% by Dec 31 | 
| Jun 2-8, 2011       | 14417                              | 99.02                 | 100% by Dec 31 | 
| Jun 9-15, 2011      | 14437                              | 99.04                 | 100% by Dec 31 | 
| Jun 16-22, 2011     | 14441                              | 99.05                 | 100% by Dec 31 | 
| Jun 23-29, 2011     | 14468                              | 99.08                 | 100% by Dec 31 | 
| Jun 30-Jul 6, 2011  | 14479                              | 99.08                 | 100% by Dec 31 | 
| Jul 7-Jul 13, 2011  | 14488                              | 99.08                 | 100% by Dec 31 | 
| Jul 14-Jul 20, 2011 | 14501                              | 99.2                  | 100% by Dec 31 | 
| Jul 21-Jul 28, 2011 | 14509                              | 99.3                  | 100% by Dec 31 | 
| Jul 29-Aug 3, 2011  | 14512                              | 99.3                  | 100% by Dec 31 | 
```