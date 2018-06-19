# TIF Status and Eligibility

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/tif-status-and-eligibility-d578b) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/3qsz-jemf) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/3qsz-jemf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/3qsz-jemf/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | 3qsz-jemf |
| Name | TIF Status and Eligibility |
| Attribution | City of Chicago - Office of Budget and Management |
| Category | Community & Economic Development |
| Tags | tif |
| Created | 2012-06-14T17:22:23Z |
| Publication Date | 2012-06-30T13:08:47Z |

## Description

Total number of TIF districts with creation and end dates, and summary of eligibility factors.

## Columns

```ls
| Included | Schema Type | Field Name                | Name                 | Data Type     | Render Type   |
| ======== | =========== | ========================= | ==================== | ============= | ============= |
| Yes      | series tag  | status                    | Status               | text          | text          |
| Yes      | series tag  | ref_number                | Ref. Number          | text          | text          |
| Yes      | series tag  | tif_district_name         | TIF District         | text          | text          |
| Yes      | time        | designation_date          | Designation Date     | calendar_date | calendar_date |
| No       |             | designation_year          | Designation Year     | number        | number        |
| No       |             | end_expiration_date       | End Date             | calendar_date | calendar_date |
| No       |             | expiration_year           | Final Year           | number        | number        |
| Yes      | series tag  | blighting_factors         | Blighting Factors    | text          | text          |
| Yes      | series tag  | conservation_factors      | Conservation Factors | text          | text          |
| Yes      | series tag  | tif_eligiblity_study_plan | Redevelopment Plan   | url           | url           |
```

## Time Field

```ls
Value = designation_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = end_expiration_date,expiration_year,designation_year
```

## Data Commands

```ls
series e:3qsz-jemf d:2006-01-11T00:00:00.000Z t:tif_eligiblity_study_plan=http://www.cityofchicago.org/content/dam/city/depts/dcd/tif/plans/T_141_26thKingRDP.pdf t:blighting_factors=No t:tif_district_name="26th and King Drive" t:status=Active t:conservation_factors=Yes t:ref_number=T-141 m:row_number.3qsz-jemf=1

series e:3qsz-jemf d:1999-07-21T00:00:00.000Z t:tif_eligiblity_study_plan=http://www.cityofchicago.org/content/dam/city/depts/dcd/tif/plans/T_072_24thMichiganRDP.pdf t:blighting_factors=Yes t:tif_district_name=24th/Michigan t:status=Active t:conservation_factors=No t:ref_number=T-072 m:row_number.3qsz-jemf=2

series e:3qsz-jemf d:2001-10-03T00:00:00.000Z t:tif_eligiblity_study_plan=http://www.cityofchicago.org/content/dam/city/depts/dcd/tif/plans/T_111_105thVincennesRDP.pdf t:blighting_factors=Yes t:tif_district_name=105th/Vincennes t:status=Active t:conservation_factors=No t:ref_number=T-111 m:row_number.3qsz-jemf=3
```

## Meta Commands

```ls
metric m:row_number.3qsz-jemf p:long l:"Row Number"

entity e:3qsz-jemf l:"TIF Status and Eligibility" t:attribution="City of Chicago - Office of Budget and Management" t:url=https://data.cityofchicago.org/api/views/3qsz-jemf

property e:3qsz-jemf t:meta.view v:id=3qsz-jemf v:category="Community & Economic Development" v:attributionLink=http://www.cityofchicago.org/city/en/depts/dcd/supp_info/redevelopment_plans.html v:averageRating=0 v:name="TIF Status and Eligibility" v:attribution="City of Chicago - Office of Budget and Management"

property e:3qsz-jemf t:meta.view.license v:name="Public Domain"

property e:3qsz-jemf t:meta.view.owner v:id=7ek2-d4pb v:screenName="David Miller" v:displayName="David Miller"

property e:3qsz-jemf t:meta.view.tableauthor v:id=7ek2-d4pb v:screenName="David Miller" v:roleName=editor v:displayName="David Miller"
```

