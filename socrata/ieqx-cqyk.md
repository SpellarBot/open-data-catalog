# Directory of Developmental Disabilities Service Provider Agencies

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/directory-of-developmental-disabilities-service-provider-agencies) |
| Metadata | [Link](https://data.ny.gov/api/views/ieqx-cqyk) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/ieqx-cqyk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/ieqx-cqyk/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | ieqx-cqyk |
| Name | Directory of Developmental Disabilities Service Provider Agencies |
| Attribution | New York State Office for People With Developmental Disabilities (NYS OPWDD) |
| Category | Human Services |
| Tags | developmental disabilities, opwdd, residential supports, day services, supported employment |
| Created | 2014-03-03T13:57:52Z |
| Publication Date | 2015-12-22T15:58:12Z |

## Description

This data set contains the address and phone number information for voluntary provider agencies of the following Office for People with Developmental Disabilities (OPWDD) supports and services:  Intermediate Care Facilities (ICFs), Individual Residential Alternative (IRAs), Family Care, Consolidated Supports And Services, Individual Support Services (ISSs), Day Training, Day Treatment, Senior/Geriatric Services, Day Habilitation, Work Shop, Prevocational, Supported Employment Enrollments, Community Habilitation, Family Support Services, Care At Home Waiver Services, and Developmental Centers And Special Population Services.  The State sector district offices (DDSOs) have remained in the Developmental Disabilities Service Provider Agencies data because they too are identified by a provider agency code that identifies the voluntary providers.

## Columns

```ls
| Included | Schema Type | Field Name                                            | Name                                                  | Data Type | Render Type |
| ======== | =========== | ===================================================== | ===================================================== | ========= | =========== |
| No       | time        | :updated_at                                           | updated_at                                            | meta_data | meta_data   |
| Yes      | series tag  | developmental_disability_services_office              | Developmental Disability Services Office              | text      | text        |
| Yes      | series tag  | service_provider                                      | Service Provider Agency                               | text      | text        |
| Yes      | series tag  | street_address                                        | Street Address                                        | text      | text        |
| Yes      | series tag  | street_address_line_2                                 | Street Address Line 2                                 | text      | text        |
| Yes      | series tag  | city                                                  | City                                                  | text      | text        |
| Yes      | series tag  | state                                                 | State                                                 | text      | text        |
| Yes      | series tag  | zip_code                                              | Zip Code                                              | text      | number      |
| Yes      | series tag  | phone                                                 | Phone                                                 | text      | text        |
| Yes      | series tag  | county                                                | County                                                | text      | text        |
| Yes      | series tag  | url                                                   | Website Url                                           | url       | url         |
| Yes      | series tag  | intermediate_care_facilities_icf_s                    | Intermediate Care Facilities (ICFs)                   | text      | text        |
| Yes      | series tag  | individual_residential_alternative_ira                | Individual Residential Alternative (IRA)              | text      | text        |
| Yes      | series tag  | family_care                                           | Family Care                                           | text      | text        |
| Yes      | series tag  | consolidated_supports_and_services                    | Consolidated Supports And Services                    | text      | text        |
| Yes      | series tag  | individual_support_services_iss                       | Individual Support Services (ISSs)                    | text      | text        |
| Yes      | series tag  | day_training                                          | Day Training                                          | text      | text        |
| Yes      | series tag  | day_treatment                                         | Day Treatment                                         | text      | text        |
| Yes      | series tag  | senior_geriatric_services                             | Senior/Geriatric Services                             | text      | text        |
| Yes      | series tag  | day_habilitation                                      | Day Habilitation                                      | text      | text        |
| Yes      | series tag  | work_shop                                             | Work Shop                                             | text      | text        |
| Yes      | series tag  | prevocational                                         | Prevocational                                         | text      | text        |
| Yes      | series tag  | supported_employment_enrollments                      | Supported Employment Enrollments                      | text      | text        |
| Yes      | series tag  | community_habilitation                                | Community Habilitation                                | text      | text        |
| Yes      | series tag  | family_support_services                               | Family Support Services                               | text      | text        |
| Yes      | series tag  | care_at_home_waiver_services                          | Care at Home Waiver Services                          | text      | text        |
| Yes      | series tag  | developmental_centers_and_special_population_services | Developmental Centers And Special Population Services | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:ieqx-cqyk d:2015-12-21T08:56:45.000Z t:supported_employment_enrollments=N t:prevocational=N t:day_treatment=N t:phone=718-217-4242 t:service_provider="0230 - BERNARD M. FINESON DDSO" t:zip_code=11428 t:consolidated_supports_and_services=N t:senior_geriatric_services=N t:developmental_centers_and_special_population_services=Y t:state=NY t:intermediate_care_facilities_icf_s=N t:care_at_home_waiver_services=Y t:family_support_services=N t:city="QUEENS VILLAGE" t:work_shop=N t:individual_support_services_iss=N t:developmental_disability_services_office="BERNARD M. FINESON DDSO" t:family_care=Y t:county=QUEENS t:street_address_line_2="80-45 WINCHESTER BLVD" t:community_habilitation=N t:individual_residential_alternative_ira=Y t:street_address="P.O. BOX 280507" t:day_habilitation=Y t:day_training=N m:row_number.ieqx-cqyk=1

series e:ieqx-cqyk d:2015-12-21T08:56:45.000Z t:supported_employment_enrollments=N t:prevocational=N t:day_treatment=N t:phone=718-276-6101 t:service_provider="EIHAB HUMAN SERVICES  INC." t:zip_code=11434 t:consolidated_supports_and_services=N t:senior_geriatric_services=N t:developmental_centers_and_special_population_services=N t:state=NY t:intermediate_care_facilities_icf_s=N t:care_at_home_waiver_services=N t:family_support_services=Y t:url=http://www.eihab.org t:city="SPRINGFIELD GARDENS" t:work_shop=N t:individual_support_services_iss=N t:developmental_disability_services_office="BERNARD M. FINESON DDSO" t:family_care=N t:county=QUEENS t:community_habilitation=Y t:individual_residential_alternative_ira=Y t:street_address="168-18 SOUTH CONDUIT AVENUE" t:day_habilitation=Y t:day_training=N m:row_number.ieqx-cqyk=2

series e:ieqx-cqyk d:2015-12-21T08:56:45.000Z t:supported_employment_enrollments=N t:prevocational=N t:day_treatment=N t:phone=718-899-8800 t:service_provider="LEXINGTON CENTER  INC." t:zip_code=11370 t:consolidated_supports_and_services=N t:senior_geriatric_services=N t:developmental_centers_and_special_population_services=N t:state=NY t:intermediate_care_facilities_icf_s=N t:care_at_home_waiver_services=N t:family_support_services=Y t:url=http://lexnyc.org t:city="JACKSON HEIGHTS" t:work_shop=N t:individual_support_services_iss=N t:developmental_disability_services_office="BERNARD M. FINESON DDSO" t:family_care=N t:county=QUEENS t:community_habilitation=N t:individual_residential_alternative_ira=N t:street_address="30TH AVENUE AND 75TH STREET" t:day_habilitation=N t:day_training=N m:row_number.ieqx-cqyk=3
```

## Meta Commands

```ls
metric m:row_number.ieqx-cqyk p:long l:"Row Number"

entity e:ieqx-cqyk l:"Directory of Developmental Disabilities Service Provider Agencies" t:attribution="New York State Office for People With Developmental Disabilities (NYS OPWDD)" t:url=https://data.ny.gov/api/views/ieqx-cqyk

property e:ieqx-cqyk t:meta.view v:id=ieqx-cqyk v:category="Human Services" v:attributionLink=http://providerdirectory.opwdd.ny.gov/ v:averageRating=0 v:name="Directory of Developmental Disabilities Service Provider Agencies" v:attribution="New York State Office for People With Developmental Disabilities (NYS OPWDD)"

property e:ieqx-cqyk t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:ieqx-cqyk t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:ieqx-cqyk t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| :updated_at | developmental_disability_services_office | service_provider                      | street_address              | street_address_line_2 | city                | state | zip_code | phone        | county | url                           | intermediate_care_facilities_icf_s | individual_residential_alternative_ira | family_care | consolidated_supports_and_services | individual_support_services_iss | day_training | day_treatment | senior_geriatric_services | day_habilitation | work_shop | prevocational | supported_employment_enrollments | community_habilitation | family_support_services | care_at_home_waiver_services | developmental_centers_and_special_population_services | 
| =========== | ======================================== | ===================================== | =========================== | ===================== | =================== | ===== | ======== | ============ | ====== | ============================= | ================================== | ====================================== | =========== | ================================== | =============================== | ============ | ============= | ========================= | ================ | ========= | ============= | ================================ | ====================== | ======================= | ============================ | ===================================================== | 
| 1450688205  | BERNARD M. FINESON DDSO                  | 0230 - BERNARD M. FINESON DDSO        | P.O. BOX 280507             | 80-45 WINCHESTER BLVD | QUEENS VILLAGE      | NY    | 11428    | 718-217-4242 | QUEENS | [null, null]                  | N                                  | Y                                      | Y           | N                                  | N                               | N            | N             | N                         | Y                | N         | N             | N                                | N                      | N                       | Y                            | Y                                                     | 
| 1450688205  | BERNARD M. FINESON DDSO                  | EIHAB HUMAN SERVICES INC.             | 168-18 SOUTH CONDUIT AVENUE |                       | SPRINGFIELD GARDENS | NY    | 11434    | 718-276-6101 | QUEENS | [http://www.eihab.org, null]  | N                                  | Y                                      | N           | N                                  | N                               | N            | N             | N                         | Y                | N         | N             | N                                | Y                      | Y                       | N                            | N                                                     | 
| 1450688205  | BERNARD M. FINESON DDSO                  | LEXINGTON CENTER INC.                 | 30TH AVENUE AND 75TH STREET |                       | JACKSON HEIGHTS     | NY    | 11370    | 718-899-8800 | QUEENS | [http://lexnyc.org, null]     | N                                  | N                                      | N           | N                                  | N                               | N            | N             | N                         | N                | N         | N             | N                                | N                      | Y                       | N                            | N                                                     | 
| 1450688205  | BERNARD M. FINESON DDSO                  | LEXINGTON VOCATIONAL SERVICES CTR INC | 30TH AVENUE AND 75TH STREET |                       | JACKSON HEIGHTS     | NY    | 11370    | 718-350-3110 | QUEENS | [http://www.lexnyc.org, null] | N                                  | N                                      | N           | N                                  | N                               | N            | N             | N                         | N                | N         | N             | Y                                | N                      | N                       | N                            | N                                                     | 
| 1450688205  | BERNARD M. FINESON DDSO                  | NEW HORIZON COUNSELING CENTER INC.    | 718-720 BEACH 20TH STREET   |                       | FAR ROCKAWAY        | NY    | 11691    | 718-327-3180 | QUEENS | [http://www.nhcc.us, null]    | N                                  | N                                      | N           | N                                  | N                               | N            | N             | N                         | Y                | N         | Y             | N                                | Y                      | Y                       | N                            | N                                                     | 
| 1450688205  | BROOKLYN DDSO                            | ADULT RESOURCES CENTER INC (DBA ARC)  | 1145 EAST 55 STREET         |                       | BROOKLYN            | NY    | 11234    | 718-531-7500 | KINGS  | [http://www.arcny.org, null]  | N                                  | Y                                      | N           | N                                  | N                               | N            | N             | N                         | N                | N         | N             | N                                | N                      | N                       | N                            | N                                                     | 
| 1450688205  | BROOKLYN DDSO                            | ADULT RESOURCES CENTER INC. (DBA ARC) | 1145 EAST 55 STREET         |                       | BROOKLYN            | NY    | 11234    |              | KINGS  | [http://www.arcny.org, null]  | N                                  | Y                                      | N           | N                                  | N                               | N            | N             | N                         | N                | N         | N             | N                                | N                      | N                       | N                            | N                                                     | 
| 1450688205  | BROOKLYN DDSO                            | ADULT RESOURCES CENTER INC. (DBA ARC) | 1145 EAST 55 STREET         |                       | BROOKLYN            | NY    | 11234    | 718-531-7500 | KINGS  | [http://www.arcny.org, null]  | N                                  | Y                                      | N           | N                                  | N                               | N            | N             | N                         | N                | N         | N             | N                                | N                      | N                       | N                            | N                                                     | 
| 1450688205  | BROOKLYN DDSO                            | ADULT RESOURCES CENTER INC. (DBA ARC) | 1145 EAST 55 STREET         |                       | BROOKLYN            | NY    | 11234    | 718-531-7500 | KINGS  | [http://www.arcny.org, null]  | Y                                  | Y                                      | N           | N                                  | N                               | N            | N             | N                         | N                | N         | N             | N                                | N                      | N                       | N                            | N                                                     | 
| 1450688205  | BROOKLYN DDSO                            | BROOKLYN CHINESE AMERICAN ASSOCIATION | 5000                        |                       | BROOKLYN            | NY    | 11220    | 718-438-0008 | KINGS  | [null, null]                  | N                                  | N                                      | N           | N                                  | N                               | N            | N             | N                         | N                | N         | N             | N                                | N                      | Y                       | N                            | N                                                     | 
```