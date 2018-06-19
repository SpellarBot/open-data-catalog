# Los Angeles International Airport - Terminal Concession Locations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/los-angeles-international-airport-terminal-concession-locations) |
| Metadata | [Link](https://data.lacity.org/api/views/j6u4-c4yh) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/j6u4-c4yh/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/j6u4-c4yh/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | j6u4-c4yh |
| Name | Los Angeles International Airport - Terminal Concession Locations |
| Category | A Prosperous City |
| Tags | airport concessions tenant lax |
| Created | 2016-10-13T20:52:10Z |
| Publication Date | 2016-11-07T16:58:01Z |

## Description

Export of Concession information found in LAX content management system with generic information of available concessions at LAX.

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                       | Data Type     | Render Type   |
| ======== | ============== | ========================== | ========================== | ============= | ============= |
| Yes      | series tag     | companylocationid          | CompanyLocationID          | text          | number        |
| Yes      | series tag     | companyid                  | CompanyID                  | text          | number        |
| Yes      | series tag     | companyname                | CompanyName                | text          | text          |
| Yes      | series tag     | companydescription         | CompanyDescription         | text          | text          |
| Yes      | series tag     | companylocationdescription | CompanyLocationDescription | text          | text          |
| Yes      | numeric metric | secuirtycheckpoint         | secuirtycheckpoint         | number        | number        |
| Yes      | series tag     | hours                      | Hours                      | text          | text          |
| Yes      | series tag     | companyurl                 | CompanyURL                 | text          | text          |
| Yes      | series tag     | airlinecode                | AirlineCode                | text          | text          |
| Yes      | series tag     | terminal                   | Terminal                   | text          | text          |
| Yes      | series tag     | location                   | Location                   | text          | text          |
| Yes      | series tag     | categories                 | Categories                 | text          | text          |
| Yes      | series tag     | urllogoimage               | urlLogoImage               | text          | text          |
| Yes      | series tag     | urlfrontimage              | urlFrontImage              | text          | text          |
| Yes      | series tag     | urlmenudoc                 | urlMenuDoc                 | text          | text          |
| Yes      | series tag     | airportname                | AirportName                | text          | text          |
| Yes      | series tag     | locationphone              | LocationPhone              | text          | text          |
| Yes      | series tag     | companylocationlastupdated | CompanyLocationLastUpdated | text          | text          |
| Yes      | series tag     | companylastupdated         | CompanyLastUpdated         | text          | text          |
| No       |                | addresslastupdated         | AddressLastUpdated         | text          | text          |
| No       |                | lat                        | Lat                        | number        | number        |
| No       |                | long                       | Long                       | number        | number        |
| No       |                | address                    | Address                    | text          | text          |
| Yes      | series tag     | city                       | City                       | text          | text          |
| Yes      | series tag     | zip                        | Zip                        | text          | text          |
| Yes      | time           | processdate                | ProcessDate                | calendar_date | calendar_date |
```

## Time Field

```ls
Value = processdate
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = addresslastupdated,lat,long,address
```

## Data Commands

```ls
series e:j6u4-c4yh d:2017-04-21T00:00:01.000Z t:companyurl=www.virginaustralia.com t:companyid=1003 t:airportname=LAX t:terminal="Terminal 3" t:location="Departure Level" t:categories="AIR CARRIER" t:companyname="Virgin Australia Departures" t:companylocationid=1617 t:companydescription="Virgin Australia Departures Terminal 3
Virgin Australia Arrivals Terminal 5" t:locationphone="(855) 253-8021" m:secuirtycheckpoint=0

series e:j6u4-c4yh d:2017-04-21T00:00:01.000Z t:companyurl=www.allegiantair.com t:zip=90045 t:companyid=1007 t:airportname=LAX t:terminal="Terminal 3" t:location=T-3 t:categories="AIR CARRIER" t:companyname="Allegiant Air" t:companylocationid=1548 t:locationphone=(866)719-3910 t:city="Los Angeles" m:secuirtycheckpoint=0

series e:j6u4-c4yh d:2017-04-21T00:00:01.000Z t:companyurl=www.jetblue.com t:zip=90045 t:companyid=1009 t:airportname=LAX t:terminal="Terminal 3" t:location=T-3 t:categories="AIR CARRIER" t:companyname="Jet Blue" t:companylocationid=1550 t:locationphone="(800) 538-2583" t:city="Los Angeles" m:secuirtycheckpoint=0
```

## Meta Commands

```ls
metric m:secuirtycheckpoint p:integer l:secuirtycheckpoint t:dataTypeName=number

entity e:j6u4-c4yh l:"Los Angeles International Airport - Terminal Concession Locations" t:url=https://data.lacity.org/api/views/j6u4-c4yh

property e:j6u4-c4yh t:meta.view v:id=j6u4-c4yh v:category="A Prosperous City" v:averageRating=0 v:name="Los Angeles International Airport - Terminal Concession Locations"

property e:j6u4-c4yh t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:j6u4-c4yh t:meta.view.owner v:id=gudt-ccne v:profileImageUrlMedium=/api/users/gudt-ccne/profile_images/THUMB v:profileImageUrlLarge=/api/users/gudt-ccne/profile_images/LARGE v:screenName="LAWA OpenData" v:profileImageUrlSmall=/api/users/gudt-ccne/profile_images/TINY v:displayName="LAWA OpenData"

property e:j6u4-c4yh t:meta.view.tableauthor v:id=gudt-ccne v:profileImageUrlMedium=/api/users/gudt-ccne/profile_images/THUMB v:profileImageUrlLarge=/api/users/gudt-ccne/profile_images/LARGE v:screenName="LAWA OpenData" v:profileImageUrlSmall=/api/users/gudt-ccne/profile_images/TINY v:roleName=publisher v:displayName="LAWA OpenData"
```

## Top Records

```ls
| companylocationid | companyid | companyname                 | companydescription                                                          | companylocationdescription                                                                                                                                                                                                                                   | secuirtycheckpoint | hours                                     | companyurl              | airlinecode | terminal   | location                     | categories                   | urllogoimage                                                         | urlfrontimage                                                          | urlmenudoc                                                        | airportname | locationphone  | companylocationlastupdated | companylastupdated | addresslastupdated | lat         | long          | address       | city        | zip   | processdate         | 
| ================= | ========= | =========================== | =========================================================================== | ============================================================================================================================================================================================================================================================ | ================== | ========================================= | ======================= | =========== | ========== | ============================ | ============================ | ==================================================================== | ====================================================================== | ================================================================= | =========== | ============== | ========================== | ================== | ================== | =========== | ============= | ============= | =========== | ===== | =================== | 
| 1617              | 1003      | Virgin Australia Departures | Virgin Australia Departures Terminal 3 Virgin Australia Arrivals Terminal 5 |                                                                                                                                                                                                                                                              | 0                  |                                           | www.virginaustralia.com |             | Terminal 3 | Departure Level              | AIR CARRIER                  |                                                                      |                                                                        |                                                                   | LAX         | (855) 253-8021 |                            |                    |                    |             |               |               |             |       | 2017-04-21T00:00:01 | 
| 1548              | 1007      | Allegiant Air               |                                                                             |                                                                                                                                                                                                                                                              | 0                  |                                           | www.allegiantair.com    |             | Terminal 3 | T-3                          | AIR CARRIER                  |                                                                      |                                                                        |                                                                   | LAX         | (866)719-3910  |                            |                    |                    |             |               | 300 World Way | Los Angeles | 90045 | 2017-04-21T00:00:01 | 
| 1550              | 1009      | Jet Blue                    |                                                                             |                                                                                                                                                                                                                                                              | 0                  |                                           | www.jetblue.com         |             | Terminal 3 | T-3                          | AIR CARRIER                  |                                                                      |                                                                        |                                                                   | LAX         | (800) 538-2583 |                            |                    |                    |             |               | 300 World Way | Los Angeles | 90045 | 2017-04-21T00:00:01 | 
| 1551              | 1010      | Volaris                     |                                                                             |                                                                                                                                                                                                                                                              | 0                  |                                           | www.volaris.mx          |             | Terminal 2 | T-2                          | AIR CARRIER                  |                                                                      |                                                                        |                                                                   | LAX         | (866) 988-3527 |                            |                    |                    |             |               | 200 World Way | Los Angeles | 90045 | 2017-04-21T00:00:01 | 
| 1572              | 1029      | Pinkberry                   |                                                                             |                                                                                                                                                                                                                                                              | 1                  |                                           |                         |             | Terminal 1 | Departure Level - Food Court | FOOD AND BEVERAGE FACILITIES | http://www.lawa.org/uploadedImages/LAX/Tenants//images/logo_1572.png | http://www.lawa.org/uploadedImages/LAX/Tenants//images/tenant_1572.jpg | http://www.lawa.org/uploadedImages/LAX/Tenants//pdf/menu_1572.pdf | LAX         | 310-947-5243   |                            |                    |                    | 33.946003   | -118.401196   | 100 World Way | Los Angeles | 90045 | 2017-04-21T00:00:01 | 
| 1682              | 1118      | 800 Degrees Pizza           |                                                                             | 800 Degrees Pizza ? a Los Angeles based concept ? offers traditional Neapolitan pizza baked in an 800 degree real wood-burning oven. Passengers can order from a few favorite combinations, or can personalize their pizza and create their own masterpiece! | 1                  | M-F 8:00am - 7:00pm S-Su 10:00am - 4:00pm |                         |             | TBIT       | Great Hall - Food Court      | FOOD AND BEVERAGE FACILITIES | http://www.lawa.org/uploadedImages/LAX/Tenants//images/logo_1682.png | http://www.lawa.org/uploadedImages/LAX/Tenants//images/tenant_1682.jpg | http://www.lawa.org/uploadedImages/LAX/Tenants//pdf/menu_1682.pdf | LAX         | (310) 258-9541 |                            |                    |                    | 33.94385039 | -118.41019519 | 380 World Way | Los Angeles | 90045 | 2017-04-21T00:00:01 | 
| 1683              | 1119      | Umami Burger                |                                                                             |                                                                                                                                                                                                                                                              | 1                  |                                           |                         |             | TBIT       | Great Hall - Food Court      | FOOD AND BEVERAGE FACILITIES | http://www.lawa.org/uploadedImages/LAX/Tenants//images/logo_1683.png | http://www.lawa.org/uploadedImages/LAX/Tenants//images/tenant_1683.jpg | http://www.lawa.org/uploadedImages/LAX/Tenants//pdf/menu_1683.pdf | LAX         | 310-646-1770   |                            |                    |                    | 33.94387796 | -118.41006045 | 380 World Way | Los Angeles | 90045 | 2017-04-21T00:00:01 | 
| 1684              | 1120      | ink.sack                    |                                                                             |                                                                                                                                                                                                                                                              | 1                  |                                           |                         |             | TBIT       | Great Hall                   | FOOD AND BEVERAGE FACILITIES | http://www.lawa.org/uploadedImages/LAX/Tenants//images/logo_1684.png | http://www.lawa.org/uploadedImages/LAX/Tenants//images/tenant_1684.jpg | http://www.lawa.org/uploadedImages/LAX/Tenants//pdf/menu_1684.pdf | LAX         | 310-646-1770   |                            |                    |                    | 33.94331034 | -118.41055974 | 380 World Way | Los Angeles | 90045 | 2017-04-21T00:00:01 | 
| 1685              | 1121      | Vino Volo                   |                                                                             |                                                                                                                                                                                                                                                              | 1                  |                                           |                         |             | TBIT       | Great Hall                   | FOOD AND BEVERAGE FACILITIES | http://www.lawa.org/uploadedImages/LAX/Tenants//images/logo_1685.png | http://www.lawa.org/uploadedImages/LAX/Tenants//images/tenant_1685.jpg | http://www.lawa.org/uploadedImages/LAX/Tenants//pdf/menu_1685.pdf | LAX         | 310-646-1770   |                            |                    |                    | 33.94321449 | -118.41052878 | 380 World Way | Los Angeles | 90045 | 2017-04-21T00:00:01 | 
| 1686              | 1122      | Starbucks Evenings          |                                                                             |                                                                                                                                                                                                                                                              | 1                  |                                           |                         |             | TBIT       | South Concourse              | FOOD AND BEVERAGE FACILITIES | http://www.lawa.org/uploadedImages/LAX/Tenants//images/logo_1686.png | http://www.lawa.org/uploadedImages/LAX/Tenants//images/tenant_1686.jpg | http://www.lawa.org/uploadedImages/LAX/Tenants//pdf/menu_1686.pdf | LAX         | (310) 258-9627 |                            |                    |                    | 33.940304   | -118.409946   | 380 World Way | Los Angeles | 90045 | 2017-04-21T00:00:01 | 
```