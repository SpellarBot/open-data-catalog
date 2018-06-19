# Violent Crime Statewide Totals by Type

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/violent-crime-statewide-totals-by-type-b725f) |
| Metadata | [Link](https://data.maryland.gov/api/views/wkgc-hy7s) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/wkgc-hy7s/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/wkgc-hy7s/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | wkgc-hy7s |
| Name | Violent Crime Statewide Totals by Type |
| Attribution | MSAC |
| Category | Public Safety |
| Tags | governor's office of performance improvement, violent crime, public safety, homicide, rape, robbery, aggravated assault |
| Created | 2012-04-09T13:08:53Z |
| Publication Date | 2015-01-09T16:02:19Z |

## Description

The data are provided are the Maryland Statistical Analysis Center (MSAC), within the Governor's Office of Crime Control and Prevention (GOCCP). MSAC, in turn, receives these data from the FBI's annual Uniform Crime Reports.

## Columns

```ls
| Included | Schema Type    | Field Name                    | Name                                   | Data Type | Render Type |
| ======== | ============== | ============================= | ====================================== | ========= | =========== |
| Yes      | time           | year                          | YEAR                                   | number    | number      |
| Yes      | numeric metric | homicide                      | HOMICIDE                               | number    | number      |
| Yes      | numeric metric | rape                          | RAPE                                   | number    | number      |
| Yes      | numeric metric | robbery                       | ROBBERY                                | number    | number      |
| Yes      | numeric metric | agg_assault                   | AGG. ASSAULT                           | number    | number      |
| Yes      | numeric metric | b_e                           | B & E                                  | number    | number      |
| Yes      | numeric metric | larceny_theft                 | LARCENY-THEFT                          | number    | number      |
| Yes      | numeric metric | m_v_theft                     | M/V THEFT                              | number    | number      |
| Yes      | numeric metric | grand_total                   | GRAND TOTAL                            | number    | number      |
| Yes      | numeric metric | percent_change                | PERCENT CHANGE                         | percent   | percent     |
| Yes      | numeric metric | violent_crime_total           | VIOLENT CRIME TOTAL                    | number    | number      |
| Yes      | numeric metric | violent_crime_percent         | VIOLENT CRIME PERCENT (OF TOTAL CRIME) | percent   | percent     |
| Yes      | numeric metric | violent_crime_percent_change  | VIOLENT CRIME PERCENT CHANGE           | percent   | percent     |
| Yes      | numeric metric | property_crime_totals         | PROPERTY CRIME TOTALS                  | number    | number      |
| Yes      | numeric metric | property_crime_percent        | PROPERTY CRIME PERCENT                 | percent   | percent     |
| Yes      | numeric metric | property_crime_percent_change | PROPERTY CRIME PERCENT CHANGE          | percent   | percent     |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:wkgc-hy7s d:1975-01-01T00:00:00.000Z m:homicide=435 m:larceny_theft=134001 m:robbery=14104 m:agg_assault=13251 m:b_e=57936 m:m_v_theft=21192 m:violent_crime_percent=12 m:property_crime_totals=213129 m:property_crime_percent=88 m:grand_total=242207 m:violent_crime_total=29078 m:rape=1288

series e:wkgc-hy7s d:1976-01-01T00:00:00.000Z m:property_crime_percent_change=-2.2 m:homicide=352 m:larceny_theft=134337 m:violent_crime_percent_change=-9.7 m:property_crime_percent=88.8 m:violent_crime_total=26248 m:robbery=12247 m:agg_assault=12322 m:b_e=56351 m:m_v_theft=17772 m:percent_change=-3.1 m:violent_crime_percent=11.2 m:property_crime_totals=208460 m:grand_total=234708 m:rape=1327

series e:wkgc-hy7s d:1977-01-01T00:00:00.000Z m:property_crime_percent_change=-0.6 m:homicide=333 m:larceny_theft=131516 m:violent_crime_percent_change=9.4 m:property_crime_percent=87.8 m:violent_crime_total=28716 m:robbery=12088 m:agg_assault=14856 m:b_e=57938 m:m_v_theft=17732 m:percent_change=0.5 m:violent_crime_percent=12.2 m:property_crime_totals=207186 m:grand_total=235902 m:rape=1439
```

## Meta Commands

```ls
metric m:homicide p:integer l:HOMICIDE t:dataTypeName=number

metric m:rape p:integer l:RAPE t:dataTypeName=number

metric m:robbery p:integer l:ROBBERY t:dataTypeName=number

metric m:agg_assault p:integer l:"AGG. ASSAULT" t:dataTypeName=number

metric m:b_e p:integer l:"B & E" t:dataTypeName=number

metric m:larceny_theft p:integer l:LARCENY-THEFT t:dataTypeName=number

metric m:m_v_theft p:integer l:"M/V THEFT" t:dataTypeName=number

metric m:grand_total p:integer l:"GRAND TOTAL" t:dataTypeName=number

metric m:percent_change p:float l:"PERCENT CHANGE" t:dataTypeName=percent

metric m:violent_crime_total p:integer l:"VIOLENT CRIME TOTAL" t:dataTypeName=number

metric m:violent_crime_percent p:float l:"VIOLENT CRIME PERCENT (OF TOTAL CRIME)" t:dataTypeName=percent

metric m:violent_crime_percent_change p:float l:"VIOLENT CRIME PERCENT CHANGE" t:dataTypeName=percent

metric m:property_crime_totals p:integer l:"PROPERTY CRIME TOTALS" t:dataTypeName=number

metric m:property_crime_percent p:float l:"PROPERTY CRIME PERCENT" t:dataTypeName=percent

metric m:property_crime_percent_change p:float l:"PROPERTY CRIME PERCENT CHANGE" t:dataTypeName=percent

entity e:wkgc-hy7s l:"Violent Crime Statewide Totals by Type" t:attribution=MSAC t:url=https://data.maryland.gov/api/views/wkgc-hy7s

property e:wkgc-hy7s t:meta.view v:id=wkgc-hy7s v:category="Public Safety" v:attributionLink=http://www.goccp.maryland.gov/msac/crime-statistics.php v:averageRating=0 v:name="Violent Crime Statewide Totals by Type" v:attribution=MSAC

property e:wkgc-hy7s t:meta.view.license v:name="Public Domain"

property e:wkgc-hy7s t:meta.view.owner v:id=cs6p-bz62 v:profileImageUrlMedium=/api/users/cs6p-bz62/profile_images/THUMB v:profileImageUrlLarge=/api/users/cs6p-bz62/profile_images/LARGE v:screenName="data.maryland.gov Administration" v:profileImageUrlSmall=/api/users/cs6p-bz62/profile_images/TINY v:lastNotificationSeenAt=1491976108 v:displayName="data.maryland.gov Administration"

property e:wkgc-hy7s t:meta.view.tableauthor v:id=cs6p-bz62 v:profileImageUrlMedium=/api/users/cs6p-bz62/profile_images/THUMB v:profileImageUrlLarge=/api/users/cs6p-bz62/profile_images/LARGE v:screenName="data.maryland.gov Administration" v:profileImageUrlSmall=/api/users/cs6p-bz62/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1491976108 v:displayName="data.maryland.gov Administration"
```

## Top Records

```ls
| year | homicide | rape | robbery | agg_assault | b_e   | larceny_theft | m_v_theft | grand_total | percent_change | violent_crime_total | violent_crime_percent | violent_crime_percent_change | property_crime_totals | property_crime_percent | property_crime_percent_change | 
| ==== | ======== | ==== | ======= | =========== | ===== | ============= | ========= | =========== | ============== | =================== | ===================== | ============================ | ===================== | ====================== | ============================= | 
| 1975 | 435      | 1288 | 14104   | 13251       | 57936 | 134001        | 21192     | 242207      |                | 29078               | 12                    |                              | 213129                | 88                     |                               | 
| 1976 | 352      | 1327 | 12247   | 12322       | 56351 | 134337        | 17772     | 234708      | -3.1           | 26248               | 11.2                  | -9.7                         | 208460                | 88.8                   | -2.2                          | 
| 1977 | 333      | 1439 | 12088   | 14856       | 57938 | 131516        | 17732     | 235902      | 0.5            | 28716               | 12.2                  | 9.4                          | 207186                | 87.8                   | -0.6                          | 
| 1978 | 338      | 1476 | 12828   | 15686       | 58901 | 134012        | 17599     | 240840      | 2.1            | 30328               | 12.6                  | 5.6                          | 210512                | 87.4                   | 1.6                           | 
| 1979 | 406      | 1628 | 13745   | 17337       | 62657 | 145278        | 20217     | 261268      | 8.5            | 33116               | 12.7                  | 9.2                          | 228152                | 87.3                   | 8.4                           | 
| 1980 | 399      | 1681 | 16462   | 17182       | 71130 | 152089        | 18885     | 277828      | 6.3            | 35724               | 12.9                  | 7.9                          | 242104                | 87.1                   | 6.1                           | 
| 1981 | 422      | 1663 | 18095   | 17691       | 70762 | 152544        | 18486     | 279663      | 0.7            | 37871               | 13.5                  | 6                            | 241792                | 86.5                   | -0.1                          | 
| 1982 | 431      | 1596 | 15377   | 18845       | 60547 | 142903        | 16719     | 256418      | -8.3           | 36249               | 14.1                  | -4.3                         | 220169                | 85.9                   | -8.9                          | 
| 1983 | 367      | 1412 | 14950   | 18007       | 52697 | 127443        | 15688     | 230564      | -10.1          | 34736               | 15.1                  | -4.2                         | 195828                | 84.9                   | -11.1                         | 
| 1984 | 354      | 1644 | 13113   | 19369       | 51498 | 123625        | 17284     | 226887      | -1.6           | 34480               | 15.2                  | -0.7                         | 192407                | 84.8                   | -1.7                          | 
```