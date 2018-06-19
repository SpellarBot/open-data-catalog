# Uniform Crime Reporting Statistics - 2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/uniform-crime-reporting-statistics-2012) |
| Metadata | [Link](https://data.ct.gov/api/views/e7pk-v6dc) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/e7pk-v6dc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/e7pk-v6dc/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | e7pk-v6dc |
| Name | Uniform Crime Reporting Statistics - 2012 |
| Category | Public Safety |
| Tags | http://www.ucrdatatool.gov/ |
| Created | 2014-03-31T18:23:08Z |
| Publication Date | 2014-04-01T19:20:59Z |

## Description

A data extract of crime in Connecticut, by reporting agency from Uniform Crime Reporting Statistics - UCR Data Online.
The UCR Program collects statistics on violent crime (murder and nonnegligent manslaughter, forcible rape, robbery, and aggravated assault) and property crime (burglary, larceny-theft, and motor vehicle theft).
Notes: When data are unavailable, the cells are blank or the year is not presented. 
Variations in population coverage and reporting practices may cause differences in reporting from year to year. (See definitions)
MSA and non-MSA county populations are not available.
Rates are the number of reported offenses per 100,000 population.
Crime rates are not available for agencies that report data for less than 12 months of a year.
Sources: FBI, Uniform Crime Reports, prepared by the National Archive of Criminal Justice Data

## Columns

```ls
| Included | Schema Type    | Field Name                                | Name                                      | Data Type | Render Type |
| ======== | ============== | ========================================= | ========================================= | ========= | =========== |
| Yes      | series tag     | agency                                    | Agency                                    | text      | text        |
| Yes      | numeric metric | months                                    | Months                                    | number    | number      |
| Yes      | numeric metric | population                                | Population                                | number    | number      |
| Yes      | numeric metric | violent_crime_total                       | Violent crime total                       | number    | number      |
| Yes      | numeric metric | murder_and_nonnegligent_manslaughter      | Murder and nonnegligent Manslaughter      | number    | number      |
| Yes      | numeric metric | forcible_rape                             | Forcible rape                             | number    | number      |
| Yes      | numeric metric | robbery                                   | Robbery                                   | number    | number      |
| Yes      | numeric metric | aggravated_assault                        | Aggravated assault                        | number    | number      |
| Yes      | numeric metric | property_crime_total                      | Property crime total                      | number    | number      |
| Yes      | numeric metric | burglary                                  | Burglary                                  | number    | number      |
| Yes      | numeric metric | larceny_theft                             | Larceny-theft                             | number    | number      |
| Yes      | numeric metric | motor_vehicle_theft                       | Motor vehicle theft                       | number    | number      |
| Yes      | numeric metric | violent_crime_rate                        | Violent Crime rate                        | number    | number      |
| Yes      | numeric metric | murder_and_nonnegligent_manslaughter_rate | Murder and nonnegligent manslaughter rate | number    | number      |
| Yes      | numeric metric | forcible_rape_rate                        | Forcible rape rate                        | number    | number      |
| Yes      | numeric metric | robbery_rate                              | Robbery rate                              | number    | number      |
| Yes      | numeric metric | aggravated_assault_rate                   | Aggravated assault rate                   | number    | number      |
| Yes      | numeric metric | property_crime_rate                       | Property crime rate                       | number    | number      |
| Yes      | numeric metric | burglary_rate                             | Burglary rate                             | number    | number      |
| Yes      | numeric metric | larceny_theft_rate                        | Larceny-theft rate                        | number    | number      |
| Yes      | numeric metric | motor_vehicle_theft_rate                  | Motor vehicle theft rate                  | number    | number      |
```

## Time Field

```ls
Value = 2012
Format & Zone = yyyy
```

## Data Commands

```ls
series e:e7pk-v6dc d:2012-01-01T00:00:00.000Z t:agency="Simsbury Police Dept" m:aggravated_assault_rate=17 m:larceny_theft=147 m:aggravated_assault=4 m:murder_and_nonnegligent_manslaughter=1 m:violent_crime_rate=29.7 m:robbery_rate=8.5 m:violent_crime_total=7 m:murder_and_nonnegligent_manslaughter_rate=4.2 m:property_crime_total=176 m:larceny_theft_rate=623.1 m:property_crime_rate=746 m:months=12 m:robbery=2 m:forcible_rape=0 m:burglary_rate=106 m:burglary=25 m:motor_vehicle_theft_rate=17 m:motor_vehicle_theft=4 m:forcible_rape_rate=0 m:population=23591

series e:e7pk-v6dc d:2012-01-01T00:00:00.000Z t:agency="Coventry Police Dept" m:aggravated_assault_rate=0 m:larceny_theft=101 m:aggravated_assault=0 m:murder_and_nonnegligent_manslaughter=0 m:violent_crime_rate=16.1 m:robbery_rate=0 m:violent_crime_total=2 m:murder_and_nonnegligent_manslaughter_rate=0 m:property_crime_total=170 m:larceny_theft_rate=811.2 m:property_crime_rate=1365.4 m:months=12 m:robbery=0 m:forcible_rape=2 m:burglary_rate=538.1 m:burglary=67 m:motor_vehicle_theft_rate=16.1 m:motor_vehicle_theft=2 m:forcible_rape_rate=16.1 m:population=12451

series e:e7pk-v6dc d:2012-01-01T00:00:00.000Z t:agency="Waterbury Police Dept" m:aggravated_assault_rate=118.6 m:larceny_theft=3538 m:aggravated_assault=131 m:murder_and_nonnegligent_manslaughter=5 m:violent_crime_rate=296.9 m:robbery_rate=167.4 m:violent_crime_total=328 m:murder_and_nonnegligent_manslaughter_rate=4.5 m:property_crime_total=4713 m:larceny_theft_rate=3202.2 m:property_crime_rate=4265.7 m:months=12 m:robbery=185 m:forcible_rape=7 m:burglary_rate=599.2 m:burglary=662 m:motor_vehicle_theft_rate=464.3 m:motor_vehicle_theft=513 m:forcible_rape_rate=6.3 m:population=110486
```

## Meta Commands

```ls
metric m:months p:integer l:Months t:dataTypeName=number

metric m:population p:integer l:Population t:dataTypeName=number

metric m:violent_crime_total p:integer l:"Violent crime total" t:dataTypeName=number

metric m:murder_and_nonnegligent_manslaughter p:integer l:"Murder and nonnegligent Manslaughter" t:dataTypeName=number

metric m:forcible_rape p:integer l:"Forcible rape" t:dataTypeName=number

metric m:robbery p:integer l:Robbery t:dataTypeName=number

metric m:aggravated_assault p:integer l:"Aggravated assault" t:dataTypeName=number

metric m:property_crime_total p:integer l:"Property crime total" t:dataTypeName=number

metric m:burglary p:integer l:Burglary t:dataTypeName=number

metric m:larceny_theft p:integer l:Larceny-theft t:dataTypeName=number

metric m:motor_vehicle_theft p:integer l:"Motor vehicle theft" t:dataTypeName=number

metric m:violent_crime_rate p:float l:"Violent Crime rate" t:dataTypeName=number

metric m:murder_and_nonnegligent_manslaughter_rate p:float l:"Murder and nonnegligent manslaughter rate" t:dataTypeName=number

metric m:forcible_rape_rate p:float l:"Forcible rape rate" t:dataTypeName=number

metric m:robbery_rate p:float l:"Robbery rate" t:dataTypeName=number

metric m:aggravated_assault_rate p:float l:"Aggravated assault rate" t:dataTypeName=number

metric m:property_crime_rate p:float l:"Property crime rate" t:dataTypeName=number

metric m:burglary_rate p:float l:"Burglary rate" t:dataTypeName=number

metric m:larceny_theft_rate p:float l:"Larceny-theft rate" t:dataTypeName=number

metric m:motor_vehicle_theft_rate p:float l:"Motor vehicle theft rate" t:dataTypeName=number

entity e:e7pk-v6dc l:"Uniform Crime Reporting Statistics - 2012" t:url=https://data.ct.gov/api/views/e7pk-v6dc

property e:e7pk-v6dc t:meta.view v:id=e7pk-v6dc v:category="Public Safety" v:attributionLink=http://www.ucrdatatool.gov/ v:averageRating=0 v:name="Uniform Crime Reporting Statistics - 2012"

property e:e7pk-v6dc t:meta.view.license v:name="Public Domain"

property e:e7pk-v6dc t:meta.view.owner v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"

property e:e7pk-v6dc t:meta.view.tableauthor v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:roleName=administrator v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"
```

## Top Records

```ls
| agency                      | months | population | violent_crime_total | murder_and_nonnegligent_manslaughter | forcible_rape | robbery | aggravated_assault | property_crime_total | burglary | larceny_theft | motor_vehicle_theft | violent_crime_rate | murder_and_nonnegligent_manslaughter_rate | forcible_rape_rate | robbery_rate | aggravated_assault_rate | property_crime_rate | burglary_rate | larceny_theft_rate | motor_vehicle_theft_rate | 
| =========================== | ====== | ========== | =================== | ==================================== | ============= | ======= | ================== | ==================== | ======== | ============= | =================== | ================== | ========================================= | ================== | ============ | ======================= | =================== | ============= | ================== | ======================== | 
| Simsbury Police Dept        | 12     | 23591      | 7                   | 1                                    | 0             | 2       | 4                  | 176                  | 25       | 147           | 4                   | 29.7               | 4.2                                       | 0                  | 8.5          | 17                      | 746                 | 106           | 623.1              | 17                       | 
| Coventry Police Dept        | 12     | 12451      | 2                   | 0                                    | 2             | 0       | 0                  | 170                  | 67       | 101           | 2                   | 16.1               | 0                                         | 16.1               | 0            | 0                       | 1365.4              | 538.1         | 811.2              | 16.1                     | 
| Waterbury Police Dept       | 12     | 110486     | 328                 | 5                                    | 7             | 185     | 131                | 4713                 | 662      | 3538          | 513                 | 296.9              | 4.5                                       | 6.3                | 167.4        | 118.6                   | 4265.7              | 599.2         | 3202.2             | 464.3                    | 
| Bristol Police Dept         | 12     | 60688      | 93                  | 3                                    | 9             | 51      | 30                 | 1590                 | 355      | 1123          | 112                 | 153.2              | 4.9                                       | 14.8               | 84           | 49.4                    | 2620                | 585           | 1850.4             | 184.6                    | 
| Avon Police Dept            | 12     | 18162      | 5                   | 0                                    | 2             | 2       | 1                  | 169                  | 25       | 143           | 1                   | 27.5               | 0                                         | 11                 | 11           | 5.5                     | 930.5               | 137.7         | 787.4              | 5.5                      | 
| Orange Police Dept          | 12     | 13971      | 7                   | 0                                    | 2             | 5       | 0                  | 376                  | 33       | 332           | 11                  | 50.1               | 0                                         | 14.3               | 35.8         | 0                       | 2691.3              | 236.2         | 2376.4             | 78.7                     | 
| Wolcott Police Dept         | 12     | 16697      | 6                   | 0                                    | 1             | 5       | 0                  | 318                  | 78       | 226           | 14                  | 35.9               | 0                                         | 6                  | 29.9         | 0                       | 1904.5              | 467.1         | 1353.5             | 83.8                     | 
| Cheshire Police Dept        | 12     | 29295      | 4                   | 0                                    | 0             | 4       | 0                  | 265                  | 48       | 210           | 7                   | 13.7               | 0                                         | 0                  | 13.7         | 0                       | 904.6               | 163.9         | 716.8              | 23.9                     | 
| Winchester Town Police Dept | 12     | 11205      | 15                  | 0                                    | 2             | 4       | 9                  | 253                  | 81       | 161           | 11                  | 133.9              | 0                                         | 17.8               | 35.7         | 80.3                    | 2257.9              | 722.9         | 1436.9             | 98.2                     | 
| Wallingford Police Dept     | 12     | 45183      | 15                  | 0                                    | 2             | 10      | 3                  | 914                  | 161      | 728           | 25                  | 33.2               | 0                                         | 4.4                | 22.1         | 6.6                     | 2022.9              | 356.3         | 1611.2             | 55.3                     | 
```