# Campaign Finance - Individual Expenditure Ceilings IECs - November 4, 2014 Election

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/campaign-finance-individual-expenditure-ceilings-iecs-november-4-2014-election-55da5) |
| Metadata | [Link](https://data.sfgov.org/api/views/wv7d-caby) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/wv7d-caby/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/wv7d-caby/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | wv7d-caby |
| Name | Campaign Finance - Individual Expenditure Ceilings IECs - November 4, 2014 Election |
| Attribution | San Francisco Ethics Commission |
| Category | City Management and Ethics |
| Tags | individual, expenditure, ceilings, iec, public, financing, campaign, finance, candidate, 2014, election, november |
| Created | 2013-11-25T22:33:51Z |
| Publication Date | 2014-10-29T23:37:42Z |

## Description

In the November 4, 2014 election, only candidates for the Board of Supervisors who have been certified as eligible to receive public funds are bound by an Individual Expenditure Ceiling (IEC). Each publicly financed candidate's IEC begins at $250,000 and may be raised in increments of $10,000.

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
series e:wv7d-caby d:2014-07-10T00:00:00.000Z t:candidate="Kelly, Tony" t:district=10 m:amount_of_iec=250000

series e:wv7d-caby d:2014-08-20T00:00:00.000Z t:candidate="Tran, Marlene" t:district=10 m:amount_of_iec=250000

series e:wv7d-caby d:2014-09-08T00:00:00.000Z t:candidate="Kelly, Tony" t:district=10 m:amount_of_iec=260000
```

## Meta Commands

```ls
metric m:amount_of_iec p:integer l:"Amount of IEC" t:dataTypeName=money

entity e:wv7d-caby l:"Campaign Finance - Individual Expenditure Ceilings  IECs  - November 4, 2014 Election" t:attribution="San Francisco Ethics Commission" t:url=https://data.sfgov.org/api/views/wv7d-caby

property e:wv7d-caby t:meta.view d:2017-09-25T07:28:13.101Z v:averageRating=0 v:name="Campaign Finance - Individual Expenditure Ceilings  IECs  - November 4, 2014 Election" v:attribution="San Francisco Ethics Commission" v:attributionLink=http://www.sfethics.org v:id=wv7d-caby v:category="City Management and Ethics"

property e:wv7d-caby t:meta.view.license d:2017-09-25T07:28:13.101Z v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:wv7d-caby t:meta.view.owner d:2017-09-25T07:28:13.101Z v:displayName="Steven Massey" v:lastNotificationSeenAt=1498669627 v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:id=vm9c-ykir v:screenName="Steven Massey" v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB

property e:wv7d-caby t:meta.view.tableauthor d:2017-09-25T07:28:13.101Z v:displayName="Steven Massey" v:lastNotificationSeenAt=1498669627 v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:roleName=publisher v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:id=vm9c-ykir v:screenName="Steven Massey" v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB
```

## Top Records

```ls
| district | candidate     | date_iec_raised     | amount_of_iec | 
| ======== | ============= | =================== | ============= | 
| 10       | Kelly, Tony   | 2014-07-10T00:00:00 | 250000        | 
| 10       | Tran, Marlene | 2014-08-20T00:00:00 | 250000        | 
| 10       | Kelly, Tony   | 2014-09-08T00:00:00 | 260000        | 
| 10       | Tran, Marlene | 2014-09-08T00:00:00 | 260000        | 
| 10       | Kelly, Tony   | 2014-09-22T00:00:00 | 290000        | 
| 10       | Tran, Marlene | 2014-09-22T00:00:00 | 290000        | 
| 10       | Kelly, Tony   | 2014-10-03T00:00:00 | 300000        | 
| 10       | Tran, Marlene | 2014-10-03T00:00:00 | 300000        | 
| 10       | Kelly, Tony   | 2014-10-24T00:00:00 | 310000        | 
| 10       | Tran, Marlene | 2014-10-24T00:00:00 | 310000        | 
```