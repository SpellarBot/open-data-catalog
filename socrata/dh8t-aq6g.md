# Parking Rates

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/parking-rates) |
| Metadata | [Link](https://data.montgomerycountymd.gov/api/views/dh8t-aq6g) |
| Data: JSON | [100 Rows](https://data.montgomerycountymd.gov/api/views/dh8t-aq6g/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.montgomerycountymd.gov/api/views/dh8t-aq6g/rows.csv?max_rows=100) |
| Host | data.montgomerycountymd.gov |
| Id | dh8t-aq6g |
| Name | Parking Rates |
| Category | Transportation |
| Tags | parking, rates, garages, lots, spaces |
| Created | 2015-06-24T14:14:21Z |
| Publication Date | 2015-07-06T15:49:07Z |

## Description

Montgomery County Public Parking Rates

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type | Render Type |
| ======== | ============== | ======================= | ======================= | ========= | =========== |
| No       | time           | :updated_at             | updated_at              | meta_data | meta_data   |
| Yes      | series tag     | district                | Parking District        | text      | text        |
| Yes      | series tag     | parking_number          | Parking Number          | text      | text        |
| Yes      | series tag     | located_at              | Located At              | text      | text        |
| Yes      | series tag     | near_lat                | Near Latitude           | text      | text        |
| Yes      | series tag     | near_lng                | Near Longitude          | text      | text        |
| Yes      | series tag     | hours_requiring_payment | Hours Requiring Payment | text      | text        |
| Yes      | numeric metric | rate                    | Parking Rate            | money     | text        |
| Yes      | series tag     | duration                | Duration                | text      | text        |
| Yes      | series tag     | who_can_park            | Who Can Park            | text      | text        |
| Yes      | series tag     | payment_options         | Payment Options         | text      | text        |
| No       |                | address1                | Address 1               | text      | text        |
| No       |                | address2                | Address 2               | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address1,address2
```

## Data Commands

```ls
series e:dh8t-aq6g d:2015-07-06T08:44:11.000Z t:near_lat=38.98809 t:duration="No Limit" t:payment_options="Coins,Pay-By-Cell, Metered" t:located_at="GAR 09" t:near_lng=-77.02901 t:parking_number=3091052 t:district=S t:who_can_park=PCS t:hours_requiring_payment="7:00AM-7:00PM Monday through Friday" m:rate=0.65

series e:dh8t-aq6g d:2015-07-06T08:44:11.000Z t:near_lat=38.98031 t:duration="15 hour limit" t:payment_options="Bills, Credit Cards, Coins,Pay-On-Foot" t:located_at="GAR 31" t:near_lng=-77.094971 t:parking_number=3313028 t:district=B t:who_can_park="General Public" t:hours_requiring_payment="7:00AM-10:00PM Monday through Friday" m:rate=0.8

series e:dh8t-aq6g d:2015-07-06T08:44:11.000Z t:near_lat=38.98809655 t:duration="1 hour limit" t:payment_options="Coins, Credit Cards, Pay-By-Cell" t:located_at="On Street" t:near_lng=-77.09514657 t:parking_number=1106134 t:district=B t:who_can_park="General Public" t:hours_requiring_payment="Mon-Fri, 03:30PM-06:00PM;Mon-Fri, 06:00PM-10:00PM;Mon-Fri, 06:30AM-09:30AM" m:rate=2
```

## Meta Commands

```ls
metric m:rate p:long l:"Parking Rate" d:"Parking Rate" t:dataTypeName=money

entity e:dh8t-aq6g l:"Parking Rates" t:url=https://data.montgomerycountymd.gov/api/views/dh8t-aq6g

property e:dh8t-aq6g t:meta.view v:id=dh8t-aq6g v:category=Transportation v:averageRating=0 v:name="Parking Rates"

property e:dh8t-aq6g t:meta.view.license v:name="Public Domain"

property e:dh8t-aq6g t:meta.view.owner v:id=ajn4-zy65 v:screenName="MCG ESB Service" v:lastNotificationSeenAt=1491401045 v:displayName="MCG ESB Service"

property e:dh8t-aq6g t:meta.view.tableauthor v:id=ajn4-zy65 v:screenName="MCG ESB Service" v:roleName=administrator v:lastNotificationSeenAt=1491401045 v:displayName="MCG ESB Service"
```

## Top Records

```ls
| :updated_at | district | parking_number | located_at | near_lat    | near_lng     | hours_requiring_payment                                                                                                  | rate     | duration      | who_can_park   | payment_options                        | address1                              | address2                                            | 
| =========== | ======== | ============== | ========== | =========== | ============ | ======================================================================================================================== | ======== | ============= | ============== | ====================================== | ===================================== | =================================================== | 
| 1436172251  | S        | 3091052        | GAR 09     | 38.98809    | -77.02901    | 7:00AM-7:00PM Monday through Friday                                                                                      | $0.65/hr | No Limit      | PCS            | Coins,Pay-By-Cell, Metered             | 8040 Kennett Street (Eastern Avenue)  | Accesspoints: Kennett Street & Eastern Avenue       | 
| 1436172251  | B        | 3313028        | GAR 31     | 38.98031    | -77.094971   | 7:00AM-10:00PM Monday through Friday                                                                                     | $0.80/hr | 15 hour limit | General Public | Bills, Credit Cards, Coins,Pay-On-Foot | 7171 Woodmont Avenue                  | Accesspoints: Bethesda Avenue and Woodmont Avenue   | 
| 1436172251  | B        | 1106134        | On Street  | 38.98809655 | -77.09514657 | Mon-Fri, 03:30PM-06:00PM;Mon-Fri, 06:00PM-10:00PM;Mon-Fri, 06:30AM-09:30AM                                               | $2.00/hr | 1 hour limit  | General Public | Coins, Credit Cards, Pay-By-Cell       | On Street: WISCONSIN AVE              | From : NORFOLK AVE To :COMMERCE D                   | 
| 1436172251  | B        | 3314259        | GAR 31     | 38.98031    | -77.094971   | 7:00AM-10:00PM Monday through Friday                                                                                     | $0.80/hr | 15 hour limit | General Public | Bills, Credit Cards, Coins,Pay-On-Foot | 7171 Woodmont Avenue                  | Accesspoints: Bethesda Avenue and Woodmont Avenue   | 
| 1436172251  | S        | 3582678        | GAR 58     | 38.99272    | -77.03094    | 7:00AM-7:00PM Monday through Friday                                                                                      | $0.65/hr | No Limit      | PCS            | Coins,Pay-By-Cell, Metered             | 1315 East-West Highway                | Accesspoints: East-West Highway                     | 
| 1436172251  | B        | 3364398        | GAR 36     | 38.98951    | -77.09968    | 7:00AM-10:00PM Monday through Friday                                                                                     | $0.80/hr | 15 hour limit | General Public | Coins,Pay-By-Cell, Metered             | 4907 Del Ray Avenue (Auburn Avenue)   | Accesspoints: Del Ray Avenue & Auburn Avenue        | 
| 1436172251  | S        | 3606522        | GAR 60     | 38.99532    | -77.02565    | 7:00AM-6:00PM Monday through Thursday; 7:00AM-5:00PM Friday;7:00AM-6:00PM Monday through Thursday; 7:00AM-5:00PM Friday; | $0.65/hr | 12 hour limit | General Public | Bills, Credit Cards, Coins,Pay-On-Foot | 921 Wayne Avenue                      | Accesspoints: Wayne Avenue & Ellsworth Avenue Alley | 
| 1436172251  | S        | 3613112        | GAR 61     | 38.99774    | -77.02534    | 7:00AM-6:00PM Monday through Thursday; 7:00AM-5:00PM Friday;7:00AM-6:00PM Monday through Thursday; 7:00AM-5:00PM Friday; | $0.65/hr | 12 hour limit | General Public | Bills, Credit Cards, Coins,Pay-On-Foot | 801 Ellsworth Drive                   | Accesspoints: Ellsworth Drive & Roeder Road         | 
| 1436172251  | B        | 3401302        | GAR 40     | 38.98792    | -77.098501   | 7:00AM-10:00PM Monday through Friday                                                                                     | $0.80/hr | 2 hour limit  | General Public | Coins,Pay-By-Cell, Metered             | 4935 St. Elmo Avenue (Cordell Avenue) | Accesspoints: St. Elmo Avenue & Cordell Avenue      | 
| 1436172251  | S        | 3616326        | GAR 61     | 38.99774    | -77.02534    | 7:00AM-6:00PM Monday through Thursday; 7:00AM-5:00PM Friday;7:00AM-6:00PM Monday through Thursday; 7:00AM-5:00PM Friday; | $0.65/hr | 12 hour limit | General Public | Bills, Credit Cards, Coins,Pay-On-Foot | 801 Ellsworth Drive                   | Accesspoints: Ellsworth Drive & Roeder Road         | 
```