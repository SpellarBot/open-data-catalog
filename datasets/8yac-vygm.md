# Routes

## Dataset

* [Dataset URL](https://data.cityofnewyork.us/api/views/8yac-vygm/rows.json?accessType=DOWNLOAD)
* [Catalog URL](https://catalog.data.gov/dataset/routes)
* Id = 8yac-vygm
* Name = Routes
* Attribution = Department of Education (DOE)
* Category = Transportation
* Created = 2015-11-13T21:00:41Z
* Publication Date = 2016-05-03T23:17:44Z
* Rows Updated = 2017-03-01T12:10:32Z

## Description

One of OPT?s main functions is to plan efficient and fiscally responsible school bus routes. OPT staff use a variety of systems to generate and share bus route information with bus vendors and the public. Specific bus route paths cannot be publicly disclosed because they could reveal personally identifiable information about individual students. In this dataset, OPT has provided all the route information that does not risk disclosing personally identifiable information. 
School-age service for students in grades K through 12 are contracted with bus vendors on a per route basis. OPT also manages bus service for Pre-K students who require curb-to-curb service as per a student?s Individualized Education Plan (IEP). This Pre-K bus service is contracted on a per student basis, instead of per route. As a consequence of this difference, OPT does not design bus routes for Pre-K service, so those routes are not included in this dataset.
There are a variety of different vehicles used on routes that serve students requiring curb-to-curb service because an Individualized Education Plan (IEP) indicates specific transportation needs. The standard bus is the only vehicle used for general education routes with students eligible for bus service but who do not have an IEP.
Users may occasionally see a route without a garage assignment. Because this dataset is derived from a snapshot of a transactional system, there may be routes that are in the process of being assigned to a garage. In those cases, the garage information will appear as NULL until the assignment is complete.

## Columns

```ls
| Name                    | Field Name              | Data Type     | Render Type   | Schema Type    | Included | 
| ======================= | ======================= | ============= | ============= | ============== | ======== | 
| School_Year             | school_year             | text          | text          | series tag     | Yes      | 
| Route_Number            | route_number            | text          | text          | series tag     | Yes      | 
| Service_Type            | service_type            | text          | text          | series tag     | Yes      | 
| Vehicle_TypeDescription | vehicle_typedescription | text          | text          | series tag     | Yes      | 
| Route_Start_Date        | route_start_date        | calendar_date | calendar_date | time           | Yes      | 
| Vendor_Code             | vendor_code             | text          | text          | series tag     | Yes      | 
| Vendor_Name             | vendor_name             | text          | text          | series tag     | Yes      | 
| Vendor_Affiliation      | vendor_affiliation      | text          | text          | series tag     | Yes      | 
| Garage _Street_Address  | garage_street_name      | text          | text          | series tag     | Yes      | 
| Garage_City             | garage_city             | text          | text          | series tag     | Yes      | 
| Garage_State            | garage_state            | text          | text          | series tag     | Yes      | 
| Garage_Zip              | garage_zip              | number        | text          | numeric metric | Yes      | 
| XCoordinates            | xcoordinates            | number        | text          | numeric metric | Yes      | 
| YCoordinates            | ycoordinates            | number        | text          | numeric metric | Yes      | 
```

## Time Field

```ls
Value = route_start_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = 
Annotation Fields = 
```

## Data Commands

```ls
series e:8yac-vygm d:2016-03-21T00:00:00.000Z t:route_number=C911 t:vendor_code=VN t:garage_street_name="670 Hillside Road" t:garage_city="Pelham Manor" t:garage_state=NY t:vendor_affiliation="VAN TRANS LLC (B2192)" t:service_type=D2D t:vehicle_typedescription="Non-Wheelchair Accessible Alternative (NWC)" t:school_year=2015-2016 t:vendor_name="VAN TRANS LLC (B2192)" m:garage_zip=10803 m:xcoordinates=1034573.79895 m:ycoordinates=265547.59264

series e:8yac-vygm d:2015-09-09T00:00:00.000Z t:route_number=J499 t:vendor_code=RV t:garage_street_name="297 NORMAN AVENUE" t:garage_city=Brooklyn t:garage_state=NY t:vendor_affiliation="RELIANT TRANS, INC. (B2321)" t:service_type=D2D t:vehicle_typedescription=Mini-Wagon t:school_year=2015-2016 t:vendor_name="RELIANT TRANS, INC. (B2321)" m:garage_zip=11222 m:xcoordinates=1000787 m:ycoordinates=204481

series e:8yac-vygm d:2015-09-01T00:00:00.000Z t:route_number=J500 t:vendor_code=HT t:garage_street_name="2859 WEST 37 STREET" t:garage_city=BROOKLYN t:garage_state=NY t:vendor_affiliation="THOMAS BUSES, INC. (B2321)" t:service_type=D2D t:vehicle_typedescription="Non-Wheelchair Accessible Alternative (NWC)" t:school_year=2015-2016 t:vendor_name="THOMAS BUSES, INC. (B2321)" m:garage_zip=11224 m:xcoordinates=983439 m:ycoordinates=148884
```

## Meta Commands

```ls
metric m:garage_zip p:integer l:Garage_Zip d:"The ZIP code for a location where the school bus servicing this particular route is parked overnight." t:dataTypeName=number

metric m:xcoordinates l:XCoordinates d:"Spatial coordinate to be used for mapping. Coordinate system used is State Plane Coordinate (SPC) system: NAD 1983 StatePlane New York Long Island FIPS 3104 Feet." t:dataTypeName=number

metric m:ycoordinates l:YCoordinates d:"Spatial coordinate to be used for mapping. Coordinate system used is State Plane Coordinate (SPC) system: NAD 1983 StatePlane New York Long Island FIPS 3104 Feet." t:dataTypeName=number

entity e:8yac-vygm l:Routes t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/8yac-vygm

property e:8yac-vygm t:meta.view d:2017-03-03T14:13:23.349Z v:id=8yac-vygm v:category=Transportation v:averageRating=0 v:name=Routes v:attribution="Department of Education (DOE)"

property e:8yac-vygm t:meta.view.owner d:2017-03-03T14:13:23.349Z v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:displayName="NYC OpenData"

property e:8yac-vygm t:meta.view.tableauthor d:2017-03-03T14:13:23.349Z v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:displayName="NYC OpenData"
```