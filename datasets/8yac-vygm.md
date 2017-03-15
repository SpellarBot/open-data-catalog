# Routes

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/routes) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/8yac-vygm) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/8yac-vygm/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/8yac-vygm/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 8yac-vygm |
| Name | Routes |
| Attribution | Department of Education (DOE) |
| Category | Transportation |
| Created | 2015-11-13T21:00:41Z |
| Publication Date | 2016-05-03T23:17:44Z |
| Rows Updated | 2017-03-01T12:10:32Z |

## Description

One of OPT’s main functions is to plan efficient and fiscally responsible school bus routes. OPT staff use a variety of systems to generate and share bus route information with bus vendors and the public. Specific bus route paths cannot be publicly disclosed because they could reveal personally identifiable information about individual students. In this dataset, OPT has provided all the route information that does not risk disclosing personally identifiable information. 
School-age service for students in grades K through 12 are contracted with bus vendors on a per route basis. OPT also manages bus service for Pre-K students who require curb-to-curb service as per a student’s Individualized Education Plan (IEP). This Pre-K bus service is contracted on a per student basis, instead of per route. As a consequence of this difference, OPT does not design bus routes for Pre-K service, so those routes are not included in this dataset.
There are a variety of different vehicles used on routes that serve students requiring curb-to-curb service because an Individualized Education Plan (IEP) indicates specific transportation needs. The standard bus is the only vehicle used for general education routes with students eligible for bus service but who do not have an IEP.
Users may occasionally see a route without a garage assignment. Because this dataset is derived from a snapshot of a transactional system, there may be routes that are in the process of being assigned to a garage. In those cases, the garage information will appear as NULL until the assignment is complete.

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type     | Render Type   |
| ======== | ============== | ======================= | ======================= | ============= | ============= |
| Yes      | series tag     | school_year             | School_Year             | text          | text          |
| Yes      | series tag     | route_number            | Route_Number            | text          | text          |
| Yes      | series tag     | service_type            | Service_Type            | text          | text          |
| Yes      | series tag     | vehicle_typedescription | Vehicle_TypeDescription | text          | text          |
| Yes      | time           | route_start_date        | Route_Start_Date        | calendar_date | calendar_date |
| Yes      | series tag     | vendor_code             | Vendor_Code             | text          | text          |
| Yes      | series tag     | vendor_name             | Vendor_Name             | text          | text          |
| Yes      | series tag     | vendor_affiliation      | Vendor_Affiliation      | text          | text          |
| Yes      | series tag     | garage_street_name      | Garage _Street_Address  | text          | text          |
| Yes      | series tag     | garage_city             | Garage_City             | text          | text          |
| Yes      | series tag     | garage_state            | Garage_State            | text          | text          |
| Yes      | series tag     | garage_zip              | Garage_Zip              | text          | text          |
| Yes      | numeric metric | xcoordinates            | XCoordinates            | number        | text          |
| Yes      | numeric metric | ycoordinates            | YCoordinates            | number        | text          |
```

## Time Field

```ls
Value = route_start_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:8yac-vygm d:2016-03-21T00:00:00.000Z t:route_number=C911 t:vendor_code=VN t:garage_street_name="670 Hillside Road" t:garage_city="Pelham Manor" t:garage_state=NY t:garage_zip=10803 t:vendor_affiliation="VAN TRANS LLC (B2192)" t:service_type=D2D t:vehicle_typedescription="Non-Wheelchair Accessible Alternative (NWC)" t:school_year=2015-2016 t:vendor_name="VAN TRANS LLC (B2192)" m:xcoordinates=1034573.79895 m:ycoordinates=265547.59264

series e:8yac-vygm d:2015-09-09T00:00:00.000Z t:route_number=J499 t:vendor_code=RV t:garage_street_name="297 NORMAN AVENUE" t:garage_city=Brooklyn t:garage_state=NY t:garage_zip=11222 t:vendor_affiliation="RELIANT TRANS, INC. (B2321)" t:service_type=D2D t:vehicle_typedescription=Mini-Wagon t:school_year=2015-2016 t:vendor_name="RELIANT TRANS, INC. (B2321)" m:xcoordinates=1000787 m:ycoordinates=204481

series e:8yac-vygm d:2015-09-01T00:00:00.000Z t:route_number=J500 t:vendor_code=HT t:garage_street_name="2859 WEST 37 STREET" t:garage_city=BROOKLYN t:garage_state=NY t:garage_zip=11224 t:vendor_affiliation="THOMAS BUSES, INC. (B2321)" t:service_type=D2D t:vehicle_typedescription="Non-Wheelchair Accessible Alternative (NWC)" t:school_year=2015-2016 t:vendor_name="THOMAS BUSES, INC. (B2321)" m:xcoordinates=983439 m:ycoordinates=148884
```

## Meta Commands

```ls
metric m:xcoordinates p:float l:XCoordinates d:"Spatial coordinate to be used for mapping. Coordinate system used is State Plane Coordinate (SPC) system: NAD 1983 StatePlane New York Long Island FIPS 3104 Feet." t:dataTypeName=number

metric m:ycoordinates p:double l:YCoordinates d:"Spatial coordinate to be used for mapping. Coordinate system used is State Plane Coordinate (SPC) system: NAD 1983 StatePlane New York Long Island FIPS 3104 Feet." t:dataTypeName=number

entity e:8yac-vygm l:Routes t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/8yac-vygm

property e:8yac-vygm t:meta.view v:id=8yac-vygm v:category=Transportation v:averageRating=0 v:name=Routes v:attribution="Department of Education (DOE)"

property e:8yac-vygm t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:displayName="NYC OpenData"

property e:8yac-vygm t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:displayName="NYC OpenData"
```