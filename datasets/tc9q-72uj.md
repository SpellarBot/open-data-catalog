# Campaign Consultants - Client Payments

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/campaign-consultants-client-payments-1e10a) |
| Metadata | [Link](https://data.sfgov.org/api/views/tc9q-72uj) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/tc9q-72uj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/tc9q-72uj/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | tc9q-72uj |
| Name | Campaign Consultants - Client Payments |
| Attribution | San Francisco Ethics Commission |
| Category | City Management and Ethics |
| Tags | campaign consultant, ethics, payments, promised, received |
| Created | 2013-07-19T17:32:18Z |
| Publication Date | 2014-01-15T19:23:58Z |

## Description

Campaign Consultants are required to report ???economic consideration?? promised by or received from clients in exchange for campaign consulting services during the applicable reporting period.  Economic consideration includes payments, fees, commissions, and reimbursements for expenses, gifts or anything else of value.

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type     | Render Type   |
| ======== | ============== | ======================= | ======================= | ============= | ============= |
| Yes      | series tag     | campaign_consultant     | Campaign Consultant     | text          | text          |
| Yes      | series tag     | client                  | Client                  | text          | text          |
| Yes      | series tag     | services_performed      | Services Performed      | text          | text          |
| Yes      | numeric metric | total_payments_promised | Total Payments Promised | money         | money         |
| Yes      | numeric metric | total_payments_received | Total Payments Received | money         | money         |
| Yes      | time           | quarter_start_date      | Quarter Start Date      | calendar_date | calendar_date |
| No       |                | quarter_end_date        | Quarter End Date        | calendar_date | calendar_date |
| No       |                | quarter                 | Quarter                 | number        | text          |
| No       |                | year                    | Year                    | number        | text          |
```

## Time Field

```ls
Value = quarter_start_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = quarter_end_date,quarter,year
```

## Data Commands

```ls
series e:tc9q-72uj d:2016-06-01T00:00:00.000Z t:client="Yes on S, San Francans for the Arts & Ending Family Homelessness" t:services_performed="Campaign management and consulting, strategic" t:campaign_consultant="50+1 Strategies" m:total_payments_received=27273 m:total_payments_promised=20000

series e:tc9q-72uj d:2016-06-01T00:00:00.000Z t:client="Alex Randolph for College Board 2016" t:services_performed="Campaign management and consulting, strategic communication and operations for 2016 campaign" t:campaign_consultant="50+1 Strategies" m:total_payments_received=13000 m:total_payments_promised=13000

series e:tc9q-72uj d:2016-06-01T00:00:00.000Z t:client="Matt Haney for School Board 2016" t:services_performed="Campaign management and consulting, strategic communication and operations" t:campaign_consultant="50+1 Strategies" m:total_payments_received=9750 m:total_payments_promised=9750
```

## Meta Commands

```ls
metric m:total_payments_promised p:integer l:"Total Payments Promised" t:dataTypeName=money

metric m:total_payments_received p:integer l:"Total Payments Received" t:dataTypeName=money

entity e:tc9q-72uj l:"Campaign Consultants - Client Payments" t:attribution="San Francisco Ethics Commission" t:url=https://data.sfgov.org/api/views/tc9q-72uj

property e:tc9q-72uj t:meta.view v:id=tc9q-72uj v:category="City Management and Ethics" v:attributionLink=http://www.sfethics.org v:averageRating=0 v:name="Campaign Consultants - Client Payments" v:attribution="San Francisco Ethics Commission"

property e:tc9q-72uj t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:tc9q-72uj t:meta.view.owner v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:displayName="Steven Massey"

property e:tc9q-72uj t:meta.view.tableauthor v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:roleName=publisher v:displayName="Steven Massey"
```

## Top Records

```ls
| campaign_consultant | client                                                           | services_performed                                                                           | total_payments_promised | total_payments_received | quarter_start_date  | quarter_end_date    | quarter | year | 
| =================== | ================================================================ | ============================================================================================ | ======================= | ======================= | =================== | =================== | ======= | ==== | 
| 50+1 Strategies     | Yes on S, San Francans for the Arts & Ending Family Homelessness | Campaign management and consulting, strategic                                                | 20000                   | 27273                   | 2016-06-01T00:00:00 | 2016-08-31T00:00:00 | 3       | 2016 | 
| 50+1 Strategies     | Alex Randolph for College Board 2016                             | Campaign management and consulting, strategic communication and operations for 2016 campaign | 13000                   | 13000                   | 2016-06-01T00:00:00 | 2016-08-31T00:00:00 | 3       | 2016 | 
| 50+1 Strategies     | Matt Haney for School Board 2016                                 | Campaign management and consulting, strategic communication and operations                   | 9750                    | 9750                    | 2016-06-01T00:00:00 | 2016-08-31T00:00:00 | 3       | 2016 | 
| 50+1 Strategies     | Joshua Arce for Supervisor 2016                                  | Campaign management and consulting, strategic communication and operations for 2016 campaign | 15000                   | 15796                   | 2016-06-01T00:00:00 | 2016-08-31T00:00:00 | 3       | 2016 | 
| Allbee, Nathan      | Dean Preston                                                     | General consulting, media, IT, field                                                         | 3000                    | 3000                    | 2016-06-01T00:00:00 | 2016-08-31T00:00:00 | 3       | 2016 | 
| Allbee, Nathan      | Hillary Ronen                                                    | General consulting, media, IT, field                                                         | 15000                   | 15000                   | 2016-06-01T00:00:00 | 2016-08-31T00:00:00 | 3       | 2016 | 
| Allbee, Nathan      | Tom Temprano                                                     | General consulting, media, IT, field                                                         | 6000                    | 6000                    | 2016-06-01T00:00:00 | 2016-08-31T00:00:00 | 3       | 2016 | 
| Bedford Grove       | Scott Wiener for State Senate                                    | Fundraising                                                                                  | 0                       | 18000                   | 2016-06-01T00:00:00 | 2016-08-31T00:00:00 | 3       | 2016 | 
| Bedford Grove       | London Breed for DCCC                                            | Fundraising                                                                                  | 0                       | 5000                    | 2016-06-01T00:00:00 | 2016-08-31T00:00:00 | 3       | 2016 | 
| Bedford Grove       | Re-Elect London Breed                                            | Fundraising                                                                                  | 0                       | 10000                   | 2016-06-01T00:00:00 | 2016-08-31T00:00:00 | 3       | 2016 | 
```