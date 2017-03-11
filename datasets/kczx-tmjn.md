# IntelCorporation

## Dataset

* [Dataset URL](https://data.oregon.gov/api/views/kczx-tmjn/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/intelcorporation-d1a56)
* [Metadata URL](https://data.oregon.gov/api/views/kczx-tmjn)
* Id = kczx-tmjn
* Name = IntelCorporation
* Created = 2013-09-26T23:23:58Z
* Publication Date = 2013-09-26T23:55:47Z
* Rows Updated = 2014-04-23T00:37:42Z

## Description



## Columns

```ls
| Name                | Field Name          | Data Type | Render Type | Schema Type | Included | 
| =================== | =================== | ========= | =========== | =========== | ======== | 
| updated_at          | :updated_at         | meta_data | meta_data   | time        | No       | 
| First Name          | first_name          | text      | text        | series tag  | Yes      | 
| Last Name           | last_name           | text      | text        | series tag  | Yes      | 
| Email Address       | email_address       | email     | email       |             | No       | 
| Organization        | organization        | text      | text        | series tag  | Yes      | 
| State               | state               | text      | text        | series tag  | Yes      | 
| Comment             | comment             | html      | html        | series tag  | Yes      | 
| Additional Document | additional_document | document  | document    | series tag  | Yes      | 
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = email_address
Annotation Fields = 
```

## Data Commands

```ls





```

## Meta Commands

```ls
entity e:kczx-tmjn l:IntelCorporation t:url=https://data.oregon.gov/api/views/kczx-tmjn

property e:kczx-tmjn t:meta.view d:2017-03-07T19:37:56.279Z v:id=kczx-tmjn v:averageRating=0 v:name=IntelCorporation

property e:kczx-tmjn t:meta.view.owner d:2017-03-07T19:37:56.279Z v:id=44u9-wper v:screenName="MT Oregon DEQ" v:roleName=editor v:displayName="MT Oregon DEQ"

property e:kczx-tmjn t:meta.view.tableauthor d:2017-03-07T19:37:56.279Z v:id=44u9-wper v:screenName="MT Oregon DEQ" v:roleName=editor v:displayName="MT Oregon DEQ"
```