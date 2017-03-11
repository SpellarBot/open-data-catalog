# Campaign Finance - Individual Expenditure Ceilings IECs - November 4, 2014 Election

## Dataset

* [Dataset URL](https://data.sfgov.org/api/views/wv7d-caby/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/campaign-finance-individual-expenditure-ceilings-iecs-november-4-2014-election-55da5)
* [Metadata URL](https://data.sfgov.org/api/views/wv7d-caby)
* Id = wv7d-caby
* Name = Campaign Finance - Individual Expenditure Ceilings IECs - November 4, 2014 Election
* Attribution = San Francisco Ethics Commission
* [Attribution Link](http://www.sfethics.org)
* Category = City Management and Ethics
* Tags = [individual, expenditure, ceilings, iec, public, financing, campaign, finance, candidate, 2014, election, november]
* Created = 2013-11-25T22:33:51Z
* Publication Date = 2014-10-29T23:37:42Z
* Rows Updated = 2014-10-29T23:37:29Z

## Description

In the November 4, 2014 election, only candidates for the Board of Supervisors who have been certified as eligible to receive public funds are bound by an Individual Expenditure Ceiling (IEC). Each publicly financed candidate's IEC begins at $250,000 and may be raised in increments of $10,000.

## Columns

```ls
| Name            | Field Name      | Data Type     | Render Type   | Schema Type    | Included | 
| =============== | =============== | ============= | ============= | ============== | ======== | 
| District        | district        | text          | text          | series tag     | Yes      | 
| Candidate       | candidate       | text          | text          | series tag     | Yes      | 
| Date IEC Raised | date_iec_raised | calendar_date | calendar_date | time           | Yes      | 
| Amount of IEC   | amount_of_iec   | money         | money         | numeric metric | Yes      | 
```

## Time Field

```ls
Value = date_iec_raised
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = 
Annotation Fields = 
```

## Data Commands

```ls
series e:wv7d-caby d:2014-07-10T00:00:00.000Z t:candidate="Kelly, Tony" t:district=10 m:amount_of_iec=250000

series e:wv7d-caby d:2014-08-20T00:00:00.000Z t:candidate="Tran, Marlene" t:district=10 m:amount_of_iec=250000

series e:wv7d-caby d:2014-09-08T00:00:00.000Z t:candidate="Kelly, Tony" t:district=10 m:amount_of_iec=260000
```

## Meta Commands

```ls
entity e:wv7d-caby l:"Campaign Finance - Individual Expenditure Ceilings  IECs  - November 4, 2014 Election" t:attribution="San Francisco Ethics Commission" t:url=https://data.sfgov.org/api/views/wv7d-caby

property e:wv7d-caby t:meta.view d:2017-03-07T22:56:15.645Z v:id=wv7d-caby v:category="City Management and Ethics" v:attributionLink=http://www.sfethics.org v:averageRating=0 v:name="Campaign Finance - Individual Expenditure Ceilings  IECs  - November 4, 2014 Election" v:attribution="San Francisco Ethics Commission"

property e:wv7d-caby t:meta.view.license d:2017-03-07T22:56:15.645Z v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:wv7d-caby t:meta.view.owner d:2017-03-07T22:56:15.645Z v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:roleName=publisher v:displayName="Steven Massey"

property e:wv7d-caby t:meta.view.tableauthor d:2017-03-07T22:56:15.645Z v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:roleName=publisher v:displayName="Steven Massey"
```