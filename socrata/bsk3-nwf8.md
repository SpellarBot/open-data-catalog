# Human Resources - Compliance Officer?s Semi-Annual Reports

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/human-resources-compliance-officers-semi-annual-reports) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/bsk3-nwf8) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/bsk3-nwf8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/bsk3-nwf8/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | bsk3-nwf8 |
| Name | Human Resources - Compliance Officer?s Semi-Annual Reports |
| Attribution | Cook County Bureau of Human Resources |
| Category | Finance & Administration |
| Created | 2016-05-19T01:46:14Z |
| Publication Date | 2017-03-22T17:36:47Z |

## Description

These reports are issued every March 15th and September 15th.

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
| Included | Schema Type | Field Name | Name | Data Type     | Render Type   |
| ======== | =========== | ========== | ==== | ============= | ============= |
| Yes      | series tag  | link       | Link | url           | url           |
| Yes      | time        | date       | Date | calendar_date | calendar_date |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:bsk3-nwf8 d:2016-03-14T00:00:00.000Z t:link=http://opendocs.cookcountyil.gov/human-resources/compliance/semi-annual/compliance-officers-semi-annual-report-march-2016.pdf m:row_number.bsk3-nwf8=1

series e:bsk3-nwf8 d:2015-09-14T00:00:00.000Z t:link=http://opendocs.cookcountyil.gov/human-resources/compliance/semi-annual/compliance-officers-semi-annual-report-september-2015.pdf m:row_number.bsk3-nwf8=2

series e:bsk3-nwf8 d:2015-03-13T00:00:00.000Z t:link=http://opendocs.cookcountyil.gov/human-resources/compliance/semi-annual/march-2015-semi-annual-report.pdf m:row_number.bsk3-nwf8=3
```

## Meta Commands

```ls
metric m:row_number.bsk3-nwf8 p:long l:"Row Number"

entity e:bsk3-nwf8 l:"Human Resources - Compliance Officer?s Semi-Annual Reports" t:attribution="Cook County Bureau of Human Resources" t:url=https://datacatalog.cookcountyil.gov/api/views/bsk3-nwf8

property e:bsk3-nwf8 t:meta.view v:id=bsk3-nwf8 v:category="Finance & Administration" v:averageRating=0 v:name="Human Resources - Compliance Officer?s Semi-Annual Reports" v:attribution="Cook County Bureau of Human Resources"

property e:bsk3-nwf8 t:meta.view.license v:name="Public Domain"

property e:bsk3-nwf8 t:meta.view.owner v:id=u38g-hbsa v:screenName="Cook County Open Data" v:lastNotificationSeenAt=1492536815 v:displayName="Cook County Open Data"

property e:bsk3-nwf8 t:meta.view.tableauthor v:id=u38g-hbsa v:screenName="Cook County Open Data" v:roleName=administrator v:lastNotificationSeenAt=1492536815 v:displayName="Cook County Open Data"
```

## Top Records

```ls
| link                                                                                                                                                                                        | date                | 
| =========================================================================================================================================================================================== | =================== | 
| [http://opendocs.cookcountyil.gov/human-resources/compliance/semi-annual/compliance-officers-semi-annual-report-march-2016.pdf, Compliance Officer?s Semi-Annual Report March 2016]         | 2016-03-14T00:00:00 | 
| [http://opendocs.cookcountyil.gov/human-resources/compliance/semi-annual/compliance-officers-semi-annual-report-september-2015.pdf, Compliance Officer?s Semi-Annual Report September 2015] | 2015-09-14T00:00:00 | 
| [http://opendocs.cookcountyil.gov/human-resources/compliance/semi-annual/march-2015-semi-annual-report.pdf, Compliance Officer?s Semi-Annual Report March 2015]                             | 2015-03-13T00:00:00 | 
| [http://opendocs.cookcountyil.gov/human-resources/compliance/semi-annual/compliance-officers-semi-annual-report-september-2014.pdf, Compliance Officer?s Semi-Annual Report September 2014] | 2014-09-12T00:00:00 | 
| [http://opendocs.cookcountyil.gov/human-resources/compliance/semi-annual/march-2014-semi-annual-report.pdf, Compliance Officer?s Semi-Annual Report March 2014]                             | 2014-03-14T00:00:00 | 
| [http://opendocs.cookcountyil.gov/human-resources/compliance/semi-annual/september-2013-semi-annual-report.pdf, Compliance Officer?s Semi-Annual Report September 2013]                     | 2013-09-13T00:00:00 | 
| [http://opendocs.cookcountyil.gov/human-resources/compliance/semi-annual/march-2013-semi-annual-report.pdf, Compliance Officer?s Semi-Annual Report March 2013]                             | 2013-03-15T00:00:00 | 
| [http://opendocs.cookcountyil.gov/human-resources/compliance/semi-annual/compliance-officers-semi-annual-report-september-2012.pdf, Compliance Officer?s Semi-Annual Report September 2012] | 2012-09-14T00:00:00 | 
| [http://opendocs.cookcountyil.gov/human-resources/compliance/semi-annual/compliance-officers-semi-annual-report-september-2016.pdf, Compliance Officer's Semi-Annual Report September 2016] | 2016-09-15T00:00:00 | 
| [http://opendocs.cookcountyil.gov/human-resources/compliance/semi-annual/compliance-officers-semi-annual-report-march-2017.pdf, Compliance Officer?s Semi-Annual Report March 2017]         | 2017-03-15T00:00:00 | 
```