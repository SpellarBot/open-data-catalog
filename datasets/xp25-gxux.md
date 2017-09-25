# LinkNYC New Site Permit Applications

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/linknyc-new-site-permit-applications) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/xp25-gxux) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/xp25-gxux/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/xp25-gxux/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | xp25-gxux |
| Name | LinkNYC New Site Permit Applications |
| Attribution | Department of Information Technology & Telecommunications (DoITT) |
| Category | Social Services |
| Created | 2016-04-25T16:05:24Z |
| Publication Date | 2017-07-26T13:59:46Z |

## Description

Proposed New Site applications for “Links” Wi-Fi Provider: LinkNYC - CityBridge, LLC (Free): LinkNYC 1 gigabyte (GB), Free Wi-Fi Internet Kiosks, Free Nation Wide Phone Locals Map

## Columns

```ls
| Included | Schema Type | Field Name                          | Name                                  | Data Type     | Render Type   |
| ======== | =========== | =================================== | ===================================== | ============= | ============= |
| Yes      | time        | gf_application_submitted_to_doitt_a | GF Application Submitted to DoITT (A) | calendar_date | calendar_date |
| Yes      | series tag  | cblinkid                            | CBL Link ID                           | text          | text          |
| No       |             | latitude                            | Latitude                              | number        | number        |
| No       |             | longitude                           | Longitude                             | number        | number        |
| Yes      | series tag  | borough                             | Borough                               | text          | text          |
| Yes      | series tag  | zoningnumb                          | Zoning                                | text          | text          |
| No       |             | cb                                  | Community Board                       | number        | number        |
| Yes      | series tag  | street_address                      | Street Address                        | text          | text          |
| Yes      | series tag  | cross_street_1                      | Cross_Street 1                        | text          | text          |
| Yes      | series tag  | cross_street_2                      | Cross_Street 2                        | text          | text          |
| Yes      | series tag  | bid                                 | BID                                   | text          | text          |
| Yes      | series tag  | greenfield_in_bid_location          | Greenfield in BID Location            | text          | text          |
| Yes      | series tag  | historic_district                   | Historic District?                    | text          | text          |
| Yes      | series tag  | historic_district_name              | Historic District Name                | text          | text          |
| Yes      | series tag  | gf_permit_appl_id                   | GF Permit_Appl_Id                     | text          | number        |
| No       |             | gf_doitt_submitted_to_cb_a          | GF DoITT Submitted to CB (A)          | calendar_date | calendar_date |
| No       |             | gf_cb_comment_period_ends_a         | GF CB Comment Period Ends (A)         | calendar_date | calendar_date |
```

## Time Field

```ls
Value = gf_application_submitted_to_doitt_a
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = latitude,longitude,cb,gf_doitt_submitted_to_cb_a,gf_cb_comment_period_ends_a
```

## Data Commands

```ls
series e:xp25-gxux d:2017-05-01T00:00:00.000Z t:street_address="93-01 ROOSEVELT AVE" t:greenfield_in_bid_location=FALSE t:cblinkid=LINK-021803 t:gf_permit_appl_id=81892 t:zoningnumb=C2-4 t:historic_district=N t:borough=Queens m:row_number.xp25-gxux=1

series e:xp25-gxux d:2017-05-19T00:00:00.000Z t:street_address="3723 Church Ave" t:greenfield_in_bid_location=FALSE t:cblinkid=LINK-022136 t:gf_permit_appl_id=81920 t:zoningnumb=C2-2 t:historic_district=N t:borough=Brooklyn m:row_number.xp25-gxux=2

series e:xp25-gxux d:2017-05-19T00:00:00.000Z t:street_address="3402 Church Ave" t:greenfield_in_bid_location=FALSE t:cblinkid=LINK-022137 t:gf_permit_appl_id=81921 t:zoningnumb=C1-2 t:historic_district=N t:borough=Brooklyn m:row_number.xp25-gxux=3
```

## Meta Commands

