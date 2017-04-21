# Durable Assets For Hawaii State and County Candidates From November 8, 2006 Through December 31, 2016

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/durable-assets-for-hawaii-state-and-county-candidates-from-november-8-2006-through-novembe) |
| Metadata | [Link](https://data.hawaii.gov/api/views/fmfj-bac2) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/fmfj-bac2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/fmfj-bac2/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | fmfj-bac2 |
| Name | Durable Assets For Hawaii State and County Candidates From November 8, 2006 Through December 31, 2016 |
| Attribution | State of Hawaii; Campaign Spending Commission |
| Category | Community |
| Tags | campaign spending commission, campaign finance, candidate, hawaii candidates, contributions, political contributions, campaign contributions, campaign spending |
| Created | 2013-02-25T23:43:04Z |
| Publication Date | 2017-03-13T23:59:50Z |

## Columns

```ls
| Included | Schema Type    | Field Name                | Name                      | Data Type     | Render Type   |
| ======== | ============== | ========================= | ========================= | ============= | ============= |
| Yes      | series tag     | candidate_name            | Candidate Name            | text          | text          |
| Yes      | series tag     | vendor_type               | Vendor Type               | text          | text          |
| Yes      | series tag     | vendor_name               | Vendor Name               | text          | text          |
| Yes      | time           | date                      | Date                      | calendar_date | calendar_date |
| Yes      | numeric metric | amount                    | Aquisition Amount         | money         | money         |
| Yes      | series tag     | durable_asset_description | Durable Asset Description | text          | text          |
| Yes      | numeric metric | diposition_amount         | Disposition Amount        | money         | money         |
| Yes      | series tag     | method                    | Method                    | text          | text          |
| Yes      | series tag     | to_whom                   | To Whom                   | text          | text          |
| Yes      | series tag     | durable_asset_id          | Durable Asset ID          | text          | text          |
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
series e:fmfj-bac2 d:2014-08-30T00:00:00.000Z t:office=Governor t:election_period=2012-2014 t:candidate_name="Abercrombie, Neil" t:to_whom="Democratic Party of Hawaii" t:method=Donated t:party=Democrat t:vendor_type=OTH t:vendor_name="Best Buy" t:reg_no=CC10529 t:durable_asset_id=296 m:diposition_amount=0

series e:fmfj-bac2 d:2014-08-30T00:00:00.000Z t:office=Governor t:election_period=2012-2014 t:candidate_name="Abercrombie, Neil" t:to_whom="Craig Ho" t:method=Sold t:party=Democrat t:vendor_type=OTH t:vendor_name="Costco Wholesale" t:reg_no=CC10529 t:durable_asset_id=345 m:diposition_amount=175

series e:fmfj-bac2 d:2014-11-04T00:00:00.000Z t:office=Governor t:election_period=2012-2014 t:candidate_name="Abercrombie, Neil" t:to_whom="Mahinda De Silva" t:method=Sold t:party=Democrat t:vendor_type=OTH t:vendor_name="Costco Wholesale - Iwilei #687" t:reg_no=CC10529 t:durable_asset_id=583 m:diposition_amount=500
```

## Meta Commands

```ls
metric m:amount p:double l:"Aquisition Amount" t:dataTypeName=money

metric m:diposition_amount p:double l:"Disposition Amount" t:dataTypeName=money

entity e:fmfj-bac2 l:"Durable Assets For Hawaii State and County Candidates From November 8, 2006 Through December 31, 2016" t:attribution="State of Hawaii; Campaign Spending Commission" t:url=https://data.hawaii.gov/api/views/fmfj-bac2

property e:fmfj-bac2 t:meta.view v:id=fmfj-bac2 v:category=Community v:attributionLink=http://www.hawaii.gov/campaign v:averageRating=0 v:name="Durable Assets For Hawaii State and County Candidates From November 8, 2006 Through December 31, 2016" v:attribution="State of Hawaii; Campaign Spending Commission"

property e:fmfj-bac2 t:meta.view.owner v:id=g6c2-gabj v:profileImageUrlMedium=/api/users/g6c2-gabj/profile_images/THUMB v:profileImageUrlLarge=/api/users/g6c2-gabj/profile_images/LARGE v:screenName="Hawaii Campaign Spending Commission" v:profileImageUrlSmall=/api/users/g6c2-gabj/profile_images/TINY v:displayName="Hawaii Campaign Spending Commission"

property e:fmfj-bac2 t:meta.view.tableauthor v:id=g6c2-gabj v:profileImageUrlMedium=/api/users/g6c2-gabj/profile_images/THUMB v:profileImageUrlLarge=/api/users/g6c2-gabj/profile_images/LARGE v:screenName="Hawaii Campaign Spending Commission" v:profileImageUrlSmall=/api/users/g6c2-gabj/profile_images/TINY v:roleName=editor v:displayName="Hawaii Campaign Spending Commission"
```

## Top Records

```ls
| candidate_name    | vendor_type | vendor_name                    | date                | amount | durable_asset_description | diposition_amount | method  | to_whom                                         | durable_asset_id | address_1 | address_2 | city | state | zip_code | office       | district | county | party      | reg_no  | election_period | 
| ================= | =========== | ============================== | =================== | ====== | ========================= | ================= | ======= | =============================================== | ================ | ========= | ========= | ==== | ===== | ======== | ============ | ======== | ====== | ========== | ======= | =============== | 
| Abercrombie, Neil | OTH         | Best Buy                       | 2014-08-30T00:00:00 |        |                           | 0                 | Donated | Democratic Party of Hawaii                      | 296              |           |           |      |       |          | Governor     |          |        | Democrat   | CC10529 | 2012-2014       | 
| Abercrombie, Neil | OTH         | Costco Wholesale               | 2014-08-30T00:00:00 |        |                           | 175               | Sold    | Craig Ho                                        | 345              |           |           |      |       |          | Governor     |          |        | Democrat   | CC10529 | 2012-2014       | 
| Abercrombie, Neil | OTH         | Costco Wholesale - Iwilei #687 | 2014-11-04T00:00:00 |        |                           | 500               | Sold    | Mahinda De Silva                                | 583              |           |           |      |       |          | Governor     |          |        | Democrat   | CC10529 | 2012-2014       | 
| Abercrombie, Neil | OTH         | Gabriel Phoenix Communications | 2014-08-30T00:00:00 |        |                           | 75                | Sold    | Anthony Benabese                                | 621              |           |           |      |       |          | Governor     |          |        | Democrat   | CC10529 | 2012-2014       | 
| Abercrombie, Neil | OTH         | Office Depot #570              | 2014-08-30T00:00:00 |        |                           | 75                | Donated | State of Hawaii, Governor Office                | 423              |           |           |      |       |          | Governor     |          |        | Democrat   | CC10529 | 2012-2014       | 
| Abercrombie, Neil | OTH         | Walmart                        | 2014-08-30T00:00:00 |        |                           | 225               | Sold    | Edward Hasegawa,Jim Fernandez, Mahinda De Silva | 620              |           |           |      |       |          | Governor     |          |        | Democrat   | CC10529 | 2012-2014       | 
| Ahu, Elwin        | OTH         | Office Depot                   | 2015-02-25T00:00:00 |        |                           | 732.97            | Donated | Governors Football                              | 611              |           |           |      |       |          | Lt. Governor |          |        | Republican | CC11035 | 2014-2016       | 
| Ahu, Elwin        | OTH         | Office Depot                   | 2015-02-25T00:00:00 |        |                           | 418.84            | Donated | Governors Football                              | 660              |           |           |      |       |          | Lt. Governor |          |        | Republican | CC11035 | 2014-2016       | 
| Aiona, James      | OTH         | Apple Online Store             | 2010-11-10T00:00:00 |        |                           | 200               | Sold    | Jonathan Bolivar                                | 287              |           |           |      |       |          | Governor     |          |        | Republican | CC10162 | 2010-2012       | 
| Aiona, James      | OTH         | Apple Online Store             | 2010-11-17T00:00:00 |        |                           | 200               | Sold    | Travis Taylor                                   | 329              |           |           |      |       |          | Governor     |          |        | Republican | CC10162 | 2010-2012       | 
```