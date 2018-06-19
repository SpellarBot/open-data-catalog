# Violent Crime & Property Crime Statewide Totals: 1975 to Present

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/violent-crime-property-crime-statewide-totals-1975-to-present) |
| Metadata | [Link](https://data.maryland.gov/api/views/hyg2-hy98) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/hyg2-hy98/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/hyg2-hy98/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | hyg2-hy98 |
| Name | Violent Crime & Property Crime Statewide Totals: 1975 to Present |
| Attribution | GOCCP (Governor's Office of Crime Control and Prevention) |
| Category | Public Safety |
| Tags | violent crime, public safety, homicide, rape, robbery, aggravated assault, goccp |
| Created | 2016-02-08T21:33:31Z |
| Publication Date | 2017-03-09T15:24:40Z |

## Description

The data are provided are the Maryland Statistical Analysis Center (MSAC), within the Governor's Office of Crime Control and Prevention (GOCCP). MSAC, in turn, receives these data from the FBI's annual Uniform Crime Reports.

## Columns

```ls
| Included | Schema Type    | Field Name                                            | Name                                                  | Data Type     | Render Type   |
| ======== | ============== | ===================================================== | ===================================================== | ============= | ============= |
| Yes      | series tag     | jurisdiction                                          | JURISDICTION                                          | text          | text          |
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
| Yes      | numeric metric | murder_rate_percent_change_per_100_000_people         | MURDER RATE PERCENT CHANGE PER 100,000 PEOPLE         | percent       | percent       |
| Yes      | numeric metric | rape_rate_percent_change_per_100_000_people           | RAPE RATE PERCENT CHANGE PER 100,000 PEOPLE           | percent       | percent       |
| Yes      | numeric metric | robbery_rate_percent_change_per_100_000_people        | ROBBERY RATE PERCENT CHANGE PER 100,000 PEOPLE        | percent       | percent       |
| Yes      | numeric metric | agg_assault_rate_percent_change_per_100_000_people    | AGG. ASSAULT RATE PERCENT CHANGE PER 100,000 PEOPLE   | percent       | percent       |
| Yes      | numeric metric | b_e_rate_percent_change_per_100_000_people            | B & E RATE PERCENT CHANGE PER 100,000 PEOPLE          | percent       | percent       |
| Yes      | numeric metric | larceny_theft_rate_percent_change_per_100_000_people  | LARCENY THEFT RATE PERCENT CHANGE PER 100,000 PEOPLE  | percent       | percent       |
| Yes      | numeric metric | m_v_theft_rate_percent_change_per_100_000_people      | M/V THEFT RATE PERCENT CHANGE PER 100,000 PEOPLE      | percent       | percent       |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:hyg2-hy98 d:1975-01-01T00:00:00.000Z t:jurisdiction=Maryland m:larceny_theft=134001 m:murder=435 m:property_crime_rate_per_100_000_people=5200.8 m:b_e_per_100_000_people=1413.8 m:robbery_per_100_000_people=344.2 m:property_crime_percent=88 m:violent_crime_rate_per_100_000_people=709.6 m:violent_crime_total=29078 m:robbery=14104 m:murder_per_100_000_people=10.6 m:agg_assault_per_100_000_people=323.4 m:larceny_theft_per_100_000_people=3269.9 m:b_e=57936 m:agg_assault=13251 m:m_v_theft=21192 m:violent_crime_percent=12 m:m_v_theft_per_100_000_people=517.1 m:property_crime_totals=213129 m:rape_per_100_000_people=31.4 m:grand_total=242207 m:rape=1288 m:population=4098000 m:overall_crime_rate_per_100_000_people=5910.4

series e:hyg2-hy98 d:1976-01-01T00:00:00.000Z t:jurisdiction=Maryland m:larceny_theft_rate_percent_change_per_100_000_people=-0.9 m:robbery_per_100_000_people=295.5 m:property_crime_percent=88.8 m:murder_rate_percent_change_per_100_000_people=-20 m:agg_assault_rate_percent_change_per_100_000_people=-8 m:overall_percent_change_per_100_000_people=-4.2 m:property_crime_rate_percent_change_per_100_000_people=-3.3 m:robbery=12247 m:murder_per_100_000_people=8.5 m:agg_assault_per_100_000_people=297.3 m:larceny_theft_per_100_000_people=3241.7 m:agg_assault=12322 m:b_e=56351 m:violent_crime_percent=11.2 m:percent_change=-3.1 m:property_crime_totals=208460 m:violent_crime_rate_percent_change_per_100_000_people=-10.7 m:rape_per_100_000_people=32 m:grand_total=234708 m:rape=1327 m:population=4144000 m:property_crime_percent_change=-2.2 m:murder=352 m:larceny_theft=134337 m:property_crime_rate_per_100_000_people=5030.4 m:b_e_per_100_000_people=1359.8 m:violent_crime_percent_change=-9.7 m:m_v_theft_rate_percent_change_per_100_000_people=-17.1 m:violent_crime_rate_per_100_000_people=633.4 m:violent_crime_total=26248 m:b_e_rate_percent_change_per_100_000_people=-3.8 m:m_v_theft=17772 m:m_v_theft_per_100_000_people=428.9 m:robbery_rate_percent_change_per_100_000_people=-14.1 m:rape_rate_percent_change_per_100_000_people=1.9 m:overall_crime_rate_per_100_000_people=5663.8

series e:hyg2-hy98 d:1977-01-01T00:00:00.000Z t:jurisdiction=Maryland m:larceny_theft_rate_percent_change_per_100_000_people=-2 m:robbery_per_100_000_people=292.1 m:property_crime_percent=87.8 m:murder_rate_percent_change_per_100_000_people=-5.3 m:agg_assault_rate_percent_change_per_100_000_people=20.7 m:overall_percent_change_per_100_000_people=0.6 m:property_crime_rate_percent_change_per_100_000_people=-0.5 m:robbery=12088 m:murder_per_100_000_people=8 m:agg_assault_per_100_000_people=358.9 m:larceny_theft_per_100_000_people=3177.5 m:agg_assault=14856 m:b_e=57938 m:violent_crime_percent=12.2 m:percent_change=0.5 m:property_crime_totals=207186 m:violent_crime_rate_percent_change_per_100_000_people=9.5 m:rape_per_100_000_people=34.8 m:grand_total=235902 m:rape=1439 m:population=4139000 m:property_crime_percent_change=-0.6 m:murder=333 m:larceny_theft=131516 m:property_crime_rate_per_100_000_people=5005.7 m:b_e_per_100_000_people=1399.8 m:violent_crime_percent_change=9.4 m:m_v_theft_rate_percent_change_per_100_000_people=-0.1 m:violent_crime_rate_per_100_000_people=693.8 m:violent_crime_total=28716 m:b_e_rate_percent_change_per_100_000_people=2.9 m:m_v_theft=17732 m:m_v_theft_per_100_000_people=428.4 m:robbery_rate_percent_change_per_100_000_people=-1.2 m:rape_rate_percent_change_per_100_000_people=8.6 m:overall_crime_rate_per_100_000_people=5699.5
```

## Meta Commands

```ls
metric m:population p:long l:POPULATION t:dataTypeName=number

metric m:murder p:integer l:MURDER t:dataTypeName=number

metric m:rape p:integer l:RAPE t:dataTypeName=number

metric m:robbery p:long l:ROBBERY t:dataTypeName=number

metric m:agg_assault p:long l:"AGG. ASSAULT" t:dataTypeName=number

metric m:b_e p:long l:"B & E" t:dataTypeName=number

metric m:larceny_theft p:long l:"LARCENY THEFT" t:dataTypeName=number

metric m:m_v_theft p:long l:"M/V THEFT" t:dataTypeName=number

metric m:grand_total p:long l:"GRAND TOTAL" t:dataTypeName=number

metric m:percent_change p:float l:"PERCENT CHANGE" t:dataTypeName=percent

metric m:violent_crime_total p:long l:"VIOLENT CRIME TOTAL" t:dataTypeName=number

metric m:violent_crime_percent p:float l:"VIOLENT CRIME PERCENT" t:dataTypeName=percent

metric m:violent_crime_percent_change p:float l:"VIOLENT CRIME PERCENT CHANGE" t:dataTypeName=percent

metric m:property_crime_totals p:long l:"PROPERTY CRIME TOTALS" t:dataTypeName=number

metric m:property_crime_percent p:float l:"PROPERTY CRIME PERCENT" t:dataTypeName=percent

metric m:property_crime_percent_change p:float l:"PROPERTY CRIME PERCENT CHANGE" t:dataTypeName=percent

metric m:overall_crime_rate_per_100_000_people p:long l:"OVERALL CRIME RATE PER 100,000 PEOPLE" t:dataTypeName=number

metric m:overall_percent_change_per_100_000_people p:float l:"OVERALL PERCENT CHANGE PER 100,000 PEOPLE" t:dataTypeName=percent

metric m:violent_crime_rate_per_100_000_people p:long l:"VIOLENT CRIME RATE PER 100,000 PEOPLE" t:dataTypeName=number

metric m:violent_crime_rate_percent_change_per_100_000_people p:float l:"VIOLENT CRIME RATE PERCENT CHANGE PER 100,000 PEOPLE" t:dataTypeName=percent

metric m:property_crime_rate_per_100_000_people p:long l:"PROPERTY CRIME RATE PER 100,000 PEOPLE" t:dataTypeName=number

metric m:property_crime_rate_percent_change_per_100_000_people p:float l:"PROPERTY CRIME RATE PERCENT CHANGE PER 100,000 PEOPLE" t:dataTypeName=percent

metric m:murder_per_100_000_people p:float l:"MURDER PER 100,000 PEOPLE" t:dataTypeName=number

metric m:rape_per_100_000_people p:float l:"RAPE PER 100,000 PEOPLE" t:dataTypeName=number

metric m:robbery_per_100_000_people p:long l:"ROBBERY PER 100,000 PEOPLE" t:dataTypeName=number

metric m:agg_assault_per_100_000_people p:long l:"AGG. ASSAULT PER 100,000 PEOPLE" t:dataTypeName=number

metric m:b_e_per_100_000_people p:long l:"B & E PER 100,000 PEOPLE" t:dataTypeName=number

metric m:larceny_theft_per_100_000_people p:long l:"LARCENY THEFT PER 100,000 PEOPLE" t:dataTypeName=number

metric m:m_v_theft_per_100_000_people p:long l:"M/V THEFT PER 100,000 PEOPLE" t:dataTypeName=number

metric m:murder_rate_percent_change_per_100_000_people p:float l:"MURDER RATE PERCENT CHANGE PER 100,000 PEOPLE" t:dataTypeName=percent

metric m:rape_rate_percent_change_per_100_000_people p:float l:"RAPE RATE PERCENT CHANGE PER 100,000 PEOPLE" t:dataTypeName=percent

metric m:robbery_rate_percent_change_per_100_000_people p:float l:"ROBBERY RATE PERCENT CHANGE PER 100,000 PEOPLE" t:dataTypeName=percent

metric m:agg_assault_rate_percent_change_per_100_000_people p:float l:"AGG. ASSAULT RATE PERCENT CHANGE PER 100,000 PEOPLE" t:dataTypeName=percent

metric m:b_e_rate_percent_change_per_100_000_people p:float l:"B & E RATE PERCENT CHANGE PER 100,000 PEOPLE" t:dataTypeName=percent

metric m:larceny_theft_rate_percent_change_per_100_000_people p:float l:"LARCENY THEFT RATE PERCENT CHANGE PER 100,000 PEOPLE" t:dataTypeName=percent

metric m:m_v_theft_rate_percent_change_per_100_000_people p:float l:"M/V THEFT RATE PERCENT CHANGE PER 100,000 PEOPLE" t:dataTypeName=percent

entity e:hyg2-hy98 l:"Violent Crime & Property Crime Statewide Totals: 1975 to Present" t:attribution="GOCCP (Governor's Office of Crime Control and Prevention)" t:url=https://data.maryland.gov/api/views/hyg2-hy98

property e:hyg2-hy98 t:meta.view v:id=hyg2-hy98 v:category="Public Safety" v:attributionLink=http://www.goccp.maryland.gov/msac/crime-statistics.php v:averageRating=0 v:name="Violent Crime & Property Crime Statewide Totals: 1975 to Present" v:attribution="GOCCP (Governor's Office of Crime Control and Prevention)"

property e:hyg2-hy98 t:meta.view.license v:name="Public Domain"

property e:hyg2-hy98 t:meta.view.owner v:id=cs6p-bz62 v:profileImageUrlMedium=/api/users/cs6p-bz62/profile_images/THUMB v:profileImageUrlLarge=/api/users/cs6p-bz62/profile_images/LARGE v:screenName="data.maryland.gov Administration" v:profileImageUrlSmall=/api/users/cs6p-bz62/profile_images/TINY v:lastNotificationSeenAt=1491976108 v:displayName="data.maryland.gov Administration"

property e:hyg2-hy98 t:meta.view.tableauthor v:id=cs6p-bz62 v:profileImageUrlMedium=/api/users/cs6p-bz62/profile_images/THUMB v:profileImageUrlLarge=/api/users/cs6p-bz62/profile_images/LARGE v:screenName="data.maryland.gov Administration" v:profileImageUrlSmall=/api/users/cs6p-bz62/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1491976108 v:displayName="data.maryland.gov Administration"
```

## Top Records

```ls
| jurisdiction | year                | population | murder | rape | robbery | agg_assault | b_e   | larceny_theft | m_v_theft | grand_total | percent_change | violent_crime_total | violent_crime_percent | violent_crime_percent_change | property_crime_totals | property_crime_percent | property_crime_percent_change | overall_crime_rate_per_100_000_people | overall_percent_change_per_100_000_people | violent_crime_rate_per_100_000_people | violent_crime_rate_percent_change_per_100_000_people | property_crime_rate_per_100_000_people | property_crime_rate_percent_change_per_100_000_people | murder_per_100_000_people | rape_per_100_000_people | robbery_per_100_000_people | agg_assault_per_100_000_people | b_e_per_100_000_people | larceny_theft_per_100_000_people | m_v_theft_per_100_000_people | murder_rate_percent_change_per_100_000_people | rape_rate_percent_change_per_100_000_people | robbery_rate_percent_change_per_100_000_people | agg_assault_rate_percent_change_per_100_000_people | b_e_rate_percent_change_per_100_000_people | larceny_theft_rate_percent_change_per_100_000_people | m_v_theft_rate_percent_change_per_100_000_people | 
| ============ | =================== | ========== | ====== | ==== | ======= | =========== | ===== | ============= | ========= | =========== | ============== | =================== | ===================== | ============================ | ===================== | ====================== | ============================= | ===================================== | ========================================= | ===================================== | ==================================================== | ====================================== | ===================================================== | ========================= | ======================= | ========================== | ============================== | ====================== | ================================ | ============================ | ============================================= | =========================================== | ============================================== | ================================================== | ========================================== | ==================================================== | ================================================ | 
| Maryland     | 1975-01-01T00:00:00 | 4098000    | 435    | 1288 | 14104   | 13251       | 57936 | 134001        | 21192     | 242207      |                | 29078               | 12.0                  |                              | 213129                | 88.0                   |                               | 5910.4                                |                                           | 709.6                                 |                                                      | 5200.8                                 |                                                       | 10.6                      | 31.4                    | 344.2                      | 323.4                          | 1413.8                 | 3269.9                           | 517.1                        |                                               |                                             |                                                |                                                    |                                            |                                                      |                                                  | 
| Maryland     | 1976-01-01T00:00:00 | 4144000    | 352    | 1327 | 12247   | 12322       | 56351 | 134337        | 17772     | 234708      | -3.1           | 26248               | 11.2                  | -9.7                         | 208460                | 88.8                   | -2.2                          | 5663.8                                | -4.2                                      | 633.4                                 | -10.7                                                | 5030.4                                 | -3.3                                                  | 8.5                       | 32.0                    | 295.5                      | 297.3                          | 1359.8                 | 3241.7                           | 428.9                        | -20.0                                         | 1.9                                         | -14.1                                          | -8.0                                               | -3.8                                       | -0.9                                                 | -17.1                                            | 
| Maryland     | 1977-01-01T00:00:00 | 4139000    | 333    | 1439 | 12088   | 14856       | 57938 | 131516        | 17732     | 235902      | 0.5            | 28716               | 12.2                  | 9.4                          | 207186                | 87.8                   | -0.6                          | 5699.5                                | 0.6                                       | 693.8                                 | 9.5                                                  | 5005.7                                 | -0.5                                                  | 8.0                       | 34.8                    | 292.1                      | 358.9                          | 1399.8                 | 3177.5                           | 428.4                        | -5.3                                          | 8.6                                         | -1.2                                           | 20.7                                               | 2.9                                        | -2.0                                                 | -0.1                                             | 
| Maryland     | 1978-01-01T00:00:00 | 4143000    | 338    | 1476 | 12828   | 15686       | 58901 | 134012        | 17599     | 240840      | 2.1            | 30328               | 12.6                  | 5.6                          | 210512                | 87.4                   | 1.6                           | 5813.2                                | 2.0                                       | 732.0                                 | 5.5                                                  | 5081.1                                 | 1.5                                                   | 8.2                       | 35.6                    | 309.6                      | 378.6                          | 1421.7                 | 3234.7                           | 424.8                        | 1.4                                           | 2.5                                         | 6.0                                            | 5.5                                                | 1.6                                        | 1.8                                                  | -0.8                                             | 
| Maryland     | 1979-01-01T00:00:00 | 4149000    | 406    | 1628 | 13745   | 17337       | 62657 | 145278        | 20217     | 261268      | 8.5            | 33116               | 12.7                  | 9.2                          | 228152                | 87.3                   | 8.4                           | 6297.1                                | 8.3                                       | 798.2                                 | 9.0                                                  | 5499.0                                 | 8.2                                                   | 9.8                       | 39.2                    | 331.3                      | 417.9                          | 1510.2                 | 3501.5                           | 487.3                        | 19.9                                          | 10.1                                        | 7.0                                            | 10.4                                               | 6.2                                        | 8.2                                                  | 14.7                                             | 
| Maryland     | 1980-01-01T00:00:00 | 4192211    | 399    | 1681 | 16462   | 17182       | 71130 | 152089        | 18885     | 277828      | 6.3            | 35724               | 12.9                  | 7.9                          | 242104                | 87.1                   | 6.1                           | 6627.2                                | 5.2                                       | 852.2                                 | 6.8                                                  | 5775.1                                 | 5.0                                                   | 9.5                       | 40.1                    | 392.7                      | 409.9                          | 1696.7                 | 3627.9                           | 450.5                        | -2.7                                          | 2.2                                         | 18.5                                           | -1.9                                               | 12.4                                       | 3.6                                                  | -7.6                                             | 
| Maryland     | 1981-01-01T00:00:00 | 4261000    | 422    | 1663 | 18095   | 17691       | 70762 | 152544        | 18486     | 279663      | 0.7            | 37871               | 13.5                  | 6.0                          | 241792                | 86.5                   | -0.1                          | 6563.3                                | -1.0                                      | 888.8                                 | 4.3                                                  | 5674.5                                 | -1.7                                                  | 9.9                       | 39.0                    | 424.7                      | 415.2                          | 1660.7                 | 3580.0                           | 433.8                        | 4.1                                           | -2.7                                        | 8.1                                            | 1.3                                                | -2.1                                       | -1.3                                                 | -3.7                                             | 
| Maryland     | 1982-01-01T00:00:00 | 4265000    | 431    | 1596 | 15377   | 18845       | 60547 | 142903        | 16719     | 256418      | -8.3           | 36249               | 14.1                  | -4.3                         | 220169                | 85.9                   | -8.9                          | 6012.1                                | -8.4                                      | 849.9                                 | -4.4                                                 | 5162.2                                 | -9.0                                                  | 10.1                      | 37.4                    | 360.5                      | 441.9                          | 1419.6                 | 3350.6                           | 392.0                        | 2.0                                           | -4.1                                        | -15.1                                          | 6.4                                                | -14.5                                      | -6.4                                                 | -9.6                                             | 
| Maryland     | 1983-01-01T00:00:00 | 4304000    | 367    | 1412 | 14950   | 18007       | 52697 | 127443        | 15688     | 230564      | -10.1          | 34736               | 15.1                  | -4.2                         | 195828                | 84.9                   | -11.1                         | 5357.0                                | -10.9                                     | 807.1                                 | -5.0                                                 | 4549.9                                 | -11.9                                                 | 8.5                       | 32.8                    | 347.4                      | 418.4                          | 1224.4                 | 2961.0                           | 364.5                        | -15.6                                         | -12.3                                       | -3.7                                           | -5.3                                               | -13.8                                      | -11.6                                                | -7.0                                             | 
| Maryland     | 1984-01-01T00:00:00 | 4349000    | 354    | 1644 | 13113   | 19369       | 51498 | 123625        | 17284     | 226887      | -1.6           | 34480               | 15.2                  | -0.7                         | 192407                | 84.8                   | -1.7                          | 5217.0                                | -2.6                                      | 792.8                                 | -1.8                                                 | 4424.2                                 | -2.8                                                  | 8.1                       | 37.8                    | 301.5                      | 445.4                          | 1184.1                 | 2842.6                           | 397.4                        | -4.5                                          | 15.2                                        | -13.2                                          | 6.5                                                | -3.3                                       | -4.0                                                 | 9.0                                              | 
```