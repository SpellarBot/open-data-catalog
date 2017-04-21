# Human Resources - Compliance Officer?s Quarterly Employment Action Reports

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/human-resources-compliance-officers-quarterly-employment-action-reports) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/haj6-m47h) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/haj6-m47h/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/haj6-m47h/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | haj6-m47h |
| Name | Human Resources - Compliance Officer?s Quarterly Employment Action Reports |
| Attribution | Cook County Bureau of Human Resources |
| Category | Finance & Administration |
| Created | 2016-06-22T23:16:43Z |
| Publication Date | 2016-11-07T20:27:14Z |

## Description

In order to ensure Cook County?s commitment to transparency, reports on employment actions and monitoring activities are available.

As required under the Employment Plan, Cook County Board President Toni Preckwinkle hired a Compliance Officer whose primary responsibilities include the following:

1. Overseeing compliance with the Employment Plan

2. Maintaining and reviewing the Exempt List

3. Accepting, investigating, and reporting on complaints related to Employment Actions and the Employment Plan

4. Taking steps to evaluate, eliminate, remedy and reporting instances of Political Contacts and Unlawful Political Discrimination; and

5. Training on Employment Plan and reviewing Policies and Procedures.

If you would like to make a complaint alleging non-compliance with the Employment Plan, a Complaint Form is available or you can contact the Compliance Officer directly.

Letitia Dominici, Compliance Officer 118 N. Clark Street, 8th Floor Chicago, IL 60602 Letitia.dominici@cookcountyil.gov

## Columns

```ls
| Included | Schema Type | Field Name  | Name        | Data Type | Render Type |
| ======== | =========== | =========== | =========== | ========= | =========== |
| Yes      | series tag  | link        | Link        | url       | url         |
| No       |             | fiscal_year | Fiscal Year | number    | number      |
| No       |             | quarter     | Quarter     | number    | number      |
```

## Time Field

```ls
Value = fiscal_year-quarter
Format & Zone = yyyy-q
```

## Series Fields

```ls
Excluded Fields = fiscal_year,quarter
```

## Data Commands

```ls
series e:haj6-m47h d:2015-10-01T00:00:00.000Z t:link=http://opendocs.cookcountyil.gov/human-resources/compliance/quarterly/q4_2015.pdf m:row_number.haj6-m47h=1

series e:haj6-m47h d:2015-07-01T00:00:00.000Z t:link=http://opendocs.cookcountyil.gov/human-resources/compliance/quarterly/q3_2015.pdf m:row_number.haj6-m47h=2

series e:haj6-m47h d:2015-04-01T00:00:00.000Z t:link=http://opendocs.cookcountyil.gov/human-resources/compliance/quarterly/q2_2015.pdf m:row_number.haj6-m47h=3
```

## Meta Commands

```ls
metric m:row_number.haj6-m47h p:long l:"Row Number"

entity e:haj6-m47h l:"Human Resources - Compliance Officer?s Quarterly Employment Action Reports" t:attribution="Cook County Bureau of Human Resources" t:url=https://datacatalog.cookcountyil.gov/api/views/haj6-m47h

property e:haj6-m47h t:meta.view v:id=haj6-m47h v:category="Finance & Administration" v:averageRating=0 v:name="Human Resources - Compliance Officer?s Quarterly Employment Action Reports" v:attribution="Cook County Bureau of Human Resources"

property e:haj6-m47h t:meta.view.license v:name="Public Domain"

property e:haj6-m47h t:meta.view.owner v:id=u38g-hbsa v:screenName="Cook County Open Data" v:lastNotificationSeenAt=1492536815 v:displayName="Cook County Open Data"

property e:haj6-m47h t:meta.view.tableauthor v:id=u38g-hbsa v:screenName="Cook County Open Data" v:roleName=administrator v:lastNotificationSeenAt=1492536815 v:displayName="Cook County Open Data"
```

## Top Records

```ls
| link                                                                                                       | fiscal_year | quarter | 
| ========================================================================================================== | =========== | ======= | 
| [http://opendocs.cookcountyil.gov/human-resources/compliance/quarterly/q4_2015.pdf, 2015 Quarter 4 Report] | 2015        | 4       | 
| [http://opendocs.cookcountyil.gov/human-resources/compliance/quarterly/q3_2015.pdf, 2015 Quarter 3 Report] | 2015        | 3       | 
| [http://opendocs.cookcountyil.gov/human-resources/compliance/quarterly/q2_2015.pdf, 2015 Quarter 2 Report] | 2015        | 2       | 
| [http://opendocs.cookcountyil.gov/human-resources/compliance/quarterly/q1_2015.pdf, 2015 Quarter 1 Report] | 2015        | 1       | 
| [http://opendocs.cookcountyil.gov/human-resources/compliance/quarterly/q4_2014.pdf, 2014 Quarter 4 Report] | 2014        | 4       | 
| [http://opendocs.cookcountyil.gov/human-resources/compliance/quarterly/q3_2014.pdf, 2014 Quarter 3 Report] | 2014        | 3       | 
| [http://opendocs.cookcountyil.gov/human-resources/compliance/quarterly/q2_2014.pdf, 2014 Quarter 2 Report] | 2014        | 2       | 
| [http://opendocs.cookcountyil.gov/human-resources/compliance/quarterly/q1_2014.pdf, 2014 Quarter 1 Report] | 2014        | 1       | 
| [http://opendocs.cookcountyil.gov/human-resources/compliance/quarterly/q4_2013.pdf, 2013 Quarter 4 Report] | 2013        | 4       | 
| [http://opendocs.cookcountyil.gov/human-resources/compliance/quarterly/q3_2013.pdf, 2013 Quarter 3 Report] | 2013        | 3       | 
```