# Chicago Southland Foreclosures

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/chicago-southland-foreclosures-3bdb3) |
| Metadata | [Link](https://data.illinois.gov/api/views/udcv-aqsu) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/udcv-aqsu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/udcv-aqsu/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | udcv-aqsu |
| Name | Chicago Southland Foreclosures |
| Attribution | Michael Rizzitiello |
| Category | Municipality |
| Tags | ssmma, chicago southland, housing, planning, foreclosures |
| Created | 2012-12-04T20:43:26Z |
| Publication Date | 2012-12-04T20:48:05Z |

## Columns

```ls
| Included | Schema Type    | Field Name                     | Name                           | Data Type     | Render Type   |
| ======== | ============== | ============================== | ============================== | ============= | ============= |
| Yes      | time           | input_date                     | Input Date                     | calendar_date | calendar_date |
| Yes      | series tag     | real_estate_auction            | Real Estate Auction            | text          | text          |
| No       |                | date_of_sale                   | Date of Sale                   | calendar_date | calendar_date |
| Yes      | series tag     | place_of_sale                  | Place of Sale                  | text          | text          |
| No       |                | time_of_sale                   | Time of Sale                   | number        | number        |
| Yes      | series tag     | case_number                    | Case Number                    | text          | text          |
| Yes      | series tag     | type_of_sale                   | Type of Sale                   | text          | text          |
| Yes      | series tag     | company_name                   | Company Name                   | text          | text          |
| Yes      | series tag     | company_phone_number           | Company Phone Number           | text          | text          |
| Yes      | series tag     | county                         | County                         | text          | text          |
| Yes      | series tag     | property_type                  | Property Type                  | text          | text          |
| Yes      | series tag     | plantiff                       | Plantiff                       | text          | text          |
| Yes      | series tag     | plantiff_law_firm              | Plantiff Law Firm              | text          | text          |
| No       |                | plantiff_law_firm_address      | Plantiff Law Firm Address      | text          | text          |
| Yes      | series tag     | plantiff_law_firm_city         | Plantiff Law Firm City         | text          | text          |
| Yes      | series tag     | plantiff_law_firm_state        | Plantiff Law Firm State        | text          | text          |
| Yes      | series tag     | plantiff_law_firm_zip_code     | Plantiff Law Firm Zip Code     | text          | text          |
| Yes      | series tag     | plantiff_law_firm_phone_number | Plantiff Law Firm Phone Number | text          | number        |
| Yes      | series tag     | defendant_first_name           | Defendant First Name           | text          | text          |
| Yes      | series tag     | defendant_last_name            | Defendant Last Name            | text          | text          |
| No       |                | defendant_address              | Defendant Address              | text          | text          |
| Yes      | series tag     | defendant_city                 | Defendant City                 | text          | text          |
| Yes      | series tag     | defendant_state                | Defendant State                | text          | text          |
| Yes      | series tag     | defendant_zip_code             | Defendant Zip Code             | text          | text          |
| Yes      | series tag     | defendant_phone_number         | Defendant Phone Number         | text          | number        |
| Yes      | numeric metric | recording_date_forecloser      | Recording Date Forecloser      | number        | number        |
| Yes      | numeric metric | complaint_judgement_amount     | Complaint/Judgement Amount     | number        | number        |
| Yes      | series tag     | pin_number                     | Pin Number                     | text          | text          |
| Yes      | series tag     | lienholder_1                   | Lienholder 1                   | text          | text          |
| Yes      | series tag     | lienholder_2                   | Lienholder 2                   | text          | text          |
| Yes      | series tag     | lienholder_3                   | Lienholder 3                   | text          | text          |
| Yes      | series tag     | lienholder_4                   | Lienholder 4                   | text          | text          |
| Yes      | numeric metric | original_mortgage_amount       | Original Mortgage Amount       | number        | number        |
| No       |                | original_mortgage_date         | Original Mortgage Date         | calendar_date | calendar_date |
| Yes      | series tag     | type_of_mortgage               | Type of Mortgage               | text          | text          |
| Yes      | numeric metric | term_of_mortgage               | Term of Mortgage               | number        | number        |
| Yes      | numeric metric | interest_rate                  | Interest Rate                  | number        | number        |
| Yes      | series tag     | document_number                | Document Number                | text          | number        |
| Yes      | numeric metric | perdiem_rate                   | Perdiem Rate                   | number        | number        |
| Yes      | numeric metric | date_of_calculation            | Date of Calculation            | number        | number        |
| Yes      | series tag     | notes                          | Notes                          | text          | text          |
| Yes      | series tag     | defendant_first_name_2         | Defendant First Name #2        | text          | text          |
| Yes      | series tag     | defendant_last_name_2          | Defendant Last Name #2         | text          | text          |
| Yes      | series tag     | do_not_call                    | Do Not Call                    | text          | text          |
| No       |                | dnc_date                       | DNC Date                       | text          | text          |
| Yes      | series tag     | re_seller_last_name            | RE Seller Last Name            | text          | text          |
| Yes      | series tag     | re_seller_first_name           | RE Seller First Name           | text          | text          |
| Yes      | numeric metric | re_ltv                         | RE LTV                         | number        | text          |
| Yes      | numeric metric | re_percent_down                | RE Percent Down                | number        | text          |
| Yes      | numeric metric | re_down_payment                | RE Down Payment                | number        | text          |
| Yes      | series tag     | re_buyer_lname1                | RE Buyer LName1                | text          | text          |
| Yes      | series tag     | re_buyer_fname1                | RE Buyer FName1                | text          | text          |
| Yes      | series tag     | re_buyer_lname2                | RE Buyer LName2                | text          | text          |
| Yes      | series tag     | re_buyer_fname2                | RE Buyer FName2                | text          | text          |
| Yes      | numeric metric | re_deeddate                    | Re DeedDate                    | number        | number        |
| No       |                | taxbilladdress                 | TaxBillAddress                 | text          | text          |
| Yes      | series tag     | taxbillcity                    | TaxBillCity                    | text          | text          |
| Yes      | numeric metric | re_purchase_price              | RE Purchase Price              | number        | number        |
| Yes      | series tag     | record_number                  | Record Number                  | text          | number        |
| Yes      | series tag     | bankruptcy                     | Bankruptcy                     | text          | text          |
| Yes      | numeric metric | sold_amount                    | Sold Amount                    | number        | text          |
| Yes      | series tag     | sold_to                        | Sold To                        | text          | text          |
| Yes      | series tag     | sale_results                   | Sale Results                   | text          | text          |
| Yes      | series tag     | community                      | Community                      | text          | text          |
| No       |                | original_sale_date             | Original Sale Date             | calendar_date | calendar_date |
| Yes      | series tag     | race                           | Race                           | text          | text          |
| Yes      | series tag     | zip_web                        | Zip Web                        | text          | number        |
| Yes      | series tag     | aldermanic_dst                 | Aldermanic Dst                 | text          | text          |
| Yes      | numeric metric | census_age                     | Census Age                     | number        | number        |
| Yes      | numeric metric | census_avg_income              | Census Avg Income              | number        | number        |
| No       |                | x                              | X                              | number        | number        |
| No       |                | y                              | Y                              | number        | number        |
| Yes      | series tag     | neighborhood                   | Neighborhood                   | text          | text          |
| Yes      | series tag     | taxbillstate                   | TaxBillState                   | text          | text          |
| Yes      | series tag     | taxbillzip                     | TaxBillZip                     | text          | text          |
| Yes      | numeric metric | census_tract                   | Census_Tract                   | number        | number        |
```

## Time Field

```ls
Value = input_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = date_of_sale,time_of_sale,plantiff_law_firm_address,defendant_address,original_mortgage_date,dnc_date,taxbilladdress,original_sale_date,x,y
```

## Data Commands

```ls
series e:udcv-aqsu d:2010-12-01T00:00:00.000Z t:type_of_sale="NEWLY FILED FORECLOSURE" t:defendant_first_name=OSCAR t:zip_web=60426 t:race=Hispanic t:plantiff_law_firm_city=CHICAGO t:real_estate_auction=NO t:defendant_last_name_2="HERNANDEZ GUTIERREZ" t:document_number=319926155 t:defendant_city=HARVEY t:defendant_first_name_2=MARIA t:type_of_mortgage=CONVENTIONAL t:pin_number="29 20 204 013 0000" t:defendant_state=IL t:defendant_last_name=PEREZ t:defendant_zip_code=60426-5210 t:record_number=453504849 t:plantiff_law_firm_phone_number=3124765500 t:case_number=10CH0046807 t:plantiff_law_firm_state=IL t:plantiff_law_firm_zip_code=60602 t:defendant_phone_number=7085964659 t:property_type="VACANT RESIDENTIAL" t:plantiff="PNC BANK" t:county=COOK t:plantiff_law_firm="PIERCE & ASSOCIATES" t:notes="ADDL PIN 29-20-204-014-0000" m:complaint_judgement_amount=47603 m:census_avg_income=37038 m:census_age=29 m:perdiem_rate=701 m:date_of_calculation=60110 m:original_mortgage_amount=82000 m:census_tract=827500 m:interest_rate=537 m:term_of_mortgage=15 m:recording_date_forecloser=102810

series e:udcv-aqsu d:2010-12-02T00:00:00.000Z t:type_of_sale="INTERCOUNTY SALES" t:defendant_first_name="JOHN A" t:zip_web=60426 t:race=Other t:plantiff_law_firm_city=CHICAGO t:real_estate_auction=YES t:defendant_last_name_2=DURR t:document_number=10598054 t:defendant_city=HARVEY t:company_name="INTERCOUNTY JUDICIAL SALES CORP" t:defendant_first_name_2="ERICA M" t:type_of_mortgage=CONVENTIONAL t:pin_number="29 08 302 030 0000" t:defendant_state=IL t:defendant_last_name="DURR JR" t:defendant_zip_code=60426-1710 t:record_number=453497259 t:plantiff_law_firm_phone_number=3123609455 t:case_number=10CH0017257 t:company_phone_number=3124441122 t:plantiff_law_firm_state=IL t:plantiff_law_firm_zip_code=60603 t:sale_results=RESCHEDULED t:property_type="SINGLE FAMILY RESIDENCE" t:plantiff="US BANK NA TRUSTEE" t:county=COOK t:lienholder_1="TERRENCE E FIELDS 0833111031 3050" t:plantiff_law_firm="WIRBICKI LAW GROUP" t:place_of_sale="120 W MADISON ST STE 718A CHICAGO 60602" m:complaint_judgement_amount=51794 m:census_avg_income=35608 m:census_age=27 m:perdiem_rate=1568 m:date_of_calculation=90109 m:original_mortgage_amount=52270 m:census_tract=827100 m:interest_rate=1090 m:term_of_mortgage=30 m:recording_date_forecloser=42110

series e:udcv-aqsu d:2010-12-02T00:00:00.000Z t:type_of_sale="NEWLY FILED FORECLOSURE" t:defendant_first_name=ALEXIS t:zip_web=60426 t:race=Other t:plantiff_law_firm_city=CHICAGO t:real_estate_auction=NO t:defendant_last_name_2=ATKINS t:document_number=526202322 t:defendant_city=HARVEY t:defendant_first_name_2="WILLIAM L" t:type_of_mortgage=ARM t:pin_number="29 19 212 039 0000" t:defendant_state=IL t:defendant_last_name=ATKINS t:defendant_zip_code=60426-4913 t:record_number=453505029 t:plantiff_law_firm_phone_number=3125419710 t:case_number=10CH0046925 t:plantiff_law_firm_state=IL t:plantiff_law_firm_zip_code=60606 t:property_type="SINGLE FAMILY RESIDENCE" t:plantiff="HSBC MORTGAGE SERVICES INC" t:county=COOK t:bankruptcy="09112002 - Chapter 7" t:plantiff_law_firm="JOHNSON BLUMBERG & ASSOCIATES LLC" m:complaint_judgement_amount=91004 m:census_avg_income=37038 m:census_age=36 m:perdiem_rate=1918 m:date_of_calculation=100109 m:original_mortgage_amount=96000 m:census_tract=827500 m:interest_rate=770 m:term_of_mortgage=30 m:recording_date_forecloser=102910
```

## Meta Commands

```ls
metric m:recording_date_forecloser p:integer l:"Recording Date Forecloser" t:dataTypeName=number

metric m:complaint_judgement_amount p:integer l:"Complaint/Judgement Amount" t:dataTypeName=number

metric m:original_mortgage_amount p:integer l:"Original Mortgage Amount" t:dataTypeName=number

metric m:term_of_mortgage p:integer l:"Term of Mortgage" t:dataTypeName=number

metric m:interest_rate p:integer l:"Interest Rate" t:dataTypeName=number

metric m:perdiem_rate p:integer l:"Perdiem Rate" t:dataTypeName=number

metric m:date_of_calculation p:integer l:"Date of Calculation" t:dataTypeName=number

metric m:re_ltv p:integer l:"RE LTV" t:dataTypeName=number

metric m:re_percent_down p:integer l:"RE Percent Down" t:dataTypeName=number

metric m:re_down_payment p:integer l:"RE Down Payment" t:dataTypeName=number

metric m:re_deeddate p:integer l:"Re DeedDate" t:dataTypeName=number

metric m:re_purchase_price p:integer l:"RE Purchase Price" t:dataTypeName=number

metric m:sold_amount p:integer l:"Sold Amount" t:dataTypeName=number

metric m:census_age p:integer l:"Census Age" t:dataTypeName=number

metric m:census_avg_income p:integer l:"Census Avg Income" t:dataTypeName=number

metric m:census_tract p:integer l:Census_Tract t:dataTypeName=number

entity e:udcv-aqsu l:"Chicago Southland Foreclosures" t:attribution="Michael Rizzitiello" t:url=https://data.illinois.gov/api/views/udcv-aqsu

property e:udcv-aqsu t:meta.view v:id=udcv-aqsu v:category=Municipality v:attributionLink=http://www.ssmma.org v:averageRating=0 v:name="Chicago Southland Foreclosures" v:attribution="Michael Rizzitiello"

property e:udcv-aqsu t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:udcv-aqsu t:meta.view.owner v:id=ykrz-5bsi v:profileImageUrlMedium=/api/users/ykrz-5bsi/profile_images/THUMB v:profileImageUrlLarge=/api/users/ykrz-5bsi/profile_images/LARGE v:screenName="Michael Rizzitiello" v:profileImageUrlSmall=/api/users/ykrz-5bsi/profile_images/TINY v:displayName="Michael Rizzitiello"

property e:udcv-aqsu t:meta.view.tableauthor v:id=ykrz-5bsi v:profileImageUrlMedium=/api/users/ykrz-5bsi/profile_images/THUMB v:profileImageUrlLarge=/api/users/ykrz-5bsi/profile_images/LARGE v:screenName="Michael Rizzitiello" v:profileImageUrlSmall=/api/users/ykrz-5bsi/profile_images/TINY v:displayName="Michael Rizzitiello"
```

## Top Records

```ls
| input_date          | real_estate_auction | date_of_sale        | place_of_sale                           | time_of_sale | case_number | type_of_sale            | company_name                    | company_phone_number | county | property_type           | plantiff                   | plantiff_law_firm                     | plantiff_law_firm_address    | plantiff_law_firm_city | plantiff_law_firm_state | plantiff_law_firm_zip_code | plantiff_law_firm_phone_number | defendant_first_name | defendant_last_name | defendant_address    | defendant_city | defendant_state | defendant_zip_code | defendant_phone_number | recording_date_forecloser | complaint_judgement_amount | pin_number         | lienholder_1                                            | lienholder_2 | lienholder_3 | lienholder_4 | original_mortgage_amount | original_mortgage_date | type_of_mortgage | term_of_mortgage | interest_rate | document_number | perdiem_rate | date_of_calculation | notes                       | defendant_first_name_2 | defendant_last_name_2 | do_not_call | dnc_date | re_seller_last_name | re_seller_first_name | re_ltv | re_percent_down | re_down_payment | re_buyer_lname1 | re_buyer_fname1 | re_buyer_lname2 | re_buyer_fname2 | re_deeddate | taxbilladdress | taxbillcity | re_purchase_price | record_number | bankruptcy             | sold_amount | sold_to | sale_results | community | original_sale_date  | race     | zip_web | aldermanic_dst | census_age | census_avg_income | x              | y             | neighborhood | taxbillstate | taxbillzip | census_tract | 
| =================== | =================== | =================== | ======================================= | ============ | =========== | ======================= | =============================== | ==================== | ====== | ======================= | ========================== | ===================================== | ============================ | ====================== | ======================= | ========================== | ============================== | ==================== | =================== | ==================== | ============== | =============== | ================== | ====================== | ========================= | ========================== | ================== | ======================================================= | ============ | ============ | ============ | ======================== | ====================== | ================ | ================ | ============= | =============== | ============ | =================== | =========================== | ====================== | ===================== | =========== | ======== | =================== | ==================== | ====== | =============== | =============== | =============== | =============== | =============== | =============== | =========== | ============== | =========== | ================= | ============= | ====================== | =========== | ======= | ============ | ========= | =================== | ======== | ======= | ============== | ========== | ================= | ============== | ============= | ============ | ============ | ========== | ============ | 
| 2010-12-01T00:00:00 | NO                  |                     |                                         |              | 10CH0046807 | NEWLY FILED FORECLOSURE |                                 |                      | COOK   | VACANT RESIDENTIAL      | PNC BANK                   | PIERCE & ASSOCIATES                   | 1 N DEARBORN ST STE 1300     | CHICAGO                | IL                      | 60602                      | 3124765500                     | OSCAR                | PEREZ               | 15921 CARSE AVE      | HARVEY         | IL              | 60426-5210         | 7085964659             | 102810                    | 47603                      | 29 20 204 013 0000 |                                                         |              |              |              | 82000                    | 2003-05-13T00:00:00    | CONVENTIONAL     | 15               | 537           | 319926155       | 701          | 60110               | ADDL PIN 29-20-204-014-0000 | MARIA                  | HERNANDEZ GUTIERREZ   |             |          |                     |                      |        |                 |                 |                 |                 |                 |                 |             |                |             |                   | 453504849     |                        |             |         |              |           |                     | Hispanic | 60426   |                | 29         | 37038             | -87.6388226726 | 41.6004588173 |              |              |            | 827500       | 
| 2010-12-02T00:00:00 | YES                 | 2011-01-13T00:00:00 | 120 W MADISON ST STE 718A CHICAGO 60602 | 1100         | 10CH0017257 | INTERCOUNTY SALES       | INTERCOUNTY JUDICIAL SALES CORP | 3124441122           | COOK   | SINGLE FAMILY RESIDENCE | US BANK NA TRUSTEE         | WIRBICKI LAW GROUP                    | 33 W MONROE ST STE 1140      | CHICAGO                | IL                      | 60603                      | 3123609455                     | JOHN A               | DURR JR             | 14720 LOOMIS AVE     | HARVEY         | IL              | 60426-1710         |                        | 42110                     | 51794                      | 29 08 302 030 0000 | TERRENCE E FIELDS 0833111031 3050                       |              |              |              | 52270                    | 2000-06-28T00:00:00    | CONVENTIONAL     | 30               | 1090          | 10598054        | 1568         | 90109               |                             | ERICA M                | DURR                  |             |          |                     |                      |        |                 |                 |                 |                 |                 |                 |             |                |             |                   | 453497259     |                        |             |         | RESCHEDULED  |           | 2010-12-02T00:00:00 | Other    | 60426   |                | 27         | 35608             | -87.6510800049 | 41.6221527169 |              |              |            | 827100       | 
| 2010-12-02T00:00:00 | NO                  |                     |                                         |              | 10CH0046925 | NEWLY FILED FORECLOSURE |                                 |                      | COOK   | SINGLE FAMILY RESIDENCE | HSBC MORTGAGE SERVICES INC | JOHNSON BLUMBERG & ASSOCIATES LLC     | 230 W MONROE ST STE 1125     | CHICAGO                | IL                      | 60606                      | 3125419710                     | ALEXIS               | ATKINS              | 16024 ASHLAND AVE    | HARVEY         | IL              | 60426-4913         |                        | 102910                    | 91004                      | 29 19 212 039 0000 |                                                         |              |              |              | 96000                    | 2005-09-06T00:00:00    | ARM              | 30               | 770           | 526202322       | 1918         | 100109              |                             | WILLIAM L              | ATKINS                |             |          |                     |                      |        |                 |                 |                 |                 |                 |                 |             |                |             |                   | 453505029     | 09112002 - Chapter 7   |             |         |              |           |                     | Other    | 60426   |                | 36         | 37038             | -87.6558707778 | 41.5985177723 |              |              |            | 827500       | 
| 2010-12-03T00:00:00 | YES                 | 2011-01-03T00:00:00 | 1 S WACKER DR STE 2400 CHICAGO 60606    | 1030         | 10CH0017065 | JUDICIAL SALES CORP     | JUDICIAL SALES CORP             | 312236SALE           | COOK   | SINGLE FAMILY RESIDENCE | JP MORGAN CHASE BANK       | CODILIS & ASSOCIATES PC               | 15W030 N FRONTAGE RD STE 100 | BURR RIDGE             | IL                      | 60527-6921                 | 6307945300                     | MATTHEW              | BRASHINGER III      | 15716 PARK AVE       | HARVEY         | IL              | 60426-4337         |                        | 41910                     | 58354                      | 29 17 317 021 0000 |                                                         |              |              |              | 63000                    | 2003-08-19T00:00:00    | CONVENTIONAL     | 30               | 725           | 326835037       |              | 10110               |                             |                        |                       |             |          |                     |                      |        |                 |                 |                 |                 |                 |                 |             |                |             |                   | 453497894     |                        |             |         | RESCHEDULED  |           | 2010-12-03T00:00:00 | Other    | 60426   |                | 0          | 37038             | -87.646333521  | 41.6040890898 |              |              |            | 827500       | 
| 2010-12-03T00:00:00 | NO                  |                     |                                         |              | 10CH0047258 | NEWLY FILED FORECLOSURE |                                 |                      | COOK   | SINGLE FAMILY RESIDENCE | BAC HOME LOANS SERVICING   | PIERCE & ASSOCIATES                   | 1 N DEARBORN ST STE 1300     | CHICAGO                | IL                      | 60602                      | 3124765500                     | CELIA                | CASTORENA           | 15713 LATHROP AVE    | HARVEY         | IL              | 60426-5117         |                        | 110110                    | 77370                      | 29 17 408 012 0000 |                                                         |              |              |              | 72800                    | 2005-11-28T00:00:00    | ARM              | 30               | 762           | 600335393       | 1209         | 70110               | ADDL PIN 29-17-408-011-0000 |                        |                       |             |          |                     |                      |        |                 |                 |                 |                 |                 |                 |             |                |             |                   | 453505209     |                        |             |         |              |           |                     | Other    | 60426   |                | 25         | 37038             | -87.6412674473 | 41.6042373163 |              |              |            | 827500       | 
| 2010-12-06T00:00:00 | YES                 | 2011-01-05T00:00:00 | 1 S WACKER DR STE 2400 CHICAGO 60606    | 1030         | 07CH0023355 | JUDICIAL SALES CORP     | JUDICIAL SALES CORP             | 312236SALE           | COOK   | SINGLE FAMILY RESIDENCE | HSBC MORTGAGE SERVICES INC | FREEDMAN ANSELMO LINDBERG & RAPPE LLC | 1807 W DIEHL RD STE 200      | NAPERVILLE             | IL                      | 60566                      | 6309830770                     | FAYE R               | KIMES               | 15236 WINCHESTER AVE | HARVEY         | IL              | 60426-2916         |                        | 82707                     | 83853                      | 29 18 208 051 0000 | ILLINOIS HEALTHCARE & FAMILY SERVICES 0611532039 NO AMT |              |              |              | 85500                    | 2005-03-14T00:00:00    | CONVENTIONAL     | 30               | 644           | 508449091       |              | 50107               |                             | DOUGLAS                | KIMES                 |             |          |                     |                      |        |                 |                 |                 |                 |                 |                 |             |                |             |                   | 453439856     | 12/3/2007 - Chapter 13 |             |         | RESCHEDULED  |           | 2010-04-01T00:00:00 | Other    | 60426   |                | 0          | 26914             | -87.66452      | 41.61263      |              |              |            | 826902       | 
| 2010-12-06T00:00:00 | NO                  |                     |                                         |              | 10CH0046628 | NEWLY FILED FORECLOSURE |                                 |                      | COOK   | SINGLE FAMILY RESIDENCE | WELLS FARGO BANK           | CODILIS & ASSOCIATES PC               | 15W030 N FRONTAGE RD STE 100 | BURR RIDGE             | IL                      | 60527-6921                 | 6307945300                     | RACHEOL L            | JORDAN              | 15015 ASHLAND AVE    | HARVEY         | IL              | 60426-2125         |                        | 102710                    | 49886                      | 29 08 318 011 0000 |                                                         |              |              |              | 56700                    | 2002-01-16T00:00:00    | CONVENTIONAL     | 30               | 763           | 20180889        |              | 50110               | ADDL PIN 29-08-318-012-0000 |                        |                       |             |          |                     |                      |        |                 |                 |                 |                 |                 |                 |             |                |             |                   | 453505442     |                        |             |         |              |           |                     | Hispanic | 60426   |                | 30         | 35608             | -87.6559192651 | 41.6168080205 |              |              |            | 827100       | 
| 2010-12-06T00:00:00 | NO                  |                     |                                         |              | 10CH0046660 | NEWLY FILED FORECLOSURE |                                 |                      | COOK   | SINGLE FAMILY RESIDENCE | CM REO TRUST               | PIERCE & ASSOCIATES                   | 1 N DEARBORN ST STE 1300     | CHICAGO                | IL                      | 60602                      | 3124765500                     | CHARLES              | WIGGINS             | 15121 LINCOLN AVE    | HARVEY         | IL              | 60426-2909         |                        | 102710                    | 79265                      | 29 18 202 007 0000 |                                                         |              |              |              | 80100                    | 2006-11-16T00:00:00    | ARM              | 30               | 769           | 635508029       | 1670         | 30108               |                             | VERNEAL                | WIGGINS               |             |          |                     |                      |        |                 |                 |                 |                 |                 |                 |             |                |             |                   | 453505443     |                        |             |         |              |           |                     | Other    | 60426   |                | 28         | 26914             | -87.6631388282 | 41.6148905106 |              |              |            | 826902       | 
| 2010-12-06T00:00:00 | NO                  |                     |                                         |              | 10CH0047566 | NEWLY FILED FORECLOSURE |                                 |                      | COOK   | SINGLE FAMILY RESIDENCE | BAC HOME LOANS SERVICING   | PIERCE & ASSOCIATES                   | 1 N DEARBORN ST STE 1300     | CHICAGO                | IL                      | 60602                      | 3124765500                     | MARISA               | LOPEZ               | 15135 PAULINA ST     | HARVEY         | IL              | 60426-3020         |                        | 110310                    | 73659                      | 29 18 206 035 0000 | COUNTRYWIDE HOME LOANS 0610253178 15000                 |              |              |              | 74259                    | 2006-03-29T00:00:00    | ARM              | 30               | 637           | 610253177       | 1304         | 50110               |                             |                        |                       |             |          |                     |                      |        |                 |                 |                 |                 |                 |                 |             |                |             |                   | 453505444     |                        |             |         |              |           |                     | Hispanic | 60426   |                | 35         | 26914             | -87.6582932589 | 41.6146396964 |              |              |            | 826902       | 
| 2010-12-06T00:00:00 | NO                  |                     |                                         |              | 10CH0047302 | NEWLY FILED FORECLOSURE |                                 |                      | COOK   | SINGLE FAMILY RESIDENCE | NATIONSTAR MORTGAGE        | PIERCE & ASSOCIATES                   | 1 N DEARBORN ST STE 1300     | CHICAGO                | IL                      | 60602                      | 3124765500                     | ALAMOS               | THOMPSON            | 15422 ASHLAND AVE    | HARVEY         | IL              | 60426-3621         |                        | 110210                    | 49933                      | 29 18 231 021 0000 | MB FINANCIAL BANK                                       |              |              |              | 52000                    | 2006-01-27T00:00:00    | CONVENTIONAL     | 30               | 825           | 603308070       | 1128         | 60110               |                             |                        |                       |             |          |                     |                      |        |                 |                 |                 |                 |                 |                 |             |                |             |                   | 453505445     |                        |             |         |              |           |                     | Other    | 60426   |                | 33         | 25313             | -87.6559062914 | 41.6094203629 |              |              |            | 827300       | 
```