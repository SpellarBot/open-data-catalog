# New Business List - May

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/new-business-list-may-0ea3a) |
| Metadata | [Link](https://data.oregon.gov/api/views/qnw2-qahx) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/qnw2-qahx/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/qnw2-qahx/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | qnw2-qahx |
| Name | New Business List - May |
| Category | Business |
| Tags | business name, registration |
| Created | 2012-07-02T15:49:28Z |
| Publication Date | 2016-06-28T16:11:11Z |

## Description

Businesses registered with the Secretary of State Corporation Division during the month of May

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
series e:qnw2-qahx d:2016-05-02T00:00:00.000Z t:business_name="A MAUI MOM CHILDCARE & PRESCHOOL, LLC" t:associated_name_type="REGISTERED AGENT" t:entity_of_record_name="UNITED STATES CORPORATION AGENTS, INC." t:zip_code=97030 t:state=OR t:entity_type="DOMESTIC LIMITED LIABILITY COMPANY" t:entity_of_record_reg_number=66022790 t:city=GRESHAM t:registry_number=121273296 m:row_number.qnw2-qahx=1

series e:qnw2-qahx d:2016-05-02T00:00:00.000Z t:business_name="A RIVER RUNS THROUGH MOBILE HOME AND RV PARK" t:associated_name_type="AUTHORIZED REPRESENTATIVE" t:entity_of_record_name="JAMES J. STOUT, P.C." t:zip_code=97501 t:state=OR t:entity_type="ASSUMED BUSINESS NAME" t:entity_of_record_reg_number=71999784 t:city=MEDFORD t:registry_number=121268692 m:row_number.qnw2-qahx=2

series e:qnw2-qahx d:2016-05-02T00:00:00.000Z t:business_name="A RIVER RUNS THROUGH MOBILE HOME AND RV PARK" t:associated_name_type="PRINCIPAL PLACE OF BUSINESS" t:zip_code=97525 t:state=OR t:entity_type="ASSUMED BUSINESS NAME" t:city="GOLD HILL" t:registry_number=121268692 m:row_number.qnw2-qahx=3
```

## Meta Commands

```ls
metric m:row_number.qnw2-qahx p:long l:"Row Number"

entity e:qnw2-qahx l:"New Business List - May" t:url=https://data.oregon.gov/api/views/qnw2-qahx

property e:qnw2-qahx t:meta.view v:id=qnw2-qahx v:category=Business v:averageRating=0 v:name="New Business List - May"

property e:qnw2-qahx t:meta.view.owner v:id=ngr9-eh9y v:screenName="Judy Weems" v:displayName="Judy Weems"

property e:qnw2-qahx t:meta.view.tableauthor v:id=ngr9-eh9y v:screenName="Judy Weems" v:roleName=editor v:displayName="Judy Weems"
```

## Top Records

```ls
| registry_number | business_name                                | entity_type                        | registry_date       | associated_name_type        | first_name | middle_name | last_name | suffix | not_of_record_entity | entity_of_record_reg_number | entity_of_record_name                    | address                              | address_continued | city      | state | zip_code | 
| =============== | ============================================ | ================================== | =================== | =========================== | ========== | =========== | ========= | ====== | ==================== | =========================== | ======================================== | ==================================== | ================= | ========= | ===== | ======== | 
| 121273296       | A MAUI MOM CHILDCARE & PRESCHOOL, LLC        | DOMESTIC LIMITED LIABILITY COMPANY | 2016-05-02T00:00:00 | REGISTERED AGENT            |            |             |           |        |                      | 66022790                    | UNITED STATES CORPORATION AGENTS, INC.   | 2951 NW DIVISION ST STE 110          |                   | GRESHAM   | OR    | 97030    | 
| 121268692       | A RIVER RUNS THROUGH MOBILE HOME AND RV PARK | ASSUMED BUSINESS NAME              | 2016-05-02T00:00:00 | AUTHORIZED REPRESENTATIVE   |            |             |           |        |                      | 71999784                    | JAMES J. STOUT, P.C.                     | 419 S OAKDALE AVE                    |                   | MEDFORD   | OR    | 97501    | 
| 121268692       | A RIVER RUNS THROUGH MOBILE HOME AND RV PARK | ASSUMED BUSINESS NAME              | 2016-05-02T00:00:00 | PRINCIPAL PLACE OF BUSINESS |            |             |           |        |                      |                             |                                          | 205 GARDEN ROW                       |                   | GOLD HILL | OR    | 97525    | 
| 121271290       | AFFORDABLE JANITORIAL LLC                    | DOMESTIC LIMITED LIABILITY COMPANY | 2016-05-02T00:00:00 | MAILING ADDRESS             |            |             |           |        |                      |                             |                                          | 4114 SUNNYVIEW RD NE SALEM OR APT 30 |                   | SALEM     | OR    | 97305    | 
| 121271290       | AFFORDABLE JANITORIAL LLC                    | DOMESTIC LIMITED LIABILITY COMPANY | 2016-05-02T00:00:00 | REGISTERED AGENT            | VLADISLAV  |             | STOYANOV  |        |                      |                             |                                          | 4114 SUNNYVIEW RD NE SALEM OR APT 30 |                   | SALEM     | OR    | 97305    | 
| 121273791       | BELLHOP BROTHERS IN CHEER                    | ASSUMED BUSINESS NAME              | 2016-05-02T00:00:00 | AUTHORIZED REPRESENTATIVE   |            |             |           |        |                      | 20006714                    | EVASHEVSKI & ELLIOTT, P.C.               | PO BOX 781                           |                   | CORVALLIS | OR    | 97339    | 
| 121273791       | BELLHOP BROTHERS IN CHEER                    | ASSUMED BUSINESS NAME              | 2016-05-02T00:00:00 | AUTHORIZED REPRESENTATIVE   |            |             |           |        |                      | 20006714                    | EVASHEVSKI, ELLIOTT & CIHAK, PC          | PO BOX 781                           |                   | CORVALLIS | OR    | 97339    | 
| 121273791       | BELLHOP BROTHERS IN CHEER                    | ASSUMED BUSINESS NAME              | 2016-05-02T00:00:00 | AUTHORIZED REPRESENTATIVE   |            |             |           |        |                      | 20006714                    | EVASHEVSKI, ELLIOTT, CIHAK & HEDIGER, PC | PO BOX 781                           |                   | CORVALLIS | OR    | 97339    | 
| 121273791       | BELLHOP BROTHERS IN CHEER                    | ASSUMED BUSINESS NAME              | 2016-05-02T00:00:00 | PRINCIPAL PLACE OF BUSINESS |            |             |           |        |                      |                             |                                          | 150 SW MADISON COURT                 |                   | CORVALLIS | OR    | 97333    | 
| 121260293       | BENNINGTON-DAVIS ENGINEERING, LLC            | DOMESTIC LIMITED LIABILITY COMPANY | 2016-05-02T00:00:00 | MAILING ADDRESS             |            |             |           |        |                      |                             |                                          | 23420 SW 65TH AVE                    |                   | TUALATIN  | OR    | 97062    | 
```