```ls
metric m:row_number.xp25-gxux p:long l:"Row Number"

entity e:xp25-gxux l:"LinkNYC New Site Permit Applications" t:attribution="Department of Information Technology & Telecommunications (DoITT)" t:url=https://data.cityofnewyork.us/api/views/xp25-gxux

property e:xp25-gxux t:meta.view d:2017-09-25T07:24:58.705Z v:averageRating=0 v:name="LinkNYC New Site Permit Applications" v:attribution="Department of Information Technology & Telecommunications (DoITT)" v:id=xp25-gxux v:category="Social Services"

property e:xp25-gxux t:meta.view.owner d:2017-09-25T07:24:58.705Z v:displayName="NYC OpenData" v:lastNotificationSeenAt=1496414226 v:id=5fuc-pqz2 v:screenName="NYC OpenData"

property e:xp25-gxux t:meta.view.tableauthor d:2017-09-25T07:24:58.705Z v:displayName="NYC OpenData" v:lastNotificationSeenAt=1496414226 v:roleName=administrator v:id=5fuc-pqz2 v:screenName="NYC OpenData"
```

## Top Records

```ls
| gf_application_submitted_to_doitt_a | cblinkid    | latitude    | longitude    | borough  | zoningnumb | cb  | street_address      | cross_street_1 | cross_street_2 | bid             | greenfield_in_bid_location | historic_district | historic_district_name | gf_permit_appl_id | gf_doitt_submitted_to_cb_a | gf_cb_comment_period_ends_a | 
| =================================== | =========== | =========== | ============ | ======== | ========== | === | =================== | ============== | ============== | =============== | ========================== | ================= | ====================== | ================= | ========================== | =========================== | 
| 2017-05-01T00:00:00                 | LINK-021803 | 40.74879795 | -73.87355043 | Queens   | C2-4       | 403 | 93-01 ROOSEVELT AVE |                |                |                 | FALSE                      | N                 |                        | 81892             | 2017-07-19T00:00:00        | 2017-09-17T00:00:00         | 
| 2017-05-19T00:00:00                 | LINK-022136 | 40.65122997 | -73.94206208 | Brooklyn | C2-2       | 317 | 3723 Church Ave     |                |                |                 | FALSE                      | N                 |                        | 81920             | 2017-06-01T00:00:00        | 2017-07-31T00:00:00         | 
| 2017-05-19T00:00:00                 | LINK-022137 | 40.65094749 | -73.94554463 | Brooklyn | C1-2       | 317 | 3402 Church Ave     |                |                |                 | FALSE                      | N                 |                        | 81921             | 2017-06-01T00:00:00        | 2017-07-31T00:00:00         | 
| 2017-05-19T00:00:00                 | LINK-022138 | 40.650962   | -73.947834   | Brooklyn | C1-2       | 317 | 3121 Church Ave     |                |                |                 | FALSE                      | N                 |                        | 81922             | 2017-06-01T00:00:00        | 2017-07-31T00:00:00         | 
| 2017-05-19T00:00:00                 | LINK-022140 | 40.648733   | -73.952414   | Brooklyn | C2-3       | 317 | 2606 Snyder Avenue  |                |                |                 | FALSE                      | N                 |                        | 81923             | 2017-06-01T00:00:00        | 2017-07-31T00:00:00         | 
| 2017-05-19T00:00:00                 | LINK-022141 | 40.64868919 | -73.95596197 | Brooklyn | C4-4A      | 314 | 43 Snyder Ave       |                |                |                 | FALSE                      | N                 |                        | 81924             | 2017-06-01T00:00:00        | 2017-07-31T00:00:00         | 
| 2017-05-19T00:00:00                 | LINK-022142 | 40.64860712 | -73.95781959 | Brooklyn | C4-4A      | 314 | 9 Snyder Ave        |                |                | Flatbush Avenue | FALSE                      | N                 |                        | 81925             | 2017-06-01T00:00:00        | 2017-07-31T00:00:00         | 
| 2017-05-24T00:00:00                 | LINK-021119 | 40.71522663 | -73.96274067 | Brooklyn | C2-4       | 301 | 230 Berry St        |                |                |                 | FALSE                      | N                 |                        | 81928             | 2017-07-20T00:00:00        | 2017-09-18T00:00:00         | 
| 2017-05-24T00:00:00                 | LINK-021120 | 40.7187031  | -73.95922842 | Brooklyn | C2-4       | 301 | 120 N 7th St        |                |                |                 | FALSE                      | N                 |                        | 81929             | 2017-07-20T00:00:00        | 2017-09-18T00:00:00         | 
| 2017-05-24T00:00:00                 | LINK-021122 | 40.71924622 | -73.95861248 | Brooklyn | C2-4       | 301 | 126 North 8 St      |                |                |                 | FALSE                      | N                 |                        | 81930             | 2017-07-20T00:00:00        | 2017-09-18T00:00:00         | 
```