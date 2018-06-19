# LAPD - Annual High Level Metrics - GOVSTAT

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/lapd-annual-high-level-metrics-govstat-f8ee9) |
| Metadata | [Link](https://data.lacity.org/api/views/t6kt-2yic) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/t6kt-2yic/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/t6kt-2yic/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | t6kt-2yic |
| Name | LAPD - Annual High Level Metrics - GOVSTAT |
| Attribution | LAPD |
| Category | A Safe City |
| Tags | lapd, police, crime, response, response time |
| Created | 2014-05-29T04:25:49Z |
| Publication Date | 2014-05-30T03:11:36Z |

## Description

Contains rolled up annual

## Columns

```ls
| Included | Schema Type    | Field Name                                     | Name                                           | Data Type     | Render Type   |
| ======== | ============== | ============================================== | ============================================== | ============= | ============= |
| Yes      | series tag     | priority_outcome                               | Priority Outcome                               | text          | text          |
| Yes      | time           | final_report_date                              | Final Report Date                              | calendar_date | calendar_date |
| No       |                | final_report_date_name                         | Final Report Date Name                         | text          | text          |
| Yes      | numeric metric | part_1_crimes                                  | Part 1 Crimes                                  | number        | number        |
| Yes      | numeric metric | gang_crimes                                    | Gang Crimes                                    | number        | number        |
| Yes      | numeric metric | homicides                                      | Homicides                                      | number        | number        |
| Yes      | numeric metric | sworn_officers                                 | Sworn Officers                                 | number        | number        |
| Yes      | numeric metric | sexual_assault_evidence_kit_backlog            | Sexual Assault Evidence kit backlog            | number        | number        |
| Yes      | numeric metric | collisions                                     | Collisions                                     | number        | number        |
| Yes      | numeric metric | 911_calls_answered_within_10_seconds           | 911 Calls answered within 10 seconds           | percent       | percent       |
| Yes      | numeric metric | non_emergency_calls_answered_within_20_seconds | Non-emergency calls answered within 20 seconds | percent       | percent       |
```

## Time Field

```ls
Value = final_report_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = final_report_date_name
```

## Data Commands

```ls
series e:t6kt-2yic d:2009-12-31T00:00:00.000Z t:priority_outcome="3. Public Safety" m:part_1_crimes=118310 m:gang_crimes=6170 m:sexual_assault_evidence_kit_backlog=4875 m:sworn_officers=9963 m:911_calls_answered_within_10_seconds=90.55 m:homicides=312 m:non_emergency_calls_answered_within_20_seconds=82.05

series e:t6kt-2yic d:2010-12-31T00:00:00.000Z t:priority_outcome="3. Public Safety" m:part_1_crimes=111188 m:gang_crimes=5545 m:sexual_assault_evidence_kit_backlog=1664 m:sworn_officers=9937 m:911_calls_answered_within_10_seconds=85.51 m:homicides=293 m:non_emergency_calls_answered_within_20_seconds=72.88

series e:t6kt-2yic d:2012-12-31T00:00:00.000Z t:priority_outcome="3. Public Safety" m:part_1_crimes=106025 m:gang_crimes=4339 m:sexual_assault_evidence_kit_backlog=38 m:sworn_officers=9947 m:collisions=20208 m:911_calls_answered_within_10_seconds=94.49 m:homicides=299 m:non_emergency_calls_answered_within_20_seconds=70.57
```

## Meta Commands

```ls
metric m:part_1_crimes p:integer l:"Part 1 Crimes" t:dataTypeName=number

metric m:gang_crimes p:integer l:"Gang Crimes" t:dataTypeName=number

metric m:homicides p:integer l:Homicides t:dataTypeName=number

metric m:sworn_officers p:integer l:"Sworn Officers" t:dataTypeName=number

metric m:sexual_assault_evidence_kit_backlog p:integer l:"Sexual Assault Evidence kit backlog" t:dataTypeName=number

metric m:collisions p:integer l:Collisions t:dataTypeName=number

metric m:911_calls_answered_within_10_seconds p:float l:"911 Calls answered within 10 seconds" t:dataTypeName=percent

metric m:non_emergency_calls_answered_within_20_seconds p:float l:"Non-emergency calls answered within 20 seconds" t:dataTypeName=percent

entity e:t6kt-2yic l:"LAPD - Annual High Level Metrics - GOVSTAT" t:attribution=LAPD t:url=https://data.lacity.org/api/views/t6kt-2yic

property e:t6kt-2yic t:meta.view v:id=t6kt-2yic v:category="A Safe City" v:averageRating=0 v:name="LAPD - Annual High Level Metrics - GOVSTAT" v:attribution=LAPD

property e:t6kt-2yic t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:t6kt-2yic t:meta.view.owner v:id=tgn6-4379 v:profileImageUrlMedium=/api/users/tgn6-4379/profile_images/THUMB v:profileImageUrlLarge=/api/users/tgn6-4379/profile_images/LARGE v:screenName="Mayor's Office OpenData" v:profileImageUrlSmall=/api/users/tgn6-4379/profile_images/TINY v:displayName="Mayor's Office OpenData"

property e:t6kt-2yic t:meta.view.tableauthor v:id=tyhz-nfmm v:screenName="Miguel Sangalang" v:roleName=publisher v:displayName="Miguel Sangalang"
```

## Top Records

```ls
| priority_outcome | final_report_date   | final_report_date_name | part_1_crimes | gang_crimes | homicides | sworn_officers | sexual_assault_evidence_kit_backlog | collisions | 911_calls_answered_within_10_seconds | non_emergency_calls_answered_within_20_seconds | 
| ================ | =================== | ====================== | ============= | =========== | ========= | ============== | =================================== | ========== | ==================================== | ============================================== | 
| 3. Public Safety | 2009-12-31T00:00:00 | Dec-09                 | 118310        | 6170        | 312       | 9963           | 4875                                |            | 90.55                                | 82.05                                          | 
| 3. Public Safety | 2010-12-31T00:00:00 | Dec-10                 | 111188        | 5545        | 293       | 9937           | 1664                                |            | 85.51                                | 72.88                                          | 
| 3. Public Safety | 2012-12-31T00:00:00 | Dec-12                 | 106025        | 4339        | 299       | 9947           | 38                                  | 20208      | 94.49                                | 70.57                                          | 
| 3. Public Safety | 2013-12-31T00:00:00 | Dec-13                 | 100521        | 3576        | 251       | 10001          | 0                                   | 21362      | 93.80                                | 69.61                                          | 
| 3. Public Safety | 2011-12-31T00:00:00 | Dec-11                 | 106375        | 4754        | 297       | 9869           | 545                                 | 20240      | 85.73                                | 69.00                                          | 
| 3. Public Safety | 2014-05-12T00:00:00 | May-14 (YTD)           | 32522         | 1042        | 91        | 9891           | 0                                   | 6492       | 94.34                                | 67.90                                          | 
```