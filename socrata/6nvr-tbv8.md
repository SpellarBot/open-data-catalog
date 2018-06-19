# Local Mental Health Programs

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/local-mental-health-programs) |
| Metadata | [Link](https://data.ny.gov/api/views/6nvr-tbv8) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/6nvr-tbv8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/6nvr-tbv8/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | 6nvr-tbv8 |
| Name | Local Mental Health Programs |
| Attribution | New York State Office of Mental Health |
| Category | Human Services |
| Tags | emergency services, inpatient services, outpatient services, support programs |
| Created | 2013-03-01T17:21:10Z |
| Publication Date | 2017-01-26T23:15:10Z |

## Description

Includes programs that are licensed by the Office of Mental Health (OMH) and programs that are funded by OMH but do not need a license to operate.

## Columns

```ls
| Included | Schema Type    | Field Name                      | Name                            | Data Type     | Render Type   |
| ======== | ============== | =============================== | =============================== | ============= | ============= |
| Yes      | time           | row_created_date_time           | Row Created Date Time           | calendar_date | calendar_date |
| Yes      | series tag     | sponsor_name                    | Sponsor Name                    | text          | text          |
| Yes      | series tag     | sponsor_code                    | Sponsor Code                    | text          | text          |
| Yes      | series tag     | agency_name                     | Agency Name                     | text          | text          |
| Yes      | series tag     | agency_code                     | Agency Code                     | text          | text          |
| Yes      | series tag     | facility_name                   | Facility Name                   | text          | text          |
| Yes      | series tag     | facility_code                   | Facility Code                   | text          | text          |
| Yes      | series tag     | program_name                    | Program Name                    | text          | text          |
| Yes      | series tag     | program_code                    | Program Code                    | text          | text          |
| Yes      | series tag     | populations_served              | Populations Served              | text          | text          |
| Yes      | series tag     | agency_phone                    | Agency Phone                    | text          | text          |
| Yes      | series tag     | program_phone                   | Program Phone                   | text          | text          |
| No       |                | program_address_1               | Program Address 1               | text          | text          |
| No       |                | program_address_2               | Program Address 2               | text          | text          |
| Yes      | series tag     | program_city                    | Program City                    | text          | text          |
| Yes      | series tag     | program_state                   | Program State                   | text          | text          |
| Yes      | series tag     | program_zip                     | Program Zip                     | text          | text          |
| Yes      | series tag     | operating_certificate_required  | Operating Certificate Required? | text          | text          |
| Yes      | numeric metric | program_tier                    | Program Tier                    | number        | number        |
| Yes      | numeric metric | operating_certificate_duration  | Operating Certificate Duration  | number        | number        |
| Yes      | series tag     | program_county                  | Program County                  | text          | text          |
| Yes      | series tag     | program_region                  | Program Region                  | text          | text          |
| Yes      | series tag     | program_type_description        | Program Type Description        | text          | text          |
| Yes      | series tag     | program_category_description    | Program Category Description    | text          | text          |
| Yes      | series tag     | program_subcategory_description | Program Subcategory Description | text          | text          |
```

## Time Field

```ls
Value = row_created_date_time
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = program_address_1,program_address_2
```

## Data Commands

```ls
series e:6nvr-tbv8 d:2017-01-18T12:10:41.000Z t:agency_phone=(718)960-7601 t:program_code=001 t:program_category_description=Residential t:program_phone="Not Available" t:program_name="PROMESA Bronx II Apartment Community Residence" t:operating_certificate_required=Y t:facility_code=8157 t:agency_name="PROMESA Inc." t:program_type_description=Apartment/Treatment t:program_region="New York City" t:program_subcategory_description="Treatment Program" t:facility_name="PROMESA Inc." t:program_county=Bronx t:sponsor_name="Acacia Network Inc." t:program_state=NY t:populations_served=Adults t:sponsor_code=000288 t:agency_code=00166 m:program_tier=1 m:operating_certificate_duration=36

series e:6nvr-tbv8 d:2017-01-18T12:10:41.000Z t:agency_phone=(518)427-5056 t:program_code=430 t:program_category_description=Residential t:program_phone="Not Available" t:program_name="Clinton Avenue Apartment Program" t:operating_certificate_required=Y t:facility_code=8632 t:agency_name="Capital Area Peer Services" t:program_type_description=Apartment/Support t:program_region="Hudson River" t:program_subcategory_description="Support Program" t:facility_name="Capital Area Peer Services" t:program_county=Albany t:sponsor_name="Capital Area Peer Services" t:program_state=NY t:populations_served=Adults t:sponsor_code=630099 t:agency_code=11620 m:program_tier=1 m:operating_certificate_duration=36

series e:6nvr-tbv8 d:2017-01-18T12:10:41.000Z t:agency_phone=(518)549-6000 t:program_code=861 t:program_category_description=Residential t:program_phone="Not Available" t:program_name="Jansen House" t:operating_certificate_required=Y t:facility_code=0024 t:agency_name="Capital District Psychiatric Center" t:program_type_description=Congregate/Treatment t:program_region="Hudson River" t:program_subcategory_description="Treatment Program" t:facility_name="Capital District Psychiatric Center" t:program_county=Albany t:sponsor_name="Capital District Psychiatric Center" t:program_state=NY t:populations_served=Adults t:sponsor_code=072099 t:agency_code=90200 m:program_tier=1 m:operating_certificate_duration=36
```

## Meta Commands

```ls
metric m:program_tier p:integer l:"Program Tier" d:"Certification Tier - I is highest and III is lowest. Does not apply to all programs" t:dataTypeName=number

metric m:operating_certificate_duration p:integer l:"Operating Certificate Duration" d:Ranges t:dataTypeName=number

entity e:6nvr-tbv8 l:"Local Mental Health Programs" t:attribution="New York State Office of Mental Health" t:url=https://data.ny.gov/api/views/6nvr-tbv8

property e:6nvr-tbv8 t:meta.view v:id=6nvr-tbv8 v:category="Human Services" v:attributionLink=http://bi.omh.ny.gov/bridges/index v:averageRating=0 v:name="Local Mental Health Programs" v:attribution="New York State Office of Mental Health"

property e:6nvr-tbv8 t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:6nvr-tbv8 t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:6nvr-tbv8 t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| row_created_date_time | sponsor_name                        | sponsor_code | agency_name                         | agency_code | facility_name                       | facility_code | program_name                                                | program_code | populations_served | agency_phone  | program_phone | program_address_1 | program_address_2 | program_city | program_state | program_zip | operating_certificate_required | program_tier | operating_certificate_duration | program_county | program_region | program_type_description             | program_category_description | program_subcategory_description | 
| ===================== | =================================== | ============ | =================================== | =========== | =================================== | ============= | =========================================================== | ============ | ================== | ============= | ============= | ================= | ================= | ============ | ============= | =========== | ============================== | ============ | ============================== | ============== | ============== | ==================================== | ============================ | =============================== | 
| 2017-01-18T12:10:41   | Acacia Network Inc.                 | 000288       | PROMESA Inc.                        | 00166       | PROMESA Inc.                        | 8157          | PROMESA Bronx II Apartment Community Residence              | 001          | Adults             | (718)960-7601 | Not Available |                   |                   |              | NY            |             | Y                              | 1            | 36                             | Bronx          | New York City  | Apartment/Treatment                  | Residential                  | Treatment Program               | 
| 2017-01-18T12:10:41   | Capital Area Peer Services          | 630099       | Capital Area Peer Services          | 11620       | Capital Area Peer Services          | 8632          | Clinton Avenue Apartment Program                            | 430          | Adults             | (518)427-5056 | Not Available |                   |                   |              | NY            |             | Y                              | 1            | 36                             | Albany         | Hudson River   | Apartment/Support                    | Residential                  | Support Program                 | 
| 2017-01-18T12:10:41   | Capital District Psychiatric Center | 072099       | Capital District Psychiatric Center | 90200       | Capital District Psychiatric Center | 0024          | Jansen House                                                | 861          | Adults             | (518)549-6000 | Not Available |                   |                   |              | NY            |             | Y                              | 1            | 36                             | Albany         | Hudson River   | Congregate/Treatment                 | Residential                  | Treatment Program               | 
| 2017-01-18T12:10:41   | Capital District Psychiatric Center | 072099       | Capital District Psychiatric Center | 90200       | Capital District Psychiatric Center | 0024          | New Scotland Residence TPP                                  | 235          | Adults             | (518)549-6000 | Not Available |                   |                   |              | NY            |             | Y                              | 1            | 36                             | Albany         | Hudson River   | Congregate/Treatment                 | Residential                  | Treatment Program               | 
| 2017-01-18T12:10:41   | Equinox Inc.                        | 280099       | Equinox Inc.                        | 14510       | Equinox Inc.                        | 7524          | Clearview Supp Housing/PC Long Stay Albany County-Comm Svcs | 631          | Adults             | (518)435-9931 | Not Available |                   |                   |              | NY            |             | N                              |              |                                | Albany         | Hudson River   | Supported Housing Community Services | Residential                  | Unlicensed Housing              | 
| 2017-01-18T12:10:41   | Equinox Inc.                        | 280099       | Equinox Inc.                        | 14510       | Equinox Inc.                        | 7524          | Cohoes Community Residence                                  | 430          | Adults             | (518)435-9931 | Not Available |                   |                   |              | NY            |             | Y                              | 1            | 36                             | Albany         | Hudson River   | Congregate/Treatment                 | Residential                  | Treatment Program               | 
| 2017-01-18T12:10:41   | Equinox Inc.                        | 280099       | Equinox Inc.                        | 14510       | Equinox Inc.                        | 7524          | Equinox Apartment Program                                   | 432          | Adults             | (518)435-9931 | Not Available |                   |                   |              | NY            |             | Y                              | 1            | 36                             | Albany         | Hudson River   | Apartment/Treatment                  | Residential                  | Treatment Program               | 
| 2017-01-18T12:10:41   | Equinox Inc.                        | 280099       | Equinox Inc.                        | 14510       | Equinox Inc.                        | 7524          | Holt House                                                  | 433          | Adults             | (518)435-9931 | Not Available |                   |                   |              | NY            |             | Y                              | 1            | 36                             | Albany         | Hudson River   | Congregate/Treatment                 | Residential                  | Treatment Program               | 
| 2017-01-18T12:10:41   | Equinox Inc.                        | 280099       | Equinox Inc.                        | 14510       | Equinox Inc.                        | 7524          | Recovery Residence                                          | 434          | Adults             | (518)435-9931 | Not Available |                   |                   |              | NY            |             | Y                              | 1            | 36                             | Albany         | Hudson River   | Congregate/Treatment                 | Residential                  | Treatment Program               | 
| 2017-01-18T12:10:41   | Homeless and Travelers Aid Society  | 631099       | Homeless and Travelers Aid Society  | 17630       | Homeless and Travelers Aid Society  | 8906          | HATAS Supp Hsing/STP Forensic Albany Cty - Comm Svcs        | 631          | Adults             | (518)463-2124 | Not Available |                   |                   |              | NY            |             | N                              |              |                                | Albany         | Hudson River   | Supported Housing Community Services | Residential                  | Unlicensed Housing              | 
```