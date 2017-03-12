# IntelCorporation

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/intelcorporation-d1a56) |
| Metadata | [Link](https://data.oregon.gov/api/views/kczx-tmjn) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/kczx-tmjn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/kczx-tmjn/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | kczx-tmjn |
| Name | IntelCorporation |
| Created | 2013-09-26T23:23:58Z |
| Publication Date | 2013-09-26T23:55:47Z |
| Rows Updated | 2014-04-23T00:37:42Z |

## Columns

```ls
| Included | Schema Type | Field Name          | Name                | Data Type | Render Type |
| ======== | =========== | =================== | =================== | ========= | =========== |
| No       | time        | :updated_at         | updated_at          | meta_data | meta_data   |
| Yes      | series tag  | first_name          | First Name          | text      | text        |
| Yes      | series tag  | last_name           | Last Name           | text      | text        |
| No       |             | email_address       | Email Address       | email     | email       |
| Yes      | series tag  | organization        | Organization        | text      | text        |
| Yes      | series tag  | state               | State               | text      | text        |
| Yes      | series tag  | comment             | Comment             | html      | html        |
| Yes      | series tag  | additional_document | Additional Document | document  | document    |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = email_address
```

## Data Commands

```ls
```

## Meta Commands

```ls
entity e:kczx-tmjn l:IntelCorporation t:url=https://data.oregon.gov/api/views/kczx-tmjn

property e:kczx-tmjn t:meta.view v:id=kczx-tmjn v:averageRating=0 v:name=IntelCorporation

property e:kczx-tmjn t:meta.view.owner v:id=44u9-wper v:screenName="MT Oregon DEQ" v:roleName=editor v:displayName="MT Oregon DEQ"

property e:kczx-tmjn t:meta.view.tableauthor v:id=44u9-wper v:screenName="MT Oregon DEQ" v:roleName=editor v:displayName="MT Oregon DEQ"
```