# Inspector General - Employment Quarterly Action Reports

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/inspector-general-employment-quarterly-action-reports) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/u6q5-2knd) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/u6q5-2knd/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/u6q5-2knd/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | u6q5-2knd |
| Name | Inspector General - Employment Quarterly Action Reports |
| Attribution | Cook County Office of the Independent Inspector General |
| Created | 2016-07-21T21:43:56Z |
| Publication Date | 2017-03-14T17:29:28Z |

## Description

Pursuant to the Employment Plan, the OIIG prepares quarterly reports listing the total number of hires, promotions, transfers and terminations involving employees during the preceding three month period, including: (i) the number and type of each such employment action; (ii) the dates of each employment action; (iii) the title of the position; and (iv) whether such employment action was pursuant to a posted or emergency hire.

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
series e:u6q5-2knd d:2016-04-01T00:00:00.000Z t:link=http://opendocs.cookcountyil.gov/inspector-general/employment/quarterly/Employment-Action-Report-Second-Quarter-2016.pdf m:row_number.u6q5-2knd=1

series e:u6q5-2knd d:2016-01-01T00:00:00.000Z t:link=http://opendocs.cookcountyil.gov/inspector-general/employment/quarterly/Employment-Action-Report-First-Quarter-2016.pdf m:row_number.u6q5-2knd=2

series e:u6q5-2knd d:2015-10-01T00:00:00.000Z t:link=http://opendocs.cookcountyil.gov/inspector-general/employment/quarterly/Employment-Action-Report-Fourth-Quarter-2015.pdf m:row_number.u6q5-2knd=3
```

## Meta Commands

```ls
metric m:row_number.u6q5-2knd p:long l:"Row Number"

entity e:u6q5-2knd l:"Inspector General - Employment Quarterly Action Reports" t:attribution="Cook County Office of the Independent Inspector General" t:url=https://datacatalog.cookcountyil.gov/api/views/u6q5-2knd

property e:u6q5-2knd t:meta.view v:id=u6q5-2knd v:averageRating=0 v:name="Inspector General - Employment Quarterly Action Reports" v:attribution="Cook County Office of the Independent Inspector General"

property e:u6q5-2knd t:meta.view.license v:name="Public Domain"

property e:u6q5-2knd t:meta.view.owner v:id=u38g-hbsa v:screenName="Cook County Open Data" v:lastNotificationSeenAt=1492536815 v:displayName="Cook County Open Data"

property e:u6q5-2knd t:meta.view.tableauthor v:id=u38g-hbsa v:screenName="Cook County Open Data" v:roleName=administrator v:lastNotificationSeenAt=1492536815 v:displayName="Cook County Open Data"
```

## Top Records

```ls
| link                                                                                                                                                                       | fiscal_year | quarter | 
| ========================================================================================================================================================================== | =========== | ======= | 
| [http://opendocs.cookcountyil.gov/inspector-general/employment/quarterly/Employment-Action-Report-Second-Quarter-2016.pdf, Employment Action Report ? Second Quarter 2016] | 2016        | 2       | 
| [http://opendocs.cookcountyil.gov/inspector-general/employment/quarterly/Employment-Action-Report-First-Quarter-2016.pdf, Employment Action Report ? First Quarter 2016]   | 2016        | 1       | 
| [http://opendocs.cookcountyil.gov/inspector-general/employment/quarterly/Employment-Action-Report-Fourth-Quarter-2015.pdf, Employment Action Report ? Fourth Quarter 2015] | 2015        | 4       | 
| [http://opendocs.cookcountyil.gov/inspector-general/employment/quarterly/Employment-Action-Report-Third-Quarter-2015.pdf, Employment Action Report ? Third Quarter 2015]   | 2015        | 3       | 
| [http://opendocs.cookcountyil.gov/inspector-general/employment/quarterly/Employment-Action-Report-Second-Quarter-2015.pdf, Employment Action Report ? Second Quarter 2015] | 2015        | 2       | 
| [http://opendocs.cookcountyil.gov/inspector-general/employment/quarterly/Employment-Action-Report-First-Quarter-2015.pdf, Employment Action Report ? First Quarter 2015]   | 2015        | 1       | 
| [http://opendocs.cookcountyil.gov/inspector-general/employment/quarterly/Employment-Action-Report-Fourth-Quarter-2014.pdf, Employment Action Report ? Fourth Quarter 2014] | 2014        | 4       | 
| [http://opendocs.cookcountyil.gov/inspector-general/employment/quarterly/Employment-Action-Report-Third-Quarter-2014.pdf, Employment Action Report ? Third Quarter 2014]   | 2014        | 3       | 
| [http://opendocs.cookcountyil.gov/inspector-general/employment/quarterly/Employment-Action-Report-Second-Quarter-2014.pdf, Employment Action Report ? Second Quarter 2015] | 2014        | 2       | 
| [http://opendocs.cookcountyil.gov/inspector-general/employment/quarterly/1st-Quarter-2014.pdf, Employment Action Report ? First Quarter 2014]                              | 2014        | 1       | 
```