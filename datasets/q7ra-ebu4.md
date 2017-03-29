# Underutilized Space Report

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/underutilized-space-report) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/q7ra-ebu4) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/q7ra-ebu4/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/q7ra-ebu4/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | q7ra-ebu4 |
| Name | Underutilized Space Report |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Created | 2015-08-27T21:45:08Z |
| Publication Date | 2015-08-31T18:44:29Z |

## Description

The DOE has previously identified 594 schools located in 330 buildings as “under-utilized” based upon the 2010-2011 Enrollment-Capacity-Utilization Report (The Blue Book). The DOE is also identifying 25 school buildings (listed below) which contain schools proposed for full phase-out, grade truncation or immediate closure due to poor performance. These proposals are scheduled to be voted on by the Panel for Education Policy on February 9, 2012. Should these proposals be approved, there will be excess space available in the buildings. In many cases, the DOE has already made companion proposals on how to use this additional space

## Columns

```ls
| Included | Schema Type    | Field Name                                       | Name                                               | Data Type | Render Type |
| ======== | ============== | ================================================ | ================================================== | ========= | =========== |
| No       | time           | :updated_at                                      | updated_at                                         | meta_data | meta_data   |
| Yes      | series tag     | school_year                                      | School Year                                        | text      | text        |
| Yes      | series tag     | borough_of_building                              | Borough of Building                                | text      | text        |
| Yes      | series tag     | district_of_building                             | District of Building                               | text      | number      |
| Yes      | series tag     | building_code                                    | Building Code                                      | text      | text        |
| Yes      | series tag     | formatting                                       | Formatting                                         | text      | text        |
| Yes      | series tag     | building_name                                    | Building Name                                      | text      | text        |
| Yes      | series tag     | building_level                                   | Building Level                                     | text      | text        |
| Yes      | numeric metric | building_enrollment_based_on_2013_2014_blue_book | Building Enrollment (based on 2013-2014 Blue Book) | number    | number      |
| Yes      | numeric metric | building_capacity_based_on_2013_2014_blue_book   | Building Capacity (based on 2013-2014 Blue Book)   | number    | number      |
| Yes      | series tag     | school_code                                      | School Code                                        | text      | text        |
| Yes      | series tag     | school_name                                      | School Name                                        | text      | text        |
| Yes      | series tag     | final_uu_2015_designation                        | FINAL UU 2015 Designation                          | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
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

property e:q7ra-ebu4 t:meta.view v:id=q7ra-ebu4 v:category=Education v:averageRating=0 v:name="Underutilized Space Report" v:attribution="Department of Education (DOE)"

property e:q7ra-ebu4 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:displayName="NYC OpenData"

property e:q7ra-ebu4 t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | school_year | borough_of_building | district_of_building | building_code | formatting | building_name      | building_level | building_enrollment_based_on_2013_2014_blue_book | building_capacity_based_on_2013_2014_blue_book | school_code | school_name                                    | final_uu_2015_designation | 
| =========== | =========== | =================== | ==================== | ============= | ========== | ================== | ============== | ================================================ | ============================================== | =========== | ============================================== | ========================= | 
| 1441020057  | 2014-15     | Brooklyn            | 16                   | K005          |            | P.S. 5 - BROOKLYN  | PS             | 412                                              | 712                                            | K005        | P.S. 005 Dr. Ronald Mcnair                     | 300+                      | 
| 1441020057  | 2014-15     | Brooklyn            | 16                   | K005          |            | P.S. 5 - BROOKLYN  | PS             | 412                                              | 712                                            | K369        | P.S. K369 - Coy L. Cox School                  | 300+                      | 
| 1441020057  | 2014-15     | Brooklyn            | 23                   | K012          |            | P.S. 12 - BROOKLYN | PS             | 357                                              | 861                                            | K012        | Dr. Jacqueline Peek-Davis School               | 300+                      | 
| 1441020057  | 2014-15     | Brooklyn            | 23                   | K012          |            | P.S. 12 - BROOKLYN | PS             | 357                                              | 861                                            | K484        | Ronald Edmonds Learning Center II              | 300+                      | 
| 1441020057  | 2014-15     | Brooklyn            | 22                   | K014          |            | I.S. 14 - BROOKLYN | IS/JHS         | 570                                              | 1132                                           | K014        | J.H.S. 014 Shell Bank                          | 300+                      | 
| 1441020057  | 2014-15     | Brooklyn            | 22                   | K014          |            | I.S. 14 - BROOKLYN | IS/JHS         | 570                                              | 1132                                           | K811        | P.S. K811 Connie Lekas School                  | 300+                      | 
| 1441020057  | 2014-15     | Brooklyn            | 16                   | K025          |            | P.S. 25 - BROOKLYN | PS             | 386                                              | 824                                            | K025        | P.S. 025 Eubie Blake School                    | 300+                      | 
| 1441020057  | 2014-15     | Brooklyn            | 16                   | K025          |            | P.S. 25 - BROOKLYN | PS             | 386                                              | 824                                            | K534        | Upper School @ P.S. 25                         | 300+                      | 
| 1441020057  | 2014-15     | Brooklyn            | 16                   | K026          |            | P.S. 26 - BROOKLYN | PS             | 574                                              | 1068                                           | K026        | P.S. 026 Jesse Owens                           | 300+                      | 
| 1441020057  | 2014-15     | Brooklyn            | 16                   | K026          |            | P.S. 26 - BROOKLYN | PS             | 574                                              | 1068                                           | K393        | Frederick Douglass Academy IV Secondary School | 300+                      | 
```