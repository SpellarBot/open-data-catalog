# Campaign Finance - Public Funds Disbursed - November 8, 2016 Election

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/campaign-finance-public-funds-disbursed-november-8-2016-election) |
| Metadata | [Link](https://data.sfgov.org/api/views/nmzh-y378) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/nmzh-y378/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/nmzh-y378/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | nmzh-y378 |
| Name | Campaign Finance - Public Funds Disbursed - November 8, 2016 Election |
| Attribution | San Francisco Ethics Commission |
| Category | City Management and Ethics |
| Tags | campaign finance dashboard 2016 |
| Created | 2016-02-22T21:34:03Z |
| Publication Date | 2016-02-26T22:04:39Z |

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
series e:nmzh-y378 d:2016-02-09T00:00:00.000Z t:pending_completed=Completed t:candidate="Philhour, Marjan" t:district=1 m:funds_disbursed=20000

series e:nmzh-y378 d:2016-06-03T00:00:00.000Z t:pending_completed=Completed t:candidate="Safai, Ahsha" t:district=11 m:funds_disbursed=20000

series e:nmzh-y378 d:2015-02-16T00:00:00.000Z t:pending_completed=Completed t:candidate="Fewer, Sandra" t:district=1 m:funds_disbursed=20000
```

## Meta Commands

```ls
metric m:funds_disbursed p:double l:"Funds Disbursed" t:dataTypeName=money

entity e:nmzh-y378 l:"Campaign Finance - Public Funds Disbursed - November 8, 2016 Election" t:attribution="San Francisco Ethics Commission" t:url=https://data.sfgov.org/api/views/nmzh-y378

property e:nmzh-y378 t:meta.view v:id=nmzh-y378 v:category="City Management and Ethics" v:attributionLink=http://www.sfethics.org v:averageRating=0 v:name="Campaign Finance - Public Funds Disbursed - November 8, 2016 Election" v:attribution="San Francisco Ethics Commission"

property e:nmzh-y378 t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:nmzh-y378 t:meta.view.owner v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:displayName="Steven Massey"

property e:nmzh-y378 t:meta.view.tableauthor v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:roleName=publisher v:displayName="Steven Massey"
```

## Top Records

```ls
| district | candidate           | date_of_submission  | date_certified_approved | pending_completed | funds_disbursed | 
| ======== | =================== | =================== | ======================= | ================= | =============== | 
| 1        | Philhour, Marjan    | 2016-02-09T00:00:00 | 2016-02-26T00:00:00     | Completed         | 20000           | 
| 11       | Safai, Ahsha        | 2016-06-03T00:00:00 | 2016-06-17T00:00:00     | Completed         | 20000           | 
| 1        | Fewer, Sandra       | 2015-02-16T00:00:00 | 2016-02-29T00:00:00     | Completed         | 20000           | 
| 7        | Engardio, Joel      | 2016-06-05T00:00:00 | 2016-06-17T00:00:00     | Completed         | 20000           | 
| 11       | Alvarenga, Kimberly | 2016-03-21T00:00:00 | 2016-03-24T00:00:00     | Completed         | 20000           | 
| 1        | Philhour, Marjan    | 2016-06-02T00:00:00 | 2016-06-08T00:00:00     | Completed         | 36922           | 
| 9        | Ronen, Hillary      | 2016-06-21T00:00:00 | 2016-06-24T00:00:00     | Completed         | 83630.79        | 
| 5        | Preston, Dean       | 2016-06-10T00:00:00 | 2016-06-22T00:00:00     | Completed         | 20000           | 
| 11       | Alvarenga, Kimberly | 2016-06-17T00:00:00 | 2016-06-22T00:00:00     | Completed         | 9788            | 
| 7        | Matranga, Benjamin  | 2016-06-05T00:00:00 | 2016-06-23T00:00:00     | Completed         | 20000           | 
```