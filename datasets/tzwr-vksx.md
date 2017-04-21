# New Capacity Program By Borough

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/new-capacity-program-by-borough) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/tzwr-vksx) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/tzwr-vksx/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/tzwr-vksx/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | tzwr-vksx |
| Name | New Capacity Program By Borough |
| Attribution | School Construction Authority (SCA) |
| Category | Education |
| Tags | sca, capacity, schools |
| Created | 2016-06-02T14:47:05Z |
| Publication Date | 2016-06-02T14:57:34Z |

## Description

Number of seats and cost by borough and district.

## Columns

```ls
| Included | Schema Type    | Field Name     | Name             | Data Type | Render Type |
| ======== | ============== | ============== | ================ | ========= | =========== |
| No       | time           | :updated_at    | updated_at       | meta_data | meta_data   |
| Yes      | series tag     | district       | DISTRICT         | text      | text        |
| Yes      | series tag     | borough        | BOROUGH          | text      | text        |
| Yes      | numeric metric | small_ps_bldgs | SMALL PS # BLDGS | number    | number      |
| Yes      | numeric metric | small_ps_seats | SMALL PS # SEATS | number    | number      |
| Yes      | numeric metric | small_ps_cost  | SMALL PS COST    | number    | number      |
| Yes      | numeric metric | ps_is_bldgs    | PS/IS # BLDGS    | number    | number      |
| Yes      | numeric metric | ps_is_seats    | PS/IS # SEATS    | number    | number      |
| Yes      | numeric metric | ps_is_cost     | PS/IS COST       | number    | number      |
| Yes      | numeric metric | is_hs_bldgs    | IS/HS # BLDGS    | number    | number      |
| Yes      | numeric metric | is_hs_seats    | IS/HS # SEATS    | number    | number      |
| Yes      | numeric metric | is_hs_cost     | IS/HS COST       | number    | number      |
| Yes      | numeric metric | total_bldgs    | TOTAL # BLDGS    | number    | number      |
| Yes      | numeric metric | total_seats    | TOTAL # SEATS    | number    | number      |
| Yes      | numeric metric | total_cost     | TOTAL COST       | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:tzwr-vksx d:2016-06-02T07:47:21.000Z t:borough=MANHATTAN t:district=1 m:ps_is_seats=0 m:is_hs_seats=0 m:is_hs_bldgs=0 m:total_seats=0 m:small_ps_seats=0 m:ps_is_bldgs=0 m:total_cost=0 m:total_bldgs=0 m:small_ps_cost=0 m:small_ps_bldgs=0 m:is_hs_cost=0 m:ps_is_cost=0

series e:tzwr-vksx d:2016-06-02T07:47:21.000Z t:borough=MANHATTAN t:district=2* m:ps_is_seats=1822 m:is_hs_seats=0 m:is_hs_bldgs=0 m:total_seats=3190 m:small_ps_seats=1368 m:ps_is_bldgs=2 m:total_cost=253.34 m:total_bldgs=5 m:small_ps_cost=118.54 m:small_ps_bldgs=3 m:is_hs_cost=0 m:ps_is_cost=134.8

series e:tzwr-vksx d:2016-06-02T07:47:21.000Z t:borough=MANHATTAN t:district=3 m:ps_is_seats=692 m:is_hs_seats=0 m:is_hs_bldgs=0 m:total_seats=692 m:small_ps_seats=0 m:ps_is_bldgs=1 m:total_cost=76.31 m:total_bldgs=1 m:small_ps_cost=0 m:small_ps_bldgs=0 m:is_hs_cost=0 m:ps_is_cost=76.31
```

## Meta Commands

```ls
metric m:small_ps_bldgs p:integer l:"SMALL PS # BLDGS" t:dataTypeName=number

metric m:small_ps_seats p:integer l:"SMALL PS # SEATS" t:dataTypeName=number

metric m:small_ps_cost p:float l:"SMALL PS COST" t:dataTypeName=number

metric m:ps_is_bldgs p:integer l:"PS/IS # BLDGS" t:dataTypeName=number

metric m:ps_is_seats p:integer l:"PS/IS # SEATS" t:dataTypeName=number

metric m:ps_is_cost p:float l:"PS/IS COST" t:dataTypeName=number

metric m:is_hs_bldgs p:integer l:"IS/HS # BLDGS" t:dataTypeName=number

metric m:is_hs_seats p:integer l:"IS/HS # SEATS" t:dataTypeName=number

metric m:is_hs_cost p:float l:"IS/HS COST" t:dataTypeName=number

metric m:total_bldgs p:integer l:"TOTAL # BLDGS" t:dataTypeName=number

metric m:total_seats p:integer l:"TOTAL # SEATS" t:dataTypeName=number

metric m:total_cost p:float l:"TOTAL COST" t:dataTypeName=number

entity e:tzwr-vksx l:"New Capacity Program By Borough" t:attribution="School Construction Authority (SCA)" t:url=https://data.cityofnewyork.us/api/views/tzwr-vksx

property e:tzwr-vksx t:meta.view v:id=tzwr-vksx v:category=Education v:averageRating=0 v:name="New Capacity Program By Borough" v:attribution="School Construction Authority (SCA)"

property e:tzwr-vksx t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:tzwr-vksx t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | district | borough   | small_ps_bldgs | small_ps_seats | small_ps_cost | ps_is_bldgs | ps_is_seats | ps_is_cost | is_hs_bldgs | is_hs_seats | is_hs_cost | total_bldgs | total_seats | total_cost | 
| =========== | ======== | ========= | ============== | ============== | ============= | =========== | =========== | ========== | =========== | =========== | ========== | =========== | =========== | ========== | 
| 1464853641  | 1        | MANHATTAN | 0              | 0              | 0             | 0           | 0           | 0          | 0           | 0           | 0          | 0           | 0           | 0          | 
| 1464853641  | 2*       | MANHATTAN | 3              | 1368           | 118.54        | 2           | 1822        | 134.8      | 0           | 0           | 0          | 5           | 3190        | 253.34     | 
| 1464853641  | 3        | MANHATTAN | 0              | 0              | 0             | 1           | 692         | 76.31      | 0           | 0           | 0          | 1           | 692         | 76.31      | 
| 1464853641  | 4        | MANHATTAN | 0              | 0              | 0             | 0           | 0           | 0          | 0           | 0           | 0          | 0           | 0           | 0          | 
| 1464853641  | 5        | MANHATTAN | 0              | 0              | 0             | 0           | 0           | 0          | 0           | 0           | 0          | 0           | 0           | 0          | 
| 1464853641  | 6        | MANHATTAN | 0              | 0              | 0             | 0           | 0           | 0          | 0           | 0           | 0          | 0           | 0           | 0          | 
| 1464853641  | 7        | BRONX     | 1              | 456            | 38.55         | 0           | 0           | 0          | 0           | 0           | 0          | 1           | 456         | 38.55      | 
| 1464853641  | 8        | BRONX     | 2              | 456            | 63.68         | 0           | 0           | 0          | 0           | 0           | 0          | 2           | 456         | 63.68      | 
| 1464853641  | 9        | BRONX     | 0              | 0              | 0             | 0           | 0           | 0          | 0           | 0           | 0          | 0           | 0           | 0          | 
| 1464853641  | 10       | BRONX     | 3              | 1412           | 175.04        | 2           | 1604        | 135.25     | 0           | 0           | 0          | 5           | 3016        | 310.29     | 
```