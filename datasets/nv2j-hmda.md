# City of Albany Vacant Building Inventory: 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/city-of-albany-vacant-building-inventory-2013) |
| Metadata | [Link](https://data.ny.gov/api/views/nv2j-hmda) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/nv2j-hmda/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/nv2j-hmda/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | nv2j-hmda |
| Name | City of Albany Vacant Building Inventory: 2013 |
| Attribution | City of Albany |
| Category | Economic Development |
| Tags | albany, vacant, building, inventory |
| Created | 2013-03-02T00:16:56Z |
| Publication Date | 2013-03-10T15:29:05Z |
| Rows Updated | 2013-03-10T15:21:43Z |

## Description

Since January 2012, the Division of Buildings & Regulatory Compliance has created a living database documenting vacant buildings in the City of Albany. To create this database, the Division reconciled the Division of Building and Codes Vacant Building Registry with the Department of Fire and Emergency Services Vacant Building Database. This first reconciliation yielded a list of approximately 750 vacant buildings. The Division then reconciled that list with lists from neighborhood associations and lists from the Department of Assessment and Taxation.

## Columns

```ls
| Included | Schema Type    | Field Name                                                                                            | Name                                                                                                                  | Data Type     | Render Type   |
| ======== | ============== | ===================================================================================================== | ===================================================================================================================== | ============= | ============= |
| Yes      | time           | completion_date                                                                                       | Completion Date                                                                                                       | calendar_date | calendar_date |
| Yes      | series tag     | reason_for_completion                                                                                 | Reason for Completion                                                                                                 | text          | text          |
| No       |                | latest_record_update                                                                                  | Latest Record Update                                                                                                  | calendar_date | calendar_date |
| Yes      | series tag     | tax_id_number                                                                                         | Tax ID Number                                                                                                         | text          | number        |
| Yes      | series tag     | sbl_number                                                                                            | SBL Number                                                                                                            | text          | text          |
| Yes      | series tag     | street_number                                                                                         | Street Number                                                                                                         | text          | number        |
| Yes      | series tag     | street_name                                                                                           | Street Name                                                                                                           | text          | text          |
| Yes      | series tag     | vacant_no_longer_vacant                                                                               | Vacant / No Longer Vacant                                                                                             | text          | text          |
| Yes      | series tag     | current_status_court_actv_registered_owner_mia_county_owned_acda_owned_aha_owned_rehab_permits_issued | Current Status - Court ACTV / Registered / Owner MIA / County Owned / ACDA Owned / AHA Owned / Rehab - Permits Issued | text          | text          |
| No       |                | registration_expiration_date                                                                          | Registration Expiration Date                                                                                          | calendar_date | calendar_date |
| No       |                | initial_registration_date                                                                             | Initial Registration Date                                                                                             | calendar_date | calendar_date |
| Yes      | numeric metric | current_registration_fee                                                                              | Current Registration Fee                                                                                              | money         | money         |
| No       |                | identification_inspection_date                                                                        | Identification Inspection Date                                                                                        | calendar_date | calendar_date |
| Yes      | series tag     | permits_issued                                                                                        | Permits Issued                                                                                                        | text          | text          |
| Yes      | series tag     | national_grid_action                                                                                  | National Grid Action                                                                                                  | text          | text          |
| Yes      | series tag     | dgs_action                                                                                            | DGS Action                                                                                                            | text          | text          |
| Yes      | series tag     | initial_disposition                                                                                   | Initial Disposition                                                                                                   | text          | text          |
| No       |                | most_recent_maintenance_notice_of_violation_date                                                      | Most Recent Maintenance Notice of Violation Date                                                                      | calendar_date | calendar_date |
| No       |                | most_recent_maintenance_inspection_date                                                               | Most Recent Maintenance Inspection Date                                                                               | calendar_date | calendar_date |
| No       |                | maintenance_re_inspection_date                                                                        | Maintenance Re-Inspection Date                                                                                        | calendar_date | calendar_date |
| Yes      | series tag     | most_recent_inspector                                                                                 | Most Recent Inspector                                                                                                 | text          | text          |
| Yes      | series tag     | maintenance_court_case_number                                                                         | Maintenance Court Case Number                                                                                         | text          | text          |
| No       |                | original_maintenance_ct_date                                                                          | Original Maintenance CT Date                                                                                          | calendar_date | calendar_date |
| Yes      | series tag     | court_notes                                                                                           | Court Notes                                                                                                           | text          | text          |
| No       |                | most_recent_registry_notice_of_violation_date                                                         | Most Recent Registry Notice of Violation Date                                                                         | calendar_date | calendar_date |
| Yes      | series tag     | registry_court_case_number                                                                            | Registry Court Case Number                                                                                            | text          | text          |
| No       |                | original_registry_ct_date                                                                             | Original Registry CT Date                                                                                             | calendar_date | calendar_date |
| Yes      | series tag     | court_notes2                                                                                          | Court Notes2                                                                                                          | text          | text          |
| Yes      | series tag     | additional_notes                                                                                      | Additional Notes                                                                                                      | text          | text          |
| Yes      | series tag     | registration_number                                                                                   | Registration Number                                                                                                   | text          | number        |
| Yes      | series tag     | registration_type                                                                                     | Registration Type                                                                                                     | text          | text          |
| Yes      | series tag     | date_of_vacancy                                                                                       | Date of Vacancy                                                                                                       | text          | text          |
| Yes      | series tag     | estimated_length_of_vacancy                                                                           | Estimated Length of Vacancy                                                                                           | text          | text          |
| Yes      | series tag     | property_description_tax_code                                                                         | Property Description / Tax Code                                                                                       | text          | text          |
| Yes      | series tag     | sq_footage                                                                                            | Sq. Footage                                                                                                           | text          | text          |
| Yes      | series tag     | age_of_building                                                                                       | Age of Building                                                                                                       | text          | text          |
| Yes      | series tag     | no_of_stories_above_below_ground                                                                      | No. of Stories Above/Below Ground                                                                                     | text          | text          |
| Yes      | series tag     | most_recent_use                                                                                       | Most Recent Use                                                                                                       | text          | text          |
| Yes      | numeric metric | no_of_dwelling_office_units                                                                           | No. of Dwelling/Office Units                                                                                          | number        | number        |
| Yes      | series tag     | sprinkler_system_y_n                                                                                  | Sprinkler System Y/N                                                                                                  | text          | text          |
| Yes      | series tag     | standpipe_system_y_n                                                                                  | Standpipe System Y/N                                                                                                  | text          | text          |
| Yes      | series tag     | fire_detection_system_y_n                                                                             | Fire Detection System Y/N                                                                                             | text          | text          |
| Yes      | series tag     | elevator_y_n                                                                                          | Elevator Y/N                                                                                                          | text          | text          |
| Yes      | series tag     | historic_y_n                                                                                          | Historic Y/N                                                                                                          | text          | text          |
| Yes      | series tag     | status_secured_abandoned_unsecured_etc                                                                | Status - secured / abandoned / unsecured / etc                                                                        | text          | text          |
| Yes      | series tag     | electric_on_off                                                                                       | Electric ON/OFF                                                                                                       | text          | text          |
| Yes      | series tag     | water_on_off                                                                                          | Water ON/OFF                                                                                                          | text          | text          |
| Yes      | series tag     | gas_on_off                                                                                            | Gas ON/OFF                                                                                                            | text          | text          |
| Yes      | series tag     | hazardous_materials_uses_conditions                                                                   | Hazardous materials, uses, conditions                                                                                 | text          | text          |
| Yes      | series tag     | bonding_company                                                                                       | Bonding Company                                                                                                       | text          | text          |
| Yes      | numeric metric | amount_of_bond                                                                                        | Amount of Bond                                                                                                        | money         | money         |
| Yes      | series tag     | copy_of_bond_y_n                                                                                      | Copy of Bond - Y/N                                                                                                    | text          | text          |
| Yes      | series tag     | owner_name                                                                                            | Owner Name                                                                                                            | text          | text          |
| Yes      | series tag     | type_of_owner                                                                                         | Type of Owner                                                                                                         | text          | text          |
| Yes      | series tag     | owner_tax_id                                                                                          | Owner Tax ID                                                                                                          | text          | text          |
| Yes      | series tag     | owner_city                                                                                            | Owner City                                                                                                            | text          | text          |
| Yes      | series tag     | owner_state                                                                                           | Owner State                                                                                                           | text          | text          |
| Yes      | series tag     | owner_zip                                                                                             | Owner Zip                                                                                                             | text          | text          |
| Yes      | series tag     | type_of_ownership                                                                                     | Type of Ownership                                                                                                     | text          | text          |
| Yes      | series tag     | vacant_building_plan                                                                                  | Vacant Building Plan                                                                                                  | text          | text          |
| Yes      | series tag     | photos_y_n                                                                                            | Photos - Y/N                                                                                                          | text          | text          |
| Yes      | series tag     | site_plan_y_n                                                                                         | Site Plan - Y/N                                                                                                       | text          | text          |
| Yes      | series tag     | historic_plan_attached_y_n_na                                                                         | Historic Plan Attached- Y/N/NA                                                                                        | text          | text          |
| No       |                | registration_anniversary_date                                                                         | Registration Anniversary Date                                                                                         | calendar_date | calendar_date |
| No       |                | last_payment_date                                                                                     | Last Payment Date                                                                                                     | calendar_date | calendar_date |
| Yes      | numeric metric | current_year_registration_fee                                                                         | Current Year Registration Fee                                                                                         | money         | money         |
| Yes      | series tag     | amount_enclosed                                                                                       | Amount Enclosed                                                                                                       | text          | text          |
| Yes      | series tag     | payment_method                                                                                        | Payment Method                                                                                                        | text          | text          |
| Yes      | series tag     | fee_received_from                                                                                     | Fee Received From                                                                                                     | text          | text          |
| No       |                | initial_registration_date2                                                                            | Initial Registration Date2                                                                                            | calendar_date | calendar_date |
| Yes      | series tag     | lienholder_1_name                                                                                     | Lienholder (1) Name                                                                                                   | text          | text          |
| Yes      | series tag     | type_of_lien                                                                                          | Type of Lien                                                                                                          | text          | text          |
```

## Time Field

```ls
Value = completion_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = latest_record_update,registration_expiration_date,initial_registration_date,identification_inspection_date,most_recent_maintenance_notice_of_violation_date,most_recent_maintenance_inspection_date,maintenance_re_inspection_date,original_maintenance_ct_date,most_recent_registry_notice_of_violation_date,original_registry_ct_date,registration_anniversary_date,last_payment_date,initial_registration_date2
```

## Data Commands

```ls
series e:nv2j-hmda d:2017-03-14T07:25:43.095Z t:owner_name="Smith Property Management LLC" t:owner_state=NY t:tax_id_number=12159 t:owner_zip=12206 t:vacant_no_longer_vacant=V t:sbl_number=65.52-2-22 t:street_name="ALBANY ST" t:court_notes2="Trial 2/22/12" t:court_notes="Trial 2/22/12" t:street_number=5 t:additional_notes="8/25/12: new owner" t:initial_disposition="Demolition recommended" t:owner_city=Albany m:current_registration_fee=250

series e:nv2j-hmda d:2017-03-14T07:25:43.095Z t:property_description_tax_code="2 family" t:fee_received_from="Robert Van Wie" t:owner_name="Charles Van Wie, Jr" t:owner_zip=12186- t:vacant_no_longer_vacant=V t:sbl_number=65.52-2-25 t:vacant_building_plan="Rehab for 2 family rental.  Pending money" t:street_name="ALBANY ST" t:initial_disposition="Good candidate for rehabilitation" t:owner_city=Voorheesville t:permits_issued="2001-fire repair" t:national_grid_action="Cut Power at the Pole" t:amount_enclosed=$1,000.00 t:owner_state=NY t:tax_id_number=12162 t:street_number=11 t:registration_number=1303 t:payment_method=Paid m:current_registration_fee=2000 m:current_year_registration_fee=1000

series e:nv2j-hmda d:2017-03-14T07:25:43.095Z t:registry_court_case_number=12-110 t:fee_received_from="Owayne Thompson" t:owner_name="Owayne Thompson" t:gas_on_off=OFF t:sbl_number=65.52-2-47 t:vacant_no_longer_vacant=V t:street_name="ALBANY ST" t:court_notes="1/16/13 - adj 1/24/13 for status-withdraw" t:age_of_building="122 yrs" t:historic_y_n=N t:fire_detection_system_y_n=N t:photos_y_n=Y t:initial_disposition="Good candidate for rehabilitation" t:owner_city=Brooklyn t:elevator_y_n=N t:status_secured_abandoned_unsecured_etc=Secure t:owner_state=NY t:tax_id_number=12135 t:electric_on_off=OFF t:standpipe_system_y_n=N t:court_notes2="1/16/13 - adj 1/24/13 for status-withdraw" t:street_number=18 t:owner_zip=11208 t:water_on_off=OFF t:current_status_court_actv_registered_owner_mia_county_owned_acda_owned_aha_owned_rehab_permits_issued="Registration Current (Without Bond)                    45 days to register $1,000.00 reduction order if not then no deal                                COURT ACTV R/M 1/24/13" t:permits_issued="2008-interior alterations; 2007-gutting" t:national_grid_action="Power already cut at pole" t:amount_enclosed=$1,000.00 t:estimated_length_of_vacancy="12 months" t:registration_type=Original t:sprinkler_system_y_n=N t:additional_notes=646-545-0057 t:maintenance_court_case_number=12-111 t:registration_number=1646 t:payment_method="Money Order" t:sq_footage="1425 sq ft" m:current_registration_fee=2000 m:current_year_registration_fee=1000
```

## Meta Commands

```ls
metric m:current_registration_fee p:double l:"Current Registration Fee" t:dataTypeName=money

metric m:no_of_dwelling_office_units p:integer l:"No. of Dwelling/Office Units" t:dataTypeName=number

metric m:amount_of_bond p:double l:"Amount of Bond" t:dataTypeName=money

metric m:current_year_registration_fee p:double l:"Current Year Registration Fee" t:dataTypeName=money

entity e:nv2j-hmda l:"City of Albany Vacant Building Inventory: 2013" t:attribution="City of Albany" t:url=https://data.ny.gov/api/views/nv2j-hmda

property e:nv2j-hmda t:meta.view v:id=nv2j-hmda v:category="Economic Development" v:attributionLink=http://albanyny.gov/Government/Departments/Codes.aspx v:averageRating=0 v:name="City of Albany Vacant Building Inventory: 2013" v:attribution="City of Albany"

property e:nv2j-hmda t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:nv2j-hmda t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:nv2j-hmda t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```