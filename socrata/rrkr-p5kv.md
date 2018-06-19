# Unpaid Expenditures For Hawaii State and County Candidates From November 8, 2006 Through December 31, 2016

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/unpaid-expenditures-for-hawaii-state-and-county-candidates-from-november-8-2006-through-no) |
| Metadata | [Link](https://data.hawaii.gov/api/views/rrkr-p5kv) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/rrkr-p5kv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/rrkr-p5kv/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | rrkr-p5kv |
| Name | Unpaid Expenditures For Hawaii State and County Candidates From November 8, 2006 Through December 31, 2016 |
| Attribution | State of Hawaii; Campaign Spending Commission |
| Category | Community |
| Tags | campaign spending commission, campaign finance, candidate, hawaii candidates, contributions, political contributions, campaign contributions, campaign spending |
| Created | 2013-02-26T00:05:09Z |
| Publication Date | 2017-03-13T23:59:18Z |

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                      | Data Type     | Render Type   |
| ======== | ============== | ====================== | ========================= | ============= | ============= |
| Yes      | series tag     | candidate_name         | Candidate Name            | text          | text          |
| Yes      | series tag     | vendor_type            | Vendor Type               | text          | text          |
| Yes      | series tag     | vendor_name            | Vendor Name               | text          | text          |
| Yes      | time           | date                   | Date                      | calendar_date | calendar_date |
| Yes      | numeric metric | amount                 | Unpaid Expenditure Amount | money         | money         |
| Yes      | series tag     | expenditure_category   | Expenditure Category      | text          | text          |
| Yes      | series tag     | purpose_of_expenditure | Purpose of Expenditure    | text          | text          |
| Yes      | numeric metric | repay_amount           | Repay Amount              | money         | money         |
| Yes      | series tag     | unpaid_expenditure_id  | Unpaid Expenditure ID     | text          | text          |
| Yes      | series tag     | forgiven               | Forgiven                  | text          | text          |
| No       |                | address_1              | Address 1                 | text          | text          |
| No       |                | address_2              | Address 2                 | text          | text          |
| Yes      | series tag     | city                   | City                      | text          | text          |
| Yes      | series tag     | state                  | State                     | text          | text          |
| Yes      | series tag     | zip_code               | Zip Code                  | text          | text          |
| Yes      | series tag     | office                 | Office                    | text          | text          |
| Yes      | series tag     | district               | District                  | text          | text          |
| Yes      | series tag     | county                 | County                    | text          | text          |
| Yes      | series tag     | party                  | Party                     | text          | text          |
| Yes      | series tag     | reg_no                 | Reg No                    | text          | text          |
| Yes      | series tag     | election_period        | Election Period           | text          | text          |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = address_1,address_2
```

## Data Commands

```ls
series e:rrkr-p5kv d:2014-08-22T17:49:08.000Z t:office=Governor t:election_period=2012-2014 t:zip_code=96797 t:candidate_name="Abercrombie, Neil" t:state=HI t:unpaid_expenditure_id=5444 t:forgiven=N t:party=Democrat t:vendor_type=OTH t:vendor_name="A Catered Experience" t:reg_no=CC10529 t:city=Waipahu m:repay_amount=471.2

series e:rrkr-p5kv d:2010-08-11T19:03:32.000Z t:office=Governor t:zip_code=96793 t:candidate_name="Abercrombie, Neil" t:state=HI t:forgiven=N t:unpaid_expenditure_id=2215 t:expenditure_category=Other t:party=Democrat t:reg_no=CC10529 t:city=Kaneohe t:election_period=2008-2010 t:purpose_of_expenditure="Promotional Clips and pens" t:vendor_type=OTH t:vendor_name="Advertising Promotions Pacific" m:amount=7878.62

series e:rrkr-p5kv d:2010-09-07T15:44:55.000Z t:office=Governor t:election_period=2008-2010 t:zip_code=96793 t:candidate_name="Abercrombie, Neil" t:state=HI t:unpaid_expenditure_id=2215 t:forgiven=N t:party=Democrat t:vendor_type=OTH t:vendor_name="Advertising Promotions Pacific" t:reg_no=CC10529 t:city=Kaneohe m:repay_amount=7878.62
```

## Meta Commands

```ls
metric m:amount p:double l:"Unpaid Expenditure Amount" t:dataTypeName=money

metric m:repay_amount p:double l:"Repay Amount" t:dataTypeName=money

entity e:rrkr-p5kv l:"Unpaid Expenditures For Hawaii State and County Candidates From November 8, 2006 Through December 31, 2016" t:attribution="State of Hawaii; Campaign Spending Commission" t:url=https://data.hawaii.gov/api/views/rrkr-p5kv

property e:rrkr-p5kv t:meta.view v:id=rrkr-p5kv v:category=Community v:attributionLink=http://www.hawaii.gov/campaign v:averageRating=0 v:name="Unpaid Expenditures For Hawaii State and County Candidates From November 8, 2006 Through December 31, 2016" v:attribution="State of Hawaii; Campaign Spending Commission"

property e:rrkr-p5kv t:meta.view.owner v:id=g6c2-gabj v:profileImageUrlMedium=/api/users/g6c2-gabj/profile_images/THUMB v:profileImageUrlLarge=/api/users/g6c2-gabj/profile_images/LARGE v:screenName="Hawaii Campaign Spending Commission" v:profileImageUrlSmall=/api/users/g6c2-gabj/profile_images/TINY v:displayName="Hawaii Campaign Spending Commission"

property e:rrkr-p5kv t:meta.view.tableauthor v:id=g6c2-gabj v:profileImageUrlMedium=/api/users/g6c2-gabj/profile_images/THUMB v:profileImageUrlLarge=/api/users/g6c2-gabj/profile_images/LARGE v:screenName="Hawaii Campaign Spending Commission" v:profileImageUrlSmall=/api/users/g6c2-gabj/profile_images/TINY v:roleName=editor v:displayName="Hawaii Campaign Spending Commission"
```

## Top Records

```ls
| candidate_name    | vendor_type | vendor_name                    | date                | amount  | expenditure_category | purpose_of_expenditure                | repay_amount | unpaid_expenditure_id | forgiven | address_1                   | address_2 | city    | state | zip_code | office   | district | county | party    | reg_no  | election_period | 
| ================= | =========== | ============================== | =================== | ======= | ==================== | ===================================== | ============ | ===================== | ======== | =========================== | ========= | ======= | ===== | ======== | ======== | ======== | ====== | ======== | ======= | =============== | 
| Abercrombie, Neil | OTH         | A Catered Experience           | 2014-08-22T17:49:08 |         |                      |                                       | 471.2        | 5444                  | N        | 94-1068 Ka Uka Blvd         |           | Waipahu | HI    | 96797    | Governor |          |        | Democrat | CC10529 | 2012-2014       | 
| Abercrombie, Neil | OTH         | Advertising Promotions Pacific | 2010-08-11T19:03:32 | 7878.62 | Other                | Promotional Clips and pens            |              | 2215                  | N        | 46-208 Kahuhipa Street #203 |           | Kaneohe | HI    | 96793    | Governor |          |        | Democrat | CC10529 | 2008-2010       | 
| Abercrombie, Neil | OTH         | Advertising Promotions Pacific | 2010-09-07T15:44:55 |         |                      |                                       | 7878.62      | 2215                  | N        | 46-208 Kahuhipa Street #203 |           | Kaneohe | HI    | 96793    | Governor |          |        | Democrat | CC10529 | 2008-2010       | 
| Abercrombie, Neil | OTH         | Aiea Copy Center               | 2009-10-29T10:05:20 | 91.09   | Printing             | Envelopes                             |              | 1241                  | N        | 99-115 Aiea Heights Drive   |           | Aiea    | HI    | 96701    | Governor |          |        | Democrat | CC10529 | 2008-2010       | 
| Abercrombie, Neil | OTH         | Aiea Copy Center               | 2010-01-14T20:37:29 |         |                      |                                       | 91.09        | 1241                  | N        | 99-115 Aiea Heights Drive   |           | Aiea    | HI    | 96701    | Governor |          |        | Democrat | CC10529 | 2008-2010       | 
| Abercrombie, Neil | OTH         | Aiea Copy Center               | 2010-08-31T19:23:23 | 672.18  | Printing             | Printing collateral materials         |              | 2221                  | N        | 99-115 Aiea Heights Drive   |           | Aiea    | HI    | 96701    | Governor |          |        | Democrat | CC10529 | 2008-2010       | 
| Abercrombie, Neil | OTH         | Aiea Copy Center               | 2010-09-09T16:02:04 |         |                      |                                       | 672.18       | 2221                  | N        | 99-115 Aiea Heights Drive   |           | Aiea    | HI    | 96701    | Governor |          |        | Democrat | CC10529 | 2008-2010       | 
| Abercrombie, Neil | OTH         | Aiea Copy Center               | 2013-06-26T17:35:09 | 18.48   | Printing             | Copying Charges - Registration Roster |              | 4675                  | N        | 99-115 Aiea Heights Drive   |           | Aiea    | HI    | 96701    | Governor |          |        | Democrat | CC10529 | 2012-2014       | 
| Abercrombie, Neil | OTH         | Aiea Copy Center               | 2013-07-09T17:35:28 |         |                      |                                       | 18.48        | 4675                  | N        | 99-115 Aiea Heights Drive   |           | Aiea    | HI    | 96701    | Governor |          |        | Democrat | CC10529 | 2012-2014       | 
| Abercrombie, Neil | OTH         | Aiea Copy Center               | 2013-11-09T12:04:13 | 43.97   | Printing             | Flyers                                |              | 4817                  | N        | 99-115 Aiea Heights Drive   |           | Aiea    | HI    | 96701    | Governor |          |        | Democrat | CC10529 | 2012-2014       | 
```