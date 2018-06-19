# Long- Term Care Hospital - General Information

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/long-term-care-hospital-general-information) |
| Metadata | [Link](https://data.medicare.gov/api/views/azum-44iv) |
| Data: JSON | [100 Rows](https://data.medicare.gov/api/views/azum-44iv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.medicare.gov/api/views/azum-44iv/rows.csv?max_rows=100) |
| Host | data.medicare.gov |
| Id | azum-44iv |
| Name | Long- Term Care Hospital - General Information |
| Category | Long-Term Care Hospital Compare |
| Tags | long term care hospital, hospital |
| Created | 2016-03-29T14:13:27Z |
| Publication Date | 2017-03-21T01:11:36Z |

## Description

A list of long-term care hospitals with information such as address, phone number, ownership data and more.

## Columns

```ls
| Included | Schema Type    | Field Name                   | Name                           | Data Type     | Render Type   |
| ======== | ============== | ============================ | ============================== | ============= | ============= |
| Yes      | series tag     | cms_certification_number_ccn | CMS Certification Number (CCN) | text          | text          |
| Yes      | series tag     | facility_name                | Facility Name                  | text          | text          |
| No       |                | address_line_1               | Address Line 1                 | text          | text          |
| No       |                | address_line_2               | Address Line 2                 | text          | text          |
| Yes      | series tag     | city                         | City                           | text          | text          |
| Yes      | series tag     | state                        | State                          | text          | text          |
| Yes      | series tag     | zip_code                     | Zip Code                       | text          | text          |
| Yes      | series tag     | county_name                  | County Name                    | text          | text          |
| Yes      | series tag     | phonenumber                  | PhoneNumber                    | text          | text          |
| Yes      | numeric metric | cms_region                   | CMS Region                     | number        | number        |
| Yes      | series tag     | ownership_type               | Ownership Type                 | text          | text          |
| Yes      | time           | certification_date           | Certification Date             | calendar_date | calendar_date |
| Yes      | numeric metric | total_number_of_beds         | Total Number of Beds           | number        | number        |
```

## Time Field

```ls
Value = certification_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = address_line_1,address_line_2
```

## Data Commands

```ls
series e:azum-44iv d:2007-07-01T00:00:00.000Z t:cms_certification_number_ccn=462005 t:phonenumber="(801) 226-8880" t:ownership_type="For profit" t:facility_name="UTAH VALLEY SPECIALTY HOSPITAL" t:zip_code=84604 t:state=UT t:county_name=Utah t:city=PROVO m:cms_region=8 m:total_number_of_beds=40

series e:azum-44iv d:2009-03-01T00:00:00.000Z t:cms_certification_number_ccn=322004 t:phonenumber="(575) 521-6600" t:ownership_type=Government t:facility_name="ADVANCED CARE HOSPITAL OF SOUTHERN NEW MEXICO LLC" t:zip_code=88011 t:state=NM t:county_name="Dona Ana" t:city="LAS CRUCES" m:cms_region=6 m:total_number_of_beds=20

series e:azum-44iv d:2003-11-25T00:00:00.000Z t:cms_certification_number_ccn=042009 t:phonenumber="(479) 713-7000" t:ownership_type="For profit" t:facility_name="REGENCY HOSPITAL OF NORTHWEST ARKANSAS" t:zip_code=72764 t:state=AR t:county_name=Washington t:city=SPRINGDALE m:cms_region=6 m:total_number_of_beds=50
```

## Meta Commands

```ls
metric m:cms_region p:integer l:"CMS Region" t:dataTypeName=number

metric m:total_number_of_beds p:integer l:"Total Number of Beds" t:dataTypeName=number

entity e:azum-44iv l:"Long- Term Care Hospital - General Information" t:url=https://data.medicare.gov/api/views/azum-44iv

property e:azum-44iv t:meta.view v:id=azum-44iv v:category="Long-Term Care Hospital Compare" v:averageRating=0 v:name="Long- Term Care Hospital - General Information"

property e:azum-44iv t:meta.view.owner v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:displayName=cms

property e:azum-44iv t:meta.view.tableauthor v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:roleName=administrator v:displayName=cms

property e:azum-44iv t:meta.view.metadata.custom_fields.common_core v:Publisher="Centers for Medicare & Medicaid Services (CMS)" v:Contact_Email=LTCHQualityQuestions@cms.hhs.gov v:Contact_Name=CMS v:Bureau_Code=009:38 v:Program_Code=009:078
```

## Top Records

```ls
| cms_certification_number_ccn | facility_name                                      | address_line_1                                    | address_line_2 | city             | state | zip_code | county_name | phonenumber    | cms_region | ownership_type | certification_date  | total_number_of_beds | 
| ============================ | ================================================== | ================================================= | ============== | ================ | ===== | ======== | =========== | ============== | ========== | ============== | =================== | ==================== | 
| 462005                       | UTAH VALLEY SPECIALTY HOSPITAL                     | 306 WEST RIVER BEND LANE                          |                | PROVO            | UT    | 84604    | Utah        | (801) 226-8880 | 8          | For profit     | 2007-07-01T00:00:00 | 40                   | 
| 322004                       | ADVANCED CARE HOSPITAL OF SOUTHERN NEW MEXICO LLC  | 4451 EAST LOHMAN AVENUE                           |                | LAS CRUCES       | NM    | 88011    | Dona Ana    | (575) 521-6600 | 6          | Government     | 2009-03-01T00:00:00 | 20                   | 
| 042009                       | REGENCY HOSPITAL OF NORTHWEST ARKANSAS             | 609 WEST MAPLE AVENUE                             |                | SPRINGDALE       | AR    | 72764    | Washington  | (479) 713-7000 | 6          | For profit     | 2003-11-25T00:00:00 | 50                   | 
| 362029                       | REGENCY HOSPITAL OF CLEVELAND EAST                 | 4200 INTERCHANGE CORPORATE CENTER ROAD            |                | WARRENSVILLE HTS | OH    | 44128    | Cuyahoga    | (330) 861-2065 | 5          | For profit     | 2002-12-01T00:00:00 | 142                  | 
| 522007                       | LIFECARE HOSPITALS OF WISCONSIN                    | 2400 GOLF ROAD                                    |                | PEWAUKEE         | WI    | 53072    | Waukesha    | (262) 524-2600 | 5          | For profit     | 2001-02-01T00:00:00 | 17                   | 
| 392047                       | SELECT SPECIALTY HOSPITAL - DANVILLE               | 100 NORTH ACADEMY AVENUE 3RD FLR BUSH & GEISINGER |                | DANVILLE         | PA    | 17822    | Montour     | (570) 214-9648 | 3          | For profit     | 2005-02-01T00:00:00 | 30                   | 
| 392039                       | SELECT SPECIALTY HOSPITAL - CENTRAL PA (CAMP HILL) | 503 NORTH 21ST STREET, FIFTH FLOOR                |                | CAMP HILL        | PA    | 17011    | Cumberland  | (717) 972-4560 | 3          | For profit     | 2002-01-01T00:00:00 | 31                   | 
| 452043                       | PINE VALLEY SPECIALTY HOSPITAL                     | 6160 S LOOP EAST                                  |                | HOUSTON          | TX    | 77087    | Harris      | (713) 640-2400 | 6          | For profit     | 1994-09-01T00:00:00 | 59                   | 
| 452112                       | ICON HOSPITAL                                      | 19211 MCKAY BLVD                                  |                | HUMBLE           | TX    | 77338    | Harris      | (704) 887-7283 | 6          | For profit     | 2009-02-01T00:00:00 | 54                   | 
| 072004                       | HOSPITAL FOR SPECIAL CARE                          | 2150 CORBIN AVE                                   |                | NEW BRITAIN      | CT    | 06050    | Hartford    | (860) 223-2761 | 1          | Non-profit     | 1966-07-01T00:00:00 | 228                  | 
```