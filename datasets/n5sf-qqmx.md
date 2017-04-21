# Campaign Finance - Public Funds Disbursed - November 4, 2014 Election

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/campaign-finance-public-funds-disbursed-november-4-2014-election-ac7e9) |
| Metadata | [Link](https://data.sfgov.org/api/views/n5sf-qqmx) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/n5sf-qqmx/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/n5sf-qqmx/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | n5sf-qqmx |
| Name | Campaign Finance - Public Funds Disbursed - November 4, 2014 Election |
| Attribution | San Francisco Ethics Commission |
| Category | City Management and Ethics |
| Tags | ethics, campaign, finance, public, funds, disbursed, 2014, november, election, candidates |
| Created | 2013-12-09T19:51:24Z |
| Publication Date | 2014-11-21T21:43:09Z |

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
series e:n5sf-qqmx d:2014-06-12T00:00:00.000Z t:pending_completed=Completed t:candidate="Kelly, Tony" t:district=10 m:funds_disbursed=20000

series e:n5sf-qqmx d:2014-07-16T00:00:00.000Z t:pending_completed=Completed t:candidate="Kelly, Tony" t:district=10 m:funds_disbursed=29918

series e:n5sf-qqmx d:2014-08-11T00:00:00.000Z t:pending_completed=Completed t:candidate="Tran, Marlene" t:district=10 m:funds_disbursed=20000
```

## Meta Commands

```ls
metric m:funds_disbursed p:double l:"Funds Disbursed" t:dataTypeName=money

entity e:n5sf-qqmx l:"Campaign Finance - Public Funds Disbursed - November 4, 2014 Election" t:attribution="San Francisco Ethics Commission" t:url=https://data.sfgov.org/api/views/n5sf-qqmx

property e:n5sf-qqmx t:meta.view v:id=n5sf-qqmx v:category="City Management and Ethics" v:attributionLink=http://www.sfethics.org v:averageRating=0 v:name="Campaign Finance - Public Funds Disbursed - November 4, 2014 Election" v:attribution="San Francisco Ethics Commission"

property e:n5sf-qqmx t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:n5sf-qqmx t:meta.view.owner v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:displayName="Steven Massey"

property e:n5sf-qqmx t:meta.view.tableauthor v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:roleName=publisher v:displayName="Steven Massey"
```

## Top Records

```ls
| district | candidate     | date_of_submission  | date_certified_approved | pending_completed | funds_disbursed | 
| ======== | ============= | =================== | ======================= | ================= | =============== | 
| 10       | Kelly, Tony   | 2014-06-12T00:00:00 | 2014-07-10T00:00:00     | Completed         | 20000           | 
| 10       | Kelly, Tony   | 2014-07-16T00:00:00 | 2014-07-22T00:00:00     | Completed         | 29918           | 
| 10       | Tran, Marlene | 2014-08-11T00:00:00 | 2014-08-20T00:00:00     | Completed         | 20000           | 
| 10       | Kelly, Tony   | 2014-07-31T00:00:00 | 2014-08-12T00:00:00     | Completed         | 18300           | 
| 10       | Kelly, Tony   | 2014-08-28T00:00:00 | 2014-09-09T00:00:00     | Completed         | 16520           | 
| 10       | Tran, Marlene | 2014-09-11T00:00:00 | 2014-09-12T00:00:00     | Completed         | 21425.94        | 
| 10       | Kelly, Tony   | 2014-09-16T00:00:00 | 2014-09-18T00:00:00     | Completed         | 13950           | 
| 10       | Tran, Marlene | 2014-10-01T00:00:00 | 2014-10-01T00:00:00     | Completed         | 15440           | 
| 10       | Kelly, Tony   | 2014-09-29T00:00:00 | 2014-10-03T00:00:00     | Completed         | 13700           | 
| 10       | Kelly, Tony   | 2014-10-14T00:00:00 | 2014-10-16T00:00:00     | Completed         | 10926           | 
```