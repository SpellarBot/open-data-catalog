# New Business List - July

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/new-business-list-july-7400a) |
| Metadata | [Link](https://data.oregon.gov/api/views/395d-muju) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/395d-muju/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/395d-muju/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | 395d-muju |
| Name | New Business List - July |
| Category | Business |
| Tags | business name, registration |
| Created | 2012-09-26T16:46:41Z |
| Publication Date | 2016-09-01T14:44:37Z |

## Description

Businesses registered with the Secretary of State Corporation Division during th emonth of July.

## Columns

```ls
| Included | Schema Type | Field Name                  | Name                        | Data Type     | Render Type   |
| ======== | =========== | =========================== | =========================== | ============= | ============= |
| Yes      | series tag  | registry_number             | Registry Number             | text          | text          |
| Yes      | series tag  | business_name               | Business Name               | text          | text          |
| Yes      | series tag  | entity_type                 | Entity Type                 | text          | text          |
| Yes      | time        | registry_date               | Registry Date               | calendar_date | calendar_date |
| Yes      | series tag  | associated_name_type        | Associated Name Type        | text          | text          |
| Yes      | series tag  | first_name                  | First Name                  | text          | text          |
| Yes      | series tag  | middle_name                 | Middle Name                 | text          | text          |
| Yes      | series tag  | last_name                   | Last Name                   | text          | text          |
| Yes      | series tag  | suffix                      | Suffix                      | text          | text          |
| Yes      | series tag  | not_of_record_entity        | Not of Record Entity        | text          | text          |
| Yes      | series tag  | entity_of_record_reg_number | Entity of Record Reg Number | text          | text          |
| Yes      | series tag  | entity_of_record_name       | Entity of Record Name       | text          | text          |
| No       |             | address                     | Address                     | text          | text          |
| No       |             | address_continued           | Address Continued           | text          | text          |
| Yes      | series tag  | city                        | City                        | text          | text          |
| Yes      | series tag  | state                       | State                       | text          | text          |
| Yes      | series tag  | zip_code                    | Zip Code                    | text          | html          |
```

## Time Field

```ls
Value = registry_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = address,address_continued
```

## Data Commands

```ls
series e:395d-muju d:2016-07-01T00:00:00.000Z t:business_name="A BETTER OREGON CITY COALITION" t:associated_name_type="MAILING ADDRESS" t:zip_code=97045 t:state=OR t:entity_type="DOMESTIC NONPROFIT CORPORATION" t:city="OREGON CITY" t:registry_number=122992894 m:row_number.395d-muju=1

series e:395d-muju d:2016-07-01T00:00:00.000Z t:business_name="A BETTER OREGON CITY COALITION" t:associated_name_type="REGISTERED AGENT" t:first_name=AL t:zip_code=97045 t:last_name=SNELL t:state=OR t:entity_type="DOMESTIC NONPROFIT CORPORATION" t:city="OREGON CITY" t:registry_number=122992894 m:row_number.395d-muju=2

series e:395d-muju d:2016-07-01T00:00:00.000Z t:business_name="ADAMS ALCHEMY LLC" t:associated_name_type="REGISTERED AGENT" t:first_name=CASIE t:zip_code=97415 t:middle_name=ELAINE t:last_name=ADAMS t:state=OR t:entity_type="DOMESTIC LIMITED LIABILITY COMPANY" t:city=BROOKINGS t:registry_number=122988892 m:row_number.395d-muju=3
```

## Meta Commands

```ls
metric m:row_number.395d-muju p:long l:"Row Number"

entity e:395d-muju l:"New Business List - July" t:url=https://data.oregon.gov/api/views/395d-muju

property e:395d-muju t:meta.view v:id=395d-muju v:category=Business v:averageRating=0 v:name="New Business List - July"

property e:395d-muju t:meta.view.owner v:id=ngr9-eh9y v:screenName="Judy Weems" v:displayName="Judy Weems"

property e:395d-muju t:meta.view.tableauthor v:id=ngr9-eh9y v:screenName="Judy Weems" v:roleName=editor v:displayName="Judy Weems"
```

## Top Records

```ls
| registry_number | business_name                               | entity_type                        | registry_date       | associated_name_type        | first_name | middle_name | last_name | suffix | not_of_record_entity | entity_of_record_reg_number | entity_of_record_name       | address                     | address_continued | city        | state | zip_code | 
| =============== | =========================================== | ================================== | =================== | =========================== | ========== | =========== | ========= | ====== | ==================== | =========================== | =========================== | =========================== | ================= | =========== | ===== | ======== | 
| 122992894       | A BETTER OREGON CITY COALITION              | DOMESTIC NONPROFIT CORPORATION     | 2016-07-01T00:00:00 | MAILING ADDRESS             |            |             |           |        |                      |                             |                             | 812 MOLALLA AVE             |                   | OREGON CITY | OR    | 97045    | 
| 122992894       | A BETTER OREGON CITY COALITION              | DOMESTIC NONPROFIT CORPORATION     | 2016-07-01T00:00:00 | REGISTERED AGENT            | AL         |             | SNELL     |        |                      |                             |                             | 812 MOLALLA AVE             |                   | OREGON CITY | OR    | 97045    | 
| 122988892       | ADAMS ALCHEMY LLC                           | DOMESTIC LIMITED LIABILITY COMPANY | 2016-07-01T00:00:00 | REGISTERED AGENT            | CASIE      | ELAINE      | ADAMS     |        |                      |                             |                             | 1206 IRIS ST                |                   | BROOKINGS   | OR    | 97415    | 
| 122686397       | AIRPORT RESEARCH AND DEVELOPMENT FOUNDATION | FOREIGN NONPROFIT CORPORATION      | 2016-07-01T00:00:00 | MAILING ADDRESS             |            |             |           |        |                      |                             |                             | 601 MADISON ST STE 400      |                   | ALEXANDRIA  | VA    | 22314    | 
| 122686397       | AIRPORT RESEARCH AND DEVELOPMENT FOUNDATION | FOREIGN NONPROFIT CORPORATION      | 2016-07-01T00:00:00 | PRINCIPAL PLACE OF BUSINESS |            |             |           |        |                      |                             |                             | 601 MADISON ST STE 400      |                   | ALEXANDRIA  | VA    | 22314    | 
| 122686397       | AIRPORT RESEARCH AND DEVELOPMENT FOUNDATION | FOREIGN NONPROFIT CORPORATION      | 2016-07-01T00:00:00 | REGISTERED AGENT            |            |             |           |        |                      | 15872088                    | CORPORATION SERVICE COMPANY | 1127 BROADWAY ST NE STE 310 |                   | SALEM       | OR    | 97301    | 
| 122995897       | ALLCARE HEALTH                              | ASSUMED BUSINESS NAME              | 2016-07-01T00:00:00 | AUTHORIZED REPRESENTATIVE   | TWILA      |             | FARRIS    |        |                      |                             |                             | 740 SE SEVENTH ST           |                   | GRANTS PASS | OR    | 97526    | 
| 122995897       | ALLCARE HEALTH                              | ASSUMED BUSINESS NAME              | 2016-07-01T00:00:00 | PRINCIPAL PLACE OF BUSINESS |            |             |           |        |                      |                             |                             | 740 SE SEVENTH ST           |                   | GRANTS PASS | OR    | 97526    | 
| 122990898       | ALTERNATIVE THERAPIES SOLUTIONS, INC        | DOMESTIC BUSINESS CORPORATION      | 2016-07-01T00:00:00 | REGISTERED AGENT            | D'ANNA     |             | DACAMARA  |        |                      |                             |                             | 2216 SE LINDEN LANE         |                   | GRANTS PASS | OR    | 97527    | 
| 122991797       | ASHLAND APPLIANCE AND MATTRESS              | ASSUMED BUSINESS NAME              | 2016-07-01T00:00:00 | AUTHORIZED REPRESENTATIVE   | NANCEE     |             | JESSEE    |        |                      |                             |                             | 1674 NE TERRACE DR          |                   | GRANTS PASS | OR    | 97526    | 
```