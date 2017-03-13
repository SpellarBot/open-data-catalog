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
| Rows Updated | 2016-05-02T20:13:55Z |

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
| Yes      | series tag  | address_continued           | Address Continued           | text          | text          |
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
Excluded Fields = address
```

## Data Commands

```ls
```

## Meta Commands

```ls
entity e:5qwt-pfng l:"New Business List - April" t:url=https://data.oregon.gov/api/views/5qwt-pfng

property e:5qwt-pfng t:meta.view v:id=5qwt-pfng v:category=Business v:averageRating=0 v:name="New Business List - April"

property e:5qwt-pfng t:meta.view.owner v:id=ngr9-eh9y v:screenName="Judy Weems" v:roleName=editor v:displayName="Judy Weems"

property e:5qwt-pfng t:meta.view.tableauthor v:id=ngr9-eh9y v:screenName="Judy Weems" v:roleName=editor v:displayName="Judy Weems"
```