# City of Champaign Permit Data (Updated 12-04-12)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/city-of-champaign-permit-data-updated-12-04-12-8f885) |
| Metadata | [Link](https://data.illinois.gov/api/views/m3fm-fpwu) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/m3fm-fpwu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/m3fm-fpwu/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | m3fm-fpwu |
| Name | City of Champaign Permit Data (Updated 12-04-12) |
| Attribution | City of Champaign |
| Category | Municipality |
| Tags | permit, construction, champaign |
| Created | 2012-12-04T19:53:57Z |
| Publication Date | 2012-12-04T21:48:50Z |

## Columns

```ls
| Included | Schema Type    | Field Name                | Name                      | Data Type     | Render Type   |
| ======== | ============== | ========================= | ========================= | ============= | ============= |
| Yes      | series tag     | prefix                    | Prefix                    | text          | text          |
| Yes      | numeric metric | yrmo                      | YRMO                      | number        | number        |
| Yes      | series tag     | seq_number                | Seq Number                | text          | number        |
| Yes      | series tag     | permit_number             | Permit Number             | text          | text          |
| Yes      | series tag     | application_number        | Application Number        | text          | text          |
| Yes      | series tag     | plancheck_number          | Plancheck Number          | text          | text          |
| Yes      | series tag     | reference_number          | Reference Number          | text          | text          |
| Yes      | time           | applied                   | Applied                   | calendar_date | calendar_date |
| Yes      | series tag     | applied_by                | Applied By                | text          | text          |
| No       |                | approved                  | Approved                  | calendar_date | calendar_date |
| Yes      | series tag     | approved_by               | Approved By               | text          | text          |
| No       |                | issued                    | Issued                    | calendar_date | calendar_date |
| Yes      | series tag     | issued_by                 | Issued By                 | text          | text          |
| No       |                | finaled                   | Finaled                   | calendar_date | calendar_date |
| Yes      | series tag     | finaled_by                | Finaled By                | text          | text          |
| Yes      | series tag     | expired                   | Expired                   | text          | text          |
| Yes      | series tag     | expired_by                | Expired By                | text          | text          |
| Yes      | series tag     | valid_for                 | Valid For                 | text          | text          |
| Yes      | series tag     | parent_project_number     | Parent Project Number     | text          | text          |
| Yes      | series tag     | parent_permit_number      | Parent Permit Number      | text          | text          |
| Yes      | series tag     | permit_type               | Permit Type               | text          | text          |
| Yes      | series tag     | permit_subtype            | Permit Subtype            | text          | text          |
| Yes      | series tag     | status                    | Status                    | text          | text          |
| Yes      | series tag     | occupancy_type            | Occupancy Type            | text          | text          |
| Yes      | series tag     | group_code                | Group Code                | text          | text          |
| Yes      | series tag     | zoning_code_1             | Zoning Code 1             | text          | text          |
| Yes      | series tag     | zoning_code_2             | Zoning Code 2             | text          | text          |
| Yes      | series tag     | construction_type         | Construction Type         | text          | text          |
| Yes      | series tag     | site_lot_no               | Site Lot No               | text          | text          |
| Yes      | numeric metric | site_block                | Site Block                | number        | number        |
| Yes      | series tag     | site_tract                | Site Tract                | text          | text          |
| Yes      | series tag     | site_subdivision          | Site Subdivision          | text          | text          |
| Yes      | series tag     | site_description          | Site Description          | text          | text          |
| Yes      | series tag     | tax_rate_area             | Tax Rate Area             | text          | text          |
| Yes      | series tag     | school                    | School                    | text          | text          |
| Yes      | series tag     | census                    | Census                    | text          | text          |
| Yes      | series tag     | fw_dodge                  | FW Dodge                  | text          | text          |
| Yes      | series tag     | site_apn                  | Site APN                  | text          | text          |
| Yes      | series tag     | site_number               | Site Number               | text          | text          |
| Yes      | series tag     | site_street_id            | Site Street ID            | text          | number        |
| Yes      | series tag     | site_street_name          | Site Street Name          | text          | text          |
| Yes      | series tag     | site_unit_no              | Site Unit No              | text          | text          |
| Yes      | series tag     | site_city                 | Site City                 | text          | text          |
| Yes      | series tag     | site_state                | Site State                | text          | text          |
| Yes      | series tag     | site_zip                  | Site Zip                  | text          | number        |
| Yes      | series tag     | site_st_no                | Site ST No                | text          | text          |
| Yes      | series tag     | location_description      | Location Description      | text          | text          |
| Yes      | series tag     | description               | Description               | text          | text          |
| Yes      | series tag     | notes                     | Notes                     | text          | text          |
| Yes      | numeric metric | lot_square_footage        | Lot Square Footage        | number        | number        |
| Yes      | numeric metric | building_square_footage   | Building Square Footage   | number        | number        |
| Yes      | numeric metric | building_2_square_footage | Building 2 Square Footage | number        | number        |
| Yes      | numeric metric | garage_square_footage     | Garage Square Footage     | number        | number        |
| Yes      | numeric metric | garage_2_square_footage   | Garage 2 Square Footage   | number        | number        |
| Yes      | numeric metric | porch_square_footage      | Porch Square Footage      | number        | number        |
| Yes      | numeric metric | porch_2_square_footage    | Porch 2 Square Footage    | number        | number        |
| Yes      | numeric metric | height                    | Height                    | number        | number        |
| Yes      | numeric metric | number_of_stories         | Number of Stories         | number        | number        |
| Yes      | numeric metric | number_of_units           | Number of Units           | number        | number        |
| Yes      | numeric metric | number_of_buildings       | Number of Buildings       | number        | number        |
| Yes      | numeric metric | job_value                 | Job Value                 | money         | money         |
| Yes      | numeric metric | fees_charged              | Fees Charged              | money         | money         |
| Yes      | numeric metric | fee_adjustments           | Fee Adjustments           | money         | money         |
| Yes      | numeric metric | fees_paid                 | Fees Paid                 | money         | money         |
| Yes      | numeric metric | balance_due               | Balance Due               | money         | money         |
| No       |                | other_date_1              | Other Date 1              | text          | text          |
| Yes      | series tag     | other_by1                 | Other_By1                 | text          | text          |
| Yes      | series tag     | owner_name                | Owner Name                | text          | text          |
| Yes      | series tag     | applicant_name            | Applicant Name            | text          | text          |
| Yes      | series tag     | contractor_name           | Contractor Name           | text          | text          |
| Yes      | series tag     | record_id                 | Record ID                 | text          | text          |
| Yes      | series tag     | lock_id                   | Lock ID                   | text          | text          |
| Yes      | series tag     | location_record_id        | Location Record ID        | text          | text          |
| Yes      | numeric metric | pin                       | PIN                       | number        | number        |
| Yes      | series tag     | deposit_type              | Deposit Type              | text          | text          |
| Yes      | series tag     | historical_apn            | Historical APN            | text          | text          |
| Yes      | series tag     | site_alternate_il         | Site Alternate IL         | text          | text          |
| Yes      | series tag     | site_geotype              | Site Geotype              | text          | text          |
```

## Time Field

```ls
Value = applied
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = approved,issued,finaled,other_date_1
```

## Data Commands

```ls
series e:m3fm-fpwu d:2006-08-18T00:00:00.000Z t:site_zip=61820 t:owner_name="SALVATION ARMY" t:applied_by=VPA t:applicant_name="Getz Fire Equipment" t:issued_by=VPA t:record_id=CRW_00612712 t:seq_number=3766 t:location_record_id=KR:512021404000034 t:finaled_by=CRL t:contractor_name="Getz Fire Equipment" t:site_tract=CI t:description=SUPPRESSION t:permit_subtype=Alteration t:site_street_id=0 t:site_city=CHAMPAIGN t:permit_type=HVAC t:status=FINALED t:site_state=IL t:site_number=2212 t:permit_number=BS06-3766 t:site_street_name="N MARKET" t:approved_by=VPA t:site_apn=462106101008 t:prefix=BS t:parent_permit_number=BS06-1438 m:building_square_footage=22465 m:lot_square_footage=0 m:fee_adjustments=0 m:balance_due=0 m:porch_2_square_footage=0 m:building_2_square_footage=0 m:job_value=300 m:height=0 m:pin=0 m:fees_charged=45 m:fees_paid=45 m:number_of_units=2 m:garage_2_square_footage=0 m:garage_square_footage=0 m:porch_square_footage=0 m:number_of_buildings=0 m:number_of_stories=0 m:yrmo=6

series e:m3fm-fpwu d:2006-06-23T00:00:00.000Z t:site_city=CHAMPAIGN t:permit_type=PLUMBING t:owner_name="MACFARLANE, ROBERT F" t:site_state=IL t:status=FINALED t:applied_by=VPA t:site_number=1017 t:applicant_name="Clark Plbg. & Htg." t:record_id=CRW_00623666 t:issued_by=VPA t:seq_number=2853 t:permit_number=BS06-2853 t:site_street_name="LINCOLNSHIRE DR" t:approved_by=VPA t:location_record_id=CRW_00810880 t:contractor_name="Clark Plbg. & Htg." t:site_apn=452023226001 t:finaled_by=MPE t:description="BACKFLOW PREVENTOR" t:prefix=BS t:permit_subtype=New t:site_street_id=0 m:building_square_footage=0 m:lot_square_footage=0 m:fee_adjustments=0 m:balance_due=0 m:porch_2_square_footage=0 m:building_2_square_footage=0 m:job_value=0 m:height=0 m:pin=0 m:fees_charged=35 m:fees_paid=35 m:number_of_units=0 m:garage_2_square_footage=0 m:garage_square_footage=0 m:porch_square_footage=0 m:number_of_buildings=0 m:number_of_stories=0 m:yrmo=6

series e:m3fm-fpwu d:2006-03-31T00:00:00.000Z t:site_city=CHAMPAIGN t:permit_type=GRADING t:site_zip=61822 t:expired=00:00.0 t:expired_by=LCL t:owner_name="RAYCORP, INC" t:site_state=IL t:status=ISSUED t:applied_by=VP t:site_number=2714-2716 t:applicant_name="Architectural Spectrum" t:record_id=CRW_00622410 t:issued_by=LCL t:seq_number=891 t:permit_number=EN06-0891 t:site_street_name=MADELYN t:approved_by=VP t:description=G&D t:prefix=EN t:permit_subtype=New t:parent_permit_number=BS06-1264 t:site_street_id=0 m:building_square_footage=0 m:lot_square_footage=0 m:fee_adjustments=0 m:balance_due=0 m:porch_2_square_footage=0 m:building_2_square_footage=0 m:job_value=0 m:height=0 m:pin=0 m:fees_charged=0 m:fees_paid=0 m:number_of_units=0 m:garage_2_square_footage=0 m:garage_square_footage=0 m:porch_square_footage=0 m:number_of_buildings=0 m:number_of_stories=0 m:yrmo=6
```

## Meta Commands

```ls
metric m:yrmo p:integer l:YRMO t:dataTypeName=number

metric m:site_block p:integer l:"Site Block" t:dataTypeName=number

metric m:lot_square_footage p:integer l:"Lot Square Footage" t:dataTypeName=number

metric m:building_square_footage p:integer l:"Building Square Footage" t:dataTypeName=number

metric m:building_2_square_footage p:integer l:"Building 2 Square Footage" t:dataTypeName=number

metric m:garage_square_footage p:integer l:"Garage Square Footage" t:dataTypeName=number

metric m:garage_2_square_footage p:integer l:"Garage 2 Square Footage" t:dataTypeName=number

metric m:porch_square_footage p:integer l:"Porch Square Footage" t:dataTypeName=number

metric m:porch_2_square_footage p:integer l:"Porch 2 Square Footage" t:dataTypeName=number

metric m:height p:integer l:Height t:dataTypeName=number

metric m:number_of_stories p:double l:"Number of Stories" t:dataTypeName=number

metric m:number_of_units p:integer l:"Number of Units" t:dataTypeName=number

metric m:number_of_buildings p:integer l:"Number of Buildings" t:dataTypeName=number

metric m:job_value p:double l:"Job Value" t:dataTypeName=money

metric m:fees_charged p:double l:"Fees Charged" t:dataTypeName=money

metric m:fee_adjustments p:integer l:"Fee Adjustments" t:dataTypeName=money

metric m:fees_paid p:double l:"Fees Paid" t:dataTypeName=money

metric m:balance_due p:double l:"Balance Due" t:dataTypeName=money

metric m:pin p:integer l:PIN t:dataTypeName=number

entity e:m3fm-fpwu l:"City of Champaign Permit Data (Updated 12-04-12)" t:attribution="City of Champaign" t:url=https://data.illinois.gov/api/views/m3fm-fpwu

property e:m3fm-fpwu t:meta.view v:id=m3fm-fpwu v:category=Municipality v:averageRating=0 v:name="City of Champaign Permit Data (Updated 12-04-12)" v:attribution="City of Champaign"

property e:m3fm-fpwu t:meta.view.license v:name="Public Domain"

property e:m3fm-fpwu t:meta.view.owner v:id=v5dz-wzd9 v:screenName="Patrick East" v:displayName="Patrick East"

property e:m3fm-fpwu t:meta.view.tableauthor v:id=v5dz-wzd9 v:screenName="Patrick East" v:displayName="Patrick East"
```

## Top Records

```ls
| prefix | yrmo | seq_number | permit_number | application_number | plancheck_number | reference_number | applied             | applied_by | approved            | approved_by | issued              | issued_by | finaled             | finaled_by | expired | expired_by | valid_for | parent_project_number | parent_permit_number | permit_type       | permit_subtype | status  | occupancy_type | group_code | zoning_code_1 | zoning_code_2 | construction_type | site_lot_no | site_block | site_tract | site_subdivision                 | site_description | tax_rate_area | school | census | fw_dodge | site_apn     | site_number | site_street_id | site_street_name   | site_unit_no | site_city | site_state | site_zip | site_st_no | location_description | description                  | notes                                                                                                                                                                                                                | lot_square_footage | building_square_footage | building_2_square_footage | garage_square_footage | garage_2_square_footage | porch_square_footage | porch_2_square_footage | height | number_of_stories | number_of_units | number_of_buildings | job_value | fees_charged | fee_adjustments | fees_paid | balance_due | other_date_1 | other_by1 | owner_name               | applicant_name                 | contractor_name                | record_id            | lock_id | location_record_id | pin | deposit_type | historical_apn | site_alternate_il | site_geotype | 
| ====== | ==== | ========== | ============= | ================== | ================ | ================ | =================== | ========== | =================== | =========== | =================== | ========= | =================== | ========== | ======= | ========== | ========= | ===================== | ==================== | ================= | ============== | ======= | ============== | ========== | ============= | ============= | ================= | =========== | ========== | ========== | ================================ | ================ | ============= | ====== | ====== | ======== | ============ | =========== | ============== | ================== | ============ | ========= | ========== | ======== | ========== | ==================== | ============================ | ==================================================================================================================================================================================================================== | ================== | ======================= | ========================= | ===================== | ======================= | ==================== | ====================== | ====== | ================= | =============== | =================== | ========= | ============ | =============== | ========= | =========== | ============ | ========= | ======================== | ============================== | ============================== | ==================== | ======= | ================== | === | ============ | ============== | ================= | ============ | 
| BS     | 6    | 3766       | BS06-3766     |                    |                  |                  | 2006-08-18T00:00:00 | VPA        | 2006-08-18T00:00:00 | VPA         | 2006-08-18T00:00:00 | VPA       | 2006-08-29T00:00:00 | CRL        |         |            |           |                       | BS06-1438            | HVAC              | Alteration     | FINALED |                |            |               |               |                   |             |            | CI         |                                  |                  |               |        |        |          | 462106101008 | 2212        | 0              | N MARKET           |              | CHAMPAIGN | IL         | 61820    |            |                      | SUPPRESSION                  |                                                                                                                                                                                                                      | 0                  | 22465                   | 0                         | 0                     | 0                       | 0                    | 0                      | 0      | 0                 | 2               | 0                   | 300       | 45           | 0               | 45        | 0           |              |           | SALVATION ARMY           | Getz Fire Equipment            | Getz Fire Equipment            | CRW_00612712         |         | KR:512021404000034 | 0   |              |                |                   |              | 
| BS     | 6    | 2853       | BS06-2853     |                    |                  |                  | 2006-06-23T00:00:00 | VPA        | 2006-06-23T00:00:00 | VPA         | 2006-06-23T00:00:00 | VPA       | 2006-07-03T00:00:00 | MPE        |         |            |           |                       |                      | PLUMBING          | New            | FINALED |                |            |               |               |                   |             |            |            |                                  |                  |               |        |        |          | 452023226001 | 1017        | 0              | LINCOLNSHIRE DR    |              | CHAMPAIGN | IL         |          |            |                      | BACKFLOW PREVENTOR           |                                                                                                                                                                                                                      | 0                  | 0                       | 0                         | 0                     | 0                       | 0                    | 0                      | 0      | 0                 | 0               | 0                   | 0         | 35           | 0               | 35        | 0           |              |           | MACFARLANE, ROBERT F     | Clark Plbg. & Htg.             | Clark Plbg. & Htg.             | CRW_00623666         |         | CRW_00810880       | 0   |              |                |                   |              | 
| EN     | 6    | 891        | EN06-0891     |                    |                  |                  | 2006-03-31T00:00:00 | VP         | 2006-03-31T00:00:00 | VP          | 2009-01-05T00:00:00 | LCL       |                     |            | 00:00.0 | LCL        |           |                       | BS06-1264            | GRADING           | New            | ISSUED  |                |            |               |               |                   |             |            |            |                                  |                  |               |        |        |          |              | 2714-2716   | 0              | MADELYN            |              | CHAMPAIGN | IL         | 61822    |            |                      | G&D                          |                                                                                                                                                                                                                      | 0                  | 0                       | 0                         | 0                     | 0                       | 0                    | 0                      | 0      | 0                 | 0               | 0                   | 0         | 0            | 0               | 0         | 0           |              |           | RAYCORP, INC             | Architectural Spectrum         |                                | CRW_00622410         |         |                    | 0   |              |                |                   |              | 
| EN     | 4    | 1712       | EN04-1712     |                    |                  |                  | 2004-12-30T00:00:00 | VP         | 2004-12-30T00:00:00 | VP          | 2005-01-04T00:00:00 | VPA       |                     |            | 00:00.0 | VPA        |           |                       | BS04-3412            | GRADING           | New            | ISSUED  |                |            |               |               |                   |             |            | MF3        |                                  |                  |               |        |        |          |              | 306         | 0              | E GREGORY          |              | CHAMPAIGN | IL         | 61820    |            |                      | G&D                          |                                                                                                                                                                                                                      | 0                  | 0                       | 0                         | 0                     | 0                       | 0                    | 0                      | 0      | 0                 | 0               | 0                   | 0         | 0            | 0               | 0         | 0           |              |           | GREGORY STREET, LLC      | JN RASSI CONSTRUCTION MANAGEME | JN RASSI CONSTRUCTION MANAGEME | CRW_00624518         |         |                    | 0   | FULL         |                |                   |              | 
| BS     | 11   | 905        | BS11-0905     |                    |                  |                  | 2011-05-12T00:00:00 | VPA        | 2011-05-12T00:00:00 | VPA         | 2011-05-12T00:00:00 | VPA       | 2011-05-13T00:00:00 | JFL        |         |            |           |                       |                      | ELECTRICAL        | REPAIR/REPLACE | FINALED |                |            |               |               |                   | 29          |            |            |                                  |                  |               |        |        |          | 412001380006 | 413         |                | FAIRVIEW           |              | CHAMPAIGN | IL         | 61820    |            |                      | Storm damage to meter socket |                                                                                                                                                                                                                      |                    |                         |                           |                       |                         |                      |                        |        |                   |                 |                     | 595       | 45           |                 | 45        | 0           |              |           | HELEN WILLIAMS           | Remco Electrical Corp.         | Remco Electrical Corp.         | VPA:1105121059101011 |         | CRW_00795878       |     |              |                |                   |              | 
| BS     | 5    | 3129       | BS05-3129     |                    |                  |                  | 2005-08-01T00:00:00 | VPA        | 2005-08-03T00:00:00 | SRD         | 2005-08-03T00:00:00 | VPA       |                     |            | 00:00.0 | SRD        |           |                       |                      | BLDG 1F2F ADD ALT | Addition       | EXPIRED |                |            |               |               |                   |             |            | SF1        |                                  |                  |               |        |        |          | 442015382003 | 1502        | 0              | WESTFIELD          |              | CHAMPAIGN | IL         |          |            |                      | SFD                          |                                                                                                                                                                                                                      | 0                  | 440                     | 0                         | 0                     | 0                       | 0                    | 0                      | 0      | 1                 | 1               | 0                   | 62900     | 240          | 0               | 240       | 0           |              |           | GILLILAND, CLYDE & CHRIS | Total Home Improvements        | Total Home Improvements        | CRW_00621744         |         | CRW_00807312       | 0   |              |                |                   |              | 
| BS     | 5    | 738        | BS05-0738     |                    |                  |                  | 2005-03-21T00:00:00 | VPA        | 2005-03-21T00:00:00 | VPA         | 2005-03-21T00:00:00 | VPA       | 2005-07-29T00:00:00 | PJA        |         |            |           |                       | BS04-3585            | PLUMBING          | Alteration     | FINALED |                |            |               |               |                   |             | 9          | CB         | Railroad Add, Sub of N 1/2 Blk 9 | City Building    |               |        |        |          | 422012431001 | 102         | 0              | N NEIL             |              | CHAMPAIGN | IL         | 61820    |            |                      | (2ND & 3RD FLOORS)           | NO PERMIT FEES - CITY BUILDING ( FEE WAIVED = $90)                                                                                                                                                                   | 0                  | 0                       | 0                         | 0                     | 0                       | 0                    | 0                      | 0      | 0                 | 0               | 0                   | 0         | 0            | 0               | 0         | 0           |              |           | CITY, OF CHAMPAIGN       | A & R Mechanical               | A & R Mechanical               | CRW_00626250         |         | CRW_00698304       | 0   | FULL         |                |                   |              | 
| BS     | 7    | 738        | BS07-0738     |                    |                  |                  | 2007-03-23T00:00:00 | LCL        | 2007-03-23T00:00:00 | LCL         | 2007-03-23T00:00:00 | LCL       | 2007-07-03T00:00:00 | CRL        |         |            |           |                       | BS06-4416            | HVAC              | New            | FINALED |                |            |               |               |                   | 3006        |            | SF2        | ASHLAND PARK                     |                  |               |        |        |          |              | 502         | 0              | LAUTERBUR LN       |              | CHAMPAIGN | IL         | 61822    |            |                      |                              | PERMIT FEE WAIVED PER ANNEXATION AGREEMENT. CB#2004-080                                                                                                                                                              | 0                  | 1811                    | 0                         | 0                     | 0                       | 0                    | 0                      | 0      | 2                 | 1               | 0                   | 4150      | 0            | 0               | 0         | 0           |              |           | The Atkins Group         | Lanz Htg. & Cooling            | Lanz Htg. & Cooling            | CRW_00628471         |         |                    | 0   |              |                |                   |              | 
| BS     | 7    | 2337       | BS07-2337     |                    |                  |                  | 2007-07-30T00:00:00 | VPA        | 2007-08-09T00:00:00 | HLE         | 2007-08-15T00:00:00 | LCL       | 2010-07-01T00:00:00 | GJR        |         |            |           |                       |                      | BLDG C NEW ADD    | New            | FINALED |                |            |               |               |                   | 3           |            | MF1        | WELLINGTON PLACE                 |                  |               |        |        |          |              | 906         | 0              | NEWCASTLE DR       |              | CHAMPAIGN | IL         | 61822    |            |                      | MULTIFAMILY                  | (12/4/2008 13:19 GJR) Just talked to Brad and he is going to send a letter of extension to Garry to request more time. (8/14/2009 4:23 PM GJR) Extended by Garry to 11/13/09. This will be the last extension given. | 0                  | 7856                    | 0                         | 0                     | 0                       | 0                    | 0                      | 0      | 2                 | 8               | 0                   | 321000    | 1788         | 0               | 1788      | 0           |              |           | Wellington Place LLC     | Wellington Place LLC           | Wellington Place LLC           | CRW_00605455         |         |                    | 0   |              |                |                   |              | 
| BS     | 10   | 2314       | BS10-2314     |                    |                  |                  | 2010-11-05T00:00:00 | VPA        | 2010-11-05T00:00:00 | VPA         | 2010-11-05T00:00:00 | VPA       | 2011-02-17T00:00:00 | PJA        |         |            |           |                       | BS10-0773            | PLUMBING          | NEW            | FINALED |                |            |               |               |                   | 104         |            | SF1        |                                  |                  |               |        |        |          | 442017379004 | 1507        |                | WYNDEMERE POINT DR |              | CHAMPAIGN | IL         | 61822    |            |                      | BackFlow Preventor           |                                                                                                                                                                                                                      |                    |                         |                           |                       |                         |                      |                        |        |                   |                 |                     |           | 45           |                 | 45        | 0           |              |           | MOHAMMED EIKRAM          | LS MECHANICAL                  | LS MECHANICAL                  | VPA:1011050327000450 |         | CRW:0946132882227  |     |              |                |                   | PARCEL       | 
```