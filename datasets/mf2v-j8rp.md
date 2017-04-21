# 2013-15 OSMB-Facilities Grant Requests June 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2013-15-osmb-facilities-grant-requests-june-2013-93a6b) |
| Metadata | [Link](https://data.oregon.gov/api/views/mf2v-j8rp) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/mf2v-j8rp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/mf2v-j8rp/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | mf2v-j8rp |
| Name | 2013-15 OSMB-Facilities Grant Requests June 2013 |
| Attribution | OSMB |
| Category | Natural Resources |
| Tags | boating, facilities, requests, grants, funding, osmb board, june 2013, 2013-15 |
| Created | 2013-05-31T20:50:39Z |
| Publication Date | 2013-09-25T23:10:24Z |

## Columns

```ls
| Included | Schema Type    | Field Name                         | Name                           | Data Type | Render Type |
| ======== | ============== | ================================== | ============================== | ========= | =========== |
| Yes      | numeric metric | b_consideration                    | BMtgOrder                      | number    | text        |
| No       |                | fg                                 | FG#                            | text      | text        |
| Yes      | series tag     | project                            | Project                        | text      | text        |
| Yes      | series tag     | project_type                       | Project Type                   | text      | text        |
| Yes      | numeric metric | rating                             | Rating                         | number    | text        |
| Yes      | series tag     | details                            | Description                    | text      | text        |
| Yes      | series tag     | facility_name                      | Facility Name                  | text      | text        |
| Yes      | series tag     | applicant                          | Applicant                      | text      | text        |
| Yes      | series tag     | waterbody                          | Waterbody                      | text      | text        |
| Yes      | series tag     | county                             | County                         | text      | text        |
| Yes      | series tag     | multi_image                        | Multi Image                    | photo     | photo       |
| Yes      | numeric metric | applicant_in_kind_funding          | Proposed In-kind Funding       | money     | money       |
| Yes      | numeric metric | cash                               | Proposed Cash                  | money     | money       |
| Yes      | numeric metric | proposed_applicant_other_cash      | Proposed Other Cash            | money     | money       |
| Yes      | numeric metric | federal_other                      | Proposed Federal CVA           | money     | money       |
| Yes      | numeric metric | proposed_federal_big               | Proposed Federal BIG           | money     | money       |
| Yes      | numeric metric | proposed_federal_sfr               | Proposed Federal SFR           | money     | money       |
| Yes      | numeric metric | proposed_state_osmb                | Proposed State-OSMB Funding    | money     | money       |
| Yes      | numeric metric | total_proposed                     | Proposed Total                 | money     | money       |
| Yes      | numeric metric | osmb_recommended_applicant_in_kind | Recommended In Kind            | money     | money       |
| Yes      | numeric metric | osmb_recommended_applicant_cash    | Recommended Cash               | money     | money       |
| Yes      | numeric metric | osmb_recommended_applicant_other   | Recommended Other Cash         | money     | money       |
| Yes      | numeric metric | osmb_recommended_federal_cva       | Recommended Federal CVA        | money     | money       |
| Yes      | numeric metric | osmb_recommended_federal_big       | Recommended Federal BIG        | money     | money       |
| Yes      | numeric metric | osmb_recommended_federal_sfr       | Recommended Federal SFR        | money     | money       |
| Yes      | numeric metric | recommended_osmb_funding           | Recommended State-OSMB Funding | money     | money       |
| Yes      | numeric metric | osmb_proposed                      | Recommended Total              | money     | money       |
| Yes      | series tag     | funding_sources                    | Funding Sources                | photo     | photo       |
| Yes      | series tag     | project_status                     | Staff Recommendations          | text      | text        |
| Yes      | numeric metric | total                              | Board Approved Total           | money     | money       |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = fg
```

## Data Commands

```ls
series e:mf2v-j8rp d:2013-01-01T00:00:00.000Z t:project="Triangle Lake Boarding Floats & Vault Restroom" t:project_status="Staff recommends that the Board approve $35,000 in state boater funds for the 2013-15 Round One funding cycle." t:facility_name="Triangle Lake Landing" t:details="Lane County will replace deteriorated boarding floats that have been removed from the site and replace a toilet at the public launch ramp on Triangle Lake" t:county=Lane t:waterbody="Triangle Lake" t:applicant="Lane County" t:funding_sources=RXU8kPtrsH4h08Yw3Egb_rJPLGQbIcbVHphtGG0_2g0 t:project_type="Boarding Float" t:multi_image=t1yTaau6VZg__68XLlviuB4m5R5ZsQi9GIXSwZk4hI0 m:total=166400 m:osmb_proposed=350000 m:proposed_federal_sfr=0 m:osmb_recommended_applicant_in_kind=0 m:recommended_osmb_funding=35000 m:proposed_federal_big=0 m:applicant_in_kind_funding=0 m:proposed_state_osmb=166400 m:osmb_recommended_federal_big=0 m:osmb_recommended_federal_sfr=0 m:federal_other=0 m:proposed_applicant_other_cash=0 m:osmb_recommended_federal_cva=0 m:b_consideration=2 m:osmb_recommended_applicant_other=0 m:osmb_recommended_applicant_cash=0 m:cash=0 m:total_proposed=166400 m:rating=63

series e:mf2v-j8rp d:2013-01-01T00:00:00.000Z t:project="Scappoose Marina Dredging" t:project_status="Staff recommends that the Board deffers FG 1497 and encourages the Port to continue to persue permits and establish firm estimates." t:facility_name="Scappoose Bay Marina" t:details="The Port of St. Helens will undertake dredging in Scappoose Bay. The Port will deepen the channel from the launch ramp to Multnomah Channel with the grant funds" t:county=Columbia t:waterbody="Scappoose Bay" t:applicant="Port of St. Helens" t:funding_sources=w8pUuo4cfiW_rwkycc7TXQZXFeMI0f2FuiKPZiRrFQw t:project_type=Dredging t:multi_image=ZgehSkEmt8elUZHy7GmT1K82ojFC6EkPEsebkxyNxZo m:total=1182213 m:osmb_proposed=1177213 m:proposed_federal_sfr=0 m:osmb_recommended_applicant_in_kind=0 m:recommended_osmb_funding=0 m:proposed_federal_big=0 m:applicant_in_kind_funding=11100 m:proposed_state_osmb=421113 m:osmb_recommended_federal_big=0 m:osmb_recommended_federal_sfr=0 m:federal_other=0 m:proposed_applicant_other_cash=0 m:osmb_recommended_federal_cva=0 m:b_consideration=3 m:osmb_recommended_applicant_other=0 m:osmb_recommended_applicant_cash=0 m:cash=750000 m:total_proposed=1182213 m:rating=93

series e:mf2v-j8rp d:2013-01-01T00:00:00.000Z t:project="Ojalla Park Facility Improvement" t:project_status="Staff recommends that the Board authorize $74,425 in state boater funds from the 2013-15 Round One funding cycle to match $12,000 of applicant cash, $12,100 in applicant in-kind contribution, and $295,575 in federal Sport Fish Restoration funds for a total cost of $394,100" t:facility_name="Ojalla Bridge" t:details="Lincoln County will replace an unimproved, over-the-bank launch site with a new boat slide, paved access road and parking, and vault toilet" t:county=Lincoln t:waterbody="Siletz River" t:applicant="Lincoln County" t:funding_sources=zM7aTa_Q8HXkSDKXRBWTfaB69ifBh1w5m15aMs5U9Ig t:project_type=Parking t:multi_image=erkUGndl_hBPiXErGbePnhzEKMT55NWCP5OTBhz7Ae0 m:total=24100 m:osmb_proposed=394100 m:proposed_federal_sfr=370000 m:osmb_recommended_applicant_in_kind=12100 m:recommended_osmb_funding=74425 m:proposed_federal_big=0 m:applicant_in_kind_funding=12100 m:proposed_state_osmb=0 m:osmb_recommended_federal_big=0 m:osmb_recommended_federal_sfr=295575 m:federal_other=0 m:proposed_applicant_other_cash=0 m:osmb_recommended_federal_cva=0 m:b_consideration=4 m:osmb_recommended_applicant_other=0 m:osmb_recommended_applicant_cash=12000 m:cash=12000 m:total_proposed=394100 m:rating=98
```

## Meta Commands

```ls
metric m:b_consideration p:integer l:BMtgOrder t:dataTypeName=number

metric m:rating p:integer l:Rating t:dataTypeName=number

metric m:applicant_in_kind_funding p:double l:"Proposed In-kind Funding" t:dataTypeName=money

metric m:cash p:double l:"Proposed Cash" t:dataTypeName=money

metric m:proposed_applicant_other_cash p:integer l:"Proposed Other Cash" t:dataTypeName=money

metric m:federal_other p:double l:"Proposed Federal CVA" t:dataTypeName=money

metric m:proposed_federal_big p:integer l:"Proposed Federal BIG" t:dataTypeName=money

metric m:proposed_federal_sfr p:integer l:"Proposed Federal SFR" t:dataTypeName=money

metric m:proposed_state_osmb p:integer l:"Proposed State-OSMB Funding" t:dataTypeName=money

metric m:total_proposed p:integer l:"Proposed Total" t:dataTypeName=money

metric m:osmb_recommended_applicant_in_kind p:integer l:"Recommended In Kind" t:dataTypeName=money

metric m:osmb_recommended_applicant_cash p:integer l:"Recommended Cash" t:dataTypeName=money

metric m:osmb_recommended_applicant_other p:integer l:"Recommended Other Cash" t:dataTypeName=money

metric m:osmb_recommended_federal_cva p:integer l:"Recommended Federal CVA" t:dataTypeName=money

metric m:osmb_recommended_federal_big p:integer l:"Recommended Federal BIG" t:dataTypeName=money

metric m:osmb_recommended_federal_sfr p:integer l:"Recommended Federal SFR" t:dataTypeName=money

metric m:recommended_osmb_funding p:integer l:"Recommended State-OSMB Funding" t:dataTypeName=money

metric m:osmb_proposed p:integer l:"Recommended Total" t:dataTypeName=money

metric m:total p:double l:"Board Approved Total" t:dataTypeName=money

entity e:mf2v-j8rp l:"2013-15 OSMB-Facilities Grant Requests June 2013" t:attribution=OSMB t:url=https://data.oregon.gov/api/views/mf2v-j8rp

property e:mf2v-j8rp t:meta.view v:id=mf2v-j8rp v:category="Natural Resources" v:averageRating=0 v:name="2013-15 OSMB-Facilities Grant Requests June 2013" v:attribution=OSMB

property e:mf2v-j8rp t:meta.view.owner v:id=iehq-inwk v:profileImageUrlMedium=/api/users/iehq-inwk/profile_images/THUMB v:profileImageUrlLarge=/api/users/iehq-inwk/profile_images/LARGE v:screenName=CRussell v:profileImageUrlSmall=/api/users/iehq-inwk/profile_images/TINY v:displayName=CRussell

property e:mf2v-j8rp t:meta.view.tableauthor v:id=iehq-inwk v:profileImageUrlMedium=/api/users/iehq-inwk/profile_images/THUMB v:profileImageUrlLarge=/api/users/iehq-inwk/profile_images/LARGE v:screenName=CRussell v:profileImageUrlSmall=/api/users/iehq-inwk/profile_images/TINY v:roleName=editor v:displayName=CRussell
```

## Top Records

```ls
| b_consideration | fg   | project                                        | project_type             | rating | details                                                                                                                                                                                                | facility_name           | applicant          | waterbody            | county    | multi_image                                 | applicant_in_kind_funding | cash      | proposed_applicant_other_cash | federal_other | proposed_federal_big | proposed_federal_sfr | proposed_state_osmb | total_proposed | osmb_recommended_applicant_in_kind | osmb_recommended_applicant_cash | osmb_recommended_applicant_other | osmb_recommended_federal_cva | osmb_recommended_federal_big | osmb_recommended_federal_sfr | recommended_osmb_funding | osmb_proposed | funding_sources                             | project_status                                                                                                                                                                                                                                                                                                                                                                                                                                                 | total      | 
| =============== | ==== | ============================================== | ======================== | ====== | ====================================================================================================================================================================================================== | ======================= | ================== | ==================== | ========= | =========================================== | ========================= | ========= | ============================= | ============= | ==================== | ==================== | =================== | ============== | ================================== | =============================== | ================================ | ============================ | ============================ | ============================ | ======================== | ============= | =========================================== | ============================================================================================================================================================================================================================================================================================================================================================================================================================================================== | ========== | 
| 2               | 1494 | Triangle Lake Boarding Floats & Vault Restroom | Boarding Float           | 63     | Lane County will replace deteriorated boarding floats that have been removed from the site and replace a toilet at the public launch ramp on Triangle Lake                                             | Triangle Lake Landing   | Lane County        | Triangle Lake        | Lane      | t1yTaau6VZg__68XLlviuB4m5R5ZsQi9GIXSwZk4hI0 | 0.00                      | 0.00      | 0                             | 0.00          | 0                    | 0                    | 166400              | 166400         | 0                                  | 0                               | 0                                | 0                            | 0                            | 0                            | 35000                    | 350000        | RXU8kPtrsH4h08Yw3Egb_rJPLGQbIcbVHphtGG0_2g0 | Staff recommends that the Board approve $35,000 in state boater funds for the 2013-15 Round One funding cycle.                                                                                                                                                                                                                                                                                                                                                 | 166400.00  | 
| 3               | 1497 | Scappoose Marina Dredging                      | Dredging                 | 93     | The Port of St. Helens will undertake dredging in Scappoose Bay. The Port will deepen the channel from the launch ramp to Multnomah Channel with the grant funds                                       | Scappoose Bay Marina    | Port of St. Helens | Scappoose Bay        | Columbia  | ZgehSkEmt8elUZHy7GmT1K82ojFC6EkPEsebkxyNxZo | 11100.00                  | 750000.00 | 0                             | 0.00          | 0                    | 0                    | 421113              | 1182213        | 0                                  | 0                               | 0                                | 0                            | 0                            | 0                            | 0                        | 1177213       | w8pUuo4cfiW_rwkycc7TXQZXFeMI0f2FuiKPZiRrFQw | Staff recommends that the Board deffers FG 1497 and encourages the Port to continue to persue permits and establish firm estimates.                                                                                                                                                                                                                                                                                                                            | 1182213.00 | 
| 4               | 1484 | Ojalla Park Facility Improvement               | Parking                  | 98     | Lincoln County will replace an unimproved, over-the-bank launch site with a new boat slide, paved access road and parking, and vault toilet                                                            | Ojalla Bridge           | Lincoln County     | Siletz River         | Lincoln   | erkUGndl_hBPiXErGbePnhzEKMT55NWCP5OTBhz7Ae0 | 12100.00                  | 12000.00  | 0                             | 0             | 0                    | 370000               | 0                   | 394100         | 12100                              | 12000                           | 0                                | 0                            | 0                            | 295575                       | 74425                    | 394100        | zM7aTa_Q8HXkSDKXRBWTfaB69ifBh1w5m15aMs5U9Ig | Staff recommends that the Board authorize $74,425 in state boater funds from the 2013-15 Round One funding cycle to match $12,000 of applicant cash, $12,100 in applicant in-kind contribution, and $295,575 in federal Sport Fish Restoration funds for a total cost of $394,100                                                                                                                                                                              | 24100.00   | 
| 4               | 1483 | Morgan Park Ramp Replacement                   | Boarding Float           | 94     | Lincoln County will replace the existing 40-year old asphalt boat ramp with a single-lane concrete ramp and replace an existing vault toilet with a new pre-fabricated toilet with handicapped parking | Morgan Park             | Lincoln County     | Siletz River         | Lincoln   | kpwvBRcY_i1j7VeFLSIZbBGX0Qn8XQs6UbiXNb6n-KY | 8850.00                   | 13100.00  | 0                             | 0.00          | 0                    | 0                    | 106900              | 128900         | 8900                               | 13100                           | 0                                | 0                            | 0                            | 0                            | 106900                   | 128900        | 6tlp8SYXz2t8aAOt1T6091GZ_PqvfovtvDdqXfxiG1k | Staff recommends that the Board authorize $106,900 in state boater funds from the 2013-15 Round One funding cycle to match $13,100 of applicant cash and $8,900 in applicant in-kind contributions for a total cost of $128,900                                                                                                                                                                                                                                | 128850.00  | 
| 4               | 1498 | Sand Island Composting Restroom Replacement    | Composting Restroom      | 92     | The City of St. Helens will replace old, deteriorating composting toilets on Sand Island with two new composting toilets. Sand Island is only accessible by boat                                       | Sand Island Marine Park | City of St. Helens | Columbia River       | Columbia  | J7hOLBD9_GvBfryl402rXTd4sUuVhB2LcYbJYwUelG8 | 22250                     | 0.00      | 0                             | 0.00          | 0                    | 0                    | 200600              | 222850         | 22250                              | 0                               | 0                                | 0                            | 92064                        | 0                            | 108536                   | 222850        | TT6i7PIremCHVmlS6v2rOBDAU2HiNpNWDLDVG9l-H6E | Staff recommends that the Board authorize $108,536 in state boater funds from the 2013-15 Round One funding cycle to match $22,250 in applicant in-kind contributions and $92,064 in federal Boating Infrastructure Grant funds for a total cost of $222,850                                                                                                                                                                                                   | 221600.00  | 
| 4               | 1495 | Mack's Canyon Launch Ramp                      | Boat Ramp                | 89     | BLM will replace an existing, deteriorated concrete plank ramp at Mack?s Canyon with a new single-lane concrete ramp along with expanded parking and ADA access                                        | Macks Canyon            | BLM/Sherman County | Deschutes River      | Sherman   | DPndLmM8_SAxjhJiU-wAWA51lDTjYHvB54XdlS_nfgM | 9000.00                   | 99725.00  | 0                             | 0.00          | 0                    | 0                    | 108725              | 217450         | 9000                               | 99725                           | 0                                | 0                            | 0                            | 0                            | 108725                   | 217450        | zmgSrp4-jq26j1ZoLErruZ9HJUkf6I7E6xGrXRsJtxw | Staff recommends that the Board authorize $108,725 in state boater funds from the 2013-15 Round One funding cycle to match $99,725 of applicant cash and $9,000 in applicant in-kind contributions for a total cost of $217,450                                                                                                                                                                                                                                | 217450.00  | 
| 4               | 1499 | Courthouse Dock Utilities Upgrade              | Utilities                | 94     | The City of St. Helens will upgrade existing utilities serving the pumpout/dump station and transient tie-up at Courthouse Dock and expand additional power pedestals and self-service kiosk           | Courthouse Docks        | City of St. Helens | Columbia River       | Columbia  | d5POHLM-I7YKN-YKJBEKeeTtUojqrynk-stevzoSmFA | 1000.00                   | 5000      | 5000                          | 0.00          | 0                    | 0                    | 100000              | 111000         | 1000                               | 5000                            | 5000                             | 5000                         | 82500                        | 0                            | 19168                    | 117668        | e4hQFsk0ZqIw7xif0zCyTJ6IUl_G6QAQKt5sPLD6byc | Staff recommends that the Board authorize $19,168 in state boater funds from the 2013-15 Round One funding cycle to match $5,000 of applicant cash, $1,000 in applicant in-kind contributions, $5,000 from Columbia River Yachting Association, $5,000 in federal Clean Vessel Act funds (to make improvements to utilities serving the existing pumpout/dump station), and $82,500 in federal Boating Infrastructure Grant funds for a total cost of $117,668 | 111000.00  | 
| 1               | 1486 | Port of Siuslaw Floating Restroom              | Floating Restroom        | 73     | The Port of Siuslaw will purchase and install a floating restroom on the Siuslaw River to serve boaters and anglers                                                                                    | Port of Siuslaw         | Port of Siuslaw    | Siuslaw River        | Lane      | UCVikLvKVr-amjzpSQZZs3anSAZaIUB4d2qQcEq3zYs | 3000.00                   | 0.00      | 0                             | 0             | 0                    | 0                    | 145000              | 148000         | 3000                               | 0                               | 0                                | 108750                       | 0                            | 0                            | 36250                    | 148000        | NU4ev16ST3LojxOqyz8Am2TAV3FNpgRgJCFBLi0iQik | Staff recommends that the Board authorize $36,250 in state boater funds from the 2013-15 Round One funding cycle to match $3,000 of applicant in kind contributions and $108,750 in Federal Clean Vessel Act funds for a total cost of $148,000 for project.                                                                                                                                                                                                   | 148000.00  | 
| 1               | 1491 | Fern Ridge Floating Restroom                   | Floating Restroom        | 85     | Lane County will replace an older floating restroom on Fern Ridge Reservoir with a new floating restroom with an added manual pumpout option                                                           | Richardson Park         | Lane County        | Fern Ridge Reservoir | Lane      | tey5XSK7TF3_6bs-dhl85uVtPoEOIW__PLUY-DPv-_s | 0.00                      | 0.00      | 0                             | 0.00          | 0                    | 0                    | 155000              | 155000         | 0                                  | 0                               | 0                                | 116250                       | 0                            | 0                            | 38750                    | 155000        | 1KtDJ4fH436IBLHi2FI7KYwvoiKOfTLABnIkOVQXblE | Staff recommendsthat the Board authorize $38,750 in state boater funds from the 2013-15 Round One funding cycle to match $116, 250 in federal funds for a total cost of $155,000 for project.                                                                                                                                                                                                                                                                  | 155000.00  | 
| 1               |      | Pumpout/Dump Station                           | Pumpout and Dump Station | 109    | Sundance Marina will purchase and install a combination pumpout/dump station in the marina                                                                                                             | Sundance Marina         | Sundance Marina    | Columbia River       | Multnomah | kNqHjPbGQI9lQ_P07QA9UVvhf8CTjUi31ytI0w9XD6U | 4421                      | 6650      | 0                             | 0.00          | 0                    | 0                    | 50397               | 61468          | 4421                               | 6650                            | 0                                | 42785                        | 0                            | 0                            | 7612                     | 61468         | NNlsxdBGtpba7SFB-_PVZ4EsH31Hb-7ho6o5qJ3ALnw | Staff recommends that the Board authorize $7,612 in state boater funds from the 2013-15 Round One funding cycle to match $4,421 of applicant in kind contributions, $6,650 in applicant's cash, and $42,785 in federal Clean Vessel Act funds for a total cost of $61,468 for project.                                                                                                                                                                         | 61468.00   | 
```