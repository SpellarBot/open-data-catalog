# Mobile Food Facility Permit

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/mobile-food-facility-permit-2c164) |
| Metadata | [Link](https://data.sfgov.org/api/views/rqzj-sfat) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/rqzj-sfat/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/rqzj-sfat/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | rqzj-sfat |
| Name | Mobile Food Facility Permit |
| Attribution | San Francisco Department of Public Works |
| Category | Economy and Community |
| Tags | mobile, food, permits, truck, facility, mff |
| Created | 2012-09-24T23:24:01Z |
| Publication Date | 2015-09-11T18:14:20Z |

## Description

Mobile Food Facility Permits including name of vendor, location, type of food sold and status of permit. Mobile Food Facility Permit Schedule is here https://data.sfgov.org/d/jjew-r69b

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type     | Render Type   |
| ======== | ============== | =================== | =================== | ============= | ============= |
| Yes      | series tag     | objectid            | locationid          | text          | number        |
| Yes      | series tag     | applicant           | Applicant           | text          | text          |
| Yes      | series tag     | facilitytype        | FacilityType        | text          | text          |
| Yes      | numeric metric | cnn                 | cnn                 | number        | number        |
| Yes      | series tag     | locationdescription | LocationDescription | text          | text          |
| No       |                | address             | Address             | text          | text          |
| Yes      | series tag     | blocklot            | blocklot            | text          | text          |
| Yes      | series tag     | block               | block               | text          | text          |
| Yes      | series tag     | lot                 | lot                 | text          | text          |
| Yes      | series tag     | permit              | permit              | text          | text          |
| Yes      | series tag     | status              | Status              | text          | text          |
| Yes      | series tag     | fooditems           | FoodItems           | text          | text          |
| No       |                | x                   | X                   | number        | number        |
| No       |                | y                   | Y                   | number        | number        |
| No       |                | latitude            | Latitude            | number        | number        |
| No       |                | longitude           | Longitude           | number        | number        |
| Yes      | series tag     | schedule            | Schedule            | text          | text          |
| Yes      | series tag     | dayshours           | dayshours           | text          | text          |
| No       |                | noisent             | NOISent             | calendar_date | calendar_date |
| No       |                | approved            | Approved            | calendar_date | calendar_date |
| Yes      | series tag     | received            | Received            | text          | text          |
| Yes      | numeric metric | priorpermit         | PriorPermit         | number        | number        |
| Yes      | time           | expirationdate      | ExpirationDate      | calendar_date | calendar_date |
```

## Time Field

```ls
Value = expirationdate
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = address,x,y,latitude,longitude,noisent,approved
```

## Data Commands

```ls
series e:rqzj-sfat d:2014-03-15T00:00:00.000Z t:schedule="http://bsm.sfdpw.org/PermitsTracker/reports/report.aspx?title=schedule&report=rptSchedule&params=permit=13MFF-0102&ExportPDF=1&Filename=13MFF-0102_schedule.pdf" t:status=EXPIRED t:permit=13MFF-0102 t:applicant="Natan's Catering" t:lot=031 t:fooditems="Burgers: melts: hot dogs: burritos:sandwiches: fries: onion rings: drinks" t:block=4101 t:received=2013-04-12 t:facilitytype=Truck t:objectid=437211 t:blocklot=4101031 t:locationdescription="MISSOURI ST: 20TH ST to SIERRA ST (500 - 630)" t:dayshours=Mo-Fr:9AM-10AM/12PM-1PM m:priorpermit=1 m:cnn=9212000

series e:rqzj-sfat d:2016-03-18T15:44:44.000Z t:schedule="http://bsm.sfdpw.org/PermitsTracker/reports/report.aspx?title=schedule&report=rptSchedule&params=permit=16MFF-0010&ExportPDF=1&Filename=16MFF-0010_schedule.pdf" t:status=REQUESTED t:permit=16MFF-0010 t:applicant="Pipo's Grill" t:lot=083 t:fooditems="Tacos: Burritos: Hot Dogs: and Hamburgers" t:block=3549 t:received=2016-02-04 t:facilitytype=Truck t:objectid=751253 t:blocklot=3549083 t:locationdescription="FOLSOM ST: 14TH ST to 15TH ST (1800 - 1899)" m:priorpermit=0 m:cnn=5688000

series e:rqzj-sfat d:2015-03-15T00:00:00.000Z t:schedule="http://bsm.sfdpw.org/PermitsTracker/reports/report.aspx?title=schedule&report=rptSchedule&params=permit=14MFF-0034&ExportPDF=1&Filename=14MFF-0034_schedule.pdf" t:status=EXPIRED t:permit=14MFF-0034 t:applicant="Bach Catering" t:lot=023 t:fooditems="Cold Truck: Cheeseburgers: Burgers: Chicken Bake: Chili Dogs: Hot Dogs: Corn Dogs: Cup of Noodles: Egg Muffins: Tamales: Hot Sandwiches Quesadillas: Gatorade: Juice: Soda: Mikl: Coffee: Hot Cocoa: Hot Tea: Flan: Fruits: Fruit Salad: Yogurt: Candy: Chips:  Donuts: Cookies: Granola: Muffins & Various Drinks & Pre-Packaged Snacks." t:block=5332 t:received=2014-03-13 t:facilitytype=Truck t:objectid=526124 t:blocklot=5332023 t:locationdescription="INDUSTRIAL ST: PALOU AVE to QUESADA AVE (51 - 99) -- SOUTH --" t:dayshours=Mo-Fr:9AM-10AM m:priorpermit=1 m:cnn=7205101
```

## Meta Commands

```ls
metric m:cnn p:integer l:cnn t:dataTypeName=number

metric m:priorpermit p:integer l:PriorPermit t:dataTypeName=number

entity e:rqzj-sfat l:"Mobile Food Facility Permit" t:attribution="San Francisco Department of Public Works" t:url=https://data.sfgov.org/api/views/rqzj-sfat

property e:rqzj-sfat t:meta.view v:id=rqzj-sfat v:category="Economy and Community" v:attributionLink=http://www.sfdpw.org v:averageRating=0 v:name="Mobile Food Facility Permit" v:attribution="San Francisco Department of Public Works"

property e:rqzj-sfat t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:rqzj-sfat t:meta.view.owner v:id=rcpp-nrjq v:profileImageUrlMedium=/api/users/rcpp-nrjq/profile_images/THUMB v:profileImageUrlLarge=/api/users/rcpp-nrjq/profile_images/LARGE v:screenName="Public Works" v:profileImageUrlSmall=/api/users/rcpp-nrjq/profile_images/TINY v:displayName="Public Works"

property e:rqzj-sfat t:meta.view.tableauthor v:id=rcpp-nrjq v:profileImageUrlMedium=/api/users/rcpp-nrjq/profile_images/THUMB v:profileImageUrlLarge=/api/users/rcpp-nrjq/profile_images/LARGE v:screenName="Public Works" v:profileImageUrlSmall=/api/users/rcpp-nrjq/profile_images/TINY v:roleName=editor v:displayName="Public Works"
```

## Top Records

```ls
| objectid | applicant         | facilitytype | cnn      | locationdescription                                             | address          | blocklot | block | lot | permit     | status    | fooditems                                                                                                                                                                                                                                                                                                                                | x             | y             | latitude         | longitude         | schedule                                                                                                                                                    | dayshours                           | noisent | approved            | received   | priorpermit | expirationdate      | 
| ======== | ================= | ============ | ======== | =============================================================== | ================ | ======== | ===== | === | ========== | ========= | ======================================================================================================================================================================================================================================================================================================================================== | ============= | ============= | ================ | ================= | =========================================================================================================================================================== | =================================== | ======= | =================== | ========== | =========== | =================== | 
| 437211   | Natan's Catering  | Truck        | 9212000  | MISSOURI ST: 20TH ST to SIERRA ST (500 - 630)                   | 555 MISSOURI ST  | 4101031  | 4101  | 031 | 13MFF-0102 | EXPIRED   | Burgers: melts: hot dogs: burritos:sandwiches: fries: onion rings: drinks                                                                                                                                                                                                                                                                | 6013632.016   | 2104493.013   | 37.7593037663834 | -122.395902231236 | http://bsm.sfdpw.org/PermitsTracker/reports/report.aspx?title=schedule&report=rptSchedule?ms=permit=13MFF-0102&ExportPDF=1&Filename=13MFF-0102_schedule.pdf | Mo-Fr:9AM-10AM/12PM-1PM             |         | 2013-04-12T00:00:00 | 2013-04-12 | 1           | 2014-03-15T00:00:00 | 
| 751253   | Pipo's Grill      | Truck        | 5688000  | FOLSOM ST: 14TH ST to 15TH ST (1800 - 1899)                     | 1800 FOLSOM ST   | 3549083  | 3549  | 083 | 16MFF-0010 | REQUESTED | Tacos: Burritos: Hot Dogs: and Hamburgers                                                                                                                                                                                                                                                                                                | 6007856.719   | 2107724.046   | 37.7678524427181 | -122.416104892532 | http://bsm.sfdpw.org/PermitsTracker/reports/report.aspx?title=schedule&report=rptSchedule?ms=permit=16MFF-0010&ExportPDF=1&Filename=16MFF-0010_schedule.pdf |                                     |         |                     | 2016-02-04 | 0           |                     | 
| 526124   | Bach Catering     | Truck        | 7205101  | INDUSTRIAL ST: PALOU AVE to QUESADA AVE (51 - 99) -- SOUTH --   | 75 INDUSTRIAL ST | 5332023  | 5332  | 023 | 14MFF-0034 | EXPIRED   | Cold Truck: Cheeseburgers: Burgers: Chicken Bake: Chili Dogs: Hot Dogs: Corn Dogs: Cup of Noodles: Egg Muffins: Tamales: Hot Sandwiches Quesadillas: Gatorade: Juice: Soda: Mikl: Coffee: Hot Cocoa: Hot Tea: Flan: Fruits: Fruit Salad: Yogurt: Candy: Chips: Donuts: Cookies: Granola: Muffins & Various Drinks & Pre-Packaged Snacks. | 6012049.291   | 2097209.482   | 37.7392165862623 | -122.400864373304 | http://bsm.sfdpw.org/PermitsTracker/reports/report.aspx?title=schedule&report=rptSchedule?ms=permit=14MFF-0034&ExportPDF=1&Filename=14MFF-0034_schedule.pdf | Mo-Fr:9AM-10AM                      |         | 2014-03-13T00:00:00 | 2014-03-13 | 1           | 2015-03-15T00:00:00 | 
| 509478   | Sun Rise Catering | Truck        | 11186000 | RUSS ST: HOWARD ST to FOLSOM ST (100 - 199)                     | 150 RUSS ST      | 3731082  | 3731  | 082 | 14MFF-0001 | EXPIRED   | Cold Truck: sandwiches: drinks: snacks: candy: hot coffee                                                                                                                                                                                                                                                                                | 6010358.298   | 2111396.153   | 37.7780755347517 | -122.407711134267 | http://bsm.sfdpw.org/PermitsTracker/reports/report.aspx?title=schedule&report=rptSchedule?ms=permit=14MFF-0001&ExportPDF=1&Filename=14MFF-0001_schedule.pdf | Mo-Fr:9AM-10AM                      |         | 2014-09-10T00:00:00 | 2014-01-08 | 1           | 2015-03-15T00:00:00 | 
| 509492   | Sun Rise Catering | Truck        | 5676000  | FOLSOM ST: RAUSCH ST to RODGERS ST (1148 - 1175)                | 1150 FOLSOM ST   | 3730178  | 3730  | 178 | 14MFF-0001 | EXPIRED   | Cold Truck: sandwiches: drinks: snacks: candy: hot coffee                                                                                                                                                                                                                                                                                | 6009885.08    | 2110631.841   | 37.775950411261  | -122.409294222069 | http://bsm.sfdpw.org/PermitsTracker/reports/report.aspx?title=schedule&report=rptSchedule?ms=permit=14MFF-0001&ExportPDF=1&Filename=14MFF-0001_schedule.pdf | Mo/Tu/We/Th/Fr:9AM-10AM             |         | 2014-09-10T00:00:00 | 2014-01-08 | 1           | 2015-03-15T00:00:00 | 
| 623661   | Julie's Hot Dogs  | Truck        | 9124000  | MISSION ST: 22ND ST to 23RD ST (2600 - 2699)                    | 2601 MISSION ST  | 3637069  | 3637  | 069 | 15MFF-0007 | REQUESTED | Soda: chips: energy drinks: hot dogs: bacon-wrapped hot dogs: fruit: corn                                                                                                                                                                                                                                                                | 6007206.1     | 2103081.156   | 37.7550675419403 | -122.41802613269  | http://bsm.sfdpw.org/PermitsTracker/reports/report.aspx?title=schedule&report=rptSchedule?ms=permit=15MFF-0007&ExportPDF=1&Filename=15MFF-0007_schedule.pdf | Th/Fr/Sa:12PM-3AM                   |         |                     | 2015-02-23 | 0           |                     | 
| 531040   | La Falafel        | Truck        | 13057002 | VALENCIA ST: ROSA PARKS LN to 15TH ST (338 - 399)               | 363 VALENCIA ST  | 3547033  | 3547  | 033 | 14MFF-0088 | EXPIRED   | Falafel Sandwiches: Fries: Soda: Iced Tea & Various Drinks.                                                                                                                                                                                                                                                                              | 6006210.45973 | 2107493.40775 | 37.767126464778  | -122.421782736139 | http://bsm.sfdpw.org/PermitsTracker/reports/report.aspx?title=schedule&report=rptSchedule?ms=permit=14MFF-0088&ExportPDF=1&Filename=14MFF-0088_schedule.pdf | Tu/We/Th:11AM-4PM;Fr/Sa:4PM-11PM    |         | 2014-03-31T00:00:00 | 2014-03-28 | 0           | 2015-03-15T00:00:00 | 
| 626189   | Taza Halal Cart   | Push Cart    | 8742101  | MARKET ST: 01ST ST \ BUSH ST to 02ND ST (501 - 599) -- SOUTH -- | 555 MARKET ST    | 3708057  | 3708  | 057 | 15MFF-0024 | INACTIVE  | Chicken gyro: lamb gyro: chicken gyro plate:lamb gyro plate: combination gyro plate                                                                                                                                                                                                                                                      | 6012693.864   | 2115651.384   | 37.7898898782098 | -122.399930411351 | http://bsm.sfdpw.org/PermitsTracker/reports/report.aspx?title=schedule&report=rptSchedule?ms=permit=15MFF-0024&ExportPDF=1&Filename=15MFF-0024_schedule.pdf | Mo-We:10AM-9PM                      |         |                     | 2015-03-02 | 0           |                     | 
| 646997   | Tacos El Primo    | Truck        | 13660000 | WILLIAMS AVE: APOLLO ST to PHELPS ST \ VESTA ST (300 - 399)     | 345 WILLIAMS AVE | 5423A009 | 5423A | 009 | 15MFF-0122 | REQUESTED | Mexican food: tacos: burritos: tortas: various meat and chicken and fish plate: chile relleno plate: fish plate: bread: flan: rice pudding: bread: fruit juice: vegetable juice: coffee: tea                                                                                                                                             | 6012447.306   | 2093773.934   | 37.7298054805741 | -122.399247104724 | http://bsm.sfdpw.org/PermitsTracker/reports/report.aspx?title=schedule&report=rptSchedule?ms=permit=15MFF-0122&ExportPDF=1&Filename=15MFF-0122_schedule.pdf | Su:8AM-10PM;Mo/Tu/We/Th/Fr:4PM-10PM |         |                     | 2015-04-21 | 1           | 2016-03-15T00:00:00 | 
| 526148   | Cheese Gone Wild  | Truck        | 11544000 | SANSOME ST: PINE ST to CALIFORNIA ST (200 - 299)                | 233 SANSOME ST   | 0260002  | 0260  | 002 | 14MFF-0035 | EXPIRED   | Grilled Cheese Sandwiches                                                                                                                                                                                                                                                                                                                | 6012313.995   | 2116649.543   | 37.792609401119  | -122.401314905451 | http://bsm.sfdpw.org/PermitsTracker/reports/report.aspx?title=schedule&report=rptSchedule?ms=permit=14MFF-0035&ExportPDF=1&Filename=14MFF-0035_schedule.pdf | Th:10AM-2PM                         |         | 2014-03-13T00:00:00 | 2014-03-13 | 0           | 2015-03-15T00:00:00 | 
```