# New Business List - April

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/new-business-list-april-15445) |
| Metadata | [Link](https://data.oregon.gov/api/views/5qwt-pfng) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/5qwt-pfng/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/5qwt-pfng/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | 5qwt-pfng |
| Name | New Business List - April |
| Category | Business |
| Tags | business name, registration |
| Created | 2012-06-01T16:37:41Z |
| Publication Date | 2017-07-05T15:27:37Z |

## Description

Businesses registered with the Secretary of State Corporation Division during the month of April.

## Columns

```ls
| Included | Schema Type    | Field Name                  | Name                        | Data Type     | Render Type   |
| ======== | ============== | =========================== | =========================== | ============= | ============= |
| Yes      | series tag     | registry_number             | Registry Number             | text          | text          |
| Yes      | series tag     | business_name               | Business Name               | text          | text          |
| Yes      | series tag     | entity_type                 | Entity Type                 | text          | text          |
| Yes      | time           | registry_date               | Registry Date               | calendar_date | calendar_date |
| Yes      | series tag     | associated_name_type        | Associated Name Type        | text          | text          |
| Yes      | series tag     | first_name                  | First Name                  | text          | text          |
| Yes      | series tag     | middle_name                 | Middle Name                 | text          | text          |
| Yes      | series tag     | last_name                   | Last Name                   | text          | text          |
| Yes      | series tag     | suffix                      | Suffix                      | text          | text          |
| Yes      | series tag     | entity_of_record_reg_number | Entity of Record Reg Number | text          | text          |
| Yes      | numeric metric | not_of_record_entity        | Not of Record Entity        | number        | text          |
| Yes      | series tag     | entity_of_record_name       | Entity of Record Name       | text          | text          |
| No       |                | address                     | Address                     | text          | text          |
| No       |                | address_continued           | Address Continued           | text          | text          |
| Yes      | series tag     | city                        | City                        | text          | text          |
| Yes      | series tag     | state                       | State                       | text          | text          |
| Yes      | series tag     | zip_code                    | Zip Code                    | text          | text          |
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
series e:5qwt-pfng d:2017-04-03T00:00:00.000Z t:business_name="ANGELS WING OF OREGON LLC" t:associated_name_type="REGISTERED AGENT" t:entity_type="DOMESTIC LIMITED LIABILITY COMPANY" t:city=PORTLAND t:registry_number=131070294 t:state=OR t:zip_code=97225 t:entity_of_record_name="INCORPORATING SERVICES, LTD." m:not_of_record_entity=27939198

series e:5qwt-pfng d:2017-04-03T00:00:00.000Z t:business_name="BREAKTIME DENTAL LLC" t:associated_name_type="REGISTERED AGENT" t:entity_type="DOMESTIC LIMITED LIABILITY COMPANY" t:city=PORTLAND t:registry_number=131063794 t:state=OR t:zip_code=97209 t:entity_of_record_name="IMMIX SERVICES INC" m:not_of_record_entity=76083394

series e:5qwt-pfng d:2017-04-03T00:00:00.000Z t:business_name="CHANDLER STAGING, LLC" t:associated_name_type="REGISTERED AGENT" t:entity_type="DOMESTIC LIMITED LIABILITY COMPANY" t:city=GRESHAM t:registry_number=131063299 t:state=OR t:zip_code=97030 t:entity_of_record_name="UNITED STATES CORPORATION AGENTS, INC." m:not_of_record_entity=66022790
```

## Meta Commands

```ls
metric m:not_of_record_entity p:integer l:"Not of Record Entity" t:dataTypeName=number

entity e:5qwt-pfng l:"New Business List - April" t:url=https://data.oregon.gov/api/views/5qwt-pfng

property e:5qwt-pfng t:meta.view d:2017-09-25T07:26:28.533Z v:averageRating=0 v:name="New Business List - April" v:id=5qwt-pfng v:category=Business

property e:5qwt-pfng t:meta.view.owner d:2017-09-25T07:26:28.533Z v:displayName="Judy Weems" v:id=ngr9-eh9y v:screenName="Judy Weems"

property e:5qwt-pfng t:meta.view.tableauthor d:2017-09-25T07:26:28.533Z v:displayName="Judy Weems" v:roleName=editor v:id=ngr9-eh9y v:screenName="Judy Weems"
```

## Top Records

```ls
| registry_number | business_name                              | entity_type                        | registry_date       | associated_name_type        | first_name | middle_name | last_name    | suffix | entity_of_record_reg_number | not_of_record_entity | entity_of_record_name        | address                         | address_continued | city      | state | zip_code | 
| =============== | ========================================== | ================================== | =================== | =========================== | ========== | =========== | ============ | ====== | =========================== | ==================== | ============================ | =============================== | ================= | ========= | ===== | ======== | 
| 131062994       | 4 PAYMENTS, INC.                           | DOMESTIC BUSINESS CORPORATION      | 2017-04-03T00:00:00 | PRINCIPAL PLACE OF BUSINESS |            |             |              |        |                             |                      |                              | 4825 SE 63RD AVE                |                   | PORTLAND  | OR    | 97206    | 
| 131062994       | 4 PAYMENTS, INC.                           | DOMESTIC BUSINESS CORPORATION      | 2017-04-03T00:00:00 | REGISTERED AGENT            | JOSEPH     | CARLOS      | BLAIR        |        |                             |                      |                              | 4825 SE 63RD AVE                |                   | PORTLAND  | OR    | 97206    | 
| 130327794       | @BE, LLC                                   | DOMESTIC LIMITED LIABILITY COMPANY | 2017-04-03T00:00:00 | REGISTERED AGENT            | JENNIFER   | R           | KLINGENSMITH |        |                             |                      |                              | 725 COUNTRY CLUB RD             |                   | EUGENE    | OR    | 97401    | 
| 131064396       | ALLYKAT ENTERPRISES, LLC                   | DOMESTIC LIMITED LIABILITY COMPANY | 2017-04-03T00:00:00 | REGISTERED AGENT            | AARON      |             | ANDERS       |        |                             |                      |                              | 1911 UNITED WAY                 |                   | MEDFORD   | OR    | 97504    | 
| 131070294       | ANGELS WING OF OREGON LLC                  | DOMESTIC LIMITED LIABILITY COMPANY | 2017-04-03T00:00:00 | MAILING ADDRESS             |            |             |              |        |                             |                      |                              | 28437 SUNGLOW RUN LAND          |                   | MENIFEE   | CA    | 92584    | 
| 131070294       | ANGELS WING OF OREGON LLC                  | DOMESTIC LIMITED LIABILITY COMPANY | 2017-04-03T00:00:00 | REGISTERED AGENT            |            |             |              |        |                             | 27939198             | INCORPORATING SERVICES, LTD. | 8130 SW BEAVERTON-HILLSDALE HWY |                   | PORTLAND  | OR    | 97225    | 
| 131055691       | APPRAISAL ASSOCIATES OF DOUGLAS COUNTY LLC | DOMESTIC LIMITED LIABILITY COMPANY | 2017-04-03T00:00:00 | MAILING ADDRESS             |            |             |              |        |                             |                      |                              | PO BOX 1018                     |                   | WINSTON   | OR    | 97496    | 
| 131055691       | APPRAISAL ASSOCIATES OF DOUGLAS COUNTY LLC | DOMESTIC LIMITED LIABILITY COMPANY | 2017-04-03T00:00:00 | REGISTERED AGENT            | ROBERT     |             | WHEELER      |        |                             |                      |                              | 88 NW MAIN ST                   |                   | WINSTON   | OR    | 97496    | 
| 131062895       | AVILA GENERAL MAINTENANCE, INC.            | DOMESTIC BUSINESS CORPORATION      | 2017-04-03T00:00:00 | PRINCIPAL PLACE OF BUSINESS |            |             |              |        |                             |                      |                              | 239 NW ADAMS AVE                |                   | HILLSBORO | OR    | 97124    | 
| 131062895       | AVILA GENERAL MAINTENANCE, INC.            | DOMESTIC BUSINESS CORPORATION      | 2017-04-03T00:00:00 | REGISTERED AGENT            | JUVENTINO  | AVILA       | ESTRADA      |        |                             |                      |                              | 239 NW ADAMS AVE                |                   | HILLSBORO | OR    | 97124    | 
```