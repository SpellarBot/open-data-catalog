# New Business List - February

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/new-business-list-february-acd88) |
| Metadata | [Link](https://data.oregon.gov/api/views/rzbk-bycp) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/rzbk-bycp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/rzbk-bycp/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | rzbk-bycp |
| Name | New Business List - February |
| Category | Business |
| Tags | buisness name, registration |
| Created | 2013-04-02T19:57:42Z |
| Publication Date | 2017-04-04T18:17:41Z |

## Description

Businesses registered with the Secretary of State Corporation Division during the month of February.

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
| Yes      | series tag  | zip_code                    | Zip Code                    | text          | text          |
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
series e:rzbk-bycp d:2017-02-01T00:00:00.000Z t:business_name="2829 APPLEGATE PRODUCTS, LLC" t:associated_name_type="MAILING ADDRESS" t:zip_code=98112 t:state=WA t:entity_type="DOMESTIC LIMITED LIABILITY COMPANY" t:city=SEATTLE t:registry_number=128935590 m:row_number.rzbk-bycp=1

series e:rzbk-bycp d:2017-02-01T00:00:00.000Z t:business_name="2829 APPLEGATE PRODUCTS, LLC" t:associated_name_type="REGISTERED AGENT" t:first_name=HENRY t:zip_code=97530 t:middle_name=D t:last_name=SEURER t:state=OR t:entity_type="DOMESTIC LIMITED LIABILITY COMPANY" t:city=JACKSONVILLE t:registry_number=128935590 m:row_number.rzbk-bycp=2

series e:rzbk-bycp d:2017-02-01T00:00:00.000Z t:business_name="340 NORTH STREET, LLC" t:associated_name_type="MAILING ADDRESS" t:zip_code=94915 t:state=CA t:entity_type="DOMESTIC LIMITED LIABILITY COMPANY" t:city="SAN RAFAEL" t:registry_number=128924396 m:row_number.rzbk-bycp=3
```

## Meta Commands

```ls
metric m:row_number.rzbk-bycp p:long l:"Row Number"

entity e:rzbk-bycp l:"New Business List - February" t:url=https://data.oregon.gov/api/views/rzbk-bycp

property e:rzbk-bycp t:meta.view v:id=rzbk-bycp v:category=Business v:averageRating=0 v:name="New Business List - February"

property e:rzbk-bycp t:meta.view.owner v:id=ngr9-eh9y v:screenName="Judy Weems" v:displayName="Judy Weems"

property e:rzbk-bycp t:meta.view.tableauthor v:id=ngr9-eh9y v:screenName="Judy Weems" v:roleName=editor v:displayName="Judy Weems"
```

## Top Records

```ls
| registry_number | business_name                | entity_type                        | registry_date       | associated_name_type        | first_name | middle_name | last_name | suffix | not_of_record_entity | entity_of_record_reg_number | entity_of_record_name | address                    | address_continued | city         | state | zip_code | 
| =============== | ============================ | ================================== | =================== | =========================== | ========== | =========== | ========= | ====== | ==================== | =========================== | ===================== | ========================== | ================= | ============ | ===== | ======== | 
| 128935590       | 2829 APPLEGATE PRODUCTS, LLC | DOMESTIC LIMITED LIABILITY COMPANY | 2017-02-01T00:00:00 | MAILING ADDRESS             |            |             |           |        |                      |                             |                       | 2514 EAST CALHOUN ST       |                   | SEATTLE      | WA    | 98112    | 
| 128935590       | 2829 APPLEGATE PRODUCTS, LLC | DOMESTIC LIMITED LIABILITY COMPANY | 2017-02-01T00:00:00 | REGISTERED AGENT            | HENRY      | D           | SEURER    |        |                      |                             |                       | 2829 UPPER APPLEGATE RD    |                   | JACKSONVILLE | OR    | 97530    | 
| 128924396       | 340 NORTH STREET, LLC        | DOMESTIC LIMITED LIABILITY COMPANY | 2017-02-01T00:00:00 | MAILING ADDRESS             |            |             |           |        |                      |                             |                       | PO BOX 151357              |                   | SAN RAFAEL   | CA    | 94915    | 
| 128924396       | 340 NORTH STREET, LLC        | DOMESTIC LIMITED LIABILITY COMPANY | 2017-02-01T00:00:00 | REGISTERED AGENT            | STEVEN     | W           | BECHTOLD  |        |                      |                             |                       | 1318 SW 12TH AVE           |                   | PORTLAND     | OR    | 97201    | 
| 128914298       | 38938 COX LANE, LLC          | DOMESTIC LIMITED LIABILITY COMPANY | 2017-02-01T00:00:00 | REGISTERED AGENT            | TYSON      | L           | CALVERT   |        |                      |                             |                       | 1300 SW FIFTH AVE STE 3400 |                   | PORTLAND     | OR    | 97201    | 
| 128908993       | ACULINE LLC                  | DOMESTIC LIMITED LIABILITY COMPANY | 2017-02-01T00:00:00 | MAILING ADDRESS             |            |             |           |        |                      |                             |                       | 214 DEANN DR #4            |                   | INDEPENDENCE | OR    | 97351    | 
| 128908993       | ACULINE LLC                  | DOMESTIC LIMITED LIABILITY COMPANY | 2017-02-01T00:00:00 | REGISTERED AGENT            | TIMOTHY    | J           | BEARDSLEY |        |                      |                             |                       | 214 DEANN DR #4            |                   | INDEPENDENCE | OR    | 97351    | 
| 128930096       | ALEXIS PROPERTIES, INC       | DOMESTIC BUSINESS CORPORATION      | 2017-02-01T00:00:00 | REGISTERED AGENT            | FABIAN     |             | ARREDONDO |        |                      |                             |                       | 1180 17TH ST NE            |                   | SALEM        | OR    | 97301    | 
| 128179397       | ALOHA DENTAL CARE            | ASSUMED BUSINESS NAME              | 2017-02-01T00:00:00 | AUTHORIZED REPRESENTATIVE   |            |             |           |        |                      | 127349991                   | PJN DENTAL, LLC       | 3895 SW 185TH AVE STE 110  |                   | ALOHA        | OR    | 97078    | 
| 128179397       | ALOHA DENTAL CARE            | ASSUMED BUSINESS NAME              | 2017-02-01T00:00:00 | PRINCIPAL PLACE OF BUSINESS |            |             |           |        |                      |                             |                       | 3895 SW 185TH AVE STE 110  |                   | ALOHA        | OR    | 97078    | 
```