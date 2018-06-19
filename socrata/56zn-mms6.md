# Campaign Finance - List of Candidates Running for Office in November 2014 who have Accepted the Voluntary Expenditure Ceiling

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/campaign-finance-list-of-candidates-running-for-office-in-november-2014-who-have-accepted--c995c) |
| Metadata | [Link](https://data.sfgov.org/api/views/56zn-mms6) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/56zn-mms6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/56zn-mms6/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | 56zn-mms6 |
| Name | Campaign Finance - List of Candidates Running for Office in November 2014 who have Accepted the Voluntary Expenditure Ceiling |
| Attribution | San Francisco Ethics Commission |
| Category | City Management and Ethics |
| Tags | ethics, campaign, finance, voluntary expenditure ceiling, november 4 2014, election, candidates |
| Created | 2013-11-25T18:09:15Z |
| Publication Date | 2014-08-11T21:05:51Z |

## Columns

```ls
| Included | Schema Type | Field Name     | Name           | Data Type | Render Type |
| ======== | =========== | ============== | ============== | ========= | =========== |
| Yes      | series tag  | candidate_name | Candidate Name | text      | text        |
| Yes      | series tag  | office_sought  | Office Sought  | text      | text        |
```

## Time Field

```ls
Value = 2014
Format & Zone = yyyy
```

## Data Commands

```ls
series e:56zn-mms6 d:2014-01-01T00:00:00.000Z t:office_sought="Board of Education" t:candidate_name="Wolfe, Jamie" m:row_number.56zn-mms6=1
```

## Meta Commands

```ls
metric m:row_number.56zn-mms6 p:long l:"Row Number"

entity e:56zn-mms6 l:"Campaign Finance - List of Candidates Running for Office in November 2014 who have Accepted the Voluntary Expenditure Ceiling" t:attribution="San Francisco Ethics Commission" t:url=https://data.sfgov.org/api/views/56zn-mms6

property e:56zn-mms6 t:meta.view v:id=56zn-mms6 v:category="City Management and Ethics" v:attributionLink=http://www.sfethics.org v:averageRating=0 v:name="Campaign Finance - List of Candidates Running for Office in November 2014 who have Accepted the Voluntary Expenditure Ceiling" v:attribution="San Francisco Ethics Commission"

property e:56zn-mms6 t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:56zn-mms6 t:meta.view.owner v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:displayName="Steven Massey"

property e:56zn-mms6 t:meta.view.tableauthor v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:roleName=publisher v:displayName="Steven Massey"
```

## Top Records

```ls
| candidate_name | office_sought      | 
| ============== | ================== | 
| Wolfe, Jamie   | Board of Education | 
```