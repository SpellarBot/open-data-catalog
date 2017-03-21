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
| Rows Updated | 2012-12-04T21:06:22Z |

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