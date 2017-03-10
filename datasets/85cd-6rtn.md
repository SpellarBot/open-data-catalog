# Campaign Finance - Individual Expenditure Ceilings (IECs) - November 6, 2012 Election

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/campaign-finance-individual-expenditure-ceilings-iecs-november-6-2012-election-ee848) |
| Metadata | [Link](https://data.sfgov.org/api/views/85cd-6rtn) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/85cd-6rtn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/85cd-6rtn/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | 85cd-6rtn |
| Name | Campaign Finance - Individual Expenditure Ceilings (IECs) - November 6, 2012 Election |
| Attribution | San Francisco Ethics Commission |
| Category | City Management and Ethics |
| Tags | individual, expenditure, ceilings, iec, public, financing, campaign, finance, candidate, 2012, election, november |
| Created | 2012-05-18T17:34:47Z |
| Publication Date | 2013-01-03T20:18:08Z |
| Rows Updated | 2012-11-09T18:06:58Z |

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type     | Render Type   |
| ======== | ============== | =============== | =============== | ============= | ============= |
| Yes      | series tag     | district        | District        | text          | text          |
| Yes      | series tag     | candidate       | Candidate       | text          | text          |
| Yes      | time           | date_iec_raised | Date IEC Raised | calendar_date | calendar_date |
| Yes      | numeric metric | amount_of_iec   | Amount of IEC   | money         | money         |
```

## Time Field

```ls
Value = date_iec_raised
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:85cd-6rtn d:2012-07-24T00:00:00.000Z t:candidate="Lee, David" t:district=1 m:amount_of_iec=250000

series e:85cd-6rtn d:2012-06-22T00:00:00.000Z t:candidate="Mar, Eric" t:district=1 m:amount_of_iec=250000

series e:85cd-6rtn d:2012-08-28T00:00:00.000Z t:candidate="Butler, Joe" t:district=3 m:amount_of_iec=250000
```

## Meta Commands

```ls
entity e:85cd-6rtn l:"Campaign Finance - Individual Expenditure Ceilings (IECs) - November 6, 2012 Election" t:attribution="San Francisco Ethics Commission" t:url=https://data.sfgov.org/api/views/85cd-6rtn

property e:85cd-6rtn t:meta.view d:2017-03-10T16:01:29.052Z v:id=85cd-6rtn v:category="City Management and Ethics" v:attributionLink=http://www.sfethics.org/ethics/2012/05/voluntary-expenditure-ceiling-and-individual-expenditure-ceilings.html v:averageRating=0 v:name="Campaign Finance - Individual Expenditure Ceilings (IECs) - November 6, 2012 Election" v:attribution="San Francisco Ethics Commission"

property e:85cd-6rtn t:meta.view.license d:2017-03-10T16:01:29.052Z v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:85cd-6rtn t:meta.view.owner d:2017-03-10T16:01:29.052Z v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:roleName=publisher v:displayName="Steven Massey"

property e:85cd-6rtn t:meta.view.tableauthor d:2017-03-10T16:01:29.052Z v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:roleName=publisher v:displayName="Steven Massey"
```