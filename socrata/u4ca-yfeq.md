# Graffiti

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/graffiti-2912b) |
| Metadata | [Link](https://data.illinois.gov/api/views/u4ca-yfeq) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/u4ca-yfeq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/u4ca-yfeq/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | u4ca-yfeq |
| Name | Graffiti |
| Attribution | City of Rockford |
| Category | Municipality |
| Created | 2013-01-17T17:11:16Z |
| Publication Date | 2013-01-17T17:14:11Z |

## Description

City of Rockford graffiti abatement requests

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type     | Render Type   |
| ======== | ============== | ================ | ================ | ============= | ============= |
| Yes      | numeric metric | servno           | SERVNO           | number        | number        |
| Yes      | time           | request_date     | Request Date     | calendar_date | calendar_date |
| No       |                | resolved_date    | Resolved Date    | calendar_date | calendar_date |
| Yes      | series tag     | addrtype         | AddrType         | text          | text          |
| No       |                | address          | Address          | text          | text          |
| Yes      | series tag     | crossstreet      | CrossStreet      | text          | text          |
| Yes      | series tag     | graffititype     | GraffitiType     | text          | text          |
| Yes      | series tag     | graffitimoniker  | GraffitiMoniker  | text          | text          |
| Yes      | series tag     | graffitimoniker2 | GraffitiMoniker2 | text          | text          |
| Yes      | series tag     | graffitimoniker3 | GraffitiMoniker3 | text          | text          |
| No       |                | latitude         | Latitude         | number        | number        |
| No       |                | longitude        | Longitude        | number        | number        |
```

## Time Field

```ls
Value = request_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = resolved_date,address,latitude,longitude
```

## Data Commands

```ls
series e:u4ca-yfeq d:2007-01-31T00:00:00.000Z t:addrtype=A m:servno=1482

series e:u4ca-yfeq d:2007-01-30T00:00:00.000Z t:addrtype=I t:crossstreet="SANFORD ST ROCKFORD IL 61102" t:graffititype=Gang m:servno=1483

series e:u4ca-yfeq d:2007-01-19T00:00:00.000Z t:addrtype=A m:servno=1484
```

## Meta Commands

```ls
metric m:servno p:integer l:SERVNO t:dataTypeName=number

entity e:u4ca-yfeq l:Graffiti t:attribution="City of Rockford" t:url=https://data.illinois.gov/api/views/u4ca-yfeq

property e:u4ca-yfeq t:meta.view v:id=u4ca-yfeq v:category=Municipality v:averageRating=0 v:name=Graffiti v:attribution="City of Rockford"

property e:u4ca-yfeq t:meta.view.owner v:id=hdqp-matg v:profileImageUrlMedium=/api/users/hdqp-matg/profile_images/THUMB v:profileImageUrlLarge=/api/users/hdqp-matg/profile_images/LARGE v:screenName=Glenn v:profileImageUrlSmall=/api/users/hdqp-matg/profile_images/TINY v:displayName=Glenn

property e:u4ca-yfeq t:meta.view.tableauthor v:id=hdqp-matg v:profileImageUrlMedium=/api/users/hdqp-matg/profile_images/THUMB v:profileImageUrlLarge=/api/users/hdqp-matg/profile_images/LARGE v:screenName=Glenn v:profileImageUrlSmall=/api/users/hdqp-matg/profile_images/TINY v:roleName=publisher v:displayName=Glenn
```

## Top Records

```ls
| servno | request_date        | resolved_date       | addrtype | address                              | crossstreet                     | graffititype | graffitimoniker | graffitimoniker2 | graffitimoniker3 | latitude | longitude | 
| ====== | =================== | =================== | ======== | ==================================== | =============================== | ============ | =============== | ================ | ================ | ======== | ========= | 
| 1482   | 2007-01-31T00:00:00 | 2007-03-13T00:00:00 | A        | 120 W STATE ST ROCKFORD IL 61101     |                                 |              |                 |                  |                  | 42.2706  | -89.0930  | 
| 1483   | 2007-01-30T00:00:00 | 2007-02-13T00:00:00 | I        | LOOMIS ST ROCKFORD IL 61102          | SANFORD ST ROCKFORD IL 61102    | Gang         |                 |                  |                  | 42.2617  | -89.1108  | 
| 1484   | 2007-01-19T00:00:00 | 2007-02-27T00:00:00 | A        | 2929 KISHWAUKEE ST ROCKFORD IL 61109 |                                 |              |                 |                  |                  | 42.2305  | -89.0874  | 
| 1485   | 2007-01-19T00:00:00 | 2007-04-24T00:00:00 | I        | DEMPSTER AVE ROCKFORD IL 61108       | LEXINGTON WAY ROCKFORD IL 61108 | Gang         |                 |                  |                  | 42.2568  | -89.0327  | 
| 1486   | 2007-01-19T00:00:00 | 2007-03-29T00:00:00 | A        | 2903 CUSTER AVE ROCKFORD IL 61101    |                                 |              |                 |                  |                  | 42.2946  | -89.1022  | 
| 1487   | 2007-01-19T00:00:00 | 2007-03-13T00:00:00 | A        | 1007 S MAIN ST ROCKFORD IL 61101     |                                 | Gang         |                 |                  |                  | 42.2628  | -89.1005  | 
| 1488   | 2007-01-19T00:00:00 | 2007-03-15T00:00:00 | A        | 1302 MORGAN ST ROCKFORD IL 61102     |                                 | Gang         |                 |                  |                  | 42.2629  | -89.1152  | 
| 1489   | 2007-01-19T00:00:00 | 2007-03-22T00:00:00 | A        | 1224 BROADWAY ROCKFORD IL 61104      |                                 | Gang         |                 |                  |                  | 42.2526  | -89.0779  | 
| 1490   | 2007-01-30T00:00:00 | 2007-03-22T00:00:00 | A        | 1653 5TH AVE ROCKFORD IL 61104       |                                 | Gang         |                 |                  |                  | 42.2613  | -89.0684  | 
| 1491   | 2007-01-22T00:00:00 | 2007-01-25T00:00:00 | A        | 126 WELTY AVE ROCKFORD IL 61107      |                                 |              |                 |                  |                  | 42.2679  | -89.0573  | 
```