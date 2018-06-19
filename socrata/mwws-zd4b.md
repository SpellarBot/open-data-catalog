# Campaign Finance / Lobbyist - Filers With Unpaid Late Filing Fees

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/campaign-finance-filers-with-unpaid-late-filing-fees-cbdde) |
| Metadata | [Link](https://data.sfgov.org/api/views/mwws-zd4b) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/mwws-zd4b/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/mwws-zd4b/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | mwws-zd4b |
| Name | Campaign Finance / Lobbyist - Filers With Unpaid Late Filing Fees |
| Attribution | San Francisco Ethics Commission |
| Category | City Management and Ethics |
| Tags | campaign finance, fines, late fees, ethics, lobbyist |
| Created | 2013-03-12T21:32:43Z |
| Publication Date | 2017-02-10T19:24:05Z |

## Description

The filers in the table below have not paid one or more late filing fees.  The filers listed below have not responded to two or more written notices and one or more verbal notices regarding late filing fees.  Filers posted to this list for not paying late filing fees are removed from this list after paying their late fees or four (4) years have elapsed since the Executive Director's final determination of the late fees (i.e., the date the late fees are assessed or the date the Executive Director makes a determination in response to a request for waiver, if any).In addition to being listed in the table below, filers whose late fees remain unpaid may be referred to the Bureau of Delinquent Revenues at the Treasurer and Tax Collectors Office.

## Columns

```ls
| Included | Schema Type    | Field Name      | Name                       | Data Type      | Render Type    |
| ======== | ============== | =============== | ========================== | ============== | ============== |
| No       | time           | :updated_at     | updated_at                 | meta_data      | meta_data      |
| Yes      | series tag     | committee_name  | COMMITTEE OR LOBBYIST NAME | text           | text           |
| Yes      | series tag     | fppc_id         | ID #                       | text           | text           |
| Yes      | series tag     | treasurer       | TREASURER                  | text           | text           |
| Yes      | numeric metric | delinquent_fees | DELINQUENT FEES            | money          | money          |
| Yes      | series tag     | fee_type        | FEE TYPE                   | drop_down_list | drop_down_list |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:mwws-zd4b d:2017-02-10T19:23:56.000Z t:committee_name="Committee to Stop Mass Demolition of Housing, A Committee to Support Proposition" t:fppc_id=1339557 t:treasurer="Ted Gullicksen" m:delinquent_fees=25

series e:mwws-zd4b d:2017-02-10T19:23:56.000Z t:committee_name="JKW Political Consulting" t:fppc_id=100716 t:treasurer="Johnny K. Wang" m:delinquent_fees=4000

series e:mwws-zd4b d:2017-02-10T19:23:56.000Z t:committee_name="Coalition to Elect Chris Jackson to Community College Board" t:fppc_id=1302351 t:treasurer="Chris Jackson" m:delinquent_fees=2658.9
```

## Meta Commands

```ls
metric m:delinquent_fees p:double l:"DELINQUENT FEES" t:dataTypeName=money

entity e:mwws-zd4b l:"Campaign Finance / Lobbyist - Filers With Unpaid Late Filing Fees" t:attribution="San Francisco Ethics Commission" t:url=https://data.sfgov.org/api/views/mwws-zd4b

property e:mwws-zd4b t:meta.view v:id=mwws-zd4b v:category="City Management and Ethics" v:attributionLink=http://www.sfethics.org v:averageRating=0 v:name="Campaign Finance / Lobbyist - Filers With Unpaid Late Filing Fees" v:attribution="San Francisco Ethics Commission"

property e:mwws-zd4b t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:mwws-zd4b t:meta.view.owner v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:displayName="Steven Massey"

property e:mwws-zd4b t:meta.view.tableauthor v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:roleName=publisher v:displayName="Steven Massey"
```

## Top Records

```ls
| :updated_at | committee_name                                                                   | fppc_id     | treasurer         | delinquent_fees | fee_type  | 
| =========== | ================================================================================ | =========== | ================= | =============== | ========= | 
| 1486754636  | Committee to Stop Mass Demolition of Housing, A Committee to Support Proposition | 1339557     | Ted Gullicksen    | 25.00           |           | 
| 1486754636  | JKW Political Consulting                                                         | 100716      | Johnny K. Wang    | 4000.00         |           | 
| 1486754636  | Coalition to Elect Chris Jackson to Community College Board                      | 1302351     | Chris Jackson     | 2658.90         |           | 
| 1486754636  | Chris Jackson for Community College Board 2012                                   | 1347066     | Chris Jackson     | 14550.94        |           | 
| 1486754636  | San Francisco Late Night Coalition (SFLNC)                                       | 991861      | John Wood         | 250.00          |           | 
| 1486754636  | Bob Squeri for District 7 Supervisor 2012                                        | 1346150     | Bob Squeri        | 2000.00         |           | 
| 1486754636  | Committee to Elect Norman for Supervisor, 2010                                   | 1327771     | Jacqueline Norman | 9000.00         |           | 
| 1486754636  | Coalition to Protect Golden Gate Park, Yes on H                                  | 1367676     | Michael Murphy    | 25.00           |           | 
| 1486754636  | Isabel Urbano                                                                    | SFO #153993 | Isabel Urbano     | 7000.00         | zag7-9frc | 
| 1486754636  | Yes on J - San Franciscans for Preserving Legacy Business                        | 1378390     | Stacy Owens       | 1250.00         |           | 
```