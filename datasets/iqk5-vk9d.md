# New Business List - March

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/new-business-list-march-26c5b) |
| Metadata | [Link](https://data.oregon.gov/api/views/iqk5-vk9d) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/iqk5-vk9d/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/iqk5-vk9d/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | iqk5-vk9d |
| Name | New Business List - March |
| Category | Business |
| Tags | business name, registration |
| Created | 2012-05-01T15:15:12Z |
| Publication Date | 2016-06-28T15:50:11Z |

## Description

Businesses registered with the Secretary of State Corporation Division during the month of March.

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
series e:iqk5-vk9d d:2016-03-01T00:00:00.000Z t:business_name="365 BY WHOLE FOODS MARKET" t:associated_name_type="AUTHORIZED REPRESENTATIVE" t:first_name=ALBERT t:zip_code=78703 t:last_name=PERCIVAL t:state=TX t:entity_type="ASSUMED BUSINESS NAME" t:city=AUSTIN t:registry_number=119336493 m:row_number.iqk5-vk9d=1

series e:iqk5-vk9d d:2016-03-01T00:00:00.000Z t:business_name="365 BY WHOLE FOODS MARKET" t:associated_name_type="PRINCIPAL PLACE OF BUSINESS" t:zip_code=97034 t:state=OR t:entity_type="ASSUMED BUSINESS NAME" t:city="LAKE OSWEGO" t:registry_number=119336493 m:row_number.iqk5-vk9d=2

series e:iqk5-vk9d d:2016-03-01T00:00:00.000Z t:business_name="ACMA, INC." t:associated_name_type="REGISTERED AGENT" t:entity_of_record_name="AW SERVICES, INC." t:zip_code=97209 t:state=OR t:entity_type="DOMESTIC BUSINESS CORPORATION" t:entity_of_record_reg_number=59372384 t:city=PORTLAND t:registry_number=119347193 m:row_number.iqk5-vk9d=3
```

## Meta Commands

```ls
metric m:row_number.iqk5-vk9d p:long l:"Row Number"

entity e:iqk5-vk9d l:"New Business List - March" t:url=https://data.oregon.gov/api/views/iqk5-vk9d

property e:iqk5-vk9d t:meta.view v:id=iqk5-vk9d v:category=Business v:averageRating=0 v:name="New Business List - March"

property e:iqk5-vk9d t:meta.view.owner v:id=ngr9-eh9y v:screenName="Judy Weems" v:displayName="Judy Weems"

property e:iqk5-vk9d t:meta.view.tableauthor v:id=ngr9-eh9y v:screenName="Judy Weems" v:roleName=editor v:displayName="Judy Weems"
```

## Top Records

```ls
| registry_number | business_name               | entity_type                        | registry_date       | associated_name_type        | first_name | middle_name | last_name | suffix | not_of_record_entity | entity_of_record_reg_number | entity_of_record_name            | address                       | address_continued          | city        | state | zip_code | 
| =============== | =========================== | ================================== | =================== | =========================== | ========== | =========== | ========= | ====== | ==================== | =========================== | ================================ | ============================= | ========================== | =========== | ===== | ======== | 
| 119336493       | 365 BY WHOLE FOODS MARKET   | ASSUMED BUSINESS NAME              | 2016-03-01T00:00:00 | AUTHORIZED REPRESENTATIVE   | ALBERT     |             | PERCIVAL  |        |                      |                             |                                  | 550 BOWIE ST                  |                            | AUSTIN      | TX    | 78703    | 
| 119336493       | 365 BY WHOLE FOODS MARKET   | ASSUMED BUSINESS NAME              | 2016-03-01T00:00:00 | PRINCIPAL PLACE OF BUSINESS |            |             |           |        |                      |                             |                                  | 11 SOUTH STATE ST             |                            | LAKE OSWEGO | OR    | 97034    | 
| 119347193       | ACMA, INC.                  | DOMESTIC BUSINESS CORPORATION      | 2016-03-01T00:00:00 | REGISTERED AGENT            |            |             |           |        |                      | 59372384                    | AW SERVICES, INC.                | C/O ATER WYNNE LLP            | 1331 NW LOVEJOY ST STE 900 | PORTLAND    | OR    | 97209    | 
| 119331494       | ANANDA, LLC                 | DOMESTIC LIMITED LIABILITY COMPANY | 2016-03-01T00:00:00 | REGISTERED AGENT            | ALEX       |             | RODRIGUEZ |        |                      |                             |                                  | 322 NW 5TH AVE STE 301C       |                            | PORTLAND    | OR    | 97209    | 
| 119349892       | BLUE SKY AG CONSULTING, LLC | DOMESTIC LIMITED LIABILITY COMPANY | 2016-03-01T00:00:00 | MAILING ADDRESS             |            |             |           |        |                      |                             |                                  | PO BOX 625                    |                            | MCMINNVILLE | OR    | 97128    | 
| 119349892       | BLUE SKY AG CONSULTING, LLC | DOMESTIC LIMITED LIABILITY COMPANY | 2016-03-01T00:00:00 | REGISTERED AGENT            |            |             |           |        |                      | 98311591                    | TANKERSLEY, WRIGHT & STRUNK, LLC | 701 NE EVANS ST               |                            | MCMINNVILLE | OR    | 97128    | 
| 119350593       | CAPITAL LOGIC, LLC          | DOMESTIC LIMITED LIABILITY COMPANY | 2016-03-01T00:00:00 | REGISTERED AGENT            | JON        |             | STADICK   |        |                      |                             |                                  | 4860 JUSTICE WAY S            |                            | SALEM       | OR    | 97302    | 
| 119350098       | CHERRY                      | ASSUMED BUSINESS NAME              | 2016-03-01T00:00:00 | AUTHORIZED REPRESENTATIVE   | LEANNE     | M           | BOWKER    |        |                      |                             |                                  | 10300 SW GREENBURG RD STE 530 |                            | PORTLAND    | OR    | 97223    | 
| 119350098       | CHERRY                      | ASSUMED BUSINESS NAME              | 2016-03-01T00:00:00 | PRINCIPAL PLACE OF BUSINESS |            |             |           |        |                      |                             |                                  | 2376 SE 45TH AVE              |                            | PORTLAND    | OR    | 97215    | 
| 119350395       | CHERRY MAGAZINE             | ASSUMED BUSINESS NAME              | 2016-03-01T00:00:00 | AUTHORIZED REPRESENTATIVE   | LEANNE     | M           | BOWKER    |        |                      |                             |                                  | 10300 SW GREENBURG RD STE 530 |                            | PORTLAND    | OR    | 97223    | 
```