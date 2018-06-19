# Campaign Finance - Individual Expenditure Ceilings IECs - November 3, 2015 Election

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/campaign-finance-individual-expenditure-ceilings-iecs-november-3-2015-election) |
| Metadata | [Link](https://data.sfgov.org/api/views/cgah-zci4) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/cgah-zci4/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/cgah-zci4/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | cgah-zci4 |
| Name | Campaign Finance - Individual Expenditure Ceilings IECs - November 3, 2015 Election |
| Attribution | San Francisco Ethics Commission |
| Category | City Management and Ethics |
| Tags | campaign finance dashboard 2015 |
| Created | 2015-06-24T20:56:34Z |
| Publication Date | 2015-06-24T21:02:18Z |

## Description

In the November 3, 2015 election, only candidates for the Board of Supervisors who have been certified as eligible to receive public funds are bound by an Individual Expenditure Ceiling (IEC). Each publicly financed candidate's IEC begins at $250,000 and may be raised in increments of $10,000.

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
series e:cgah-zci4 d:2015-10-26T00:00:00.000Z t:candidate="Peskin, Aaron" t:district=3 m:amount_of_iec=840000

series e:cgah-zci4 d:2015-10-26T00:00:00.000Z t:candidate="Christensen, Julie" t:district=3 m:amount_of_iec=860000

series e:cgah-zci4 d:2015-06-23T00:00:00.000Z t:candidate="Christensen, Julie" t:district=3 m:amount_of_iec=250000
```

## Meta Commands

```ls
metric m:amount_of_iec p:integer l:"Amount of IEC" t:dataTypeName=money

entity e:cgah-zci4 l:"Campaign Finance - Individual Expenditure Ceilings  IECs  - November 3, 2015 Election" t:attribution="San Francisco Ethics Commission" t:url=https://data.sfgov.org/api/views/cgah-zci4

property e:cgah-zci4 t:meta.view v:id=cgah-zci4 v:category="City Management and Ethics" v:attributionLink=http://www.sfethics.org v:averageRating=0 v:name="Campaign Finance - Individual Expenditure Ceilings  IECs  - November 3, 2015 Election" v:attribution="San Francisco Ethics Commission"

property e:cgah-zci4 t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:cgah-zci4 t:meta.view.owner v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:displayName="Steven Massey"

property e:cgah-zci4 t:meta.view.tableauthor v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:roleName=publisher v:displayName="Steven Massey"
```

## Top Records

```ls
| district | candidate          | date_iec_raised     | amount_of_iec | 
| ======== | ================== | =================== | ============= | 
| 3        | Peskin, Aaron      | 2015-10-26T00:00:00 | 840000        | 
| 3        | Christensen, Julie | 2015-10-26T00:00:00 | 860000        | 
| 3        | Christensen, Julie | 2015-06-23T00:00:00 | 250000        | 
| 3        | Peskin, Aaron      | 2015-06-23T00:00:00 | 250000        | 
| 3        | Peskin, Aaron      | 2015-08-18T00:00:00 | 270000        | 
| 3        | Christensen, Julie | 2015-08-18T00:00:00 | 280000        | 
| 3        | Christensen, Julie | 2015-08-21T00:00:00 | 300000        | 
| 3        | Peskin, Aaron      | 2015-08-25T00:00:00 | 300000        | 
| 3        | Peskin, Aaron      | 2015-08-31T00:00:00 | 310000        | 
| 3        | Christensen, Julie | 2015-08-31T00:00:00 | 330000        | 
```