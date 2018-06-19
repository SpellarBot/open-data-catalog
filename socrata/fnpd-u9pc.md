# Actively Licensed Youth Camps

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/actively-licensed-youth-camps) |
| Metadata | [Link](https://data.ct.gov/api/views/fnpd-u9pc) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/fnpd-u9pc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/fnpd-u9pc/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | fnpd-u9pc |
| Name | Actively Licensed Youth Camps |
| Attribution | Office of Early Childhood |
| Category | Health and Human Services |
| Tags | youth, camp, license |
| Created | 2014-09-29T20:01:19Z |
| Publication Date | 2014-09-30T13:25:40Z |

## Description

This dataset is a listing of actively licensed youth camps in Connecticut and is updated on a periodic basis. This data is for general information only. To accurately verify a whether a youth camp is currently licensed, please refer to the following:http://www.ct.gov/oec/cwp/view.asp?a=4542&q=545168#Check

## Columns

```ls
| Included | Schema Type | Field Name              | Name                    | Data Type     | Render Type   |
| ======== | =========== | ======================= | ======================= | ============= | ============= |
| Yes      | series tag  | license_type            | License Type            | text          | text          |
| Yes      | series tag  | license_number          | License Number          | text          | text          |
| Yes      | time        | expiration_date         | Expiration Date         | calendar_date | calendar_date |
| Yes      | series tag  | camp_name               | Camp Name               | text          | text          |
| No       |             | camp_address_2          | Camp Address 2          | text          | text          |
| No       |             | camp_address_city       | Camp Address City       | text          | text          |
| No       |             | camp_address_state      | Camp Address State      | text          | text          |
| No       |             | camp_address_zip        | Camp Address Zip        | text          | text          |
| Yes      | series tag  | multiple_camp_locations | Multiple Camp Locations | text          | text          |
| Yes      | series tag  | camp_phone              | Camp Phone              | text          | text          |
| Yes      | series tag  | camp_service_type       | Camp Service Type       | text          | text          |
| Yes      | series tag  | camp_type               | Camp Type               | text          | text          |
| Yes      | series tag  | camp_gender             | Camp Gender             | text          | text          |
| Yes      | series tag  | min_camper_age          | Min. Camper Age         | text          | text          |
| Yes      | series tag  | max_camper_age          | Max. Camper Age         | text          | text          |
| Yes      | series tag  | food_service            | Food Service            | text          | text          |
| Yes      | series tag  | water_supply            | Water Supply            | text          | text          |
| Yes      | series tag  | sponsor_name            | Sponsor Name            | text          | text          |
| No       |             | sponsor_address_1       | Sponsor Address 1       | text          | text          |
| No       |             | sponsor_address_2       | Sponsor Address 2       | text          | text          |
| No       |             | sponsor_address_city    | Sponsor Address City    | text          | text          |
| No       |             | sponsor_address_state   | Sponsor Address State   | text          | text          |
| No       |             | sponsor_address_zip     | Sponsor Address Zip     | text          | text          |
| Yes      | series tag  | sponsor_phone           | Sponsor Phone           | text          | text          |
```

## Time Field

```ls
Value = expiration_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = camp_address_2,camp_address_city,camp_address_state,camp_address_zip,sponsor_address_1,sponsor_address_2,sponsor_address_city,sponsor_address_state,sponsor_address_zip
```

## Data Commands

```ls
series e:fnpd-u9pc d:2015-06-30T00:00:00.000Z t:camp_name=THRIVE t:license_type="Youth Camp" t:min_camper_age="6 Years" t:license_number=YCYC.01145 t:camp_service_type=Sports t:max_camper_age="12 Years" t:camp_type="Day Camp" t:food_service=No t:multiple_camp_locations=No t:sponsor_phone="(860) 214-8344" t:camp_phone="(860) 214-8344" t:water_supply="Public Water" t:sponsor_name="KINETIC HOPE LLC" t:camp_gender=Co-Ed m:row_number.fnpd-u9pc=1

series e:fnpd-u9pc d:2015-05-31T00:00:00.000Z t:camp_name="The Stanwich Club" t:license_type="Youth Camp" t:min_camper_age="3 Years" t:license_number=YCYC.00533 t:camp_service_type=General t:max_camper_age="13 Years" t:camp_type="Day Camp" t:food_service=Yes t:multiple_camp_locations=No t:sponsor_phone="(203) 869-0555 x225" t:camp_phone="(203) 869-0555 x236" t:water_supply="Private Well" t:sponsor_name="THE STANWICH CLUB INC" t:camp_gender=Co-Ed m:row_number.fnpd-u9pc=2

series e:fnpd-u9pc d:2015-06-30T00:00:00.000Z t:camp_name="TOM MOORE BASKETBALL CAMP AT QUINNIPIAC" t:license_type="Youth Camp" t:min_camper_age="6 Years" t:license_number=YCYC.01101 t:camp_service_type=Sports t:max_camper_age="16 Years" t:camp_type="Day Camp" t:food_service=No t:multiple_camp_locations=No t:sponsor_phone="(203) 582-3806" t:camp_phone="(203) 582-3806" t:water_supply="Public Water" t:sponsor_name="QUINNIPIAC UNIVERSITY" t:camp_gender=Male m:row_number.fnpd-u9pc=3
```

## Meta Commands

```ls
metric m:row_number.fnpd-u9pc p:long l:"Row Number"

entity e:fnpd-u9pc l:"Actively Licensed Youth Camps" t:attribution="Office of Early Childhood" t:url=https://data.ct.gov/api/views/fnpd-u9pc

property e:fnpd-u9pc t:meta.view v:id=fnpd-u9pc v:category="Health and Human Services" v:attributionLink="http://www.ct.gov/oec/cwp/view.asp?a=4542&q=545168#Check" v:averageRating=0 v:name="Actively Licensed Youth Camps" v:attribution="Office of Early Childhood"

property e:fnpd-u9pc t:meta.view.license v:name="Public Domain"

property e:fnpd-u9pc t:meta.view.owner v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"

property e:fnpd-u9pc t:meta.view.tableauthor v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:roleName=administrator v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"
```

## Top Records

```ls
| license_type | license_number | expiration_date     | camp_name                                            | camp_address_2              | camp_address_city | camp_address_state | camp_address_zip | multiple_camp_locations | camp_phone          | camp_service_type | camp_type              | camp_gender | min_camper_age | max_camper_age | food_service | water_supply | sponsor_name                   | sponsor_address_1                    | sponsor_address_2 | sponsor_address_city | sponsor_address_state | sponsor_address_zip | sponsor_phone       | 
| ============ | ============== | =================== | ==================================================== | =========================== | ================= | ================== | ================ | ======================= | =================== | ================= | ====================== | =========== | ============== | ============== | ============ | ============ | ============================== | ==================================== | ================= | ==================== | ===================== | =================== | =================== | 
| Youth Camp   | YCYC.01145     | 2015-06-30T00:00:00 | THRIVE                                               |                             | MANCHESTER        | CT                 | 06042-3138       | No                      | (860) 214-8344      | Sports            | Day Camp               | Co-Ed       | 6 Years        | 12 Years       | No           | Public Water | KINETIC HOPE LLC               | 47 ROSSETTO DR                       |                   | MANCHESTER           | CT                    | 06042-1980          | (860) 214-8344      | 
| Youth Camp   | YCYC.00533     | 2015-05-31T00:00:00 | The Stanwich Club                                    | CAMP HOUSE                  | GREENWICH         | CT                 | 06831-2844       | No                      | (203) 869-0555 x236 | General           | Day Camp               | Co-Ed       | 3 Years        | 13 Years       | Yes          | Private Well | THE STANWICH CLUB INC          | 888 NORTH ST                         |                   | GREENWICH            | CT                    | 06831-2844          | (203) 869-0555 x225 | 
| Youth Camp   | YCYC.01101     | 2015-06-30T00:00:00 | TOM MOORE BASKETBALL CAMP AT QUINNIPIAC              | QUINNIPIAC UNIVERSITY       | HAMDEN            | CT                 | 06518-1905       | No                      | (203) 582-3806      | Sports            | Day Camp               | Male        | 6 Years        | 16 Years       | No           | Public Water | QUINNIPIAC UNIVERSITY          | 275 MOUNT CARMEL AVE                 |                   | HAMDEN               | CT                    | 06518-1905          | (203) 582-3806      | 
| Youth Camp   | YCYC.00443     | 2015-06-30T00:00:00 | CAMP GAN ISRAEL                                      | COLEYTOWN ELEMENTARY SCHOOL | WESTPORT          | CT                 | 06880-2217       | No                      |                     | Religious         | Day Camp               | Co-Ed       | 3 Years        | 12 Years       | No           | Public Water | Chabad Lubavitch of Westport   | 79 NEWTOWN TPKE                      |                   | WESTPORT             | CT                    | 06880-1845          | (203) 226-8584      | 
| Youth Camp   | YCYC.00862     | 2015-05-31T00:00:00 | Merrie-Wood Day Camp                                 | MERRI-WOOD PROGRAM CENTER   | MANCHESTER        | CT                 | 06040-6607       | No                      | (860) 649-4209      | General           | Day Camp               | Female      | 5 Years        | 18 Years       | No           | Private Well | GIRL SCOUTS OF CONNECTICUT INC | 340 WASHINGTON ST                    |                   | HARTFORD             | CT                    | 06106-3317          | (860) 522-0163      | 
| Youth Camp   | YCYC.00200     | 2015-06-30T00:00:00 | SUMMER AT I.D.S.                                     | INDEPENDENT DAY SCHOOL      | MIDDLEFIELD       | CT                 | 06455-1253       | No                      | (860) 347-7235      | General           | Day Camp               | Co-Ed       | 3 Years        | 15 Years       | No           | Private Well | The Independent Day School     | P. O. BOX 451, 115 LAUREL BROOK ROAD |                   | MIDDLEFIELD          | CT                    | 06455               | (860) 347-7235      | 
| Youth Camp   | YCYC.00367     | 2015-06-30T00:00:00 | LITCHFIELD JAZZ CAMP                                 | CANTERBURY SCHOOL           | NEW MILFORD       | CT                 | 06776-2825       | No                      | (860) 210-3800      | General           | Day & Residential Camp | Co-Ed       | 12 Years       | 18 Years       | Yes          | Public Water | LITCHFIELD PERFORMING ARTS INC | PO BOX 69                            |                   | LITCHFIELD           | CT                    | 06759-0069          | (860) 361-6285      | 
| Youth Camp   | YCYC.01106     | 2015-06-30T00:00:00 | EMAGINATION COMPUTER CAMPS                           | FAIRFIELD UNIVERSITY        | FAIRFIELD         | CT                 | 06824-5171       | No                      | (781) 933-8795      | General           | Day & Residential Camp | Co-Ed       | 8 Years        | 17 Years       | Yes          | Public Water | EDUCATION HOLDINGS, INC.       | 16 SETTLERS TRL                      |                   | DARIEN               | CT                    | 06820-5531          |                     | 
| Youth Camp   | YCYC.01160     | 2015-06-30T00:00:00 | COLUMBUS SCHOOL SUMMER CAMP                          | COLUMBUS MAGNET SCHOOL      | NORWALK           | CT                 | 06854-2904       | No                      | (203) 899-2840      | General           | Day Camp               | Co-Ed       | 5 Years        | 12 Years       | No           | Public Water | CARVER FOUNDATION OF NORWALK   | 7 ACADEMY ST                         |                   | NORWALK              | CT                    | 06850-4016          | (203) 838-4305      | 
| Youth Camp   | YCYC.01175     | 2015-07-31T00:00:00 | YALE - BRIDGEPORT GEAR UP RESIDENTIAL SUMMER PROGRAM | PIERSON COLLEGE             | NEW HAVEN         | CT                 | 06511-8942       | No                      | (203) 521-0246      | General           | Residential Camp       | Co-Ed       | 14 Years       | 16 Years       | Yes          | Public Water | YALE UNIVERSITY                | 389 WHITNEY AVE                      |                   | NEW HAVEN            | CT                    | 06511-2301          | (203) 789-7645      | 
```