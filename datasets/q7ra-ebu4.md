# Underutilized Space Report

## Dataset

* [Dataset URL](https://data.cityofnewyork.us/api/views/q7ra-ebu4/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/underutilized-space-report)
* [Metadata URL](https://data.cityofnewyork.us/api/views/q7ra-ebu4)
* Id = q7ra-ebu4
* Name = Underutilized Space Report
* Attribution = Department of Education (DOE)
* Category = Education
* Created = 2015-08-27T21:45:08Z
* Publication Date = 2015-08-31T18:44:29Z
* Rows Updated = 2015-08-31T18:21:12Z

## Description

The DOE has previously identified 594 schools located in 330 buildings as ?under-utilized? based upon the 2010-2011 Enrollment-Capacity-Utilization Report (The Blue Book). The DOE is also identifying 25 school buildings (listed below) which contain schools proposed for full phase-out, grade truncation or immediate closure due to poor performance. These proposals are scheduled to be voted on by the Panel for Education Policy on February 9, 2012. Should these proposals be approved, there will be excess space available in the buildings. In many cases, the DOE has already made companion proposals on how to use this additional space

## Columns

```ls
| Name                                               | Field Name                                       | Data Type | Render Type | Schema Type    | Included | 
| ================================================== | ================================================ | ========= | =========== | ============== | ======== | 
| updated_at                                         | :updated_at                                      | meta_data | meta_data   | time           | No       | 
| School Year                                        | school_year                                      | text      | text        | series tag     | Yes      | 
| Borough of Building                                | borough_of_building                              | text      | text        | series tag     | Yes      | 
| District of Building                               | district_of_building                             | text      | number      | series tag     | Yes      | 
| Building Code                                      | building_code                                    | text      | text        | series tag     | Yes      | 
| Formatting                                         | formatting                                       | text      | text        | series tag     | Yes      | 
| Building Name                                      | building_name                                    | text      | text        | series tag     | Yes      | 
| Building Level                                     | building_level                                   | text      | text        | series tag     | Yes      | 
| Building Enrollment (based on 2013-2014 Blue Book) | building_enrollment_based_on_2013_2014_blue_book | number    | number      | numeric metric | Yes      | 
| Building Capacity (based on 2013-2014 Blue Book)   | building_capacity_based_on_2013_2014_blue_book   | number    | number      | numeric metric | Yes      | 
| School Code                                        | school_code                                      | text      | text        | series tag     | Yes      | 
| School Name                                        | school_name                                      | text      | text        | series tag     | Yes      | 
| FINAL UU 2015 Designation                          | final_uu_2015_designation                        | text      | text        | series tag     | Yes      | 
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
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
series e:q7ra-ebu4 d:2015-08-31T11:20:57.000Z t:building_name="P.S. 5 - BROOKLYN" t:borough_of_building=Brooklyn t:final_uu_2015_designation=300+ t:school_name="P.S. 005 Dr. Ronald Mcnair" t:building_level=PS t:district_of_building=16 t:school_code=K005 t:school_year=2014-15 t:building_code=K005 m:building_capacity_based_on_2013_2014_blue_book=712 m:building_enrollment_based_on_2013_2014_blue_book=412

series e:q7ra-ebu4 d:2015-08-31T11:20:57.000Z t:building_name="P.S. 5 - BROOKLYN" t:borough_of_building=Brooklyn t:final_uu_2015_designation=300+ t:school_name="P.S. K369 - Coy L. Cox School" t:building_level=PS t:district_of_building=16 t:school_code=K369 t:school_year=2014-15 t:building_code=K005 m:building_capacity_based_on_2013_2014_blue_book=712 m:building_enrollment_based_on_2013_2014_blue_book=412

series e:q7ra-ebu4 d:2015-08-31T11:20:57.000Z t:building_name="P.S. 12 - BROOKLYN" t:borough_of_building=Brooklyn t:final_uu_2015_designation=300+ t:school_name="Dr. Jacqueline Peek-Davis School" t:building_level=PS t:district_of_building=23 t:school_code=K012 t:school_year=2014-15 t:building_code=K012 m:building_capacity_based_on_2013_2014_blue_book=861 m:building_enrollment_based_on_2013_2014_blue_book=357
```

## Meta Commands

```ls
metric m:building_enrollment_based_on_2013_2014_blue_book p:integer l:"Building Enrollment (based on 2013-2014 Blue Book)" t:dataTypeName=number

metric m:building_capacity_based_on_2013_2014_blue_book p:integer l:"Building Capacity (based on 2013-2014 Blue Book)" t:dataTypeName=number

entity e:q7ra-ebu4 l:"Underutilized Space Report" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/q7ra-ebu4

property e:q7ra-ebu4 t:meta.view d:2017-03-08T00:24:32.566Z v:id=q7ra-ebu4 v:category=Education v:averageRating=0 v:name="Underutilized Space Report" v:attribution="Department of Education (DOE)"

property e:q7ra-ebu4 t:meta.view.owner d:2017-03-08T00:24:32.566Z v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:displayName="NYC OpenData"

property e:q7ra-ebu4 t:meta.view.tableauthor d:2017-03-08T00:24:32.566Z v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:displayName="NYC OpenData"
```