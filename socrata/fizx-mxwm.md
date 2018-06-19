# New Business List - December

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/new-business-list-december-db6ff) |
| Metadata | [Link](https://data.oregon.gov/api/views/fizx-mxwm) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/fizx-mxwm/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/fizx-mxwm/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | fizx-mxwm |
| Name | New Business List - December |
| Category | Business |
| Tags | business name, registration |
| Created | 2012-02-01T17:21:19Z |
| Publication Date | 2017-02-14T20:11:04Z |

## Description

Businesses registered with the Secretary of State Corporation Division during the month of December.

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
| No       |             | address_                    | Address                     | text          | text          |
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
Excluded Fields = address_,address_continued
```

## Data Commands

```ls
series e:fizx-mxwm d:2016-12-01T00:00:00.000Z t:business_name="2900 GORDON LP" t:associated_name_type="GENERAL PARTNER" t:zip_code=95054 t:not_of_record_entity="DPJV TIC MANAGEMENT LLC, A CALIFORNIA LLC" t:state=CA t:entity_type="FOREIGN LIMITED PARTNERSHIP" t:city="SANTA CLARA" t:registry_number=127129591 m:row_number.fizx-mxwm=1

series e:fizx-mxwm d:2016-12-01T00:00:00.000Z t:business_name="2900 GORDON LP" t:associated_name_type="MAILING ADDRESS" t:zip_code=95054 t:state=CA t:entity_type="FOREIGN LIMITED PARTNERSHIP" t:city="SANTA CLARA" t:registry_number=127129591 m:row_number.fizx-mxwm=2

series e:fizx-mxwm d:2016-12-01T00:00:00.000Z t:business_name="2900 GORDON LP" t:associated_name_type="RECORDS OFFICE" t:zip_code=95054 t:state=CA t:entity_type="FOREIGN LIMITED PARTNERSHIP" t:city="SANTA CLARA" t:registry_number=127129591 m:row_number.fizx-mxwm=3
```

## Meta Commands

```ls
metric m:row_number.fizx-mxwm p:long l:"Row Number"

entity e:fizx-mxwm l:"New Business List - December" t:url=https://data.oregon.gov/api/views/fizx-mxwm

property e:fizx-mxwm t:meta.view v:id=fizx-mxwm v:category=Business v:averageRating=0 v:name="New Business List - December"

property e:fizx-mxwm t:meta.view.owner v:id=ngr9-eh9y v:screenName="Judy Weems" v:displayName="Judy Weems"

property e:fizx-mxwm t:meta.view.tableauthor v:id=ngr9-eh9y v:screenName="Judy Weems" v:roleName=editor v:displayName="Judy Weems"
```

## Top Records

```ls
| registry_number | business_name  | entity_type                 | registry_date       | associated_name_type | first_name | middle_name | last_name | suffix | not_of_record_entity                      | entity_of_record_reg_number | entity_of_record_name             | address_                | address_continued             | city        | state | zip_code | 
| =============== | ============== | =========================== | =================== | ==================== | ========== | =========== | ========= | ====== | ========================================= | =========================== | ================================= | ======================= | ============================= | =========== | ===== | ======== | 
| 127129591       | 2900 GORDON LP | FOREIGN LIMITED PARTNERSHIP | 2016-12-01T00:00:00 | GENERAL PARTNER      |            |             |           |        | DPJV TIC MANAGEMENT LLC, A CALIFORNIA LLC |                             |                                   | C/O PEARLMAN PROPERTIES | 4633 OLD IRONSIDES DR STE 100 | SANTA CLARA | CA    | 95054    | 
| 127129591       | 2900 GORDON LP | FOREIGN LIMITED PARTNERSHIP | 2016-12-01T00:00:00 | MAILING ADDRESS      |            |             |           |        |                                           |                             |                                   | C/O PEARLMAN PROPERTIES | 4633 OLD IRONSIDES DR STE 100 | SANTA CLARA | CA    | 95054    | 
| 127129591       | 2900 GORDON LP | FOREIGN LIMITED PARTNERSHIP | 2016-12-01T00:00:00 | RECORDS OFFICE       |            |             |           |        |                                           |                             |                                   | C/O PEARLMAN PROPERTIES | 4633 OLD IRONSIDES DR STE 100 | SANTA CLARA | CA    | 95054    | 
| 127129591       | 2900 GORDON LP | FOREIGN LIMITED PARTNERSHIP | 2016-12-01T00:00:00 | REGISTERED AGENT     |            |             |           |        |                                           | 56822381                    | NATIONAL CORPORATE RESEARCH, LTD. | 325 13TH ST NE STE 404  |                               | SALEM       | OR    | 97301    | 
| 127130193       | 2901 GORDON LP | FOREIGN LIMITED PARTNERSHIP | 2016-12-01T00:00:00 | GENERAL PARTNER      |            |             |           |        | PJV TIC MANAGEMENT LLC, A CALIFORNIA LLC  |                             |                                   | C/O PEARLMAN PROPERTIES | 4633 OLD IRONSIDES DR STE 100 | SANTA CLARA | CA    | 95054    | 
| 127130193       | 2901 GORDON LP | FOREIGN LIMITED PARTNERSHIP | 2016-12-01T00:00:00 | MAILING ADDRESS      |            |             |           |        |                                           |                             |                                   | C/O PEARLMAN PROPERTIES | 4633 OLD IRONSIDES DR STE 100 | SANTA CLARA | CA    | 95054    | 
| 127130193       | 2901 GORDON LP | FOREIGN LIMITED PARTNERSHIP | 2016-12-01T00:00:00 | RECORDS OFFICE       |            |             |           |        |                                           |                             |                                   | C/O PEARLMAN PROPERTIES | 4633 OLD IRONSIDES DR STE 100 | SANTA CLARA | CA    | 95054    | 
| 127130193       | 2901 GORDON LP | FOREIGN LIMITED PARTNERSHIP | 2016-12-01T00:00:00 | REGISTERED AGENT     |            |             |           |        |                                           | 56822381                    | NATIONAL CORPORATE RESEARCH, LTD. | 325 13TH ST NE STE 404  |                               | SALEM       | OR    | 97301    | 
| 127129898       | 2951 GORDON LP | FOREIGN LIMITED PARTNERSHIP | 2016-12-01T00:00:00 | GENERAL PARTNER      |            |             |           |        | PJV TIC MANAGEMENT LLC, A CALIFORNIA LLC  |                             |                                   | C/O PEARLMAN PROPERTIES | 4633 OLD IRONSIDES DR STE 100 | SANTA CLARA | CA    | 95054    | 
| 127129898       | 2951 GORDON LP | FOREIGN LIMITED PARTNERSHIP | 2016-12-01T00:00:00 | MAILING ADDRESS      |            |             |           |        |                                           |                             |                                   | C/O PEARLMAN PROPERTIES | 4633 OLD IRONSIDES DR STE 100 | SANTA CLARA | CA    | 95054    | 
```