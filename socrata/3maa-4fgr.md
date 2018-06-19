# Expenditures Made By Hawaii State and County Candidates From November 8, 2006 Through December 31, 2016

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/expenditures-made-by-hawaii-state-and-county-candidates-from-november-8-2006-through-novem) |
| Metadata | [Link](https://data.hawaii.gov/api/views/3maa-4fgr) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/3maa-4fgr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/3maa-4fgr/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | 3maa-4fgr |
| Name | Expenditures Made By Hawaii State and County Candidates From November 8, 2006 Through December 31, 2016 |
| Attribution | State of Hawaii; Campaign Spending Commission |
| Category | Community |
| Tags | campaign spending commission, campaign finance, candidate, hawaii candidates, contributions, political contributions, campaign contributions, campaign spending |
| Created | 2013-02-26T17:51:43Z |
| Publication Date | 2017-03-14T02:37:58Z |

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                   | Data Type     | Render Type   |
| ======== | ============== | ====================== | ====================== | ============= | ============= |
| Yes      | series tag     | candidate_name         | Candidate Name         | text          | text          |
| Yes      | series tag     | vendor_type            | Vendor Type            | text          | text          |
| Yes      | series tag     | vendor_name            | Vendor Name            | text          | text          |
| Yes      | time           | date                   | Date                   | calendar_date | calendar_date |
| Yes      | numeric metric | amount                 | Amount                 | money         | money         |
| Yes      | series tag     | authorized_use         | Authorized Use         | text          | text          |
| Yes      | series tag     | expenditure_category   | Expenditure Category   | text          | text          |
| Yes      | series tag     | purpose_of_expenditure | Purpose of Expenditure | text          | text          |
| No       |                | address_1              | Address 1              | text          | text          |
| No       |                | address_2              | Address 2              | text          | text          |
| Yes      | series tag     | city                   | City                   | text          | text          |
| Yes      | series tag     | state                  | State                  | text          | text          |
| Yes      | series tag     | zip_code               | Zip Code               | text          | text          |
| Yes      | series tag     | office                 | Office                 | text          | text          |
| Yes      | series tag     | district               | District               | text          | text          |
| Yes      | series tag     | county                 | County                 | text          | text          |
| Yes      | series tag     | party                  | Party                  | text          | text          |
| Yes      | series tag     | reg_no                 | Reg No                 | text          | text          |
| Yes      | series tag     | election_period        | Election Period        | text          | text          |
| Yes      | series tag     | inoutstate             | InOutState             | text          | text          |
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
series e:3maa-4fgr d:2014-09-23T00:00:00.000Z t:office="Hawaii Council" t:inoutstate=HI t:zip_code=96737 t:candidate_name="Abbett, Richard" t:state=HI t:authorized_use="Directly Related to Candidate's Campaign" t:expenditure_category=Other t:party=Non-Partisan t:reg_no=CC11028 t:city="Ocean View" t:election_period=2012-2014 t:county=Hawaii t:purpose_of_expenditure="Late fee to Campaign Spending Commission" t:district=6 t:vendor_type=CAN t:vendor_name="Abbett, Richard E." m:amount=37.5

series e:3maa-4fgr d:2014-11-03T00:00:00.000Z t:office="Hawaii Council" t:inoutstate=HI t:zip_code=96737 t:candidate_name="Abbett, Richard" t:state=HI t:authorized_use="Directly Related to Candidate's Campaign" t:expenditure_category="Travel & Lodging" t:party=Non-Partisan t:reg_no=CC11028 t:city="Ocean View" t:election_period=2012-2014 t:county=Hawaii t:purpose_of_expenditure="mileage reimbursment" t:district=6 t:vendor_type=CAN t:vendor_name="Abbett, Richard E." m:amount=603.95

series e:3maa-4fgr d:2014-08-10T00:00:00.000Z t:office="Hawaii Council" t:inoutstate=HI t:zip_code=96737 t:candidate_name="Abbett, Richard" t:state=HI t:authorized_use="Political Party Contributions" t:expenditure_category="Contribution to Political Party" t:party=Non-Partisan t:reg_no=CC11028 t:city="Ocean View" t:election_period=2012-2014 t:county=Hawaii t:purpose_of_expenditure="attendance at rally" t:district=6 t:vendor_type=CAN t:vendor_name="Abbett, Richard E." m:amount=50
```

## Meta Commands

```ls
metric m:amount p:double l:Amount t:dataTypeName=money

entity e:3maa-4fgr l:"Expenditures Made By Hawaii State and County Candidates From November 8, 2006 Through December 31, 2016" t:attribution="State of Hawaii; Campaign Spending Commission" t:url=https://data.hawaii.gov/api/views/3maa-4fgr

property e:3maa-4fgr t:meta.view v:id=3maa-4fgr v:category=Community v:attributionLink=http://www.hawaii.gov/campaign v:averageRating=0 v:name="Expenditures Made By Hawaii State and County Candidates From November 8, 2006 Through December 31, 2016" v:attribution="State of Hawaii; Campaign Spending Commission"

property e:3maa-4fgr t:meta.view.owner v:id=g6c2-gabj v:profileImageUrlMedium=/api/users/g6c2-gabj/profile_images/THUMB v:profileImageUrlLarge=/api/users/g6c2-gabj/profile_images/LARGE v:screenName="Hawaii Campaign Spending Commission" v:profileImageUrlSmall=/api/users/g6c2-gabj/profile_images/TINY v:displayName="Hawaii Campaign Spending Commission"

property e:3maa-4fgr t:meta.view.tableauthor v:id=g6c2-gabj v:profileImageUrlMedium=/api/users/g6c2-gabj/profile_images/THUMB v:profileImageUrlLarge=/api/users/g6c2-gabj/profile_images/LARGE v:screenName="Hawaii Campaign Spending Commission" v:profileImageUrlSmall=/api/users/g6c2-gabj/profile_images/TINY v:roleName=editor v:displayName="Hawaii Campaign Spending Commission"
```

## Top Records

```ls
| candidate_name  | vendor_type | vendor_name                | date                | amount | authorized_use                           | expenditure_category            | purpose_of_expenditure                   | address_1                               | address_2 | city        | state | zip_code | office         | district | county | party        | reg_no  | election_period | inoutstate | 
| =============== | =========== | ========================== | =================== | ====== | ======================================== | =============================== | ======================================== | ======================================= | ========= | =========== | ===== | ======== | ============== | ======== | ====== | ============ | ======= | =============== | ========== | 
| Abbett, Richard | CAN         | Abbett, Richard E.         | 2014-09-23T00:00:00 | 37.5   | Directly Related to Candidate's Campaign | Other                           | Late fee to Campaign Spending Commission | PO BOX 6201                             |           | Ocean View  | HI    | 96737    | Hawaii Council | 6        | Hawaii | Non-Partisan | CC11028 | 2012-2014       | HI         | 
| Abbett, Richard | CAN         | Abbett, Richard E.         | 2014-11-03T00:00:00 | 603.95 | Directly Related to Candidate's Campaign | Travel & Lodging                | mileage reimbursment                     | PO BOX 6201                             |           | Ocean View  | HI    | 96737    | Hawaii Council | 6        | Hawaii | Non-Partisan | CC11028 | 2012-2014       | HI         | 
| Abbett, Richard | CAN         | Abbett, Richard E.         | 2014-08-10T00:00:00 | 50     | Political Party Contributions            | Contribution to Political Party | attendance at rally                      | PO BOX 6201                             |           | Ocean View  | HI    | 96737    | Hawaii Council | 6        | Hawaii | Non-Partisan | CC11028 | 2012-2014       | HI         | 
| Abbett, Richard | CAN         | Abbett, Richard E.         | 2014-11-17T00:00:00 | 6.25   | Directly Related to Candidate's Campaign | Travel & Lodging                | mileage reimbursment                     | PO BOX 6201                             |           | Ocean View  | HI    | 96737    | Hawaii Council | 6        | Hawaii | Non-Partisan | CC11028 | 2014-2016       | HI         | 
| Abbett, Richard | CAN         | Abbett, Richard E.         | 2014-09-23T00:00:00 | 93.75  | Directly Related to Candidate's Campaign | Advertising                     | Ka'u Calendar ad                         | PO BOX 6201                             |           | Ocean View  | HI    | 96737    | Hawaii Council | 6        | Hawaii | Non-Partisan | CC11028 | 2012-2014       | HI         | 
| Abbett, Richard | CAN         | Abbett, Richard E.         | 2014-07-30T00:00:00 | 148.99 | Directly Related to Candidate's Campaign | Travel & Lodging                | Mileage 7/01/2014-7/25/2014              | PO BOX 6201                             |           | Ocean View  | HI    | 96737    | Hawaii Council | 6        | Hawaii | Non-Partisan | CC11028 | 2012-2014       | HI         | 
| Abbett, Richard | OTH         | County of Hawaii           | 2014-04-25T00:00:00 | 25     | Directly Related to Candidate's Campaign | Filing Fee                      | Nomination Paper Filing Fee              | 74-5044 Ane Keohokalole Highway, Bldg B |           | Kailua-Kona | HI    | 96740    | Hawaii Council | 6        | Hawaii | Non-Partisan | CC11028 | 2012-2014       | HI         | 
| Abbett, Richard | PP          | Democratic Party of Hawaii | 2014-06-25T00:00:00 | 25     | Directly Related to Candidate's Campaign | Advertising                     | Table at 4th of July Event               | 76-6181 Alii Drive                      |           | Kailua-Kona | HI    | 96740    | Hawaii Council | 6        | Hawaii | Non-Partisan | CC11028 | 2012-2014       | HI         | 
| Cachola, Romy   | OTH         | Chevron                    | 2010-11-08T00:00:00 | 54.2   |                                          | Vehicle                         | GAS                                      | Honolulu                                |           | Honolulu    | HI    | 96813    | House          | 30       |        | Democrat     | CC10137 | 2008-2010       | HI         | 
| Abbett, Richard | IND         | Eno, Jason                 | 2016-11-08T00:00:00 | 90.77  | Directly Related to Candidate's Campaign | Other                           | Reimbursement for campaign expenses      | 470 KALUANUI RD                         |           | Makawao     | HI    | 96768    | House          | 8        |        | Democrat     | CC11314 | 2014-2016       | HI         | 
```