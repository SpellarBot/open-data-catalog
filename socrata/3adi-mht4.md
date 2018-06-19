# Campaign Expenditures

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/campaign-expenditures) |
| Metadata | [Link](https://data.iowa.gov/api/views/3adi-mht4) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/3adi-mht4/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/3adi-mht4/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | 3adi-mht4 |
| Name | Campaign Expenditures |
| Attribution | Iowa Ethics and Campaign Disclosure Board, State/Local Campaign Disclosure Reports |
| Category | Government |
| Tags | political, campaigns, pac, candidates, party committees, state political committees, federal/out-of-state political committees, county/local committees, county central committees, ballot issue com... |
| Created | 2015-06-19T15:32:29Z |
| Publication Date | 2015-07-07T15:44:10Z |

## Description

This dataset contains information on expenditures made by state-wide, legislative or local candidate committees, state PACs, county central committees, state parties, and state and local ballot issue committees. Data is available beginning in 2003 for all reports filed electronically, and some paper filed reports.  Data is provided through reports submitted by candidate committees, state political committees, federal/out-of-state political committees, county central committees, ballot issue committees and organizations making contributions or independent expenditures.  Quality of the data provided in the dataset is dependent upon the accuracy of the data reported electronically.

## Columns

```ls
| Included | Schema Type    | Field Name       | Name                        | Data Type     | Render Type   |
| ======== | ============== | ================ | =========================== | ============= | ============= |
| Yes      | series tag     | transaction_id   | Transaction ID              | text          | text          |
| Yes      | time           | date             | Date                        | calendar_date | calendar_date |
| Yes      | series tag     | committee_cd     | Committee Code              | text          | number        |
| Yes      | series tag     | committee_nm     | Committee Name              | text          | text          |
| Yes      | series tag     | rec_committee_cd | Receiving Committee Code    | text          | number        |
| Yes      | series tag     | organization_nm  | Receiving Organization Name | text          | text          |
| Yes      | series tag     | first_nm         | First Name                  | text          | text          |
| Yes      | series tag     | initial_nm       | Middle Initial              | text          | text          |
| Yes      | series tag     | last_nm          | Last Name                   | text          | text          |
| No       |                | address_line_1   | Address - Line 1            | text          | text          |
| No       |                | address_line_2   | Address - Line 2            | text          | text          |
| Yes      | series tag     | city             | City                        | text          | text          |
| Yes      | series tag     | state_cd         | State                       | text          | text          |
| Yes      | series tag     | zip              | Zip                         | text          | text          |
| Yes      | numeric metric | amount           | Expenditure Amount          | money         | money         |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = address_line_1,address_line_2
```

## Data Commands

```ls
series e:3adi-mht4 d:2008-01-28T00:00:00.000Z t:committee_cd=662 t:rec_committee_cd=0 t:committee_nm="RANTS FOR STATE HOUSE COMMITTEE" t:organization_nm="DOLLAR CAR RENTAL" t:transaction_id={066AB80A-67B9-4364-85C4-74FF16A70889} m:amount=208

series e:3adi-mht4 d:2012-05-23T00:00:00.000Z t:zip=52247 t:state_cd=IA t:committee_cd=18824 t:committee_nm="Ciha for Supervisor" t:organization_nm="Kalona News" t:transaction_id={066AFC07-065B-406A-87D7-27896C8041F4} t:city=Kalona m:amount=51

series e:3adi-mht4 d:2013-01-04T00:00:00.000Z t:zip=52241 t:state_cd=IA t:committee_cd=9105 t:committee_nm="Johnson County Democratic Central Committee" t:organization_nm="Marriott Hotel Coralville" t:transaction_id={066B6451-3564-4F7E-B7A6-371CF0C0EB5E} t:city=Coralville m:amount=750
```

## Meta Commands

```ls
metric m:amount p:double l:"Expenditure Amount" d:"Dollar amount of expenditure made by the committee." t:dataTypeName=money

entity e:3adi-mht4 l:"Campaign Expenditures" t:attribution="Iowa Ethics and Campaign Disclosure Board, State/Local Campaign Disclosure Reports" t:url=https://data.iowa.gov/api/views/3adi-mht4

property e:3adi-mht4 t:meta.view v:id=3adi-mht4 v:category=Government v:attributionLink=https://webapp.iecdb.iowa.gov/publicview/Intro.aspx v:averageRating=0 v:name="Campaign Expenditures" v:attribution="Iowa Ethics and Campaign Disclosure Board, State/Local Campaign Disclosure Reports"

property e:3adi-mht4 t:meta.view.license v:name="Public Domain"

property e:3adi-mht4 t:meta.view.owner v:id=8x33-bu4e v:profileImageUrlMedium=/api/users/8x33-bu4e/profile_images/THUMB v:profileImageUrlLarge=/api/users/8x33-bu4e/profile_images/LARGE v:screenName="Ethics and Campaign Disclosure Board" v:profileImageUrlSmall=/api/users/8x33-bu4e/profile_images/TINY v:displayName="Ethics and Campaign Disclosure Board"

property e:3adi-mht4 t:meta.view.tableauthor v:id=8x33-bu4e v:profileImageUrlMedium=/api/users/8x33-bu4e/profile_images/THUMB v:profileImageUrlLarge=/api/users/8x33-bu4e/profile_images/LARGE v:screenName="Ethics and Campaign Disclosure Board" v:profileImageUrlSmall=/api/users/8x33-bu4e/profile_images/TINY v:roleName=editor v:displayName="Ethics and Campaign Disclosure Board"
```

## Top Records

```ls
| transaction_id                         | date                | committee_cd | committee_nm                                                 | rec_committee_cd | organization_nm                 | first_nm | initial_nm | last_nm | address_line_1           | address_line_2 | city       | state_cd | zip   | amount | 
| ====================================== | =================== | ============ | ============================================================ | ================ | =============================== | ======== | ========== | ======= | ======================== | ============== | ========== | ======== | ===== | ====== | 
| {066AB80A-67B9-4364-85C4-74FF16A70889} | 2008-01-28T00:00:00 | 662          | RANTS FOR STATE HOUSE COMMITTEE                              | 0                | DOLLAR CAR RENTAL               |          |            |         | FT MEYERS AIPORT         |                |            |          |       | 208    | 
| {066AFC07-065B-406A-87D7-27896C8041F4} | 2012-05-23T00:00:00 | 18824        | Ciha for Supervisor                                          |                  | Kalona News                     |          |            |         | 419 B Ave.               |                | Kalona     | IA       | 52247 | 51     | 
| {066B6451-3564-4F7E-B7A6-371CF0C0EB5E} | 2013-01-04T00:00:00 | 9105         | Johnson County Democratic Central Committee                  |                  | Marriott Hotel Coralville       |          |            |         | 300 E 9th St             |                | Coralville | IA       | 52241 | 750    | 
| {066B8D2B-842D-427E-A793-CF750E332F8A} | 2012-09-25T00:00:00 | 8659         | Quad County Corn Processors Cooperative PAC                  | 40019            | Citizens for Susan Judkins      |          |            |         | 14067 South Shore Drive  |                | Clive      | IA       | 50325 | 100    | 
| {066BA1ED-B762-4993-983D-D0F2D4040FA1} | 2012-09-26T00:00:00 | 1392         | Olson for State Representative Committee, Donovan Olson, Can |                  | US Postal Service               |          |            |         | 815 Arden Street         |                | Boone      | IA       | 50036 | 621    | 
| {066C343D-01BD-4F4B-8124-CC31610A2C01} | 2008-10-29T00:00:00 | 9126         | Mahaska County Republican Central Committee                  |                  | Oskaloosa Herald                |          |            |         | PO Box 530               |                | Oskaloosa  | IA       | 52577 | 577    | 
| {066C96CA-DEB4-491A-AB48-1DEF0854D013} | 2014-04-07T00:00:00 | 1604         | Citizens for Ako Abdul-Samad                                 |                  | Groupon                         |          |            |         | 600 W Chicago            | Ste 620        | Chicago    | IA       | 60654 | 19     | 
| {066CA1AE-39BC-4226-BCB9-F883B247943C} | 2013-11-05T00:00:00 | 14114        | Catherine Champion for Iowa City, City Council               |                  | Potpourri Inc                   |          |            |         | 7 south dubuque street   |                | iowa city  | IA       | 52240 | 548.37 | 
| {066D3285-566D-458D-B3F9-C320772E3383} | 2010-09-14T00:00:00 | 6098         | Iowa BEV PAC #6098                                           | 564              | Murphy for State Representative |          |            |         | 155 North Grandview Ave. |                | Dubuque    | IA       | 52001 | 3000   | 
| {066D786B-7CB8-49FA-A3E1-40F97B3B1AB8} | 2011-10-12T00:00:00 | 14021        | Citizens to Elect Krempel                                    |                  | US Bank                         |          |            |         | 2300 North 3rd St        |                | Clinton    | IA       | 52732 | 27.06  | 
```