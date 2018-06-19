# New Business List - January

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/new-business-list-january-9eddc) |
| Metadata | [Link](https://data.oregon.gov/api/views/v44b-kxkg) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/v44b-kxkg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/v44b-kxkg/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | v44b-kxkg |
| Name | New Business List - January |
| Category | Business |
| Tags | business name, registration |
| Created | 2012-03-01T15:45:13Z |
| Publication Date | 2017-03-01T16:50:59Z |

## Description

Businesses registered with the Secretary of State Corporation Division during the month of January.

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
| No       |             | address                     | Address                     | text      | text        |
| No       |             | address_continued           | Address Continued           | text      | text        |
| Yes      | series tag  | city                        | City                        | text      | text        |
| Yes      | series tag  | state                       | State                       | text      | text        |
| Yes      | series tag  | zip_code                    | Zip Code                    | text      | number      |
```

## Time Field

```ls
Value = registry_date
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address,address_continued
```

## Data Commands

```ls
series e:v44b-kxkg d:2016-01-04T00:00:00.000Z t:business_name="AEQUITAS EIF DEBT FUND, LLC" t:associated_name_type="MAILING ADDRESS" t:zip_code=97035 t:state=OR t:entity_type="FOREIGN LIMITED LIABILITY COMPANY" t:city="LAKE OSWEGO" t:registry_number=117457697 m:row_number.v44b-kxkg=1

series e:v44b-kxkg d:2016-01-04T00:00:00.000Z t:business_name="AEQUITAS EIF DEBT FUND, LLC" t:associated_name_type="PRINCIPAL PLACE OF BUSINESS" t:zip_code=97035 t:state=OR t:entity_type="FOREIGN LIMITED LIABILITY COMPANY" t:city="LAKE OSWEGO" t:registry_number=117457697 m:row_number.v44b-kxkg=2

series e:v44b-kxkg d:2016-01-04T00:00:00.000Z t:business_name="AEQUITAS EIF DEBT FUND, LLC" t:associated_name_type="REGISTERED AGENT" t:entity_of_record_name="AEQUITAS CAPITAL MANAGEMENT, INC." t:zip_code=97035 t:state=OR t:entity_type="FOREIGN LIMITED LIABILITY COMPANY" t:entity_of_record_reg_number=36908689 t:city="LAKE OSWEGO" t:registry_number=117457697 m:row_number.v44b-kxkg=3
```

## Meta Commands

```ls
metric m:row_number.v44b-kxkg p:long l:"Row Number"

entity e:v44b-kxkg l:"New Business List - January" t:url=https://data.oregon.gov/api/views/v44b-kxkg

property e:v44b-kxkg t:meta.view v:id=v44b-kxkg v:category=Business v:averageRating=0 v:name="New Business List - January"

property e:v44b-kxkg t:meta.view.owner v:id=ngr9-eh9y v:screenName="Judy Weems" v:displayName="Judy Weems"

property e:v44b-kxkg t:meta.view.tableauthor v:id=ngr9-eh9y v:screenName="Judy Weems" v:roleName=editor v:displayName="Judy Weems"
```

## Top Records

```ls
| registry_number | business_name                             | entity_type                       | registry_date | associated_name_type        | first_name | middle_name | last_name | suffix | not_of_record_entity | entity_of_record_reg_number | entity_of_record_name             | address                 | address_continued | city          | state | zip_code | 
| =============== | ========================================= | ================================= | ============= | =========================== | ========== | =========== | ========= | ====== | ==================== | =========================== | ================================= | ======================= | ================= | ============= | ===== | ======== | 
| 117457697       | AEQUITAS EIF DEBT FUND, LLC               | FOREIGN LIMITED LIABILITY COMPANY | 1451865600    | MAILING ADDRESS             |            |             |           |        |                      |                             |                                   | 5300 MEADOWS RD STE 400 |                   | LAKE OSWEGO   | OR    | 97035    | 
| 117457697       | AEQUITAS EIF DEBT FUND, LLC               | FOREIGN LIMITED LIABILITY COMPANY | 1451865600    | PRINCIPAL PLACE OF BUSINESS |            |             |           |        |                      |                             |                                   | 5300 MEADOWS RD STE 400 |                   | LAKE OSWEGO   | OR    | 97035    | 
| 117457697       | AEQUITAS EIF DEBT FUND, LLC               | FOREIGN LIMITED LIABILITY COMPANY | 1451865600    | REGISTERED AGENT            |            |             |           |        |                      | 36908689                    | AEQUITAS CAPITAL MANAGEMENT, INC. | 5300 MEADOWS RD STE 400 |                   | LAKE OSWEGO   | OR    | 97035    | 
| 117457697       | AEQUITAS EIF DEBT FUND, LLC               | FOREIGN LIMITED LIABILITY COMPANY | 1451865600    | REGISTERED AGENT            |            |             |           |        |                      | 36908689                    | JMW CAPITAL PARTNERS, INC         | 5300 MEADOWS RD STE 400 |                   | LAKE OSWEGO   | OR    | 97035    | 
| 117462598       | AGAMATRIX, INC.                           | FOREIGN BUSINESS CORPORATION      | 1451865600    | MAILING ADDRESS             |            |             |           |        |                      |                             |                                   | 7C RAYMOND AVE          |                   | SALEM         | NH    | 3079     | 
| 117462598       | AGAMATRIX, INC.                           | FOREIGN BUSINESS CORPORATION      | 1451865600    | PRINCIPAL PLACE OF BUSINESS |            |             |           |        |                      |                             |                                   | 7C RAYMOND AVE          |                   | SALEM         | NH    | 3079     | 
| 117462598       | AGAMATRIX, INC.                           | FOREIGN BUSINESS CORPORATION      | 1451865600    | REGISTERED AGENT            |            |             |           |        |                      | 329227                      | C T CORPORATION SYSTEM            | 388 STATE ST STE 420    |                   | SALEM         | OR    | 97301    | 
| 117466193       | ALLIED TUBE & CONDUIT                     | ASSUMED BUSINESS NAME             | 1451865600    | AUTHORIZED REPRESENTATIVE   | DANIEL     | S           | KELLY     |        |                      |                             |                                   | 16100 S LATHROP AVE     |                   | HARVEY        | IL    | 60426    | 
| 117466193       | ALLIED TUBE & CONDUIT                     | ASSUMED BUSINESS NAME             | 1451865600    | PRINCIPAL PLACE OF BUSINESS |            |             |           |        |                      |                             |                                   | 16100 S LATHROP AVE     |                   | HARVEY        | IL    | 60426    | 
| 117468199       | BLACK & VEATCH MANAGEMENT CONSULTING, LLC | FOREIGN LIMITED LIABILITY COMPANY | 1451865600    | MAILING ADDRESS             |            |             |           |        |                      |                             |                                   | 11401 LAMAR AVE         |                   | OVERLAND PARK | KS    | 66211    | 
```