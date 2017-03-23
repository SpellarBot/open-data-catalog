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
| Rows Updated | 2017-03-22T07:07:56Z |

## Description

Listing of all formal upcoming bid openings and past bid tabulation results processed by the City-Parish Purchasing Division.

## Columns

```ls
| Included | Schema Type | Field Name      | Name                    | Data Type     | Render Type   |
| ======== | =========== | =============== | ======================= | ============= | ============= |
| No       |             | bid_date        | BID DATE                | calendar_date | calendar_date |
| No       |             | bid_time        | BID TIME                | text          | text          |
| Yes      | series tag  | department_name | DEPARTMENT              | text          | text          |
| Yes      | series tag  | division_name   | DIVISION                | text          | text          |
| Yes      | series tag  | description     | DESCRIPTION             | text          | text          |
| Yes      | series tag  | contact_name    | PROJECT CONTACT         | text          | text          |
| Yes      | series tag  | phone           | PROJECT PHONE           | text          | text          |
| Yes      | series tag  | phone_ext       | PROJECT PHONE EXTENSION | text          | text          |
| Yes      | series tag  | buyer_name      | BUYER NAME              | text          | text          |
| Yes      | series tag  | room_number     | ROOM NUMBER             | text          | text          |
| Yes      | series tag  | note            | NOTE                    | text          | text          |
| Yes      | series tag  | bid_results     | BID RESULTS             | url           | url           |
| Yes      | series tag  | unique_id       | UNIQUE ID               | text          | number        |
```

## Time Field

```ls
Value = bid_date-bid_time
Format & Zone = yyyy-MM-dd'T'HH:mm:ss-hh:mm a
```

## Series Fields

```ls
Excluded Fields = bid_time,bid_date
```

## Data Commands

```ls
series e:u9zk-8nix d:2015-06-25T11:00:00.000Z t:unique_id=14363 t:phone_ext=323 t:room_number=806 t:phone=225-389-3259 t:description="RQ038473 MEN'S SNAG RESISTANT MOISTURE WICKING POLO SHIRTS" t:contact_name="Dexter Stewart" t:buyer_name="Dexter Stewart" t:department_name="FIRE DEPARTMENT" t:division_name="FIRE DEPARTMENT-ADMINISTRATION" t:note="ALL ITEMS TO BID AS ALL OR NONE" m:row_number.u9zk-8nix=1

series e:u9zk-8nix d:2014-10-09T11:00:00.000Z t:unique_id=13606 t:phone_ext=323 t:room_number=806 t:phone=225-389-3259 t:description="Central Garage Wrecker Service for Vehicles/Equipment
up to and including 10,000 GVW" t:contact_name="Lori Foreman" t:buyer_name="Dexter Stewart" t:department_name="DEPARTMENT OF PUBLIC WORKS" t:division_name="CENTRAL GARAGE-OPERATIONS and MAINTENANCE" t:note="Addendum No. 1 Added" m:row_number.u9zk-8nix=2

series e:u9zk-8nix d:2013-03-18T11:00:00.000Z t:unique_id=11882 t:room_number=308 t:phone=225-389-3259 t:bid_results="http://brgov.com/dept/purchase/loadbidresults.asp?GetBid=11882" t:description="Sealed Bid for a Server and Workstation for In-Car Cameras for the Police Department

File # 01021-13" t:contact_name="Brandon Malbrough" t:buyer_name="Arielle Williams" t:department_name="POLICE DEPARTMENT" t:division_name="POLICE DEPARTMENT-UNIFORM PATROL BUREAU" m:row_number.u9zk-8nix=3
```

## Meta Commands

```ls
metric m:row_number.u9zk-8nix p:long l:"Row Number"

entity e:u9zk-8nix l:"Bid Openings and Results" t:attribution=Purchasing t:url=https://data.brla.gov/api/views/u9zk-8nix

property e:u9zk-8nix t:meta.view v:id=u9zk-8nix v:category=Government v:attributionLink=http://www.brgov.com/dept/purchase/bids.asp v:averageRating=0 v:name="Bid Openings and Results" v:attribution=Purchasing

property e:u9zk-8nix t:meta.view.license v:name="Public Domain"

property e:u9zk-8nix t:meta.view.owner v:id=mjn2-v86v v:profileImageUrlMedium=/api/users/mjn2-v86v/profile_images/THUMB v:profileImageUrlLarge=/api/users/mjn2-v86v/profile_images/LARGE v:screenName="Open Data BR" v:profileImageUrlSmall=/api/users/mjn2-v86v/profile_images/TINY v:displayName="Open Data BR"

property e:u9zk-8nix t:meta.view.tableauthor v:id=mjn2-v86v v:profileImageUrlMedium=/api/users/mjn2-v86v/profile_images/THUMB v:profileImageUrlLarge=/api/users/mjn2-v86v/profile_images/LARGE v:screenName="Open Data BR" v:profileImageUrlSmall=/api/users/mjn2-v86v/profile_images/TINY v:roleName=viewer v:displayName="Open Data BR"
```