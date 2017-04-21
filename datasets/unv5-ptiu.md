# Contracts: ESD: Lane ESD: Fiscal Year 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/contracts-esd-lane-esd-fiscal-year-2013-279e7) |
| Metadata | [Link](https://data.oregon.gov/api/views/unv5-ptiu) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/unv5-ptiu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/unv5-ptiu/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | unv5-ptiu |
| Name | Contracts: ESD: Lane ESD: Fiscal Year 2013 |
| Category | Administrative |
| Tags | esd, contracts, lane esd, lane esd contracts |
| Created | 2014-03-12T21:28:52Z |
| Publication Date | 2014-03-12T21:34:21Z |

## Columns

```ls
| Included | Schema Type    | Field Name                             | Name                                   | Data Type | Render Type |
| ======== | ============== | ====================================== | ====================================== | ========= | =========== |
| Yes      | numeric metric | esd                                    | ESD#                                   | number    | number      |
| Yes      | series tag     | esd_name                               | ESD Name                               | text      | text        |
| Yes      | series tag     | award                                  | Award #                                | text      | text        |
| Yes      | series tag     | award_title                            | Award Title                            | text      | text        |
| Yes      | series tag     | award_type                             | Award Type                             | text      | text        |
| Yes      | series tag     | type_of_contract_subcontract           | Type of Contract/ Subcontract          | text      | text        |
| Yes      | series tag     | contractor_information                 | Contractor Information                 | text      | text        |
| No       |                | contractor_address                     | Contractor Address                     | text      | text        |
| Yes      | series tag     | contractor_city                        | Contractor City                        | text      | text        |
| Yes      | series tag     | contractor_state                       | Contractor State                       | text      | text        |
| Yes      | series tag     | contractor_zip                         | Contractor Zip                         | text      | number      |
| No       |                | original_start_amended_expiration_date | Original Start/Amended/Expiration Date | text      | text        |
| Yes      | numeric metric | original_awardvalue                    | Original AwardValue                    | number    | number      |
| Yes      | numeric metric | amendmentvalue                         | AmendmentValue                         | number    | number      |
| Yes      | numeric metric | total_awardvalue                       | Total AwardValue                       | number    | number      |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = contractor_address,original_start_amended_expiration_date
```

## Data Commands

```ls
series e:unv5-ptiu d:2013-01-01T00:00:00.000Z t:esd_name="LANE EDUCATION SERVICE DISTRICT" t:contractor_state=OR t:type_of_contract_subcontract=Subcontract t:award=- t:contractor_city=Eugene t:award_type=Sub-Contract t:award_title="Regional services - HI/VI/OI" t:contractor_information="Eugene School District" t:contractor_zip=97402 m:original_awardvalue=1243116 m:amendmentvalue=0 m:esd=2064 m:total_awardvalue=1243116

series e:unv5-ptiu d:2013-01-01T00:00:00.000Z t:esd_name="LANE EDUCATION SERVICE DISTRICT" t:contractor_state=OR t:type_of_contract_subcontract=Sub-Contract t:award=8597 t:contractor_city=Eugene t:award_type=Sub-Contract t:award_title="EI/ECSE sub-contract" t:contractor_information="University of Oregon-EC CARES" t:contractor_zip=97403 m:original_awardvalue=8551701 m:amendmentvalue=0 m:esd=2064 m:total_awardvalue=8551701

series e:unv5-ptiu d:2013-01-01T00:00:00.000Z t:esd_name="LANE EDUCATION SERVICE DISTRICT" t:contractor_state=OR t:type_of_contract_subcontract=Contract t:award=- t:contractor_city="Junction City" t:award_type="Price Agreement" t:award_title="Nurse services" t:contractor_information="Junction City School District" t:contractor_zip=97448 m:original_awardvalue=448 m:amendmentvalue=0 m:esd=2064 m:total_awardvalue=448
```

## Meta Commands

```ls
metric m:esd p:integer l:ESD# t:dataTypeName=number

metric m:original_awardvalue p:integer l:"Original AwardValue" t:dataTypeName=number

metric m:amendmentvalue p:integer l:AmendmentValue t:dataTypeName=number

metric m:total_awardvalue p:integer l:"Total AwardValue" t:dataTypeName=number

entity e:unv5-ptiu l:"Contracts: ESD: Lane ESD: Fiscal Year 2013" t:url=https://data.oregon.gov/api/views/unv5-ptiu

property e:unv5-ptiu t:meta.view v:id=unv5-ptiu v:category=Administrative v:averageRating=0 v:name="Contracts: ESD: Lane ESD: Fiscal Year 2013"

property e:unv5-ptiu t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:unv5-ptiu t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| esd  | esd_name                        | award | award_title                   | award_type      | type_of_contract_subcontract | contractor_information        | contractor_address           | contractor_city | contractor_state | contractor_zip | original_start_amended_expiration_date | original_awardvalue | amendmentvalue | total_awardvalue | 
| ==== | =============================== | ===== | ============================= | =============== | ============================ | ============================= | ============================ | =============== | ================ | ============== | ====================================== | =================== | ============== | ================ | 
| 2064 | LANE EDUCATION SERVICE DISTRICT | -     | Regional services - HI/VI/OI  | Sub-Contract    | Subcontract                  | Eugene School District        | 200 N Monroe Street          | Eugene          | OR               | 97402          | 07/01/12 - / / - 06/30/13              | 1243116             | 0              | 1243116          | 
| 2064 | LANE EDUCATION SERVICE DISTRICT | 8597  | EI/ECSE sub-contract          | Sub-Contract    | Sub-Contract                 | University of Oregon-EC CARES | PO Box 3237                  | Eugene          | OR               | 97403          | 07/01/12 - / / - 06/30/13              | 8551701             | 0              | 8551701          | 
| 2064 | LANE EDUCATION SERVICE DISTRICT | -     | Nurse services                | Price Agreement | Contract                     | Junction City School District | 325 Maple Street             | Junction City   | OR               | 97448          | 07/01/12 - / / - 06/30/13              | 448                 | 0              | 448              | 
| 2064 | LANE EDUCATION SERVICE DISTRICT | -     | Nurse services                | Price Agreement | Contract                     | Bethel School District        | 4640 Barger Drive            | Eugene          | OR               | 97402          | 07/01/12 - / / - 06/30/13              | 448                 | 0              | 448              | 
| 2064 | LANE EDUCATION SERVICE DISTRICT | -     | Financial audit               | Price Agreement | Contract                     | Pauly, Rogers and Co., P.C.   | 12700 S.W. 72ND Avenue       | Tigard          | OR               | 97223          | 07/01/12 - / / - 06/30/13              | 35000               | 0              | 35000            | 
| 2064 | LANE EDUCATION SERVICE DISTRICT | -     | Financial software            | Price Agreement | Contract                     | Sungard Pentamation           | 2290 Collection Center Drive | Chicago         | IL               | 60693          | 07/01/12 - / / - 06/30/13              | 19776               | 0              | 19776            | 
| 2064 | LANE EDUCATION SERVICE DISTRICT | -     | Physical/Occupational therapy | Price Agreement | Contract                     | Eugene School District        | 200 N Monroe Street          | Eugene          | OR               | 97402          | 07/01/12 - / / - 06/30/13              | 353238              | 0              | 353238           | 
| 2064 | LANE EDUCATION SERVICE DISTRICT | -     | Data warehousing              | Price Agreement | Contract                     | Willamette ESD                | 2611 Pringle Road NE         | Salem           | OR               | 97302          | 07/01/12 - / / - 06/30/13              | 153600              | 0              | 153600           | 
| 2064 | LANE EDUCATION SERVICE DISTRICT | -     | Learn 360 subscription        | Price Agreement | Contract                     | NW Regional ESD               | 5825 Northeast Ray Circle    | Hillsboro       | OR               | 97124          | 07/01/12 - / / - 06/30/13              | 10086               | 0              | 10086            | 
| 2064 | LANE EDUCATION SERVICE DISTRICT | -     | Data circuit                  | Price Agreement | Contract                     | City of Cottage Grove         | 400 East Main Street         | Cottage Grove   | OR               | 97424          | 07/01/12 - / / - 06/30/13              | 14400               | 0              | 14400            | 
```