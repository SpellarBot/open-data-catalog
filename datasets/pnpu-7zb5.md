# Campaign Finance - Public Funds Disbursed - November 3, 2015 Election

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/campaign-finance-public-funds-disbursed-november-3-2015-election) |
| Metadata | [Link](https://data.sfgov.org/api/views/pnpu-7zb5) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/pnpu-7zb5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/pnpu-7zb5/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | pnpu-7zb5 |
| Name | Campaign Finance - Public Funds Disbursed - November 3, 2015 Election |
| Category | City Management and Ethics |
| Tags | campaign finance dashboard 2015 |
| Created | 2015-06-23T18:40:28Z |
| Publication Date | 2016-02-29T18:54:33Z |

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type     | Render Type   |
| ======== | ============== | ======================= | ======================= | ============= | ============= |
| Yes      | series tag     | district                | District                | text          | text          |
| Yes      | series tag     | candidate               | Candidate               | text          | text          |
| Yes      | time           | date_of_submission      | Date of Submission      | calendar_date | calendar_date |
| No       |                | date_certified_approved | Date Certified/Approved | calendar_date | calendar_date |
| Yes      | series tag     | pending_completed       | Pending/Completed       | text          | text          |
| Yes      | numeric metric | funds_disbursed         | Funds Disbursed         | money         | money         |
```

## Time Field

```ls
Value = date_of_submission
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = date_certified_approved
```

## Data Commands

```ls
series e:pnpu-7zb5 d:2015-06-17T00:00:00.000Z t:pending_completed=Completed t:candidate="Christensen, Julie" t:district=3 m:funds_disbursed=20000

series e:pnpu-7zb5 d:2015-06-12T00:00:00.000Z t:pending_completed=Completed t:candidate="Peskin, Aaron" t:district=3 m:funds_disbursed=20000

series e:pnpu-7zb5 d:2015-06-24T00:00:00.000Z t:pending_completed=Completed t:candidate="Christensen, Julie" t:district=3 m:funds_disbursed=55039
```

## Meta Commands

```ls
metric m:funds_disbursed p:integer l:"Funds Disbursed" t:dataTypeName=money

entity e:pnpu-7zb5 l:"Campaign Finance - Public Funds Disbursed - November 3, 2015 Election" t:url=https://data.sfgov.org/api/views/pnpu-7zb5

property e:pnpu-7zb5 t:meta.view d:2017-06-09T13:56:34.728Z v:id=pnpu-7zb5 v:category="City Management and Ethics" v:averageRating=0 v:name="Campaign Finance - Public Funds Disbursed - November 3, 2015 Election"

property e:pnpu-7zb5 t:meta.view.license d:2017-06-09T13:56:34.728Z v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:pnpu-7zb5 t:meta.view.owner d:2017-06-09T13:56:34.728Z v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:displayName="Steven Massey"

property e:pnpu-7zb5 t:meta.view.tableauthor d:2017-06-09T13:56:34.728Z v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:roleName=publisher v:displayName="Steven Massey"
```

## Top Records

```ls
| district | candidate          | date_of_submission  | date_certified_approved | pending_completed | funds_disbursed | 
| ======== | ================== | =================== | ======================= | ================= | =============== | 
| 3        | Christensen, Julie | 2015-06-17T00:00:00 | 2015-06-23T00:00:00     | Completed         | 20000           | 
| 3        | Peskin, Aaron      | 2015-06-12T00:00:00 | 2015-06-23T00:00:00     | Completed         | 20000           | 
| 3        | Christensen, Julie | 2015-06-24T00:00:00 | 2015-07-02T00:00:00     | Completed         | 55039           | 
| 3        | Peskin, Aaron      | 2015-07-02T00:00:00 | 2015-07-06T00:00:00     | Completed         | 36670           | 
| 3        | Christensen, Julie | 2015-06-24T00:00:00 | 2015-08-20T00:00:00     | Completed         | 30000           | 
| 3        | Peskin, Aaron      | 2015-07-02T00:00:00 | 2015-08-28T00:00:00     | Completed         | 4780            | 
| 3        | Peskin, Aaron      | 2015-08-27T00:00:00 | 2015-09-02T00:00:00     | Completed         | 20000           | 
| 3        | Christensen, Julie | 2015-06-24T00:00:00 | 2015-09-10T00:00:00     | Completed         | 9461            | 
| 3        | Peskin, Aaron      | 2015-08-27T00:00:00 | 2015-09-17T00:00:00     | Completed         | 12006           | 
| 3        | Christensen, Julie | 2015-09-21T00:00:00 | 2015-09-23T00:00:00     | Completed         | 38000           | 
```