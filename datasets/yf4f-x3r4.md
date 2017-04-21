# Loans Received By Hawaii State and County Candidates From November 8, 2006 Through December 31, 2016

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/loans-received-by-hawaii-state-and-county-candidates-from-november-8-2006-through-november) |
| Metadata | [Link](https://data.hawaii.gov/api/views/yf4f-x3r4) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/yf4f-x3r4/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/yf4f-x3r4/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | yf4f-x3r4 |
| Name | Loans Received By Hawaii State and County Candidates From November 8, 2006 Through December 31, 2016 |
| Attribution | State of Hawaii; Campaign Spending Commission |
| Category | Community |
| Tags | campaign spending commission, campaign finance, candidate, hawaii candidates, contributions, political contributions, campaign contributions, campaign spending |
| Created | 2013-02-26T00:16:12Z |
| Publication Date | 2017-03-13T23:58:16Z |

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type     | Render Type   |
| ======== | ============== | =============== | =============== | ============= | ============= |
| Yes      | series tag     | candidate_name  | Candidate Name  | text          | text          |
| Yes      | series tag     | lender_type     | Lender Type     | text          | text          |
| Yes      | series tag     | lender_name     | Lender Name     | text          | text          |
| Yes      | time           | date            | Date            | calendar_date | calendar_date |
| Yes      | numeric metric | amount          | Loan Amount     | money         | money         |
| Yes      | series tag     | loan_type       | Loan Type       | text          | text          |
| Yes      | series tag     | loan_source     | Loan Source     | text          | text          |
| Yes      | series tag     | purpose_of_loan | Purpose of Loan | text          | text          |
| Yes      | numeric metric | repay_amount    | Repay Amount    | money         | money         |
| Yes      | series tag     | loan_id         | Loan ID         | text          | text          |
| Yes      | series tag     | forgiven        | Forgiven        | text          | text          |
| No       |                | address_1       | Address 1       | text          | text          |
| No       |                | address_2       | Address 2       | text          | text          |
| Yes      | series tag     | city            | City            | text          | text          |
| Yes      | series tag     | state           | State           | text          | text          |
| Yes      | series tag     | zip_code        | Zip Code        | text          | text          |
| Yes      | series tag     | office          | Office          | text          | text          |
| Yes      | series tag     | district        | District        | text          | text          |
| Yes      | series tag     | county          | County          | text          | text          |
| Yes      | series tag     | party           | Party           | text          | text          |
| Yes      | series tag     | reg_no          | Reg No          | text          | text          |
| Yes      | series tag     | election_period | Election Period | text          | text          |
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
series e:yf4f-x3r4 d:2014-06-05T14:15:07.000Z t:office="Hawaii Council" t:loan_type=CAN t:zip_code=96737 t:candidate_name="Abbett, Richard" t:state=HI t:forgiven=N t:loan_source=Candidate t:party=Non-Partisan t:reg_no=CC11028 t:city="Ocean View" t:election_period=2012-2014 t:county=Hawaii t:lender_name="Abbett, Richard E." t:district=6 t:lender_type=CAN t:purpose_of_loan="Campaign Signs" t:loan_id=6428 m:amount=1445.22

series e:yf4f-x3r4 d:2014-12-04T09:15:45.000Z t:office="Hawaii Council" t:zip_code=96737 t:candidate_name="Abbett, Richard" t:state=HI t:forgiven=Y t:party=Non-Partisan t:reg_no=CC11028 t:city="Ocean View" t:election_period=2014-2016 t:lender_name="Abbett, Richard E." t:county=Hawaii t:district=6 t:lender_type=CAN t:loan_id=6428 m:repay_amount=1445.22

series e:yf4f-x3r4 d:2014-04-11T03:48:24.000Z t:office=House t:loan_type=CAN t:zip_code=96701-5314 t:candidate_name="Agustin, Jaci" t:state=HI t:forgiven=N t:loan_source=Candidate t:party=Republican t:reg_no=CC11062 t:city=AIEA t:election_period=2012-2014 t:lender_name="AGUSTIN, JACI" t:district=34 t:lender_type=CAN t:purpose_of_loan="Parking & Mailbox rental" t:loan_id=6416 m:amount=204.92
```

## Meta Commands

```ls
metric m:amount p:double l:"Loan Amount" t:dataTypeName=money

metric m:repay_amount p:double l:"Repay Amount" t:dataTypeName=money

entity e:yf4f-x3r4 l:"Loans Received By Hawaii State and County Candidates From November 8, 2006 Through December 31, 2016" t:attribution="State of Hawaii; Campaign Spending Commission" t:url=https://data.hawaii.gov/api/views/yf4f-x3r4

property e:yf4f-x3r4 t:meta.view v:id=yf4f-x3r4 v:category=Community v:attributionLink=http://www.hawaii.gov/campaign v:averageRating=0 v:name="Loans Received By Hawaii State and County Candidates From November 8, 2006 Through December 31, 2016" v:attribution="State of Hawaii; Campaign Spending Commission"

property e:yf4f-x3r4 t:meta.view.owner v:id=g6c2-gabj v:profileImageUrlMedium=/api/users/g6c2-gabj/profile_images/THUMB v:profileImageUrlLarge=/api/users/g6c2-gabj/profile_images/LARGE v:screenName="Hawaii Campaign Spending Commission" v:profileImageUrlSmall=/api/users/g6c2-gabj/profile_images/TINY v:displayName="Hawaii Campaign Spending Commission"

property e:yf4f-x3r4 t:meta.view.tableauthor v:id=g6c2-gabj v:profileImageUrlMedium=/api/users/g6c2-gabj/profile_images/THUMB v:profileImageUrlLarge=/api/users/g6c2-gabj/profile_images/LARGE v:screenName="Hawaii Campaign Spending Commission" v:profileImageUrlSmall=/api/users/g6c2-gabj/profile_images/TINY v:roleName=editor v:displayName="Hawaii Campaign Spending Commission"
```

## Top Records

```ls
| candidate_name  | lender_type | lender_name        | date                | amount  | loan_type | loan_source | purpose_of_loan                                     | repay_amount | loan_id | forgiven | address_1                 | address_2 | city       | state | zip_code   | office         | district | county | party        | reg_no  | election_period | 
| =============== | =========== | ================== | =================== | ======= | ========= | =========== | =================================================== | ============ | ======= | ======== | ========================= | ========= | ========== | ===== | ========== | ============== | ======== | ====== | ============ | ======= | =============== | 
| Abbett, Richard | CAN         | Abbett, Richard E. | 2014-06-05T14:15:07 | 1445.22 | CAN       | Candidate   | Campaign Signs                                      |              | 6428    | N        | PO BOX 6201               |           | Ocean View | HI    | 96737      | Hawaii Council | 6        | Hawaii | Non-Partisan | CC11028 | 2012-2014       | 
| Abbett, Richard | CAN         | Abbett, Richard E. | 2014-12-04T09:15:45 |         |           |             |                                                     | 1445.22      | 6428    | Y        | PO BOX 6201               |           | Ocean View | HI    | 96737      | Hawaii Council | 6        | Hawaii | Non-Partisan | CC11028 | 2014-2016       | 
| Agustin, Jaci   | CAN         | AGUSTIN, JACI      | 2014-04-11T03:48:24 | 204.92  | CAN       | Candidate   | Parking & Mailbox rental                            |              | 6416    | N        | 98-1277 KAAHUMANU ST #106 | PMB 196   | AIEA       | HI    | 96701-5314 | House          | 34       |        | Republican   | CC11062 | 2012-2014       | 
| Agustin, Jaci   | CAN         | AGUSTIN, JACI      | 2014-05-08T03:49:03 | 618.85  | CAN       | Candidate   | 30 signs 12"x24" from Signs by Dey                  |              | 6417    | N        | 98-1277 KAAHUMANU ST #106 | PMB 196   | AIEA       | HI    | 96701-5314 | House          | 34       |        | Republican   | CC11062 | 2012-2014       | 
| Agustin, Jaci   | CAN         | AGUSTIN, JACI      | 2014-05-12T03:49:53 | 129.98  | CAN       | Candidate   | fundraiser invitations from Vistaprint              |              | 6418    | N        | 98-1277 KAAHUMANU ST #106 | PMB 196   | AIEA       | HI    | 96701-5314 | House          | 34       |        | Republican   | CC11062 | 2012-2014       | 
| Agustin, Jaci   | CAN         | AGUSTIN, JACI      | 2014-05-13T03:51:10 | 3386.6  | CAN       | Candidate   | Becker Comm 50% init pymt: website, facebook, email |              | 6419    | N        | 98-1277 KAAHUMANU ST #106 | PMB 196   | AIEA       | HI    | 96701-5314 | House          | 34       |        | Republican   | CC11062 | 2012-2014       | 
| Agustin, Jaci   | CAN         | AGUSTIN, JACI      | 2014-06-02T03:52:01 | 250     | CAN       | Candidate   | Hawaii Ofc of Elections: State Candidacy Filing Fee |              | 6420    | N        | 98-1277 KAAHUMANU ST #106 | PMB 196   | AIEA       | HI    | 96701-5314 | House          | 34       |        | Republican   | CC11062 | 2012-2014       | 
| Agustin, Jaci   | CAN         | AGUSTIN, JACI      | 2014-06-16T04:00:11 | 100     | CAN       | Candidate   | dpstd 6/16/14: to cover cost of canvass cards       |              | 6421    | N        | 98-1277 KAAHUMANU ST #106 | PMB 196   | AIEA       | HI    | 96701-5314 | House          | 34       |        | Republican   | CC11062 | 2012-2014       | 
| Agustin, Jaci   | CAN         | AGUSTIN, JACI      | 2014-07-14T22:17:51 | 265.6   | CAN       | Candidate   | food for Campaign Kickoff Fundraiser                |              | 6984    | N        | 98-1277 KAAHUMANU ST #106 | PMB 196   | AIEA       | HI    | 96701-5314 | House          | 34       |        | Republican   | CC11062 | 2012-2014       | 
| Agustin, Jaci   | CAN         | AGUSTIN, JACI      | 2014-10-10T22:18:40 | 1417.33 | CAN       | Candidate   | Reskyu: printing of mailer                          |              | 6986    | N        | 98-1277 KAAHUMANU ST #106 | PMB 196   | AIEA       | HI    | 96701-5314 | House          | 34       |        | Republican   | CC11062 | 2012-2014       | 
```