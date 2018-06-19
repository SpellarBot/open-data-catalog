# Oahu State Public Parking Lots

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/oahu-state-public-parking-lots-fcdc9) |
| Metadata | [Link](https://data.hawaii.gov/api/views/tbyx-mr7t) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/tbyx-mr7t/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/tbyx-mr7t/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | tbyx-mr7t |
| Name | Oahu State Public Parking Lots |
| Attribution | DAGS |
| Category | Transportation Facilities |
| Created | 2013-09-20T20:08:02Z |
| Publication Date | 2013-09-20T20:10:40Z |

## Description

September 20, 2013

## Columns

```ls
| Included | Schema Type    | Field Name                   | Name                         | Data Type | Render Type |
| ======== | ============== | ============================ | ============================ | ========= | =========== |
| No       | time           | :updated_at                  | updated_at                   | meta_data | meta_data   |
| Yes      | series tag     | lot                          | Lot                          | text      | text        |
| Yes      | series tag     | name                         | Name                         | text      | text        |
| Yes      | series tag     | second_entrance_cross_street | Second Entrance/Cross Street | text      | text        |
| Yes      | series tag     | island                       | Island                       | text      | text        |
| Yes      | numeric metric | stalls                       | Stalls                       | number    | number      |
| Yes      | series tag     | type                         | Type                         | text      | text        |
| Yes      | series tag     | payment                      | Payment                      | text      | text        |
| Yes      | numeric metric | rates                        | Rates                        | money     | text        |
| Yes      | series tag     | rate_limit                   | Rate Limit                   | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:tbyx-mr7t d:2013-09-20T13:08:12.000Z t:rate_limit="2-hour maximum" t:payment="Quarters Only" t:name="Waipahu Civic Center" t:lot=WA t:type=meters t:island=Oahu m:rates=0.5 m:stalls=41

series e:tbyx-mr7t d:2013-09-20T13:08:12.000Z t:rate_limit="4-hour maximum" t:payment="Quarters Only" t:name="Iolani Palace" t:lot=F t:type=meters t:island=Oahu m:rates=1 m:stalls=47

series e:tbyx-mr7t d:2013-09-20T13:08:12.000Z t:rate_limit="2-hour maximum" t:payment="Quarters Only" t:name="State Office Building" t:lot=Z1 t:type=meters t:island=Kauai m:rates=0.5 m:stalls=13
```

## Meta Commands

```ls
metric m:stalls p:integer l:Stalls t:dataTypeName=number

metric m:rates p:long l:Rates t:dataTypeName=money

entity e:tbyx-mr7t l:"Oahu State Public Parking Lots" t:attribution=DAGS t:url=https://data.hawaii.gov/api/views/tbyx-mr7t

property e:tbyx-mr7t t:meta.view v:id=tbyx-mr7t v:category="Transportation Facilities" v:averageRating=0 v:name="Oahu State Public Parking Lots" v:attribution=DAGS

property e:tbyx-mr7t t:meta.view.owner v:id=q99n-k47h v:screenName="Open Data Portal Administrator" v:displayName="Open Data Portal Administrator"

property e:tbyx-mr7t t:meta.view.tableauthor v:id=q99n-k47h v:screenName="Open Data Portal Administrator" v:roleName=administrator v:displayName="Open Data Portal Administrator"
```

## Top Records

```ls
| :updated_at | lot | name                          | second_entrance_cross_street | island | stalls | type       | payment             | rates                 | rate_limit         | 
| =========== | === | ============================= | ============================ | ====== | ====== | ========== | =================== | ===================== | ================== | 
| 1379682492  | WA  | Waipahu Civic Center          |                              | Oahu   | 41     | meters     | Quarters Only       | $0.50/hour            | 2-hour maximum     | 
| 1379682492  | F   | Iolani Palace                 |                              | Oahu   | 47     | meters     | Quarters Only       | $1/hour               | 4-hour maximum     | 
| 1379682492  | Z1  | State Office Building         |                              | Kauai  | 13     | meters     | Quarters Only       | $0.50/hour            | 2-hour maximum     | 
| 1379682492  | A   | Makai Garage                  | Corner Punchbowl             | Oahu   | 87     | stalls     | Attendant           | $1/hour first 2-hours | $2/hour thereafter | 
| 1379682492  | D   | Kekuanaoa Building            | Corner Punchbowl             | Oahu   | 40     | meters     | Quarters Only       | $1/hour               | 4-hour maximum     | 
| 1379682492  | Z3  | Department of Health Building |                              | Kauai  | 9      | meters     | Quarters Only       | $0.50/hour            | 2-hour maximum     | 
| 1379682492  | G   | Kalanimoku Building           | Corner Beretania             | Oahu   | 51     | meters     | Quarters Only       | $1/hour               | 2-hour maximum     | 
| 1379682492  | KP  | Kapolei Civic Center          | Uluohia                      | Oahu   | 81     | paystation | insert exact amount | $0.50/hour            | 2-hour maximum     | 
| 1379682492  | X1  | State Office Building         |                              | Maui   | 38     | meters     | Quarters Only       | $0.50/hour            | 2-hour maximum     | 
| 1379682492  | YR  | State Office Building         |                              | Hawaii | 43     | meters     | Quarters Only       | $0.50/hour            | 2-hour maximum     | 
```