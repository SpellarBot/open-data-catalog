# Major Crimes (Monthly)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/major-crimes-monthly) |
| Metadata | [Link](https://data.jacksonms.gov/api/views/8xyg-kbzy) |
| Data: JSON | [100 Rows](https://data.jacksonms.gov/api/views/8xyg-kbzy/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.jacksonms.gov/api/views/8xyg-kbzy/rows.csv?max_rows=100) |
| Host | data.jacksonms.gov |
| Id | 8xyg-kbzy |
| Name | Major Crimes (Monthly) |
| Attribution | City of Jackson Police Department |
| Category | Public Safety |
| Tags | police, crime, violent, property, safety, part 1, major, city of jackson, citations |
| Created | 2016-03-29T19:39:42Z |
| Publication Date | 2016-09-07T15:53:08Z |

## Description

This data set provides information on all Part 1 (Major Crimes) from October 2014 to Current. It is update monthly to show the current status of crime in the City of Jackson.

## Columns

```ls
| Included | Schema Type    | Field Name                           | Name                                  | Data Type     | Render Type   |
| ======== | ============== | ==================================== | ===================================== | ============= | ============= |
| Yes      | time           | month                                | Month                                 | calendar_date | calendar_date |
| Yes      | numeric metric | total_violent                        | Total Violent                         | number        | number        |
| Yes      | numeric metric | total_property                       | Total Property                        | number        | number        |
| Yes      | numeric metric | total_part_1_crime                   | Total Part 1 Crime                    | number        | number        |
| Yes      | numeric metric | violent_number_of_homicides          | Violent: Number of Homicides          | number        | number        |
| Yes      | numeric metric | violent_number_of_agg_assualts       | Violent: Number of Agg. Assualts      | number        | number        |
| Yes      | numeric metric | violent_number_of_armed_robberies    | Violent: Number of Armed Robberies    | number        | number        |
| Yes      | numeric metric | violent_number_of_carjackings        | Violent: Number of Carjackings        | number        | number        |
| Yes      | numeric metric | violent_number_of_rapes              | Violent: Number of Rapes              | number        | number        |
| Yes      | numeric metric | property_number_of_auto_theft        | Property: Number of Auto Theft        | number        | number        |
| Yes      | numeric metric | property_number_of_auto_burglary     | Property: Number of Auto Burglary     | number        | number        |
| Yes      | numeric metric | property_number_of_business_burglary | Property: Number of Business Burglary | number        | number        |
| Yes      | numeric metric | property_number_of_grand_larceny     | Property: Number of Grand Larceny     | number        | number        |
| Yes      | numeric metric | property_number_of_house_burglary    | Property: Number of House Burglary    | number        | number        |
```

## Time Field

```ls
Value = month
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:8xyg-kbzy d:2016-08-01T00:00:00.000Z m:violent_number_of_agg_assualts=43 m:violent_number_of_carjackings=13 m:total_part_1_crime=545 m:total_property=424 m:violent_number_of_homicides=5 m:property_number_of_house_burglary=136 m:property_number_of_auto_theft=63 m:property_number_of_business_burglary=55 m:total_violent=121 m:violent_number_of_rapes=9 m:property_number_of_grand_larceny=31 m:property_number_of_auto_burglary=139 m:violent_number_of_armed_robberies=51

series e:8xyg-kbzy d:2016-07-01T00:00:00.000Z m:violent_number_of_agg_assualts=54 m:violent_number_of_carjackings=17 m:total_part_1_crime=625 m:total_property=478 m:violent_number_of_homicides=4 m:property_number_of_house_burglary=128 m:property_number_of_auto_theft=82 m:property_number_of_business_burglary=50 m:total_violent=147 m:violent_number_of_rapes=13 m:property_number_of_grand_larceny=42 m:property_number_of_auto_burglary=176 m:violent_number_of_armed_robberies=59

series e:8xyg-kbzy d:2016-06-01T00:00:00.000Z m:violent_number_of_agg_assualts=52 m:violent_number_of_carjackings=5 m:total_part_1_crime=552 m:total_property=457 m:violent_number_of_homicides=2 m:property_number_of_house_burglary=116 m:property_number_of_auto_theft=65 m:property_number_of_business_burglary=47 m:total_violent=95 m:violent_number_of_rapes=4 m:property_number_of_grand_larceny=35 m:property_number_of_auto_burglary=194 m:violent_number_of_armed_robberies=32
```

## Meta Commands

```ls
metric m:total_violent p:integer l:"Total Violent" t:dataTypeName=number

metric m:total_property p:integer l:"Total Property" t:dataTypeName=number

metric m:total_part_1_crime p:integer l:"Total Part 1 Crime" t:dataTypeName=number

metric m:violent_number_of_homicides p:integer l:"Violent: Number of Homicides" t:dataTypeName=number

metric m:violent_number_of_agg_assualts p:integer l:"Violent: Number of Agg. Assualts" t:dataTypeName=number

metric m:violent_number_of_armed_robberies p:integer l:"Violent: Number of Armed Robberies" t:dataTypeName=number

metric m:violent_number_of_carjackings p:integer l:"Violent: Number of Carjackings" t:dataTypeName=number

metric m:violent_number_of_rapes p:integer l:"Violent: Number of Rapes" t:dataTypeName=number

metric m:property_number_of_auto_theft p:integer l:"Property: Number of Auto Theft" t:dataTypeName=number

metric m:property_number_of_auto_burglary p:integer l:"Property: Number of Auto Burglary" t:dataTypeName=number

metric m:property_number_of_business_burglary p:integer l:"Property: Number of Business Burglary" t:dataTypeName=number

metric m:property_number_of_grand_larceny p:integer l:"Property: Number of Grand Larceny" t:dataTypeName=number

metric m:property_number_of_house_burglary p:integer l:"Property: Number of House Burglary" t:dataTypeName=number

entity e:8xyg-kbzy l:"Major Crimes (Monthly)" t:attribution="City of Jackson Police Department" t:url=https://data.jacksonms.gov/api/views/8xyg-kbzy

property e:8xyg-kbzy t:meta.view v:id=8xyg-kbzy v:category="Public Safety" v:attributionLink=http://www.jacksonms.gov v:averageRating=0 v:name="Major Crimes (Monthly)" v:attribution="City of Jackson Police Department"

property e:8xyg-kbzy t:meta.view.owner v:id=6ngd-c2u2 v:profileImageUrlMedium=/api/users/6ngd-c2u2/profile_images/THUMB v:profileImageUrlLarge=/api/users/6ngd-c2u2/profile_images/LARGE v:screenName="Justin Bruce" v:profileImageUrlSmall=/api/users/6ngd-c2u2/profile_images/TINY v:lastNotificationSeenAt=1492180672 v:displayName="Justin Bruce"

property e:8xyg-kbzy t:meta.view.tableauthor v:id=6ngd-c2u2 v:profileImageUrlMedium=/api/users/6ngd-c2u2/profile_images/THUMB v:profileImageUrlLarge=/api/users/6ngd-c2u2/profile_images/LARGE v:screenName="Justin Bruce" v:profileImageUrlSmall=/api/users/6ngd-c2u2/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1492180672 v:displayName="Justin Bruce"
```

## Top Records

```ls
| month               | total_violent | total_property | total_part_1_crime | violent_number_of_homicides | violent_number_of_agg_assualts | violent_number_of_armed_robberies | violent_number_of_carjackings | violent_number_of_rapes | property_number_of_auto_theft | property_number_of_auto_burglary | property_number_of_business_burglary | property_number_of_grand_larceny | property_number_of_house_burglary | 
| =================== | ============= | ============== | ================== | =========================== | ============================== | ================================= | ============================= | ======================= | ============================= | ================================ | ==================================== | ================================ | ================================= | 
| 2016-08-01T00:00:00 | 121           | 424            | 545                | 5                           | 43                             | 51                                | 13                            | 9                       | 63                            | 139                              | 55                                   | 31                               | 136                               | 
| 2016-07-01T00:00:00 | 147           | 478            | 625                | 4                           | 54                             | 59                                | 17                            | 13                      | 82                            | 176                              | 50                                   | 42                               | 128                               | 
| 2016-06-01T00:00:00 | 95            | 457            | 552                | 2                           | 52                             | 32                                | 5                             | 4                       | 65                            | 194                              | 47                                   | 35                               | 116                               | 
| 2016-05-01T00:00:00 | 114           | 346            | 460                | 4                           | 57                             | 38                                | 7                             | 8                       | 64                            | 110                              | 42                                   | 19                               | 111                               | 
| 2016-04-01T00:00:00 | 125           | 390            | 515                | 5                           | 63                             | 38                                | 8                             | 11                      | 67                            | 162                              | 32                                   | 11                               | 118                               | 
| 2016-03-01T00:00:00 | 83            | 291            | 374                | 8                           | 38                             | 30                                | 3                             | 4                       | 68                            | 115                              | 14                                   | 19                               | 75                                | 
| 2016-02-01T00:00:00 | 94            | 370            | 464                | 4                           | 37                             | 43                                | 6                             | 4                       | 66                            | 136                              | 20                                   | 22                               | 126                               | 
| 2016-01-01T00:00:00 | 148           | 480            | 628                | 3                           | 39                             | 73                                | 25                            | 8                       | 98                            | 175                              | 40                                   | 16                               | 151                               | 
| 2015-12-01T00:00:00 | 137           | 514            | 651                | 2                           | 49                             | 69                                | 6                             | 11                      | 89                            | 176                              | 30                                   | 20                               | 199                               | 
| 2015-11-01T00:00:00 | 160           | 482            | 642                | 6                           | 49                             | 87                                | 7                             | 11                      | 82                            | 172                              | 51                                   | 20                               | 157                               | 
```