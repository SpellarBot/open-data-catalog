# New Business List - June

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/new-business-list-june-1accb) |
| Metadata | [Link](https://data.oregon.gov/api/views/i8h7-mn6v) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/i8h7-mn6v/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/i8h7-mn6v/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | i8h7-mn6v |
| Name | New Business List - June |
| Category | Business |
| Tags | business name, registration |
| Created | 2012-08-01T15:44:22Z |
| Publication Date | 2016-08-01T18:37:54Z |

## Description

Businesses registered with the Secretary of State Corporation Division during the month of June.

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
series e:i8h7-mn6v d:2016-06-01T00:00:00.000Z t:business_name="12 STONE CONTRACTING GROUP, INC." t:associated_name_type="MAILING ADDRESS" t:zip_code=31106 t:state=GA t:entity_type="FOREIGN BUSINESS CORPORATION" t:city=ATLANTA t:registry_number=122151194 m:row_number.i8h7-mn6v=1

series e:i8h7-mn6v d:2016-06-01T00:00:00.000Z t:business_name="12 STONE CONTRACTING GROUP, INC." t:associated_name_type="PRINCIPAL PLACE OF BUSINESS" t:zip_code=30135 t:state=GA t:entity_type="FOREIGN BUSINESS CORPORATION" t:city=DOUGLASVILLE t:registry_number=122151194 m:row_number.i8h7-mn6v=2

series e:i8h7-mn6v d:2016-06-01T00:00:00.000Z t:business_name="12 STONE CONTRACTING GROUP, INC." t:associated_name_type="REGISTERED AGENT" t:entity_of_record_name="C T CORPORATION SYSTEM" t:zip_code=97301 t:state=OR t:entity_type="FOREIGN BUSINESS CORPORATION" t:entity_of_record_reg_number=329227 t:city=SALEM t:registry_number=122151194 m:row_number.i8h7-mn6v=3
```

## Meta Commands

```ls
metric m:row_number.i8h7-mn6v p:long l:"Row Number"

entity e:i8h7-mn6v l:"New Business List - June" t:url=https://data.oregon.gov/api/views/i8h7-mn6v

property e:i8h7-mn6v t:meta.view v:id=i8h7-mn6v v:category=Business v:averageRating=0 v:name="New Business List - June"

property e:i8h7-mn6v t:meta.view.owner v:id=ngr9-eh9y v:screenName="Judy Weems" v:displayName="Judy Weems"

property e:i8h7-mn6v t:meta.view.tableauthor v:id=ngr9-eh9y v:screenName="Judy Weems" v:roleName=editor v:displayName="Judy Weems"
```

## Top Records

```ls
| registry_number | business_name                    | entity_type                    | registry_date       | associated_name_type        | first_name | middle_name | last_name | suffix | not_of_record_entity | entity_of_record_reg_number | entity_of_record_name          | address                    | address_continued | city         | state | zip_code | 
| =============== | ================================ | ============================== | =================== | =========================== | ========== | =========== | ========= | ====== | ==================== | =========================== | ============================== | ========================== | ================= | ============ | ===== | ======== | 
| 122151194       | 12 STONE CONTRACTING GROUP, INC. | FOREIGN BUSINESS CORPORATION   | 2016-06-01T00:00:00 | MAILING ADDRESS             |            |             |           |        |                      |                             |                                | PO BOX 8958                |                   | ATLANTA      | GA    | 31106    | 
| 122151194       | 12 STONE CONTRACTING GROUP, INC. | FOREIGN BUSINESS CORPORATION   | 2016-06-01T00:00:00 | PRINCIPAL PLACE OF BUSINESS |            |             |           |        |                      |                             |                                | 5855 HIGHWAY 5             |                   | DOUGLASVILLE | GA    | 30135    | 
| 122151194       | 12 STONE CONTRACTING GROUP, INC. | FOREIGN BUSINESS CORPORATION   | 2016-06-01T00:00:00 | REGISTERED AGENT            |            |             |           |        |                      | 329227                      | C T CORPORATION SYSTEM         | 388 STATE ST STE 420       |                   | SALEM        | OR    | 97301    | 
| 122141294       | ABBA'S GARDEN                    | DOMESTIC NONPROFIT CORPORATION | 2016-06-01T00:00:00 | MAILING ADDRESS             | KYLE       |             | ROY       |        |                      |                             |                                | 2426 SE 70TH AVE           |                   | PORTLAND     | OR    | 97206    | 
| 122141294       | ABBA'S GARDEN                    | DOMESTIC NONPROFIT CORPORATION | 2016-06-01T00:00:00 | REGISTERED AGENT            | KYLE       |             | ROY       |        |                      |                             |                                | 2426 SE 70TH AVE           |                   | PORTLAND     | OR    | 97206    | 
| 122140098       | AIR 1 PLUMBING INC               | FOREIGN BUSINESS CORPORATION   | 2016-06-01T00:00:00 | MAILING ADDRESS             |            |             |           |        |                      |                             |                                | 9012 NE 89TH CIRCLE        |                   | VANCOUVER    | WA    | 98662    | 
| 122140098       | AIR 1 PLUMBING INC               | FOREIGN BUSINESS CORPORATION   | 2016-06-01T00:00:00 | PRINCIPAL PLACE OF BUSINESS |            |             |           |        |                      |                             |                                | 9012 NE 89TH CIRCLE        |                   | VANCOUVER    | WA    | 98662    | 
| 122140098       | AIR 1 PLUMBING INC               | FOREIGN BUSINESS CORPORATION   | 2016-06-01T00:00:00 | REGISTERED AGENT            | CORNELL    |             | CUREA     |        |                      |                             |                                | 6138 SE 136TH AVE          |                   | PORTLAND     | OR    | 97236    | 
| 122135197       | ASSUMPTION VILLAGE               | ASSUMED BUSINESS NAME          | 2016-06-01T00:00:00 | AUTHORIZED REPRESENTATIVE   |            |             |           |        |                      | 74556284                    | S W & W LEGAL SERVICES, INC.   | 1211 SW FIFTH AVE STE 1900 |                   | PORTLAND     | OR    | 97204    | 
| 122135197       | ASSUMPTION VILLAGE               | ASSUMED BUSINESS NAME          | 2016-06-01T00:00:00 | AUTHORIZED REPRESENTATIVE   |            |             |           |        |                      | 74556284                    | SW & W REGISTERED AGENTS, INC. | 1211 SW FIFTH AVE STE 1900 |                   | PORTLAND     | OR    | 97204    | 
```