## Top Records

```ls
| status | ref_number | tif_district_name                            | designation_date    | designation_year | end_expiration_date | expiration_year | blighting_factors | conservation_factors | tif_eligiblity_study_plan                                                                                           | 
| ====== | ========== | ============================================ | =================== | ================ | =================== | =============== | ================= | ==================== | =================================================================================================================== | 
| Active | T-141      | 26th and King Drive                          | 2006-01-11T00:00:00 | 2006             | 2030-12-31T00:00:00 | 2030            | No                | Yes                  | [http://www.cityofchicago.org/content/dam/city/depts/dcd/tif/plans/T_141_26thKingRDP.pdf, Redevelopment Plan]       | 
| Active | T-072      | 24th/Michigan                                | 1999-07-21T00:00:00 | 1999             | 2022-07-21T00:00:00 | 2022            | Yes               | No                   | [http://www.cityofchicago.org/content/dam/city/depts/dcd/tif/plans/T_072_24thMichiganRDP.pdf, Redevelopment Plan]   | 
| Active | T-111      | 105th/Vincennes                              | 2001-10-03T00:00:00 | 2001             | 2025-12-31T00:00:00 | 2025            | Yes               | No                   | [http://www.cityofchicago.org/content/dam/city/depts/dcd/tif/plans/T_111_105thVincennesRDP.pdf, Redevelopment Plan] | 
| Active | T-073      | 111th Street/Kedzie Avenue Business District | 1999-09-29T00:00:00 | 1999             | 2022-09-29T00:00:00 | 2022            | No                | Yes                  | [http://www.cityofchicago.org/content/dam/city/depts/dcd/tif/plans/T_073_111thKedzieRDP.pdf, Redevelopment Plan]    | 
| Active | T-114      | 119th and Halsted                            | 2002-02-06T00:00:00 | 2002             | 2026-12-31T00:00:00 | 2026            | Yes               | No                   | [http://www.cityofchicago.org/content/dam/city/depts/dcd/tif/plans/T_114_119thHalstedRDP.pdf, Redevelopment Plan]   | 
| Active | T-125      | 119th/I-57                                   | 2002-11-06T00:00:00 | 2002             | 2026-12-31T00:00:00 | 2026            | Yes               | No                   | [http://www.cityofchicago.org/content/dam/city/depts/dcd/tif/plans/T_125_119thI57RDP.pdf, Redevelopment Plan]       | 
| Active | T-010      | 126th and Torrence                           | 1994-12-21T00:00:00 | 1994             | 2017-12-21T00:00:00 | 2017            | Yes               | Yes                  | [http://www.cityofchicago.org/content/dam/city/depts/dcd/tif/plans/T_010_126thTorrenceRDP.pdf, Redevelopment Plan]  | 
| Active | T-079      | 35th and Wallace                             | 1999-12-15T00:00:00 | 1999             | 2023-12-31T00:00:00 | 2023            | No                | Yes                  | [http://www.cityofchicago.org/content/dam/city/depts/dcd/tif/plans/T_079_35thWallaceRDP.pdf, Redevelopment Plan]    | 
| Active | T-001      | 35th/Halsted                                 | 1997-01-14T00:00:00 | 1997             | 2021-12-31T00:00:00 | 2021            | Yes               | No                   | [http://www.cityofchicago.org/content/dam/city/depts/dcd/tif/plans/T_001_35thHalstedRDP.pdf, Redevelopment Plan]    | 
| Active | T-131      | 35th/State                                   | 2004-01-14T00:00:00 | 2004             | 2028-12-31T00:00:00 | 2028            | Yes               | No                   | [http://www.cityofchicago.org/content/dam/city/depts/dcd/tif/plans/T_131_35thStateRDP.pdf, Redevelopment Plan]      | 
```