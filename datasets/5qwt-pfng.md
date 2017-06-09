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
| Publication Date | 2016-05-02T20:14:59Z |

## Description

Businesses registered with the Secretary of State Corporation Division during the month of April.

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
| Yes      | series tag  | entity_of_record_reg_number | Entity of Record Reg Number | text          | text          |
| Yes      | series tag  | not_of_record_entity        | Not of Record Entity        | text          | text          |
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
series e:5qwt-pfng d:2016-04-01T00:00:00.000Z t:business_name="ALBERTSON'S SAFEWAY PHARMACY #4705" t:associated_name_type="AUTHORIZED REPRESENTATIVE" t:entity_of_record_name="C T CORPORATION SYSTEM" t:zip_code=97301 t:state=OR t:entity_type="ASSUMED BUSINESS NAME" t:entity_of_record_reg_number=329227 t:city=SALEM t:registry_number=120367297 m:row_number.5qwt-pfng=1

series e:5qwt-pfng d:2016-04-01T00:00:00.000Z t:business_name="ALBERTSON'S SAFEWAY PHARMACY #4705" t:associated_name_type="PRINCIPAL PLACE OF BUSINESS" t:zip_code=90670 t:state=CA t:entity_type="ASSUMED BUSINESS NAME" t:city="SANTA FE SPRINGS" t:registry_number=120367297 m:row_number.5qwt-pfng=2

series e:5qwt-pfng d:2016-04-01T00:00:00.000Z t:business_name="AMBROSIA FARMS QUARTZ CREEK, LLC" t:associated_name_type="MAILING ADDRESS" t:zip_code=97532 t:state=OR t:entity_type="DOMESTIC LIMITED LIABILITY COMPANY" t:city=MERLIN t:registry_number=120350798 m:row_number.5qwt-pfng=3
```

## Meta Commands

```ls
metric m:row_number.5qwt-pfng p:long l:"Row Number"

entity e:5qwt-pfng l:"New Business List - April" t:url=https://data.oregon.gov/api/views/5qwt-pfng

property e:5qwt-pfng t:meta.view d:2017-06-09T13:55:02.258Z v:id=5qwt-pfng v:category=Business v:averageRating=0 v:name="New Business List - April"

property e:5qwt-pfng t:meta.view.owner d:2017-06-09T13:55:02.258Z v:id=ngr9-eh9y v:screenName="Judy Weems" v:displayName="Judy Weems"

property e:5qwt-pfng t:meta.view.tableauthor d:2017-06-09T13:55:02.258Z v:id=ngr9-eh9y v:screenName="Judy Weems" v:roleName=editor v:displayName="Judy Weems"
```

## Top Records

```ls
| registry_number | business_name                      | entity_type                        | registry_date       | associated_name_type        | first_name | middle_name | last_name | suffix | entity_of_record_reg_number | not_of_record_entity | entity_of_record_name           | address                      | address_continued | city             | state | zip_code | 
| =============== | ================================== | ================================== | =================== | =========================== | ========== | =========== | ========= | ====== | =========================== | ==================== | =============================== | ============================ | ================= | ================ | ===== | ======== | 
| 120367297       | ALBERTSON'S SAFEWAY PHARMACY #4705 | ASSUMED BUSINESS NAME              | 2016-04-01T00:00:00 | AUTHORIZED REPRESENTATIVE   |            |             |           |        | 329227                      |                      | C T CORPORATION SYSTEM          | 388 STATE ST STE 420         |                   | SALEM            | OR    | 97301    | 
| 120367297       | ALBERTSON'S SAFEWAY PHARMACY #4705 | ASSUMED BUSINESS NAME              | 2016-04-01T00:00:00 | PRINCIPAL PLACE OF BUSINESS |            |             |           |        |                             |                      |                                 | 12874 E FLORENCE AVE         |                   | SANTA FE SPRINGS | CA    | 90670    | 
| 120350798       | AMBROSIA FARMS QUARTZ CREEK, LLC   | DOMESTIC LIMITED LIABILITY COMPANY | 2016-04-01T00:00:00 | MAILING ADDRESS             |            |             |           |        |                             |                      |                                 | PO BOX 1052                  |                   | MERLIN           | OR    | 97532    | 
| 120350798       | AMBROSIA FARMS QUARTZ CREEK, LLC   | DOMESTIC LIMITED LIABILITY COMPANY | 2016-04-01T00:00:00 | REGISTERED AGENT            | NATALIE    | M           | WETENHALL |        |                             |                      |                                 | 542 WASHINGTON ST STE 104    |                   | ASHLAND          | OR    | 97520    | 
| 120351994       | ART DOCTOR                         | ASSUMED BUSINESS NAME              | 2016-04-01T00:00:00 | AUTHORIZED REPRESENTATIVE   | KEN        |             | PIERCE    |        |                             |                      |                                 | PO BOX 989                   |                   | KIMBERLY         | ID    | 83341    | 
| 120351994       | ART DOCTOR                         | ASSUMED BUSINESS NAME              | 2016-04-01T00:00:00 | PRINCIPAL PLACE OF BUSINESS |            |             |           |        |                             |                      |                                 | 3970 SW 97TH AVE             |                   | PORTLAND         | OR    | 97225    | 
| 120351192       | BAXTER SOLAR LLC                   | DOMESTIC LIMITED LIABILITY COMPANY | 2016-04-01T00:00:00 | MAILING ADDRESS             |            |             |           |        |                             | PETER K BROWN        |                                 | 5 CENTERPOINTE DR STE 250    |                   | LAKE OSWEGO      | OR    | 97035    | 
| 120351192       | BAXTER SOLAR LLC                   | DOMESTIC LIMITED LIABILITY COMPANY | 2016-04-01T00:00:00 | REGISTERED AGENT            |            |             |           |        | 8601296                     |                      | TT ADMINISTRATIVE SERVICES, LLC | 1600 PIONEER TOWER           | 888 SW FIFTH AVE  | PORTLAND         | OR    | 97204    | 
| 119830693       | BAY EQUITY LLC THE PLATINUM GROUP  | ASSUMED BUSINESS NAME              | 2016-04-01T00:00:00 | AUTHORIZED REPRESENTATIVE   | BRETT      |             | MCGOVERN  |        |                             |                      |                                 | 28 LIBERTY SHIP WAY STE 2800 |                   | SAUSALITO        | CA    | 94965    | 
| 119830693       | BAY EQUITY LLC THE PLATINUM GROUP  | ASSUMED BUSINESS NAME              | 2016-04-01T00:00:00 | PRINCIPAL PLACE OF BUSINESS |            |             |           |        |                             |                      |                                 | 28 LIBERTY SHIP WAY STE 2800 |                   | SAUSALITO        | CA    | 94965    | 
```