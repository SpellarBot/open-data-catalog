# Current San Francisco Advisories

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/current-san-francisco-advisories-b1338) |
| Metadata | [Link](https://data.sfgov.org/api/views/qn4d-bra2) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/qn4d-bra2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/qn4d-bra2/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | qn4d-bra2 |
| Name | Current San Francisco Advisories |
| Category | Culture and Recreation |
| Created | 2013-07-25T17:18:49Z |
| Publication Date | 2017-01-26T18:22:03Z |

## Description

Current events that impact visitors to San Francisco - Available on our mobile app at sf311.org/mobile

## Columns

```ls
| Included | Schema Type | Field Name       | Name       | Data Type     | Render Type   |
| ======== | =========== | ================ | ========== | ============= | ============= |
| No       |             | id               | ID         | text          | number        |
| Yes      | series tag  | title            | TITLE      | text          | text          |
| Yes      | series tag  | body             | DETAILS    | html          | html          |
| Yes      | series tag  | alert_flag       | ALERT FLAG | text          | text          |
| Yes      | time        | lastauthoreddate | UPDATED    | calendar_date | calendar_date |
| No       |             | created          | CREATED    | calendar_date | calendar_date |
```

## Time Field

```ls
Value = lastauthoreddate
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = id,created
```

## Data Commands

```ls
series e:qn4d-bra2 d:2017-04-19T16:38:31.000Z t:body="<p> Saturday, April 22, 2017</p><p> MISSION CRIT BIKE RACE</p><p> Road Closures:&nbsp; 17th Street between Folsom &amp; Alabama beginning at 12:00 PM to 11:59 PM</p><p> <strong>NO REROUTES HAVE BEEN PLANNED</strong></p>" t:title="MISSION CRITE BIKE RACE SAT 4.22.17" t:alert_flag=NO m:row_number.qn4d-bra2=1

series e:qn4d-bra2 d:2017-04-19T16:43:34.000Z t:body="<p> On Saturday April 22nd, 2017, there will be a combined rally, march, and festival for the March for Science and Earth Day San Francisco.&nbsp;The rally will begin at 11:00 a.m. at Justin Herman Plaza; the march will begin at 12:30 p.m. and go&nbsp;up Market Street toward Civic Center Plaza.&nbsp;The Earth Day festival will take place from 10:00 a.m. to 6:00 p.m. at Civic Center Plaza.</p><p> From 11:30 a.m. to 3:00 p.m., Muni will <a href=""https://www.sfmta.com/sites/default/files/events/2017/Market%20Street%20Reroutes.jpg"" target=""_blank"">reroute transit lines</a>&nbsp;that travel on or across Market Street east of 10th Street.&nbsp;Customers can expect delays and&nbsp;are encouraged to use the Muni Metro subway to enter or leave the downtown area.</p>" t:title="MARCH FOR SCIENCE & EARTH DAY FESTIVAL SAT 4.22.17" t:alert_flag=NO m:row_number.qn4d-bra2=2

series e:qn4d-bra2 d:2017-04-18T16:32:40.000Z t:body="<p> &nbsp;</p><p> The Great Highway is currently open from Lincoln to HWY 35 in both directions.</p><p> Per DPW 4/18/17 9:32 AM</p>" t:title="GREAT HIGHWAY UPDATES" t:alert_flag=NO m:row_number.qn4d-bra2=3
```

## Meta Commands

```ls
metric m:row_number.qn4d-bra2 p:long l:"Row Number"

entity e:qn4d-bra2 l:"Current San Francisco Advisories" t:url=https://data.sfgov.org/api/views/qn4d-bra2

property e:qn4d-bra2 t:meta.view v:id=qn4d-bra2 v:category="Culture and Recreation" v:averageRating=0 v:name="Current San Francisco Advisories"

property e:qn4d-bra2 t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:qn4d-bra2 t:meta.view.owner v:id=isin-8y46 v:profileImageUrlMedium=/api/users/isin-8y46/profile_images/THUMB v:profileImageUrlLarge=/api/users/isin-8y46/profile_images/LARGE v:screenName=AndyM v:profileImageUrlSmall=/api/users/isin-8y46/profile_images/TINY v:displayName=AndyM

property e:qn4d-bra2 t:meta.view.tableauthor v:id=isin-8y46 v:profileImageUrlMedium=/api/users/isin-8y46/profile_images/THUMB v:profileImageUrlLarge=/api/users/isin-8y46/profile_images/LARGE v:screenName=AndyM v:profileImageUrlSmall=/api/users/isin-8y46/profile_images/TINY v:roleName=publisher v:displayName=AndyM
```

## Top Records

```ls
| id | title                                                          | body                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     | alert_flag | lastauthoreddate    | created             | 
| == | ============================================================== | ======================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================== | ========== | =================== | =================== | 
| 7  | MISSION CRITE BIKE RACE SAT 4.22.17                            | Saturday, April 22, 2017
MISSION CRIT BIKE RACE
Road Closures:  17th Street between Folsom & Alabama beginning at 12:00 PM to 11:59 PM
NO REROUTES HAVE BEEN PLANNED                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     | NO         | 2017-04-19T16:38:31 | 2017-04-19T16:38:31 | 
| 2  | MARCH FOR SCIENCE & EARTH DAY FESTIVAL SAT 4.22.17             | On Saturday April 22nd, 2017, there will be a combined rally, march, and festival for the March for Science and Earth Day San Francisco. The rally will begin at 11:00 a.m. at Justin Herman Plaza; the march will begin at 12:30 p.m. and go up Market Street toward Civic Center Plaza. The Earth Day festival will take place from 10:00 a.m. to 6:00 p.m. at Civic Center Plaza.
From 11:30 a.m. to 3:00 p.m., Muni will reroute transit lines that travel on or across Market Street east of 10th Street. Customers can expect delays and are encouraged to use the Muni Metro subway to enter or leave the downtown area.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          | NO         | 2017-04-19T16:43:34 | 2017-04-19T00:23:38 | 
| 3  | GREAT HIGHWAY UPDATES                                          |   The Great Highway is currently open from Lincoln to HWY 35 in both directions.
Per DPW 4/18/17 9:32 AM                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 | NO         | 2017-04-18T16:32:40 | 2017-02-25T23:24:43 | 
| 5  | SFMTA Sales Kiosk Hours of Operation, Effective March 25, 2017 | SFMTA Sales Kiosk Hours of Operation, Effective March 25, 2017
Powell/Market: 8A ? 8P 7 Days per week, including holidays
Hyde/Beach: 8A -8P 7 Days per week, including holidays
Bay/Taylor: 10A ? 4P 7 days per week, including holidays
Presidio/Geary: 10A 4P 7 days per week,  CLOSED HOLIDAYS                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       | NO         | 2017-03-22T17:39:25 | 2017-03-22T17:39:25 | 
| 4  | Marriage Reservations are Being Accepted                       | TEMP EVENT: Marriage Reservations are Being Accepted
  We are accepting Marriage License and Marriage Ceremony Appointments as the problem with creating appointments has been fixed.
  For any customers that have already tried to create an appointment and were charged but did not receive their appointment, please open a Service Request with the following information:
Primary name on reservation
Customer Email Address
Date/time of Marriage License Appointment if any. Amount and Date Charged on Credit Card
Date/time of Marriage Ceremony Appointment if any. Amount and Date Charged on Credit Card
Exact name on Credit Card (Suggest they read it from the credit card and include middle initial if on the card. Ask if they used the same card for both charges or multiple cards).
  TEMP EVENT: All Customers Who Paid for Marriage Appointments Will Have Their Reservation Honored
Any customers who paid for a Marriage License and/or Ceremony Appointment and did not get a confirmation when our reservation system was experiencing issues will have their appointment honored. Please make sure customer knows this, then open a Service Request with the following information to document that the customer paid but did not receive a confirmation. The reservation system was fixed yesterday and is available on our website for all new appointments.
Primary name on reservation
Customer Email Address
Date/time of Marriage License Appointment if any. Amount and Date Charged on Credit Card
Date/time of Marriage Ceremony Appointment if any. Amount and Date Charged on Credit Card
Exact name on Credit Card (Suggest they read it from the credit card and include middle initial if on the card. Ask if they used the same card for both charges or multiple cards).
  | NO         | 2017-03-23T22:22:42 | 2017-03-21T20:57:37 | 
| 6  | 4/20 Event at Sharon Meadow                                    | Name of Organizer: Sounds Bazaar, LLC Time line for set-up and clean-up: Vendor to begin installation of the fencing on Wednesday, April 19th it will come down on Friday, April 21st Impacted Area: The event organizer will be fencing the area around Sharon Meadow.   City Agencies Involved: SFPD, SFFD, DEM, DPW, SFMTA, Sheriff and Juvenile Probation. Hours of Permitted Event: Event is set to open to public from 9 am until 6 pm. Moderate amplified sound will be allowed from 12pm to 5 pm. The event is limited to 18 and over. Event Organizer will also put in place: In addition to 40 security guards, there will be 20 food vendor booths approved by Dept of Public Health, as well as an emergency/medical plan in place.
The Following items are not permitted to be brought in to the event:
No Tents, Canopies, Tables, or other structures
No Unpermitted Vendors
No Coolers larger than 9?x12?
No Barbecues or cooking equipment
No Amplified Sound Equipment
No Generators
No Glass
TRAFFIC CLOSURE: Please note that  JFK Drive between Kezar Drive and Nancy Pelosi Drive will be close to the public and vehicles, as well as part of the Nancy Pelosi, Bowling Green Drive all the way to MLK Jr. Drive.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 | NO         | 2017-04-19T20:00:30 | 2017-04-19T00:13:37 | 
| 1  | LRV4 Testing on J Church Route                                 | Muni will be performing late night tests of the new light rail vehicles on the J Church line starting at 11:59 p.m. every night from Wednesday, April 19th to Saturday, April 29th, 2017. During testing, Muni will provide J Church shuttle buses between Balboa Park and Church/Duboce.
Tests will not impact morning Muni Metro service on the J Church line.
  Inbound to Downtown
Use island stops along Church Street at Day, 24th, 16th, and Market streets; use curbside stops along at all other stops.
  Outbound to Balboa Park Use island stops along Church Street at 16th, 24th, and Day streets and use curbside stops at all other locations from Church & 18th to Balboa Park.
                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         | NO         | 2017-04-19T00:16:22 | 2017-04-19T00:10:33 | 
```