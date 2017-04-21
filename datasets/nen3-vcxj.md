# Public Technology Resources

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/public-technology-resources-134a0) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/nen3-vcxj) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/nen3-vcxj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/nen3-vcxj/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | nen3-vcxj |
| Name | Public Technology Resources |
| Attribution | City of Chicago |
| Category | Facilities & Geographic Boundaries |
| Tags | facilities, gis |
| Created | 2011-04-08T20:00:12Z |
| Publication Date | 2013-02-11T23:03:53Z |

## Description

Chicago sites that offer free or affordable technology resources and services, like computers with Internet access, Wi-Fi hotspots and technology training. Call or visit the organization's website before going to the location. For more information, visit http://locations.weconnectchicago.org/.

## Columns

```ls
| Included | Schema Type | Field Name     | Name           | Data Type | Render Type |
| ======== | =========== | ============== | ============== | ========= | =========== |
| No       | time        | :updated_at    | updated_at     | meta_data | meta_data   |
| Yes      | series tag  | type           | TYPE           | text      | text        |
| Yes      | series tag  | facility       | FACILITY       | text      | text        |
| Yes      | series tag  | street_address | STREET ADDRESS | text      | text        |
| Yes      | series tag  | city           | CITY           | text      | text        |
| Yes      | series tag  | state          | STATE          | text      | text        |
| Yes      | series tag  | zip            | ZIP            | text      | text        |
| Yes      | series tag  | phone          | PHONE          | text      | text        |
| Yes      | series tag  | website        | WEBSITE        | url       | url         |
| Yes      | series tag  | hours          | HOURS          | text      | text        |
| Yes      | series tag  | appointment    | APPOINTMENT    | text      | text        |
| Yes      | series tag  | internet       | INTERNET       | checkbox  | checkbox    |
| Yes      | series tag  | wifi           | WIFI           | checkbox  | checkbox    |
| Yes      | series tag  | training       | TRAINING       | checkbox  | checkbox    |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:nen3-vcxj d:2012-03-22T08:47:50.000Z t:training=false t:zip=60827 t:wifi=true t:phone="(312) 747-3270" t:facility=Altgeld t:website=http://www.chipublib.org/branch/details/library/altgeld/ t:hours="M: 2PM-6PM; TU, TH: 10AM-6PM; W: 12PM-8PM; F, SA: 9AM-5PM; SU: Closed" t:state=IL t:street_address="13281 S. Corliss Avenue" t:type="Chicago Public Library" t:internet=true t:city=Chicago t:appointment=NA m:row_number.nen3-vcxj=1

series e:nen3-vcxj d:2012-03-22T08:47:50.000Z t:training=true t:zip=60629 t:wifi=false t:phone="(312) 212-1290" t:facility="Goodwill Industries of Metropolitan Chicago" t:website="http://www.goodwillchicago.com/page.asp?dbID=78" t:hours="M-F: 8:30AM-4PM" t:state=IL t:street_address="2435 W. 63rd Street" t:type="Community Technology Center" t:internet=true t:city=Chicago t:appointment=No m:row_number.nen3-vcxj=2

series e:nen3-vcxj d:2012-03-22T08:47:50.000Z t:training=true t:zip=60638 t:wifi=false t:phone="(773) 767-7773" t:facility="Polish American Association" t:website=http://www.polish.org/ t:hours="TU-TH 1PM-8:45PM; SA: 10AM-5:45PM; M, F, SU: Closed" t:state=IL t:street_address="6276 W. Archer" t:type="WorkForce Center" t:internet=true t:city=Chicago t:appointment=NA m:row_number.nen3-vcxj=3
```

## Meta Commands

```ls
metric m:row_number.nen3-vcxj p:long l:"Row Number"

entity e:nen3-vcxj l:"Public Technology Resources" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/nen3-vcxj

property e:nen3-vcxj t:meta.view v:id=nen3-vcxj v:category="Facilities & Geographic Boundaries" v:attributionLink=http://locations.weconnectchicago.org/ v:averageRating=0 v:name="Public Technology Resources" v:attribution="City of Chicago"

property e:nen3-vcxj t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:nen3-vcxj t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```

