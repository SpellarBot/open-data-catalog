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
| Publication Date | 2017-06-01T16:29:24Z |

## Description

Proposed New Site applications for “Links” Wi-Fi Provider: LinkNYC - CityBridge, LLC (Free): LinkNYC 1 gigabyte (GB), Free Wi-Fi Internet Kiosks, Free Nation Wide Phone Locals Map

## Columns

```ls
| Included | Schema Type    | Field Name                          | Name                                  | Data Type     | Render Type   |
| ======== | ============== | =================================== | ===================================== | ============= | ============= |
| Yes      | time           | gf_application_submitted_to_doitt_a | GF Application Submitted to DoITT (A) | calendar_date | calendar_date |
| Yes      | series tag     | cblinkid                            | CBL Link ID                           | text          | text          |
| No       |                | latitude                            | Latitude                              | number        | number        |
| No       |                | longitude                           | Longitude                             | number        | number        |
| Yes      | series tag     | borough                             | Borough                               | text          | text          |
| Yes      | series tag     | zoningnumb                          | Zoning                                | text          | text          |
| No       |                | cb                                  | Community Board                       | number        | number        |
| Yes      | series tag     | street_address                      | Street Address                        | text          | text          |
| Yes      | series tag     | cross_street_1                      | Cross_Street 1                        | text          | text          |
| Yes      | series tag     | cross_street_2                      | Cross_Street 2                        | text          | text          |
| Yes      | series tag     | bid                                 | BID                                   | text          | text          |
| Yes      | numeric metric | greenfield_in_bid_location          | Greenfield in BID Location            | number        | text          |
| Yes      | series tag     | historic_district                   | Historic District?                    | text          | text          |
| Yes      | series tag     | historic_district_name              | Historic District Name                | text          | text          |
| Yes      | series tag     | gf_permit_appl_id                   | GF Permit_Appl_Id                     | text          | number        |
| No       |                | gf_doitt_submitted_to_cb_a          | GF DoITT Submitted to CB (A)          | calendar_date | calendar_date |
| No       |                | gf_cb_comment_period_ends_a         | GF CB Comment Period Ends (A)         | calendar_date | calendar_date |
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
series e:xp25-gxux d:2016-08-15T00:00:00.000Z t:historic_district=N t:cblinkid=LINK-018177 t:gf_permit_appl_id=81586 t:zoningnumb=C2-4 t:borough=Manhattan t:street_address="1895 Amsterdam Ave" m:greenfield_in_bid_location=0

series e:xp25-gxux d:2016-11-22T00:00:00.000Z t:historic_district=N t:cblinkid=LINK-019776 t:gf_permit_appl_id=81756 t:zoningnumb=M1-5/R9 t:borough=Queens t:street_address="27-35 Jackson Ave" t:bid="Long Island City" m:greenfield_in_bid_location=0

series e:xp25-gxux d:2016-11-22T00:00:00.000Z t:historic_district=N t:cblinkid=LINK-019781 t:gf_permit_appl_id=81759 t:zoningnumb=M1-3/R7X t:borough=Queens t:street_address="29-27 40 Road" m:greenfield_in_bid_location=0
```

## Meta Commands

```ls
metric m:greenfield_in_bid_location p:integer l:"Greenfield in BID Location" d:"The new site in a Business Improvement District." t:dataTypeName=number

entity e:xp25-gxux l:"LinkNYC New Site Permit Applications" t:attribution="Department of Information Technology & Telecommunications (DoITT)" t:url=https://data.cityofnewyork.us/api/views/xp25-gxux

property e:xp25-gxux t:meta.view d:2017-06-09T13:53:36.526Z v:id=xp25-gxux v:category="Social Services" v:averageRating=0 v:name="LinkNYC New Site Permit Applications" v:attribution="Department of Information Technology & Telecommunications (DoITT)"

property e:xp25-gxux t:meta.view.owner d:2017-06-09T13:53:36.526Z v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1496414226 v:displayName="NYC OpenData"

property e:xp25-gxux t:meta.view.tableauthor d:2017-06-09T13:53:36.526Z v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1496414226 v:displayName="NYC OpenData"
```

