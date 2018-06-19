# Mobile Food Schedule

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/mobile-food-schedule-7fd4d) |
| Metadata | [Link](https://data.sfgov.org/api/views/jjew-r69b) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/jjew-r69b/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/jjew-r69b/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | jjew-r69b |
| Name | Mobile Food Schedule |
| Attribution | Department of Public Works |
| Category | Economy and Community |
| Tags | mobile, food, trucks, schedule, permits, facility, mff |
| Created | 2012-09-24T23:18:08Z |
| Publication Date | 2017-02-07T22:41:03Z |

## Description

A child data set of --Mobile Food Facility Permit-- includes day of week, start / end time, location and a description of type of food sold by vendor. Mobile Food Facility Permit data is here:  https://data.sfgov.org/d/rqzj-sfat

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type     | Render Type   |
| ======== | ============== | ================== | ================== | ============= | ============= |
| Yes      | numeric metric | dayorder           | DayOrder           | number        | number        |
| Yes      | series tag     | dayofweekstr       | DayOfWeekStr       | text          | text          |
| Yes      | series tag     | starttime          | starttime          | text          | text          |
| Yes      | series tag     | endtime            | endtime            | text          | text          |
| Yes      | series tag     | permit             | permit             | text          | text          |
| Yes      | series tag     | location           | PermitLocation     | text          | text          |
| Yes      | series tag     | locationdesc       | locationdesc       | text          | text          |
| Yes      | series tag     | optionaltext       | optionaltext       | text          | text          |
| Yes      | numeric metric | locationid         | locationid         | number        | number        |
| Yes      | numeric metric | scheduleid         | scheduleid         | number        | number        |
| Yes      | series tag     | start24            | start24            | text          | text          |
| Yes      | series tag     | end24              | end24              | text          | text          |
| Yes      | numeric metric | cnn                | CNN                | number        | number        |
| Yes      | time           | addr_date_create   | Addr_Date_Create   | calendar_date | calendar_date |
| No       |                | addr_date_modified | Addr_Date_Modified | calendar_date | calendar_date |
| Yes      | series tag     | block              | block              | text          | text          |
| Yes      | series tag     | lot                | lot                | text          | text          |
| Yes      | series tag     | coldtruck          | ColdTruck          | text          | text          |
| Yes      | series tag     | applicant          | Applicant          | text          | text          |
| No       |                | x                  | X                  | number        | number        |
| No       |                | y                  | Y                  | number        | number        |
| No       |                | latitude           | Latitude           | number        | number        |
| No       |                | longitude          | Longitude          | number        | number        |
```

## Time Field

```ls
Value = addr_date_create
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = addr_date_modified,x,y,latitude,longitude
```

## Data Commands

```ls
series e:jjew-r69b d:2011-06-07T11:58:19.000Z t:endtime=1PM t:locationdesc="Setup at 650 Pennsylvania Ave. 1:10pm-1:20pm" t:coldtruck=Y t:starttime=12PM t:location="Assessors Block 4103/Lot023A" t:start24=12:00 t:permit=13MFF-0102 t:block=4103 t:optionaltext="Burgers, melts, hot dogs, burritos,sandwiches, fries, onion rings, drinks" t:dayofweekstr=Friday t:applicant="Natan's Catering" t:lot=023A t:end24=13:00 m:locationid=437207 m:dayorder=5 m:cnn=0

series e:jjew-r69b d:2011-08-31T15:37:17.000Z t:endtime=1PM t:locationdesc="Set-up at 400 Clay St: 7:00am-7:10am, 10:00am-10:10am, 12:00pm-12:10pm" t:coldtruck=Y t:starttime=12PM t:location="432 CLAY ST" t:start24=12:00 t:permit=14MFF-0109 t:block=0206 t:optionaltext="COLD TRUCK. Deli: bbq chicken skewer, Chinese spring roll, Chinese fried rice/noodle, fried chicken leg/wing, bbq chicken sandwich, chicken cheese burger, burrito, lumpia. Snack: sunflower seeds, muffins, chips, snickers, kit-kat, 10 types of chocolate. Drinks: Coke, 7-Up, Dr. Pepper, Pepsi, Redbull, Vitamin Water, Rockstar, Coconut Juice, Water. Hot drinks: coffee, tea." t:dayofweekstr=Wednesday t:applicant="Mang Hang Catering" t:lot=006 t:end24=13:00 m:locationid=559779 m:dayorder=3 m:cnn=4083000

series e:jjew-r69b d:2011-06-07T08:52:40.000Z t:endtime=10AM t:locationdesc=9:30am-9:35am t:coldtruck=Y t:starttime=9AM t:location="1150 FOLSOM ST" t:start24=09:00 t:permit=14MFF-0001 t:block=3730 t:optionaltext="Cold Truck: sandwiches, drinks, snacks, candy, hot coffee" t:dayofweekstr=Tuesday t:applicant="Sun Rise Catering" t:lot=178 t:end24=10:00 m:locationid=509492 m:dayorder=2 m:cnn=5676000
```

## Meta Commands

```ls
metric m:dayorder p:integer l:DayOrder t:dataTypeName=number

metric m:locationid p:integer l:locationid t:dataTypeName=number

metric m:scheduleid p:long l:scheduleid t:dataTypeName=number

metric m:cnn p:integer l:CNN t:dataTypeName=number

entity e:jjew-r69b l:"Mobile Food Schedule" t:attribution="Department of Public Works" t:url=https://data.sfgov.org/api/views/jjew-r69b

property e:jjew-r69b t:meta.view v:id=jjew-r69b v:category="Economy and Community" v:attributionLink=http://www.sfdpw.org v:averageRating=0 v:name="Mobile Food Schedule" v:attribution="Department of Public Works"

property e:jjew-r69b t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:jjew-r69b t:meta.view.owner v:id=rcpp-nrjq v:profileImageUrlMedium=/api/users/rcpp-nrjq/profile_images/THUMB v:profileImageUrlLarge=/api/users/rcpp-nrjq/profile_images/LARGE v:screenName="Public Works" v:profileImageUrlSmall=/api/users/rcpp-nrjq/profile_images/TINY v:displayName="Public Works"

property e:jjew-r69b t:meta.view.tableauthor v:id=rcpp-nrjq v:profileImageUrlMedium=/api/users/rcpp-nrjq/profile_images/THUMB v:profileImageUrlLarge=/api/users/rcpp-nrjq/profile_images/LARGE v:screenName="Public Works" v:profileImageUrlSmall=/api/users/rcpp-nrjq/profile_images/TINY v:roleName=editor v:displayName="Public Works"
```

## Top Records

```ls
| dayorder | dayofweekstr | starttime | endtime | permit     | location                      | locationdesc                                                                                                   | optionaltext                                                                                                                                                                                                                                                                                                                                                                          | locationid | scheduleid | start24 | end24 | cnn     | addr_date_create    | addr_date_modified  | block | lot  | coldtruck | applicant          | x             | y             | latitude           | longitude           | 
| ======== | ============ | ========= | ======= | ========== | ============================= | ============================================================================================================== | ===================================================================================================================================================================================================================================================================================================================================================================================== | ========== | ========== | ======= | ===== | ======= | =================== | =================== | ===== | ==== | ========= | ================== | ============= | ============= | ================== | =================== | 
| 5        | Friday       | 12PM      | 1PM     | 13MFF-0102 | Assessors Block 4103/Lot023A  | Setup at 650 Pennsylvania Ave. 1:10pm-1:20pm                                                                   | Burgers, melts, hot dogs, burritos,sandwiches, fries, onion rings, drinks                                                                                                                                                                                                                                                                                                             | 437207     |            | 12:00   | 13:00 | 0       | 2011-06-07T11:58:19 | 2011-06-07T11:58:43 | 4103  | 023A | Y         | Natan's Catering   | 6014314.885   | 2104114.856   | 37.758303395642486 | -122.39351405481675 | 
| 3        | Wednesday    | 12PM      | 1PM     | 14MFF-0109 | 432 CLAY ST                   | Set-up at 400 Clay St: 7:00am-7:10am, 10:00am-10:10am, 12:00pm-12:10pm                                         | COLD TRUCK. Deli: bbq chicken skewer, Chinese spring roll, Chinese fried rice/noodle, fried chicken leg/wing, bbq chicken sandwich, chicken cheese burger, burrito, lumpia. Snack: sunflower seeds, muffins, chips, snickers, kit-kat, 10 types of chocolate. Drinks: Coke, 7-Up, Dr. Pepper, Pepsi, Redbull, Vitamin Water, Rockstar, Coconut Juice, Water. Hot drinks: coffee, tea. | 559779     |            | 12:00   | 13:00 | 4083000 | 2011-08-31T15:37:17 | 2011-08-31T15:38:07 | 0206  | 006  | Y         | Mang Hang Catering | 6012503.29414 | 2117510.66106 | 37.794984386224662 | -122.40072044206335 | 
| 2        | Tuesday      | 9AM       | 10AM    | 14MFF-0001 | 1150 FOLSOM ST                | 9:30am-9:35am                                                                                                  | Cold Truck: sandwiches, drinks, snacks, candy, hot coffee                                                                                                                                                                                                                                                                                                                             | 509492     |            | 09:00   | 10:00 | 5676000 | 2011-06-07T08:52:40 | 2011-06-07T08:52:58 | 3730  | 178  | Y         | Sun Rise Catering  | 6009954.96844 | 2110600.81776 | 37.775869144021151 | -122.40905026920332 | 
| 2        | Tuesday      | 7AM       | 4PM     | 13MFF-0123 | 235 15TH ST                   | Truck located on 15th Street in the first parking space west of the 15th Street and Rhode Island intersection. | 100% Grass fed beef hot dogs, wellshire bacon wrapped hot dogs, beef & heirloom pork spicy link, smoked pork bratwurst, organic chicken apple sausage, Irish breakfast rolls, sandwiches, various sides (fries, potato salad, coleslaw, salad) & ice cream.                                                                                                                           | 487908     |            | 07:00   | 16:00 | 635000  | 2013-10-22T11:47:21 | 2013-10-22T14:12:20 | 3936  | 001  | N         | Mr. Nice, LLC      | 6011599.02957 | 2107445.81451 | 37.767298186369068 | -122.40314102991042 | 
| 1        | Monday       | 1PM       | 2PM     | 13MFF-0102 | Assessors Block 4281a/Lot012A | Setup at 2200 26th St. 1:15pm-1:20pm                                                                           | Burgers, melts, hot dogs, burritos,sandwiches, fries, onion rings, drinks                                                                                                                                                                                                                                                                                                             | 437217     |            | 13:00   | 14:00 | 1507000 | 2011-06-07T12:40:07 | 2011-06-07T12:40:27 | 4281a | 012A | Y         | Natan's Catering   | 6011939.286   | 2101416.045   | 37.750760769460129 | -122.40154029135653 | 
| 0        | Sunday       | 5PM       | 10PM    | 13MFF-0112 | 2142 JERROLD AVE              | Set-up at 2100 Jerrold Ave: 5:00pm-9:30pm                                                                      | Tacos, Burritos , Tortas, Quesadillas & Beverages                                                                                                                                                                                                                                                                                                                                     | 453014     |            | 17:00   | 22:00 | 7501000 | 2011-10-25T08:58:59 | 2011-10-25T08:59:27 | 5230  | 011  | N         | Tacos Santana      | 6012560.69539 | 2099100.15603 | 37.744436489303595 | -122.39922883916833 | 
| 1        | Monday       | 8AM       | 5PM     | 16MFF-0032 | 2198 OAKDALE AVE              |                                                                                                                | Tacos, burritos, quesadillas, soda & water                                                                                                                                                                                                                                                                                                                                            | 762514     |            | 08:00   | 17:00 | 9794000 | 2011-07-27T11:46:51 | 2011-07-27T11:47:09 | 5590A | 008  | N         | Tacos Rodriguez    | 6011890.27099 | 2097853.05368 | 37.740974826226491 | -122.40145941403989 | 
| 2        | Tuesday      | 10AM      | 11AM    | 14MFF-0109 | 690 MISSION ST                | 7:10am-7:15am, 10:05am-10:15am, 12:00pm-12:05pm                                                                | COLD TRUCK. Deli: bbq chicken skewer, Chinese spring roll, Chinese fried rice/noodle, fried chicken leg/wing, bbq chicken sandwich, chicken cheese burger, burrito, lumpia. Snack: sunflower seeds, muffins, chips, snickers, kit-kat, 10 types of chocolate. Drinks: Coke, 7-Up, Dr. Pepper, Pepsi, Redbull, Vitamin Water, Rockstar, Coconut Juice, Water. Hot drinks: coffee, tea. | 559776     |            | 10:00   | 11:00 | 9094000 | 2011-08-31T15:20:16 | 2011-08-31T15:20:56 | 3707  | 024  | Y         | Mang Hang Catering | 6012107.51053 | 2114409.4119  | 37.786447007961982 | -122.40187181336954 | 
| 4        | Thursday     | 9AM       | 10AM    | 14MFF-0001 | 640 NATOMA ST                 | 9:35am-9:45am                                                                                                  | Cold Truck: sandwiches, drinks, snacks, candy, hot coffee                                                                                                                                                                                                                                                                                                                             | 509493     |            | 09:00   | 10:00 | 9514000 | 2011-06-07T08:53:30 | 2011-06-07T08:53:46 | 3727  | 052  | Y         | Sun Rise Catering  | 6009432.76097 | 2111288.855   | 37.777729065088565 | -122.4109053319889  | 
| 6        | Saturday     | 10AM      | 11AM    | 13MFF-0102 | Assessors Block 7295/Lot022   | Setup at 501 Buckingham Way. 11:50am-12:00pm                                                                   | Burgers, melts, hot dogs, burritos,sandwiches, fries, onion rings, drinks                                                                                                                                                                                                                                                                                                             | 437194     |            | 10:00   | 11:00 | 0       | 2011-06-07T10:17:00 | 2011-06-07T10:18:22 | 7295  | 022  | Y         | Natan's Catering   | 5989624.724   | 2094318.981   | 37.730003683189196 | -122.4781863254146  | 
```