## Top Records

```ls
| :updated_at | type                        | facility                                       | street_address                | city    | state | zip   | phone          | website                                                                                           | hours                                                                 | appointment | internet | wifi  | training | 
| =========== | =========================== | ============================================== | ============================= | ======= | ===== | ===== | ============== | ================================================================================================= | ===================================================================== | =========== | ======== | ===== | ======== | 
| 1332406070  | Chicago Public Library      | Altgeld                                        | 13281 S. Corliss Avenue       | Chicago | IL    | 60827 | (312) 747-3270 | [http://www.chipublib.org/branch/details/library/altgeld/, null]                                  | M: 2PM-6PM; TU, TH: 10AM-6PM; W: 12PM-8PM; F, SA: 9AM-5PM; SU: Closed | NA          | true     | true  | false    | 
| 1332406070  | Community Technology Center | Goodwill Industries of Metropolitan Chicago    | 2435 W. 63rd Street           | Chicago | IL    | 60629 | (312) 212-1290 | [http://www.goodwillchicago.com/page.asp?dbID=78, null]                                           | M-F: 8:30AM-4PM                                                       | No          | true     | false | true     | 
| 1332406070  | WorkForce Center            | Polish American Association                    | 6276 W. Archer                | Chicago | IL    | 60638 | (773) 767-7773 | [http://www.polish.org/, null]                                                                    | TU-TH 1PM-8:45PM; SA: 10AM-5:45PM; M, F, SU: Closed                   | NA          | true     | false | true     | 
| 1332406070  | Community Technology Center | Chinese American Service League                | 2141 S. Tan Court             | Chicago | IL    | 60616 | (312) 791-0418 | [http://www.caslservice.org, null]                                                                | M-F: 9AM-5PM                                                          | No          | true     | true  | true     | 
| 1332406070  | Community Technology Center | Back of the Yards Neighborhood Council CTC     | 1751 W 47th Street, 2nd Floor | Chicago | IL    | 60609 | (773) 523-4416 | [http://www.bync.org, null]                                                                       | M-F: 9AM-7PM                                                          |             | true     | true  | true     | 
| 1332406070  | Community Technology Center | Rogers Park Computer Lab and Technology Center | 1557 W. Howard                | Chicago | IL    | 60626 | (773) 508-5885 | [http://www.rogers-park.com, null]                                                                | M-F: 9AM-5PM                                                          | Yes         | true     | true  | true     | 
| 1332406070  | Business Resource Network   | Greater Auburn Gresham Development Corporation | 1159 W. 79th Street           | Chicago | IL    | 60620 | (773) 483-3696 | [http://www.auburngreshamportal.org, null]                                                        | M-F 9a- 5P                                                            | yes         | true     | true  | true     | 
| 1332406070  | Senior Center               | Abbot Park Satellite Center                    | 49 E. 95th St.                | Chicago | IL    | 60619 | (312) 745-3493 | [http://www.cityofchicago.org/city/en/depts/fss/supp_info/satellite_centerinformation.html, null] | M-F: 8:30AM-4:30PM; SA-SU: Closed                                     | Yes         | false    | false | true     | 
| 1332406070  | Community Technology Center | South Loop CTC                                 | 1521 S. Wabash Ave            | Chicago | IL    | 60605 | (312) 447-4681 | [http://www.mercyhousing.org, null]                                                               | M-F: 9AM-5PM                                                          |             | true     | false | true     | 
| 1332406070  | Community Technology Center | Hispanic Housing Development Corporation       | 2610 W. North Ave             | Chicago | IL    | 60647 | (773) 862-1892 | [http://www.hispanichousingdevelopment.com/opportunities/workforce.html, null]                    | M-F: 9AM-5PM                                                          | No          | true     | false | true     | 
```