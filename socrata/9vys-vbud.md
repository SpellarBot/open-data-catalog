# New Business List - October

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/new-business-list-october-91ab2) |
| Metadata | [Link](https://data.oregon.gov/api/views/9vys-vbud) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/9vys-vbud/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/9vys-vbud/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | 9vys-vbud |
| Name | New Business List - October |
| Category | Business |
| Tags | business name, registration |
| Created | 2011-12-06T15:03:00Z |
| Publication Date | 2016-12-01T16:52:23Z |

## Description

Businesses registered with the Secretary of State Corporation Division during the month of October.

## Columns

```ls
| Included | Schema Type | Field Name                  | Name                        | Data Type | Render Type |
| ======== | =========== | =========================== | =========================== | ========= | =========== |
| Yes      | series tag  | registry_number             | Registry Number             | text      | text        |
| Yes      | series tag  | business_name               | Business Name               | text      | text        |
| Yes      | series tag  | entity_type                 | Entity Type                 | text      | text        |
| Yes      | time        | registry_date               | Registry Date               | date      | date        |
| Yes      | series tag  | associated_name_type        | Associated Name Type        | text      | text        |
| Yes      | series tag  | first_name                  | First Name                  | text      | text        |
| Yes      | series tag  | middle_name                 | Middle Name                 | text      | text        |
| Yes      | series tag  | last_name                   | Last Name                   | text      | text        |
| Yes      | series tag  | suffix                      | Suffix                      | text      | text        |
| Yes      | series tag  | not_of_record_entity        | Not of Record Entity        | text      | text        |
| Yes      | series tag  | entity_of_record_reg_number | Entity of Record Reg Number | text      | text        |
| Yes      | series tag  | entity_of_record_name       | Entity of Record Name       | text      | text        |
| No       |             | address_                    | Address                     | text      | text        |
| No       |             | address_continued           | Address Continued           | text      | text        |
| Yes      | series tag  | city                        | City                        | text      | text        |
| Yes      | series tag  | state                       | State                       | text      | text        |
| Yes      | series tag  | zip_code                    | Zip Code                    | text      | text        |
```

## Time Field

```ls
Value = registry_date
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address_,address_continued
```

## Data Commands

```ls
series e:9vys-vbud d:2016-10-03T00:00:00.000Z t:business_name="7 SEVEN THAI RESTAURANT INC." t:associated_name_type="MAILING ADDRESS" t:zip_code=97420 t:state=OR t:entity_type="DOMESTIC BUSINESS CORPORATION" t:city="COOS BAY" t:registry_number=125521690 m:row_number.9vys-vbud=1

series e:9vys-vbud d:2016-10-03T00:00:00.000Z t:business_name="7 SEVEN THAI RESTAURANT INC." t:associated_name_type="REGISTERED AGENT" t:first_name=RATTACHAI t:zip_code=97471 t:last_name=PHROMMANOJ t:state=OR t:entity_type="DOMESTIC BUSINESS CORPORATION" t:city=ROSEBURG t:registry_number=125521690 m:row_number.9vys-vbud=2

series e:9vys-vbud d:2016-10-03T00:00:00.000Z t:business_name="AM PM MOVING, LLC" t:associated_name_type="REGISTERED AGENT" t:first_name=CHARLES t:zip_code=97301 t:last_name=RAMBO t:state=OR t:entity_type="DOMESTIC LIMITED LIABILITY COMPANY" t:city=SALEM t:registry_number=125514497 m:row_number.9vys-vbud=3
```

## Meta Commands

```ls
metric m:row_number.9vys-vbud p:long l:"Row Number"

entity e:9vys-vbud l:"New Business List - October" t:url=https://data.oregon.gov/api/views/9vys-vbud

property e:9vys-vbud t:meta.view v:id=9vys-vbud v:category=Business v:averageRating=0 v:name="New Business List - October"

property e:9vys-vbud t:meta.view.owner v:id=ngr9-eh9y v:screenName="Judy Weems" v:displayName="Judy Weems"

property e:9vys-vbud t:meta.view.tableauthor v:id=ngr9-eh9y v:screenName="Judy Weems" v:roleName=editor v:displayName="Judy Weems"
```

## Top Records

```ls
| registry_number | business_name                  | entity_type                        | registry_date | associated_name_type        | first_name | middle_name | last_name  | suffix | not_of_record_entity | entity_of_record_reg_number | entity_of_record_name | address_                   | address_continued | city     | state | zip_code | 
| =============== | ============================== | ================================== | ============= | =========================== | ========== | =========== | ========== | ====== | ==================== | =========================== | ===================== | ========================== | ================= | ======== | ===== | ======== | 
| 125521690       | 7 SEVEN THAI RESTAURANT INC.   | DOMESTIC BUSINESS CORPORATION      | 1475452800    | MAILING ADDRESS             |            |             |            |        |                      |                             |                       | 486 ELROD AVE              |                   | COOS BAY | OR    | 97420    | 
| 125521690       | 7 SEVEN THAI RESTAURANT INC.   | DOMESTIC BUSINESS CORPORATION      | 1475452800    | REGISTERED AGENT            | RATTACHAI  |             | PHROMMANOJ |        |                      |                             |                       | 764 NW GARDEN VALLEY BLVD  |                   | ROSEBURG | OR    | 97471    | 
| 125514497       | AM PM MOVING, LLC              | DOMESTIC LIMITED LIABILITY COMPANY | 1475452800    | REGISTERED AGENT            | CHARLES    |             | RAMBO      |        |                      |                             |                       | 2860 CHERRY AVE NE         |                   | SALEM    | OR    | 97301    | 
| 125516591       | ANCAEL CONSTRUCTION LLC        | DOMESTIC LIMITED LIABILITY COMPANY | 1475452800    | REGISTERED AGENT            | ANTONIO    | CARBAJAL    | ELIZALDE   |        |                      |                             |                       | 2160 34TH AVE NE           |                   | SALEM    | OR    | 97301    | 
| 125505396       | ANCHORS AND INK TATTOO         | ASSUMED BUSINESS NAME              | 1475452800    | AUTHORIZED REPRESENTATIVE   | KRISTOPHER |             | BROWN      |        |                      |                             |                       | 3159 NE RICHMOND CT        |                   | BEND     | OR    | 97701    | 
| 125505396       | ANCHORS AND INK TATTOO         | ASSUMED BUSINESS NAME              | 1475452800    | PRINCIPAL PLACE OF BUSINESS |            |             |            |        |                      |                             |                       | 925 NW WALL ST             |                   | BEND     | OR    | 97701    | 
| 125498493       | APPLE TREE COLLABORATIONS, LLC | DOMESTIC LIMITED LIABILITY COMPANY | 1475452800    | MAILING ADDRESS             |            |             |            |        |                      |                             |                       | 1605 N COAST HWY           |                   | NEWPORT  | OR    | 97365    | 
| 125498493       | APPLE TREE COLLABORATIONS, LLC | DOMESTIC LIMITED LIABILITY COMPANY | 1475452800    | PRINCIPAL PLACE OF BUSINESS |            |             |            |        |                      |                             |                       | 1605 N COAST HWY           |                   | NEWPORT  | OR    | 97365    | 
| 125498493       | APPLE TREE COLLABORATIONS, LLC | DOMESTIC LIMITED LIABILITY COMPANY | 1475452800    | REGISTERED AGENT            | JENNIFER   |             | WIMPRESS   |        |                      |                             |                       | 1605 N COAST HWY           |                   | NEWPORT  | OR    | 97365    | 
| 125520494       | BRIGHTHOUSE SERVICES, LLC      | FOREIGN LIMITED LIABILITY COMPANY  | 1475452800    | MAILING ADDRESS             |            |             |            |        |                      |                             |                       | 1095 AVENUE OF THE AMERICA |                   | NEW YORK | NY    | 10036    | 
```