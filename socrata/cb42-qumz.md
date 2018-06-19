# Child Care Regulated Programs

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/child-care-regulated-programs) |
| Metadata | [Link](https://data.ny.gov/api/views/cb42-qumz) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/cb42-qumz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/cb42-qumz/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | cb42-qumz |
| Name | Child Care Regulated Programs |
| Attribution | NYS Office of Children and Family Services |
| Category | Human Services |
| Tags | child care, day care, violations, programs |
| Created | 2013-02-25T23:50:07Z |
| Publication Date | 2017-04-20T10:19:25Z |

## Description

Information on OCFS regulated child care programs, which includes program overview information and violation history.

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type     | Render Type   |
| ======== | ============== | ======================= | ======================= | ============= | ============= |
| Yes      | series tag     | facility_id             | Facility ID             | text          | number        |
| Yes      | series tag     | program_type            | Program Type            | text          | text          |
| Yes      | series tag     | region_code             | Region Code             | text          | text          |
| Yes      | series tag     | county                  | County                  | text          | text          |
| Yes      | series tag     | facility_status         | Facility Status         | text          | text          |
| Yes      | series tag     | facility_name           | Facility Name           | text          | text          |
| Yes      | time           | facility_opened_date    | Facility Opened Date    | calendar_date | calendar_date |
| No       |                | license_issue_date      | License Issue Date      | calendar_date | calendar_date |
| No       |                | license_expiration_date | License Expiration Date | calendar_date | calendar_date |
| No       |                | address_omitted         | Address Omitted         | text          | text          |
| Yes      | series tag     | street_number           | Street Number           | text          | text          |
| Yes      | series tag     | street_name             | Street Name             | text          | text          |
| No       |                | additional_address      | Additional Address      | text          | text          |
| Yes      | series tag     | floor                   | Floor                   | text          | text          |
| Yes      | series tag     | apartment               | Apartment               | text          | text          |
| Yes      | series tag     | city                    | City                    | text          | text          |
| Yes      | series tag     | state                   | State                   | text          | text          |
| Yes      | series tag     | zip_code                | Zip Code                | text          | number        |
| Yes      | series tag     | phone_number_omitted    | Phone Number Omitted    | text          | text          |
| Yes      | series tag     | phone_number            | Phone Number            | text          | text          |
| Yes      | series tag     | phone_extension         | Phone Extension         | text          | text          |
| Yes      | series tag     | provider_name           | Provider Name           | text          | text          |
| Yes      | series tag     | school_district_name    | School District Name    | text          | text          |
| Yes      | series tag     | capacity_description    | Capacity Description    | text          | text          |
| Yes      | numeric metric | infant_capacity         | Infant Capacity         | number        | number        |
| Yes      | numeric metric | toddler_capacity        | Toddler Capacity        | number        | number        |
| Yes      | numeric metric | preschool_capacity      | Preschool Capacity      | number        | number        |
| Yes      | numeric metric | school_age_capacity     | School Age Capacity     | number        | number        |
| Yes      | numeric metric | total_capacity          | Total Capacity          | number        | number        |
| Yes      | series tag     | additional_information  | Program Profile         | url           | url           |
| Yes      | series tag     | latitude                | Latitude                | text          | text          |
| Yes      | series tag     | longitude               | Longitude               | text          | text          |
```

## Time Field

```ls
Value = facility_opened_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = license_issue_date,license_expiration_date,address_omitted,additional_address
```

## Data Commands

```ls
series e:cb42-qumz d:1993-02-01T00:00:00.000Z t:program_type=GFDC t:phone_number=(518)869-9186 t:zip_code=122034419 t:street_name="Rapp Rd" t:state=NY t:facility_id=9 t:capacity_description="12 children, ages 6 weeks to 12 years AND 4 additional school-aged children" t:city=Albany t:school_district_name=Albany t:facility_name="First Steps" t:county=Albany t:region_code=ARO t:facility_status=License t:longitude=-73.85138 t:street_number=28 t:latitude=42.696243 t:provider_name="Janel C. Chapple" t:additional_information=http://it.ocfs.ny.gov/DayCareFacilitySearch/Profile/Index/9 m:total_capacity=16 m:preschool_capacity=0 m:school_age_capacity=4 m:infant_capacity=0 m:toddler_capacity=0

series e:cb42-qumz d:1991-10-01T00:00:00.000Z t:program_type=GFDC t:phone_number=(518)482-6864 t:zip_code=12203 t:state=NY t:facility_id=14 t:capacity_description="12 children, ages 6 weeks to 12 years AND 2 additional school-aged children" t:city=Albany t:school_district_name=Albany t:facility_name="Levine, Rosemarie" t:county=Albany t:facility_status=License t:region_code=ARO t:provider_name="Rosemarie G. Levine" t:additional_information=http://it.ocfs.ny.gov/DayCareFacilitySearch/Profile/Index/14 m:total_capacity=14 m:preschool_capacity=0 m:school_age_capacity=2 m:infant_capacity=0 m:toddler_capacity=0

series e:cb42-qumz d:1991-08-20T00:00:00.000Z t:program_type=FDC t:phone_number=(518)463-2376 t:zip_code=12210 t:street_name="Livingston Ave" t:state=NY t:facility_id=117 t:capacity_description="6 children, ages 6 weeks to 12 years AND 2 additional school-aged children" t:city=Albany t:school_district_name=Albany t:facility_name="Jackson, Lillie" t:county=Albany t:region_code=ARO t:facility_status=Registration t:longitude=-73.757313 t:street_number=262 t:latitude=42.662738 t:provider_name="Lillie M. Jackson" t:additional_information=http://it.ocfs.ny.gov/DayCareFacilitySearch/Profile/Index/117 m:total_capacity=8 m:preschool_capacity=0 m:school_age_capacity=2 m:infant_capacity=0 m:toddler_capacity=0
```

## Meta Commands

```ls
metric m:infant_capacity p:long l:"Infant Capacity" d:"For DCC, total number of children up to 18 months of age" t:dataTypeName=number

metric m:toddler_capacity p:long l:"Toddler Capacity" d:"For DCC, total number of children ages 18 months to 36 months" t:dataTypeName=number

metric m:preschool_capacity p:long l:"Preschool Capacity" d:"For DCC, total number of children at least 3 years of age who are not yet enrolled in kindergarten or a higher grade" t:dataTypeName=number

metric m:school_age_capacity p:long l:"School Age Capacity" d:"For DCC and SACC, total number of children who are under 13 years of age who are enrolled in kindergarten or a higher grade" t:dataTypeName=number

metric m:total_capacity p:long l:"Total Capacity" d:"Refer to the data dictionary found in the About tab for the definition of Total Capacity." t:dataTypeName=number

entity e:cb42-qumz l:"Child Care Regulated Programs" t:attribution="NYS Office of Children and Family Services" t:url=https://data.ny.gov/api/views/cb42-qumz

property e:cb42-qumz t:meta.view v:id=cb42-qumz v:category="Human Services" v:attributionLink=http://www.ocfs.state.ny.us/main/childcare/default.asp v:averageRating=0 v:name="Child Care Regulated Programs" v:attribution="NYS Office of Children and Family Services"

property e:cb42-qumz t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:cb42-qumz t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:cb42-qumz t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| facility_id | program_type | region_code | county  | facility_status | facility_name              | facility_opened_date | license_issue_date  | license_expiration_date | address_omitted | street_number | street_name    | additional_address | floor | apartment | city         | state | zip_code  | phone_number_omitted | phone_number  | phone_extension | provider_name                | school_district_name | capacity_description                                                        | infant_capacity | toddler_capacity | preschool_capacity | school_age_capacity | total_capacity | additional_information                                                | latitude    | longitude   | 
| =========== | ============ | =========== | ======= | =============== | ========================== | ==================== | =================== | ======================= | =============== | ============= | ============== | ================== | ===== | ========= | ============ | ===== | ========= | ==================== | ============= | =============== | ============================ | ==================== | =========================================================================== | =============== | ================ | ================== | =================== | ============== | ===================================================================== | =========== | =========== | 
| 9           | GFDC         | ARO         | Albany  | License         | First Steps                | 1993-02-01T00:00:00  | 2016-02-01T00:00:00 | 2020-01-31T00:00:00     |                 | 28            | Rapp Rd        |                    |       |           | Albany       | NY    | 122034419 |                      | (518)869-9186 |                 | Janel C. Chapple             | Albany               | 12 children, ages 6 weeks to 12 years AND 4 additional school-aged children | 0               | 0                | 0                  | 4                   | 16             | [http://it.ocfs.ny.gov/DayCareFacilitySearch/Profile/Index/9, null]   | 42.696243   | -73.85138   | 
| 14          | GFDC         | ARO         | Albany  | License         | Levine, Rosemarie          | 1991-10-01T00:00:00  | 2015-10-01T00:00:00 | 2019-09-30T00:00:00     | Y               |               |                |                    |       |           | Albany       | NY    | 12203     |                      | (518)482-6864 |                 | Rosemarie G. Levine          | Albany               | 12 children, ages 6 weeks to 12 years AND 2 additional school-aged children | 0               | 0                | 0                  | 2                   | 14             | [http://it.ocfs.ny.gov/DayCareFacilitySearch/Profile/Index/14, null]  |             |             | 
| 117         | FDC          | ARO         | Albany  | Registration    | Jackson, Lillie            | 1991-08-20T00:00:00  | 2014-08-20T00:00:00 | 2018-08-19T00:00:00     |                 | 262           | Livingston Ave |                    |       |           | Albany       | NY    | 12210     |                      | (518)463-2376 |                 | Lillie M. Jackson            | Albany               | 6 children, ages 6 weeks to 12 years AND 2 additional school-aged children  | 0               | 0                | 0                  | 2                   | 8              | [http://it.ocfs.ny.gov/DayCareFacilitySearch/Profile/Index/117, null] | 42.662738   | -73.757313  | 
| 143         | FDC          | ARO         | Albany  | Registration    | Terpening- Langan, Theresa | 1990-09-01T00:00:00  | 2014-09-01T00:00:00 | 2018-08-31T00:00:00     |                 | Five          | Pollack Road   |                    |       |           | Latham       | NY    | 12110     |                      | (518)786-1041 |                 | Theresa A. Terpening- Langan | North Colonie        | 6 children, ages 6 weeks to 12 years AND 2 additional school-aged children  | 0               | 0                | 0                  | 2                   | 8              | [http://it.ocfs.ny.gov/DayCareFacilitySearch/Profile/Index/143, null] | 42.768268   | -73.779596  | 
| 193         | GFDC         | ARO         | Albany  | License         | JoJo Child Care Services   | 1991-07-01T00:00:00  | 2014-07-01T00:00:00 | 2018-06-30T00:00:00     | Y               |               |                |                    |       |           | Albany       | NY    | 12203     |                      | (518)452-6306 |                 | Josephine Otitigbe           | Albany               | 12 children, ages 6 weeks to 12 years AND 4 additional school-aged children | 0               | 0                | 0                  | 4                   | 16             | [http://it.ocfs.ny.gov/DayCareFacilitySearch/Profile/Index/193, null] |             |             | 
| 215         | FDC          | SRO         | Broome  | Registration    | Montemagno, Lois           | 1990-12-01T00:00:00  | 2015-12-01T00:00:00 | 2019-11-30T00:00:00     | Y               |               |                |                    |       |           | Binghamton   | NY    | 13901     |                      | (607)722-2541 |                 | Lois A. Montemagno           | Chenango Valley      | 6 children, ages 6 weeks to 12 years AND 2 additional school-aged children  | 0               | 0                | 0                  | 2                   | 8              | [http://it.ocfs.ny.gov/DayCareFacilitySearch/Profile/Index/215, null] |             |             | 
| 228         | FDC          | SRO         | Broome  | Registration    | A Child's Garden Day Care  | 1990-10-01T00:00:00  | 2015-08-01T00:00:00 | 2019-07-31T00:00:00     |                 | 28            | Frederick St.  |                    |       | Apt. 1    | Johnson City | NY    | 13790     |                      | (607)798-7780 |                 | Carolyn M. Headrick          | Johnson City         | 6 children, ages 6 weeks to 12 years AND 2 additional school-aged children  | 0               | 0                | 0                  | 2                   | 8              | [http://it.ocfs.ny.gov/DayCareFacilitySearch/Profile/Index/228, null] | 42.116655   | -75.974643  | 
| 318         | FDC          | SRO         | Cayuga  | Registration    | Fey, Linda                 | 1991-10-28T00:00:00  | 2015-12-01T00:00:00 | 2019-11-30T00:00:00     | Y               |               |                |                    |       |           | Weedsport    | NY    | 131669634 |                      | (315)834-9691 |                 | Linda G. Fey                 | Weedsport            | 6 children, ages 6 weeks to 12 years AND 2 additional school-aged children  | 0               | 0                | 0                  | 2                   | 8              | [http://it.ocfs.ny.gov/DayCareFacilitySearch/Profile/Index/318, null] |             |             | 
| 440         | FDC          | ARO         | Clinton | Registration    | Woodward, Mary             | 1989-07-05T00:00:00  | 2015-03-22T00:00:00 | 2019-03-21T00:00:00     |                 | 218           | Sharron Ave    |                    |       |           | Plattsburgh  | NY    | 12901     |                      | (518)561-3227 |                 | Mary E. Woodward             | Plattsburgh          | 6 children, ages 6 weeks to 12 years AND 2 additional school-aged children  | 0               | 0                | 0                  | 2                   | 8              | [http://it.ocfs.ny.gov/DayCareFacilitySearch/Profile/Index/440, null] | 44.672866   | -73.462128  | 
| 486         | GFDC         | ARO         | Clinton | License         | Boulerice, Catherine       | 1990-01-01T00:00:00  | 2015-12-31T00:00:00 | 2019-12-30T00:00:00     |                 | 289           | Route 276      |                    |       |           | Champlain    | NY    | 129194837 |                      | (518)298-2861 |                 | Catherine C. Boulerice       | Northeastern Clinton | 12 children, ages 6 weeks to 12 years AND 4 additional school-aged children | 0               | 0                | 0                  | 4                   | 16             | [http://it.ocfs.ny.gov/DayCareFacilitySearch/Profile/Index/486, null] | 45.00078481 | -73.4057482 | 
```