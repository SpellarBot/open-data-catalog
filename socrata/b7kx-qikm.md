# 2012 NYC Farmers Market List

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2012-nyc-farmers-market-list-5197b) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/b7kx-qikm) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/b7kx-qikm/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/b7kx-qikm/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | b7kx-qikm |
| Name | 2012 NYC Farmers Market List |
| Attribution | Department of Health and Mental Hygiene (DOHMH) |
| Category | Business |
| Tags | 2012 nyc market list, dohmh, farmers market, green, food, health, healthy living |
| Created | 2012-06-26T15:29:07Z |
| Publication Date | 2013-06-21T19:27:16Z |

## Description

Listing of NYC farmers markets.

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type | Render Type |
| ======== | ============== | ======================= | ======================= | ========= | =========== |
| Yes      | series tag     | borough                 | Borough                 | text      | text        |
| Yes      | series tag     | market_name             | Market Name             | text      | text        |
| Yes      | series tag     | street_address          | Street Address          | text      | text        |
| Yes      | series tag     | day_s                   | Day(s)                  | text      | text        |
| Yes      | series tag     | hours                   | Hours                   | text      | text        |
| Yes      | numeric metric | distribute_health_bucks | Distribute Health Bucks | number    | number      |
| Yes      | numeric metric | accepts_health_bucks    | Accepts Health Bucks    | number    | number      |
| Yes      | numeric metric | ebt                     | EBT                     | number    | number      |
| Yes      | numeric metric | stellar                 | Stellar                 | number    | number      |
```

## Time Field

```ls
Value = 2012
Format & Zone = yyyy
```

## Data Commands

```ls
series e:b7kx-qikm d:2012-01-01T00:00:00.000Z t:market_name="Bissel Gardens Farmers' Market" t:hours=9am-5pm t:borough=Bronx t:day_s="Wednesday & Saturday" t:street_address="Baychester Ave & E 241st St" m:ebt=1 m:stellar=0 m:accepts_health_bucks=1 m:distribute_health_bucks=1

series e:b7kx-qikm d:2012-01-01T00:00:00.000Z t:market_name="Bronx Borough Hall Greenmarket" t:hours=8am-4pm t:borough=Bronx t:day_s=Tuesday t:street_address="Grand Concourse bet 161st & 162nd Sts" m:ebt=1 m:stellar=1 m:accepts_health_bucks=1 m:distribute_health_bucks=1

series e:b7kx-qikm d:2012-01-01T00:00:00.000Z t:market_name="Crotona Park Greenmarket" t:hours=8am-3pm t:borough=Bronx t:day_s=Saturday t:street_address="Crotona Park South & Clinton Ave, in Crotona Park" m:ebt=1 m:stellar=1 m:accepts_health_bucks=1 m:distribute_health_bucks=1
```

## Meta Commands

```ls
metric m:distribute_health_bucks p:integer l:"Distribute Health Bucks" t:dataTypeName=number

metric m:accepts_health_bucks p:integer l:"Accepts Health Bucks" t:dataTypeName=number

metric m:ebt p:integer l:EBT t:dataTypeName=number

metric m:stellar p:integer l:Stellar t:dataTypeName=number

entity e:b7kx-qikm l:"2012 NYC Farmers Market List" t:attribution="Department of Health and Mental Hygiene (DOHMH)" t:url=https://data.cityofnewyork.us/api/views/b7kx-qikm

property e:b7kx-qikm t:meta.view v:id=b7kx-qikm v:category=Business v:averageRating=0 v:name="2012 NYC Farmers Market List" v:attribution="Department of Health and Mental Hygiene (DOHMH)"

property e:b7kx-qikm t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:b7kx-qikm t:meta.view.tableauthor v:id=txun-eb7e v:screenName="Albert Webber" v:roleName=administrator v:displayName="Albert Webber"
```

## Top Records

```ls
| borough | market_name                                      | street_address                                    | day_s                | hours   | distribute_health_bucks | accepts_health_bucks | ebt | stellar | 
| ======= | ================================================ | ================================================= | ==================== | ======= | ======================= | ==================== | === | ======= | 
| Bronx   | Bissel Gardens Farmers' Market                   | Baychester Ave & E 241st St                       | Wednesday & Saturday | 9am-5pm | 1                       | 1                    | 1   | 0       | 
| Bronx   | Bronx Borough Hall Greenmarket                   | Grand Concourse bet 161st & 162nd Sts             | Tuesday              | 8am-4pm | 1                       | 1                    | 1   | 1       | 
| Bronx   | Crotona Park Greenmarket                         | Crotona Park South & Clinton Ave, in Crotona Park | Saturday             | 8am-3pm | 1                       | 1                    | 1   | 1       | 
| Bronx   | Harvest Home Co-op City Farmers' Market          | 140 Bellamy Loop                                  | Saturday             | 8am-4pm | 1                       | 1                    | 1   | 0       | 
| Bronx   | Harvest Home Echo Park Market                    | Ryer & Burnside Aves                              | Wednesday            | 8am-4pm | 1                       | 1                    | 1   | 0       | 
| Bronx   | Harvest Home Forest Avenue Farmers' Market       | Forest Ave bet Westchester Ave & 156th St         | Wednesday            | 8am-4pm | 1                       | 1                    | 1   | 0       | 
| Bronx   | Harvest Home Jacobi Hospital Farmers' Market     | 1400 Pelham Pkwy at Eastchester Rd                | Tuesday              | 8am-4pm | 1                       | 1                    | 1   | 0       | 
| Bronx   | Harvest Home Jerome Avenue Market                | Plaza Dr bet 170th St & Elliot Pl                 | Friday               | 8am-4pm | 1                       | 1                    | 1   | 0       | 
| Bronx   | Harvest Home Mt. Eden Farmers' Market            | Mt. Eden & Morris Aves, at Claremont Park         | Thursday             | 8am-4pm | 1                       | 1                    | 1   | 0       | 
| Bronx   | Harvest Home North Central Bronx Farmers' Market | Mosholu Pkwy & Jerome Ave                         | Wednesday            | 8am-4pm | 1                       | 1                    | 1   | 0       | 
```