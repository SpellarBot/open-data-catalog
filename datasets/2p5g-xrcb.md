# Violent Crime & Property Crime by Municipality: 2000 to Present

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/violent-crime-property-crime-by-municipality-2000-to-present) |
| Metadata | [Link](https://data.maryland.gov/api/views/2p5g-xrcb) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/2p5g-xrcb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/2p5g-xrcb/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | 2p5g-xrcb |
| Name | Violent Crime & Property Crime by Municipality: 2000 to Present |
| Attribution | GOCCP (Governor's Office of Crime Control and Prevention) |
| Category | Public Safety |
| Tags | violent crime, public safety, homicide, rape, robbery, aggravated assault, goccp |
| Created | 2016-02-02T19:27:10Z |
| Publication Date | 2017-03-09T18:14:08Z |

## Description

The data are provided are the Maryland Statistical Analysis Center (MSAC), within the Governor's Office of Crime Control and Prevention (GOCCP). MSAC, in turn, receives these data from the FBI's annual Uniform Crime Reports.

## Columns

```ls
| Included | Schema Type    | Field Name                                            | Name                                                  | Data Type     | Render Type   |
| ======== | ============== | ===================================================== | ===================================================== | ============= | ============= |
| Yes      | series tag     | jurisdiction                                          | JURISDICTION                                          | text          | text          |
| Yes      | series tag     | county                                                | COUNTY                                                | text          | text          |
| Yes      | time           | year                                                  | YEAR                                                  | calendar_date | calendar_date |
| Yes      | numeric metric | population                                            | POPULATION                                            | number        | number        |
| Yes      | numeric metric | murder                                                | MURDER                                                | number        | number        |
| Yes      | numeric metric | rape                                                  | RAPE                                                  | number        | number        |
| Yes      | numeric metric | robbery                                               | ROBBERY                                               | number        | number        |
| Yes      | numeric metric | agg_assault                                           | AGG. ASSAULT                                          | number        | number        |
| Yes      | numeric metric | b_e                                                   | B & E                                                 | number        | number        |
| Yes      | numeric metric | larceny_theft                                         | LARCENY THEFT                                         | number        | number        |
| Yes      | numeric metric | m_v_theft                                             | M/V THEFT                                             | number        | number        |
| Yes      | numeric metric | grand_total                                           | GRAND TOTAL                                           | number        | number        |
| Yes      | numeric metric | percent_change                                        | PERCENT CHANGE                                        | percent       | percent       |
| Yes      | numeric metric | violent_crime_total                                   | VIOLENT CRIME TOTAL                                   | number        | number        |
| Yes      | numeric metric | violent_crime_percent                                 | VIOLENT CRIME PERCENT                                 | percent       | percent       |
| Yes      | numeric metric | violent_crime_percent_change                          | VIOLENT CRIME PERCENT CHANGE                          | percent       | percent       |
| Yes      | numeric metric | property_crime_totals                                 | PROPERTY CRIME TOTALS                                 | number        | number        |
| Yes      | numeric metric | property_crime_percent                                | PROPERTY CRIME PERCENT                                | percent       | percent       |
| Yes      | numeric metric | property_crime_percent_change                         | PROPERTY CRIME PERCENT CHANGE                         | percent       | percent       |
| Yes      | numeric metric | overall_crime_rate_per_100_000_people                 | OVERALL CRIME RATE PER 100,000 PEOPLE                 | number        | number        |
| Yes      | numeric metric | overall_percent_change_per_100_000_people             | OVERALL PERCENT CHANGE PER 100,000 PEOPLE             | percent       | percent       |
| Yes      | numeric metric | violent_crime_rate_per_100_000_people                 | VIOLENT CRIME RATE PER 100,000 PEOPLE                 | number        | number        |
| Yes      | numeric metric | violent_crime_rate_percent_change_per_100_000_people  | VIOLENT CRIME RATE PERCENT CHANGE PER 100,000 PEOPLE  | percent       | percent       |
| Yes      | numeric metric | property_crime_rate_per_100_000_people                | PROPERTY CRIME RATE PER 100,000 PEOPLE                | number        | number        |
| Yes      | numeric metric | property_crime_rate_percent_change_per_100_000_people | PROPERTY CRIME RATE PERCENT CHANGE PER 100,000 PEOPLE | percent       | percent       |
| Yes      | numeric metric | murder_per_100_000_people                             | MURDER PER 100,000 PEOPLE                             | number        | number        |
| Yes      | numeric metric | rape_per_100_000_people                               | RAPE PER 100,000 PEOPLE                               | number        | number        |
| Yes      | numeric metric | robbery_per_100_000_people                            | ROBBERY PER 100,000 PEOPLE                            | number        | number        |
| Yes      | numeric metric | agg_assault_per_100_000_people                        | AGG. ASSAULT PER 100,000 PEOPLE                       | number        | number        |
| Yes      | numeric metric | b_e_per_100_000_people                                | B & E PER 100,000 PEOPLE                              | number        | number        |
| Yes      | numeric metric | larceny_theft_per_100_000_people                      | LARCENY THEFT PER 100,000 PEOPLE                      | number        | number        |
| Yes      | numeric metric | m_v_theft_per_100_000_people                          | M/V THEFT PER 100,000 PEOPLE                          | number        | number        |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:2p5g-xrcb d:1990-01-01T00:00:00.000Z t:county=Caroline t:jurisdiction=Preston m:larceny_theft=1 m:murder=0 m:property_crime_rate_per_100_000_people=184.2 m:b_e_per_100_000_people=0 m:robbery_per_100_000_people=0 m:property_crime_percent=100 m:violent_crime_rate_per_100_000_people=0 m:violent_crime_total=0 m:robbery=0 m:murder_per_100_000_people=0 m:agg_assault_per_100_000_people=0 m:larceny_theft_per_100_000_people=184.2 m:b_e=0 m:agg_assault=0 m:m_v_theft=0 m:violent_crime_percent=0 m:m_v_theft_per_100_000_people=0 m:property_crime_totals=1 m:rape_per_100_000_people=0 m:grand_total=1 m:rape=0 m:population=543 m:overall_crime_rate_per_100_000_people=184.2

series e:2p5g-xrcb d:1990-01-01T00:00:00.000Z t:county=Wicomico t:jurisdiction=Willards m:larceny_theft=0 m:murder=0 m:property_crime_rate_per_100_000_people=0 m:b_e_per_100_000_people=0 m:robbery_per_100_000_people=0 m:property_crime_percent=0 m:violent_crime_rate_per_100_000_people=0 m:violent_crime_total=0 m:robbery=0 m:murder_per_100_000_people=0 m:agg_assault_per_100_000_people=0 m:larceny_theft_per_100_000_people=0 m:b_e=0 m:agg_assault=0 m:m_v_theft=0 m:violent_crime_percent=0 m:m_v_theft_per_100_000_people=0 m:property_crime_totals=0 m:rape_per_100_000_people=0 m:grand_total=0 m:rape=0 m:population=708 m:overall_crime_rate_per_100_000_people=0

series e:2p5g-xrcb d:1990-01-01T00:00:00.000Z t:county=Harford t:jurisdiction=Aberdeen m:larceny_theft=542 m:murder=1 m:property_crime_rate_per_100_000_people=6319.3 m:b_e_per_100_000_people=1803.3 m:robbery_per_100_000_people=198.7 m:property_crime_percent=90.6 m:violent_crime_rate_per_100_000_people=657.1 m:violent_crime_total=86 m:robbery=26 m:murder_per_100_000_people=7.6 m:agg_assault_per_100_000_people=443.2 m:larceny_theft_per_100_000_people=4141.5 m:b_e=236 m:agg_assault=58 m:m_v_theft=49 m:violent_crime_percent=9.4 m:m_v_theft_per_100_000_people=374.4 m:property_crime_totals=827 m:rape_per_100_000_people=7.6 m:grand_total=913 m:rape=1 m:population=13087 m:overall_crime_rate_per_100_000_people=6976.4
```

## Meta Commands

```ls
metric m:population p:integer l:POPULATION t:dataTypeName=number

metric m:murder p:integer l:MURDER t:dataTypeName=number

metric m:rape p:integer l:RAPE t:dataTypeName=number

metric m:robbery p:integer l:ROBBERY t:dataTypeName=number

metric m:agg_assault p:integer l:"AGG. ASSAULT" t:dataTypeName=number

metric m:b_e p:integer l:"B & E" t:dataTypeName=number

metric m:larceny_theft p:integer l:"LARCENY THEFT" t:dataTypeName=number

metric m:m_v_theft p:integer l:"M/V THEFT" t:dataTypeName=number

metric m:grand_total p:integer l:"GRAND TOTAL" t:dataTypeName=number

metric m:percent_change p:float l:"PERCENT CHANGE" t:dataTypeName=percent

metric m:violent_crime_total p:integer l:"VIOLENT CRIME TOTAL" t:dataTypeName=number

metric m:violent_crime_percent p:float l:"VIOLENT CRIME PERCENT" t:dataTypeName=percent

metric m:violent_crime_percent_change p:float l:"VIOLENT CRIME PERCENT CHANGE" t:dataTypeName=percent

metric m:property_crime_totals p:integer l:"PROPERTY CRIME TOTALS" t:dataTypeName=number

metric m:property_crime_percent p:float l:"PROPERTY CRIME PERCENT" t:dataTypeName=percent

metric m:property_crime_percent_change p:float l:"PROPERTY CRIME PERCENT CHANGE" t:dataTypeName=percent

metric m:overall_crime_rate_per_100_000_people p:float l:"OVERALL CRIME RATE PER 100,000 PEOPLE" t:dataTypeName=number

metric m:overall_percent_change_per_100_000_people p:float l:"OVERALL PERCENT CHANGE PER 100,000 PEOPLE" t:dataTypeName=percent

metric m:violent_crime_rate_per_100_000_people p:float l:"VIOLENT CRIME RATE PER 100,000 PEOPLE" t:dataTypeName=number

metric m:violent_crime_rate_percent_change_per_100_000_people p:float l:"VIOLENT CRIME RATE PERCENT CHANGE PER 100,000 PEOPLE" t:dataTypeName=percent

metric m:property_crime_rate_per_100_000_people p:float l:"PROPERTY CRIME RATE PER 100,000 PEOPLE" t:dataTypeName=number

metric m:property_crime_rate_percent_change_per_100_000_people p:float l:"PROPERTY CRIME RATE PERCENT CHANGE PER 100,000 PEOPLE" t:dataTypeName=percent

metric m:murder_per_100_000_people p:float l:"MURDER PER 100,000 PEOPLE" t:dataTypeName=number

metric m:rape_per_100_000_people p:float l:"RAPE PER 100,000 PEOPLE" t:dataTypeName=number

metric m:robbery_per_100_000_people p:float l:"ROBBERY PER 100,000 PEOPLE" t:dataTypeName=number

metric m:agg_assault_per_100_000_people p:float l:"AGG. ASSAULT PER 100,000 PEOPLE" t:dataTypeName=number

metric m:b_e_per_100_000_people p:float l:"B & E PER 100,000 PEOPLE" t:dataTypeName=number

metric m:larceny_theft_per_100_000_people p:float l:"LARCENY THEFT PER 100,000 PEOPLE" t:dataTypeName=number

metric m:m_v_theft_per_100_000_people p:float l:"M/V THEFT PER 100,000 PEOPLE" t:dataTypeName=number

entity e:2p5g-xrcb l:"Violent Crime & Property Crime by Municipality: 2000 to Present" t:attribution="GOCCP (Governor's Office of Crime Control and Prevention)" t:url=https://data.maryland.gov/api/views/2p5g-xrcb

property e:2p5g-xrcb t:meta.view v:id=2p5g-xrcb v:category="Public Safety" v:attributionLink=http://www.goccp.maryland.gov/msac/crime-statistics.php v:averageRating=0 v:name="Violent Crime & Property Crime by Municipality: 2000 to Present" v:attribution="GOCCP (Governor's Office of Crime Control and Prevention)"

property e:2p5g-xrcb t:meta.view.license v:name="Public Domain"

property e:2p5g-xrcb t:meta.view.owner v:id=cs6p-bz62 v:profileImageUrlMedium=/api/users/cs6p-bz62/profile_images/THUMB v:profileImageUrlLarge=/api/users/cs6p-bz62/profile_images/LARGE v:screenName="data.maryland.gov Administration" v:profileImageUrlSmall=/api/users/cs6p-bz62/profile_images/TINY v:lastNotificationSeenAt=1491976108 v:displayName="data.maryland.gov Administration"

property e:2p5g-xrcb t:meta.view.tableauthor v:id=cs6p-bz62 v:profileImageUrlMedium=/api/users/cs6p-bz62/profile_images/THUMB v:profileImageUrlLarge=/api/users/cs6p-bz62/profile_images/LARGE v:screenName="data.maryland.gov Administration" v:profileImageUrlSmall=/api/users/cs6p-bz62/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1491976108 v:displayName="data.maryland.gov Administration"
```

## Top Records

```ls
| jurisdiction | county   | year                | population | murder | rape | robbery | agg_assault | b_e | larceny_theft | m_v_theft | grand_total | percent_change | violent_crime_total | violent_crime_percent | violent_crime_percent_change | property_crime_totals | property_crime_percent | property_crime_percent_change | overall_crime_rate_per_100_000_people | overall_percent_change_per_100_000_people | violent_crime_rate_per_100_000_people | violent_crime_rate_percent_change_per_100_000_people | property_crime_rate_per_100_000_people | property_crime_rate_percent_change_per_100_000_people | murder_per_100_000_people | rape_per_100_000_people | robbery_per_100_000_people | agg_assault_per_100_000_people | b_e_per_100_000_people | larceny_theft_per_100_000_people | m_v_theft_per_100_000_people | 
| ============ | ======== | =================== | ========== | ====== | ==== | ======= | =========== | === | ============= | ========= | =========== | ============== | =================== | ===================== | ============================ | ===================== | ====================== | ============================= | ===================================== | ========================================= | ===================================== | ==================================================== | ====================================== | ===================================================== | ========================= | ======================= | ========================== | ============================== | ====================== | ================================ | ============================ | 
| Preston      | Caroline | 1990-01-01T00:00:00 | 543        | 0      | 0    | 0       | 0           | 0   | 1             | 0         | 1           |                | 0                   | 0.0                   |                              | 1                     | 100.0                  |                               | 184.2                                 |                                           | 0.0                                   |                                                      | 184.2                                  |                                                       | 0.0                       | 0.0                     | 0.0                        | 0.0                            | 0.0                    | 184.2                            | 0.0                          | 
| Willards     | Wicomico | 1990-01-01T00:00:00 | 708        | 0      | 0    | 0       | 0           | 0   | 0             | 0         | 0           |                | 0                   | 0.0                   |                              | 0                     | 0.0                    |                               | 0.0                                   |                                           | 0.0                                   |                                                      | 0.0                                    |                                                       | 0.0                       | 0.0                     | 0.0                        | 0.0                            | 0.0                    | 0.0                              | 0.0                          | 
| Aberdeen     | Harford  | 1990-01-01T00:00:00 | 13087      | 1      | 1    | 26      | 58          | 236 | 542           | 49        | 913         |                | 86                  | 9.4                   |                              | 827                   | 90.6                   |                               | 6976.4                                |                                           | 657.1                                 |                                                      | 6319.3                                 |                                                       | 7.6                       | 7.6                     | 198.7                      | 443.2                          | 1803.3                 | 4141.5                           | 374.4                        | 
| Aberdeen     | Harford  | 1991-01-01T00:00:00 | 13301      | 0      | 6    | 14      | 80          | 202 | 707           | 60        | 1069        | 17.1           | 100                 | 9.4                   | 16.3                         | 969                   | 90.6                   | 17.2                          | 8037.0                                | 15.2                                      | 751.8                                 | 14.4                                                 | 7285.2                                 | 15.3                                                  | 0.0                       | 45.1                    | 105.3                      | 601.5                          | 1518.7                 | 5315.4                           | 451.1                        | 
| Aberdeen     | Harford  | 1992-01-01T00:00:00 | 13432      | 0      | 8    | 18      | 70          | 138 | 552           | 34        | 820         | -23.3          | 96                  | 11.7                  | -4.0                         | 724                   | 88.3                   | -25.3                         | 6104.8                                | -24.0                                     | 714.7                                 | -4.9                                                 | 5390.1                                 | -26.0                                                 | 0.0                       | 59.6                    | 134.0                      | 521.1                          | 1027.4                 | 4109.6                           | 253.1                        | 
| Aberdeen     | Harford  | 1993-01-01T00:00:00 | 13703      | 0      | 12   | 16      | 112         | 142 | 537           | 31        | 850         | 3.7            | 140                 | 16.5                  | 45.8                         | 710                   | 83.5                   | -1.9                          | 6203.0                                | 1.6                                       | 1021.7                                | 42.9                                                 | 5181.3                                 | -3.9                                                  | 0.0                       | 87.6                    | 116.8                      | 817.3                          | 1036.3                 | 3918.8                           | 226.2                        | 
| Aberdeen     | Harford  | 1994-01-01T00:00:00 | 13815      | 0      | 3    | 16      | 99          | 117 | 565           | 40        | 840         | -1.2           | 118                 | 14.0                  | -15.7                        | 722                   | 86.0                   | 1.7                           | 6080.3                                | -2.0                                      | 854.1                                 | -16.4                                                | 5226.2                                 | 0.9                                                   | 0.0                       | 21.7                    | 115.8                      | 716.6                          | 846.9                  | 4089.7                           | 289.5                        | 
| Aberdeen     | Harford  | 1995-01-01T00:00:00 | 13554      | 1      | 12   | 25      | 90          | 107 | 653           | 42        | 930         | 10.7           | 128                 | 13.8                  | 8.5                          | 802                   | 86.2                   | 11.1                          | 6861.4                                | 12.8                                      | 944.4                                 | 10.6                                                 | 5917.0                                 | 13.2                                                  | 7.4                       | 88.5                    | 184.4                      | 664.0                          | 789.4                  | 4817.7                           | 309.9                        | 
| Aberdeen     | Harford  | 1996-01-01T00:00:00 | 13634      | 1      | 3    | 26      | 57          | 130 | 622           | 39        | 878         | -5.6           | 87                  | 9.9                   | -32.0                        | 791                   | 90.1                   | -1.4                          | 6439.8                                | -6.1                                      | 638.1                                 | -32.4                                                | 5801.7                                 | -1.9                                                  | 7.3                       | 22.0                    | 190.7                      | 418.1                          | 953.5                  | 4562.1                           | 286.1                        | 
| Aberdeen     | Harford  | 1997-01-01T00:00:00 | 13693      | 1      | 11   | 17      | 47          | 102 | 501           | 29        | 708         | -19.4          | 76                  | 10.7                  | -12.6                        | 632                   | 89.3                   | -20.1                         | 5170.5                                | -19.7                                     | 555.0                                 | -13.0                                                | 4615.5                                 | -20.4                                                 | 7.3                       | 80.3                    | 124.2                      | 343.2                          | 744.9                  | 3658.8                           | 211.8                        | 
```