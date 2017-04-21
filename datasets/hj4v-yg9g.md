# Violent Crime & Property Crime Statewide Totals: 2006 to Present

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/violent-crime-property-crime-statewide-totals-2006-to-present) |
| Metadata | [Link](https://data.maryland.gov/api/views/hj4v-yg9g) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/hj4v-yg9g/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/hj4v-yg9g/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | hj4v-yg9g |
| Name | Violent Crime & Property Crime Statewide Totals: 2006 to Present |
| Attribution | GOCCP (Governor's Office of Crime Control and Prevention) |
| Category | Public Safety |
| Tags | violent crime, public safety, homicide, rape, robbery, aggravated assault, goccp |
| Created | 2016-02-19T17:14:20Z |
| Publication Date | 2017-03-09T15:09:09Z |

## Description

This dataset shows Maryland crime versus all other states. The data are provided are the Maryland Statistical Analysis Center (MSAC), within the Governor's Office of Crime Control and Prevention (GOCCP). MSAC, in turn, receives these data from the FBI's annual Uniform Crime Reports.

## Columns

```ls
| Included | Schema Type    | Field Name                                            | Name                                                  | Data Type     | Render Type   |
| ======== | ============== | ===================================================== | ===================================================== | ============= | ============= |
| Yes      | series tag     | jurisdiction                                          | JURISDICTION                                          | text          | text          |
| Yes      | time           | year                                                  | YEAR                                                  | calendar_date | calendar_date |
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
series e:hj4v-yg9g d:2007-01-01T00:00:00.000Z t:jurisdiction=Alabama m:property_crime_rate_per_100_000_people=3971.6 m:larceny_theft_rate_percent_change_per_100_000_people=1.5 m:robbery_per_100_000_people=159.9 m:b_e_per_100_000_people=979.5 m:m_v_theft_rate_percent_change_per_100_000_people=-4.7 m:violent_crime_rate_per_100_000_people=448 m:murder_rate_percent_change_per_100_000_people=7.2 m:agg_assault_rate_percent_change_per_100_000_people=8 m:overall_percent_change_per_100_000_people=1.3 m:b_e_rate_percent_change_per_100_000_people=1.1 m:property_crime_rate_percent_change_per_100_000_people=0.9 m:agg_assault_per_100_000_people=245.8 m:murder_per_100_000_people=8.9 m:larceny_theft_per_100_000_people=2684.6 m:m_v_theft_per_100_000_people=307.5 m:rape_per_100_000_people=33.4 m:violent_crime_rate_percent_change_per_100_000_people=5.4 m:robbery_rate_percent_change_per_100_000_people=4.2 m:rape_rate_percent_change_per_100_000_people=-7 m:overall_crime_rate_per_100_000_people=4419.6

series e:hj4v-yg9g d:2008-01-01T00:00:00.000Z t:jurisdiction=Alabama m:property_crime_rate_per_100_000_people=4082.9 m:larceny_theft_rate_percent_change_per_100_000_people=0.7 m:robbery_per_100_000_people=157 m:b_e_per_100_000_people=1077.1 m:m_v_theft_rate_percent_change_per_100_000_people=-1.7 m:violent_crime_rate_per_100_000_people=452.8 m:murder_rate_percent_change_per_100_000_people=-14.6 m:agg_assault_rate_percent_change_per_100_000_people=2.6 m:overall_percent_change_per_100_000_people=2.6 m:b_e_rate_percent_change_per_100_000_people=10 m:property_crime_rate_percent_change_per_100_000_people=2.8 m:agg_assault_per_100_000_people=252.1 m:murder_per_100_000_people=7.6 m:larceny_theft_per_100_000_people=2703.6 m:m_v_theft_per_100_000_people=302.2 m:rape_per_100_000_people=34.6 m:violent_crime_rate_percent_change_per_100_000_people=1.1 m:robbery_rate_percent_change_per_100_000_people=-1.8 m:rape_rate_percent_change_per_100_000_people=3.6 m:overall_crime_rate_per_100_000_people=4535.7

series e:hj4v-yg9g d:2009-01-01T00:00:00.000Z t:jurisdiction=Alabama m:property_crime_rate_per_100_000_people=3772.4 m:larceny_theft_rate_percent_change_per_100_000_people=-7.5 m:robbery_per_100_000_people=132.9 m:b_e_per_100_000_people=1037.2 m:m_v_theft_rate_percent_change_per_100_000_people=-22.1 m:violent_crime_rate_per_100_000_people=449.8 m:murder_rate_percent_change_per_100_000_people=-9.2 m:agg_assault_rate_percent_change_per_100_000_people=10.3 m:overall_percent_change_per_100_000_people=-6.9 m:b_e_rate_percent_change_per_100_000_people=-3.7 m:property_crime_rate_percent_change_per_100_000_people=-7.6 m:agg_assault_per_100_000_people=278.1 m:murder_per_100_000_people=6.9 m:larceny_theft_per_100_000_people=2499.9 m:m_v_theft_per_100_000_people=235.3 m:rape_per_100_000_people=31.9 m:violent_crime_rate_percent_change_per_100_000_people=-0.7 m:robbery_rate_percent_change_per_100_000_people=-15.4 m:rape_rate_percent_change_per_100_000_people=-7.8 m:overall_crime_rate_per_100_000_people=4222.2
```

## Meta Commands

```ls
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

metric m:murder_rate_percent_change_per_100_000_people p:float l:"MURDER RATE PERCENT CHANGE PER 100,000 PEOPLE" t:dataTypeName=percent

metric m:rape_rate_percent_change_per_100_000_people p:float l:"RAPE RATE PERCENT CHANGE PER 100,000 PEOPLE" t:dataTypeName=percent

metric m:robbery_rate_percent_change_per_100_000_people p:float l:"ROBBERY RATE PERCENT CHANGE PER 100,000 PEOPLE" t:dataTypeName=percent

metric m:agg_assault_rate_percent_change_per_100_000_people p:float l:"AGG. ASSAULT RATE PERCENT CHANGE PER 100,000 PEOPLE" t:dataTypeName=percent

metric m:b_e_rate_percent_change_per_100_000_people p:float l:"B & E RATE PERCENT CHANGE PER 100,000 PEOPLE" t:dataTypeName=percent

metric m:larceny_theft_rate_percent_change_per_100_000_people p:float l:"LARCENY THEFT RATE PERCENT CHANGE PER 100,000 PEOPLE" t:dataTypeName=percent

metric m:m_v_theft_rate_percent_change_per_100_000_people p:float l:"M/V THEFT RATE PERCENT CHANGE PER 100,000 PEOPLE" t:dataTypeName=percent

entity e:hj4v-yg9g l:"Violent Crime & Property Crime Statewide Totals: 2006 to Present" t:attribution="GOCCP (Governor's Office of Crime Control and Prevention)" t:url=https://data.maryland.gov/api/views/hj4v-yg9g

property e:hj4v-yg9g t:meta.view v:id=hj4v-yg9g v:category="Public Safety" v:attributionLink=http://www.goccp.maryland.gov/msac/crime-statistics.php v:averageRating=0 v:name="Violent Crime & Property Crime Statewide Totals: 2006 to Present" v:attribution="GOCCP (Governor's Office of Crime Control and Prevention)"

property e:hj4v-yg9g t:meta.view.license v:name="Public Domain"

property e:hj4v-yg9g t:meta.view.owner v:id=cs6p-bz62 v:profileImageUrlMedium=/api/users/cs6p-bz62/profile_images/THUMB v:profileImageUrlLarge=/api/users/cs6p-bz62/profile_images/LARGE v:screenName="data.maryland.gov Administration" v:profileImageUrlSmall=/api/users/cs6p-bz62/profile_images/TINY v:lastNotificationSeenAt=1491976108 v:displayName="data.maryland.gov Administration"

property e:hj4v-yg9g t:meta.view.tableauthor v:id=cs6p-bz62 v:profileImageUrlMedium=/api/users/cs6p-bz62/profile_images/THUMB v:profileImageUrlLarge=/api/users/cs6p-bz62/profile_images/LARGE v:screenName="data.maryland.gov Administration" v:profileImageUrlSmall=/api/users/cs6p-bz62/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1491976108 v:displayName="data.maryland.gov Administration"
```

## Top Records

```ls
| jurisdiction | year                | overall_crime_rate_per_100_000_people | overall_percent_change_per_100_000_people | violent_crime_rate_per_100_000_people | violent_crime_rate_percent_change_per_100_000_people | property_crime_rate_per_100_000_people | property_crime_rate_percent_change_per_100_000_people | murder_per_100_000_people | rape_per_100_000_people | robbery_per_100_000_people | agg_assault_per_100_000_people | b_e_per_100_000_people | larceny_theft_per_100_000_people | m_v_theft_per_100_000_people | murder_rate_percent_change_per_100_000_people | rape_rate_percent_change_per_100_000_people | robbery_rate_percent_change_per_100_000_people | agg_assault_rate_percent_change_per_100_000_people | b_e_rate_percent_change_per_100_000_people | larceny_theft_rate_percent_change_per_100_000_people | m_v_theft_rate_percent_change_per_100_000_people | 
| ============ | =================== | ===================================== | ========================================= | ===================================== | ==================================================== | ====================================== | ===================================================== | ========================= | ======================= | ========================== | ============================== | ====================== | ================================ | ============================ | ============================================= | =========================================== | ============================================== | ================================================== | ========================================== | ==================================================== | ================================================ | 
| Alabama      | 2007-01-01T00:00:00 | 4419.6                                | 1.3                                       | 448.0                                 | 5.4                                                  | 3971.6                                 | 0.9                                                   | 8.9                       | 33.4                    | 159.9                      | 245.8                          | 979.5                  | 2684.6                           | 307.5                        | 7.2                                           | -7.0                                        | 4.2                                            | 8.0                                                | 1.1                                        | 1.5                                                  | -4.7                                             | 
| Alabama      | 2008-01-01T00:00:00 | 4535.7                                | 2.6                                       | 452.8                                 | 1.1                                                  | 4082.9                                 | 2.8                                                   | 7.6                       | 34.6                    | 157.0                      | 252.1                          | 1077.1                 | 2703.6                           | 302.2                        | -14.6                                         | 3.6                                         | -1.8                                           | 2.6                                                | 10.0                                       | 0.7                                                  | -1.7                                             | 
| Alabama      | 2009-01-01T00:00:00 | 4222.2                                | -6.9                                      | 449.8                                 | -0.7                                                 | 3772.4                                 | -7.6                                                  | 6.9                       | 31.9                    | 132.9                      | 278.1                          | 1037.2                 | 2499.9                           | 235.3                        | -9.2                                          | -7.8                                        | -15.4                                          | 10.3                                               | -3.7                                       | -7.5                                                 | -22.1                                            | 
| Alabama      | 2011-01-01T00:00:00 | 4026.2                                | 3.4                                       | 420.1                                 | 11.2                                                 | 3606.1                                 | 2.5                                                   | 6.3                       | 28.5                    | 102.2                      | 283.0                          | 1064.3                 | 2319.7                           | 222.1                        | 10.5                                          | 1.1                                         | 2.6                                            | 15.9                                               | 21.0                                       | -4.0                                                 | 0.1                                              | 
| Alabama      | 2012-01-01T00:00:00 | 3952.1                                | -1.8                                      | 449.9                                 | 7.1                                                  | 3502.2                                 | -2.9                                                  | 7.1                       | 26.9                    | 104.2                      | 312.1                          | 985.6                  | 2314.9                           | 201.7                        | 12.7                                          | -5.6                                        | 2.0                                            | 10.3                                               | -7.4                                       | -0.2                                                 | -9.2                                             | 
| Alabama      | 2013-01-01T00:00:00 | 3782.1                                | -4.3                                      | 430.8                                 | -4.2                                                 | 3351.3                                 | -4.3                                                  | 7.2                       | 29.5                    | 96.2                       | 285.1                          | 877.8                  | 2254.8                           | 218.7                        | 1.4                                           | 9.7                                         | -7.7                                           | -8.7                                               | -10.9                                      | -2.6                                                 | 8.4                                              | 
| Alabama      | 2014-01-01T00:00:00 | 3605.0                                | -4.7                                      | 427.4                                 | -0.8                                                 | 3177.6                                 | -5.2                                                  | 5.7                       | 29.6                    | 96.9                       | 283.4                          | 819.0                  | 2149.5                           | 209.1                        | -20.8                                         | 0.3                                         | 0.7                                            | -0.6                                               | -6.7                                       | -4.7                                                 | -4.4                                             | 
| Alabama      | 2015-01-01T00:00:00 | 3451.4                                | -4.3                                      | 472.4                                 | 10.5                                                 | 2979.0                                 | -6.3                                                  | 7.2                       | 42.0                    | 94.9                       | 328.3                          | 725.6                  | 2040.7                           | 212.7                        | 26.3                                          | 41.9                                        | -2.1                                           | 15.8                                               | -11.4                                      | -5.1                                                 | 1.7                                              | 
| Alaska       | 2006-01-01T00:00:00 | 4292.9                                | 24.4                                      | 688.0                                 |                                                      | 3604.9                                 |                                                       | 5.4                       | 76.0                    | 90.3                       | 516.4                          | 617.3                  | 2610.2                           | 377.4                        |                                               |                                             |                                                |                                                    |                                            |                                                      |                                                  | 
| Alaska       | 2007-01-01T00:00:00 | 4040.7                                | -5.9                                      | 661.2                                 | -3.9                                                 | 3379.5                                 | -6.3                                                  | 6.4                       | 77.4                    | 85.3                       | 492.0                          | 538.7                  | 2247.0                           | 593.8                        | 18.5                                          | 1.8                                         | -5.5                                           | -4.7                                               | -12.7                                      | -13.9                                                | 57.3                                             | 
```