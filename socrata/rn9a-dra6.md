# Budget - Fiscal Year 2017 Executive Recommendation - Capital Equipment

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/budget-fiscal-year-2017-executive-recommendation-capital-equipment) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/rn9a-dra6) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/rn9a-dra6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/rn9a-dra6/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | rn9a-dra6 |
| Name | Budget - Fiscal Year 2017 Executive Recommendation - Capital Equipment |
| Attribution | Cook County Department of Budget & Management Services |
| Category | Finance & Administration |
| Tags | 2017 budget executive recommendation, 2017 budget |
| Created | 2016-10-18T04:25:13Z |
| Publication Date | 2016-10-18T04:29:06Z |

## Description

Executive Recommendation for the Fiscal Year 2017 Budget Capital Equipment. For more information on the budget and schedule of public hearings see http://www.cookcountyil.gov/budget/

## Columns

```ls
| Included | Schema Type    | Field Name            | Name                  | Data Type | Render Type |
| ======== | ============== | ===================== | ===================== | ========= | =========== |
| Yes      | series tag     | office                | Office                | text      | text        |
| Yes      | series tag     | control_officer       | Control Officer       | text      | text        |
| Yes      | series tag     | bureau                | Bureau                | text      | text        |
| Yes      | series tag     | fund                  | Fund                  | text      | text        |
| Yes      | series tag     | department_number     | Department Number     | text      | number      |
| Yes      | series tag     | department_name       | Department Name       | text      | text        |
| Yes      | series tag     | capital_project_title | Capital Project Title | text      | text        |
| Yes      | series tag     | capital_project_type  | Capital Project Type  | text      | text        |
| Yes      | numeric metric | request               | Request               | money     | money       |
| Yes      | numeric metric | account               | Account               | number    | number      |
| Yes      | series tag     | account_name          | Account Name          | text      | text        |
```

## Time Field

```ls
Value = 2017
Format & Zone = yyyy
```

## Data Commands

```ls
series e:rn9a-dra6 d:2017-01-01T00:00:00.000Z t:office="OFFICES UNDER THE PRESIDENT" t:capital_project_title="Shared Fleet" t:department_number=11 t:control_officer="CHIEF ADMINISTRATIVE OFFICER" t:fund="Capital Levy Funding" t:department_name="Office of the Chief Administrative Officer" t:capital_project_type="Vehicle Purchase" t:bureau="BUREAU OF ADMINISTRATION" t:account_name="Vehicle Purchase" m:request=75000 m:account=549

series e:rn9a-dra6 d:2017-01-01T00:00:00.000Z t:office="OFFICES UNDER THE PRESIDENT" t:capital_project_title="Air Monitoring Trailers" t:department_number=161 t:control_officer="CHIEF ADMINISTRATIVE OFFICER" t:fund="Capital Levy Funding" t:department_name="Department of Environmental Control" t:capital_project_type="Fixed Plant or Institutional Equipment" t:bureau="BUREAU OF ADMINISTRATION" t:account_name="Institutional Equipment" m:request=262500 m:account=521

series e:rn9a-dra6 d:2017-01-01T00:00:00.000Z t:office="OFFICES UNDER THE PRESIDENT" t:capital_project_title="Particulate speciation monitors" t:department_number=161 t:control_officer="CHIEF ADMINISTRATIVE OFFICER" t:fund="Capital Levy Funding" t:department_name="Department of Environmental Control" t:capital_project_type="Medical and Lab Equipment" t:bureau="BUREAU OF ADMINISTRATION" t:account_name="Medical, Dental and Laboratory Equipment" m:request=138600 m:account=540
```

## Meta Commands

```ls
metric m:request p:integer l:Request t:dataTypeName=money

metric m:account p:integer l:Account t:dataTypeName=number

entity e:rn9a-dra6 l:"Budget - Fiscal Year 2017 Executive Recommendation - Capital Equipment" t:attribution="Cook County Department of Budget & Management Services" t:url=https://datacatalog.cookcountyil.gov/api/views/rn9a-dra6

property e:rn9a-dra6 t:meta.view v:id=rn9a-dra6 v:category="Finance & Administration" v:attributionLink=http://www.cookcountyil.gov/budget/ v:averageRating=0 v:name="Budget - Fiscal Year 2017 Executive Recommendation - Capital Equipment" v:attribution="Cook County Department of Budget & Management Services"

property e:rn9a-dra6 t:meta.view.license v:name="Public Domain"

property e:rn9a-dra6 t:meta.view.owner v:id=u38g-hbsa v:screenName="Cook County Open Data" v:lastNotificationSeenAt=1492536815 v:displayName="Cook County Open Data"

property e:rn9a-dra6 t:meta.view.tableauthor v:id=u38g-hbsa v:screenName="Cook County Open Data" v:roleName=administrator v:lastNotificationSeenAt=1492536815 v:displayName="Cook County Open Data"
```

