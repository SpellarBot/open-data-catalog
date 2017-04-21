# Long- Term Care Hospital - Provider Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/long-term-care-hospital-provider-data) |
| Metadata | [Link](https://data.medicare.gov/api/views/fp6g-2gsn) |
| Data: JSON | [100 Rows](https://data.medicare.gov/api/views/fp6g-2gsn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.medicare.gov/api/views/fp6g-2gsn/rows.csv?max_rows=100) |
| Host | data.medicare.gov |
| Id | fp6g-2gsn |
| Name | Long- Term Care Hospital - Provider Data |
| Category | Long-Term Care Hospital Compare |
| Tags | long term care hospital, hospital |
| Created | 2016-03-29T14:17:23Z |
| Publication Date | 2017-03-21T01:11:42Z |

## Description

A list of long-term care hospitals with data on the quality of patient care measures shown on Long-Term Care Hospital Compare.

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
| Yes      | series tag     | measure_code                 | Measure Code                   | text          | text          |
| Yes      | series tag     | score                        | Score                          | text          | text          |
| No       |                | footnote                     | Footnote                       | number        | number        |
| Yes      | time           | start_date                   | Start Date                     | calendar_date | calendar_date |
| No       |                | end_date                     | End Date                       | calendar_date | calendar_date |
```

## Time Field

```ls
Value = start_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = address_line_1,address_line_2,footnote,end_date
```

## Data Commands

```ls
series e:fp6g-2gsn d:2015-04-01T00:00:00.000Z t:cms_certification_number_ccn=012012 t:phonenumber="(205) 759-7241" t:facility_name="NOLAND HOSPITAL TUSCALOOSA II, LLC" t:zip_code=35401 t:state=AL t:score=3.896 t:measure_code=L_007_01_ELIGCASES t:county_name=Tuscaloosa t:city=TUSCALOOSA m:cms_region=4

series e:fp6g-2gsn d:2013-01-01T00:00:00.000Z t:cms_certification_number_ccn=052038 t:phonenumber="(562) 944-1900" t:facility_name="KINDRED HOSPITAL -- LA MIRADA" t:zip_code=90638 t:state=CA t:score=25.14 t:measure_code=L_008_01_RSRR t:county_name="Los Angeles" t:city="LA MIRADA" m:cms_region=9

series e:fp6g-2gsn d:2013-01-01T00:00:00.000Z t:cms_certification_number_ccn=102009 t:phonenumber="(813) 839-6341" t:facility_name="KINDRED HOSPITAL-BAY AREA-TAMPA" t:zip_code=33611 t:state=FL t:score=26.28 t:measure_code=L_008_01_RSRR_97_5 t:county_name=Hillsborough t:city=TAMPA m:cms_region=4
```

## Meta Commands

```ls
metric m:cms_region p:integer l:"CMS Region" t:dataTypeName=number

entity e:fp6g-2gsn l:"Long- Term Care Hospital - Provider Data" t:url=https://data.medicare.gov/api/views/fp6g-2gsn

property e:fp6g-2gsn t:meta.view v:id=fp6g-2gsn v:category="Long-Term Care Hospital Compare" v:averageRating=0 v:name="Long- Term Care Hospital - Provider Data"

property e:fp6g-2gsn t:meta.view.owner v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:displayName=cms

property e:fp6g-2gsn t:meta.view.tableauthor v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:roleName=administrator v:displayName=cms

property e:fp6g-2gsn t:meta.view.metadata.custom_fields.common_core v:Publisher="Centers for Medicare & Medicaid Services (CMS)" v:Contact_Email=LTCHQualityQuestions@cms.hhs.gov v:Contact_Name=CMS v:Bureau_Code=009:38 v:Program_Code=009:078
```

## Top Records

```ls
| cms_certification_number_ccn | facility_name                           | address_line_1                           | address_line_2 | city        | state | zip_code | county_name    | phonenumber    | cms_region | measure_code       | score | footnote | start_date          | end_date            | 
| ============================ | ======================================= | ======================================== | ============== | =========== | ===== | ======== | ============== | ============== | ========== | ================== | ===== | ======== | =================== | =================== | 
| 012012                       | NOLAND HOSPITAL TUSCALOOSA II, LLC      | 809 UNIVERSITY BOULEVARD EAST, 4TH FLOOR |                | TUSCALOOSA  | AL    | 35401    | Tuscaloosa     | (205) 759-7241 | 4          | L_007_01_ELIGCASES | 3.896 |          | 2015-04-01T00:00:00 | 2016-03-31T00:00:00 | 
| 052038                       | KINDRED HOSPITAL -- LA MIRADA           | 14900 E IMPERIAL HWY                     |                | LA MIRADA   | CA    | 90638    | Los Angeles    | (562) 944-1900 | 9          | L_008_01_RSRR      | 25.14 |          | 2013-01-01T00:00:00 | 2014-12-31T00:00:00 | 
| 102009                       | KINDRED HOSPITAL-BAY AREA-TAMPA         | 4555 S MANHATTAN AVE                     |                | TAMPA       | FL    | 33611    | Hillsborough   | (813) 839-6341 | 4          | L_008_01_RSRR_97_5 | 26.28 |          | 2013-01-01T00:00:00 | 2014-12-31T00:00:00 | 
| 042004                       | CHRISTUS DUBUIS HOSPITAL OF HOT SPRINGS | 300 WERNER STREET, 3RD FLOOR             |                | HOT SPRINGS | AR    | 71913    | Garland        | (501) 609-4333 | 6          | L_001_01_ADJ_RATE  | 3.1   |          | 2015-04-01T00:00:00 | 2016-03-31T00:00:00 | 
| 062015                       | KINDRED HOSPITAL - DENVER SOUTH         | 2525 S DOWNING ST 3RD FLOOR              |                | DENVER      | CO    | 80210    | Denver         | (303) 898-0369 | 8          | L_007_01_CI_LOWER  | 0.214 |          | 2015-04-01T00:00:00 | 2016-03-31T00:00:00 | 
| 052044                       | VIBRA HOSPITAL OF SAN DIEGO             | 555 WASHINGTON STREET                    |                | SAN DIEGO   | CA    | 92103    | San Diego      | (619) 260-8300 | 9          | L_006_01_NUMERATOR | 31    |          | 2015-04-01T00:00:00 | 2016-03-31T00:00:00 | 
| 012013                       | NOLAND HOSPITAL SHELBY II, LLC          | 1000 FIRST STREET, 3RD FLOOR             |                | ALABASTER   | AL    | 35007    | Shelby         | (205) 620-8641 | 4          | L_008_01_VOLUME    | 103   |          | 2013-01-01T00:00:00 | 2014-12-31T00:00:00 | 
| 052046                       | PROMISE HOSPITAL OF EAST LOS ANGELES    | 443 SOUTH SOTO STREET                    |                | LOS ANGELES | CA    | 90033    | Los Angeles    | (323) 261-1181 | 9          | L_007_01_CI_LOWER  | 0.738 |          | 2015-04-01T00:00:00 | 2016-03-31T00:00:00 | 
| 052031                       | BARLOW RESPIRATORY HOSPITAL             | 2000 STADIUM WAY                         |                | LOS ANGELES | CA    | 90026    | Los Angeles    | (213) 250-4200 | 9          | L_007_01_CI_LOWER  | 0.962 |          | 2015-04-01T00:00:00 | 2016-03-31T00:00:00 | 
| 052037                       | KINDRED HOSPITAL ONTARIO                | 550 NORTH MONTEREY                       |                | ONTARIO     | CA    | 91764    | San Bernardino | (909) 391-0333 | 9          | L_007_01_CI_LOWER  | 1.634 |          | 2015-04-01T00:00:00 | 2016-03-31T00:00:00 | 
```