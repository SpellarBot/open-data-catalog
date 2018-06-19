# Violent Crime & Property Crime by County: 1975 to Present

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/violent-crime-property-crime-by-county-1975-to-present) |
| Metadata | [Link](https://data.maryland.gov/api/views/jwfa-fdxs) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/jwfa-fdxs/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/jwfa-fdxs/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | jwfa-fdxs |
| Name | Violent Crime & Property Crime by County: 1975 to Present |
| Attribution | GOCCP |
| Category | Public Safety |
| Tags | violent crime, public safety, homicide, rape, robbery, aggravated assault, goccp |
| Created | 2015-07-27T19:40:05Z |
| Publication Date | 2017-03-09T17:03:13Z |

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
series e:jwfa-fdxs d:1975-01-01T00:00:00.000Z t:jurisdiction="Garrett County" m:larceny_theft=221 m:murder=2 m:property_crime_rate_per_100_000_people=1877.6 m:b_e_per_100_000_people=824.2 m:robbery_per_100_000_people=22 m:property_crime_percent=91.6 m:violent_crime_rate_per_100_000_people=171.9 m:violent_crime_total=39 m:robbery=5 m:murder_per_100_000_people=8.8 m:agg_assault_per_100_000_people=132.2 m:larceny_theft_per_100_000_people=974 m:b_e=187 m:agg_assault=30 m:m_v_theft=18 m:violent_crime_percent=8.4 m:m_v_theft_per_100_000_people=79.3 m:property_crime_totals=426 m:rape_per_100_000_people=8.8 m:grand_total=465 m:rape=2 m:population=22689 m:overall_crime_rate_per_100_000_people=2049.5

series e:jwfa-fdxs d:1975-01-01T00:00:00.000Z t:jurisdiction="Howard County" m:larceny_theft=3161 m:murder=6 m:property_crime_rate_per_100_000_people=5184 m:b_e_per_100_000_people=1408.2 m:robbery_per_100_000_people=119.5 m:property_crime_percent=92 m:violent_crime_rate_per_100_000_people=447.7 m:violent_crime_total=427 m:robbery=114 m:murder_per_100_000_people=6.3 m:agg_assault_per_100_000_people=280 m:larceny_theft_per_100_000_people=3314.5 m:b_e=1343 m:agg_assault=267 m:m_v_theft=440 m:violent_crime_percent=8 m:m_v_theft_per_100_000_people=461.4 m:property_crime_totals=4944 m:rape_per_100_000_people=41.9 m:grand_total=5371 m:rape=40 m:population=95370 m:overall_crime_rate_per_100_000_people=5631.8

series e:jwfa-fdxs d:1975-01-01T00:00:00.000Z t:jurisdiction="Queen Anne's County" m:larceny_theft=356 m:murder=5 m:property_crime_rate_per_100_000_people=3297.6 m:b_e_per_100_000_people=1458.5 m:robbery_per_100_000_people=78 m:property_crime_percent=92.5 m:violent_crime_rate_per_100_000_people=268.3 m:violent_crime_total=55 m:robbery=16 m:murder_per_100_000_people=24.4 m:agg_assault_per_100_000_people=146.3 m:larceny_theft_per_100_000_people=1736.6 m:b_e=299 m:agg_assault=30 m:m_v_theft=21 m:violent_crime_percent=7.5 m:m_v_theft_per_100_000_people=102.4 m:property_crime_totals=676 m:rape_per_100_000_people=19.5 m:grand_total=731 m:rape=4 m:population=20500 m:overall_crime_rate_per_100_000_people=3565.9
```

## Meta Commands

```ls
metric m:population p:long l:POPULATION t:dataTypeName=number

metric m:murder p:integer l:MURDER t:dataTypeName=number

metric m:rape p:integer l:RAPE t:dataTypeName=number

metric m:robbery p:integer l:ROBBERY t:dataTypeName=number

metric m:agg_assault p:integer l:"AGG. ASSAULT" t:dataTypeName=number

metric m:b_e p:integer l:"B & E" t:dataTypeName=number

metric m:larceny_theft p:integer l:"LARCENY THEFT" t:dataTypeName=number

metric m:m_v_theft p:integer l:"M/V THEFT" t:dataTypeName=number

metric m:grand_total p:long l:"GRAND TOTAL" t:dataTypeName=number

metric m:percent_change p:float l:"PERCENT CHANGE" t:dataTypeName=percent

metric m:violent_crime_total p:integer l:"VIOLENT CRIME TOTAL" t:dataTypeName=number

metric m:violent_crime_percent p:float l:"VIOLENT CRIME PERCENT" t:dataTypeName=percent

metric m:violent_crime_percent_change p:float l:"VIOLENT CRIME PERCENT CHANGE" t:dataTypeName=percent

metric m:property_crime_totals p:integer l:"PROPERTY CRIME TOTALS" t:dataTypeName=number

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

entity e:jwfa-fdxs l:"Violent Crime & Property Crime by County: 1975 to Present" t:attribution=GOCCP t:url=https://data.maryland.gov/api/views/jwfa-fdxs

property e:jwfa-fdxs t:meta.view v:id=jwfa-fdxs v:category="Public Safety" v:attributionLink=http://www.goccp.maryland.gov/msac/crime-statistics.php v:averageRating=0 v:name="Violent Crime & Property Crime by County: 1975 to Present" v:attribution=GOCCP

property e:jwfa-fdxs t:meta.view.license v:name="Public Domain"

property e:jwfa-fdxs t:meta.view.owner v:id=cs6p-bz62 v:profileImageUrlMedium=/api/users/cs6p-bz62/profile_images/THUMB v:profileImageUrlLarge=/api/users/cs6p-bz62/profile_images/LARGE v:screenName="data.maryland.gov Administration" v:profileImageUrlSmall=/api/users/cs6p-bz62/profile_images/TINY v:lastNotificationSeenAt=1491976108 v:displayName="data.maryland.gov Administration"

property e:jwfa-fdxs t:meta.view.tableauthor v:id=cs6p-bz62 v:profileImageUrlMedium=/api/users/cs6p-bz62/profile_images/THUMB v:profileImageUrlLarge=/api/users/cs6p-bz62/profile_images/LARGE v:screenName="data.maryland.gov Administration" v:profileImageUrlSmall=/api/users/cs6p-bz62/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1491976108 v:displayName="data.maryland.gov Administration"
```

## Top Records

```ls
| jurisdiction        | year                | population | murder | rape | robbery | agg_assault | b_e  | larceny_theft | m_v_theft | grand_total | percent_change | violent_crime_total | violent_crime_percent | violent_crime_percent_change | property_crime_totals | property_crime_percent | property_crime_percent_change | overall_crime_rate_per_100_000_people | overall_percent_change_per_100_000_people | violent_crime_rate_per_100_000_people | violent_crime_rate_percent_change_per_100_000_people | property_crime_rate_per_100_000_people | property_crime_rate_percent_change_per_100_000_people | murder_per_100_000_people | rape_per_100_000_people | robbery_per_100_000_people | agg_assault_per_100_000_people | b_e_per_100_000_people | larceny_theft_per_100_000_people | m_v_theft_per_100_000_people | murder_rate_percent_change_per_100_000_people | rape_rate_percent_change_per_100_000_people | robbery_rate_percent_change_per_100_000_people | agg_assault_rate_percent_change_per_100_000_people | b_e_rate_percent_change_per_100_000_people | larceny_theft_rate_percent_change_per_100_000_people | m_v_theft_rate_percent_change_per_100_000_people | 
| =================== | =================== | ========== | ====== | ==== | ======= | =========== | ==== | ============= | ========= | =========== | ============== | =================== | ===================== | ============================ | ===================== | ====================== | ============================= | ===================================== | ========================================= | ===================================== | ==================================================== | ====================================== | ===================================================== | ========================= | ======================= | ========================== | ============================== | ====================== | ================================ | ============================ | ============================================= | =========================================== | ============================================== | ================================================== | ========================================== | ==================================================== | ================================================ | 
| Garrett County      | 1975-01-01T00:00:00 | 22689      | 2      | 2    | 5       | 30          | 187  | 221           | 18        | 465         |                | 39                  | 8.4                   |                              | 426                   | 91.6                   |                               | 2049.5                                |                                           | 171.9                                 |                                                      | 1877.6                                 |                                                       | 8.8                       | 8.8                     | 22.0                       | 132.2                          | 824.2                  | 974.0                            | 79.3                         |                                               |                                             |                                                |                                                    |                                            |                                                      |                                                  | 
| Howard County       | 1975-01-01T00:00:00 | 95370      | 6      | 40   | 114     | 267         | 1343 | 3161          | 440       | 5371        |                | 427                 | 8.0                   |                              | 4944                  | 92.0                   |                               | 5631.8                                |                                           | 447.7                                 |                                                      | 5184.0                                 |                                                       | 6.3                       | 41.9                    | 119.5                      | 280.0                          | 1408.2                 | 3314.5                           | 461.4                        |                                               |                                             |                                                |                                                    |                                            |                                                      |                                                  | 
| Queen Anne's County | 1975-01-01T00:00:00 | 20500      | 5      | 4    | 16      | 30          | 299  | 356           | 21        | 731         |                | 55                  | 7.5                   |                              | 676                   | 92.5                   |                               | 3565.9                                |                                           | 268.3                                 |                                                      | 3297.6                                 |                                                       | 24.4                      | 19.5                    | 78.0                       | 146.3                          | 1458.5                 | 1736.6                           | 102.4                        |                                               |                                             |                                                |                                                    |                                            |                                                      |                                                  | 
| Talbot County       | 1975-01-01T00:00:00 | 24948      | 2      | 4    | 23      | 48          | 246  | 528           | 28        | 879         |                | 77                  | 8.8                   |                              | 802                   | 91.2                   |                               | 3523.3                                |                                           | 308.6                                 |                                                      | 3214.7                                 |                                                       | 8.0                       | 16.0                    | 92.2                       | 192.4                          | 986.1                  | 2116.4                           | 112.2                        |                                               |                                             |                                                |                                                    |                                            |                                                      |                                                  | 
| Allegany County     | 1976-01-01T00:00:00 | 83923      | 2      | 2    | 24      | 59          | 581  | 1384          | 73        | 2125        | -8.8           | 87                  | 4.1                   | -38.7                        | 2038                  | 95.9                   | -6.8                          | 2532.1                                | -13.4                                     | 103.7                                 | -41.8                                                | 2428.4                                 | -11.6                                                 | 2.4                       | 2.4                     | 28.6                       | 70.3                           | 692.3                  | 1649.1                           | 87.0                         | -36.7                                         | -62.0                                       | 13.9                                           | -50.9                                              | -17.6                                      | -7.8                                                 | -25.5                                            | 
| Allegany County     | 1977-01-01T00:00:00 | 82102      | 3      | 7    | 32      | 85          | 592  | 1390          | 102       | 2211        | 4.0            | 127                 | 5.7                   | 46.0                         | 2084                  | 94.3                   | 2.3                           | 2693.0                                | 6.4                                       | 154.7                                 | 49.2                                                 | 2538.3                                 | 4.5                                                   | 3.7                       | 8.5                     | 39.0                       | 103.5                          | 721.1                  | 1693.0                           | 124.2                        | 53.3                                          | 257.8                                       | 36.3                                           | 47.3                                               | 4.2                                        | 2.7                                                  | 42.8                                             | 
| Allegany County     | 1978-01-01T00:00:00 | 79966      | 1      | 2    | 18      | 81          | 539  | 1390          | 100       | 2131        | -3.6           | 102                 | 4.8                   | -19.7                        | 2029                  | 95.2                   | -2.6                          | 2664.9                                | -1.0                                      | 127.6                                 | -17.5                                                | 2537.3                                 | 0.0                                                   | 1.3                       | 2.5                     | 22.5                       | 101.3                          | 674.0                  | 1738.2                           | 125.1                        | -65.8                                         | -70.7                                       | -42.2                                          | -2.2                                               | -6.5                                       | 2.7                                                  | 0.7                                              | 
| Allegany County     | 1979-01-01T00:00:00 | 79721      | 1      | 7    | 18      | 84          | 502  | 1611          | 99        | 2322        | 9.0            | 110                 | 4.7                   | 7.8                          | 2212                  | 95.3                   | 9.0                           | 2912.7                                | 9.3                                       | 138.0                                 | 8.2                                                  | 2774.7                                 | 9.4                                                   | 1.3                       | 8.8                     | 22.6                       | 105.4                          | 629.7                  | 2020.8                           | 124.2                        | 0.3                                           | 251.1                                       | 0.3                                            | 4.0                                                | -6.6                                       | 16.3                                                 | -0.7                                             | 
| Allegany County     | 1980-01-01T00:00:00 | 80461      | 2      | 12   | 26      | 79          | 541  | 1706          | 108       | 2474        | 6.5            | 119                 | 4.8                   | 8.2                          | 2355                  | 95.2                   | 6.5                           | 3074.8                                | 5.6                                       | 147.9                                 | 7.2                                                  | 2926.9                                 | 5.5                                                   | 2.5                       | 14.9                    | 32.3                       | 98.2                           | 672.4                  | 2120.3                           | 134.2                        | 98.2                                          | 69.9                                        | 43.1                                           | -6.8                                               | 6.8                                        | 4.9                                                  | 8.1                                              | 
| Allegany County     | 1981-01-01T00:00:00 | 81781      | 11     | 13   | 24      | 101         | 539  | 1697          | 88        | 2473        | 0.0            | 149                 | 6.0                   | 25.2                         | 2324                  | 94.0                   | -1.3                          | 3023.9                                | -1.7                                      | 182.2                                 | 23.2                                                 | 2841.7                                 | -2.9                                                  | 13.5                      | 15.9                    | 29.3                       | 123.5                          | 659.1                  | 2075.1                           | 107.6                        | 441.1                                         | 6.6                                         | -9.2                                           | 25.8                                               | -2.0                                       | -2.1                                                 | -19.8                                            | 
```