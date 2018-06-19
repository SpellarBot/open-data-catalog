# Vehicles

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/vehicles) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/28rh-vpvr) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/28rh-vpvr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/28rh-vpvr/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 28rh-vpvr |
| Name | Vehicles |
| Attribution | Department of Education (DOE) |
| Category | Transportation |
| Created | 2015-11-13T21:50:01Z |
| Publication Date | 2016-05-03T22:57:59Z |

## Description

OPT maintains an inventory of all the vehicles used by contracted bus vendors in service to the Department of Education. The vehicles inventory can include school buses, ambulances or coach buses. This dataset details the active vehicle inventory for each bus vendor. 
There are a variety of different vehicles used to serve students requiring curb-to-curb service because an Individualized Education Plan (IEP) indicates specific transportation needs. The standard bus is the only vehicle used for general education students eligible for bus service but who do not have an IEP.

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type | Render Type |
| ======== | ============== | ======================= | ======================= | ========= | =========== |
| No       | time           | :updated_at             | updated_at              | meta_data | meta_data   |
| Yes      | series tag     | school_year             | School_Year             | text      | text        |
| Yes      | series tag     | vendor_name             | Vendor_Name             | text      | text        |
| Yes      | series tag     | vehicle_typedescription | Vehicle_TypeDescription | text      | text        |
| Yes      | numeric metric | active_vehicles         | Active_Vehicles         | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:28rh-vpvr d:2016-10-01T11:00:40.000Z t:vehicle_typedescription="Motor Coach Bus" t:school_year=2015-2016 t:vendor_name="ACADEMY EXPRESS LLC" m:active_vehicles=22

series e:28rh-vpvr d:2016-10-01T11:00:40.000Z t:vehicle_typedescription=Mini-Wagon t:school_year=2015-2016 t:vendor_name="ACME BUS CORP. (B2321)" m:active_vehicles=71

series e:28rh-vpvr d:2016-10-01T11:00:40.000Z t:vehicle_typedescription=Mini-Wagon t:school_year=2015-2016 t:vendor_name="MJT BUS" m:active_vehicles=6
```

## Meta Commands

```ls
metric m:active_vehicles p:integer l:Active_Vehicles d:"The total number of active vehicles for each vendor and vehicle type category. This number includes spare and substitute buses." t:dataTypeName=number

entity e:28rh-vpvr l:Vehicles t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/28rh-vpvr

property e:28rh-vpvr t:meta.view v:id=28rh-vpvr v:category=Transportation v:averageRating=0 v:name=Vehicles v:attribution="Department of Education (DOE)"

property e:28rh-vpvr t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:28rh-vpvr t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | school_year | vendor_name                   | vehicle_typedescription | active_vehicles | 
| =========== | =========== | ============================= | ======================= | =============== | 
| 1475319640  | 2015-2016   | ACADEMY EXPRESS LLC           | Motor Coach Bus         | 22              | 
| 1475319640  | 2015-2016   | ACME BUS CORP. (B2321)        | Mini-Wagon              | 71              | 
| 1475319640  | 2015-2016   | MJT BUS                       | Mini-Wagon              | 6               | 
| 1475319640  | 2015-2016   | ALINA SERVICES CORP.          | Mini-Wagon              | 62              | 
| 1475319640  | 2015-2016   | ALINA SERVICES CORP.          | Ramp-Wagon              | 1               | 
| 1475319640  | 2015-2016   | ALL AMERICAN SCHOOL BUS CORP. | Mini-Wagon              | 9               | 
| 1475319640  | 2015-2016   | ALL AMERICAN SCHOOL BUS CORP. | Ramp-Wagon              | 71              | 
| 1475319640  | 2015-2016   | ALLIED TRANSIT CORP.          | Mini-Wagon              | 6               | 
| 1475319640  | 2015-2016   | ALL AMERICAN SCHOOL BUS CORP. | Standard Bus (GE)       | 63              | 
| 1475319640  | 2015-2016   | ALL AMERICAN SCHOOL BUS CORP. | Standard Bus (SE)       | 47              | 
```