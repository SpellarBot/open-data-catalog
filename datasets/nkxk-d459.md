# Expenditure Lobbyists Registration and Monthly Disclosure Reports

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/expenditure-lobbyists-registration-and-monthly-disclosure-reports) |
| Metadata | [Link](https://data.sfgov.org/api/views/nkxk-d459) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/nkxk-d459/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/nkxk-d459/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | nkxk-d459 |
| Name | Expenditure Lobbyists Registration and Monthly Disclosure Reports |
| Attribution | San Francisco Ethics Commission |
| Category | City Management and Ethics |
| Tags | expenditure lobbyist registration lobbying disclosure reports |
| Created | 2016-07-21T15:19:09Z |
| Publication Date | 2016-07-21T15:36:10Z |

## Description

An expenditure lobbyist is an individual or entity that spends $2,500 or more in a calendar month to solicit, request, or urge others to communicate directly with a City officer in order to influence local legislative or administrative action.  City officers covered by this rule generally include elected City officials, members of City boards and commissions, and City department heads.

Examples of spending that counts toward the $2,500 registration threshold include public relations, media relations, advertising, public outreach, research, investigation, reports, analysis, and studies to the extent those activities are used to solicit, request or urge other persons to communicate directly with a City officer.

Examples of spending that does not count toward the $2,500 registration threshold include: payments made to a registered ?contact? lobbyist who directly contacts City officers; payments made to an organization for membership dues; payments made by an organization to distribute communications to its members; payments made by a news media organization to develop and distribute its publications; and payments made by a client to a representative to appear on the client?s behalf in a legal proceeding before a City agency or department; salary paid by employer to employee for activities to solicit, request, or urge others to communicate directly with an officer of the City in order to influence a matter of local legislative or administrative action.

Each expenditure lobbyist must register by filing a registration form with the Ethics Commission no later than five business days after qualifying as such, and prior to making any additional payments to influence local legislative or administrative action.

Each registered expenditure lobbyist must file monthly reports with the Ethics Commission by the fifteenth day of the month following the calendar month covered by the report. For example, a report covering activity in the month of February must be filed by March 15.  Deadlines falling on a weekend or holiday are extended to the next business day.  Please note the monthly disclosures are different than the registration requirements.

## Columns

```ls
| Included | Schema Type    | Field Name                      | Name                            | Data Type      | Render Type    |
| ======== | ============== | =============================== | =============================== | ============== | ============== |
| Yes      | series tag     | lobbyist_name                   | Lobbyist Name                   | text           | text           |
| Yes      | series tag     | report                          | Report                          | document       | document       |
| Yes      | time           | date_filed                      | Date Filed                      | calendar_date  | calendar_date  |
| Yes      | series tag     | report_type                     | Report Type                     | drop_down_list | drop_down_list |
| No       |                | period_start_date               | Period Start Date               | calendar_date  | calendar_date  |
| No       |                | period_end_date                 | Period End Date                 | calendar_date  | calendar_date  |
| Yes      | series tag     | activity                        | Activity                        | checkbox       | checkbox       |
| Yes      | series tag     | termination                     | Termination                     | checkbox       | checkbox       |
| Yes      | series tag     | amendment_filing                | Amendment Filing                | checkbox       | checkbox       |
| No       |                | amendment_to_report_filed       | Amendment to Report Filed       | calendar_date  | calendar_date  |
| Yes      | series tag     | type_of_expenditure_lobbyist    | Type of Expenditure Lobbyist    | drop_down_list | drop_down_list |
| Yes      | numeric metric | total_amount_spent_to_influence | Total Amount Spent to Influence | money          | money          |
```

## Time Field

```ls
Value = date_filed
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = period_start_date,period_end_date,amendment_to_report_filed
```

## Data Commands

```ls
series e:nkxk-d459 d:2016-07-14T00:00:00.000Z t:report.content_type=application/pdf t:report.filename=20160601_20160714_2110B_Airbnb_Inc._Redacted.pdf t:lobbyist_name="Airbnb, Inc." t:report_type=wm5f-tm26 t:report.file_id=3146827c-4ef9-4042-a7f9-473e8c7e28e3 t:report.size=73520 t:activity=true m:total_amount_spent_to_influence=12945.14
```

## Meta Commands

```ls
metric m:total_amount_spent_to_influence p:double l:"Total Amount Spent to Influence" t:dataTypeName=money

entity e:nkxk-d459 l:"Expenditure Lobbyists Registration and Monthly Disclosure Reports" t:attribution="San Francisco Ethics Commission" t:url=https://data.sfgov.org/api/views/nkxk-d459

property e:nkxk-d459 t:meta.view v:id=nkxk-d459 v:category="City Management and Ethics" v:attributionLink=http://www.sfethics.org v:averageRating=0 v:name="Expenditure Lobbyists Registration and Monthly Disclosure Reports" v:attribution="San Francisco Ethics Commission"

property e:nkxk-d459 t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:nkxk-d459 t:meta.view.owner v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:displayName="Steven Massey"

property e:nkxk-d459 t:meta.view.tableauthor v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:roleName=publisher v:displayName="Steven Massey"
```

## Top Records

```ls
| lobbyist_name | report                                                                                                            | date_filed          | report_type | period_start_date   | period_end_date     | activity | termination | amendment_filing | amendment_to_report_filed | type_of_expenditure_lobbyist | total_amount_spent_to_influence | 
| ============= | ================================================================================================================= | =================== | =========== | =================== | =================== | ======== | =========== | ================ | ========================= | ============================ | =============================== | 
| Airbnb, Inc.  | [application/pdf, d6eba0e1-bb1c-4724-b08c-96ccdf757857, 20160617_20160617_2110A_Airbnb_Inc._Redacted.pdf, 87841]  | 2016-06-17T00:00:00 | iwhf-d5m4   | 2016-06-17T00:00:00 | 2016-06-17T00:00:00 |          |             |                  | 2016-07-26T21:40:06       | ns3d-9iib                    |                                 | 
| Airbnb, Inc.  | [application/pdf, 3146827c-4ef9-4042-a7f9-473e8c7e28e3, 20160601_20160714_2110B_Airbnb_Inc._Redacted.pdf, 73520]  | 2016-07-14T00:00:00 | wm5f-tm26   | 2016-06-01T00:00:00 | 2016-06-30T00:00:00 | true     |             |                  | 2016-07-26T22:09:56       |                              | 12945.14                        | 
| Airbnb, Inc.  | [application/pdf, c61eebc4-be70-4287-95ac-d24a57ba0c0b, 20160801_20160902_2110B_Airbnb_Inc._Redacted.pdf, 222536] | 2016-09-02T00:00:00 | wm5f-tm26   | 2016-08-01T00:00:00 | 2016-08-31T00:00:00 |          |             |                  | 2016-09-02T22:31:44       |                              |                                 | 
```