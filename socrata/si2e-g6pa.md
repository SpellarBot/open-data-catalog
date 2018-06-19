# American Recovery and Reinvestment Act (ARRA) Employment Numbers: 2009 - 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/american-recovery-and-reinvestment-act-arra-employment-numbers-beginning-2009) |
| Metadata | [Link](https://data.ny.gov/api/views/si2e-g6pa) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/si2e-g6pa/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/si2e-g6pa/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | si2e-g6pa |
| Name | American Recovery and Reinvestment Act (ARRA) Employment Numbers: 2009 - 2013 |
| Attribution | New York State Department of Transportation |
| Category | Transportation |
| Tags | american recovery and reinvestment act, recover act, arra, transportation mode, ftes |
| Created | 2013-05-20T17:41:42Z |
| Publication Date | 2014-09-11T16:50:41Z |

## Description

The dataset lists the employment numbers per transportation mode per quarterly reporting period from March 2009 to 2013

## Columns

```ls
| Included | Schema Type    | Field Name                                     | Name                                           | Data Type     | Render Type   |
| ======== | ============== | ============================================== | ============================================== | ============= | ============= |
| No       |                | year                                           | Year                                           | number        | number        |
| No       |                | calendar_quarter                               | Calendar Quarter                               | number        | number        |
| Yes      | time           | beginning_dates                                | Beginning Date                                 | calendar_date | calendar_date |
| No       |                | dates                                          | Ending Date                                    | calendar_date | calendar_date |
| Yes      | numeric metric | fhwa_hiif_highway_bridge                       | FHWA HIIF (Highway & Bridge)                   | number        | number        |
| Yes      | numeric metric | fhwa_ferry_boat_grants                         | FHWA Ferry-Boat Grants                         | number        | number        |
| Yes      | numeric metric | fhwa_ycip_grant                                | FHWA YCIP Grant                                | number        | number        |
| Yes      | numeric metric | fra_high_speed_intercity_passenger_rail_grants | FRA High-Speed Intercity Passenger Rail Grants | number        | number        |
| Yes      | numeric metric | fta_non_urban_transit_funds                    | FTA Non-Urban Transit Funds                    | number        | number        |
| Yes      | numeric metric | epa_clean_diesel_grant                         | EPA Clean Diesel Grant                         | number        | number        |
| No       |                | total_ftes_per_quarter                         | Total FTEs per Quarter                         | number        | number        |
```

## Time Field

```ls
Value = beginning_dates
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = dates,total_ftes_per_quarter,year,calendar_quarter
```

## Data Commands

```ls
series e:si2e-g6pa d:2013-01-01T00:00:00.000Z m:fra_high_speed_intercity_passenger_rail_grants=22.3 m:fta_non_urban_transit_funds=3.01 m:fhwa_hiif_highway_bridge=162.46 m:fhwa_ferry_boat_grants=12.6

series e:si2e-g6pa d:2012-10-01T00:00:00.000Z m:fra_high_speed_intercity_passenger_rail_grants=19.47 m:fta_non_urban_transit_funds=0.94 m:fhwa_hiif_highway_bridge=288.48 m:fhwa_ferry_boat_grants=14.18

series e:si2e-g6pa d:2012-07-01T00:00:00.000Z m:fra_high_speed_intercity_passenger_rail_grants=31.76 m:fta_non_urban_transit_funds=2.74 m:fhwa_hiif_highway_bridge=430.15 m:fhwa_ferry_boat_grants=18.17
```

## Meta Commands

```ls
metric m:fhwa_hiif_highway_bridge p:float l:"FHWA HIIF (Highway & Bridge)" d:"Federal Highway Administration Highway Infrastructure Investment Fund" t:dataTypeName=number

metric m:fhwa_ferry_boat_grants p:float l:"FHWA Ferry-Boat Grants" d:"Federal Highway Administration Ferry Boat program. Blank denotes no FTEs due to the program either not starting or having closed out. Zero means no grant funding of this type received for this quarter." t:dataTypeName=number

metric m:fhwa_ycip_grant p:float l:"FHWA YCIP Grant" d:"Federal Highway Administration Youth Construction Initiative Program (YCIP) is an on-the-job-training program for high school aged students designed to provide an opportunity for 11th and 12th graders to explore careers in the highway construction industry. Blank denotes no FTEs due to the program either not starting or having closed out. Zero means no grant funding of this type received for this quarter." t:dataTypeName=number

metric m:fra_high_speed_intercity_passenger_rail_grants p:float l:"FRA High-Speed Intercity Passenger Rail Grants" d:"Federal Railroad Administration High-Speed Intercity Passenger Rail program. Blank denotes no FTEs due to the program either not starting or having closed out. Zero means no grant funding of this type received for this quarter." t:dataTypeName=number

metric m:fta_non_urban_transit_funds p:float l:"FTA Non-Urban Transit Funds" d:"Federal Transit Administration Non-Urban and Rural Transit program. Blank denotes no FTEs due to the program either not starting or having closed out. Zero means no funding of this type received for this quarter." t:dataTypeName=number

metric m:epa_clean_diesel_grant p:double l:"EPA Clean Diesel Grant" d:"Environmental Protection Agency program to upgrade transportation modes using diesel burning fuel program. Blank denotes no FTEs due to the program either not starting or having closed out. Zero means no grant funding of this type received for this quarter." t:dataTypeName=number

entity e:si2e-g6pa l:"American Recovery and Reinvestment Act (ARRA) Employment Numbers: 2009 - 2013" t:attribution="New York State Department of Transportation" t:url=https://data.ny.gov/api/views/si2e-g6pa

property e:si2e-g6pa t:meta.view v:id=si2e-g6pa v:category=Transportation v:attributionLink=https://www.dot.ny.gov/recovery v:averageRating=0 v:name="American Recovery and Reinvestment Act (ARRA) Employment Numbers: 2009 - 2013" v:attribution="New York State Department of Transportation"

property e:si2e-g6pa t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:si2e-g6pa t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:si2e-g6pa t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| year | calendar_quarter | beginning_dates     | dates               | fhwa_hiif_highway_bridge | fhwa_ferry_boat_grants | fhwa_ycip_grant | fra_high_speed_intercity_passenger_rail_grants | fta_non_urban_transit_funds | epa_clean_diesel_grant | total_ftes_per_quarter | 
| ==== | ================ | =================== | =================== | ======================== | ====================== | =============== | ============================================== | =========================== | ====================== | ====================== | 
| 2013 | 1                | 2013-01-01T00:00:00 | 2013-03-30T00:00:00 | 162.46                   | 12.6                   |                 | 22.3                                           | 3.01                        |                        | 200.37                 | 
| 2012 | 4                | 2012-10-01T00:00:00 | 2012-12-31T00:00:00 | 288.48                   | 14.18                  |                 | 19.47                                          | 0.94                        |                        | 323.07                 | 
| 2012 | 3                | 2012-07-01T00:00:00 | 2012-09-30T00:00:00 | 430.15                   | 18.17                  |                 | 31.76                                          | 2.74                        |                        | 482.82                 | 
| 2012 | 2                | 2012-04-01T00:00:00 | 2012-06-30T00:00:00 | 490.86                   | 12.32                  |                 | 12.01                                          | 1.71                        |                        | 516.9                  | 
| 2012 | 1                | 2012-01-01T00:00:00 | 2012-03-30T00:00:00 | 340.26                   | 15.67                  |                 | 13.68                                          | 0.97                        |                        | 370.58                 | 
| 2011 | 4                | 2011-10-01T00:00:00 | 2011-12-31T00:00:00 | 571.38                   | 14.52                  | 2               | 52.01                                          | 22.52                       |                        | 662.43                 | 
| 2011 | 3                | 2011-07-01T00:00:00 | 2011-09-30T00:00:00 | 777.47                   | 15.27                  | 21.67           | 1.38                                           | 12.64                       |                        | 828.43                 | 
| 2011 | 2                | 2011-04-01T00:00:00 | 2011-06-30T00:00:00 | 793.18                   | 12.96                  | 8.47            | 0                                              | 2.25                        | 0                      | 816.86                 | 
| 2011 | 1                | 2011-01-01T00:00:00 | 2011-03-30T00:00:00 | 317.37                   | 8.04                   | 11.72           | 0                                              | 0.16                        | 1.42                   | 338.71                 | 
| 2010 | 4                | 2010-10-01T00:00:00 | 2010-12-31T00:00:00 | 1015.92                  | 10.46                  | 9.48            | 1                                              | 4.64                        | 8                      | 1049.50                | 
```