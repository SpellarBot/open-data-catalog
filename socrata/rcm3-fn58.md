# NOLA Permits

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nola-permits) |
| Metadata | [Link](https://data.nola.gov/api/views/rcm3-fn58) |
| Data: JSON | [100 Rows](https://data.nola.gov/api/views/rcm3-fn58/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.nola.gov/api/views/rcm3-fn58/rows.csv?max_rows=100) |
| Host | data.nola.gov |
| Id | rcm3-fn58 |
| Name | NOLA Permits |
| Category | Housing, Land Use, and Blight |
| Tags | city of new orleans, permits |
| Created | 2013-02-19T17:40:42Z |
| Publication Date | 2014-11-12T21:55:46Z |

## Description

City of New Orleans permit data starting from 1/01/2012; Updated nightly.Note: For download of entire dataset, export as .csv

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type     | Render Type   |
| ======== | ============== | ================= | ================= | ============= | ============= |
| No       |                | address           | Address           | text          | text          |
| Yes      | series tag     | owner             | Owner             | text          | text          |
| Yes      | series tag     | description       | Description       | text          | text          |
| Yes      | series tag     | numstring         | NumString         | text          | text          |
| Yes      | series tag     | isclosed          | IsClosed          | text          | text          |
| Yes      | series tag     | type              | Type              | text          | text          |
| Yes      | series tag     | code              | Code              | text          | text          |
| Yes      | series tag     | division          | Division          | text          | text          |
| Yes      | series tag     | m_s               | M_S               | text          | text          |
| No       |                | filingdate        | FilingDate        | calendar_date | calendar_date |
| Yes      | time           | issuedate         | IssueDate         | calendar_date | calendar_date |
| Yes      | series tag     | currentstatus     | CurrentStatus     | text          | text          |
| Yes      | series tag     | nextstatus        | NextStatus        | text          | text          |
| No       |                | currentstatusdate | CurrentStatusDate | calendar_date | calendar_date |
| No       |                | nextstatusdate    | NextStatusDate    | calendar_date | calendar_date |
| Yes      | series tag     | landuse           | LandUse           | text          | text          |
| Yes      | series tag     | landuseshort      | LandUseShort      | text          | text          |
| Yes      | series tag     | projectname       | ProjectName       | text          | text          |
| Yes      | numeric metric | unpaidfees        | UnpaidFees        | number        | number        |
| Yes      | numeric metric | totalfees         | TotalFees         | number        | number        |
| Yes      | numeric metric | bldgarea          | BldgArea          | number        | number        |
| Yes      | numeric metric | constrval         | ConstrVal         | number        | number        |
| Yes      | numeric metric | bondamount        | BondAmount        | number        | number        |
| Yes      | numeric metric | opencomments      | OpenComments      | number        | number        |
| Yes      | series tag     | applicant         | Applicant         | text          | text          |
| Yes      | numeric metric | totalinspections  | TotalInspections  | number        | number        |
| Yes      | series tag     | contractors       | Contractors       | text          | text          |
| Yes      | series tag     | pin               | PIN               | text          | text          |
| Yes      | numeric metric | beds              | Beds              | number        | number        |
| Yes      | numeric metric | baths             | Baths             | number        | number        |
| Yes      | series tag     | heattype          | HeatType          | text          | text          |
| Yes      | numeric metric | secondfloo        | SecondFloo        | number        | number        |
| Yes      | numeric metric | basementar        | BasementAr        | number        | number        |
| Yes      | numeric metric | daysopen          | DaysOpen          | number        | number        |
| Yes      | numeric metric | daysissued        | DaysIssued        | number        | number        |
| Yes      | series tag     | leadagency        | LeadAgency        | text          | text          |
| Yes      | series tag     | exitreason        | ExitReason        | text          | text          |
| Yes      | series tag     | subdivision       | Subdivision       | text          | text          |
| Yes      | series tag     | councildist       | CouncilDist       | text          | text          |
| Yes      | series tag     | zoning            | Zoning            | text          | text          |
| Yes      | series tag     | historicdistrict  | HistoricDistrict  | text          | text          |
```

## Time Field

```ls
Value = issuedate
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = address,filingdate,currentstatusdate,nextstatusdate
```

## Data Commands

```ls
series e:rcm3-fn58 d:2014-03-14T00:00:00.000Z t:isclosed=false t:subdivision=Milneburg t:landuseshort=RSFD t:nextstatus="Inspections Finaled" t:m_s=M t:code=RNVS t:type="Renovation (Structural)" t:currentstatus="Permit Issued" t:division=SP t:pin=38W409403 t:description="Leveling/Shoring of a single family dwelling, adding a deck in the rear, and relocating existing shed as per sketch, renovate bath and kitchen, fixtures, hvac, plumbing, painting and trim." t:leadagency="City of New Orleans" t:applicant="Lynn Tinto" t:owner="Lynn Tinto" t:contractors="Lynn Tinto" t:landuse="Single Family" t:councildist=D t:zoning=RD-2 m:baths=0 m:bondamount=0 m:secondfloo=0 m:totalfees=160 m:daysopen=435 m:daysissued=434 m:beds=0 m:bldgarea=0 m:unpaidfees=0 m:basementar=0 m:opencomments=0 m:totalinspections=4 m:constrval=20000

series e:rcm3-fn58 d:2014-03-14T00:00:00.000Z t:isclosed=false t:subdivision=Milneburg t:landuseshort=RSFD t:nextstatus="Inspections Finaled" t:m_s=M t:code=RNVS t:type="Renovation (Structural)" t:currentstatus="Permit Issued" t:division=SP t:pin=38W409403 t:description="Leveling/Shoring of a single family dwelling, adding a deck in the rear, and relocating existing shed as per sketch, renovate bath and kitchen, fixtures, hvac, plumbing, painting and trim." t:leadagency="City of New Orleans" t:applicant="Lynn Tinto" t:owner="Lynn Tinto" t:contractors="Lynn Tinto" t:landuse="Single Family" t:councildist=D t:zoning=RD-2 m:baths=0 m:bondamount=0 m:secondfloo=0 m:totalfees=160 m:daysopen=437 m:daysissued=436 m:beds=0 m:bldgarea=0 m:unpaidfees=0 m:basementar=0 m:opencomments=0 m:totalinspections=4 m:constrval=20000

series e:rcm3-fn58 d:2014-03-14T00:00:00.000Z t:isclosed=false t:subdivision=Milneburg t:landuseshort=RSFD t:nextstatus="Inspections Finaled" t:m_s=M t:code=RNVS t:type="Renovation (Structural)" t:currentstatus="Permit Issued" t:division=SP t:pin=38W409403 t:description="Leveling/Shoring of a single family dwelling, adding a deck in the rear, and relocating existing shed as per sketch, renovate bath and kitchen, fixtures, hvac, plumbing, painting and trim." t:leadagency="City of New Orleans" t:applicant="Lynn Tinto" t:owner="Lynn Tinto" t:contractors="Lynn Tinto" t:landuse="Single Family" t:councildist=D t:zoning=RD-2 m:baths=0 m:bondamount=0 m:secondfloo=0 m:totalfees=160 m:daysopen=439 m:daysissued=438 m:beds=0 m:bldgarea=0 m:unpaidfees=0 m:basementar=0 m:opencomments=0 m:totalinspections=4 m:constrval=20000
```

## Meta Commands

```ls
metric m:unpaidfees p:float l:UnpaidFees d:"Permit fees that have not been paid yet" t:dataTypeName=number

metric m:totalfees p:float l:TotalFees d:"Total permit fees, in dollars" t:dataTypeName=number

metric m:bldgarea p:integer l:BldgArea d:"Square footage of new construction or addition (if applicable)" t:dataTypeName=number

metric m:constrval p:integer l:ConstrVal d:"Construction value, based on a copy of the construction contract or an itemized estimate in the case of self-performed work" t:dataTypeName=number

metric m:bondamount p:float l:BondAmount d:"Not used by Safety & Permits" t:dataTypeName=number

metric m:opencomments p:integer l:OpenComments d:"Number of permit review comments that have not been resolved or withdrawn" t:dataTypeName=number

metric m:totalinspections p:integer l:TotalInspections d:"Total number of inspections required or performed, both complete and incomplete" t:dataTypeName=number

metric m:beds p:integer l:Beds d:"Optional - number of bedrooms" t:dataTypeName=number

metric m:baths p:float l:Baths d:"Optional - number of bathrooms" t:dataTypeName=number

metric m:secondfloo p:integer l:SecondFloo d:"Not used - area of second floor in square feet" t:dataTypeName=number

metric m:basementar p:integer l:BasementAr d:"Not used - area of basement in square feet" t:dataTypeName=number

metric m:daysopen p:integer l:DaysOpen d:"Number of days from filing the application to closing the permit (whether finaled, voided, withdrawn, or denied)" t:dataTypeName=number

metric m:daysissued p:integer l:DaysIssued d:"Number of days from issuing the permit to closing the permit (whether finaled, voided, withdrawn, or denied)" t:dataTypeName=number

entity e:rcm3-fn58 l:"NOLA Permits" t:url=https://data.nola.gov/api/views/rcm3-fn58

property e:rcm3-fn58 t:meta.view v:id=rcm3-fn58 v:category="Housing, Land Use, and Blight" v:averageRating=0 v:name="NOLA Permits"

property e:rcm3-fn58 t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:rcm3-fn58 t:meta.view.owner v:id=guap-8ddq v:profileImageUrlMedium=/api/users/guap-8ddq/profile_images/THUMB v:profileImageUrlLarge=/api/users/guap-8ddq/profile_images/LARGE v:screenName="City of New Orleans GIS Department" v:profileImageUrlSmall=/api/users/guap-8ddq/profile_images/TINY v:displayName="City of New Orleans GIS Department" v:privilegesDisabled=false

property e:rcm3-fn58 t:meta.view.tableauthor v:id=guap-8ddq v:profileImageUrlMedium=/api/users/guap-8ddq/profile_images/THUMB v:profileImageUrlLarge=/api/users/guap-8ddq/profile_images/LARGE v:screenName="City of New Orleans GIS Department" v:profileImageUrlSmall=/api/users/guap-8ddq/profile_images/TINY v:roleName=administrator v:displayName="City of New Orleans GIS Department" v:privilegesDisabled=false

property e:rcm3-fn58 t:meta.view.metadata.custom_fields.common_core v:Contact_Email=data@nola.gov
```

## Top Records

```ls
| address        | owner      | description                                                                                                                                                                                  | numstring | isclosed | type                    | code | division | m_s | filingdate          | issuedate           | currentstatus | nextstatus          | currentstatusdate   | nextstatusdate      | landuse       | landuseshort | projectname | unpaidfees | totalfees | bldgarea | constrval | bondamount | opencomments | applicant  | totalinspections | contractors | pin       | beds | baths | heattype | secondfloo | basementar | daysopen | daysissued | leadagency          | exitreason | subdivision | councildist | zoning | historicdistrict | 
| ============== | ========== | ============================================================================================================================================================================================ | ========= | ======== | ======================= | ==== | ======== | === | =================== | =================== | ============= | =================== | =================== | =================== | ============= | ============ | =========== | ========== | ========= | ======== | ========= | ========== | ============ | ========== | ================ | =========== | ========= | ==== | ===== | ======== | ========== | ========== | ======== | ========== | =================== | ========== | =========== | =========== | ====== | ================ | 
| 5313 Lafaye St | Lynn Tinto | Leveling/Shoring of a single family dwelling, adding a deck in the rear, and relocating existing shed as per sketch, renovate bath and kitchen, fixtures, hvac, plumbing, painting and trim. |           | false    | Renovation (Structural) | RNVS | SP       | M   | 2014-03-13T00:00:00 | 2014-03-14T00:00:00 | Permit Issued | Inspections Finaled | 2014-03-14T00:00:00 | 2014-11-24T00:00:00 | Single Family | RSFD         |             | 0.0        | 160.0     | 0        | 20000     | 0.0        | 0            | Lynn Tinto | 4                | Lynn Tinto  | 38W409403 | 0    | 0.0   |          | 0          | 0          | 435      | 434        | City of New Orleans |            | Milneburg   | D           | RD-2   |                  | 
| 5313 Lafaye St | Lynn Tinto | Leveling/Shoring of a single family dwelling, adding a deck in the rear, and relocating existing shed as per sketch, renovate bath and kitchen, fixtures, hvac, plumbing, painting and trim. |           | false    | Renovation (Structural) | RNVS | SP       | M   | 2014-03-13T00:00:00 | 2014-03-14T00:00:00 | Permit Issued | Inspections Finaled | 2014-03-14T00:00:00 | 2014-11-24T00:00:00 | Single Family | RSFD         |             | 0.0        | 160.0     | 0        | 20000     | 0.0        | 0            | Lynn Tinto | 4                | Lynn Tinto  | 38W409403 | 0    | 0.0   |          | 0          | 0          | 437      | 436        | City of New Orleans |            | Milneburg   | D           | RD-2   |                  | 
| 5313 Lafaye St | Lynn Tinto | Leveling/Shoring of a single family dwelling, adding a deck in the rear, and relocating existing shed as per sketch, renovate bath and kitchen, fixtures, hvac, plumbing, painting and trim. |           | false    | Renovation (Structural) | RNVS | SP       | M   | 2014-03-13T00:00:00 | 2014-03-14T00:00:00 | Permit Issued | Inspections Finaled | 2014-03-14T00:00:00 | 2014-11-24T00:00:00 | Single Family | RSFD         |             | 0.0        | 160.0     | 0        | 20000     | 0.0        | 0            | Lynn Tinto | 4                | Lynn Tinto  | 38W409403 | 0    | 0.0   |          | 0          | 0          | 439      | 438        | City of New Orleans |            | Milneburg   | D           | RD-2   |                  | 
| 5313 Lafaye St | Lynn Tinto | Leveling/Shoring of a single family dwelling, adding a deck in the rear, and relocating existing shed as per sketch, renovate bath and kitchen, fixtures, hvac, plumbing, painting and trim. |           | false    | Renovation (Structural) | RNVS | SP       | M   | 2014-03-13T00:00:00 | 2014-03-14T00:00:00 | Permit Issued | Inspections Finaled | 2014-03-14T00:00:00 | 2014-11-24T00:00:00 | Single Family | RSFD         |             | 0.0        | 160.0     | 0        | 20000     | 0.0        | 0            | Lynn Tinto | 4                | Lynn Tinto  | 38W409403 | 0    | 0.0   |          | 0          | 0          | 442      | 441        | City of New Orleans |            | Milneburg   | D           | RD-2   |                  | 
| 5313 Lafaye St | Lynn Tinto | Leveling/Shoring of a single family dwelling, adding a deck in the rear, and relocating existing shed as per sketch, renovate bath and kitchen, fixtures, hvac, plumbing, painting and trim. |           | false    | Renovation (Structural) | RNVS | SP       | M   | 2014-03-13T00:00:00 | 2014-03-14T00:00:00 | Permit Issued | Inspections Finaled | 2014-03-14T00:00:00 | 2014-11-24T00:00:00 | Single Family | RSFD         |             | 0.0        | 160.0     | 0        | 20000     | 0.0        | 0            | Lynn Tinto | 4                | Lynn Tinto  | 38W409403 | 0    | 0.0   |          | 0          | 0          | 445      | 444        | City of New Orleans |            | Milneburg   | D           | RD-2   |                  | 
| 5313 Lafaye St | Lynn Tinto | Leveling/Shoring of a single family dwelling, adding a deck in the rear, and relocating existing shed as per sketch, renovate bath and kitchen, fixtures, hvac, plumbing, painting and trim. |           | false    | Renovation (Structural) | RNVS | SP       | M   | 2014-03-13T00:00:00 | 2014-03-14T00:00:00 | Permit Issued | Inspections Finaled | 2014-03-14T00:00:00 | 2014-11-24T00:00:00 | Single Family | RSFD         |             | 0.0        | 160.0     | 0        | 20000     | 0.0        | 0            | Lynn Tinto | 4                | Lynn Tinto  | 38W409403 | 0    | 0.0   |          | 0          | 0          | 447      | 446        | City of New Orleans |            | Milneburg   | D           | RD-2   |                  | 
| 5313 Lafaye St | Lynn Tinto | Leveling/Shoring of a single family dwelling, adding a deck in the rear, and relocating existing shed as per sketch, renovate bath and kitchen, fixtures, hvac, plumbing, painting and trim. |           | false    | Renovation (Structural) | RNVS | SP       | M   | 2014-03-13T00:00:00 | 2014-03-14T00:00:00 | Permit Issued | Inspections Finaled | 2014-03-14T00:00:00 | 2014-11-24T00:00:00 | Single Family | RSFD         |             | 0.0        | 160.0     | 0        | 20000     | 0.0        | 0            | Lynn Tinto | 4                | Lynn Tinto  | 38W409403 | 0    | 0.0   |          | 0          | 0          | 449      | 448        | City of New Orleans |            | Milneburg   | D           | RD-2   |                  | 
| 5313 Lafaye St | Lynn Tinto | Leveling/Shoring of a single family dwelling, adding a deck in the rear, and relocating existing shed as per sketch, renovate bath and kitchen, fixtures, hvac, plumbing, painting and trim. |           | false    | Renovation (Structural) | RNVS | SP       | M   | 2014-03-13T00:00:00 | 2014-03-14T00:00:00 | Permit Issued | Inspections Finaled | 2014-03-14T00:00:00 | 2014-11-24T00:00:00 | Single Family | RSFD         |             | 0.0        | 160.0     | 0        | 20000     | 0.0        | 0            | Lynn Tinto | 4                | Lynn Tinto  | 38W409403 | 0    | 0.0   |          | 0          | 0          | 434      | 433        | City of New Orleans |            | Milneburg   | D           | RD-2   |                  | 
| 5313 Lafaye St | Lynn Tinto | Leveling/Shoring of a single family dwelling, adding a deck in the rear, and relocating existing shed as per sketch, renovate bath and kitchen, fixtures, hvac, plumbing, painting and trim. |           | false    | Renovation (Structural) | RNVS | SP       | M   | 2014-03-13T00:00:00 | 2014-03-14T00:00:00 | Permit Issued | Inspections Finaled | 2014-03-14T00:00:00 | 2014-11-24T00:00:00 | Single Family | RSFD         |             | 0.0        | 160.0     | 0        | 20000     | 0.0        | 0            | Lynn Tinto | 4                | Lynn Tinto  | 38W409403 | 0    | 0.0   |          | 0          | 0          | 451      | 450        | City of New Orleans |            | Milneburg   | D           | RD-2   |                  | 
| 5313 Lafaye St | Lynn Tinto | Leveling/Shoring of a single family dwelling, adding a deck in the rear, and relocating existing shed as per sketch, renovate bath and kitchen, fixtures, hvac, plumbing, painting and trim. |           | false    | Renovation (Structural) | RNVS | SP       | M   | 2014-03-13T00:00:00 | 2014-03-14T00:00:00 | Permit Issued | Inspections Finaled | 2014-03-14T00:00:00 | 2014-11-24T00:00:00 | Single Family | RSFD         |             | 0.0        | 160.0     | 0        | 20000     | 0.0        | 0            | Lynn Tinto | 4                | Lynn Tinto  | 38W409403 | 0    | 0.0   |          | 0          | 0          | 456      | 455        | City of New Orleans |            | Milneburg   | D           | RD-2   |                  | 
```