## Top Records

```ls
| office                      | control_officer              | bureau                   | fund                 | department_number | department_name                            | capital_project_title                                | capital_project_type                   | request | account | account_name                             | 
| =========================== | ============================ | ======================== | ==================== | ================= | ========================================== | ==================================================== | ====================================== | ======= | ======= | ======================================== | 
| OFFICES UNDER THE PRESIDENT | CHIEF ADMINISTRATIVE OFFICER | BUREAU OF ADMINISTRATION | Capital Levy Funding | 11                | Office of the Chief Administrative Officer | Shared Fleet                                         | Vehicle Purchase                       | 75000   | 549     | Vehicle Purchase                         | 
| OFFICES UNDER THE PRESIDENT | CHIEF ADMINISTRATIVE OFFICER | BUREAU OF ADMINISTRATION | Capital Levy Funding | 161               | Department of Environmental Control        | Air Monitoring Trailers                              | Fixed Plant or Institutional Equipment | 262500  | 521     | Institutional Equipment                  | 
| OFFICES UNDER THE PRESIDENT | CHIEF ADMINISTRATIVE OFFICER | BUREAU OF ADMINISTRATION | Capital Levy Funding | 161               | Department of Environmental Control        | Particulate speciation monitors                      | Medical and Lab Equipment              | 138600  | 540     | Medical, Dental and Laboratory Equipment | 
| OFFICES UNDER THE PRESIDENT | CHIEF ADMINISTRATIVE OFFICER | BUREAU OF ADMINISTRATION | Capital Levy Funding | 161               | Department of Environmental Control        | Sonic Meteorological Data Translation System         | Medical and Lab Equipment              | 29600   | 540     | Medical, Dental and Laboratory Equipment | 
| OFFICES UNDER THE PRESIDENT | CHIEF ADMINISTRATIVE OFFICER | BUREAU OF ADMINISTRATION | Capital Levy Funding | 161               | Department of Environmental Control        | Primary Standard                                     | Medical and Lab Equipment              | 13750   | 540     | Medical, Dental and Laboratory Equipment | 
| OFFICES UNDER THE PRESIDENT | CHIEF ADMINISTRATIVE OFFICER | BUREAU OF ADMINISTRATION | Capital Levy Funding | 161               | Department of Environmental Control        | Secondary Standard                                   | Medical and Lab Equipment              | 10000   | 540     | Medical, Dental and Laboratory Equipment | 
| OFFICES UNDER THE PRESIDENT | CHIEF ADMINISTRATIVE OFFICER | BUREAU OF ADMINISTRATION | Capital Levy Funding | 259               | Medical Examiner                           | Digital Mobile C-Arm ESP with Hybrid Graphic Printer | Medical and Lab Equipment              | 180000  | 540     | Medical, Dental and Laboratory Equipment | 
| OFFICES UNDER THE PRESIDENT | CHIEF ADMINISTRATIVE OFFICER | BUREAU OF ADMINISTRATION | Capital Levy Funding | 259               | Medical Examiner                           | Toxicology Blood Banks                               | Medical and Lab Equipment              | 80000   | 540     | Medical, Dental and Laboratory Equipment | 
| OFFICES UNDER THE PRESIDENT | CHIEF ADMINISTRATIVE OFFICER | BUREAU OF ADMINISTRATION | Capital Levy Funding | 259               | Medical Examiner                           | STAT Drug Analyzer                                   | Medical and Lab Equipment              | 70000   | 540     | Medical, Dental and Laboratory Equipment | 
| OFFICES UNDER THE PRESIDENT | CHIEF ADMINISTRATIVE OFFICER | BUREAU OF ADMINISTRATION | Capital Levy Funding | 259               | Medical Examiner                           | SCBA - Hazmat PPE w/ storage cabinets                | Medical and Lab Equipment              | 55000   | 540     | Medical, Dental and Laboratory Equipment | 
```