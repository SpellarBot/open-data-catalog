# New Business List - November

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/new-business-list-november-dd8c6) |
| Metadata | [Link](https://data.oregon.gov/api/views/tu37-gsxb) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/tu37-gsxb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/tu37-gsxb/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | tu37-gsxb |
| Name | New Business List - November |
| Category | Business |
| Tags | business name, registration |
| Created | 2013-01-02T16:53:16Z |
| Publication Date | 2016-12-01T16:46:40Z |

## Description

Businesses registered with the Secretary of State Corporation Division during the month of November.

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
| Yes      | series tag  | zip_code                    | Zip Code                    | text          | number        |
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
series e:tu37-gsxb d:2016-11-01T00:00:00.000Z t:business_name="2301 LAUREL PROPERTY, LLC" t:associated_name_type="MAILING ADDRESS" t:zip_code=90028 t:state=CA t:entity_type="DOMESTIC LIMITED LIABILITY COMPANY" t:city=HOLLYWOOD t:registry_number=126356294 m:row_number.tu37-gsxb=1

series e:tu37-gsxb d:2016-11-01T00:00:00.000Z t:business_name="2301 LAUREL PROPERTY, LLC" t:associated_name_type="REGISTERED AGENT" t:entity_of_record_name="PARACORP INCORPORATED" t:zip_code=97302 t:state=OR t:entity_type="DOMESTIC LIMITED LIABILITY COMPANY" t:entity_of_record_reg_number=63141486 t:city=SALEM t:registry_number=126356294 m:row_number.tu37-gsxb=2

series e:tu37-gsxb d:2016-11-01T00:00:00.000Z t:business_name="925 NE 4TH, LLC" t:associated_name_type="REGISTERED AGENT" t:first_name=JULIE t:zip_code=97302 t:last_name=PENCE-WALTERS t:state=OR t:entity_type="DOMESTIC LIMITED LIABILITY COMPANY" t:city=SALEM t:registry_number=126357490 m:row_number.tu37-gsxb=3
```

## Meta Commands

```ls
metric m:row_number.tu37-gsxb p:long l:"Row Number"

entity e:tu37-gsxb l:"New Business List - November" t:url=https://data.oregon.gov/api/views/tu37-gsxb

property e:tu37-gsxb t:meta.view v:id=tu37-gsxb v:category=Business v:averageRating=0 v:name="New Business List - November"

property e:tu37-gsxb t:meta.view.owner v:id=ngr9-eh9y v:screenName="Judy Weems" v:displayName="Judy Weems"

property e:tu37-gsxb t:meta.view.tableauthor v:id=ngr9-eh9y v:screenName="Judy Weems" v:roleName=editor v:displayName="Judy Weems"
```

## Top Records

```ls
| registry_number | business_name                       | entity_type                        | registry_date       | associated_name_type        | first_name | middle_name | last_name     | suffix | not_of_record_entity | entity_of_record_reg_number | entity_of_record_name           | address                        | address_continued | city        | state | zip_code | 
| =============== | =================================== | ================================== | =================== | =========================== | ========== | =========== | ============= | ====== | ==================== | =========================== | =============================== | ============================== | ================= | =========== | ===== | ======== | 
| 126356294       | 2301 LAUREL PROPERTY, LLC           | DOMESTIC LIMITED LIABILITY COMPANY | 2016-11-01T00:00:00 | MAILING ADDRESS             |            |             |               |        |                      |                             |                                 | 6925 HOLLYWOOD BLVD            |                   | HOLLYWOOD   | CA    | 90028    | 
| 126356294       | 2301 LAUREL PROPERTY, LLC           | DOMESTIC LIMITED LIABILITY COMPANY | 2016-11-01T00:00:00 | REGISTERED AGENT            |            |             |               |        |                      | 63141486                    | PARACORP INCORPORATED           | 3533 FAIRVIEW INDUSTRIAL DR SE |                   | SALEM       | OR    | 97302    | 
| 126357490       | 925 NE 4TH, LLC                     | DOMESTIC LIMITED LIABILITY COMPANY | 2016-11-01T00:00:00 | REGISTERED AGENT            | JULIE      |             | PENCE-WALTERS |        |                      |                             |                                 | 1260 OXFORD ST SE              |                   | SALEM       | OR    | 97302    | 
| 126358092       | ALBANY WISE INVESTMENTS, LLC        | DOMESTIC LIMITED LIABILITY COMPANY | 2016-11-01T00:00:00 | REGISTERED AGENT            | VICTORIA   | A           | USHER         |        |                      |                             |                                 | 520 NW CRESWELL LN             |                   | ALBANY      | OR    | 97321    | 
| 126340793       | AURORA FLOWER COMPANY               | ASSUMED BUSINESS NAME              | 2016-11-01T00:00:00 | AUTHORIZED REPRESENTATIVE   |            |             |               |        |                      | 8601296                     | TT ADMINISTRATIVE SERVICES, LLC | 888 SW FIFTH AVE STE 1600      |                   | PORTLAND    | OR    | 97204    | 
| 126340793       | AURORA FLOWER COMPANY               | ASSUMED BUSINESS NAME              | 2016-11-01T00:00:00 | PRINCIPAL PLACE OF BUSINESS |            |             |               |        |                      |                             |                                 | 220 NW 8TH AVE                 |                   | PORTLAND    | OR    | 97209    | 
| 126338490       | BOWEN FAMILY PROPERTIES LLC         | DOMESTIC LIMITED LIABILITY COMPANY | 2016-11-01T00:00:00 | REGISTERED AGENT            | PATRICIA   |             | FILIP         |        |                      |                             |                                 | 3425 BELKNAP DR                |                   | WEST LINN   | OR    | 97068    | 
| 126340397       | BREWSTER & CROCKER ARCHITECTS, P.C. | FOREIGN PROFESSIONAL CORPORATION   | 2016-11-01T00:00:00 | MAILING ADDRESS             |            |             |               |        |                      |                             |                                 | 410 BRADFORD ST NW             |                   | GAINESVILLE | GA    | 30501    | 
| 126340397       | BREWSTER & CROCKER ARCHITECTS, P.C. | FOREIGN PROFESSIONAL CORPORATION   | 2016-11-01T00:00:00 | PRINCIPAL PLACE OF BUSINESS |            |             |               |        |                      |                             |                                 | 410 BRADFORD ST NW             |                   | GAINESVILLE | GA    | 30501    | 
| 126340397       | BREWSTER & CROCKER ARCHITECTS, P.C. | FOREIGN PROFESSIONAL CORPORATION   | 2016-11-01T00:00:00 | REGISTERED AGENT            |            |             |               |        |                      | 75788399                    | REGISTERED AGENTS INC           | 5305 RIVER RD N STE B          |                   | KEIZER      | OR    | 97303    | 
```