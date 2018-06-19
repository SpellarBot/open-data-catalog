# Agency Codes and Authorized Abbreviations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/agency-codes-and-authorized-abbreviations) |
| Metadata | [Link](https://data.wa.gov/api/views/uie2-nw4g) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/uie2-nw4g/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/uie2-nw4g/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | uie2-nw4g |
| Name | Agency Codes and Authorized Abbreviations |
| Attribution | OFM |
| Category | Procurements and Contracts |
| Tags | agencies, accounting |
| Created | 2016-05-18T22:54:28Z |
| Publication Date | 2016-08-11T15:49:43Z |

## Description

Agency Codes from SAAM Used for the identification of state agencies. Refer to Section 75.20 for the statewide agency codes and authorized abbreviations.

## Columns

```ls
| Included | Schema Type    | Field Name    | Name          | Data Type | Render Type |
| ======== | ============== | ============= | ============= | ========= | =========== |
| No       | time           | :updated_at   | updated_at    | meta_data | meta_data   |
| Yes      | series tag     | agency_number | AGENCY NUMBER | text      | number      |
| Yes      | series tag     | agency_title  | AGENCY TITLE  | text      | text        |
| Yes      | series tag     | abbreviation  | Abbreviation  | text      | text        |
| Yes      | numeric metric | expose        | Expose        | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:uie2-nw4g d:2016-05-18T15:54:31.000Z t:agency_title="State Revenue for Distribution (SRD)" t:agency_number=10 t:abbreviation=SRD m:expose=1

series e:uie2-nw4g d:2016-05-18T15:54:31.000Z t:agency_title="Federal Revenue for Distribution (FRD)" t:agency_number=50 t:abbreviation=FRD m:expose=1

series e:uie2-nw4g d:2016-05-18T15:54:31.000Z t:agency_title="Bond Retirement and Interest (BRI)" t:agency_number=100 t:abbreviation=BRI m:expose=1
```

## Meta Commands

```ls
metric m:expose p:integer l:Expose d:"1 indicates an operating agency; 0 indicates an accounting code" t:dataTypeName=number

entity e:uie2-nw4g l:"Agency Codes and Authorized Abbreviations" t:attribution=OFM t:url=https://data.wa.gov/api/views/uie2-nw4g

property e:uie2-nw4g t:meta.view v:id=uie2-nw4g v:category="Procurements and Contracts" v:attributionLink=http://www.ofm.wa.gov/policy/75.20.htm v:averageRating=0 v:name="Agency Codes and Authorized Abbreviations" v:attribution=OFM

property e:uie2-nw4g t:meta.view.owner v:id=h2ue-vnnt v:profileImageUrlMedium=/api/users/h2ue-vnnt/profile_images/THUMB v:profileImageUrlLarge=/api/users/h2ue-vnnt/profile_images/LARGE v:screenName="OCIO-Will Saunders" v:profileImageUrlSmall=/api/users/h2ue-vnnt/profile_images/TINY v:displayName="OCIO-Will Saunders"

property e:uie2-nw4g t:meta.view.tableauthor v:id=h2ue-vnnt v:profileImageUrlMedium=/api/users/h2ue-vnnt/profile_images/THUMB v:profileImageUrlLarge=/api/users/h2ue-vnnt/profile_images/LARGE v:screenName="OCIO-Will Saunders" v:profileImageUrlSmall=/api/users/h2ue-vnnt/profile_images/TINY v:roleName=publisher v:displayName="OCIO-Will Saunders"
```

## Top Records

```ls
| :updated_at | agency_number | agency_title                                                       | abbreviation | expose | 
| =========== | ============= | ================================================================== | ============ | ====== | 
| 1463586871  | 10            | State Revenue for Distribution (SRD)                               | SRD          | 1      | 
| 1463586871  | 50            | Federal Revenue for Distribution (FRD)                             | FRD          | 1      | 
| 1463586871  | 100           | Bond Retirement and Interest (BRI)                                 | BRI          | 1      | 
| 1463586871  | 110           | House of Representatives (REP)                                     | REP          | 1      | 
| 1463586871  | 120           | Senate (SEN)                                                       | SEN          | 1      | 
| 1463586871  | 130           | Joint Transportation Committee (JTC)                               | JTC          | 1      | 
| 1463586871  | 140           | Joint Legislative Audit and Review Committee (JLARC)               | ARC          | 1      | 
| 1463586871  | 200           | Legislative Evaluation and Accountability Program Committee (LEAP) | EAP          | 1      | 
| 1463586871  | 350           | Office of the State Actuary (OSA)                                  | OSA          | 1      | 
| 1463586871  | 370           | Office of Legislative Support Services (LSS)                       | LSS          | 1      | 
```