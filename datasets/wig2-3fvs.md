# HPD Project Element

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/hpd-project-element-c17c1) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/wig2-3fvs) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/wig2-3fvs/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/wig2-3fvs/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | wig2-3fvs |
| Name | HPD Project Element |
| Attribution | Department of Housing Preservation and Development (HPD) |
| Category | Housing & Development |
| Tags | department of housing preservation and development, hpd, project element |
| Created | 2014-02-26T21:30:07Z |
| Publication Date | 2014-08-21T14:11:38Z |

## Description

Information on a Housing Development Project about which HPD is required to report. This includes general project information such as start and completion dates, units, Borrower Legal Entity, general contractor (GC), and prevailing wage information.

## Columns

```ls
| Included | Schema Type    | Field Name                    | Name                          | Data Type     | Render Type   |
| ======== | ============== | ============================= | ============================= | ============= | ============= |
| Yes      | series tag     | project_dwid                  | Project DWID                  | text          | number        |
| Yes      | series tag     | project_id                    | Project ID                    | text          | number        |
| Yes      | series tag     | project_name                  | Project Name                  | text          | text          |
| Yes      | series tag     | program_name                  | Program Name                  | text          | text          |
| Yes      | time           | start_date                    | Start Date                    | calendar_date | calendar_date |
| No       |                | projected_completion_date     | Projected Completion Date     | calendar_date | calendar_date |
| No       |                | actual_completion_date        | Actual Completion Date        | calendar_date | calendar_date |
| Yes      | numeric metric | total_project_units           | Total Project Units           | number        | number        |
| Yes      | numeric metric | commercial_square_footage     | Commercial Square Footage     | number        | number        |
| Yes      | series tag     | borrower_legal_entity_name    | Borrower Legal Entity Name    | text          | text          |
| Yes      | series tag     | general_contractor_name       | General Contractor Name       | text          | text          |
| Yes      | series tag     | is_davisbacon_                | Is DavisBacon?                | text          | text          |
| Yes      | series tag     | is_section_220_nys_labor_law_ | Is Section 220 NYS Labor Law? | text          | text          |
| Yes      | series tag     | final_outcome                 | Final Outcome                 | text          | text          |
```

## Time Field

```ls
Value = start_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = projected_completion_date,actual_completion_date
```

## Data Commands

```ls
series e:wig2-3fvs d:2009-05-08T00:00:00.000Z t:general_contractor_name="Prisma Construction" t:project_name="56 BOND STREET" t:borrower_legal_entity_name="Restored Homes HDFC" t:project_id=38989 t:program_name="Asset Control Area" t:project_dwid=16762 m:total_project_units=1

series e:wig2-3fvs d:2009-05-08T00:00:00.000Z t:general_contractor_name="Poko Builders LLC" t:project_name="664 GEORGIA AVENUE" t:borrower_legal_entity_name="Restored Homes HDFC" t:project_id=38990 t:program_name="Asset Control Area" t:project_dwid=16763 m:total_project_units=2

series e:wig2-3fvs d:2009-05-08T00:00:00.000Z t:general_contractor_name="Horizon Construction" t:project_name="281 MONTAUK AVENUE" t:borrower_legal_entity_name="Restored Homes HDFC" t:project_id=38991 t:program_name="Asset Control Area" t:project_dwid=16764 m:total_project_units=2
```

## Meta Commands

```ls
metric m:total_project_units p:integer l:"Total Project Units" d:"Prior to project completion, this number represents the planned number of dwelling units for the project. At completion, this number represents the actual dwelling units for the project" t:dataTypeName=number

metric m:commercial_square_footage p:integer l:"Commercial Square Footage" d:"Commercial square footage (gross) for the project" t:dataTypeName=number

entity e:wig2-3fvs l:"HPD Project Element" t:attribution="Department of Housing Preservation and Development (HPD)" t:url=https://data.cityofnewyork.us/api/views/wig2-3fvs

property e:wig2-3fvs t:meta.view v:id=wig2-3fvs v:category="Housing & Development" v:averageRating=0 v:name="HPD Project Element" v:attribution="Department of Housing Preservation and Development (HPD)"

property e:wig2-3fvs t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:wig2-3fvs t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| project_dwid | project_id | project_name                  | program_name               | start_date          | projected_completion_date | actual_completion_date | total_project_units | commercial_square_footage | borrower_legal_entity_name                           | general_contractor_name         | is_davisbacon_ | is_section_220_nys_labor_law_ | final_outcome | 
| ============ | ========== | ============================= | ========================== | =================== | ========================= | ====================== | =================== | ========================= | ==================================================== | =============================== | ============== | ============================= | ============= | 
| 16762        | 38989      | 56 BOND STREET                | Asset Control Area         | 2009-05-08T00:00:00 |                           | 2011-04-20T00:00:00    | 1                   |                           | Restored Homes HDFC                                  | Prisma Construction             |                |                               |               | 
| 16763        | 38990      | 664 GEORGIA AVENUE            | Asset Control Area         | 2009-05-08T00:00:00 |                           | 2011-04-26T00:00:00    | 2                   |                           | Restored Homes HDFC                                  | Poko Builders LLC               |                |                               |               | 
| 16764        | 38991      | 281 MONTAUK AVENUE            | Asset Control Area         | 2009-05-08T00:00:00 |                           | 2011-07-12T00:00:00    | 2                   |                           | Restored Homes HDFC                                  | Horizon Construction            |                |                               |               | 
| 16769        | 39155      | 75 & 81 WADSWORTH             | Participation Loan Program | 2009-06-18T00:00:00 |                           | 2011-07-01T00:00:00    | 83                  |                           |                                                      |                                 |                |                               |               | 
| 16772        | 39223      | 733 E 9 ST.                   | Participation Loan Program | 2009-06-25T00:00:00 |                           | 2011-02-03T00:00:00    | 18                  |                           | UHAB HDFC                                            | TMA Contracting Corp.           |                |                               |               | 
| 16773        | 39227      | TMN602                        | TPT - PLP                  | 2009-06-23T00:00:00 |                           | 2010-10-29T00:00:00    | 9                   | 2000                      | West Lenox, LLC                                      | Almo Group Corp.                |                |                               |               | 
| 16774        | 39256      | 1950 Hutchinson River Parkway | Article 8A Loan            | 2009-06-25T00:00:00 |                           | 2011-06-25T00:00:00    | 159                 |                           | Hutchinson Parkway Apartments                        |                                 |                |                               |               | 
| 16802        | 39326      | TMN501                        | TPT - PLP                  | 2009-06-30T00:00:00 |                           | 2011-03-01T00:00:00    | 8                   | 1856                      | Rivington Housing Development Fund Corporation, Inc. | Central Development Corporation |                |                               |               | 
| 16804        | 39343      | TBK708                        | TPT - PLP                  | 2009-06-30T00:00:00 |                           | 2011-03-09T00:00:00    | 36                  | 2150                      | 215 Properties LLC                                   | MDG Design & Construction       |                |                               |               | 
| 16805        | 39349      | 941 Jerome Ave Tenants HDFC   | Article 8A Loan            | 2009-06-30T00:00:00 |                           | 2011-10-30T00:00:00    | 85                  |                           | 941 Jerome Ave Tenants HDFC                          | Ricky & B Brothers              |                |                               |               | 
```