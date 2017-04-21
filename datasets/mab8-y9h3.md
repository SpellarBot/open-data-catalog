# 311 Service Requests - Tree Debris

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/311-service-requests-tree-debris-ae235) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/mab8-y9h3) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/mab8-y9h3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/mab8-y9h3/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | mab8-y9h3 |
| Name | 311 Service Requests - Tree Debris |
| Attribution | City of Chicago |
| Category | Service Requests |
| Tags | trees |
| Created | 2011-09-30T09:06:05Z |
| Publication Date | 2017-04-20T08:45:28Z |

## Description

All open tree debris removal requests made to 311 and all requests completed since January 1, 2011. Large piles of branches or bushes may be picked up by the Department of Streets and Sanitation.
311 sometimes creates duplicate requests for tree debris removal.  When there is an open tree debris request, a duplicate request is created when the exact same address and the exact same service request type are used. Streets and Sanitation responds to the initial request opened and closes the duplicates. A forestry "Clam" is the name of the vehicle the Forestry Bureau deploys to collect tree debris.
Data Owner: Streets and Sanitation (http://www.cityofchicago.org/content/city/en/depts/streets.html).
Time Period: January 1, 2011 to present.
Frequency: Data is updated daily.
Related Applications: 311 Service Request Status Inquiry (https://servicerequest.cityofchicago.org/web_intake_chic/Controller?op=createsrquery2) and 
                                    Request Tree Debris Removal (https://servicerequest.cityofchicago.org/web_intake_chic/Controller?op=locform&invSRType=SEL&invSRDesc=Tree%20Debris&locreq=Y).

## Columns

```ls
| Included | Schema Type | Field Name                          | Name                                 | Data Type     | Render Type   |
| ======== | =========== | =================================== | ==================================== | ============= | ============= |
| Yes      | time        | creation_date                       | Creation Date                        | calendar_date | calendar_date |
| Yes      | series tag  | status                              | Status                               | text          | text          |
| No       |             | completion_date                     | Completion Date                      | calendar_date | calendar_date |
| Yes      | series tag  | service_request_number              | Service Request Number               | text          | text          |
| Yes      | series tag  | type_of_service_request             | Type of Service Request              | text          | text          |
| Yes      | series tag  | if_yes_where_is_the_debris_located_ | If Yes, where is the debris located? | text          | text          |
| Yes      | series tag  | current_activity                    | Current Activity                     | text          | text          |
| Yes      | series tag  | most_recent_action                  | Most Recent Action                   | text          | text          |
| Yes      | series tag  | street_address                      | Street Address                       | text          | text          |
| Yes      | series tag  | zip_code                            | ZIP Code                             | text          | number        |
| No       |             | x_coordinate                        | X Coordinate                         | number        | number        |
| No       |             | y_coordinate                        | Y Coordinate                         | number        | number        |
| Yes      | series tag  | ward                                | Ward                                 | text          | number        |
| Yes      | series tag  | police_district                     | Police District                      | text          | number        |
| Yes      | series tag  | community_area                      | Community Area                       | text          | number        |
| No       |             | latitude                            | Latitude                             | number        | number        |
| No       |             | longitude                           | Longitude                            | number        | number        |
```

## Time Field

```ls
Value = creation_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = completion_date,x_coordinate,y_coordinate,latitude,longitude
```

## Data Commands

```ls
series e:mab8-y9h3 d:2017-04-20T08:44:15.000Z t:most_recent_action="MOST RECENT ACTION" t:status=STATUS t:service_request_number="SERVICE REQUEST NUMBER" t:current_activity="CURRENT ACTIVITY" t:type_of_service_request="TYPE OF SERVICE REQUEST" t:street_address="STREET ADDRESS" t:if_yes_where_is_the_debris_located_="IF YES, WHERE IS THE DEBRIS LOCATED?" m:row_number.mab8-y9h3=1

series e:mab8-y9h3 d:2011-01-01T00:00:00.000Z t:ward=35 t:police_district=14 t:zip_code=60647 t:most_recent_action="*Complete the Service Request" t:status=Completed t:service_request_number=11-00001766 t:current_activity="Dispatch Clam" t:community_area=22 t:type_of_service_request="Tree Debris" t:street_address="2524 N MOZART ST" t:if_yes_where_is_the_debris_located_=Parkway m:row_number.mab8-y9h3=2

series e:mab8-y9h3 d:2012-01-01T00:00:00.000Z t:ward=9 t:police_district=22 t:zip_code=60628 t:most_recent_action="*Complete the Service Request" t:status=Completed t:service_request_number=12-00001807 t:current_activity="Dispatch Clam" t:community_area=73 t:type_of_service_request="Tree Debris" t:street_address="10132 S EGGLESTON AVE" t:if_yes_where_is_the_debris_located_=Parkway m:row_number.mab8-y9h3=3
```

## Meta Commands

```ls
metric m:row_number.mab8-y9h3 p:long l:"Row Number"

entity e:mab8-y9h3 l:"311 Service Requests - Tree Debris" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/mab8-y9h3

property e:mab8-y9h3 t:meta.view v:id=mab8-y9h3 v:category="Service Requests" v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="311 Service Requests - Tree Debris" v:attribution="City of Chicago"

property e:mab8-y9h3 t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:mab8-y9h3 t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```

## Top Records

```ls
| creation_date       | status          | completion_date     | service_request_number | type_of_service_request | if_yes_where_is_the_debris_located_  | current_activity | most_recent_action            | street_address         | zip_code | x_coordinate     | y_coordinate     | ward | police_district | community_area | latitude           | longitude          | 
| =================== | =============== | =================== | ====================== | ======================= | ==================================== | ================ | ============================= | ====================== | ======== | ================ | ================ | ==== | =============== | ============== | ================== | ================== | 
|                     | STATUS          |                     | SERVICE REQUEST NUMBER | TYPE OF SERVICE REQUEST | IF YES, WHERE IS THE DEBRIS LOCATED? | CURRENT ACTIVITY | MOST RECENT ACTION            | STREET ADDRESS         |          |                  |                  |      |                 |                |                    |                    | 
| 2011-01-01T00:00:00 | Completed       | 2011-01-04T00:00:00 | 11-00001766            | Tree Debris             | Parkway                              | Dispatch Clam    | *Complete the Service Request | 2524 N MOZART ST       | 60647    | 1156945.33866643 | 1916756.54337137 | 35   | 14              | 22             | 41.92735345762709  | -87.69870933383872 | 
| 2012-01-01T00:00:00 | Completed       | 2012-01-03T00:00:00 | 12-00001807            | Tree Debris             | Parkway                              | Dispatch Clam    | *Complete the Service Request | 10132 S EGGLESTON AVE  | 60628    | 1175293.29133151 | 1837607.05001364 | 9    | 22              | 73             | 41.70976771267409  | -87.63365681877502 | 
| 2012-01-01T00:00:00 | Completed       | 2012-01-03T00:00:00 | 12-00002563            | Tree Debris             | Alley                                | Dispatch Clam    | *Complete the Service Request | 362 E 89TH PL          | 60619    | 1180205.64151591 | 1845719.96819315 | 6    | 6               | 44             | 41.73191964410131  | -87.61541942144278 | 
| 2013-01-01T00:00:00 | Completed       | 2013-01-02T00:00:00 | 13-00000901            | Tree Debris             | Parkway                              | Dispatch Clam    | *Complete the Service Request | 9117 S URBAN AVE       | 60619    | 1178270.54451797 | 1844417.51018182 | 6    | 6               | 49             | 41.72838960811961  | -87.62254782298375 | 
| 2011-01-02T00:00:00 | Completed - Dup | 2011-01-04T00:00:00 | 11-00003981            | Tree Debris             | Parkway                              |                  |                               | 4102 N WOLCOTT AVE     | 60613    | 1162939.86399482 | 1927268.10909903 | 47   | 19              | 5              | 41.956073918430725 | -87.67638589575405 | 
| 2011-01-02T00:00:00 | Completed       | 2011-01-03T00:00:00 | 11-00004699            | Tree Debris             | Alley                                | Dispatch Clam    | *Complete the Service Request | 5005 W FOSTER AVE      | 60630    | 1142024.27000674 | 1934113.37317787 | 45   | 16              | 12             | 41.97527212775161  | -87.753106915463   | 
| 2011-01-02T00:00:00 | Completed       | 2011-01-04T00:00:00 | 11-00004573            | Tree Debris             | Parkway                              | Dispatch Clam    | *Complete the Service Request | 5055 W CRYSTAL ST      | 60651    | 1142433.81368532 | 1907849.68338768 | 37   | 25              | 25             | 41.90319442254708  | -87.75225553106478 | 
| 2012-01-02T00:00:00 | Completed       | 2012-01-03T00:00:00 | 12-00003746            | Tree Debris             | Alley                                |                  |                               | 5823 W SUPERIOR ST     | 60644    | 1137460.64980662 | 1904410.01240658 | 29   | 15              | 25             | 41.89384652397142  | -87.77060612900046 | 
| 2012-01-02T00:00:00 | Completed       | 2012-01-03T00:00:00 | 12-00005038            | Tree Debris             | Alley                                | Dispatch Clam    | *Complete the Service Request | 5832 N EAST CIRCLE AVE | 60631    | 1129204.09493102 | 1938425.07941851 | 41   | 16              | 10             | 41.9873324710467   | -87.80015328916164 | 
```