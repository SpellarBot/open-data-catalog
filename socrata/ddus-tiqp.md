# New Business List - September

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/new-business-list-september-de0b8) |
| Metadata | [Link](https://data.oregon.gov/api/views/ddus-tiqp) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/ddus-tiqp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/ddus-tiqp/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | ddus-tiqp |
| Name | New Business List - September |
| Category | Business |
| Tags | business name, registration |
| Created | 2012-11-01T13:55:55Z |
| Publication Date | 2016-11-01T14:53:31Z |

## Description

Businesses registered with the Secretary of State Corporation Division during the month of September.

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
series e:ddus-tiqp d:2016-09-01T00:00:00.000Z t:business_name="13TH AVENUE MARKET" t:associated_name_type="AUTHORIZED REPRESENTATIVE" t:first_name=BC t:zip_code=97401 t:last_name=LEE t:state=OR t:entity_type="ASSUMED BUSINESS NAME" t:city=EUGENE t:registry_number=124636697 m:row_number.ddus-tiqp=1

series e:ddus-tiqp d:2016-09-01T00:00:00.000Z t:business_name="13TH AVENUE MARKET" t:associated_name_type="PRINCIPAL PLACE OF BUSINESS" t:zip_code=97401 t:state=OR t:entity_type="ASSUMED BUSINESS NAME" t:city=EUGENE t:registry_number=124636697 m:row_number.ddus-tiqp=2

series e:ddus-tiqp d:2016-09-01T00:00:00.000Z t:business_name="734 ALBANY LLC" t:associated_name_type="REGISTERED AGENT" t:first_name=JOSEPH t:zip_code=97321 t:middle_name=F. t:last_name=KRAEMER t:state=OR t:entity_type="DOMESTIC LIMITED LIABILITY COMPANY" t:city=ALBANY t:registry_number=124643297 m:row_number.ddus-tiqp=3
```

## Meta Commands

```ls
metric m:row_number.ddus-tiqp p:long l:"Row Number"

entity e:ddus-tiqp l:"New Business List - September" t:url=https://data.oregon.gov/api/views/ddus-tiqp

property e:ddus-tiqp t:meta.view v:id=ddus-tiqp v:category=Business v:averageRating=0 v:name="New Business List - September"

property e:ddus-tiqp t:meta.view.owner v:id=ngr9-eh9y v:screenName="Judy Weems" v:displayName="Judy Weems"

property e:ddus-tiqp t:meta.view.tableauthor v:id=ngr9-eh9y v:screenName="Judy Weems" v:roleName=editor v:displayName="Judy Weems"
```

## Top Records

```ls
| registry_number | business_name            | entity_type                        | registry_date       | associated_name_type        | first_name | middle_name | last_name | suffix | not_of_record_entity | entity_of_record_reg_number | entity_of_record_name | address                | address_continued | city         | state | zip_code | 
| =============== | ======================== | ================================== | =================== | =========================== | ========== | =========== | ========= | ====== | ==================== | =========================== | ===================== | ====================== | ================= | ============ | ===== | ======== | 
| 124636697       | 13TH AVENUE MARKET       | ASSUMED BUSINESS NAME              | 2016-09-01T00:00:00 | AUTHORIZED REPRESENTATIVE   | BC         |             | LEE       |        |                      |                             |                       | 410 W 13TH AVE         |                   | EUGENE       | OR    | 97401    | 
| 124636697       | 13TH AVENUE MARKET       | ASSUMED BUSINESS NAME              | 2016-09-01T00:00:00 | PRINCIPAL PLACE OF BUSINESS |            |             |           |        |                      |                             |                       | 410 W 13TH AVE         |                   | EUGENE       | OR    | 97401    | 
| 124643297       | 734 ALBANY LLC           | DOMESTIC LIMITED LIABILITY COMPANY | 2016-09-01T00:00:00 | REGISTERED AGENT            | JOSEPH     | F.          | KRAEMER   |        |                      |                             |                       | 1240 LAKEWOOD DR SW    |                   | ALBANY       | OR    | 97321    | 
| 124641192       | A-FRAME LLC              | DOMESTIC LIMITED LIABILITY COMPANY | 2016-09-01T00:00:00 | REGISTERED AGENT            | JESSIE     |             | MOTT      |        |                      |                             |                       | 1685 SE COCHRAN DR     |                   | GRESHAM      | OR    | 97080    | 
| 124622796       | AN LAC RESTAURANT LLC    | DOMESTIC LIMITED LIABILITY COMPANY | 2016-09-01T00:00:00 | MAILING ADDRESS             |            |             |           |        |                      |                             |                       | 7510 SE 111TH AVE      |                   | PORTLAND     | OR    | 97266    | 
| 124622796       | AN LAC RESTAURANT LLC    | DOMESTIC LIMITED LIABILITY COMPANY | 2016-09-01T00:00:00 | REGISTERED AGENT            | TU         |             | DO        |        |                      |                             |                       | 5253 SE 82ND AVE STE C |                   | PORTLAND     | OR    | 97266    | 
| 124649690       | AQUATIC TRAINING VESSELS | ASSUMED BUSINESS NAME              | 2016-09-01T00:00:00 | AUTHORIZED REPRESENTATIVE   | JOHN       | M           | SCHRENK   |        |                      |                             |                       | 596 HOFFMAN RD         |                   | INDEPENDENCE | OR    | 97351    | 
| 124649690       | AQUATIC TRAINING VESSELS | ASSUMED BUSINESS NAME              | 2016-09-01T00:00:00 | PRINCIPAL PLACE OF BUSINESS |            |             |           |        |                      |                             |                       | 596 HOFFMAN RD         |                   | INDEPENDENCE | OR    | 97351    | 
| 124632993       | BB BOOKKEEPING, LLC      | DOMESTIC LIMITED LIABILITY COMPANY | 2016-09-01T00:00:00 | REGISTERED AGENT            | BRANDI     |             | BUTLER    |        |                      |                             |                       | 5294 NE 52ND AVE       |                   | PORTLAND     | OR    | 97218    | 
| 124648197       | BC MEDIA LLC             | DOMESTIC LIMITED LIABILITY COMPANY | 2016-09-01T00:00:00 | REGISTERED AGENT            | BC         |             | NELSON    |        |                      |                             |                       | 470 E WASHINGTON ST    |                   | STAYTON      | OR    | 97383    | 
```