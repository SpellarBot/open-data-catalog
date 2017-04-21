# Other Receipts For Hawaii State and County Candidates From November 8, 2006 Through December 31, 2016

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/other-receipts-for-hawaii-state-and-county-candidates-from-november-8-2006-through-novembe) |
| Metadata | [Link](https://data.hawaii.gov/api/views/ue3d-efjr) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/ue3d-efjr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/ue3d-efjr/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | ue3d-efjr |
| Name | Other Receipts For Hawaii State and County Candidates From November 8, 2006 Through December 31, 2016 |
| Attribution | State of Hawaii; Campaign Spending Commission |
| Category | Community |
| Tags | campaign spending commission, campaign finance, candidate, hawaii candidates, contributions, political contributions, campaign contributions, campaign spending |
| Created | 2013-02-26T00:42:30Z |
| Publication Date | 2017-03-13T23:57:24Z |

## Columns

```ls
| Included | Schema Type    | Field Name                | Name                      | Data Type     | Render Type   |
| ======== | ============== | ========================= | ========================= | ============= | ============= |
| Yes      | series tag     | candidate_name            | Candidate Name            | text          | text          |
| Yes      | series tag     | source_type               | Source Type               | text          | text          |
| Yes      | series tag     | source_name               | Source Name               | text          | text          |
| Yes      | time           | date                      | Date                      | calendar_date | calendar_date |
| Yes      | numeric metric | amount                    | Amount                    | money         | money         |
| Yes      | series tag     | other_receipt_category    | Other Receipt Category    | text          | text          |
| Yes      | series tag     | other_receipt_description | Other Receipt Description | text          | text          |
| No       |                | address_1                 | Address 1                 | text          | text          |
| No       |                | address_2                 | Address 2                 | text          | text          |
| Yes      | series tag     | city                      | City                      | text          | text          |
| Yes      | series tag     | state                     | State                     | text          | text          |
| Yes      | series tag     | zip_code                  | Zip Code                  | text          | text          |
| Yes      | series tag     | office                    | Office                    | text          | text          |
| Yes      | series tag     | district                  | District                  | text          | text          |
| Yes      | series tag     | county                    | County                    | text          | text          |
| Yes      | series tag     | party                     | Party                     | text          | text          |
| Yes      | series tag     | reg_no                    | Reg No                    | text          | text          |
| Yes      | series tag     | election_period           | Election Period           | text          | text          |
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
series e:ue3d-efjr d:2016-06-07T00:00:00.000Z t:office=House t:zip_code=96793 t:other_receipt_category="Candidate's Own Funds" t:candidate_name="Abbett, Richard" t:state=HI t:source_type=CAN t:party=Democrat t:other_receipt_description="Funds for filing fee" t:reg_no=CC11314 t:city=Wailuku t:election_period=2014-2016 t:source_name="Abbett, Richard" t:district=8 m:amount=25

series e:ue3d-efjr d:2016-06-16T00:00:00.000Z t:office=House t:zip_code=96793 t:other_receipt_category="Candidate's Own Funds" t:candidate_name="Abbett, Richard" t:state=HI t:source_type=CAN t:party=Democrat t:other_receipt_description="Opening Deposit" t:reg_no=CC11314 t:city=Wailuku t:election_period=2014-2016 t:source_name="Abbett, Richard" t:district=8 m:amount=100

series e:ue3d-efjr d:2016-07-22T00:00:00.000Z t:office=House t:zip_code=96793 t:other_receipt_category="Candidate's Own Funds" t:candidate_name="Abbett, Richard" t:state=HI t:source_type=CAN t:party=Democrat t:other_receipt_description="Candidates own funds" t:reg_no=CC11314 t:city=Wailuku t:election_period=2014-2016 t:source_name="Abbett, Richard" t:district=8 m:amount=100
```

## Meta Commands

```ls
metric m:amount p:double l:Amount t:dataTypeName=money

entity e:ue3d-efjr l:"Other Receipts For Hawaii State and County Candidates From November 8, 2006 Through December 31, 2016" t:attribution="State of Hawaii; Campaign Spending Commission" t:url=https://data.hawaii.gov/api/views/ue3d-efjr

property e:ue3d-efjr t:meta.view v:id=ue3d-efjr v:category=Community v:attributionLink=http://www.hawaii.gov/campaign v:averageRating=0 v:name="Other Receipts For Hawaii State and County Candidates From November 8, 2006 Through December 31, 2016" v:attribution="State of Hawaii; Campaign Spending Commission"

property e:ue3d-efjr t:meta.view.owner v:id=g6c2-gabj v:profileImageUrlMedium=/api/users/g6c2-gabj/profile_images/THUMB v:profileImageUrlLarge=/api/users/g6c2-gabj/profile_images/LARGE v:screenName="Hawaii Campaign Spending Commission" v:profileImageUrlSmall=/api/users/g6c2-gabj/profile_images/TINY v:displayName="Hawaii Campaign Spending Commission"

property e:ue3d-efjr t:meta.view.tableauthor v:id=g6c2-gabj v:profileImageUrlMedium=/api/users/g6c2-gabj/profile_images/THUMB v:profileImageUrlLarge=/api/users/g6c2-gabj/profile_images/LARGE v:screenName="Hawaii Campaign Spending Commission" v:profileImageUrlSmall=/api/users/g6c2-gabj/profile_images/TINY v:roleName=editor v:displayName="Hawaii Campaign Spending Commission"
```

## Top Records

```ls
| candidate_name    | source_type | source_name          | date                | amount  | other_receipt_category | other_receipt_description                       | address_1                    | address_2 | city        | state | zip_code | office         | district | county | party        | reg_no  | election_period | 
| ================= | =========== | ==================== | =================== | ======= | ====================== | =============================================== | ============================ | ========= | =========== | ===== | ======== | ============== | ======== | ====== | ============ | ======= | =============== | 
| Abbett, Richard   | CAN         | Abbett, Richard      | 2016-06-07T00:00:00 | 25      | Candidate's Own Funds  | Funds for filing fee                            | PO BOX 2734                  |           | Wailuku     | HI    | 96793    | House          | 8        |        | Democrat     | CC11314 | 2014-2016       | 
| Abbett, Richard   | CAN         | Abbett, Richard      | 2016-06-16T00:00:00 | 100     | Candidate's Own Funds  | Opening Deposit                                 | PO BOX 2734                  |           | Wailuku     | HI    | 96793    | House          | 8        |        | Democrat     | CC11314 | 2014-2016       | 
| Abbett, Richard   | CAN         | Abbett, Richard      | 2016-07-22T00:00:00 | 100     | Candidate's Own Funds  | Candidates own funds                            | PO BOX 2734                  |           | Wailuku     | HI    | 96793    | House          | 8        |        | Democrat     | CC11314 | 2014-2016       | 
| Abbett, Richard   | CAN         | Abbett, Richard      | 2016-09-29T00:00:00 | 20      | Candidate's Own Funds  | Candidate's Own Funds                           | PO BOX 2734                  |           | Wailuku     | HI    | 96793    | House          | 8        |        | Democrat     | CC11314 | 2014-2016       | 
| Abbett, Richard   | CAN         | Abbett, Richard E.   | 2014-04-25T00:00:00 | 26.25   | Candidate's Own Funds  | Funds for Candidate Filing Fee                  | PO BOX 6201                  |           | Ocean View  | HI    | 96737    | Hawaii Council | 6        | Hawaii | Non-Partisan | CC11028 | 2012-2014       | 
| Abbett, Richard   | CAN         | Abbett, Richard E.   | 2014-11-17T00:00:00 | 6.25    | Candidate's Own Funds  | mileage for gas                                 | PO BOX 6201                  |           | Ocean View  | HI    | 96737    | Hawaii Council | 6        | Hawaii | Non-Partisan | CC11028 | 2014-2016       | 
| Abbett, Richard   | CAN         | Abbett, Richard E.   | 2014-12-04T00:00:00 | 93.75   | Candidate's Own Funds  | advertising                                     | PO BOX 6201                  |           | Ocean View  | HI    | 96737    | Hawaii Council | 6        | Hawaii | Non-Partisan | CC11028 | 2014-2016       | 
| Abbett, Richard   | CAN         | Abbett, Richard E.   | 2014-12-04T00:00:00 | 1445.22 | Candidate's Own Funds  | campaign expenses                               | PO BOX 6201                  |           | Ocean View  | HI    | 96737    | Hawaii Council | 6        | Hawaii | Non-Partisan | CC11028 | 2014-2016       | 
| Abercrombie, Neil | IND         | Benabese, Anthony P. | 2014-08-30T00:00:00 | 45      | Sale of Durable Asset  | Printer                                         | 41-910 Kakaina Street        |           | Waimanalo   | HI    | 96795    | Governor       |          |        | Democrat     | CC10529 | 2012-2014       | 
| Abercrombie, Neil | IND         | Coatney, Reba M.     | 2010-12-09T00:00:00 | 1252.34 | Refund                 | Security Deposit - Neighbor island Head Quarter | 75-5656 Kuakini Hwy Ste 102A |           | Kailua-Kona | HI    | 96740    | Governor       |          |        | Democrat     | CC10529 | 2010-2012       | 
```