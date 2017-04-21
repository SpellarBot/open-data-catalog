# Active Nonprofit Corporations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/active-nonprofit-corporations-9860e) |
| Metadata | [Link](https://data.oregon.gov/api/views/8kyv-b2kw) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/8kyv-b2kw/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/8kyv-b2kw/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | 8kyv-b2kw |
| Name | Active Nonprofit Corporations |
| Category | Business |
| Tags | nonprofit, nonprofit name, registration |
| Created | 2012-05-01T20:50:34Z |
| Publication Date | 2017-04-04T16:46:33Z |

## Description

Updated 4/4/2017. Nonprofit corporations active on the record of the Secretary of State Corporation Division as of the first working day of the month.

## Columns

```ls
| Included | Schema Type | Field Name                  | Name                        | Data Type | Render Type |
| ======== | =========== | =========================== | =========================== | ========= | =========== |
| Yes      | series tag  | registry_number             | Registry Number             | text      | text        |
| Yes      | series tag  | business_name               | Business Name               | text      | text        |
| Yes      | series tag  | entity_type                 | Entity Type                 | text      | text        |
| Yes      | time        | registry_date               | Registry Date               | text      | text        |
| Yes      | series tag  | nonprofit_type              | Nonprofit Type              | text      | text        |
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
| Yes      | series tag  | zip_code                    | Zip Code                    | text      | text        |
```

## Time Field

```ls
Value = registry_date
Format & Zone = yyyy-MM-dd HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = address,address_continued
```

## Data Commands

```ls
series e:8kyv-b2kw d:1850-05-17T00:00:00.000Z t:business_name="UNITED METHODIST CHURCH, OREGON CITY, OREGON" t:associated_name_type="MAILING ADDRESS" t:zip_code=97045 t:state=OR t:nonprofit_type="RELIGIOUS WITH MEMBERS" t:entity_type="DOMESTIC NONPROFIT CORPORATION" t:city="OREGON CITY" t:registry_number=299818 m:row_number.8kyv-b2kw=1

series e:8kyv-b2kw d:1850-05-17T00:00:00.000Z t:business_name="UNITED METHODIST CHURCH, OREGON CITY, OREGON" t:associated_name_type=PRESIDENT t:first_name=JANE t:zip_code=97045 t:last_name=MYERS t:state=OR t:nonprofit_type="RELIGIOUS WITH MEMBERS" t:entity_type="DOMESTIC NONPROFIT CORPORATION" t:city="OREGON CITY" t:registry_number=299818 m:row_number.8kyv-b2kw=2

series e:8kyv-b2kw d:1850-05-17T00:00:00.000Z t:business_name="UNITED METHODIST CHURCH, OREGON CITY, OREGON" t:associated_name_type="PRINCIPAL PLACE OF BUSINESS" t:zip_code=97045 t:state=OR t:nonprofit_type="RELIGIOUS WITH MEMBERS" t:entity_type="DOMESTIC NONPROFIT CORPORATION" t:city="OREGON CITY" t:registry_number=299818 m:row_number.8kyv-b2kw=3
```

## Meta Commands

```ls
metric m:row_number.8kyv-b2kw p:long l:"Row Number"

entity e:8kyv-b2kw l:"Active Nonprofit Corporations" t:url=https://data.oregon.gov/api/views/8kyv-b2kw

property e:8kyv-b2kw t:meta.view v:id=8kyv-b2kw v:category=Business v:averageRating=0 v:name="Active Nonprofit Corporations"

property e:8kyv-b2kw t:meta.view.owner v:id=ngr9-eh9y v:screenName="Judy Weems" v:displayName="Judy Weems"

property e:8kyv-b2kw t:meta.view.tableauthor v:id=ngr9-eh9y v:screenName="Judy Weems" v:roleName=editor v:displayName="Judy Weems"
```

## Top Records

```ls
| registry_number | business_name                                | entity_type                    | registry_date       | nonprofit_type         | associated_name_type        | first_name | middle_name | last_name | suffix | not_of_record_entity | entity_of_record_reg_number | entity_of_record_name | address              | address_continued | city        | state | zip_code | 
| =============== | ============================================ | ============================== | =================== | ====================== | =========================== | ========== | =========== | ========= | ====== | ==================== | =========================== | ===================== | ==================== | ================= | =========== | ===== | ======== | 
| 299818          | UNITED METHODIST CHURCH, OREGON CITY, OREGON | DOMESTIC NONPROFIT CORPORATION | 1850-05-17 00:00:00 | RELIGIOUS WITH MEMBERS | MAILING ADDRESS             |            |             |           |        |                      |                             |                       | 18955 S SOUTH END RD |                   | OREGON CITY | OR    | 97045    | 
| 299818          | UNITED METHODIST CHURCH, OREGON CITY, OREGON | DOMESTIC NONPROFIT CORPORATION | 1850-05-17 00:00:00 | RELIGIOUS WITH MEMBERS | PRESIDENT                   | JANE       |             | MYERS     |        |                      |                             |                       | 18955 S SOUTH END RD |                   | OREGON CITY | OR    | 97045    | 
| 299818          | UNITED METHODIST CHURCH, OREGON CITY, OREGON | DOMESTIC NONPROFIT CORPORATION | 1850-05-17 00:00:00 | RELIGIOUS WITH MEMBERS | PRINCIPAL PLACE OF BUSINESS |            |             |           |        |                      |                             |                       | 18955 S SOUTH END RD |                   | OREGON CITY | OR    | 97045    | 
| 299818          | UNITED METHODIST CHURCH, OREGON CITY, OREGON | DOMESTIC NONPROFIT CORPORATION | 1850-05-17 00:00:00 | RELIGIOUS WITH MEMBERS | REGISTERED AGENT            | MIKE       |             | BENISCHEK |        |                      |                             |                       | 18955 S SOUTH END RD |                   | OREGON CITY | OR    | 97045    | 
| 299818          | UNITED METHODIST CHURCH, OREGON CITY, OREGON | DOMESTIC NONPROFIT CORPORATION | 1850-05-17 00:00:00 | RELIGIOUS WITH MEMBERS | SECRETARY                   | CHRISTA    |             | PALMER    |        |                      |                             |                       | 18955 S SOUTH END RD |                   | OREGON CITY | OR    | 97045    | 
| 574418          | WILLAMETTE UNIVERSITY                        | DOMESTIC NONPROFIT CORPORATION | 1853-01-21 00:00:00 | PUBLIC BENEFIT         | MAILING ADDRESS             |            |             |           |        |                      |                             |                       | 900 STATE ST         |                   | SALEM       | OR    | 97301    | 
| 574418          | WILLAMETTE UNIVERSITY                        | DOMESTIC NONPROFIT CORPORATION | 1853-01-21 00:00:00 | PUBLIC BENEFIT         | PRESIDENT                   | STEPHEN    | E           | THORSETT  |        |                      |                             |                       | 900 STATE ST         |                   | SALEM       | OR    | 97301    | 
| 574418          | WILLAMETTE UNIVERSITY                        | DOMESTIC NONPROFIT CORPORATION | 1853-01-21 00:00:00 | PUBLIC BENEFIT         | PRINCIPAL PLACE OF BUSINESS |            |             |           |        |                      |                             |                       | 900 STATE ST         |                   | SALEM       | OR    | 97301    | 
| 574418          | WILLAMETTE UNIVERSITY                        | DOMESTIC NONPROFIT CORPORATION | 1853-01-21 00:00:00 | PUBLIC BENEFIT         | REGISTERED AGENT            | MONICA     |             | RIMAI     |        |                      |                             |                       | 900 STATE ST         |                   | SALEM       | OR    | 97301    | 
| 574418          | WILLAMETTE UNIVERSITY                        | DOMESTIC NONPROFIT CORPORATION | 1853-01-21 00:00:00 | PUBLIC BENEFIT         | SECRETARY                   | SANDRA     | M           | ROWE      |        |                      |                             |                       | 900 STATE ST         |                   | SALEM       | OR    | 97301    | 
```