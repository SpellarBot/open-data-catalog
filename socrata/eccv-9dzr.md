# CURRENT BASES

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/current-bases) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/eccv-9dzr) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/eccv-9dzr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/eccv-9dzr/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | eccv-9dzr |
| Name | CURRENT BASES |
| Attribution | Taxi and Limousine Commission (TLC) |
| Category | Transportation |
| Created | 2015-04-21T17:43:01Z |
| Publication Date | 2017-03-08T19:39:22Z |

## Description

CURRENT BASES

## Columns

```ls
| Included | Schema Type | Field Name       | Name             | Data Type     | Render Type   |
| ======== | =========== | ================ | ================ | ============= | ============= |
| Yes      | series tag  | license_number   | License Number   | text          | text          |
| Yes      | series tag  | entity_name      | Entity Name      | text          | text          |
| Yes      | series tag  | telephone_number | Telephone Number | text          | text          |
| Yes      | series tag  | shl_endorsed     | SHL Endorsed     | text          | text          |
| Yes      | series tag  | building         | Building         | text          | text          |
| Yes      | series tag  | street           | Street           | text          | text          |
| Yes      | series tag  | city             | City             | text          | text          |
| Yes      | series tag  | state            | State            | text          | text          |
| Yes      | series tag  | zip              | Zip              | text          | text          |
| Yes      | series tag  | type_of_base     | Type of Base     | text          | text          |
| No       |             | latitude         | Latitude         | number        | number        |
| No       |             | longitude        | Longitude        | number        | number        |
| Yes      | time        | date             | Date             | calendar_date | calendar_date |
| Yes      | series tag  | time             | Time             | text          | text          |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = latitude,longitude
```

## Data Commands

```ls
series e:eccv-9dzr d:2017-04-14T00:00:00.000Z t:type_of_base="COMMUTER VAN AUTHORITY BASE" t:zip=11434 t:time=17:00:14 t:entity_name="CITY EXPRESS CORP" t:telephone_number=8886468666 t:building=152-32 t:license_number=B80028 t:street="ROCKAWAY BLVD  #205" t:state=NY t:shl_endorsed=No t:city=JAMAICA m:row_number.eccv-9dzr=1

series e:eccv-9dzr d:2017-04-14T00:00:00.000Z t:type_of_base="LIVERY BASE" t:zip=10002 t:time=17:00:14 t:entity_name="DELANCEY CAR SERVICE INC." t:telephone_number=2122283301 t:building=29 t:license_number=B00225 t:street="ESSEX STREET  NORTH STORE" t:state=NY t:shl_endorsed=No t:city="NEW YORK" m:row_number.eccv-9dzr=2

series e:eccv-9dzr d:2017-04-14T00:00:00.000Z t:type_of_base="COMMUTER VAN AUTHORITY BASE" t:zip=11422 t:time=17:00:14 t:entity_name="COMMUNITY TRANSPORTATION SYSTEMS, CORP" t:telephone_number=7185275500 t:building=157-11 t:license_number=B80087 t:street="ROCKAWAY BLVD" t:state=NY t:shl_endorsed=No t:city=JAMAICA m:row_number.eccv-9dzr=3
```

## Meta Commands

```ls
metric m:row_number.eccv-9dzr p:long l:"Row Number"

entity e:eccv-9dzr l:"CURRENT BASES" t:attribution="Taxi and Limousine Commission (TLC)" t:url=https://data.cityofnewyork.us/api/views/eccv-9dzr

property e:eccv-9dzr t:meta.view v:id=eccv-9dzr v:category=Transportation v:averageRating=0 v:name="CURRENT BASES" v:attribution="Taxi and Limousine Commission (TLC)"

property e:eccv-9dzr t:meta.view.license v:name="Public Domain"

property e:eccv-9dzr t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:eccv-9dzr t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| license_number | entity_name                            | telephone_number | shl_endorsed | building | street                   | city          | state | zip   | type_of_base                | latitude  | longitude  | date                | time     | 
| ============== | ====================================== | ================ | ============ | ======== | ======================== | ============= | ===== | ===== | =========================== | ========= | ========== | =================== | ======== | 
| B80028         | CITY EXPRESS CORP                      | 8886468666       | No           | 152-32   | ROCKAWAY BLVD #205       | JAMAICA       | NY    | 11434 | COMMUTER VAN AUTHORITY BASE | 40.671623 | -73.785164 | 2017-04-14T00:00:00 | 17:00:14 | 
| B00225         | DELANCEY CAR SERVICE INC.              | 2122283301       | No           | 29       | ESSEX STREET NORTH STORE | NEW YORK      | NY    | 10002 | LIVERY BASE                 | 44.049572 | -73.459721 | 2017-04-14T00:00:00 | 17:00:14 | 
| B80087         | COMMUNITY TRANSPORTATION SYSTEMS, CORP | 7185275500       | No           | 157-11   | ROCKAWAY BLVD            | JAMAICA       | NY    | 11422 | COMMUTER VAN AUTHORITY BASE | 40.666206 | -73.778903 | 2017-04-14T00:00:00 | 17:00:14 | 
| B01177         | SLMK INC.                              | 7189801111       | No           | 658      | NEW DORP LANE            | STATEN ISLAND | NY    | 10306 | LIVERY BASE                 | 40.566361 | -74.10189  | 2017-04-14T00:00:00 | 17:00:14 | 
| B02667         | LEON LUXURY LIMO INC                   | 7186265300       | No           | 21-02    | 23 STREET                | ASTORIA       | NY    | 11105 | LUXURY/LIMOUSINE            | 40.781591 | -73.91386  | 2017-04-14T00:00:00 | 17:00:14 | 
| B02725         | KIRIN TRANSPORTATION INC               | 7185268888       | No           | 131-10   | 40TH RD 2 FL             | FLUSHING      | NY    | 11354 | BLACK CAR BASE              | 40.755756 | -73.836021 | 2017-04-14T00:00:00 | 17:00:14 | 
| B01731         | ROSEDALE BASE CAR SERVICE CORP.        | 7185283434       | No           | 139-15   | FRANCIS LEWIS BOULEVARD  | ROSEDALE      | NY    | 11422 | LIVERY BASE                 | 40.666272 | -73.735806 | 2017-04-14T00:00:00 | 17:00:14 | 
| B00078         | R & R ROAD LIMO SVCE INC               | 7185858500       | No           | 865      | EAST 138 STREET          | BRONX         | NY    | 10454 | LUXURY/LIMOUSINE            | 40.803251 | -73.90843  | 2017-04-14T00:00:00 | 17:00:14 | 
| B01777         | PREMIUM RADIO DISP & MULTI SVC         | 2126942222       | Yes          | 425      | EDGECOMBE AVENUE         | NEW YORK      | NY    | 10032 | LIVERY BASE                 | 40.82983  | -73.94008  | 2017-04-14T00:00:00 | 17:00:14 | 
| B01280         | BENSONHURST RIDE INC.                  | 7189461111       | No           | 2134     | 86 STREET                | BROOKLYN      | NY    | 11214 | LIVERY BASE                 | 40.602721 | -73.99516  | 2017-04-14T00:00:00 | 17:00:14 | 
```