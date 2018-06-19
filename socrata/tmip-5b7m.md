# Oregon Workers' Compensation System, Summary Statistics

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/oregon-workers-compensation-system-summary-statistics-27d52) |
| Metadata | [Link](https://data.oregon.gov/api/views/tmip-5b7m) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/tmip-5b7m/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/tmip-5b7m/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | tmip-5b7m |
| Name | Oregon Workers' Compensation System, Summary Statistics |
| Attribution | Oregon Department of Conusmer and Business Services, Information Management Division |
| Category | Business |
| Tags | oregon, workers' compensation, business |
| Created | 2011-06-28T19:07:51Z |
| Publication Date | 2012-08-28T23:17:04Z |

## Description

In 1968, most Oregon employers became subject to Oregon?s workers? compensation statute. The table provides some information for much of the life of the workers? compensation system. (Descriptions of the data series are provided in the document stored as an attachment under the "About" tab.)

## Columns

```ls
| Included | Schema Type    | Field Name                            | Name                                       | Data Type | Render Type |
| ======== | ============== | ===================================== | ========================================== | ========= | =========== |
| Yes      | time           | calendar_year                         | Calendar year                              | number    | number      |
| Yes      | numeric metric | wc_system_employers                   | WC system employers                        | number    | number      |
| Yes      | numeric metric | subject_employees                     | Subject employees                          | number    | number      |
| Yes      | numeric metric | accepted_disabling_claims             | Accepted disabling claims                  | number    | number      |
| Yes      | numeric metric | denied_claims                         | Denied claims                              | number    | number      |
| Yes      | numeric metric | claims_closures_and_resolutions       | Claims closures and resolutions            | number    | number      |
| Yes      | numeric metric | compensable_fatality_claims           | Compensable fatality claims                | number    | number      |
| Yes      | numeric metric | net_permanent_total_disability_claims | Net permanent total disability claims      | number    | number      |
| Yes      | numeric metric | administrative_dispute_requests       | Administrative dispute requests            | number    | number      |
| Yes      | numeric metric | hearing_requests_received             | Hearing requests received                  | number    | number      |
| Yes      | numeric metric | board_review_requests_received        | Board review requests received             | number    | number      |
| Yes      | numeric metric | claim_disposition_agreements          | Claim disposition agreements               | number    | number      |
| Yes      | numeric metric | court_of_appeals_requests_received    | Court of Appeals requests received         | number    | number      |
| Yes      | numeric metric | vocational_assistance_eligibilities   | Vocational assistance eligibilities        | number    | number      |
| Yes      | numeric metric | workers_compensation_premium_millions | Workers' compensation premium ($ millions) | money     | money       |
| Yes      | numeric metric | benefit_average_weekly_wage           | Benefit average weekly wage                | money     | money       |
```

## Time Field

```ls
Value = calendar_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:tmip-5b7m d:1968-01-01T00:00:00.000Z m:board_review_requests_received=440 m:subject_employees=671900 m:hearing_requests_received=2105 m:wc_system_employers=49021 m:compensable_fatality_claims=118 m:claims_closures_and_resolutions=23334 m:accepted_disabling_claims=32509 m:workers_compensation_premium_millions=70.5 m:benefit_average_weekly_wage=126.59

series e:tmip-5b7m d:1969-01-01T00:00:00.000Z m:board_review_requests_received=492 m:net_permanent_total_disability_claims=96 m:subject_employees=700800 m:hearing_requests_received=2365 m:wc_system_employers=52191 m:compensable_fatality_claims=131 m:claims_closures_and_resolutions=27583 m:accepted_disabling_claims=35372 m:workers_compensation_premium_millions=82.4 m:benefit_average_weekly_wage=134.47

series e:tmip-5b7m d:1970-01-01T00:00:00.000Z m:board_review_requests_received=505 m:net_permanent_total_disability_claims=159 m:subject_employees=704300 m:denied_claims=1935 m:hearing_requests_received=2706 m:wc_system_employers=52789 m:compensable_fatality_claims=137 m:claims_closures_and_resolutions=50917 m:accepted_disabling_claims=30338 m:workers_compensation_premium_millions=86.8 m:benefit_average_weekly_wage=140.58
```

## Meta Commands

```ls
metric m:wc_system_employers p:integer l:"WC system employers" d:"Counts of employers in the Oregon workers? compensation system. See the attached document for a detailed definition." t:dataTypeName=number

metric m:subject_employees p:integer l:"Subject employees" d:"Counts of workers covered by the Oregon workers? compensation system. See the attached document for a detailed definition." t:dataTypeName=number

metric m:accepted_disabling_claims p:integer l:"Accepted disabling claims" d:"Counts of claims accepted as disabling. An injury is classified as disabling if it causes the worker temporary disability (time-loss), permanent disability, or death. See the attached document for a detailed definition." t:dataTypeName=number

metric m:denied_claims p:integer l:"Denied claims" d:"Workers? compensation claims denied by insurers. The figures include both denied disabling and denied nondisabling claims. See the attached document for a detailed definition." t:dataTypeName=number

metric m:claims_closures_and_resolutions p:integer l:"Claims closures and resolutions" d:"The claims closure process involves closing a claim, halting temporary disability payments, and determining permanent disability when an injured worker is found to be medically stationary. See the attached document for a detailed definition." t:dataTypeName=number

metric m:compensable_fatality_claims p:integer l:"Compensable fatality claims" d:"Counts of the fatalities that had death benefits paid under the Oregon workers? compensation statute." t:dataTypeName=number

metric m:net_permanent_total_disability_claims p:integer l:"Net permanent total disability claims" d:"PTD is the loss of use or function of any portion of the body, in combination with any pre-existing disability, that permanently prevents the worker from regularly performing gainful and suitable work. See the attached document for a detailed definition." t:dataTypeName=number

metric m:administrative_dispute_requests p:integer l:"Administrative dispute requests" d:"Counts of the major portions of the DCBS Workers? Compensation Division (WCD) administrative review process. See the attached document for a detailed definition." t:dataTypeName=number

metric m:hearing_requests_received p:integer l:"Hearing requests received" d:"Counts of the cases involving requests for hearings to the Workers? Compensation Board. See the attached document for a detailed definition." t:dataTypeName=number

metric m:board_review_requests_received p:integer l:"Board review requests received" d:"Counts of requests for Board review of appealed hearings orders. See the attached document for a detailed definition." t:dataTypeName=number

metric m:claim_disposition_agreements p:integer l:"Claim disposition agreements" d:"A claim disposition agreement (CDA) is an agreement between the parties to a workers' compensation claim. Aee the attached document for a detailed definition." t:dataTypeName=number

metric m:court_of_appeals_requests_received p:integer l:"Court of Appeals requests received" d:"Counts of requests to the Oregon Court of Appeals of board-review orders." t:dataTypeName=number

metric m:vocational_assistance_eligibilities p:integer l:"Vocational assistance eligibilities" d:"The figures include all decisions signifying eligibility or eligibility restoration by insurers or the DCBS Workers' Compensation Division." t:dataTypeName=number

metric m:workers_compensation_premium_millions p:double l:"Workers' compensation premium ($ millions)" d:"For 1977-present, total-system written premiums are shown. The figures are the sum of direct premiums written for private insurers and SAIF Corporation, earned large deductible premium credits for private insurers, See the attached document for a detailed" t:dataTypeName=money

metric m:benefit_average_weekly_wage p:double l:"Benefit average weekly wage" d:"Provides the Oregon average weekly wage of workers in covered employment for the last quarter of the calendar year. This is applied to the computation of benefits the following fiscal year. See the attached document for a detailed definition." t:dataTypeName=money

entity e:tmip-5b7m l:"Oregon Workers' Compensation System, Summary Statistics" t:attribution="Oregon Department of Conusmer and Business Services, Information Management Division" t:url=https://data.oregon.gov/api/views/tmip-5b7m

property e:tmip-5b7m t:meta.view v:id=tmip-5b7m v:category=Business v:attributionLink=http://www4.cbs.state.or.us/ex/imd/external/ v:averageRating=0 v:name="Oregon Workers' Compensation System, Summary Statistics" v:attribution="Oregon Department of Conusmer and Business Services, Information Management Division"

property e:tmip-5b7m t:meta.view.owner v:id=fe3n-werh v:screenName="Gary Helmer" v:displayName="Gary Helmer"

property e:tmip-5b7m t:meta.view.tableauthor v:id=fe3n-werh v:screenName="Gary Helmer" v:roleName=editor v:displayName="Gary Helmer"
```

## Top Records

```ls
| calendar_year | wc_system_employers | subject_employees | accepted_disabling_claims | denied_claims | claims_closures_and_resolutions | compensable_fatality_claims | net_permanent_total_disability_claims | administrative_dispute_requests | hearing_requests_received | board_review_requests_received | claim_disposition_agreements | court_of_appeals_requests_received | vocational_assistance_eligibilities | workers_compensation_premium_millions | benefit_average_weekly_wage | 
| ============= | =================== | ================= | ========================= | ============= | =============================== | =========================== | ===================================== | =============================== | ========================= | ============================== | ============================ | ================================== | =================================== | ===================================== | =========================== | 
| 1968          | 49021               | 671900            | 32509                     |               | 23334                           | 118                         |                                       |                                 | 2105                      | 440                            |                              |                                    |                                     | 70.5                                  | 126.59                      | 
| 1969          | 52191               | 700800            | 35372                     |               | 27583                           | 131                         | 96                                    |                                 | 2365                      | 492                            |                              |                                    |                                     | 82.4                                  | 134.47                      | 
| 1970          | 52789               | 704300            | 30338                     | 1935          | 50917                           | 137                         | 159                                   |                                 | 2706                      | 505                            |                              |                                    |                                     | 86.8                                  | 140.58                      | 
| 1971          | 58768               | 732500            | 30663                     | 1709          | 26710                           | 132                         | 217                                   |                                 | 2936                      | 562                            |                              |                                    |                                     | 107.4                                 | 148.82                      | 
| 1972          | 62584               | 778800            | 34835                     | 2177          | 27166                           | 133                         | 286                                   |                                 | 3596                      | 519                            |                              |                                    |                                     | 136.6                                 | 156.50                      | 
| 1973          | 65788               | 820600            | 36802                     | 2408          | 31704                           | 144                         | 285                                   |                                 | 4244                      | 504                            |                              |                                    |                                     | 149.0                                 | 166.34                      | 
| 1974          | 60638               | 841100            | 34214                     | 2647          | 33952                           | 123                         | 254                                   |                                 | 4710                      | 718                            |                              |                                    |                                     | 196.9                                 | 180.17                      | 
| 1975          | 60650               | 840100            | 32172                     | 2699          | 35256                           | 132                         | 299                                   |                                 | 5588                      | 756                            |                              |                                    |                                     | 221.2                                 | 195.18                      | 
| 1976          | 62884               | 879200            | 31013                     | 3087          | 36908                           | 104                         | 237                                   |                                 | 7194                      | 812                            |                              |                                    |                                     | 280.89999999999998                    | 213.78                      | 
| 1977          | 68782               | 937100            | 38657                     | 4384          | 41599                           | 124                         | 211                                   |                                 | 8005                      | 914                            |                              |                                    | 3469                                | 421.9                                 | 224.16                      | 
```