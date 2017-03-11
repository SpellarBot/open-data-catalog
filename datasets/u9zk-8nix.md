# Bid Openings and Results

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/bid-openings-and-results) |
| Metadata | [Link](https://data.brla.gov/api/views/u9zk-8nix) |
| Data: JSON | [100 Rows](https://data.brla.gov/api/views/u9zk-8nix/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.brla.gov/api/views/u9zk-8nix/rows.csv?max_rows=100) |
| Host | data.brla.gov |
| Id | u9zk-8nix |
| Name | Bid Openings and Results |
| Attribution | Purchasing |
| Category | Government |
| Tags | procurement, bids, purchasing |
| Created | 2015-03-08T04:46:07Z |
| Publication Date | 2015-07-07T14:27:39Z |
| Rows Updated | 2017-03-10T08:05:52Z |

## Description

Listing of all formal upcoming bid openings and past bid tabulation results processed by the City-Parish Purchasing Division.

## Columns

```ls
| Included | Schema Type    | Field Name      | Name                    | Data Type     | Render Type   |
| ======== | ============== | =============== | ======================= | ============= | ============= |
| Yes      | time           | bid_date        | BID DATE                | calendar_date | calendar_date |
| Yes      | series tag     | bid_time        | BID TIME                | text          | text          |
| Yes      | series tag     | department_name | DEPARTMENT              | text          | text          |
| Yes      | series tag     | division_name   | DIVISION                | text          | text          |
| Yes      | series tag     | description     | DESCRIPTION             | text          | text          |
| Yes      | series tag     | contact_name    | PROJECT CONTACT         | text          | text          |
| Yes      | series tag     | phone           | PROJECT PHONE           | text          | text          |
| Yes      | numeric metric | phone_ext       | PROJECT PHONE EXTENSION | number        | text          |
| Yes      | series tag     | buyer_name      | BUYER NAME              | text          | text          |
| Yes      | numeric metric | room_number     | ROOM NUMBER             | number        | text          |
| Yes      | series tag     | note            | NOTE                    | text          | text          |
| Yes      | series tag     | bid_results     | BID RESULTS             | url           | url           |
| Yes      | series tag     | unique_id       | UNIQUE ID               | text          | number        |
```

## Time Field

```ls
Value = bid_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:u9zk-8nix d:2015-06-25T00:00:00.000Z t:unique_id=14363 t:bid_time="11:00 AM" t:phone=225-389-3259 t:description="RQ038473 MEN'S SNAG RESISTANT MOISTURE WICKING POLO SHIRTS" t:contact_name="Dexter Stewart" t:buyer_name="Dexter Stewart" t:division_name="FIRE DEPARTMENT-ADMINISTRATION" t:department_name="FIRE DEPARTMENT" t:note="ALL ITEMS TO BID AS ALL OR NONE" m:phone_ext=323 m:room_number=806

series e:u9zk-8nix d:2014-10-09T00:00:00.000Z t:unique_id=13606 t:bid_time="11:00 AM" t:phone=225-389-3259 t:description="Central Garage Wrecker Service for Vehicles/Equipment

series e:u9zk-8nix d:2013-03-18T00:00:00.000Z t:unique_id=11882 t:bid_time="11:00 AM" t:phone=225-389-3259 t:description="Sealed Bid for a Server and Workstation for In-Car Cameras for the Police Department
```

## Meta Commands

```ls
metric m:phone_ext p:integer l:"PROJECT PHONE EXTENSION" d:"Phone number extension for the project" t:dataTypeName=number

metric m:room_number p:integer l:"ROOM NUMBER" d:"Room number where bid opening will be held" t:dataTypeName=number

entity e:u9zk-8nix l:"Bid Openings and Results" t:attribution=Purchasing t:url=https://data.brla.gov/api/views/u9zk-8nix

property e:u9zk-8nix t:meta.view d:2017-03-10T16:13:17.494Z v:id=u9zk-8nix v:category=Government v:attributionLink=http://www.brgov.com/dept/purchase/bids.asp v:averageRating=0 v:name="Bid Openings and Results" v:attribution=Purchasing

property e:u9zk-8nix t:meta.view.license d:2017-03-10T16:13:17.494Z v:name="Public Domain"

property e:u9zk-8nix t:meta.view.owner d:2017-03-10T16:13:17.494Z v:id=mjn2-v86v v:profileImageUrlMedium=/api/users/mjn2-v86v/profile_images/THUMB v:profileImageUrlLarge=/api/users/mjn2-v86v/profile_images/LARGE v:screenName="Open Data BR" v:profileImageUrlSmall=/api/users/mjn2-v86v/profile_images/TINY v:roleName=viewer v:displayName="Open Data BR"

property e:u9zk-8nix t:meta.view.tableauthor d:2017-03-10T16:13:17.494Z v:id=mjn2-v86v v:profileImageUrlMedium=/api/users/mjn2-v86v/profile_images/THUMB v:profileImageUrlLarge=/api/users/mjn2-v86v/profile_images/LARGE v:screenName="Open Data BR" v:profileImageUrlSmall=/api/users/mjn2-v86v/profile_images/TINY v:roleName=viewer v:displayName="Open Data BR"
```