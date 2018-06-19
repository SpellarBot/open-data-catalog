# Expenditures Made By Hawaii Noncandidate Committees From January 1, 2008 Through December 31, 2016

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/expenditures-made-by-hawaii-noncandidate-committees-from-january-1-2008-through-november-4) |
| Metadata | [Link](https://data.hawaii.gov/api/views/riiu-7d4b) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/riiu-7d4b/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/riiu-7d4b/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | riiu-7d4b |
| Name | Expenditures Made By Hawaii Noncandidate Committees From January 1, 2008 Through December 31, 2016 |
| Attribution | State of Hawaii; Campaign Spending Commission |
| Category | Community |
| Tags | campaign spending commission, campaign finance, candidate, hawaii candidates, contributions, political contributions, campaign contributions, campaign spending |
| Created | 2013-02-22T21:32:09Z |
| Publication Date | 2017-03-17T23:59:58Z |

## Columns

```ls
| Included | Schema Type    | Field Name                  | Name                        | Data Type     | Render Type   |
| ======== | ============== | =========================== | =========================== | ============= | ============= |
| Yes      | series tag     | noncandidate_committee_name | Noncandidate Committee Name | text          | text          |
| Yes      | series tag     | vendor_type                 | Vendor Type                 | text          | text          |
| Yes      | series tag     | vendor_name                 | Vendor Name                 | text          | text          |
| Yes      | time           | date                        | Date                        | calendar_date | calendar_date |
| Yes      | numeric metric | amount                      | Amount                      | money         | money         |
| Yes      | series tag     | expenditure_category        | Expenditure Category        | text          | text          |
| Yes      | series tag     | purpose_of_expenditure      | Purpose of Expenditure      | text          | text          |
| Yes      | series tag     | independent_expenditure     | Independent Expenditure     | text          | text          |
| Yes      | series tag     | candidate_name_s            | Candidate Name(s)           | text          | text          |
| Yes      | series tag     | support_oppose              | Support/Oppose              | text          | text          |
| No       |                | address_1                   | Address 1                   | text          | text          |
| No       |                | address_2                   | Address 2                   | text          | text          |
| Yes      | series tag     | city                        | City                        | text          | text          |
| Yes      | series tag     | state                       | State                       | text          | text          |
| Yes      | series tag     | zip_code                    | Zip Code                    | text          | text          |
| Yes      | series tag     | reg_no                      | Reg No                      | text          | text          |
| Yes      | series tag     | election_period             | Election Period             | text          | text          |
| Yes      | series tag     | inoutstate                  | InOutState                  | text          | text          |
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
series e:riiu-7d4b d:2010-08-10T00:00:00.000Z t:inoutstate=HI t:election_period=2008-2010 t:independent_expenditure=Expenditure t:zip_code=96706 t:purpose_of_expenditure="Consulting & Accounting Services" t:noncandidate_committee_name="8th Senatorial District" t:state=HI t:expenditure_category="Professional Services" t:vendor_type=OTH t:vendor_name="Pam Smith Consulting" t:reg_no=NC20197 t:city="Ewa Beach" m:amount=47.12

series e:riiu-7d4b d:2010-09-03T00:00:00.000Z t:inoutstate=HI t:election_period=2008-2010 t:independent_expenditure=Expenditure t:zip_code=96804-2300 t:purpose_of_expenditure="Bank Charges" t:noncandidate_committee_name="8th Senatorial District" t:state=HI t:expenditure_category="Bank Charges & Adjustments" t:vendor_type=OTH t:vendor_name="American Savings Bank" t:reg_no=NC20197 t:city=Honolulu m:amount=145

series e:riiu-7d4b d:2010-09-13T00:00:00.000Z t:inoutstate=HI t:election_period=2008-2010 t:independent_expenditure=Expenditure t:zip_code=96824 t:purpose_of_expenditure=Donation t:noncandidate_committee_name="A-1 A-lectrician, Inc." t:state=HI t:expenditure_category="Contribution to Political Party" t:vendor_type=NCC t:vendor_name="Aloha Family Alliance" t:reg_no=NC20001 t:city=Honolulu m:amount=1000
```

## Meta Commands

```ls
metric m:amount p:double l:Amount t:dataTypeName=money

entity e:riiu-7d4b l:"Expenditures Made By Hawaii Noncandidate Committees From January 1, 2008 Through December 31, 2016" t:attribution="State of Hawaii; Campaign Spending Commission" t:url=https://data.hawaii.gov/api/views/riiu-7d4b

property e:riiu-7d4b t:meta.view v:id=riiu-7d4b v:category=Community v:attributionLink=http://www.hawaii.gov/campaign v:averageRating=0 v:name="Expenditures Made By Hawaii Noncandidate Committees From January 1, 2008 Through December 31, 2016" v:attribution="State of Hawaii; Campaign Spending Commission"

property e:riiu-7d4b t:meta.view.owner v:id=g6c2-gabj v:profileImageUrlMedium=/api/users/g6c2-gabj/profile_images/THUMB v:profileImageUrlLarge=/api/users/g6c2-gabj/profile_images/LARGE v:screenName="Hawaii Campaign Spending Commission" v:profileImageUrlSmall=/api/users/g6c2-gabj/profile_images/TINY v:displayName="Hawaii Campaign Spending Commission"

property e:riiu-7d4b t:meta.view.tableauthor v:id=g6c2-gabj v:profileImageUrlMedium=/api/users/g6c2-gabj/profile_images/THUMB v:profileImageUrlLarge=/api/users/g6c2-gabj/profile_images/LARGE v:screenName="Hawaii Campaign Spending Commission" v:profileImageUrlSmall=/api/users/g6c2-gabj/profile_images/TINY v:roleName=editor v:displayName="Hawaii Campaign Spending Commission"
```

## Top Records

```ls
| noncandidate_committee_name | vendor_type | vendor_name                     | date                | amount | expenditure_category            | purpose_of_expenditure            | independent_expenditure | candidate_name_s | support_oppose | address_1                        | address_2         | city        | state | zip_code   | reg_no  | election_period | inoutstate | 
| =========================== | =========== | =============================== | =================== | ====== | =============================== | ================================= | ======================= | ================ | ============== | ================================ | ================= | =========== | ===== | ========== | ======= | =============== | ========== | 
| 8th Senatorial District     | OTH         | Pam Smith Consulting            | 2010-08-10T00:00:00 | 47.12  | Professional Services           | Consulting & Accounting Services  | Expenditure             |                  |                | PO Box 2242                      |                   | Ewa Beach   | HI    | 96706      | NC20197 | 2008-2010       | HI         | 
| 8th Senatorial District     | OTH         | American Savings Bank           | 2010-09-03T00:00:00 | 145    | Bank Charges & Adjustments      | Bank Charges                      | Expenditure             |                  |                | PO Box 2300                      |                   | Honolulu    | HI    | 96804-2300 | NC20197 | 2008-2010       | HI         | 
| A-1 A-lectrician, Inc.      | NCC         | Aloha Family Alliance           | 2010-09-13T00:00:00 | 1000   | Contribution to Political Party | Donation                          | Expenditure             |                  |                | P. O. Box 241043                 |                   | Honolulu    | HI    | 96824      | NC20001 | 2008-2010       | HI         | 
| Abercrombie for Congress    | NCC         | Maui County Democratic Party    | 2009-02-16T00:00:00 | 1000   | Contribution to Political Party | Contribution                      | Expenditure             |                  |                | P O Box 790656                   |                   | Paia        | HI    | 96779      | NC20247 | 2008-2010       | HI         | 
| Abercrombie for Congress    | NPP         | Democratic Party - Kauai County | 2008-11-04T00:00:00 | 1000   | Other                           | Donation                          | Expenditure             |                  |                | P. O. Box 3936                   |                   | Lihue       | HI    | 96766      | NC20002 | 2006-2008       | HI         | 
| Abercrombie for Congress    | NCC         | Patsy T. Mink PAC               | 2008-10-21T00:00:00 | 1000   | Other                           | Contribution                      | Expenditure             |                  |                | P. O. Box 2591                   |                   | Honolulu    | HI    | 96825      | NC20002 | 2006-2008       | HI         | 
| Abercrombie for Congress    | NCC         | Democratic Party - Maui County  | 2008-11-04T00:00:00 | 1000   | Other                           | Donation                          | Expenditure             |                  |                | PO Box 790656                    |                   | Paia        | HI    | 96779      | NC20002 | 2006-2008       | HI         | 
| Abercrombie for Congress    | NCC         | Patsy Mink PAC                  | 2010-10-28T00:00:00 | 1000   | Other                           | Nonfederal political contribution | Expenditure             |                  |                | P. O. Box 25002                  |                   | Honolulu    | HI    | 96825      | NC20247 | 2008-2010       | HI         | 
| Abercrombie for Congress    | CCC         | Friends of Denny Coffman        | 2010-09-14T00:00:00 | 1000   | Other                           | Nonfederal Political Contribution | Expenditure             |                  |                | 77-258 Hookaana Street           |                   | Kailua Kona | HI    | 96740      | NC20247 | 2008-2010       | HI         | 
| Abercrombie for Congress    | CCC         | Friends of Rich Turbin          | 2009-11-18T00:00:00 | 125    | Other                           | Nonfederal Political Contribution | Expenditure             |                  |                | Pacific Guardian Tower, Ste 2730 | 737 Bishop Street | Honolulu    | HI    | 96815      | NC20247 | 2008-2010       | HI         | 
```