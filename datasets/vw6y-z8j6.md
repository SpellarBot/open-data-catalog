# [Notice of Dataset Change] Case Data from San Francisco 311 (SF311)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/case-data-from-san-francisco-311-sf311-d42fc) |
| Metadata | [Link](https://data.sfgov.org/api/views/vw6y-z8j6) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/vw6y-z8j6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/vw6y-z8j6/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | vw6y-z8j6 |
| Name | [Notice of Dataset Change] Case Data from San Francisco 311 (SF311) |
| Attribution | San Francisco 311 |
| Category | City Infrastructure |
| Tags | 311, case, cases, customer service |
| Created | 2011-10-08T20:01:17Z |
| Publication Date | 2017-04-20T14:45:57Z |

## Description

***This dataset will be reset and modified on 04/19/2017. Read the full notice of changes in the 'About' section of this dataset. During most of that day, the dataset will be unavailable.*** 

SF311 cases created since 7/1/2008 with location information

## Columns

```ls
| Included | Schema Type    | Field Name                      | Name                | Data Type     | Render Type   |
| ======== | ============== | =============================== | =================== | ============= | ============= |
| Yes      | series tag     | service_request_id              | CaseID              | text          | number        |
| Yes      | time           | requested_datetime              | Opened              | calendar_date | calendar_date |
| No       |                | closed_date                     | Closed              | calendar_date | calendar_date |
| No       |                | updated_datetime                | Updated             | calendar_date | calendar_date |
| Yes      | series tag     | status_description              | Status              | text          | text          |
| Yes      | series tag     | status_notes                    | Status Notes        | text          | text          |
| Yes      | series tag     | agency_responsible              | Responsible Agency  | text          | text          |
| Yes      | series tag     | service_name                    | Category            | text          | text          |
| Yes      | series tag     | service_subtype                 | Request Type        | text          | text          |
| Yes      | series tag     | service_details                 | Request Details     | text          | text          |
| No       |                | address                         | Address             | text          | text          |
| Yes      | series tag     | supervisor_district             | Supervisor District | text          | number        |
| Yes      | series tag     | neighborhoods_sffind_boundaries | Neighborhood        | text          | text          |
| Yes      | series tag     | police_district                 | Police District     | text          | text          |
| Yes      | numeric metric | lat                             | Latitude            | number        | number        |
| Yes      | numeric metric | long                            | Longitude           | number        | number        |
| Yes      | series tag     | source                          | Source              | text          | text          |
| Yes      | series tag     | media_url                       | Media URL           | url           | url           |
```

## Time Field

```ls
Value = requested_datetime
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = closed_date,updated_datetime,address
```

## Data Commands

```ls
series e:vw6y-z8j6 d:2012-04-12T14:56:47.000Z t:status_notes="Case Resolved - Closed" t:source="Voice In" t:police_district=TARAVAL t:status_description=Closed t:neighborhoods_sffind_boundaries="Outer Sunset" t:service_subtype=Utility_Excavation t:agency_responsible="DPW BSM Queue" t:service_details=Utility_Excavation t:service_name="Street Defects" t:supervisor_district=4 t:service_request_id=1104032 m:long=-122.4959 m:lat=37.76273

series e:vw6y-z8j6 d:2013-05-15T18:09:08.000Z t:status_notes="Case Completed - resolved:  Request closed by SES .  Notes = ""  BUF Action:PLANT. date completed - 6/3/2011. ""." t:source="Voice In" t:police_district=BAYVIEW t:status_description=Closed t:neighborhoods_sffind_boundaries=Bayview t:service_subtype="Trees - Landscaping" t:agency_responsible="DPW Ops Queue" t:service_details=Empty_tree_basin t:service_name="Tree Maintenance" t:supervisor_district=10 t:service_request_id=2369627 m:long=-122.3926 m:lat=37.72928

series e:vw6y-z8j6 d:2008-07-02T15:16:55.000Z t:status_notes="See Notes tab for more details -" t:source="Voice In" t:police_district=NORTHERN t:status_description=Closed t:neighborhoods_sffind_boundaries=Marina t:service_subtype="Trees - Damaging_Property" t:agency_responsible="DPW Ops Queue" t:service_details=Lifted_sidewalk_tree_roots t:service_name="Tree Maintenance" t:supervisor_district=2 t:service_request_id=241459 m:long=-122.4381 m:lat=37.80493
```

## Meta Commands

```ls
metric m:lat p:long l:Latitude d:"Latitude of the location, using the WGS84 projection" t:dataTypeName=number

metric m:long p:long l:Longitude d:"Longitude of the location, using the WGS84 projection" t:dataTypeName=number

entity e:vw6y-z8j6 l:"[Notice of Dataset Change] Case Data from San Francisco 311 (SF311)" t:attribution="San Francisco 311" t:url=https://data.sfgov.org/api/views/vw6y-z8j6

property e:vw6y-z8j6 t:meta.view v:id=vw6y-z8j6 v:category="City Infrastructure" v:attributionLink=http://www.sf311.org v:averageRating=0 v:name="[Notice of Dataset Change] Case Data from San Francisco 311 (SF311)" v:attribution="San Francisco 311"

property e:vw6y-z8j6 t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:vw6y-z8j6 t:meta.view.owner v:id=isin-8y46 v:profileImageUrlMedium=/api/users/isin-8y46/profile_images/THUMB v:profileImageUrlLarge=/api/users/isin-8y46/profile_images/LARGE v:screenName=AndyM v:profileImageUrlSmall=/api/users/isin-8y46/profile_images/TINY v:displayName=AndyM

property e:vw6y-z8j6 t:meta.view.tableauthor v:id=isin-8y46 v:profileImageUrlMedium=/api/users/isin-8y46/profile_images/THUMB v:profileImageUrlLarge=/api/users/isin-8y46/profile_images/LARGE v:screenName=AndyM v:profileImageUrlSmall=/api/users/isin-8y46/profile_images/TINY v:roleName=publisher v:displayName=AndyM
```

## Top Records

```ls
| service_request_id | requested_datetime  | closed_date         | updated_datetime    | status_description | status_notes                                                                                                 | agency_responsible | service_name                 | service_subtype           | service_details            | address                                    | supervisor_district | neighborhoods_sffind_boundaries | police_district | lat      | long      | source   | media_url    | 
| ================== | =================== | =================== | =================== | ================== | ============================================================================================================ | ================== | ============================ | ========================= | ========================== | ========================================== | =================== | =============================== | =============== | ======== | ========= | ======== | ============ | 
| 1104032            | 2012-04-12T14:56:47 | 2011-01-31T04:36:00 | 2011-01-31T04:36:00 | Closed             | Case Resolved - Closed                                                                                       | DPW BSM Queue      | Street Defects               | Utility_Excavation        | Utility_Excavation         | Intersection of IRVING ST and SUNSET BLVD  | 4                   | Outer Sunset                    | TARAVAL         | 37.76273 | -122.4959 | Voice In | [null, null] | 
| 2369627            | 2013-05-15T18:09:08 | 2011-06-03T12:00:00 | 2011-06-03T12:00:00 | Closed             | Case Completed - resolved: Request closed by SES . Notes = " BUF Action:PLANT. date completed - 6/3/2011. ". | DPW Ops Queue      | Tree Maintenance             | Trees - Landscaping       | Empty_tree_basin           | Intersection of 3RD ST and WILLIAMS AVE    | 10                  | Bayview                         | BAYVIEW         | 37.72928 | -122.3926 | Voice In | [null, null] | 
| 241459             | 2008-07-02T15:16:55 | 2010-07-12T10:16:59 | 2010-07-12T10:16:59 | Closed             | See Notes tab for more details -                                                                             | DPW Ops Queue      | Tree Maintenance             | Trees - Damaging_Property | Lifted_sidewalk_tree_roots | Intersection of RETIRO WAY and RICO WAY    | 2                   | Marina                          | NORTHERN        | 37.80493 | -122.4381 | Voice In | [null, null] | 
| 241571             | 2008-07-02T17:54:07 | 2010-10-21T12:09:32 | 2010-10-21T12:09:32 | Closed             | See Notes tab for more details -                                                                             | DPW Ops Queue      | Tree Maintenance             | Trees - Overgrown_Tree    | Blocking_street_lights     | 4228 GEARY BLVD, SAN FRANCISCO, CA, 94118  | 1                   | Inner Richmond                  | RICHMOND        | 37.78117 | -122.465  | Voice In | [null, null] | 
| 241917             | 2008-07-03T12:44:26 | 2010-07-06T18:16:58 | 2010-07-06T18:16:58 | Closed             | See Notes tab for more details -                                                                             | DPW Ops Queue      | Street and Sidewalk Cleaning | General Cleaning          | Other Loose Garbage        | Intersection of BRANNAN ST and DELANCEY ST | 6                   | South Beach                     | SOUTHERN        | 37.78361 | -122.3898 | Voice In | [null, null] | 
| 241941             | 2008-07-03T13:24:07 | 2010-08-16T15:19:05 | 2010-08-16T15:19:05 | Closed             | See Notes tab for more details -                                                                             | DPW Ops Queue      | Tree Maintenance             | Trees - Damaging_Property | Lifted_sidewalk_tree_roots | 1901 SUTTER ST, SAN FRANCISCO, CA, 94115   | 5                   |                                 | NORTHERN        | 37.78574 | -122.4323 | Voice In | [null, null] | 
| 243749             | 2008-07-07T15:14:07 | 2010-07-06T15:16:57 | 2010-07-06T15:16:57 | Closed             | See Notes tab for more details -                                                                             | DPW Ops Queue      | Tree Maintenance             | Trees - Overgrown_Tree    | Near_communication_line    | 2043 PALOU AVE, SAN FRANCISCO, CA, 94124   | 10                  |                                 | BAYVIEW         | 37.73847 | -122.3994 | Voice In | [null, null] | 
| 244958             | 2008-07-09T14:57:52 | 2010-07-30T15:17:03 | 2010-07-30T15:17:03 | Closed             | See Notes tab for more details -                                                                             | DPW Ops Queue      | Tree Maintenance             | Trees - Overgrown_Tree    | Near_communication_line    | Intersection of 6TH AVE and CALIFORNIA ST  | 1                   | Presidio Terrace                | RICHMOND        | 37.78499 | -122.4646 | Voice In | [null, null] | 
| 245061             | 2008-07-09T16:57:24 | 2010-07-08T08:16:58 | 2010-07-08T08:16:58 | Closed             | See Notes tab for more details -                                                                             | DPW Ops Queue      | Tree Maintenance             | Trees - Overgrown_Tree    | Near_communication_line    | Intersection of ORD CT and VULCAN STWY     | 8                   | Corona Heights                  | PARK            | 37.76349 | -122.4403 | Voice In | [null, null] | 
| 245369             | 2008-07-10T10:22:27 | 2010-07-08T10:16:58 | 2010-07-08T10:16:58 | Closed             | See Notes tab for more details -                                                                             | DPW Ops Queue      | Tree Maintenance             | Trees - Overgrown_Tree    | Blocking_signs             | 3126 22ND ST, SAN FRANCISCO, CA, 94110     | 9                   | Mission                         | MISSION         | 37.75562 | -122.4173 | Voice In | [null, null] | 
```