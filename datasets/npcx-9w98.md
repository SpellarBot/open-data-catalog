# Campaign Finance - List of Candidates Running for Office in November 2012 who have Accepted the Voluntary Expenditure Ceiling

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/campaign-finance-list-of-candidates-running-for-office-in-november-2012-who-have-accepted--37254) |
| Metadata | [Link](https://data.sfgov.org/api/views/npcx-9w98) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/npcx-9w98/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/npcx-9w98/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | npcx-9w98 |
| Name | Campaign Finance - List of Candidates Running for Office in November 2012 who have Accepted the Voluntary Expenditure Ceiling |
| Attribution | San Francisco Ethics Commission |
| Category | City Management and Ethics |
| Tags | ethics, campaign, finance, voluntary expenditure ceiling, november 6 2012, election, candidates |
| Created | 2012-08-15T17:08:24Z |
| Publication Date | 2012-08-21T21:55:20Z |

## Columns

```ls
| Included | Schema Type | Field Name     | Name           | Data Type | Render Type |
| ======== | =========== | ============== | ============== | ========= | =========== |
| Yes      | series tag  | candidate_name | Candidate Name | text      | text        |
| Yes      | series tag  | office_sought  | Office Sought  | text      | text        |
```

## Time Field

```ls
Value = 2012
Format & Zone = yyyy
```

## Data Commands

```ls
series e:npcx-9w98 d:2012-01-01T00:00:00.000Z t:office_sought="Board of Education" t:candidate_name="Rawlings-Fein, Martin" m:row_number.npcx-9w98=1

series e:npcx-9w98 d:2012-01-01T00:00:00.000Z t:office_sought="Community College Board" t:candidate_name="Berg, Natalie" m:row_number.npcx-9w98=2

series e:npcx-9w98 d:2012-01-01T00:00:00.000Z t:office_sought="Community College Board" t:candidate_name="Jackson, Chris" m:row_number.npcx-9w98=3
```

## Meta Commands

```ls
metric m:row_number.npcx-9w98 p:long l:"Row Number"

entity e:npcx-9w98 l:"Campaign Finance - List of Candidates Running for Office in November 2012 who have Accepted the Voluntary Expenditure Ceiling" t:attribution="San Francisco Ethics Commission" t:url=https://data.sfgov.org/api/views/npcx-9w98

property e:npcx-9w98 t:meta.view v:id=npcx-9w98 v:category="City Management and Ethics" v:attributionLink=http://www.sfethics.org v:averageRating=0 v:name="Campaign Finance - List of Candidates Running for Office in November 2012 who have Accepted the Voluntary Expenditure Ceiling" v:attribution="San Francisco Ethics Commission"

property e:npcx-9w98 t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:npcx-9w98 t:meta.view.owner v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:displayName="Steven Massey"

property e:npcx-9w98 t:meta.view.tableauthor v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:roleName=publisher v:displayName="Steven Massey"
```

## Top Records

```ls
| candidate_name          | office_sought           | 
| ======================= | ======================= | 
| Rawlings-Fein, Martin   | Board of Education      | 
| Berg, Natalie           | Community College Board | 
| Jackson, Chris          | Community College Board | 
| Walker, William         | Community College Board | 
| Soto, Gladys            | Board of Education      | 
| Fewer, Sandra-Lee       | Board of Education      | 
| Robertson, Paul         | Board of Education      | 
| Beverly Ho-A-Yun, Popek | Board of Education      | 
| Norton, Rachel          | Board of Education      | 
| Lo, Victoria            | Board of Education      | 
```