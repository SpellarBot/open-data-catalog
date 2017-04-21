# NYC City Hall Library Publications

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nyc-city-hall-library-publications-a939b) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/ei8e-zggc) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/ei8e-zggc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/ei8e-zggc/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | ei8e-zggc |
| Name | NYC City Hall Library Publications |
| Attribution | Department of Records and Information Services (RECORDS) |
| Category | Recreation |
| Tags | library, catalog, catalogue, report, study, studies, depository, records, official, publication |
| Created | 2011-10-08T22:51:34Z |
| Publication Date | 2013-06-21T20:26:40Z |

## Description

"Official publications submitted by city agencies in electronic format to the City Hall Library, also available at http://nyc.gov/html/records/html/govpub/home.shtml "

## Columns

```ls
| Included | Schema Type | Field Name  | Name        | Data Type | Render Type |
| ======== | =========== | =========== | =========== | ========= | =========== |
| No       | time        | :updated_at | updated_at  | meta_data | meta_data   |
| Yes      | series tag  | publication | Publication | text      | text        |
| Yes      | series tag  | category    | Category    | text      | text        |
| Yes      | series tag  | format      | Format      | text      | text        |
| No       |             | date        | Date        | text      | text        |
| Yes      | series tag  | category_2  | Category 2  | text      | text        |
| Yes      | series tag  | description | Description | text      | text        |
| Yes      | series tag  | category_3  | Category 3  | text      | text        |
| Yes      | series tag  | url         | URL         | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = date
```

## Data Commands

```ls
series e:ei8e-zggc d:2011-10-08T15:51:35.000Z t:category="Independent Budget" t:category_3="Budget Report" t:description="With Welfare Surplus Shrinking City Could Face $80 Million Aid Loss" t:category_2="Finance and Budget" t:format="Fiscal Brief (7 pages-PDF Format)" t:url=http://nyc.gov/html/records/pdf/govpub/972tanfsurplus2004fb.pdf t:publication="With Welfare Surplus Shrinking City Could Face $80 Million Aid Loss" m:row_number.ei8e-zggc=1

series e:ei8e-zggc d:2011-10-08T15:51:35.000Z t:category="Independent Budget" t:category_3="Budget Report" t:description="Police Overtime: Tracking the Big Growth in Spending" t:category_2="Finance and Budget" t:format="Fiscal Brief (7 pages-PDF Format)" t:url=http://nyc.gov/html/records/pdf/govpub/971nypdotfiscalbrief.pdf t:publication="Police Overtime: Tracking the Big Growth in Spending" m:row_number.ei8e-zggc=2

series e:ei8e-zggc d:2011-10-08T15:51:35.000Z t:category="Independent Budget" t:category_3="Budget Report" t:description="Inside the Budget, No. 129 As Federal Aid Drops, City's Cost for Policing Public Housing Climbs" t:category_2="Finance and Budget" t:format="IBO Newsfax, 3 pages PDF Format" t:url=http://nyc.gov/html/records/pdf/govpub/970insidethebudget129.pdf t:publication="Inside the Budget, No. 129 As Federal Aid Drops, City's Cost for Policing Public Housing Climbs" m:row_number.ei8e-zggc=3
```

## Meta Commands

