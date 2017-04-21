# Auditor - Reports

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/auditor-reports) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/4u8a-te7p) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/4u8a-te7p/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/4u8a-te7p/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | 4u8a-te7p |
| Name | Auditor - Reports |
| Attribution | Cook County Office of the County Auditor |
| Category | Finance & Administration |
| Tags | audit |
| Created | 2016-06-21T19:43:00Z |
| Publication Date | 2016-11-17T21:04:55Z |

## Columns

```ls
| Included | Schema Type | Field Name  | Name        | Data Type     | Render Type   |
| ======== | =========== | =========== | =========== | ============= | ============= |
| Yes      | series tag  | link        | Link        | url           | url           |
| Yes      | time        | report_date | Report Date | calendar_date | calendar_date |
| No       |             | fiscal_year | Fiscal Year | calendar_date | calendar_date |
```

## Time Field

```ls
Value = report_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = fiscal_year
```

## Data Commands

```ls
series e:4u8a-te7p d:2016-01-25T00:00:00.000Z t:link=http://opendocs.cookcountyil.gov/auditor/reports/Software-Licenses-Final-Audit-Report.pdf m:row_number.4u8a-te7p=1

series e:4u8a-te7p d:2016-01-26T00:00:00.000Z t:link=http://opendocs.cookcountyil.gov/auditor/reports/Travel-Expenditures-Final-Audit-Report.pdf m:row_number.4u8a-te7p=2

series e:4u8a-te7p d:2015-10-23T00:00:00.000Z t:link=http://opendocs.cookcountyil.gov/auditor/reports/CCC-Revenue-Process-Final-Audit-Report.pdf m:row_number.4u8a-te7p=3
```

## Meta Commands

```ls
metric m:row_number.4u8a-te7p p:long l:"Row Number"

entity e:4u8a-te7p l:"Auditor - Reports" t:attribution="Cook County Office of the County Auditor" t:url=https://datacatalog.cookcountyil.gov/api/views/4u8a-te7p

property e:4u8a-te7p t:meta.view v:id=4u8a-te7p v:category="Finance & Administration" v:averageRating=0 v:name="Auditor - Reports" v:attribution="Cook County Office of the County Auditor"

property e:4u8a-te7p t:meta.view.license v:name="Public Domain"

property e:4u8a-te7p t:meta.view.owner v:id=u38g-hbsa v:screenName="Cook County Open Data" v:lastNotificationSeenAt=1492536815 v:displayName="Cook County Open Data"

property e:4u8a-te7p t:meta.view.tableauthor v:id=u38g-hbsa v:screenName="Cook County Open Data" v:roleName=administrator v:lastNotificationSeenAt=1492536815 v:displayName="Cook County Open Data"
```

## Top Records

```ls
| link                                                                                                                                                                 | report_date         | fiscal_year         | 
| ==================================================================================================================================================================== | =================== | =================== | 
| [http://opendocs.cookcountyil.gov/auditor/reports/Software-Licenses-Final-Audit-Report.pdf, Software Licenses Final Audit Report]                                    | 2016-01-25T00:00:00 | 2016-01-01T00:00:00 | 
| [http://opendocs.cookcountyil.gov/auditor/reports/Travel-Expenditures-Final-Audit-Report.pdf, Travel Expenditures Final Audit Report]                                | 2016-01-26T00:00:00 | 2016-01-01T00:00:00 | 
| [http://opendocs.cookcountyil.gov/auditor/reports/CCC-Revenue-Process-Final-Audit-Report.pdf, CCC Revenue Process Final Audit Report]                                | 2015-10-23T00:00:00 | 2015-01-01T00:00:00 | 
| [http://opendocs.cookcountyil.gov/auditor/reports/CDBG-Final-Audit-Report.pdf, CDBG Final Audit Report]                                                              | 2015-01-07T00:00:00 | 2015-01-01T00:00:00 | 
| [http://opendocs.cookcountyil.gov/auditor/reports/Court-Reporting-Orders-Process-Final-Audit-Report.pdf, Court Reporting Orders Process Final Audit Report]          | 2015-01-28T00:00:00 | 2015-01-01T00:00:00 | 
| [http://opendocs.cookcountyil.gov/auditor/reports/Delinquent-Home-Rule-Taxes-Final-Audit-Report.pdf, Delinquent Home Rule Taxes Final Audit Report]                  | 2015-01-28T00:00:00 | 2015-01-01T00:00:00 | 
| [http://opendocs.cookcountyil.gov/auditor/reports/Dental-Insurance-Benefits-Contract-Final-Audit-Report1.pdf, Dental Insurance Benefits Contract Final Audit Report] | 2015-04-09T00:00:00 | 2015-01-01T00:00:00 | 
| [http://opendocs.cookcountyil.gov/auditor/reports/DOTH-Sale-of-Permits-Final-Audit-Report.pdf, DOTH Sale of Permits Final Audit Report]                              | 2015-05-27T00:00:00 | 2015-01-01T00:00:00 | 
| [http://opendocs.cookcountyil.gov/auditor/reports/FPDCC-Cash-Management-Final-Audit-Report.pdf, FPDCC Cash Management Final Audit Report]                            | 2015-04-20T00:00:00 | 2015-01-01T00:00:00 | 
| [http://opendocs.cookcountyil.gov/auditor/reports/ICF-Final-Audit-Report.pdf, ICF Final Audit Report]                                                                | 2015-09-22T00:00:00 | 2015-01-01T00:00:00 | 
```