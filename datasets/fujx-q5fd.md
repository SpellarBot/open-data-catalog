# Inspector General - Quarterly Reports

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/inspector-general-quarterly-reports) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/fujx-q5fd) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/fujx-q5fd/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/fujx-q5fd/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | fujx-q5fd |
| Name | Inspector General - Quarterly Reports |
| Attribution | Cook County Office of the Independent Inspector General |
| Category | Finance & Administration |
| Tags | oiig |
| Created | 2016-05-18T21:08:04Z |
| Publication Date | 2017-04-14T21:04:56Z |

## Description

The Independent Inspector General submits a Quarterly Report to the President and the County Board. The Quarterly Report is released the 15th day of January, April, July, and October of each year. Quarterly Reports chronicle the number and type of investigations initiated, concluded or pending since the date of the last report. The Quarterly Report identifies the number and type of investigations (corruption, fraud, waste, mismanagement, unlawful political discrimination or misconduct) of any County employee, appointed officials, elected officials, contractors, subcontractors, persons seeking County Contracts, or persons seeking certification of eligibility for County contracts or other County Programs. The Quarterly Report identifies the number and type of investigations conducted by the OIIG regarding employees under the separately elected officials. The Quarterly Report identifies the number and type of recommendations made to any department heads or elected officials and whether or not the recommendation was followed.

## Columns

```ls
| Included | Schema Type | Field Name  | Name        | Data Type     | Render Type   |
| ======== | =========== | =========== | =========== | ============= | ============= |
| Yes      | series tag  | link        | Link        | url           | url           |
| Yes      | time        | date_issued | Date Issued | calendar_date | calendar_date |
| No       |             | fiscal_year | Fiscal Year | calendar_date | calendar_date |
| No       |             | quarter     | Quarter     | number        | number        |
```

## Time Field

```ls
Value = date_issued
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = fiscal_year,quarter
```

## Data Commands

```ls
series e:fujx-q5fd d:2016-04-15T00:00:00.000Z t:link=http://opendocs.cookcountyil.gov/inspector-general/quarterly-reports/OIIG-Quarterly-Report-1st-Qtr-2016.pdf m:row_number.fujx-q5fd=1

series e:fujx-q5fd d:2016-01-15T00:00:00.000Z t:link=http://opendocs.cookcountyil.gov/inspector-general/quarterly-reports/OIIG-Quarterly-Report-4th-Qtr-2015.pdf m:row_number.fujx-q5fd=2

series e:fujx-q5fd d:2015-10-15T00:00:00.000Z t:link=http://opendocs.cookcountyil.gov/inspector-general/quarterly-reports/OIIG-Quarterly-Report-3rd-Qtr-2015.pdf m:row_number.fujx-q5fd=3
```

## Meta Commands

```ls
metric m:row_number.fujx-q5fd p:long l:"Row Number"

entity e:fujx-q5fd l:"Inspector General - Quarterly Reports" t:attribution="Cook County Office of the Independent Inspector General" t:url=https://datacatalog.cookcountyil.gov/api/views/fujx-q5fd

property e:fujx-q5fd t:meta.view v:id=fujx-q5fd v:category="Finance & Administration" v:averageRating=0 v:name="Inspector General - Quarterly Reports" v:attribution="Cook County Office of the Independent Inspector General"

property e:fujx-q5fd t:meta.view.license v:name="Public Domain"

property e:fujx-q5fd t:meta.view.owner v:id=u38g-hbsa v:screenName="Cook County Open Data" v:lastNotificationSeenAt=1492536815 v:displayName="Cook County Open Data"

property e:fujx-q5fd t:meta.view.tableauthor v:id=u38g-hbsa v:screenName="Cook County Open Data" v:roleName=administrator v:lastNotificationSeenAt=1492536815 v:displayName="Cook County Open Data"
```

## Top Records

```ls
| link                                                                                                                                                   | date_issued         | fiscal_year         | quarter | 
| ====================================================================================================================================================== | =================== | =================== | ======= | 
| [http://opendocs.cookcountyil.gov/inspector-general/quarterly-reports/OIIG-Quarterly-Report-1st-Qtr-2016.pdf, OIIG Quarterly Report 1st Quarter 2016]  | 2016-04-15T00:00:00 | 2016-01-01T00:00:00 | 1       | 
| [http://opendocs.cookcountyil.gov/inspector-general/quarterly-reports/OIIG-Quarterly-Report-4th-Qtr-2015.pdf, OIIG Quarterly Report 4th Quarter 2015]  | 2016-01-15T00:00:00 | 2015-01-01T00:00:00 | 4       | 
| [http://opendocs.cookcountyil.gov/inspector-general/quarterly-reports/OIIG-Quarterly-Report-3rd-Qtr-2015.pdf, OIIG Quarterly Report 3rd Quarter 2015]  | 2015-10-15T00:00:00 | 2015-01-01T00:00:00 | 3       | 
| [http://opendocs.cookcountyil.gov/inspector-general/quarterly-reports/OIIG-Quarterly-Report-2nd-Qtr-2015.pdf, OIIG Quarterly Report 2nd Quarter 2015]  | 2015-07-15T00:00:00 | 2015-01-01T00:00:00 | 2       | 
| [http://opendocs.cookcountyil.gov/inspector-general/quarterly-reports/OIIG-Quarterly-Report-1st-Qtr-2015.pdf, OIIG Quarterly Report 1st Quarter 2015]  | 2015-04-15T00:00:00 | 2015-01-01T00:00:00 | 1       | 
| [http://opendocs.cookcountyil.gov/inspector-general/quarterly-reports/OIIG-Quarterly-Report-4th-Qtr-2014.pdf, OIIG Quarterly Report 4th Quarter 2014]  | 2015-01-15T00:00:00 | 2014-01-01T00:00:00 | 4       | 
| [http://opendocs.cookcountyil.gov/inspector-general/quarterly-reports/OIIG-Quarterly-Report-3rd-Qtr-2014.pdf, OIIG Quarterly Report 3rd Quarter 2014]  | 2014-10-15T00:00:00 | 2014-01-01T00:00:00 | 3       | 
| [http://opendocs.cookcountyil.gov/inspector-general/quarterly-reports/OIIG-Quarterly-Report-2nd-Qtr-20141.pdf, OIIG Quarterly Report 2nd Quarter 2014] | 2014-07-15T00:00:00 | 2014-01-01T00:00:00 | 2       | 
| [http://opendocs.cookcountyil.gov/inspector-general/quarterly-reports/OIIG-Quarterly-Report-1st-Qtr-2014.pdf, OIIG Quarterly Report 1st Quarter 2014]  | 2014-04-15T00:00:00 | 2014-01-01T00:00:00 | 1       | 
| [http://opendocs.cookcountyil.gov/inspector-general/quarterly-reports/OIIG-Quarterly-Report-4th-Qtr-2013.pdf, OIIG Quarterly Report 4th Quarter 2013]  | 2014-01-15T00:00:00 | 2013-01-01T00:00:00 | 4       | 
```