```ls
metric m:row_number.ei8e-zggc p:long l:"Row Number"

entity e:ei8e-zggc l:"NYC City Hall Library Publications" t:attribution="Department of Records and Information Services (RECORDS)" t:url=https://data.cityofnewyork.us/api/views/ei8e-zggc

property e:ei8e-zggc t:meta.view v:id=ei8e-zggc v:category=Recreation v:averageRating=0 v:name="NYC City Hall Library Publications" v:attribution="Department of Records and Information Services (RECORDS)"

property e:ei8e-zggc t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:ei8e-zggc t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | publication                                                                                                                                          | category            | format                                                                                                                                                                                                                                                          | date      | category_2         | description                                                                                                                                          | category_3    | url                                                                       | 
| =========== | ==================================================================================================================================================== | =================== | =============================================================================================================================================================================================================================================================== | ========= | ================== | ==================================================================================================================================================== | ============= | ========================================================================= | 
| 1318089095  | With Welfare Surplus Shrinking City Could Face $80 Million Aid Loss                                                                                  | Independent Budget  | Fiscal Brief (7 pages-PDF Format)                                                                                                                                                                                                                               | 06-Apr-04 | Finance and Budget | With Welfare Surplus Shrinking City Could Face $80 Million Aid Loss                                                                                  | Budget Report | http://nyc.gov/html/records/pdf/govpub/972tanfsurplus2004fb.pdf           | 
| 1318089095  | Police Overtime: Tracking the Big Growth in Spending                                                                                                 | Independent Budget  | Fiscal Brief (7 pages-PDF Format)                                                                                                                                                                                                                               | 29-Apr-04 | Finance and Budget | Police Overtime: Tracking the Big Growth in Spending                                                                                                 | Budget Report | http://nyc.gov/html/records/pdf/govpub/971nypdotfiscalbrief.pdf           | 
| 1318089095  | Inside the Budget, No. 129 As Federal Aid Drops, City's Cost for Policing Public Housing Climbs                                                      | Independent Budget  | IBO Newsfax, 3 pages PDF Format                                                                                                                                                                                                                                 | 15-Apr-04 | Finance and Budget | Inside the Budget, No. 129 As Federal Aid Drops, City's Cost for Policing Public Housing Climbs                                                      | Budget Report | http://nyc.gov/html/records/pdf/govpub/970insidethebudget129.pdf          | 
| 1318089095  | Emergency Contraception: Available at a Hospital EMERGENCY ROOM near you?                                                                            | City Council        | On April 21, 2004, City Council Speaker Gifford Miller, Council Member Christine Quinn, Chair of the Health Committee, Council Member Gioia, Chair of the Oversight and Investigations Committee and Council Member Eva Moskowitz released a Council Investiga  | 21-Apr-04 | Health             | Emergency Contraception: Available at a Hospital EMERGENCY ROOM near you?                                                                            | Report        | http://nyc.gov/html/records/pdf/govpub/959em_contra.pdf                   | 
| 1318089095  | DOI's Examination of the Circumstances Surrounding the Assault of a Firefighter and Subsequent Cover-up at the NYC FDNY Engine Co. 151/Ladder Co. 76 | DOI - Investigation | This report summarizes DOI's findings to date relating to Firefighter Michael Silvestri's assault on Firefighter Robert Walsh with a metal chair on December 31, 2003 inside a New York City firehouse located in Staten Island. This report concludes that fol | 24-Mar-04 | Labor Relations    | DOI's Examination of the Circumstances Surrounding the Assault of a Firefighter and Subsequent Cover-up at the NYC FDNY Engine Co. 151/Ladder Co. 76 | Report        | http://nyc.gov/html/records/pdf/govpub/957fdny_final_3-24-04.pdf          | 
| 1318089095  | 2002-2003 DOI Annual Report                                                                                                                          | DOI - Investigation | The 2002-2003 Annual Report chronicles DOI's efforts. It defines the agency and describes its big, impact cases, as well as its recommendations to improve government operations.                                                                               | 01-Jul-03 | Government Policy  | 2002-2003 DOI Annual Report                                                                                                                          | Annual Report | http://nyc.gov/html/records/pdf/govpub/9562002-2003_doi_annual_report.pdf | 
| 1318089095  | Civil List- Section 2                                                                                                                                | Citywide Admin Svcs | The Civil List is the annual report of all City of New York employees listed by name, title, agency and salary.                                                                                                                                                 | 01-Apr-04 | Labor Relations    | Civil List                                                                                                                                           | Annual Report | http://nyc.gov/html/records/pdf/govpub/952civil_list_2.pdf                | 
| 1318089095  | Civil List- Section 1                                                                                                                                | Citywide Admin Svcs | The Civil List is the annual report of all City of New York employees listed by name, title, agency and salary.                                                                                                                                                 | 01-Apr-04 | Labor Relations    | Civil List                                                                                                                                           | Annual Report | http://nyc.gov/html/records/pdf/govpub/952civil_list_1.pdf                | 
| 1318089095  | IBO Fiscal Brief, Refuse and Recycling: Comparing the Costs                                                                                          | Independent Budget  | IBO Fiscal Brief, 7 pages PDF Format                                                                                                                                                                                                                            | 02-Feb-04 | Finance and Budget | IBO Fiscal Brief, Refuse and Recycling: Comparing the Costs                                                                                          | Budget Report | http://nyc.gov/html/records/pdf/govpub/939refuseandrecycle.pdf            | 
| 1318089095  | Analysis of The Mayor's Preliminary Budget For 2005                                                                                                  | Independent Budget  | Mandated Report, 123 pages PDF Format                                                                                                                                                                                                                           | 15-Mar-04 | Finance and Budget | Analysis of The Mayor's Preliminary Budget For 2005                                                                                                  | Budget Report | http://nyc.gov/html/records/pdf/govpub/938march2004forweb.pdf             | 
```