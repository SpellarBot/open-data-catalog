# Maryland Farmland in Acres, Change in Farmland Acreage and Percent Change

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/maryland-farmland-in-acres-change-in-farmland-acreage-and-percent-change-02eba) |
| Metadata | [Link](https://data.maryland.gov/api/views/xwfr-g3qg) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/xwfr-g3qg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/xwfr-g3qg/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | xwfr-g3qg |
| Name | Maryland Farmland in Acres, Change in Farmland Acreage and Percent Change |
| Attribution | Maryland Department of Planning |
| Tags | farmland, acreage, agriculture census, mdp |
| Created | 2014-08-27T21:39:31Z |
| Publication Date | 2014-08-27T21:43:55Z |

## Description

Acreage of Farmland in Maryland, Change in acreage of farmland in Maryland and percent change of farmland acreage. 1997, 2002, 2007 and 2012 Census of Agriculture

## Columns

```ls
| Included | Schema Type    | Field Name                          | Name                                 | Data Type     | Render Type   |
| ======== | ============== | =================================== | ==================================== | ============= | ============= |
| Yes      | time           | date_created                        | Date created                         | calendar_date | calendar_date |
| Yes      | series tag     | year                                | Year                                 | text          | text          |
| Yes      | numeric metric | number_of_acres_in_farmland_1987    | Number of Acres in Farmland, 1987    | number        | number        |
| Yes      | numeric metric | number_of_acres_in_farmland_1992    | Number of Acres in Farmland, 1992    | number        | number        |
| Yes      | numeric metric | number_of_acres_in_farmland_1997    | Number of Acres in Farmland, 1997    | number        | number        |
| Yes      | numeric metric | number_of_acres_in_farmland_2002    | Number of Acres in Farmland, 2002    | number        | number        |
| Yes      | numeric metric | number_of_acres_in_farmland_2007    | Number of Acres in Farmland, 2007    | number        | number        |
| Yes      | numeric metric | number_of_acres_in_farmland_2012    | Number of Acres in Farmland, 2012    | number        | number        |
| Yes      | numeric metric | change_in_number_of_acres_1987_1992 | Change in Number of Acres, 1987-1992 | number        | number        |
| Yes      | numeric metric | change_in_number_of_acres_1992_1997 | Change in Number of Acres, 1992-1997 | number        | number        |
| Yes      | numeric metric | change_in_number_of_acres_1997_2002 | Change in Number of Acres, 1997-2002 | number        | number        |
| Yes      | numeric metric | change_in_number_of_acres_2002_2007 | Change in Number of Acres, 2002-2007 | number        | number        |
| Yes      | numeric metric | change_in_number_of_acres_2007_2012 | Change in Number of Acres, 2007-2012 | number        | number        |
| Yes      | numeric metric | percent_change_in_acres_1987_1992   | Percent Change in Acres, 1987-1992   | percent       | percent       |
| Yes      | numeric metric | percent_change_in_acres_1992_1997   | Percent Change in Acres, 1992-1997   | percent       | percent       |
| Yes      | numeric metric | percent_change_in_acres_1997_2002   | Percent Change in Acres, 1997-2002   | percent       | percent       |
| Yes      | numeric metric | percent_change_in_acres_2002_2007   | Percent Change in Acres, 2002-2007   | percent       | percent       |
| Yes      | numeric metric | percent_change_in_acres_2007_2012   | Percent Change in Acres, 2007-2012   | percent       | percent       |
| Yes      | numeric metric | change_in_number_of_acres_1987_2012 | Change in Number of Acres, 1987-2012 | number        | number        |
| Yes      | numeric metric | percent_change_in_acres_1987_2012   | Percent Change in Acres, 1987-2012   | percent       | percent       |
```

## Time Field

```ls
Value = date_created
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:xwfr-g3qg d:2014-08-27T00:00:00.000Z t:year=MARYLAND m:percent_change_in_acres_1997_2002=-5.3 m:change_in_number_of_acres_2002_2007=-25874 m:percent_change_in_acres_2002_2007=-1.2 m:number_of_acres_in_farmland_1997=2193063 m:percent_change_in_acres_1987_2012=-15.3 m:number_of_acres_in_farmland_1992=2223476 m:number_of_acres_in_farmland_1987=2396629 m:change_in_number_of_acres_2007_2012=-21011 m:change_in_number_of_acres_1997_2002=-115433 m:percent_change_in_acres_1987_1992=-7.2 m:percent_change_in_acres_2007_2012=-1 m:number_of_acres_in_farmland_2007=2051756 m:change_in_number_of_acres_1987_2012=-365884 m:change_in_number_of_acres_1992_1997=-30413 m:number_of_acres_in_farmland_2002=2077630 m:change_in_number_of_acres_1987_1992=-173153 m:number_of_acres_in_farmland_2012=2030745 m:percent_change_in_acres_1992_1997=-1.4

series e:xwfr-g3qg d:2014-08-27T00:00:00.000Z t:year="Allegany County" m:percent_change_in_acres_1997_2002=-10.4 m:change_in_number_of_acres_2002_2007=-2736 m:percent_change_in_acres_2002_2007=-6.9 m:number_of_acres_in_farmland_1997=43944 m:percent_change_in_acres_1987_2012=-25.9 m:number_of_acres_in_farmland_1992=37802 m:number_of_acres_in_farmland_1987=48941 m:change_in_number_of_acres_2007_2012=-382 m:change_in_number_of_acres_1997_2002=-4565 m:percent_change_in_acres_1987_1992=-22.8 m:percent_change_in_acres_2007_2012=-1 m:number_of_acres_in_farmland_2007=36643 m:change_in_number_of_acres_1987_2012=-12680 m:change_in_number_of_acres_1992_1997=6142 m:number_of_acres_in_farmland_2002=39379 m:change_in_number_of_acres_1987_1992=-11139 m:number_of_acres_in_farmland_2012=36261 m:percent_change_in_acres_1992_1997=16.2

series e:xwfr-g3qg d:2014-08-27T00:00:00.000Z t:year="Anne Arundel County" m:percent_change_in_acres_1997_2002=-3.3 m:change_in_number_of_acres_2002_2007=-5974 m:percent_change_in_acres_2002_2007=-17 m:number_of_acres_in_farmland_1997=36438 m:percent_change_in_acres_1987_2012=-33.7 m:number_of_acres_in_farmland_1992=43320 m:number_of_acres_in_farmland_1987=42413 m:change_in_number_of_acres_2007_2012=-1133 m:change_in_number_of_acres_1997_2002=-1220 m:percent_change_in_acres_1987_1992=2.1 m:percent_change_in_acres_2007_2012=-3.9 m:number_of_acres_in_farmland_2007=29244 m:change_in_number_of_acres_1987_2012=-14302 m:change_in_number_of_acres_1992_1997=-6882 m:number_of_acres_in_farmland_2002=35218 m:change_in_number_of_acres_1987_1992=907 m:number_of_acres_in_farmland_2012=28111 m:percent_change_in_acres_1992_1997=-15.9
```

## Meta Commands

```ls
metric m:number_of_acres_in_farmland_1987 p:integer l:"Number of Acres in Farmland, 1987" t:dataTypeName=number

metric m:number_of_acres_in_farmland_1992 p:integer l:"Number of Acres in Farmland, 1992" t:dataTypeName=number

metric m:number_of_acres_in_farmland_1997 p:integer l:"Number of Acres in Farmland, 1997" t:dataTypeName=number

metric m:number_of_acres_in_farmland_2002 p:integer l:"Number of Acres in Farmland, 2002" t:dataTypeName=number

metric m:number_of_acres_in_farmland_2007 p:integer l:"Number of Acres in Farmland, 2007" t:dataTypeName=number

metric m:number_of_acres_in_farmland_2012 p:integer l:"Number of Acres in Farmland, 2012" t:dataTypeName=number

metric m:change_in_number_of_acres_1987_1992 p:integer l:"Change in Number of Acres, 1987-1992" t:dataTypeName=number

metric m:change_in_number_of_acres_1992_1997 p:integer l:"Change in Number of Acres, 1992-1997" t:dataTypeName=number

metric m:change_in_number_of_acres_1997_2002 p:integer l:"Change in Number of Acres, 1997-2002" t:dataTypeName=number

metric m:change_in_number_of_acres_2002_2007 p:integer l:"Change in Number of Acres, 2002-2007" t:dataTypeName=number

metric m:change_in_number_of_acres_2007_2012 p:integer l:"Change in Number of Acres, 2007-2012" t:dataTypeName=number

metric m:percent_change_in_acres_1987_1992 p:float l:"Percent Change in Acres, 1987-1992" t:dataTypeName=percent

metric m:percent_change_in_acres_1992_1997 p:float l:"Percent Change in Acres, 1992-1997" t:dataTypeName=percent

metric m:percent_change_in_acres_1997_2002 p:float l:"Percent Change in Acres, 1997-2002" t:dataTypeName=percent

metric m:percent_change_in_acres_2002_2007 p:float l:"Percent Change in Acres, 2002-2007" t:dataTypeName=percent

metric m:percent_change_in_acres_2007_2012 p:float l:"Percent Change in Acres, 2007-2012" t:dataTypeName=percent

metric m:change_in_number_of_acres_1987_2012 p:integer l:"Change in Number of Acres, 1987-2012" t:dataTypeName=number

metric m:percent_change_in_acres_1987_2012 p:float l:"Percent Change in Acres, 1987-2012" t:dataTypeName=percent

entity e:xwfr-g3qg l:"Maryland Farmland in Acres, Change in Farmland Acreage and Percent Change" t:attribution="Maryland Department of Planning" t:url=https://data.maryland.gov/api/views/xwfr-g3qg

property e:xwfr-g3qg t:meta.view v:id=xwfr-g3qg v:attributionLink=http://planning.maryland.gov/msdc/S6_Econ_Agri_Census.shtml v:averageRating=0 v:name="Maryland Farmland in Acres, Change in Farmland Acreage and Percent Change" v:attribution="Maryland Department of Planning"

property e:xwfr-g3qg t:meta.view.owner v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:displayName=MDP

property e:xwfr-g3qg t:meta.view.tableauthor v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:roleName=editor v:displayName=MDP
```

## Top Records

```ls
| date_created        | year                | number_of_acres_in_farmland_1987 | number_of_acres_in_farmland_1992 | number_of_acres_in_farmland_1997 | number_of_acres_in_farmland_2002 | number_of_acres_in_farmland_2007 | number_of_acres_in_farmland_2012 | change_in_number_of_acres_1987_1992 | change_in_number_of_acres_1992_1997 | change_in_number_of_acres_1997_2002 | change_in_number_of_acres_2002_2007 | change_in_number_of_acres_2007_2012 | percent_change_in_acres_1987_1992 | percent_change_in_acres_1992_1997 | percent_change_in_acres_1997_2002 | percent_change_in_acres_2002_2007 | percent_change_in_acres_2007_2012 | change_in_number_of_acres_1987_2012 | percent_change_in_acres_1987_2012 | 
| =================== | =================== | ================================ | ================================ | ================================ | ================================ | ================================ | ================================ | =================================== | =================================== | =================================== | =================================== | =================================== | ================================= | ================================= | ================================= | ================================= | ================================= | =================================== | ================================= | 
| 2014-08-27T00:00:00 | MARYLAND            | 2396629                          | 2223476                          | 2193063                          | 2077630                          | 2051756                          | 2030745                          | -173153                             | -30413                              | -115433                             | -25874                              | -21011                              | -7.2                              | -1.4                              | -5.3                              | -1.2                              | -1.0                              | -365884                             | -15.3                             | 
| 2014-08-27T00:00:00 | Allegany County     | 48941                            | 37802                            | 43944                            | 39379                            | 36643                            | 36261                            | -11139                              | 6142                                | -4565                               | -2736                               | -382                                | -22.8                             | 16.2                              | -10.4                             | -6.9                              | -1.0                              | -12680                              | -25.9                             | 
| 2014-08-27T00:00:00 | Anne Arundel County | 42413                            | 43320                            | 36438                            | 35218                            | 29244                            | 28111                            | 907                                 | -6882                               | -1220                               | -5974                               | -1133                               | 2.1                               | -15.9                             | -3.3                              | -17.0                             | -3.9                              | -14302                              | -33.7                             | 
| 2014-08-27T00:00:00 | Baltimore City      |                                  |                                  |                                  |                                  |                                  |                                  |                                     |                                     |                                     |                                     |                                     |                                   |                                   |                                   |                                   |                                   |                                     |                                   | 
| 2014-08-27T00:00:00 | Baltimore County    | 92806                            | 83232                            | 79479                            | 71227                            | 78282                            | 70419                            | -9574                               | -3753                               | -8252                               | 7055                                | -7863                               | -10.3                             | -4.5                              | -10.4                             | 9.9                               | -10.0                             | -22387                              | -24.1                             | 
| 2014-08-27T00:00:00 | Calvert County      | 41251                            | 37320                            | 35274                            | 30032                            | 26443                            | 32901                            | -3931                               | -2046                               | -5242                               | -3589                               | 6458                                | -9.5                              | -5.5                              | -14.9                             | -12.0                             | 24.4                              | -8350                               | -20.2                             | 
| 2014-08-27T00:00:00 | Caroline County     | 132804                           | 126981                           | 112545                           | 114843                           | 131277                           | 150357                           | -5823                               | -14436                              | 2298                                | 16434                               | 19080                               | -4.4                              | -11.4                             | 2.0                               | 14.3                              | 14.5                              | 17553                               | 13.2                              | 
| 2014-08-27T00:00:00 | Carroll County      | 166745                           | 157505                           | 167871                           | 147252                           | 141934                           | 132630                           | -9240                               | 10366                               | -20619                              | -5318                               | -9304                               | -5.5                              | 6.6                               | -12.3                             | -3.6                              | -6.6                              | -34115                              | -20.5                             | 
| 2014-08-27T00:00:00 | Cecil County        | 86861                            | 80241                            | 86419                            | 77089                            | 85026                            | 76667                            | -6620                               | 6178                                | -9330                               | 7937                                | -8359                               | -7.6                              | 7.7                               | -10.8                             | 10.3                              | -9.8                              | -10194                              | -11.7                             | 
| 2014-08-27T00:00:00 | Charles County      | 67655                            | 59389                            | 56648                            | 52056                            | 52147                            | 46659                            | -8266                               | -2741                               | -4592                               | 91                                  | -5488                               | -12.2                             | -4.6                              | -8.1                              | 0.2                               | -10.5                             | -20996                              | -31.0                             | 
```