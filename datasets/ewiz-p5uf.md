# Maryland Number of Farms, Change in Farms and Percent Change in Farms

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/maryland-number-of-farms-change-in-farms-and-percent-change-in-farms-74b67) |
| Metadata | [Link](https://data.maryland.gov/api/views/ewiz-p5uf) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/ewiz-p5uf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/ewiz-p5uf/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | ewiz-p5uf |
| Name | Maryland Number of Farms, Change in Farms and Percent Change in Farms |
| Attribution | Maryland Department of Planning |
| Tags | farms, ag census, agriculture, mdp |
| Created | 2014-08-27T19:40:47Z |
| Publication Date | 2014-08-27T19:44:17Z |

## Description

Number of Farms in Maryland and its Jurisdiction, change in number of farms and percent change in farms. 1997, 2002, 2007 and 2012 Census of Agriculture

## Columns

```ls
| Included | Schema Type    | Field Name                          | Name                                 | Data Type     | Render Type   |
| ======== | ============== | =================================== | ==================================== | ============= | ============= |
| Yes      | time           | date_created                        | Date created                         | calendar_date | calendar_date |
| Yes      | series tag     | jurisdiction                        | Jurisdiction                         | text          | text          |
| Yes      | numeric metric | number_of_farms_1987                | Number of Farms, 1987                | number        | number        |
| Yes      | numeric metric | number_of_farms_1992                | Number of Farms, 1992                | number        | number        |
| Yes      | numeric metric | number_of_farms_1997                | Number of Farms, 1997                | number        | number        |
| Yes      | numeric metric | number_of_farms_2002                | Number of Farms, 2002                | number        | number        |
| Yes      | numeric metric | number_of_farms_2007                | Number of Farms, 2007                | number        | number        |
| Yes      | numeric metric | number_of_farms_2012                | Number of Farms, 2012                | number        | number        |
| Yes      | numeric metric | change_in_number_of_farms_1987_1992 | Change in Number of Farms, 1987-1992 | number        | number        |
| Yes      | numeric metric | change_in_number_of_farms_1992_1997 | Change in Number of Farms, 1992-1997 | number        | number        |
| Yes      | numeric metric | change_in_number_of_farms_1997_2002 | Change in Number of Farms, 1997-2002 | number        | number        |
| Yes      | numeric metric | change_in_number_of_farms_2002_2007 | Change in Number of Farms, 2002-2007 | number        | number        |
| Yes      | numeric metric | change_in_number_of_farms_2007_2012 | Change in Number of Farms, 2007-2012 | number        | number        |
| Yes      | numeric metric | percent_change_in_farms_1987_1992   | Percent Change in Farms, 1987-1992   | percent       | percent       |
| Yes      | numeric metric | percent_change_in_farms_1992_1997   | Percent Change in Farms, 1992-1997   | percent       | percent       |
| Yes      | numeric metric | percent_change_in_farms_1997_2002   | Percent Change in Farms, 1997-2002   | percent       | percent       |
| Yes      | numeric metric | percent_change_in_farms_2002_2007   | Percent Change in Farms, 2002-2007   | percent       | percent       |
| Yes      | numeric metric | percent_change_in_farms_2007_2012   | Percent Change in Farms, 2007-2012   | percent       | percent       |
| Yes      | numeric metric | change_in_number_of_farms_1987_2012 | Change in Number of Farms, 1987-2012 | number        | number        |
| Yes      | numeric metric | percent_change_in_farms_1987_2012   | Percent Change in Farms, 1987-2012   | percent       | percent       |
```

## Time Field

```ls
Value = date_created
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:ewiz-p5uf d:2014-08-27T00:00:00.000Z t:jurisdiction=MARYLAND m:percent_change_in_farms_1992_1997=1.7 m:number_of_farms_2002=12198 m:number_of_farms_2012=12256 m:percent_change_in_farms_1987_2012=-17.1 m:change_in_number_of_farms_1992_1997=217 m:change_in_number_of_farms_1997_2002=-1056 m:percent_change_in_farms_1997_2002=-8 m:number_of_farms_2007=12834 m:percent_change_in_farms_2007_2012=-4.5 m:change_in_number_of_farms_1987_1992=-1739 m:percent_change_in_farms_2002_2007=5.2 m:number_of_farms_1992=13037 m:change_in_number_of_farms_1987_2012=-2520 m:change_in_number_of_farms_2007_2012=-578 m:number_of_farms_1987=14776 m:number_of_farms_1997=13254 m:change_in_number_of_farms_2002_2007=636 m:percent_change_in_farms_1987_1992=-11.8

series e:ewiz-p5uf d:2014-08-27T00:00:00.000Z t:jurisdiction="Allegany County" m:percent_change_in_farms_1992_1997=25.1 m:number_of_farms_2002=278 m:number_of_farms_2012=291 m:percent_change_in_farms_1987_2012=21.3 m:change_in_number_of_farms_1992_1997=55 m:change_in_number_of_farms_1997_2002=4 m:percent_change_in_farms_1997_2002=1.5 m:number_of_farms_2007=302 m:percent_change_in_farms_2007_2012=-3.6 m:change_in_number_of_farms_1987_1992=-21 m:percent_change_in_farms_2002_2007=8.6 m:number_of_farms_1992=219 m:change_in_number_of_farms_1987_2012=51 m:change_in_number_of_farms_2007_2012=-11 m:number_of_farms_1987=240 m:number_of_farms_1997=274 m:change_in_number_of_farms_2002_2007=24 m:percent_change_in_farms_1987_1992=-8.8

series e:ewiz-p5uf d:2014-08-27T00:00:00.000Z t:jurisdiction="Anne Arundel County" m:percent_change_in_farms_1992_1997=-2.5 m:number_of_farms_2002=432 m:number_of_farms_2012=381 m:percent_change_in_farms_1987_2012=-32.8 m:change_in_number_of_farms_1992_1997=-12 m:change_in_number_of_farms_1997_2002=-33 m:percent_change_in_farms_1997_2002=-7.1 m:number_of_farms_2007=377 m:percent_change_in_farms_2007_2012=1.1 m:change_in_number_of_farms_1987_1992=-90 m:percent_change_in_farms_2002_2007=-12.7 m:number_of_farms_1992=477 m:change_in_number_of_farms_1987_2012=-186 m:change_in_number_of_farms_2007_2012=4 m:number_of_farms_1987=567 m:number_of_farms_1997=465 m:change_in_number_of_farms_2002_2007=-55 m:percent_change_in_farms_1987_1992=-15.9
```

## Meta Commands

```ls
metric m:number_of_farms_1987 p:integer l:"Number of Farms, 1987" t:dataTypeName=number

metric m:number_of_farms_1992 p:integer l:"Number of Farms, 1992" t:dataTypeName=number

metric m:number_of_farms_1997 p:integer l:"Number of Farms, 1997" t:dataTypeName=number

metric m:number_of_farms_2002 p:integer l:"Number of Farms, 2002" t:dataTypeName=number

metric m:number_of_farms_2007 p:integer l:"Number of Farms, 2007" t:dataTypeName=number

metric m:number_of_farms_2012 p:integer l:"Number of Farms, 2012" t:dataTypeName=number

metric m:change_in_number_of_farms_1987_1992 p:integer l:"Change in Number of Farms, 1987-1992" t:dataTypeName=number

metric m:change_in_number_of_farms_1992_1997 p:integer l:"Change in Number of Farms, 1992-1997" t:dataTypeName=number

metric m:change_in_number_of_farms_1997_2002 p:integer l:"Change in Number of Farms, 1997-2002" t:dataTypeName=number

metric m:change_in_number_of_farms_2002_2007 p:integer l:"Change in Number of Farms, 2002-2007" t:dataTypeName=number

metric m:change_in_number_of_farms_2007_2012 p:integer l:"Change in Number of Farms, 2007-2012" t:dataTypeName=number

metric m:percent_change_in_farms_1987_1992 p:float l:"Percent Change in Farms, 1987-1992" t:dataTypeName=percent

metric m:percent_change_in_farms_1992_1997 p:float l:"Percent Change in Farms, 1992-1997" t:dataTypeName=percent

metric m:percent_change_in_farms_1997_2002 p:float l:"Percent Change in Farms, 1997-2002" t:dataTypeName=percent

metric m:percent_change_in_farms_2002_2007 p:float l:"Percent Change in Farms, 2002-2007" t:dataTypeName=percent

metric m:percent_change_in_farms_2007_2012 p:float l:"Percent Change in Farms, 2007-2012" t:dataTypeName=percent

metric m:change_in_number_of_farms_1987_2012 p:integer l:"Change in Number of Farms, 1987-2012" t:dataTypeName=number

metric m:percent_change_in_farms_1987_2012 p:float l:"Percent Change in Farms, 1987-2012" t:dataTypeName=percent

entity e:ewiz-p5uf l:"Maryland Number of  Farms, Change in Farms and Percent Change in Farms" t:attribution="Maryland Department of Planning" t:url=https://data.maryland.gov/api/views/ewiz-p5uf

property e:ewiz-p5uf t:meta.view v:id=ewiz-p5uf v:attributionLink=http://planning.maryland.gov/msdc/S6_Econ_Agri_Census.shtml v:averageRating=0 v:name="Maryland Number of  Farms, Change in Farms and Percent Change in Farms" v:attribution="Maryland Department of Planning"

property e:ewiz-p5uf t:meta.view.owner v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:displayName=MDP

property e:ewiz-p5uf t:meta.view.tableauthor v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:roleName=editor v:displayName=MDP
```

## Top Records

```ls
| date_created        | jurisdiction        | number_of_farms_1987 | number_of_farms_1992 | number_of_farms_1997 | number_of_farms_2002 | number_of_farms_2007 | number_of_farms_2012 | change_in_number_of_farms_1987_1992 | change_in_number_of_farms_1992_1997 | change_in_number_of_farms_1997_2002 | change_in_number_of_farms_2002_2007 | change_in_number_of_farms_2007_2012 | percent_change_in_farms_1987_1992 | percent_change_in_farms_1992_1997 | percent_change_in_farms_1997_2002 | percent_change_in_farms_2002_2007 | percent_change_in_farms_2007_2012 | change_in_number_of_farms_1987_2012 | percent_change_in_farms_1987_2012 | 
| =================== | =================== | ==================== | ==================== | ==================== | ==================== | ==================== | ==================== | =================================== | =================================== | =================================== | =================================== | =================================== | ================================= | ================================= | ================================= | ================================= | ================================= | =================================== | ================================= | 
| 2014-08-27T00:00:00 | MARYLAND            | 14776                | 13037                | 13254                | 12198                | 12834                | 12256                | -1739                               | 217                                 | -1056                               | 636                                 | -578                                | -11.8                             | 1.7                               | -8.0                              | 5.2                               | -4.5                              | -2520                               | -17.1                             | 
| 2014-08-27T00:00:00 | Allegany County     | 240                  | 219                  | 274                  | 278                  | 302                  | 291                  | -21                                 | 55                                  | 4                                   | 24                                  | -11                                 | -8.8                              | 25.1                              | 1.5                               | 8.6                               | -3.6                              | 51                                  | 21.3                              | 
| 2014-08-27T00:00:00 | Anne Arundel County | 567                  | 477                  | 465                  | 432                  | 377                  | 381                  | -90                                 | -12                                 | -33                                 | -55                                 | 4                                   | -15.9                             | -2.5                              | -7.1                              | -12.7                             | 1.1                               | -186                                | -32.8                             | 
| 2014-08-27T00:00:00 | Baltimore City      |                      |                      |                      |                      |                      |                      |                                     |                                     |                                     |                                     |                                     |                                   |                                   |                                   |                                   |                                   |                                     |                                   | 
| 2014-08-27T00:00:00 | Baltimore County    | 917                  | 840                  | 889                  | 784                  | 751                  | 640                  | -77                                 | 49                                  | -105                                | -33                                 | -111                                | -8.4                              | 5.8                               | -11.8                             | -4.2                              | -14.8                             | -277                                | -30.2                             | 
| 2014-08-27T00:00:00 | Calvert County      | 464                  | 400                  | 383                  | 321                  | 274                  | 269                  | -64                                 | -17                                 | -62                                 | -47                                 | -5                                  | -13.8                             | -4.3                              | -16.2                             | -14.6                             | -1.8                              | -195                                | -42.0                             | 
| 2014-08-27T00:00:00 | Caroline County     | 636                  | 588                  | 556                  | 506                  | 574                  | 658                  | -48                                 | -32                                 | -50                                 | 68                                  | 84                                  | -7.5                              | -5.4                              | -9.0                              | 13.4                              | 14.6                              | 22                                  | 3.5                               | 
| 2014-08-27T00:00:00 | Carroll County      | 1238                 | 1080                 | 1159                 | 1058                 | 1148                 | 1092                 | -158                                | 79                                  | -101                                | 90                                  | -56                                 | -12.8                             | 7.3                               | -8.7                              | 8.5                               | -4.9                              | -146                                | -11.8                             | 
| 2014-08-27T00:00:00 | Cecil County        | 501                  | 455                  | 510                  | 468                  | 583                  | 496                  | -46                                 | 55                                  | -42                                 | 115                                 | -87                                 | -9.2                              | 12.1                              | -8.2                              | 24.6                              | -14.9                             | -5                                  | -1.0                              | 
| 2014-08-27T00:00:00 | Charles County      | 601                  | 496                  | 451                  | 418                  | 418                  | 382                  | -105                                | -45                                 | -33                                 | 0                                   | -36                                 | -17.5                             | -9.1                              | -7.3                              | 0.0                               | -8.6                              | -219                                | -36.4                             | 
```