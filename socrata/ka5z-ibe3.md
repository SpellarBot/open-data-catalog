# Inpatient Rehabilitation Facility - Conditions

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/inpatient-rehabilitation-facility-conditions) |
| Metadata | [Link](https://data.medicare.gov/api/views/ka5z-ibe3) |
| Data: JSON | [100 Rows](https://data.medicare.gov/api/views/ka5z-ibe3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.medicare.gov/api/views/ka5z-ibe3/rows.csv?max_rows=100) |
| Host | data.medicare.gov |
| Id | ka5z-ibe3 |
| Name | Inpatient Rehabilitation Facility - Conditions |
| Category | Inpatient Rehabilitation Facility Compare |
| Tags | inpatient rehabilitation facilities, inpatient rehabilitation facility, rehabilitation |
| Created | 2016-03-28T17:47:40Z |
| Publication Date | 2017-03-21T01:12:42Z |

## Description

A list of inpatient rehabilitation facilities with data on the number of times people with Medicare who had certain medical conditions were treated in the last year.

## Columns

```ls
| Included | Schema Type    | Field Name                   | Name                           | Data Type | Render Type |
| ======== | ============== | ============================ | ============================== | ========= | =========== |
| No       | time           | :updated_at                  | updated_at                     | meta_data | meta_data   |
| Yes      | series tag     | cms_certification_number_ccn | CMS Certification Number (CCN) | text      | text        |
| Yes      | series tag     | facility_name                | Facility Name                  | text      | text        |
| No       |                | address_line_1               | Address Line 1                 | text      | text        |
| No       |                | address_line_2               | Address Line 2                 | text      | text        |
| Yes      | series tag     | city                         | City                           | text      | text        |
| Yes      | series tag     | state                        | State                          | text      | text        |
| Yes      | series tag     | zip_code                     | Zip Code                       | text      | text        |
| Yes      | series tag     | county_name                  | County Name                    | text      | text        |
| Yes      | series tag     | phonenumber                  | PhoneNumber                    | phone     | phone       |
| Yes      | numeric metric | cms_region                   | CMS Region                     | number    | number      |
| Yes      | series tag     | condition                    | Condition                      | text      | text        |
| Yes      | series tag     | count                        | Count                          | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address_line_1,address_line_2
```

## Data Commands

```ls
series e:ka5z-ibe3 d:2017-02-14T17:03:19.000Z t:cms_certification_number_ccn=013029 t:phone_number="(205) 535-2300" t:facility_name="HEALTHSOUTH REHABILITATION HOSPITAL OF NORTH AL" t:count=180 t:zip_code=35801 t:condition="Nervous system disorder (excluding stroke)" t:state=AL t:county_name=Madison t:city=HUNTSVILLE m:cms_region=4

series e:ka5z-ibe3 d:2017-02-14T17:03:19.000Z t:cms_certification_number_ccn=013025 t:phone_number="(205) 868-2000" t:facility_name="HEALTHSOUTH LAKESHORE REHABILITATION HOSPITAL" t:count=238 t:zip_code=35209 t:condition="All other conditions" t:state=AL t:county_name=Jefferson t:city=BIRMINGHAM m:cms_region=4

series e:ka5z-ibe3 d:2017-02-14T17:03:19.000Z t:cms_certification_number_ccn=02T001 t:phone_number="(907) 212-8458" t:facility_name="PROVIDENCE ALASKA MEDICAL CTR" t:count=26 t:zip_code=99519 t:condition="Hip or knee replacement, amputation or other bone or joint condition" t:state=AK t:county_name=Anchorage t:city=ANCHORAGE m:cms_region=10
```

## Meta Commands

```ls
metric m:cms_region p:integer l:"CMS Region" t:dataTypeName=number

entity e:ka5z-ibe3 l:"Inpatient Rehabilitation Facility - Conditions" t:url=https://data.medicare.gov/api/views/ka5z-ibe3

property e:ka5z-ibe3 t:meta.view v:id=ka5z-ibe3 v:category="Inpatient Rehabilitation Facility Compare" v:averageRating=0 v:name="Inpatient Rehabilitation Facility - Conditions"

property e:ka5z-ibe3 t:meta.view.owner v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:displayName=cms

property e:ka5z-ibe3 t:meta.view.tableauthor v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:roleName=administrator v:displayName=cms

property e:ka5z-ibe3 t:meta.view.metadata.custom_fields.common_core v:Publisher="Centers for Medicare & Medicaid Services (CMS)" v:Contact_Email=IRFQualityQuestions@cms.hhs.gov v:Contact_Name=CMS v:Bureau_Code=009:38 v:Program_Code=009:078
```

## Top Records

```ls
| :updated_at | cms_certification_number_ccn | facility_name                                   | address_line_1          | address_line_2 | city       | state | zip_code | county_name | phonenumber            | cms_region | condition                                                            | count        | 
| =========== | ============================ | =============================================== | ======================= | ============== | ========== | ===== | ======== | =========== | ====================== | ========== | ==================================================================== | ============ | 
| 1487091799  | 013029                       | HEALTHSOUTH REHABILITATION HOSPITAL OF NORTH AL | 107 GOVERNORS DRIVE     |                | HUNTSVILLE | AL    | 35801    | Madison     | [(205) 535-2300, null] | 4          | Nervous system disorder (excluding stroke)                           | 180          | 
| 1487091799  | 013025                       | HEALTHSOUTH LAKESHORE REHABILITATION HOSPITAL   | 3800 RIDGEWAY DRIVE     |                | BIRMINGHAM | AL    | 35209    | Jefferson   | [(205) 868-2000, null] | 4          | All other conditions                                                 | 238          | 
| 1487091799  | 02T001                       | PROVIDENCE ALASKA MEDICAL CTR                   | 3200 PROVIDENCE DR.     |                | ANCHORAGE  | AK    | 99519    | Anchorage   | [(907) 212-8458, null] | 10         | Hip or knee replacement, amputation or other bone or joint condition | 26           | 
| 1487091799  | 033032                       | HEALTHSOUTH VALLEY OF THE SUN REHABILITATION    | 13460 NORTH 67TH AVENUE |                | GLENDALE   | AZ    | 85304    | Maricopa    | [(623) 878-8800, null] | 9          | Hip or femur fracture                                                | 73           | 
| 1487091799  | 033032                       | HEALTHSOUTH VALLEY OF THE SUN REHABILITATION    | 13460 NORTH 67TH AVENUE |                | GLENDALE   | AZ    | 85304    | Maricopa    | [(623) 878-8800, null] | 9          | All other conditions                                                 | 151          | 
| 1487091800  | 03T011                       | CARONDELET ST JOSEPHS HOSPITAL                  | 350 N WILMOT RD         |                | TUCSON     | AZ    | 85711    | Pima        | [(520) 873-3959, null] | 9          | Spinal cord disease or condition (non-traumatic)                     | less than 11 | 
| 1487091800  | 03T011                       | CARONDELET ST JOSEPHS HOSPITAL                  | 350 N WILMOT RD         |                | TUCSON     | AZ    | 85711    | Pima        | [(520) 873-3959, null] | 9          | Hip or femur fracture                                                | 43           | 
| 1487091801  | 03T011                       | CARONDELET ST JOSEPHS HOSPITAL                  | 350 N WILMOT RD         |                | TUCSON     | AZ    | 85711    | Pima        | [(520) 873-3959, null] | 9          | Brain injury (traumatic)                                             | 19           | 
| 1487091799  | 03T024                       | ST JOSEPHS HOSP                                 | 240 W THOMAS RD         |                | PHOENIX    | AZ    | 85013    | Maricopa    | [(602) 406-4796, null] | 9          | Hip or knee replacement, amputation or other bone or joint condition | 15           | 
| 1487091800  | 03T055                       | KINGMAN REGIONAL MEDICAL CENTER                 | 3269 STOCKTON HILL RD.  |                | KINGMAN    | AZ    | 86401    | Mohave      | [(928) 263-4632, null] | 9          | Stroke                                                               | 46           | 
```