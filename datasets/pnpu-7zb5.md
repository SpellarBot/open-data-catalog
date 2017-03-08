# Campaign Finance - Public Funds Disbursed - November 3, 2015 Election

## Dataset

* [Dataset URL](https://data.sfgov.org/api/views/pnpu-7zb5/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/campaign-finance-public-funds-disbursed-november-3-2015-election)
* [Metadata URL](https://data.sfgov.org/api/views/pnpu-7zb5)
* Id = pnpu-7zb5
* Name = Campaign Finance - Public Funds Disbursed - November 3, 2015 Election
* Category = City Management and Ethics
* Tags = [campaign finance dashboard 2015]
* Created = 2015-06-23T18:40:28Z
* Publication Date = 2016-02-29T18:54:33Z
* Rows Updated = 2016-02-29T18:53:25Z

## Description



## Columns

```ls
| Name                    | Field Name              | Data Type     | Render Type   | Schema Type    | Included | 
| ======================= | ======================= | ============= | ============= | ============== | ======== | 
| District                | district                | text          | text          | series tag     | Yes      | 
| Candidate               | candidate               | text          | text          | series tag     | Yes      | 
| Date of Submission      | date_of_submission      | calendar_date | calendar_date | time           | Yes      | 
| Date Certified/Approved | date_certified_approved | calendar_date | calendar_date |                | No       | 
| Pending/Completed       | pending_completed       | text          | text          | series tag     | Yes      | 
| Funds Disbursed         | funds_disbursed         | money         | money         | numeric metric | Yes      | 
```

## Time Field

```ls
Value = date_of_submission
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = date_certified_approved
Annotation Fields = 
```

## Data Commands

```ls
series e:pnpu-7zb5 d:2015-06-17T00:00:00.000Z t:pending_completed=Completed t:candidate="Christensen, Julie" t:district=3 m:funds_disbursed=20000

series e:pnpu-7zb5 d:2015-06-12T00:00:00.000Z t:pending_completed=Completed t:candidate="Peskin, Aaron" t:district=3 m:funds_disbursed=20000

series e:pnpu-7zb5 d:2015-06-24T00:00:00.000Z t:pending_completed=Completed t:candidate="Christensen, Julie" t:district=3 m:funds_disbursed=55039
```

## Meta Commands

```ls
entity e:pnpu-7zb5 l:"Campaign Finance - Public Funds Disbursed - November 3, 2015 Election" t:url=https://data.sfgov.org/api/views/pnpu-7zb5

property e:pnpu-7zb5 t:meta.view d:2017-03-08T01:15:00.839Z v:id=pnpu-7zb5 v:category="City Management and Ethics" v:averageRating=0 v:name="Campaign Finance - Public Funds Disbursed - November 3, 2015 Election"

property e:pnpu-7zb5 t:meta.view.license d:2017-03-08T01:15:00.839Z v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:pnpu-7zb5 t:meta.view.owner d:2017-03-08T01:15:00.839Z v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:roleName=publisher v:displayName="Steven Massey"

property e:pnpu-7zb5 t:meta.view.tableauthor d:2017-03-08T01:15:00.839Z v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:roleName=publisher v:displayName="Steven Massey"
```