# City of Albany Vacant Building Inventory: 2013

## Dataset

* [Dataset URL](https://data.ny.gov/api/views/nv2j-hmda/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/city-of-albany-vacant-building-inventory-2013)
* [Metadata URL](https://data.ny.gov/api/views/nv2j-hmda)
* Id = nv2j-hmda
* Name = City of Albany Vacant Building Inventory: 2013
* Attribution = City of Albany
* [Attribution Link](http://albanyny.gov/Government/Departments/Codes.aspx)
* Category = Economic Development
* Tags = [albany, vacant, building, inventory]
* Created = 2013-03-02T00:16:56Z
* Publication Date = 2013-03-10T15:29:05Z
* Rows Updated = 2013-03-10T15:21:43Z

## Description

Since January 2012, the Division of Buildings & Regulatory Compliance has created a living database documenting vacant buildings in the City of Albany. To create this database, the Division reconciled the Division of Building and Codes Vacant Building Registry with the Department of Fire and Emergency Services Vacant Building Database. This first reconciliation yielded a list of approximately 750 vacant buildings. The Division then reconciled that list with lists from neighborhood associations and lists from the Department of Assessment and Taxation.

## Columns

```ls
| Name                                                                                                                  | Field Name                                                                                            | Data Type     | Render Type   | Schema Type    | Included | 
| ===================================================================================================================== | ===================================================================================================== | ============= | ============= | ============== | ======== | 
| Completion Date                                                                                                       | completion_date                                                                                       | calendar_date | calendar_date | time           | Yes      | 
| Reason for Completion                                                                                                 | reason_for_completion                                                                                 | text          | text          | series tag     | Yes      | 
| Latest Record Update                                                                                                  | latest_record_update                                                                                  | calendar_date | calendar_date |                | No       | 
| Tax ID Number                                                                                                         | tax_id_number                                                                                         | number        | number        | numeric metric | Yes      | 
| SBL Number                                                                                                            | sbl_number                                                                                            | text          | text          | series tag     | Yes      | 
| Street Number                                                                                                         | street_number                                                                                         | text          | number        | series tag     | Yes      | 
| Street Name                                                                                                           | street_name                                                                                           | text          | text          | series tag     | Yes      | 
| Vacant / No Longer Vacant                                                                                             | vacant_no_longer_vacant                                                                               | text          | text          | series tag     | Yes      | 
| Current Status - Court ACTV / Registered / Owner MIA / County Owned / ACDA Owned / AHA Owned / Rehab - Permits Issued | current_status_court_actv_registered_owner_mia_county_owned_acda_owned_aha_owned_rehab_permits_issued | text          | text          | series tag     | Yes      | 
| Registration Expiration Date                                                                                          | registration_expiration_date                                                                          | calendar_date | calendar_date |                | No       | 
| Initial Registration Date                                                                                             | initial_registration_date                                                                             | calendar_date | calendar_date |                | No       | 
| Current Registration Fee                                                                                              | current_registration_fee                                                                              | money         | money         | numeric metric | Yes      | 
| Identification Inspection Date                                                                                        | identification_inspection_date                                                                        | calendar_date | calendar_date |                | No       | 
| Permits Issued                                                                                                        | permits_issued                                                                                        | text          | text          | series tag     | Yes      | 
| National Grid Action                                                                                                  | national_grid_action                                                                                  | text          | text          | series tag     | Yes      | 
| DGS Action                                                                                                            | dgs_action                                                                                            | text          | text          | series tag     | Yes      | 
| Initial Disposition                                                                                                   | initial_disposition                                                                                   | text          | text          | series tag     | Yes      | 
| Most Recent Maintenance Notice of Violation Date                                                                      | most_recent_maintenance_notice_of_violation_date                                                      | calendar_date | calendar_date |                | No       | 
| Most Recent Maintenance Inspection Date                                                                               | most_recent_maintenance_inspection_date                                                               | calendar_date | calendar_date |                | No       | 
| Maintenance Re-Inspection Date                                                                                        | maintenance_re_inspection_date                                                                        | calendar_date | calendar_date |                | No       | 
| Most Recent Inspector                                                                                                 | most_recent_inspector                                                                                 | text          | text          | series tag     | Yes      | 
| Maintenance Court Case Number                                                                                         | maintenance_court_case_number                                                                         | text          | text          | series tag     | Yes      | 
| Original Maintenance CT Date                                                                                          | original_maintenance_ct_date                                                                          | calendar_date | calendar_date |                | No       | 
| Court Notes                                                                                                           | court_notes                                                                                           | text          | text          | series tag     | Yes      | 
| Most Recent Registry Notice of Violation Date                                                                         | most_recent_registry_notice_of_violation_date                                                         | calendar_date | calendar_date |                | No       | 
| Registry Court Case Number                                                                                            | registry_court_case_number                                                                            | text          | text          | series tag     | Yes      | 
| Original Registry CT Date                                                                                             | original_registry_ct_date                                                                             | calendar_date | calendar_date |                | No       | 
| Court Notes2                                                                                                          | court_notes2                                                                                          | text          | text          | series tag     | Yes      | 
| Additional Notes                                                                                                      | additional_notes                                                                                      | text          | text          | series tag     | Yes      | 
| Registration Number                                                                                                   | registration_number                                                                                   | number        | number        | numeric metric | Yes      | 
| Registration Type                                                                                                     | registration_type                                                                                     | text          | text          | series tag     | Yes      | 
| Date of Vacancy                                                                                                       | date_of_vacancy                                                                                       | text          | text          | series tag     | Yes      | 
| Estimated Length of Vacancy                                                                                           | estimated_length_of_vacancy                                                                           | text          | text          | series tag     | Yes      | 
| Property Description / Tax Code                                                                                       | property_description_tax_code                                                                         | text          | text          | series tag     | Yes      | 
| Sq. Footage                                                                                                           | sq_footage                                                                                            | text          | text          | series tag     | Yes      | 
| Age of Building                                                                                                       | age_of_building                                                                                       | text          | text          | series tag     | Yes      | 
| No. of Stories Above/Below Ground                                                                                     | no_of_stories_above_below_ground                                                                      | text          | text          | series tag     | Yes      | 
| Most Recent Use                                                                                                       | most_recent_use                                                                                       | text          | text          | series tag     | Yes      | 
| No. of Dwelling/Office Units                                                                                          | no_of_dwelling_office_units                                                                           | number        | number        | numeric metric | Yes      | 
| Sprinkler System Y/N                                                                                                  | sprinkler_system_y_n                                                                                  | text          | text          | series tag     | Yes      | 
| Standpipe System Y/N                                                                                                  | standpipe_system_y_n                                                                                  | text          | text          | series tag     | Yes      | 
| Fire Detection System Y/N                                                                                             | fire_detection_system_y_n                                                                             | text          | text          | series tag     | Yes      | 
| Elevator Y/N                                                                                                          | elevator_y_n                                                                                          | text          | text          | series tag     | Yes      | 
| Historic Y/N                                                                                                          | historic_y_n                                                                                          | text          | text          | series tag     | Yes      | 
| Status - secured / abandoned / unsecured / etc                                                                        | status_secured_abandoned_unsecured_etc                                                                | text          | text          | series tag     | Yes      | 
| Electric ON/OFF                                                                                                       | electric_on_off                                                                                       | text          | text          | series tag     | Yes      | 
| Water ON/OFF                                                                                                          | water_on_off                                                                                          | text          | text          | series tag     | Yes      | 
| Gas ON/OFF                                                                                                            | gas_on_off                                                                                            | text          | text          | series tag     | Yes      | 
| Hazardous materials, uses, conditions                                                                                 | hazardous_materials_uses_conditions                                                                   | text          | text          | series tag     | Yes      | 
| Bonding Company                                                                                                       | bonding_company                                                                                       | text          | text          | series tag     | Yes      | 
| Amount of Bond                                                                                                        | amount_of_bond                                                                                        | money         | money         | numeric metric | Yes      | 
| Copy of Bond - Y/N                                                                                                    | copy_of_bond_y_n                                                                                      | text          | text          | series tag     | Yes      | 
| Owner Name                                                                                                            | owner_name                                                                                            | text          | text          | series tag     | Yes      | 
| Type of Owner                                                                                                         | type_of_owner                                                                                         | text          | text          | series tag     | Yes      | 
| Owner Tax ID                                                                                                          | owner_tax_id                                                                                          | text          | text          | series tag     | Yes      | 
| Owner City                                                                                                            | owner_city                                                                                            | text          | text          | series tag     | Yes      | 
| Owner State                                                                                                           | owner_state                                                                                           | text          | text          | series tag     | Yes      | 
| Owner Zip                                                                                                             | owner_zip                                                                                             | text          | text          | series tag     | Yes      | 
| Type of Ownership                                                                                                     | type_of_ownership                                                                                     | text          | text          | series tag     | Yes      | 
| Vacant Building Plan                                                                                                  | vacant_building_plan                                                                                  | text          | text          | series tag     | Yes      | 
| Photos - Y/N                                                                                                          | photos_y_n                                                                                            | text          | text          | series tag     | Yes      | 
| Site Plan - Y/N                                                                                                       | site_plan_y_n                                                                                         | text          | text          | series tag     | Yes      | 
| Historic Plan Attached- Y/N/NA                                                                                        | historic_plan_attached_y_n_na                                                                         | text          | text          | series tag     | Yes      | 
| Registration Anniversary Date                                                                                         | registration_anniversary_date                                                                         | calendar_date | calendar_date |                | No       | 
| Last Payment Date                                                                                                     | last_payment_date                                                                                     | calendar_date | calendar_date |                | No       | 
| Current Year Registration Fee                                                                                         | current_year_registration_fee                                                                         | money         | money         | numeric metric | Yes      | 
| Amount Enclosed                                                                                                       | amount_enclosed                                                                                       | text          | text          | series tag     | Yes      | 
| Payment Method                                                                                                        | payment_method                                                                                        | text          | text          | series tag     | Yes      | 
| Fee Received From                                                                                                     | fee_received_from                                                                                     | text          | text          | series tag     | Yes      | 
| Initial Registration Date2                                                                                            | initial_registration_date2                                                                            | calendar_date | calendar_date |                | No       | 
| Lienholder (1) Name                                                                                                   | lienholder_1_name                                                                                     | text          | text          | series tag     | Yes      | 
| Type of Lien                                                                                                          | type_of_lien                                                                                          | text          | text          | series tag     | Yes      | 
```

## Time Field

```ls
Value = completion_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = initial_registration_date,registration_expiration_date,initial_registration_date2,original_registry_ct_date,identification_inspection_date,last_payment_date,most_recent_maintenance_notice_of_violation_date,registration_anniversary_date,maintenance_re_inspection_date,most_recent_maintenance_inspection_date,latest_record_update,most_recent_registry_notice_of_violation_date,original_maintenance_ct_date
Annotation Fields = 
```

## Data Commands

```ls
series e:nv2j-hmda d:2017-03-08T01:45:00.699Z t:owner_name="Smith Property Management LLC" t:owner_state=NY t:owner_zip=12206 t:vacant_no_longer_vacant=V t:sbl_number=65.52-2-22 t:street_name="ALBANY ST" t:court_notes2="Trial 2/22/12" t:court_notes="Trial 2/22/12" t:street_number=5 t:additional_notes="8/25/12: new owner" t:initial_disposition="Demolition recommended" t:owner_city=Albany m:tax_id_number=12159 m:current_registration_fee=250

series e:nv2j-hmda d:2017-03-08T01:45:00.699Z t:property_description_tax_code="2 family" t:fee_received_from="Robert Van Wie" t:owner_name="Charles Van Wie, Jr" t:owner_zip=12186- t:sbl_number=65.52-2-25 t:vacant_building_plan="Rehab for 2 family rental.  Pending money" t:vacant_no_longer_vacant=V t:street_name="ALBANY ST" t:initial_disposition="Good candidate for rehabilitation" t:owner_city=Voorheesville t:permits_issued="2001-fire repair" t:national_grid_action="Cut Power at the Pole" t:amount_enclosed=$1,000.00 t:owner_state=NY t:street_number=11 t:payment_method=Paid m:tax_id_number=12162 m:current_registration_fee=2000 m:current_year_registration_fee=1000 m:registration_number=1303

series e:nv2j-hmda d:2017-03-08T01:45:00.699Z t:registry_court_case_number=12-110 t:fee_received_from="Owayne Thompson" t:owner_name="Owayne Thompson" t:gas_on_off=OFF t:sbl_number=65.52-2-47 t:vacant_no_longer_vacant=V t:street_name="ALBANY ST" t:court_notes="1/16/13 - adj 1/24/13 for status-withdraw" t:age_of_building="122 yrs" t:historic_y_n=N t:fire_detection_system_y_n=N t:photos_y_n=Y t:initial_disposition="Good candidate for rehabilitation" t:owner_city=Brooklyn t:elevator_y_n=N t:status_secured_abandoned_unsecured_etc=Secure t:owner_state=NY t:electric_on_off=OFF t:standpipe_system_y_n=N t:court_notes2="1/16/13 - adj 1/24/13 for status-withdraw" t:street_number=18 t:owner_zip=11208 t:water_on_off=OFF t:current_status_court_actv_registered_owner_mia_county_owned_acda_owned_aha_owned_rehab_permits_issued="Registration Current (Without Bond)                    45 days to register $1,000.00 reduction order if not then no deal                                COURT ACTV R/M 1/24/13" t:permits_issued="2008-interior alterations; 2007-gutting" t:national_grid_action="Power already cut at pole" t:amount_enclosed=$1,000.00 t:estimated_length_of_vacancy="12 months" t:registration_type=Original t:sprinkler_system_y_n=N t:additional_notes=646-545-0057 t:maintenance_court_case_number=12-111 t:payment_method="Money Order" t:sq_footage="1425 sq ft" m:tax_id_number=12135 m:current_registration_fee=2000 m:current_year_registration_fee=1000 m:registration_number=1646
```

## Meta Commands

```ls
metric m:tax_id_number p:integer l:"Tax ID Number" t:dataTypeName=number

metric m:registration_number p:integer l:"Registration Number" t:dataTypeName=number

metric m:no_of_dwelling_office_units p:integer l:"No. of Dwelling/Office Units" t:dataTypeName=number

entity e:nv2j-hmda l:"City of Albany Vacant Building Inventory: 2013" t:attribution="City of Albany" t:url=https://data.ny.gov/api/views/nv2j-hmda

property e:nv2j-hmda t:meta.view d:2017-03-08T01:45:00.699Z v:id=nv2j-hmda v:category="Economic Development" v:attributionLink=http://albanyny.gov/Government/Departments/Codes.aspx v:averageRating=0 v:name="City of Albany Vacant Building Inventory: 2013" v:attribution="City of Albany"

property e:nv2j-hmda t:meta.view.owner d:2017-03-08T01:45:00.699Z v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:nv2j-hmda t:meta.view.tableauthor d:2017-03-08T01:45:00.699Z v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:nv2j-hmda t:meta.view.metadata.custom_fields.common_core d:2017-03-08T01:45:00.699Z v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```