# 311 Service Requests - Rodent Baiting

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/311-service-requests-rodent-baiting-9f9be) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/97t6-zrhs) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/97t6-zrhs/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/97t6-zrhs/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | 97t6-zrhs |
| Name | 311 Service Requests - Rodent Baiting |
| Attribution | City of Chicago |
| Category | Service Requests |
| Tags | rodents, rats |
| Created | 2011-09-30T09:07:40Z |
| Publication Date | 2017-04-21T09:00:51Z |

## Description

All open rodent baiting requests and rat complaints made to 311 and all requests completed since January 1, 2011. The Department of Streets & Sanitation investigates reported rat sightings. Alley conditions are examined. If any damaged carts are identified, Sanitation Ward Offices, which distribute the carts are notified. Rodenticide is placed in rat burrows to eradicate nests. 311 sometimes receives duplicate rat complaints and requests for rodent baiting. Requests that have been labeled as Duplicates are in the same geographic area and have been entered into 311?s Customer Service Requests (CSR) system at around the same time as a previous request. Duplicate reports/requests are labeled as such in the Status field, as either "Open - Dup" or "Completed - Dup." Data is updated daily.

## Columns

```ls
| Included | Schema Type    | Field Name                      | Name                            | Data Type     | Render Type   |
| ======== | ============== | =============================== | =============================== | ============= | ============= |
| Yes      | time           | creation_date                   | Creation Date                   | calendar_date | calendar_date |
| Yes      | series tag     | status                          | Status                          | text          | text          |
| No       |                | completion_date                 | Completion Date                 | calendar_date | calendar_date |
| Yes      | series tag     | service_request_number          | Service Request Number          | text          | text          |
| Yes      | series tag     | type_of_service_request         | Type of Service Request         | text          | text          |
| Yes      | numeric metric | number_of_premises_baited       | Number of Premises Baited       | number        | number        |
| Yes      | numeric metric | number_of_premises_with_garbage | Number of Premises with Garbage | number        | number        |
| Yes      | numeric metric | number_of_premises_with_rats    | Number of Premises with Rats    | number        | number        |
| Yes      | series tag     | current_activity                | Current Activity                | text          | text          |
| Yes      | series tag     | most_recent_action              | Most Recent Action              | text          | text          |
| Yes      | series tag     | street_address                  | Street Address                  | text          | text          |
| Yes      | series tag     | zip_code                        | ZIP Code                        | text          | number        |
| No       |                | x_coordinate                    | X Coordinate                    | number        | number        |
| No       |                | y_coordinate                    | Y Coordinate                    | number        | number        |
| Yes      | series tag     | ward                            | Ward                            | text          | number        |
| Yes      | series tag     | police_district                 | Police District                 | text          | number        |
| Yes      | series tag     | community_area                  | Community Area                  | text          | number        |
| Yes      | numeric metric | latitude                        | Latitude                        | number        | number        |
| Yes      | numeric metric | longitude                       | Longitude                       | number        | number        |
```

## Time Field

```ls
Value = creation_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = completion_date,x_coordinate,y_coordinate
```

## Data Commands

```ls
series e:97t6-zrhs d:2011-01-01T00:00:00.000Z t:ward=3 t:police_district=9 t:zip_code=60609 t:most_recent_action="Inspected and baited" t:status=Completed t:service_request_number=11-00000992 t:current_activity="Dispatch Crew" t:community_area=37 t:type_of_service_request="Rodent Baiting/Rat Complaint" t:street_address="437 W ROOT ST" m:number_of_premises_baited=2 m:number_of_premises_with_garbage=1 m:longitude=-87.63695396416237 m:latitude=41.81904110375691 m:number_of_premises_with_rats=2

series e:97t6-zrhs d:2011-01-01T00:00:00.000Z t:ward=29 t:police_district=15 t:zip_code=60644 t:most_recent_action="Area inspected, no cause and no baiting" t:status=Completed t:service_request_number=11-00001321 t:current_activity="Dispatch Crew" t:community_area=25 t:type_of_service_request="Rodent Baiting/Rat Complaint" t:street_address="5545 W MADISON ST" m:number_of_premises_baited=0 m:number_of_premises_with_garbage=0 m:longitude=-87.7639495188141 m:latitude=41.88025817420532 m:number_of_premises_with_rats=0

series e:97t6-zrhs d:2011-01-01T00:00:00.000Z t:ward=50 t:police_district=24 t:zip_code=60645 t:most_recent_action="Area inspected, no cause and no baiting" t:status=Completed t:service_request_number=11-00001629 t:current_activity="Dispatch Crew" t:community_area=2 t:type_of_service_request="Rodent Baiting/Rat Complaint" t:street_address="2540 W ESTES AVE" m:number_of_premises_baited=0 m:number_of_premises_with_garbage=0 m:longitude=-87.69371292873835 m:latitude=42.01039236610359 m:number_of_premises_with_rats=0
```

## Meta Commands

