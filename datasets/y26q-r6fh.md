# Department of Human Resources(DHR): Child Support Enforcement Administration Performance Measures

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/department-of-human-resourcesdhr-child-support-enforcement-administration-performance-meas) |
| Metadata | [Link](https://data.maryland.gov/api/views/y26q-r6fh) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/y26q-r6fh/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/y26q-r6fh/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | y26q-r6fh |
| Name | Department of Human Resources(DHR): Child Support Enforcement Administration Performance Measures |
| Attribution | Department of Human Resources |
| Category | Health and Human Services |
| Tags | child support, child, paternity, support order, support collection, support arrears |
| Created | 2016-07-08T15:38:58Z |
| Publication Date | 2017-03-22T13:53:55Z |

## Description

CHILD SUPPORT ENFORCEMENT ADMINISTRATION

The performance measures are used to evaluate each State's performance and measure results in the Child Support Enforcement program. These measures emphasize paternity establishment, support order establishment, collection of current support, collection of arrearages, and cost effectiveness. The performance measures, except cost effectiveness which can only be measured annually, are calculated from data which is reported on federal form OCSE 157.  

CASES WITH SUPPORT ORDERS
This metric measures the proportion of IV-D cases with support orders established.

Equation:
Number of IV-D Cases with Support Orders divided by Total Number of IV-D Cases

IV-D Paternity Establishment Percentage:
This metric measures the proportion of children in the IV-D caseload as of the end of the preceding FFY who were born out of wedlock is the total number of children in the IV-D caseload in the federal fiscal year born out of wedlock with paternity established or acknowledged divided by the total number of children in the IV-D caseload as of the end of the preceding FFY who were born out of wedlock.  .

Equation:
Total # of Children in IV-D Caseload in the Federal Fiscal Year or, as of the end of the Fiscal Year who were born out of wedlock with Paternity Established or Acknowledged divided by Total # of Children in IV-D Caseload as of the end of the preceding Federal Fiscal Year who were Born Out of Wedlock

COLLECTIONS ON CURRENT SUPPORT
This measure focuses on the proportion of current support due that is collected on IV-D cases. 

Equation:
Total Dollars Collected for Current Support in IV-D Cases during the Federal Fiscal Year divided by Total Dollars Owed for Current Support in IV-D Cases during the Federal Fiscal Year

COLLECTIONS ON ARREARS
The measure assesses efforts to collect money from those cases with an arrearage due. 
The measure specifically counts paying cases, and not total arrears dollars collected.

Equation:
Total number of IV-D cases paying toward arrears during the Federal Fiscal Year divided by Total number of IV-D cases with arrears due

## Columns

```ls
| Included | Schema Type    | Field Name                                                                    | Name                                                                              | Data Type     | Render Type   |
| ======== | ============== | ============================================================================= | ================================================================================= | ============= | ============= |
| Yes      | time           | date                                                                          | Date                                                                              | calendar_date | calendar_date |
| No       |                | month                                                                         | Month                                                                             | text          | text          |
| No       |                | fiscal_year                                                                   | Calendar Year                                                                     | number        | number        |
| Yes      | numeric metric | percentages_of_cases_in_the_state_child_support_caseload_with_support_orders  | Percentages of cases in the State child support caseload with support orders (%)  | percent       | percent       |
| Yes      | numeric metric | percentages_of_current_support_paid                                           | Percentages of Current Support Paid (%)                                           | percent       | percent       |
| Yes      | numeric metric | percentages_of_child_support_cases_in_arrears_for_which_a_payment_is_received | Percentages of child support cases in arrears for which a payment is received (%) | percent       | percent       |
| Yes      | series tag     | month_year                                                                    | Month year                                                                        | text          | text          |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = fiscal_year,month
```

## Data Commands

```ls
series e:y26q-r6fh d:2012-05-31T00:00:00.000Z t:month_year="May 2012" m:percentages_of_cases_in_the_state_child_support_caseload_with_support_orders=83.29 m:percentages_of_current_support_paid=66.02 m:percentages_of_child_support_cases_in_arrears_for_which_a_payment_is_received=58.59

series e:y26q-r6fh d:2013-05-31T00:00:00.000Z t:month_year="May 2013" m:percentages_of_cases_in_the_state_child_support_caseload_with_support_orders=83.22 m:percentages_of_current_support_paid=66.06 m:percentages_of_child_support_cases_in_arrears_for_which_a_payment_is_received=63.24

series e:y26q-r6fh d:2013-07-31T00:00:00.000Z t:month_year="Jul 2013" m:percentages_of_cases_in_the_state_child_support_caseload_with_support_orders=83.47 m:percentages_of_current_support_paid=66.48 m:percentages_of_child_support_cases_in_arrears_for_which_a_payment_is_received=66.15
```

## Meta Commands

```ls
metric m:percentages_of_cases_in_the_state_child_support_caseload_with_support_orders p:float l:"Percentages of cases in the State child support caseload with support orders (%)" t:dataTypeName=percent

metric m:percentages_of_current_support_paid p:float l:"Percentages of Current Support Paid (%)" t:dataTypeName=percent

metric m:percentages_of_child_support_cases_in_arrears_for_which_a_payment_is_received p:float l:"Percentages of child support cases in arrears for which a payment is received (%)" t:dataTypeName=percent

entity e:y26q-r6fh l:"Department of Human Resources(DHR): Child Support Enforcement Administration Performance Measures" t:attribution="Department of Human Resources" t:url=https://data.maryland.gov/api/views/y26q-r6fh

property e:y26q-r6fh t:meta.view v:id=y26q-r6fh v:category="Health and Human Services" v:attributionLink=http://www.dhr.state.md.us/blog/ v:averageRating=0 v:name="Department of Human Resources(DHR): Child Support Enforcement Administration Performance Measures" v:attribution="Department of Human Resources"

property e:y26q-r6fh t:meta.view.license v:name="Public Domain"

property e:y26q-r6fh t:meta.view.owner v:id=84qh-8fvb v:screenName="Christa Linton" v:displayName="Christa Linton"

property e:y26q-r6fh t:meta.view.tableauthor v:id=84qh-8fvb v:screenName="Christa Linton" v:roleName=editor v:displayName="Christa Linton"
```

## Top Records

```ls
| date                | month | fiscal_year | percentages_of_cases_in_the_state_child_support_caseload_with_support_orders | percentages_of_current_support_paid | percentages_of_child_support_cases_in_arrears_for_which_a_payment_is_received | month_year | 
| =================== | ===== | =========== | ============================================================================ | =================================== | ============================================================================= | ========== | 
| 2012-05-31T00:00:00 | may   | 2012        | 83.29                                                                        | 66.02                               | 58.59                                                                         | May 2012   | 
| 2013-05-31T00:00:00 | may   | 2013        | 83.22                                                                        | 66.06                               | 63.24                                                                         | May 2013   | 
| 2013-07-31T00:00:00 | jul   | 2013        | 83.47                                                                        | 66.48                               | 66.15                                                                         | Jul 2013   | 
| 2013-06-30T00:00:00 | jun   | 2013        | 83.32                                                                        | 66.49                               | 65.25                                                                         | Jun 2013   | 
| 2013-04-30T00:00:00 | apr   | 2013        | 83.23                                                                        | 65.87                               | 61.27                                                                         | Apr 2013   | 
| 2013-03-31T00:00:00 | mar   | 2013        | 83.31                                                                        | 66.02                               | 59.34                                                                         | Mar 2013   | 
| 2013-02-28T00:00:00 | feb   | 2013        | 83.23                                                                        | 65.08                               | 53.65                                                                         | Feb 2013   | 
| 2013-01-31T00:00:00 | jan   | 2013        | 83.22                                                                        | 65.45                               | 51.09                                                                         | Jan 2013   | 
| 2012-12-31T00:00:00 | dec   | 2012        | 83.24                                                                        | 64.84                               | 45.30                                                                         | Dec 2012   | 
| 2012-11-30T00:00:00 | nov   | 2012        | 83.78                                                                        | 64.92                               | 40.59                                                                         | Nov 2012   | 
```