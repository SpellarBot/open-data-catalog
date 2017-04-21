# Directory Of Competitive Bid

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/directory-of-competitive-bid-e526a) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/2eq2-trdu) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/2eq2-trdu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/2eq2-trdu/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 2eq2-trdu |
| Name | Directory Of Competitive Bid |
| Attribution | Department of Design and Construction (DDC) |
| Category | Housing & Development |
| Tags | department of design and construction, ddc, competitive, bids |
| Created | 2013-03-06T13:33:35Z |
| Publication Date | 2013-06-21T20:48:44Z |

## Description

This table displays currently advertised projects (type of work), estimated range ($) for project completion, bid date, time and projects description along with Project ID. It also provides link to plan holders information.

## Columns

```ls
| Included | Schema Type | Field Name      | Name                 | Data Type | Render Type |
| ======== | =========== | =============== | ==================== | ========= | =========== |
| No       | time        | :updated_at     | updated_at           | meta_data | meta_data   |
| No       |             | _               | #                    | number    | number      |
| Yes      | series tag  | type_of_work    | TYPE OF WORK         | text      | text        |
| Yes      | series tag  | estimated_range | ESTIMATED $ RANGE    | text      | text        |
| No       |             | bid_date_time   | BID DATE & TIME      | text      | text        |
| Yes      | series tag  | pin             | PIN                  | text      | text        |
| Yes      | series tag  | proj_id         | PROJ ID              | text      | text        |
| Yes      | series tag  | description     | DESCRIPTION          | text      | text        |
| Yes      | series tag  | plan_holders    | PLAN HOLDERS         | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = _,bid_date_time
```

## Data Commands

```ls
series e:2eq2-trdu d:2013-03-06T05:33:40.000Z t:estimated_range=$5,000,000-$10,000,000 t:plan_holders="http://ddcftp.nyc.gov/biddoc/list.aspx?bid_id=1144" t:pin=8502012TR0004C t:description="HARPER STREET YARD CONSTRUCTION OF NEW DIESEL STATION, ELECTRICAL, ROOF & FLOOR UPDGRADE - BOROUGH OF QUEENS" t:type_of_work=Construction/ t:proj_id=HWQF027C m:row_number.2eq2-trdu=1

series e:2eq2-trdu d:2013-03-06T05:33:40.000Z t:type_of_work=Regular/ m:row_number.2eq2-trdu=2

series e:2eq2-trdu d:2013-03-06T05:33:40.000Z t:type_of_work="General Construction/" m:row_number.2eq2-trdu=3
```

## Meta Commands

```ls
metric m:row_number.2eq2-trdu p:long l:"Row Number"

entity e:2eq2-trdu l:"Directory Of Competitive Bid" t:attribution="Department of Design and Construction (DDC)" t:url=https://data.cityofnewyork.us/api/views/2eq2-trdu

property e:2eq2-trdu t:meta.view v:id=2eq2-trdu v:category="Housing & Development" v:attributionLink=http://ddcftp.nyc.gov/inet/html/contrbid.asp v:averageRating=0 v:name="Directory Of Competitive Bid" v:attribution="Department of Design and Construction (DDC)"

property e:2eq2-trdu t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:2eq2-trdu t:meta.view.tableauthor v:id=iacr-duv5 v:screenName=Tejas.Patel v:displayName=Tejas.Patel
```

## Top Records

```ls
| :updated_at | _ | type_of_work          | estimated_range        | bid_date_time | pin            | proj_id   | description                                                                                                                                                                                                              | plan_holders                                       | 
| =========== | = | ===================== | ====================== | ============= | ============== | ========= | ======================================================================================================================================================================================================================== | ================================================== | 
| 1362548020  | 1 | Construction/         | $5,000,000-$10,000,000 | 3/7/13        | 8502012TR0004C | HWQF027C  | HARPER STREET YARD CONSTRUCTION OF NEW DIESEL STATION, ELECTRICAL, ROOF & FLOOR UPDGRADE - BOROUGH OF QUEENS                                                                                                             | http://ddcftp.nyc.gov/biddoc/list.aspx?bid_id=1144 | 
| 1362548020  |   | Regular/              |                        | 2:00 PM       |                |           |                                                                                                                                                                                                                          |                                                    | 
| 1362548020  |   | General Construction/ |                        |               |                |           |                                                                                                                                                                                                                          |                                                    | 
| 1362548020  | 2 | Construction/         | OVER 10 MILLION        | 3/20/13       | 8502013PV0004C | P-1CROT16 | NEW CONSTRUCTION OF THE BRONX RIVER HOUSE                                                                                                                                                                                | http://ddcftp.nyc.gov/biddoc/list.aspx?bid_id=1149 | 
| 1362548020  |   | Regular/              |                        | 2:00 PM       |                |           |                                                                                                                                                                                                                          |                                                    | 
| 1362548020  |   | General Construction/ |                        |               |                |           |                                                                                                                                                                                                                          |                                                    | 
| 1362548020  | 3 | Construction/         | $1,000,000-$2,499,999  | 3/21/13       | 8502012PV0015C | PV467DCTV | DOWNTOWN COMMUNITY TELEVISION CENTER: SCREENING ROOM RENOVATION - BOROUGH OF MANHATTAN                                                                                                                                   | http://ddcftp.nyc.gov/biddoc/list.aspx?bid_id=1155 | 
| 1362548020  |   | Regular/              |                        | 2:00 PM       |                |           |                                                                                                                                                                                                                          |                                                    | 
| 1362548020  |   | General Construction/ |                        |               |                |           |                                                                                                                                                                                                                          |                                                    | 
| 1362548020  | 4 | Construction/         | $5,000,000-$10,000,000 | 3/13/13       | 8502013WM0004C | QED1015   | INSTALLATION OF WATER MAINS AND APPURTENANCES FOR NEW BUILDING CONSTRUCTION AND FOR IMPROVEMENT TO THE CITY'S WATER MAIN DISTRIBUTION SYSTEM AND FIRE PROTECTION IN VARIOUS LOCATIONS - BOROUGHS OF QUEENS AND THE BRONX | http://ddcftp.nyc.gov/biddoc/list.aspx?bid_id=1156 | 
```