## Top Records

```ls
| gf_application_submitted_to_doitt_a | cblinkid    | latitude           | longitude           | borough   | zoningnumb | cb  | street_address      | cross_street_1 | cross_street_2 | bid              | greenfield_in_bid_location | historic_district | historic_district_name | gf_permit_appl_id | gf_doitt_submitted_to_cb_a | gf_cb_comment_period_ends_a | 
| =================================== | =========== | ================== | =================== | ========= | ========== | === | =================== | ============== | ============== | ================ | ========================== | ================= | ====================== | ================= | ========================== | =========================== | 
| 2016-08-15T00:00:00                 | LINK-018177 | 40.83083542        | -73.943392259999996 | Manhattan | C2-4       | 109 | 1895 Amsterdam Ave  |                |                |                  | 0                          | N                 |                        | 81586             | 2016-10-03T00:00:00        | 2016-12-02T00:00:00         | 
| 2016-11-22T00:00:00                 | LINK-019776 | 40.7478957240127   | -73.940586468226797 | Queens    | M1-5/R9    | 402 | 27-35 Jackson Ave   |                |                | Long Island City | 0                          | N                 |                        | 81756             | 2017-05-04T00:00:00        | 2017-07-03T00:00:00         | 
| 2016-11-22T00:00:00                 | LINK-019781 | 40.751150340145301 | -73.934941539880697 | Queens    | M1-3/R7X   | 401 | 29-27 40 Road       |                |                |                  | 0                          | N                 |                        | 81759             | 2017-05-23T00:00:00        | 2017-07-22T00:00:00         | 
| 2016-11-22T00:00:00                 | LINK-019782 | 40.751507147513102 | -73.934166629911203 | Queens    | M1-3/R7X   | 401 | 30-25 Northern Blvd |                |                |                  | 0                          | N                 |                        | 81764             | 2017-05-23T00:00:00        | 2017-07-22T00:00:00         | 
| 2016-11-22T00:00:00                 | LINK-019783 | 40.751950441625397 | -73.933379632254699 | Queens    | M1-3/R7X   | 401 | 140 31 St           |                |                |                  | 0                          | N                 |                        | 81762             | 2017-05-23T00:00:00        | 2017-07-22T00:00:00         | 
| 2016-11-22T00:00:00                 | LINK-019785 | 40.754774198931202 | -73.931065324952499 | Queens    | M1-2/R6A   | 401 | 37-01 31 Street     |                |                |                  | 0                          | N                 |                        | 81744             | 2017-05-23T00:00:00        | 2017-07-22T00:00:00         | 
| 2016-12-13T00:00:00                 | LINK-019897 | 40.739334026805302 | -73.878132837256899 | Queens    | C1-4       | 404 | 84-43 Corona Ave    |                |                |                  | 0                          | N                 |                        | 81845             | 2017-04-20T00:00:00        | 2017-06-19T00:00:00         | 
| 2016-12-13T00:00:00                 | LINK-019899 | 40.740752725212701 | -73.879340776296701 | Queens    | C1-3       | 404 | 83-23 Broadway      |                |                |                  | 0                          | N                 |                        | 81844             | 2017-04-20T00:00:00        | 2017-06-19T00:00:00         | 
| 2016-12-13T00:00:00                 | LINK-019901 | 40.743035468848497 | -73.882913456979907 | Queens    | C1-3       | 404 | 81-37 Broadway      |                |                |                  | 0                          | N                 |                        | 81842             | 2017-04-20T00:00:00        | 2017-06-19T00:00:00         | 
| 2016-12-13T00:00:00                 | LINK-019902 | 40.743563222872197 | -73.883788790161006 | Queens    | C1-3       | 404 | 81-02 Pettit Ave    |                |                |                  | 0                          | N                 |                        | 81843             | 2017-04-20T00:00:00        | 2017-06-19T00:00:00         | 
```