# Fundraiser Notices Filed By Hawaii Noncandidate Committees

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/fundraiser-notices-filed-by-hawaii-noncandidate-committees-66eb3) |
| Metadata | [Link](https://data.hawaii.gov/api/views/448v-cbnq) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/448v-cbnq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/448v-cbnq/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | 448v-cbnq |
| Name | Fundraiser Notices Filed By Hawaii Noncandidate Committees |
| Attribution | Campaign Spending Commission |
| Category | Community |
| Created | 2014-02-11T19:20:48Z |
| Publication Date | 2017-01-05T02:50:56Z |

## Columns

```ls
| Included | Schema Type    | Field Name                                              | Name                                                       | Data Type     | Render Type   |
| ======== | ============== | ======================================================= | ========================================================== | ============= | ============= |
| Yes      | series tag     | noncandidate_committee_name                             | Noncandidate Committee Name                                | text          | text          |
| Yes      | series tag     | person_in_charge                                        | Person in Charge                                           | text          | text          |
| No       |                | address_1                                               | Address 1                                                  | text          | text          |
| No       |                | address_2                                               | Address 2                                                  | text          | text          |
| Yes      | series tag     | city                                                    | City                                                       | text          | text          |
| Yes      | series tag     | state                                                   | State                                                      | text          | text          |
| Yes      | series tag     | zip_code                                                | Zip Code                                                   | text          | text          |
| Yes      | time           | fundraiser_date                                         | Fundraiser Date                                            | calendar_date | calendar_date |
| No       |                | hour_time                                               | Hour (Time)                                                | text          | text          |
| Yes      | series tag     | place_of_fundraiser                                     | Place of Fundraiser                                        | text          | text          |
| No       |                | fundraiser_address_1                                    | Fundraiser Address 1                                       | text          | text          |
| No       |                | fundraiser_address_2                                    | Fundraiser Address 2                                       | text          | text          |
| Yes      | series tag     | fundraiser_city                                         | Fundraiser City                                            | text          | text          |
| Yes      | series tag     | fundraiser_state                                        | Fundraiser State                                           | text          | text          |
| Yes      | series tag     | fundraiser_zip_code                                     | Fundraiser Zip Code                                        | text          | text          |
| Yes      | numeric metric | price_or_suggested_contribution_range                   | Price or Suggested Contribution (Range)                    | money         | text          |
| Yes      | numeric metric | price_or_suggested_contribution_max_range_if_applicable | Price or Suggested Contribution (Max Range, if applicable) | money         | money         |
| Yes      | series tag     | reg_no                                                  | Reg No                                                     | text          | text          |
| Yes      | series tag     | election_period                                         | Election Period                                            | text          | text          |
| No       |                | fundraiser_date_text                                    | Fundraiser Date (text)                                     | text          | text          |
```

## Time Field

```ls
Value = fundraiser_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = address_1,address_2,hour_time,fundraiser_address_1,fundraiser_address_2,fundraiser_date_text
```

## Data Commands

```ls
series e:448v-cbnq d:2012-12-11T00:00:00.000Z t:person_in_charge="White, Carol" t:election_period=2012-2014 t:zip_code=96813 t:fundraiser_zip_code=96814 t:place_of_fundraiser="Dave and Busters" t:noncandidate_committee_name="Hawaii Republicans for Life" t:state=HI t:fundraiser_city=Honolulu t:reg_no=NC20304 t:fundraiser_state=HI t:city=Honolulu m:price_or_suggested_contribution_range=25 m:price_or_suggested_contribution_max_range_if_applicable=30

series e:448v-cbnq d:2013-10-14T00:00:00.000Z t:person_in_charge="Monk, Amy" t:election_period=2012-2014 t:zip_code=96825 t:fundraiser_zip_code=96817 t:place_of_fundraiser="Lemongrass Caf?" t:noncandidate_committee_name="Patsy T. Mink PAC" t:state=HI t:fundraiser_city=Honolulu t:reg_no=NC20132 t:fundraiser_state=HI t:city=Honolulu m:price_or_suggested_contribution_max_range_if_applicable=100

series e:448v-cbnq d:2014-01-30T00:00:00.000Z t:person_in_charge="Parsons, Blake" t:election_period=2012-2014 t:zip_code=96813 t:fundraiser_zip_code=96816 t:place_of_fundraiser="Waialae Country Club" t:noncandidate_committee_name="Hawaii Republican Party" t:state=HI t:fundraiser_city=Honolulu t:reg_no=NC20069 t:fundraiser_state=HI t:city=Honolulu m:price_or_suggested_contribution_max_range_if_applicable=175
```

## Meta Commands

```ls
metric m:price_or_suggested_contribution_range p:long l:"Price or Suggested Contribution (Range)" t:dataTypeName=money

metric m:price_or_suggested_contribution_max_range_if_applicable p:double l:"Price or Suggested Contribution (Max Range, if applicable)" t:dataTypeName=money

entity e:448v-cbnq l:"Fundraiser Notices Filed By Hawaii Noncandidate Committees" t:attribution="Campaign Spending Commission" t:url=https://data.hawaii.gov/api/views/448v-cbnq

property e:448v-cbnq t:meta.view v:id=448v-cbnq v:category=Community v:averageRating=0 v:name="Fundraiser Notices Filed By Hawaii Noncandidate Committees" v:attribution="Campaign Spending Commission"

property e:448v-cbnq t:meta.view.owner v:id=g6c2-gabj v:profileImageUrlMedium=/api/users/g6c2-gabj/profile_images/THUMB v:profileImageUrlLarge=/api/users/g6c2-gabj/profile_images/LARGE v:screenName="Hawaii Campaign Spending Commission" v:profileImageUrlSmall=/api/users/g6c2-gabj/profile_images/TINY v:displayName="Hawaii Campaign Spending Commission"

property e:448v-cbnq t:meta.view.tableauthor v:id=g6c2-gabj v:profileImageUrlMedium=/api/users/g6c2-gabj/profile_images/THUMB v:profileImageUrlLarge=/api/users/g6c2-gabj/profile_images/LARGE v:screenName="Hawaii Campaign Spending Commission" v:profileImageUrlSmall=/api/users/g6c2-gabj/profile_images/TINY v:roleName=editor v:displayName="Hawaii Campaign Spending Commission"
```

## Top Records

```ls
| noncandidate_committee_name | person_in_charge   | address_1                | address_2 | city      | state | zip_code | fundraiser_date     | hour_time           | place_of_fundraiser                                | fundraiser_address_1      | fundraiser_address_2 | fundraiser_city | fundraiser_state | fundraiser_zip_code | price_or_suggested_contribution_range | price_or_suggested_contribution_max_range_if_applicable | reg_no  | election_period | fundraiser_date_text | 
| =========================== | ================== | ======================== | ========= | ========= | ===== | ======== | =================== | =================== | ================================================== | ========================= | ==================== | =============== | ================ | =================== | ===================================== | ======================================================= | ======= | =============== | ==================== | 
| Hawaii Republicans for Life | White, Carol       | 1516 Emerson Street      | #102      | Honolulu  | HI    | 96813    | 2012-12-11T00:00:00 | 11:15 am            | Dave and Busters                                   | 1030 Auahi Street         |                      | Honolulu        | HI               | 96814               | $25/$30                               | 30.00                                                   | NC20304 | 2012-2014       | 12/11/12             | 
| Patsy T. Mink PAC           | Monk, Amy          | 7476 Kekaa Street        |           | Honolulu  | HI    | 96825    | 2013-10-14T00:00:00 | 5:00 pm to 7:00 pm  | Lemongrass Caf?                                    | 83 N. King Street         |                      | Honolulu        | HI               | 96817               |                                       | 100.00                                                  | NC20132 | 2012-2014       | 10/14/13             | 
| Hawaii Republican Party     | Parsons, Blake     | 725 Kapiolani Blvd.      | #C-105    | Honolulu  | HI    | 96813    | 2014-01-30T00:00:00 | 6:00 pm to 9:00 pm  | Waialae Country Club                               | 4997 Kahala Avenue        |                      | Honolulu        | HI               | 96816               |                                       | 175.00                                                  | NC20069 | 2012-2014       | 1/30/14              | 
| Hawaii Republican Assembly  | Palcic, Michael G. | P.O. Box 2805            |           | Honolulu  | HI    | 96803    | 2013-07-19T00:00:00 | 11:30 am            | Waialae Country Club                               | 4997 Kahala Avenue        |                      | Honolulu        | HI               | 96816               |                                       | 50.00                                                   | NC20248 | 2012-2014       | 7/19/13              | 
| Democratic Party of Hawaii  | Sugimura, Jane     | 404 Ward Avenue          | Suite 200 | Honolulu  | HI    | 96814    | 2013-08-18T00:00:00 | 4:30 pm to 7:30 pm  | Ward Warehouse - Kakaako & Kewalo Conference Rooms | 1050 Ala Moana Blvd.      |                      | Honolulu        | HI               | 96814               |                                       | 50.00                                                   | NC20037 | 2012-2014       | 8/18/13              | 
| Hawaii Republican Party     | Blom, Nacia Lee    | 725 Kapiolani Blvd.      | #C-105    | Honolulu  | HI    | 96813    | 2013-04-16T00:00:00 | 5:30 pm             | Ko'olau Ballrooms & Conference Center              | 45-550 Kionaole Road      |                      | Kaneohe         | HI               | 96744               | $150-$25,000                          | 25000.00                                                | NC20069 | 2012-2014       | 4/16/13              | 
| Hawaii Republicans for Life | White, Carol       | 1516 Emerson Street      | #102      | Honolulu  | HI    | 96813    | 2013-01-15T00:00:00 | 11:15 am            | Dave and Busters                                   | 1030 Auahi Street         |                      | Honolulu        | HI               | 96814               | $25/$30                               | 30.00                                                   | NC20304 | 2012-2014       | 1/15/13              | 
| HIRA Action                 | Kulbis, Brett      | 91-1010 Kaipalaoa Street |           | Ewa Beach | HI    | 96706    | 2014-01-23T00:00:00 | 5:00 pm to 8:00 pm  | Waialae Country Club                               | 4997 Kahala Avenue        |                      | Honolulu        | HI               | 96816               | $30/$25,000                           | 25000.00                                                | NC20392 | 2012-2014       | 1/23/14              | 
| HIRA Action                 | Kulbis, Brett      | 91-1010 Kaipalaoa Street |           | Ewa Beach | HI    | 96706    | 2014-02-06T00:00:00 | 6:00 pm to 10:00 pm | Pearl Country Club                                 | 98-535 Kaonohi Street     |                      | Aiea            | HI               | 96701               | $75/$25,000                           | 25000.00                                                | NC20392 | 2012-2014       | 2/6/14               | 
| Democratic Party of Hawaii  | Hashimoto, Troy    | 1280 Pulehuiki Road      |           | Kula      | HI    | 96790    | 2014-05-03T00:00:00 | 5:30 pm             | Puu Kukui Elementary School                        | 3700 Kehalani Mauka Pkwy. |                      | Wailuku         | HI               | 96793               |                                       | 35                                                      | NC20037 | 2012-2014       | 5/3/14               | 
```