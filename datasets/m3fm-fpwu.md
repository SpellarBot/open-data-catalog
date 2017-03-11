# City of Champaign Permit Data (Updated 12-04-12)

## Dataset

* [Dataset URL](https://data.illinois.gov/api/views/m3fm-fpwu/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/city-of-champaign-permit-data-updated-12-04-12-8f885)
* [Metadata URL](https://data.illinois.gov/api/views/m3fm-fpwu)
* Id = m3fm-fpwu
* Name = City of Champaign Permit Data (Updated 12-04-12)
* Attribution = City of Champaign
* Category = Municipality
* Tags = [permit, construction, champaign]
* Created = 2012-12-04T19:53:57Z
* Publication Date = 2012-12-04T21:48:50Z
* Rows Updated = 2012-12-04T21:06:22Z

## Description



## Columns

```ls
| Name                      | Field Name                | Data Type     | Render Type   | Schema Type    | Included | 
| ========================= | ========================= | ============= | ============= | ============== | ======== | 
| Prefix                    | prefix                    | text          | text          | series tag     | Yes      | 
| YRMO                      | yrmo                      | number        | number        | numeric metric | Yes      | 
| Seq Number                | seq_number                | number        | number        | numeric metric | Yes      | 
| Permit Number             | permit_number             | text          | text          | series tag     | Yes      | 
| Application Number        | application_number        | text          | text          | series tag     | Yes      | 
| Plancheck Number          | plancheck_number          | text          | text          | series tag     | Yes      | 
| Reference Number          | reference_number          | text          | text          | series tag     | Yes      | 
| Applied                   | applied                   | calendar_date | calendar_date | time           | Yes      | 
| Applied By                | applied_by                | text          | text          | series tag     | Yes      | 
| Approved                  | approved                  | calendar_date | calendar_date |                | No       | 
| Approved By               | approved_by               | text          | text          | series tag     | Yes      | 
| Issued                    | issued                    | calendar_date | calendar_date |                | No       | 
| Issued By                 | issued_by                 | text          | text          | series tag     | Yes      | 
| Finaled                   | finaled                   | calendar_date | calendar_date |                | No       | 
| Finaled By                | finaled_by                | text          | text          | series tag     | Yes      | 
| Expired                   | expired                   | text          | text          | series tag     | Yes      | 
| Expired By                | expired_by                | text          | text          | series tag     | Yes      | 
| Valid For                 | valid_for                 | text          | text          | series tag     | Yes      | 
| Parent Project Number     | parent_project_number     | text          | text          | series tag     | Yes      | 
| Parent Permit Number      | parent_permit_number      | text          | text          | series tag     | Yes      | 
| Permit Type               | permit_type               | text          | text          | series tag     | Yes      | 
| Permit Subtype            | permit_subtype            | text          | text          | series tag     | Yes      | 
| Status                    | status                    | text          | text          | series tag     | Yes      | 
| Occupancy Type            | occupancy_type            | text          | text          | series tag     | Yes      | 
| Group Code                | group_code                | text          | text          | series tag     | Yes      | 
| Zoning Code 1             | zoning_code_1             | text          | text          | series tag     | Yes      | 
| Zoning Code 2             | zoning_code_2             | text          | text          | series tag     | Yes      | 
| Construction Type         | construction_type         | text          | text          | series tag     | Yes      | 
| Site Lot No               | site_lot_no               | text          | text          | series tag     | Yes      | 
| Site Block                | site_block                | number        | number        | numeric metric | Yes      | 
| Site Tract                | site_tract                | text          | text          | series tag     | Yes      | 
| Site Subdivision          | site_subdivision          | text          | text          | series tag     | Yes      | 
| Site Description          | site_description          | text          | text          | series tag     | Yes      | 
| Tax Rate Area             | tax_rate_area             | text          | text          | series tag     | Yes      | 
| School                    | school                    | text          | text          | series tag     | Yes      | 
| Census                    | census                    | text          | text          | series tag     | Yes      | 
| FW Dodge                  | fw_dodge                  | text          | text          | series tag     | Yes      | 
| Site APN                  | site_apn                  | text          | text          | series tag     | Yes      | 
| Site Number               | site_number               | text          | text          | series tag     | Yes      | 
| Site Street ID            | site_street_id            | text          | number        | series tag     | Yes      | 
| Site Street Name          | site_street_name          | text          | text          | series tag     | Yes      | 
| Site Unit No              | site_unit_no              | text          | text          | series tag     | Yes      | 
| Site City                 | site_city                 | text          | text          | series tag     | Yes      | 
| Site State                | site_state                | text          | text          | series tag     | Yes      | 
| Site Zip                  | site_zip                  | text          | number        | series tag     | Yes      | 
| Site ST No                | site_st_no                | text          | text          | series tag     | Yes      | 
| Location Description      | location_description      | text          | text          | series tag     | Yes      | 
| Description               | description               | text          | text          | series tag     | Yes      | 
| Notes                     | notes                     | text          | text          | series tag     | Yes      | 
| Lot Square Footage        | lot_square_footage        | number        | number        | numeric metric | Yes      | 
| Building Square Footage   | building_square_footage   | number        | number        | numeric metric | Yes      | 
| Building 2 Square Footage | building_2_square_footage | number        | number        | numeric metric | Yes      | 
| Garage Square Footage     | garage_square_footage     | number        | number        | numeric metric | Yes      | 
| Garage 2 Square Footage   | garage_2_square_footage   | number        | number        | numeric metric | Yes      | 
| Porch Square Footage      | porch_square_footage      | number        | number        | numeric metric | Yes      | 
| Porch 2 Square Footage    | porch_2_square_footage    | number        | number        | numeric metric | Yes      | 
| Height                    | height                    | number        | number        | numeric metric | Yes      | 
| Number of Stories         | number_of_stories         | number        | number        | numeric metric | Yes      | 
| Number of Units           | number_of_units           | number        | number        | numeric metric | Yes      | 
| Number of Buildings       | number_of_buildings       | number        | number        | numeric metric | Yes      | 
| Job Value                 | job_value                 | money         | money         | numeric metric | Yes      | 
| Fees Charged              | fees_charged              | money         | money         | numeric metric | Yes      | 
| Fee Adjustments           | fee_adjustments           | money         | money         | numeric metric | Yes      | 
| Fees Paid                 | fees_paid                 | money         | money         | numeric metric | Yes      | 
| Balance Due               | balance_due               | money         | money         | numeric metric | Yes      | 
| Other Date 1              | other_date_1              | text          | text          | series tag     | Yes      | 
| Other_By1                 | other_by1                 | text          | text          | series tag     | Yes      | 
| Owner Name                | owner_name                | text          | text          | series tag     | Yes      | 
| Applicant Name            | applicant_name            | text          | text          | series tag     | Yes      | 
| Contractor Name           | contractor_name           | text          | text          | series tag     | Yes      | 
| Record ID                 | record_id                 | text          | text          | series tag     | Yes      | 
| Lock ID                   | lock_id                   | text          | text          | series tag     | Yes      | 
| Location Record ID        | location_record_id        | text          | text          | series tag     | Yes      | 
| PIN                       | pin                       | number        | number        | numeric metric | Yes      | 
| Deposit Type              | deposit_type              | text          | text          | series tag     | Yes      | 
| Historical APN            | historical_apn            | text          | text          | series tag     | Yes      | 
| Site Alternate IL         | site_alternate_il         | text          | text          | series tag     | Yes      | 
| Site Geotype              | site_geotype              | text          | text          | series tag     | Yes      | 
```

## Time Field

```ls
Value = applied
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = approved,issued,finaled
Annotation Fields = 
```

## Data Commands

```ls
series e:m3fm-fpwu d:2006-08-18T00:00:00.000Z t:site_city=CHAMPAIGN t:permit_type=HVAC t:site_zip=61820 t:owner_name="SALVATION ARMY" t:site_state=IL t:status=FINALED t:applied_by=VPA t:site_number=2212 t:applicant_name="Getz Fire Equipment" t:record_id=CRW_00612712 t:issued_by=VPA t:permit_number=BS06-3766 t:site_street_name="N MARKET" t:approved_by=VPA t:location_record_id=KR:512021404000034 t:contractor_name="Getz Fire Equipment" t:site_apn=462106101008 t:finaled_by=CRL t:description=SUPPRESSION t:site_tract=CI t:prefix=BS t:permit_subtype=Alteration t:parent_permit_number=BS06-1438 t:site_street_id=0 m:building_square_footage=22465 m:lot_square_footage=0 m:fee_adjustments=0 m:balance_due=0 m:porch_2_square_footage=0 m:building_2_square_footage=0 m:job_value=300 m:seq_number=3766 m:height=0 m:pin=0 m:fees_charged=45 m:fees_paid=45 m:number_of_units=2 m:garage_2_square_footage=0 m:garage_square_footage=0 m:porch_square_footage=0 m:number_of_buildings=0 m:number_of_stories=0 m:yrmo=6

series e:m3fm-fpwu d:2006-06-23T00:00:00.000Z t:site_city=CHAMPAIGN t:permit_type=PLUMBING t:owner_name="MACFARLANE, ROBERT F" t:site_state=IL t:status=FINALED t:applied_by=VPA t:site_number=1017 t:applicant_name="Clark Plbg. & Htg." t:record_id=CRW_00623666 t:issued_by=VPA t:permit_number=BS06-2853 t:site_street_name="LINCOLNSHIRE DR" t:location_record_id=CRW_00810880 t:approved_by=VPA t:contractor_name="Clark Plbg. & Htg." t:site_apn=452023226001 t:finaled_by=MPE t:description="BACKFLOW PREVENTOR" t:prefix=BS t:permit_subtype=New t:site_street_id=0 m:building_square_footage=0 m:lot_square_footage=0 m:fee_adjustments=0 m:balance_due=0 m:porch_2_square_footage=0 m:building_2_square_footage=0 m:job_value=0 m:seq_number=2853 m:height=0 m:pin=0 m:fees_charged=35 m:fees_paid=35 m:number_of_units=0 m:garage_2_square_footage=0 m:garage_square_footage=0 m:porch_square_footage=0 m:number_of_buildings=0 m:number_of_stories=0 m:yrmo=6

series e:m3fm-fpwu d:2006-03-31T00:00:00.000Z t:site_city=CHAMPAIGN t:permit_type=GRADING t:site_zip=61822 t:expired=00:00.0 t:expired_by=LCL t:owner_name="RAYCORP, INC" t:site_state=IL t:status=ISSUED t:applied_by=VP t:site_number=2714-2716 t:applicant_name="Architectural Spectrum" t:record_id=CRW_00622410 t:issued_by=LCL t:permit_number=EN06-0891 t:site_street_name=MADELYN t:approved_by=VP t:description=G&D t:prefix=EN t:permit_subtype=New t:parent_permit_number=BS06-1264 t:site_street_id=0 m:building_square_footage=0 m:lot_square_footage=0 m:fee_adjustments=0 m:balance_due=0 m:porch_2_square_footage=0 m:building_2_square_footage=0 m:job_value=0 m:seq_number=891 m:height=0 m:pin=0 m:fees_charged=0 m:fees_paid=0 m:number_of_units=0 m:garage_2_square_footage=0 m:garage_square_footage=0 m:porch_square_footage=0 m:number_of_buildings=0 m:number_of_stories=0 m:yrmo=6
```

## Meta Commands

```ls
metric m:yrmo p:integer l:YRMO t:dataTypeName=number

metric m:seq_number p:integer l:"Seq Number" t:dataTypeName=number

metric m:site_block p:integer l:"Site Block" t:dataTypeName=number

metric m:lot_square_footage p:integer l:"Lot Square Footage" t:dataTypeName=number

metric m:building_square_footage p:integer l:"Building Square Footage" t:dataTypeName=number

metric m:building_2_square_footage p:integer l:"Building 2 Square Footage" t:dataTypeName=number

metric m:garage_square_footage p:integer l:"Garage Square Footage" t:dataTypeName=number

metric m:garage_2_square_footage p:integer l:"Garage 2 Square Footage" t:dataTypeName=number

metric m:porch_square_footage p:integer l:"Porch Square Footage" t:dataTypeName=number

metric m:porch_2_square_footage p:integer l:"Porch 2 Square Footage" t:dataTypeName=number

metric m:height p:integer l:Height t:dataTypeName=number

metric m:number_of_stories l:"Number of Stories" t:dataTypeName=number

metric m:number_of_units p:integer l:"Number of Units" t:dataTypeName=number

metric m:number_of_buildings p:integer l:"Number of Buildings" t:dataTypeName=number

metric m:pin p:integer l:PIN t:dataTypeName=number

entity e:m3fm-fpwu l:"City of Champaign Permit Data (Updated 12-04-12)" t:attribution="City of Champaign" t:url=https://data.illinois.gov/api/views/m3fm-fpwu

property e:m3fm-fpwu t:meta.view d:2017-03-08T00:38:37.534Z v:id=m3fm-fpwu v:category=Municipality v:averageRating=0 v:name="City of Champaign Permit Data (Updated 12-04-12)" v:attribution="City of Champaign"

property e:m3fm-fpwu t:meta.view.license d:2017-03-08T00:38:37.534Z v:name="Public Domain"

property e:m3fm-fpwu t:meta.view.owner d:2017-03-08T00:38:37.534Z v:id=v5dz-wzd9 v:screenName="Patrick East" v:displayName="Patrick East"

property e:m3fm-fpwu t:meta.view.tableauthor d:2017-03-08T00:38:37.534Z v:id=v5dz-wzd9 v:screenName="Patrick East" v:displayName="Patrick East"
```