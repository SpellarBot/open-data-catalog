# Budget - Fiscal Year 2016 Executive Recommendation - Capital Equipment

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/budget-fiscal-year-2016-executive-recommendation-capital-equipment) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/pgvr-x745) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/pgvr-x745/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/pgvr-x745/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | pgvr-x745 |
| Name | Budget - Fiscal Year 2016 Executive Recommendation - Capital Equipment |
| Attribution | Cook County Department of Budget & Management Services |
| Category | Finance & Administration |
| Tags | 2016 budget executive recommendation |
| Created | 2015-10-14T15:55:17Z |
| Publication Date | 2015-10-14T16:00:07Z |

## Description

Executive Recommendation for the Fiscal Year 2016 Budget Capital Equipment. For more information on the budget and schedule of public hearings see http://www.cookcountyil.gov/budget/

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
Value = 2016
Format & Zone = yyyy
```

## Data Commands

```ls
series e:pgvr-x745 d:2016-01-01T00:00:00.000Z t:office="OFFICES UNDER THE PRESIDENT" t:capital_project_title="Vehicle Replacement" t:department_number=161 t:control_officer="CHIEF ADMINISTRATIVE OFFICER" t:fund="Debit Proceeds" t:department_name="Department of Environmental Control" t:capital_project_type="Vehicle Purchase" t:bureau="BUREAU OF ADMINISTRATION" t:account_name="Vehicle Purchase" m:request=51000 m:account=549

series e:pgvr-x745 d:2016-01-01T00:00:00.000Z t:office="OFFICES UNDER THE PRESIDENT" t:capital_project_title="TSP Particle Sampler" t:department_number=161 t:control_officer="CHIEF ADMINISTRATIVE OFFICER" t:fund="Debit Proceeds" t:department_name="Department of Environmental Control" t:capital_project_type="Medical and Lab Equipment" t:bureau="BUREAU OF ADMINISTRATION" t:account_name="Medical, Dental and Laboratory Equipment" m:request=88500 m:account=540

series e:pgvr-x745 d:2016-01-01T00:00:00.000Z t:office="OFFICES UNDER THE PRESIDENT" t:capital_project_title="Nox Monitor" t:department_number=161 t:control_officer="CHIEF ADMINISTRATIVE OFFICER" t:fund="Debit Proceeds" t:department_name="Department of Environmental Control" t:capital_project_type="Medical and Lab Equipment" t:bureau="BUREAU OF ADMINISTRATION" t:account_name="Medical, Dental and Laboratory Equipment" m:request=30000 m:account=540
```

## Meta Commands

```ls
metric m:request p:integer l:Request t:dataTypeName=money

metric m:account p:integer l:Account t:dataTypeName=number

entity e:pgvr-x745 l:"Budget - Fiscal Year 2016 Executive Recommendation - Capital Equipment" t:attribution="Cook County Department of Budget & Management Services" t:url=https://datacatalog.cookcountyil.gov/api/views/pgvr-x745

property e:pgvr-x745 t:meta.view v:id=pgvr-x745 v:category="Finance & Administration" v:attributionLink=http://www.cookcountyil.gov/budget/ v:averageRating=0 v:name="Budget - Fiscal Year 2016 Executive Recommendation - Capital Equipment" v:attribution="Cook County Department of Budget & Management Services"

property e:pgvr-x745 t:meta.view.license v:name="Public Domain"

property e:pgvr-x745 t:meta.view.owner v:id=u38g-hbsa v:screenName="Cook County Open Data" v:lastNotificationSeenAt=1492536815 v:displayName="Cook County Open Data"

property e:pgvr-x745 t:meta.view.tableauthor v:id=u38g-hbsa v:screenName="Cook County Open Data" v:roleName=administrator v:lastNotificationSeenAt=1492536815 v:displayName="Cook County Open Data"
```

## Top Records

```ls
| office                      | control_officer              | bureau                   | fund           | department_number | department_name                           | capital_project_title                 | capital_project_type      | request | account | account_name                             | 
| =========================== | ============================ | ======================== | ============== | ================= | ========================================= | ===================================== | ========================= | ======= | ======= | ======================================== | 
| OFFICES UNDER THE PRESIDENT | CHIEF ADMINISTRATIVE OFFICER | BUREAU OF ADMINISTRATION | Debit Proceeds | 161               | Department of Environmental Control       | Vehicle Replacement                   | Vehicle Purchase          | 51000   | 549     | Vehicle Purchase                         | 
| OFFICES UNDER THE PRESIDENT | CHIEF ADMINISTRATIVE OFFICER | BUREAU OF ADMINISTRATION | Debit Proceeds | 161               | Department of Environmental Control       | TSP Particle Sampler                  | Medical and Lab Equipment | 88500   | 540     | Medical, Dental and Laboratory Equipment | 
| OFFICES UNDER THE PRESIDENT | CHIEF ADMINISTRATIVE OFFICER | BUREAU OF ADMINISTRATION | Debit Proceeds | 161               | Department of Environmental Control       | Nox Monitor                           | Medical and Lab Equipment | 30000   | 540     | Medical, Dental and Laboratory Equipment | 
| OFFICES UNDER THE PRESIDENT | CHIEF ADMINISTRATIVE OFFICER | BUREAU OF ADMINISTRATION | Debit Proceeds | 259               | Medical Examiner                          | Surgical Microscope with Camera/Stand | Medical and Lab Equipment | 25000   | 540     | Medical, Dental and Laboratory Equipment | 
| OFFICES UNDER THE PRESIDENT | CHIEF ADMINISTRATIVE OFFICER | BUREAU OF ADMINISTRATION | Debit Proceeds | 259               | Medical Examiner                          | Upgrade Radiology Hardware/Software   | Medical and Lab Equipment | 50000   | 540     | Medical, Dental and Laboratory Equipment | 
| OFFICES UNDER THE PRESIDENT | CHIEF ADMINISTRATIVE OFFICER | BUREAU OF ADMINISTRATION | Debit Proceeds | 259               | Medical Examiner                          | Replace Autopsy Bench Scales          | Medical and Lab Equipment | 15000   | 540     | Medical, Dental and Laboratory Equipment | 
| OFFICES UNDER THE PRESIDENT | CHIEF ADMINISTRATIVE OFFICER | BUREAU OF ADMINISTRATION | Debit Proceeds | 259               | Medical Examiner                          | Heavy Duty Autopsy Carts              | Medical and Lab Equipment | 10000   | 540     | Medical, Dental and Laboratory Equipment | 
| OFFICES UNDER THE PRESIDENT | CHIEF ADMINISTRATIVE OFFICER | BUREAU OF ADMINISTRATION | Debit Proceeds | 500               | Department of Transportation and Highways | Snow Fighters                         | Vehicle Purchase          | 540000  | 549     | Vehicle Purchase                         | 
| OFFICES UNDER THE PRESIDENT | CHIEF ADMINISTRATIVE OFFICER | BUREAU OF ADMINISTRATION | Debit Proceeds | 500               | Department of Transportation and Highways | SUV Passenger Vehicles                | Vehicle Purchase          | 124000  | 549     | Vehicle Purchase                         | 
| OFFICES UNDER THE PRESIDENT | CHIEF ADMINISTRATIVE OFFICER | BUREAU OF ADMINISTRATION | Debit Proceeds | 500               | Department of Transportation and Highways | Crew-cab Pick-up Trucks               | Vehicle Purchase          | 120000  | 549     | Vehicle Purchase                         | 
```