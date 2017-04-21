# Bicycle Rack Requests

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/bicycle-rack-requests) |
| Metadata | [Link](https://data.austintexas.gov/api/views/5tx2-pk4n) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/5tx2-pk4n/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/5tx2-pk4n/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | 5tx2-pk4n |
| Name | Bicycle Rack Requests |
| Attribution | City of Austin |
| Tags | bicycle, racks |
| Created | 2012-05-04T13:52:49Z |
| Publication Date | 2012-05-04T13:55:26Z |

## Description

This is a list of bicycle racks installed and/or distributed by the City of Austin Bicycle Program.

## Columns

```ls
| Included | Schema Type    | Field Name                | Name                      | Data Type     | Render Type   |
| ======== | ============== | ========================= | ========================= | ============= | ============= |
| Yes      | time           | request_date              | Request Date              | calendar_date | calendar_date |
| Yes      | series tag     | location                  | Location                  | text          | text          |
| Yes      | series tag     | install                   | Install?                  | text          | text          |
| Yes      | series tag     | requestor                 | Requestor                 | text          | text          |
| Yes      | numeric metric | galv_1                    | Galv                      | number        | number        |
| Yes      | numeric metric | green_1                   | Green                     | number        | number        |
| Yes      | numeric metric | cables_1                  | Cables                    | number        | text          |
| Yes      | series tag     | galv_2                    | Galv                      | text          | text          |
| Yes      | series tag     | green_2                   | Green                     | text          | text          |
| Yes      | series tag     | cables_2                  | Cables                    | text          | text          |
| Yes      | series tag     | delivered                 | Delivered                 | text          | text          |
| Yes      | series tag     | installed                 | Installed                 | text          | text          |
| Yes      | series tag     | central_buisness_district | Central Buisness District | text          | text          |
| Yes      | numeric metric | cbd_of_racks              | CBD #of Racks             | number        | number        |
| Yes      | numeric metric | gis_id2                   | GIS ID2                   | number        | number        |
| No       |                | x                         | x                         | number        | number        |
| No       |                | y                         | y                         | number        | number        |
```

## Time Field

```ls
Value = request_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = x,y
```

## Data Commands

```ls
series e:5tx2-pk4n d:2005-10-21T00:00:00.000Z t:install=Delivered t:delivered=10/26 t:location="Texas Healing Arts Institure, 7001 Burnet Rd, 78733" t:installed=1/1 t:green_2=0 t:central_buisness_district=Yes t:galv_2=0 t:requestor=Merchant m:green_1=0 m:cbd_of_racks=0 m:gis_id2=0 m:galv_1=2

series e:5tx2-pk4n d:2005-10-21T00:00:00.000Z t:install=Delivered t:delivered=10/26 t:location="Texas School for the Blind and Visually Impaired
1100 W. 45th St, 78756" m:galv_1=1

series e:5tx2-pk4n d:2005-10-21T00:00:00.000Z t:install=Delivered t:delivered=11/2 t:location="Home Slice Pizza, 1415 S. Congress Ave, 78704" m:galv_1=5
```

## Meta Commands

```ls
metric m:galv_1 p:integer l:Galv t:dataTypeName=number

metric m:green_1 p:integer l:Green t:dataTypeName=number

metric m:cables_1 p:integer l:Cables t:dataTypeName=number

metric m:cbd_of_racks p:integer l:"CBD #of Racks" t:dataTypeName=number

metric m:gis_id2 p:integer l:"GIS ID2" t:dataTypeName=number

entity e:5tx2-pk4n l:"Bicycle Rack Requests" t:attribution="City of Austin" t:url=https://data.austintexas.gov/api/views/5tx2-pk4n

property e:5tx2-pk4n t:meta.view v:id=5tx2-pk4n v:averageRating=0 v:name="Bicycle Rack Requests" v:attribution="City of Austin"

property e:5tx2-pk4n t:meta.view.owner v:id=99uc-9byy v:screenName=opendataatx v:displayName=opendataatx

property e:5tx2-pk4n t:meta.view.tableauthor v:id=99uc-9byy v:screenName=opendataatx v:roleName=administrator v:displayName=opendataatx
```

## Top Records

```ls
| request_date        | location                                                                | install                       | requestor | galv_1 | green_1 | cables_1 | galv_2 | green_2 | cables_2 | delivered | installed | central_buisness_district | cbd_of_racks | gis_id2 | x | y | 
| =================== | ======================================================================= | ============================= | ========= | ====== | ======= | ======== | ====== | ======= | ======== | ========= | ========= | ========================= | ============ | ======= | = | = | 
| 2005-10-21T00:00:00 | Texas Healing Arts Institure, 7001 Burnet Rd, 78733                     | Delivered                     | Merchant  | 2      | 0       |          | 0      | 0       |          | 10/26     | 1/1       | Yes                       | 0            | 0       |   |   | 
| 2005-10-21T00:00:00 | Texas School for the Blind and Visually Impaired 1100 W. 45th St, 78756 | Delivered                     |           | 1      |         |          |        |         |          | 10/26     |           |                           |              |         |   |   | 
| 2005-10-21T00:00:00 | Home Slice Pizza, 1415 S. Congress Ave, 78704                           | Delivered                     |           | 5      |         |          |        |         |          | 11/2      |           |                           |              |         |   |   | 
| 2005-10-21T00:00:00 | 17th Street Condos, 806 W. 17th St, #4                                  | Delivered                     |           | 1      |         |          |        |         |          | 10/24     |           |                           |              |         |   |   | 
| 2005-10-21T00:00:00 | Dandelion Caf?, 1115 E. 11th St,                                        | no loaction                   |           | 0      |         |          |        |         |          | 11/29     |           |                           |              |         |   |   | 
| 2005-10-21T00:00:00 | Texas State Library and Archives Commission 1201 Brazos St,             | Picked up at Techni Center Dr |           | 35     |         |          |        |         |          | 12/13     |           |                           |              |         |   |   | 
| 2005-11-02T00:00:00 | Texas Showdown, 2610 Quadalupe St                                       | hold                          |           |        |         |          |        |         |          |           |           |                           |              |         |   |   | 
| 2005-11-02T00:00:00 | Fresh Plus Grocery, 1221 West Lynn                                      | no location                   |           | 0      |         |          |        |         |          | 11/8      |           |                           |              |         |   |   | 
| 2005-11-07T00:00:00 | Meals on Wheels                                                         | Picked up                     |           | 2      |         |          |        |         |          | 11/8      |           |                           |              |         |   |   | 
| 2005-11-08T00:00:00 | Ambion, Inc 2150 Woodward St                                            | Delivered                     |           | 7      |         |          |        |         |          | 11/30     |           |                           |              |         |   |   | 
```