```ls
metric m:number_of_premises_baited p:long l:"Number of Premises Baited" t:dataTypeName=number

metric m:number_of_premises_with_garbage p:long l:"Number of Premises with Garbage" t:dataTypeName=number

metric m:number_of_premises_with_rats p:long l:"Number of Premises with Rats" t:dataTypeName=number

metric m:latitude p:long l:Latitude t:dataTypeName=number

metric m:longitude p:long l:Longitude t:dataTypeName=number

entity e:97t6-zrhs l:"311 Service Requests - Rodent Baiting" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/97t6-zrhs

property e:97t6-zrhs t:meta.view v:id=97t6-zrhs v:category="Service Requests" v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="311 Service Requests - Rodent Baiting" v:attribution="City of Chicago"

property e:97t6-zrhs t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:97t6-zrhs t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```

## Top Records

```ls
| creation_date       | status    | completion_date     | service_request_number | type_of_service_request      | number_of_premises_baited | number_of_premises_with_garbage | number_of_premises_with_rats | current_activity | most_recent_action                      | street_address       | zip_code | x_coordinate     | y_coordinate     | ward | police_district | community_area | latitude           | longitude          | 
| =================== | ========= | =================== | ====================== | ============================ | ========================= | =============================== | ============================ | ================ | ======================================= | ==================== | ======== | ================ | ================ | ==== | =============== | ============== | ================== | ================== | 
|                     | STATUS    |                     | SERVICE REQUEST NUMBER | TYPE OF SERVICE REQUEST      |                           |                                 |                              | CURRENT ACTIVITY | MOST RECENT ACTION                      | STREET ADDRESS       |          |                  |                  |      |                 |                |                    |                    | 
| 2011-01-01T00:00:00 | Completed | 2011-01-05T00:00:00 | 11-00000992            | Rodent Baiting/Rat Complaint | 2                         | 1                               | 2                            | Dispatch Crew    | Inspected and baited                    | 437 W ROOT ST        | 60609    | 1174070.65202445 | 1877418.09150898 | 3    | 9               | 37             | 41.81904110375691  | -87.63695396416237 | 
| 2011-01-01T00:00:00 | Completed | 2011-01-05T00:00:00 | 11-00001321            | Rodent Baiting/Rat Complaint | 0                         | 0                               | 0                            | Dispatch Crew    | Area inspected, no cause and no baiting | 5545 W MADISON ST    | 60644    | 1139305.86986935 | 1899470.3932844  | 29   | 15              | 25             | 41.88025817420532  | -87.7639495188141  | 
| 2011-01-01T00:00:00 | Completed | 2011-01-05T00:00:00 | 11-00001629            | Rodent Baiting/Rat Complaint | 0                         | 0                               | 0                            | Dispatch Crew    | Area inspected, no cause and no baiting | 2540 W ESTES AVE     | 60645    | 1158079.07002097 | 1947026.37998249 | 50   | 24              | 2              | 42.01039236610359  | -87.69371292873835 | 
| 2011-01-01T00:00:00 | Completed | 2011-01-05T00:00:00 | 11-00002551            | Rodent Baiting/Rat Complaint | 3                         | 6                               | 3                            | Dispatch Crew    | Inspected and baited                    | 7039 S NORMAL BLVD   | 60621    | 1174168.26431373 | 1858240.98502664 | 6    | 7               | 68             | 41.76641494684121  | -87.63716556232575 | 
| 2011-01-01T00:00:00 | Completed | 2011-01-05T00:00:00 | 11-00002697            | Rodent Baiting/Rat Complaint | 1                         | 3                               | 1                            | Dispatch Crew    | Inspected and baited                    | 1111 E 93RD ST       | 60619    | 1185291.74371894 | 1843539.75029876 | 8    | 4               | 47             | 41.72581895961811  | -87.59685549830274 | 
| 2011-01-01T00:00:00 | Completed | 2011-01-05T00:00:00 | 11-00003085            | Rodent Baiting/Rat Complaint | 1                         | 3                               | 1                            | Dispatch Crew    | Inspected and baited                    | 7756 S TROY ST       | 60652    | 1156723.83741961 | 1852989.47198156 | 18   | 8               | 70             | 41.752373627738436 | -87.70124765768429 | 
| 2011-01-01T00:00:00 | Completed | 2011-01-05T00:00:00 | 11-00003145            | Rodent Baiting/Rat Complaint | 0                         | 0                               | 0                            | Dispatch Crew    | Area inspected, no cause and no baiting | 2511 W AUGUSTA BLVD  | 60622    | 1159481.71357182 | 1906571.08907416 | 26   | 13              | 24             | 41.89935190229656  | -87.68967006324442 | 
| 2011-01-01T00:00:00 | Completed | 2011-01-05T00:00:00 | 11-00003368            | Rodent Baiting/Rat Complaint | 2                         | 9                               | 2                            | Dispatch Crew    | Inspected and baited                    | 6700 S HERMITAGE AVE | 60636    | 1165830.09768491 | 1860263.98562895 | 15   | 7               | 67             | 41.77214745780087  | -87.66767067184314 | 
| 2011-01-01T00:00:00 | Completed | 2011-01-05T00:00:00 | 11-00003411            | Rodent Baiting/Rat Complaint | 0                         | 5                               | 0                            | Dispatch Crew    | No contact, left door hanger            | 1241 N LOCKWOOD AVE  | 60651    | 1140795.50647215 | 1907858.97237715 | 37   | 25              | 25             | 41.90325020713387  | -87.75827322161487 | 
```