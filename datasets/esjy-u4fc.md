# New Businesses Registered Last Month

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/new-businesses-registered-last-month-322f8) |
| Metadata | [Link](https://data.oregon.gov/api/views/esjy-u4fc) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/esjy-u4fc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/esjy-u4fc/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | esjy-u4fc |
| Name | New Businesses Registered Last Month |
| Category | Business |
| Tags | business name, registration |
| Created | 2011-10-03T15:11:39Z |
| Publication Date | 2017-04-04T18:24:15Z |

## Description

New businesses registered with the Secretary of State Corporation Division during the previous month. Data is updated on the first working day of each month.

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
series e:esjy-u4fc d:2017-03-01T00:00:00.000Z t:business_name="1405 SW LAUREL, LLC" t:associated_name_type="MAILING ADDRESS" t:zip_code=97269 t:state=OR t:entity_type="DOMESTIC LIMITED LIABILITY COMPANY" t:city=PORTLAND t:registry_number=129894291 m:row_number.esjy-u4fc=1

series e:esjy-u4fc d:2017-03-01T00:00:00.000Z t:business_name="1405 SW LAUREL, LLC" t:associated_name_type="REGISTERED AGENT" t:first_name=D t:zip_code=97239 t:middle_name=BEN t:last_name=HENZEL t:state=OR t:entity_type="DOMESTIC LIMITED LIABILITY COMPANY" t:city=PORTLAND t:registry_number=129894291 m:row_number.esjy-u4fc=2

series e:esjy-u4fc d:2017-03-01T00:00:00.000Z t:business_name="ARMSTRONG 24 HOUR CARE HOME, LLC" t:associated_name_type="REGISTERED AGENT" t:entity_of_record_name="UNITED STATES CORPORATION AGENTS, INC." t:zip_code=97030 t:state=OR t:entity_type="DOMESTIC LIMITED LIABILITY COMPANY" t:entity_of_record_reg_number=66022790 t:city=GRESHAM t:registry_number=129886792 m:row_number.esjy-u4fc=3
```

## Meta Commands

```ls
metric m:row_number.esjy-u4fc p:long l:"Row Number"

entity e:esjy-u4fc l:"New Businesses Registered Last Month" t:url=https://data.oregon.gov/api/views/esjy-u4fc

property e:esjy-u4fc t:meta.view v:id=esjy-u4fc v:category=Business v:averageRating=0 v:name="New Businesses Registered Last Month"

property e:esjy-u4fc t:meta.view.owner v:id=ngr9-eh9y v:screenName="Judy Weems" v:displayName="Judy Weems"

property e:esjy-u4fc t:meta.view.tableauthor v:id=ngr9-eh9y v:screenName="Judy Weems" v:roleName=editor v:displayName="Judy Weems"
```

## Top Records

```ls
| registry_number | business_name                             | entity_type                        | registry_date       | associated_name_type        | first_name | middle_name | last_name | suffix | not_of_record_entity | entity_of_record_reg_number | entity_of_record_name                  | address_                    | address_continued        | city        | state | zip_code | 
| =============== | ========================================= | ================================== | =================== | =========================== | ========== | =========== | ========= | ====== | ==================== | =========================== | ====================================== | =========================== | ======================== | =========== | ===== | ======== | 
| 129894291       | 1405 SW LAUREL, LLC                       | DOMESTIC LIMITED LIABILITY COMPANY | 2017-03-01T00:00:00 | MAILING ADDRESS             |            |             |           |        |                      |                             |                                        | HENZEL LAW OFFICES          | PO BOX 220027            | PORTLAND    | OR    | 97269    | 
| 129894291       | 1405 SW LAUREL, LLC                       | DOMESTIC LIMITED LIABILITY COMPANY | 2017-03-01T00:00:00 | REGISTERED AGENT            | D          | BEN         | HENZEL    |        |                      |                             |                                        | 0224 SW HAMILTON ST STE 301 |                          | PORTLAND    | OR    | 97239    | 
| 129886792       | ARMSTRONG 24 HOUR CARE HOME, LLC          | DOMESTIC LIMITED LIABILITY COMPANY | 2017-03-01T00:00:00 | REGISTERED AGENT            |            |             |           |        |                      | 66022790                    | UNITED STATES CORPORATION AGENTS, INC. | 2951 NW DIVISION ST STE 110 |                          | GRESHAM     | OR    | 97030    | 
| 129895090       | B.A.S. QUINCY LLC                         | FOREIGN LIMITED LIABILITY COMPANY  | 2017-03-01T00:00:00 | MAILING ADDRESS             |            |             |           |        |                      |                             |                                        | 1300 S WEBB PL              |                          | E WENATCHEE | WA    | 98802    | 
| 129895090       | B.A.S. QUINCY LLC                         | FOREIGN LIMITED LIABILITY COMPANY  | 2017-03-01T00:00:00 | PRINCIPAL PLACE OF BUSINESS |            |             |           |        |                      |                             |                                        | 1300 S WEBB PL              |                          | E WENATCHEE | WA    | 98802    | 
| 129895090       | B.A.S. QUINCY LLC                         | FOREIGN LIMITED LIABILITY COMPANY  | 2017-03-01T00:00:00 | REGISTERED AGENT            |            |             |           |        |                      | 46258083                    | NATIONAL REGISTERED AGENTS, INC.       | 388 STATE ST STE 420        |                          | SALEM       | OR    | 97301    | 
| 129891693       | BANKS VETERINARY SERVICE                  | ASSUMED BUSINESS NAME              | 2017-03-01T00:00:00 | AUTHORIZED REPRESENTATIVE   |            |             |           |        |                      | 129222097                   | POST & BERNARDS PC                     | PO BOX 69                   |                          | BANKS       | OR    | 97106    | 
| 129891693       | BANKS VETERINARY SERVICE                  | ASSUMED BUSINESS NAME              | 2017-03-01T00:00:00 | PRINCIPAL PLACE OF BUSINESS |            |             |           |        |                      |                             |                                        | 13541 NW MAIN ST            |                          | BANKS       | OR    | 97106    | 
| 129884193       | BECKER/MARK REAL ESTATE INVESTORS II, LLC | DOMESTIC LIMITED LIABILITY COMPANY | 2017-03-01T00:00:00 | REGISTERED AGENT            |            |             |           |        |                      | 11519618                    | BECKER CAPITAL MANAGEMENT, INC.        | 1211 SW FIFTH AVE STE 2185  | ATTN PATRICK E BECKER JR | PORTLAND    | OR    | 97204    | 
| 129884193       | BECKER/MARK REAL ESTATE INVESTORS II, LLC | DOMESTIC LIMITED LIABILITY COMPANY | 2017-03-01T00:00:00 | REGISTERED AGENT            |            |             |           |        |                      | 11519618                    | P. E. BECKER, INC.                     | 1211 SW FIFTH AVE STE 2185  | ATTN PATRICK E BECKER JR | PORTLAND    | OR    | 97204    | 
```