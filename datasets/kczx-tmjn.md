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

## Columns

```ls
| Included | Schema Type | Field Name          | Name                | Data Type | Render Type |
| ======== | =========== | =================== | =================== | ========= | =========== |
| No       | time        | :updated_at         | updated_at          | meta_data | meta_data   |
| Yes      | series tag  | first_name          | First Name          | text      | text        |
| Yes      | series tag  | last_name           | Last Name           | text      | text        |
| Yes      | series tag  | email_address       | Email Address       | email     | email       |
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

## Data Commands

```ls
series e:kczx-tmjn d:2013-09-30T15:31:24.000Z t:first_name=David t:organization="Self: Citizen Air Breather" t:state=Oregon t:last_name=Hoffman t:comment="Proposed new higher limits are NOT good enough but are a step in the right direction." t:email_address=fixit@efn.org m:row_number.kczx-tmjn=1

series e:kczx-tmjn d:2013-09-30T17:23:48.000Z t:first_name=David t:state=Oregon t:last_name=Newman t:comment="The form of fluoride emmissions by Intel must be specified in the permit. Specific forms of fluoride must be measured and reported by DEQ and Intel. For example, if hydrofluoric acid (HF) is included in Intel's emmissions, there are serious health and environmental effects. Many fluorine containing chemical compounds, such as fluorocarbons, are harmful to the environment. All specific fluoride compound emmisions should be monitored." t:email_address=md.newman@comcast.net m:row_number.kczx-tmjn=2

series e:kczx-tmjn d:2013-10-06T14:44:22.000Z t:first_name=Anne t:organization=NFCA t:state=Oregon t:last_name=Ferguson t:comment="I wish to express my opposition to any renewal of any permit for emissions until there is more transparency and  more oversight of the ROnler Acres plant in Hillsboro" t:email_address=ArtistAnne@Paganini.us m:row_number.kczx-tmjn=3
```

## Meta Commands

```ls
metric m:row_number.kczx-tmjn p:long l:"Row Number"

entity e:kczx-tmjn l:IntelCorporation t:url=https://data.oregon.gov/api/views/kczx-tmjn

property e:kczx-tmjn t:meta.view v:id=kczx-tmjn v:averageRating=0 v:name=IntelCorporation

property e:kczx-tmjn t:meta.view.owner v:id=44u9-wper v:screenName="MT Oregon DEQ" v:displayName="MT Oregon DEQ"

property e:kczx-tmjn t:meta.view.tableauthor v:id=44u9-wper v:screenName="MT Oregon DEQ" v:roleName=editor v:displayName="MT Oregon DEQ"
```