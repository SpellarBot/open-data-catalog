# Contributions Received By Hawaii Noncandidate Committees From January 1, 2008 Through December 31, 2016

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/contributions-received-by-hawaii-noncandidate-committees-from-january-1-2008-through-novem) |
| Metadata | [Link](https://data.hawaii.gov/api/views/rajm-32md) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/rajm-32md/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/rajm-32md/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | rajm-32md |
| Name | Contributions Received By Hawaii Noncandidate Committees From January 1, 2008 Through December 31, 2016 |
| Attribution | State of Hawaii; Campaign Spending Commission |
| Category | Community |
| Tags | campaign spending commission, campaign finance, candidate, hawaii candidates, contributions, political contributions, campaign contributions, campaign spending |
| Created | 2013-02-22T20:35:15Z |
| Publication Date | 2017-03-17T21:49:28Z |

## Columns

```ls
| Included | Schema Type    | Field Name                  | Name                        | Data Type     | Render Type   |
| ======== | ============== | =========================== | =========================== | ============= | ============= |
| Yes      | series tag     | noncandidate_committee_name | Noncandidate Committee Name | text          | text          |
| Yes      | series tag     | contributor_type            | Contributor Type            | text          | text          |
| Yes      | series tag     | contributor_name            | Contributor Name            | text          | text          |
| Yes      | time           | date                        | Date                        | calendar_date | calendar_date |
| Yes      | numeric metric | amount                      | Amount                      | money         | money         |
| Yes      | numeric metric | aggregate                   | Aggregate                   | money         | money         |
| Yes      | series tag     | employer                    | Employer                    | text          | text          |
| Yes      | series tag     | occupation                  | Occupation                  | text          | text          |
| No       |                | address_1                   | Address 1                   | text          | text          |
| No       |                | address_2                   | Address 2                   | text          | text          |
| Yes      | series tag     | city                        | City                        | text          | text          |
| Yes      | series tag     | state                       | State                       | text          | text          |
| Yes      | series tag     | zip_code                    | Zip Code                    | text          | text          |
| Yes      | series tag     | non_monetary_yes_or_no      | Non-Monetary (Yes or No)    | text          | text          |
| Yes      | series tag     | non_monetary_category       | Non-Monetary Category       | text          | text          |
| Yes      | series tag     | non_monetary_description    | Non-Monetary Description    | text          | text          |
| Yes      | series tag     | reg_no                      | Reg No                      | text          | text          |
| Yes      | series tag     | election_period             | Election Period             | text          | text          |
| Yes      | series tag     | inoutstate                  | InOutState                  | text          | text          |
| Yes      | series tag     | range                       | Range                       | text          | text          |
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
series e:rajm-32md d:2014-10-20T00:00:00.000Z t:inoutstate=HI t:occupation="REFRIGERATION FITTER" t:zip_code=96813 t:range=0-1000 t:contributor_type=Individual t:state=HI t:employer="AIR ENGINEERING CO INC" t:contributor_name="KANESHIRO, THEODORE M." t:reg_no=NC20134 t:city=HONOLULU t:election_period=2012-2014 t:noncandidate_committee_name="Plumbers & Pipefitters Political Action Committee" t:non_monetary_yes_or_no=N m:amount=41.88 m:aggregate=311.84

series e:rajm-32md d:2014-10-31T00:00:00.000Z t:inoutstate=HI t:occupation=PLUMBER t:zip_code=96816 t:range=0-1000 t:contributor_type=Individual t:state=HI t:employer="COMMERCIAL PLUMBING, INC." t:contributor_name="KATSUDA, JON I." t:reg_no=NC20134 t:city=HONOLULU t:election_period=2012-2014 t:noncandidate_committee_name="Plumbers & Pipefitters Political Action Committee" t:non_monetary_yes_or_no=N m:amount=18.98 m:aggregate=326.92

series e:rajm-32md d:2013-05-10T13:25:32.000Z t:inoutstate=HI t:election_period=2012-2014 t:range=>1000 t:zip_code=96797 t:contributor_type="Noncandidate Committee" t:noncandidate_committee_name="808 Hits, LLC" t:state=HI t:non_monetary_yes_or_no=N t:contributor_name="808 HITS, LLC" t:reg_no=NC20412 t:city=Waipahu m:amount=2500 m:aggregate=2500
```

## Meta Commands

```ls
metric m:amount p:integer l:Amount t:dataTypeName=money

metric m:aggregate p:double l:Aggregate t:dataTypeName=money

entity e:rajm-32md l:"Contributions Received By Hawaii Noncandidate Committees From January 1, 2008 Through December 31, 2016" t:attribution="State of Hawaii; Campaign Spending Commission" t:url=https://data.hawaii.gov/api/views/rajm-32md

property e:rajm-32md t:meta.view v:id=rajm-32md v:category=Community v:attributionLink=http://www.hawaii.gov/campaign v:averageRating=0 v:name="Contributions Received By Hawaii Noncandidate Committees From January 1, 2008 Through December 31, 2016" v:attribution="State of Hawaii; Campaign Spending Commission"

property e:rajm-32md t:meta.view.license v:name="Public Domain"

property e:rajm-32md t:meta.view.owner v:id=g6c2-gabj v:profileImageUrlMedium=/api/users/g6c2-gabj/profile_images/THUMB v:profileImageUrlLarge=/api/users/g6c2-gabj/profile_images/LARGE v:screenName="Hawaii Campaign Spending Commission" v:profileImageUrlSmall=/api/users/g6c2-gabj/profile_images/TINY v:displayName="Hawaii Campaign Spending Commission"

property e:rajm-32md t:meta.view.tableauthor v:id=g6c2-gabj v:profileImageUrlMedium=/api/users/g6c2-gabj/profile_images/THUMB v:profileImageUrlLarge=/api/users/g6c2-gabj/profile_images/LARGE v:screenName="Hawaii Campaign Spending Commission" v:profileImageUrlSmall=/api/users/g6c2-gabj/profile_images/TINY v:roleName=editor v:displayName="Hawaii Campaign Spending Commission"
```

## Top Records

```ls
| noncandidate_committee_name                       | contributor_type       | contributor_name       | date                | amount | aggregate | employer                    | occupation           | address_1                 | address_2 | city     | state | zip_code | non_monetary_yes_or_no | non_monetary_category | non_monetary_description | reg_no  | election_period | inoutstate | range  | 
| ================================================= | ====================== | ====================== | =================== | ====== | ========= | =========================== | ==================== | ========================= | ========= | ======== | ===== | ======== | ====================== | ===================== | ======================== | ======= | =============== | ========== | ====== | 
| Plumbers & Pipefitters Political Action Committee | Individual             | KANESHIRO, THEODORE M. | 2014-10-20T00:00:00 | 41.88  | 311.84    | AIR ENGINEERING CO INC      | REFRIGERATION FITTER | 430 HOOKUI ST             |           | HONOLULU | HI    | 96813    | N                      |                       |                          | NC20134 | 2012-2014       | HI         | 0-1000 | 
| Plumbers & Pipefitters Political Action Committee | Individual             | KATSUDA, JON I.        | 2014-10-31T00:00:00 | 18.98  | 326.92    | COMMERCIAL PLUMBING, INC.   | PLUMBER              | 2270 POOLEKA STREET       |           | HONOLULU | HI    | 96816    | N                      |                       |                          | NC20134 | 2012-2014       | HI         | 0-1000 | 
| 808 Hits, LLC                                     | Noncandidate Committee | 808 HITS, LLC          | 2013-05-10T13:25:32 | 2500   | 2500      |                             |                      | 94-155 Leoole Street #308 |           | Waipahu  | HI    | 96797    | N                      |                       |                          | NC20412 | 2012-2014       | HI         | >1000  | 
| Plumbers & Pipefitters Political Action Committee | Individual             | WONG, JENSEN M.        | 2015-12-31T00:00:00 | 133.91 | 289.6     | HEIDE & COOK LTD            | REFRIGERATION FITTER | 1955 KINIKOHU ST          |           | WAHIAWA  | HI    | 96786    | N                      |                       |                          | NC20134 | 2014-2016       | HI         | 0-1000 | 
| Plumbers & Pipefitters Political Action Committee | Individual             | BALDAUF, DANIEL J.     | 2012-11-02T00:00:00 | 13.6   | 272.9     | AIR CENTRAL INC.            | REFRIGERATION FITTER | 544 KAIMAKE LOOP          |           | KAILUA   | HI    | 96734    | N                      |                       |                          | NC20134 | 2010-2012       | HI         | 0-1000 | 
| Plumbers & Pipefitters Political Action Committee | Individual             | RODRIGUES, JASON M.    | 2012-11-02T00:00:00 | 12.28  | 252.47    | ALAKA'I MECHANICAL CORP     | REFRIGERATION FITTER | 1224 NANIALII STREET      |           | KAILUA   | HI    | 96734    | N                      |                       |                          | NC20134 | 2010-2012       | HI         | 0-1000 | 
| Plumbers & Pipefitters Political Action Committee | Individual             | KAIPO, ELEOT K.        | 2010-09-03T00:00:00 | 173.76 | 173.76    | OAHU PLUMBING & SHEET METAL | PLUMBER              | 103 PUHILI STREET         |           | HILO     | HI    | 96720    | N                      |                       |                          | NC20134 | 2008-2010       | HI         | 0-1000 | 
| Plumbers & Pipefitters Political Action Committee | Individual             | RIVERA, MICHAEL K.     | 2010-09-03T00:00:00 | 148.56 | 148.56    | BISCAYNE AQUACULTURE, INC.  | REFRIGERATION FITTER | 4357 LIKINI STREET        |           | HONOLULU | HI    | 96818    | N                      |                       |                          | NC20134 | 2008-2010       | HI         | 0-1000 | 
| Plumbers & Pipefitters Political Action Committee | Individual             | WONG, JENSEN M.        | 2014-10-20T00:00:00 | 45.57  | 306.41    | HEIDE & COOK LTD            | REFRIGERATION FITTER | 1955 KINIKOHU ST          |           | WAHIAWA  | HI    | 96786    | N                      |                       |                          | NC20134 | 2012-2014       | HI         | 0-1000 | 
| Plumbers & Pipefitters Political Action Committee | Individual             | YOUNG, DAVID K.        | 2010-09-03T00:00:00 | 212.31 | 212.31    | REGENT PLUMBING INC         | PLUMBER              | 4621 FARMERS ROAD         |           | HONOLULU | HI    | 96816    | N                      |                       |                          | NC20134 | 2008-2010       | HI         | 0-1000 | 
```