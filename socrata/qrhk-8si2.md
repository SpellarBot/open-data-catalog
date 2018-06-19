# Statement of Economic Interests (SEI) (Form 700) - Filers with unpaid late filing fees

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/statement-of-economic-interests-sei-form-700-filers-with-unpaid-late-filing-fees-5da1c) |
| Metadata | [Link](https://data.sfgov.org/api/views/qrhk-8si2) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/qrhk-8si2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/qrhk-8si2/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | qrhk-8si2 |
| Name | Statement of Economic Interests (SEI) (Form 700) - Filers with unpaid late filing fees |
| Attribution | San Francisco Ethics Commission |
| Category | City Management and Ethics |
| Tags | statement of economic interests, sei, form 700, ethics, conflict of interest, unpaid, late, filing, fees |
| Created | 2013-10-01T22:10:00Z |
| Publication Date | 2015-06-01T23:59:15Z |

## Description

The Statement of Economic Interests (SEI) filers listed in the table below have not paid their late filing fees. The filers listed below have not responded to a direct written or a verbal notice to their Commission regarding late filing fees. Filers posted to this list for not paying late filing fees are removed from this list after paying their late fees or four (4) years have elapsed since the Executive Director??s final determination of the late fees (i.e., the date the late fees are assessed or the date the Executive Director makes a determination in response to a request for waiver, if any).

## Columns

```ls
| Included | Schema Type    | Field Name                     | Name                           | Data Type | Render Type |
| ======== | ============== | ============================== | ============================== | ========= | =========== |
| No       | time           | :updated_at                    | updated_at                     | meta_data | meta_data   |
| Yes      | series tag     | commissioner_board_member_name | Commissioner/Board Member Name | text      | text        |
| Yes      | series tag     | agency_name                    | Agency Name                    | text      | text        |
| Yes      | numeric metric | delinquent_fees                | Delinquent Fees                | money     | money       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:qrhk-8si2 d:2015-06-01T16:58:46.000Z t:agency_name="Police Commission" t:commissioner_board_member_name="Joseph Marshall" m:delinquent_fees=100

series e:qrhk-8si2 d:2015-06-01T16:58:46.000Z t:agency_name="Elections Commission" t:commissioner_board_member_name="Kathleen Ruiz-Healy" m:delinquent_fees=100

series e:qrhk-8si2 d:2015-06-01T16:58:46.000Z t:agency_name="Health Authority" t:commissioner_board_member_name="Edwin Batongbacal" m:delinquent_fees=30
```

## Meta Commands

```ls
metric m:delinquent_fees p:integer l:"Delinquent Fees" t:dataTypeName=money

entity e:qrhk-8si2 l:"Statement of Economic Interests (SEI) (Form 700) - Filers with unpaid late filing fees" t:attribution="San Francisco Ethics Commission" t:url=https://data.sfgov.org/api/views/qrhk-8si2

property e:qrhk-8si2 t:meta.view v:id=qrhk-8si2 v:category="City Management and Ethics" v:attributionLink=http://www.sfethics.org v:averageRating=0 v:name="Statement of Economic Interests (SEI) (Form 700) - Filers with unpaid late filing fees" v:attribution="San Francisco Ethics Commission"

property e:qrhk-8si2 t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:qrhk-8si2 t:meta.view.owner v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:displayName="Steven Massey"

property e:qrhk-8si2 t:meta.view.tableauthor v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:roleName=publisher v:displayName="Steven Massey"
```

## Top Records

```ls
| :updated_at | commissioner_board_member_name | agency_name                            | delinquent_fees | 
| =========== | ============================== | ====================================== | =============== | 
| 1433177926  | Joseph Marshall                | Police Commission                      | 100             | 
| 1433177926  | Kathleen Ruiz-Healy            | Elections Commission                   | 100             | 
| 1433177926  | Edwin Batongbacal              | Health Authority                       | 30              | 
| 1433177926  | Mark Dunlop                    | Treasure Island Development Authority  | 100             | 
| 1433177926  | Gwyneth Borden                 | Planning Commission                    | 80              | 
| 1433177926  | Richard Hillis                 | Board of Appeals - Planning Commission | 100             | 
| 1433177926  | Karl Hasz                      | Historic Preservation Commission       | 100             | 
```