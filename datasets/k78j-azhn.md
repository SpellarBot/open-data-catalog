# DOT Towing

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dot-towing) |
| Metadata | [Link](https://data.baltimorecity.gov/api/views/k78j-azhn) |
| Data: JSON | [100 Rows](https://data.baltimorecity.gov/api/views/k78j-azhn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.baltimorecity.gov/api/views/k78j-azhn/rows.csv?max_rows=100) |
| Host | data.baltimorecity.gov |
| Id | k78j-azhn |
| Name | DOT Towing |
| Attribution | Department of Transportation |
| Category | Transportation |
| Tags | transportation, towing, tow |
| Created | 2012-10-22T16:27:49Z |
| Publication Date | 2017-01-07T18:31:05Z |

## Description

Cars that are towed within city limits are taken to either the Main Impound Storage Facility located at 6700 Pulaski Highway, or a smaller holding facility at 410 Fallsway. The majority of abandoned vehicles, scofflaw vehicles and cars that are towed as a result of an accident or police activity are taken to the Main Impound Storage Facility. Vehicles that are illegally parked along major city gateways during peak hours (rush hour) are placed at the Fallsway lot for up to 48 hours. If the vehicle is not retrieved from the facility within 48 hours, it is then moved to the Pulaski Highway lot where storage fees may be assessed. Vehicles remaining at the Fallsway facility by the close of business each Friday will also be moved to Pulaski Highway.

## Columns

```ls
| Included | Schema Type    | Field Name                | Name                      | Data Type     | Render Type   |
| ======== | ============== | ========================= | ========================= | ============= | ============= |
| Yes      | series tag     | propertynumber            | propertynumber            | text          | text          |
| No       |                | toweddatetime             | towedDateTime             | calendar_date | calendar_date |
| Yes      | series tag     | vehicletype               | vehicleType               | text          | text          |
| Yes      | series tag     | vehicleyear               | vehicleYear               | text          | text          |
| Yes      | series tag     | vehiclemake               | vehicleMake               | text          | text          |
| Yes      | series tag     | vehiclemodel              | vehicleModel              | text          | text          |
| Yes      | series tag     | vehiclecolor              | vehicleColor              | text          | text          |
| Yes      | series tag     | tagnumber                 | tagNumber                 | text          | text          |
| Yes      | series tag     | towcompany                | towCompany                | text          | text          |
| Yes      | numeric metric | towcharge                 | towCharge                 | money         | money         |
| Yes      | series tag     | towedfromlocation         | towedFromLocation         | text          | text          |
| Yes      | series tag     | howtowed                  | howTowed                  | text          | text          |
| Yes      | series tag     | slingused                 | slingUsed                 | text          | text          |
| Yes      | series tag     | dollyused                 | dollyUsed                 | text          | text          |
| Yes      | series tag     | rollbackused              | rollBackUsed              | text          | text          |
| Yes      | series tag     | pinpulled                 | pinPulled                 | text          | text          |
| Yes      | series tag     | pinreplaced               | pinReplaced               | text          | text          |
| Yes      | series tag     | wheellift                 | wheelLift                 | text          | text          |
| Yes      | series tag     | stinger                   | stinger                   | text          | text          |
| Yes      | time           | receivingdatetime         | receivingDateTime         | calendar_date | calendar_date |
| Yes      | series tag     | storageyard               | storageYard               | text          | text          |
| Yes      | series tag     | storagelocation           | storageLocation           | text          | text          |
| Yes      | series tag     | storagetelephone          | storageTelephone          | text          | text          |
| Yes      | numeric metric | titlerenounciation        | titleRenounciation        | number        | text          |
| No       |                | trdatetime                | trDateTime                | calendar_date | calendar_date |
| Yes      | series tag     | personalpropremoved       | personalPropRemoved       | text          | text          |
| Yes      | series tag     | personalpropleftinvehicle | personalPropLeftInVehicle | text          | text          |
| No       |                | holddatetime              | holdDateTime              | calendar_date | calendar_date |
| No       |                | holdreleaseddatetime      | holdReleasedDateTime      | calendar_date | calendar_date |
| No       |                | holdreleasednotifydate    | holdReleasedNotifyDate    | calendar_date | calendar_date |
| No       |                | removedfromyarddate       | removedFromYardDate       | calendar_date | calendar_date |
| Yes      | numeric metric | stolenvehicleflag         | stolenVehicleFlag         | number        | text          |
| Yes      | series tag     | status                    | status                    | text          | text          |
| No       |                | releasedatetime           | releaseDateTime           | calendar_date | calendar_date |
| Yes      | series tag     | releasetype               | releaseType               | text          | text          |
| Yes      | numeric metric | totalpaid                 | totalPaid                 | money         | money         |
```

## Time Field

```ls
Value = receivingdatetime
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = toweddatetime,trdatetime,holddatetime,holdreleaseddatetime,holdreleasednotifydate,removedfromyarddate,releasedatetime
```

## Data Commands

```ls
series e:k78j-azhn d:2010-10-24T12:41:00.000Z t:towcompany=City t:tagnumber=9GAA97 t:storagetelephone="(410) 396-4639" t:storageyard="Fallsway Impound Lot" t:slingused=No t:towedfromlocation="U/B W HUGHES ST." t:vehicletype=Van t:rollbackused=No t:releasetype="Release to Owner" t:propertynumber=F011135 t:wheellift=No t:vehiclemake=LEXUS t:storagelocation="410 Fallsway Baltimore, Maryland 21202" t:howtowed=Partial/Multiple m:towcharge=130 m:totalpaid=322

series e:k78j-azhn d:2012-10-29T13:39:00.000Z t:vehiclemodel=Sebring t:vehiclecolor=Red t:towcompany=City t:tagnumber=8AF1522 t:status=Auctioned t:pinreplaced=No t:dollyused=No t:storagetelephone="(410) 396-9958" t:slingused=No t:storageyard=Pulaski t:towedfromlocation="800 E 25th St" t:vehicleyear=01 t:vehicletype=Car t:releasetype=Auctioned t:rollbackused=Yes t:propertynumber=P246906 t:wheellift=No t:vehiclemake=Chrysler t:stinger=No t:storagelocation="6700 Pulaski Highway Baltimore, Maryland 21237" t:howtowed=Front t:pinpulled=No m:towcharge=130 m:titlerenounciation=0 m:totalpaid=0 m:stolenvehicleflag=0

series e:k78j-azhn d:2012-06-20T10:14:00.000Z t:vehiclemodel="Haul Rite" t:vehiclecolor=Silver t:towcompany=City t:pinreplaced=No t:storagetelephone="(410) 396-9958" t:dollyused=No t:slingused=No t:storageyard=Pulaski t:towedfromlocation="600  Baltic Ave" t:vehicleyear=91 t:vehicletype=Trailer t:rollbackused=No t:propertynumber=P239381 t:wheellift=Yes t:vehiclemake=B/M t:stinger=No t:storagelocation="6700 Pulaski Highway Baltimore, Maryland 21237" t:howtowed=Front t:pinpulled=No m:towcharge=140 m:titlerenounciation=0 m:totalpaid=0 m:stolenvehicleflag=0
```

## Meta Commands

```ls
metric m:towcharge p:double l:towCharge t:dataTypeName=money

metric m:titlerenounciation p:integer l:titleRenounciation t:dataTypeName=number

metric m:stolenvehicleflag p:integer l:stolenVehicleFlag t:dataTypeName=number

metric m:totalpaid p:double l:totalPaid t:dataTypeName=money

entity e:k78j-azhn l:"DOT Towing" t:attribution="Department of Transportation" t:url=https://data.baltimorecity.gov/api/views/k78j-azhn

property e:k78j-azhn t:meta.view v:id=k78j-azhn v:category=Transportation v:attributionLink=http://www.baltimorecity.gov/Government/AgenciesDepartments/Transportation.aspx v:averageRating=0 v:name="DOT Towing" v:attribution="Department of Transportation"

property e:k78j-azhn t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:k78j-azhn t:meta.view.owner v:id=6r9a-dfdj v:screenName="Open Baltimore" v:displayName="Open Baltimore"

property e:k78j-azhn t:meta.view.tableauthor v:id=6r9a-dfdj v:screenName="Open Baltimore" v:roleName=administrator v:displayName="Open Baltimore"
```

## Top Records

```ls
| propertynumber | toweddatetime       | vehicletype | vehicleyear | vehiclemake | vehiclemodel | vehiclecolor | tagnumber | towcompany                 | towcharge | towedfromlocation | howtowed         | slingused | dollyused | rollbackused | pinpulled | pinreplaced | wheellift | stinger | receivingdatetime   | storageyard          | storagelocation                                | storagetelephone | titlerenounciation | trdatetime | personalpropremoved | personalpropleftinvehicle | holddatetime | holdreleaseddatetime | holdreleasednotifydate | removedfromyarddate | stolenvehicleflag | status    | releasedatetime     | releasetype      | totalpaid | 
| ============== | =================== | =========== | =========== | =========== | ============ | ============ | ========= | ========================== | ========= | ================= | ================ | ========= | ========= | ============ | ========= | =========== | ========= | ======= | =================== | ==================== | ============================================== | ================ | ================== | ========== | =================== | ========================= | ============ | ==================== | ====================== | =================== | ================= | ========= | =================== | ================ | ========= | 
| F011135        | 2010-10-24T12:38:00 | Van         |             | LEXUS       |              |              | 9GAA97    | City                       | 130.00    | U/B W HUGHES ST.  | Partial/Multiple | No        |           | No           |           |             | No        |         | 2010-10-24T12:41:00 | Fallsway Impound Lot | 410 Fallsway Baltimore, Maryland 21202         | (410) 396-4639   |                    |            |                     |                           |              |                      |                        |                     |                   |           | 2010-10-24T15:23:00 | Release to Owner | 322.00    | 
| P246906        | 2012-10-29T13:39:00 | Car         | 01          | Chrysler    | Sebring      | Red          | 8AF1522   | City                       | 130.00    | 800 E 25th St     | Front            | No        | No        | Yes          | No        | No          | No        | No      | 2012-10-29T13:39:00 | Pulaski              | 6700 Pulaski Highway Baltimore, Maryland 21237 | (410) 396-9958   | 0                  |            |                     |                           |              |                      |                        | 2013-01-23T00:00:00 | 0                 | Auctioned | 2013-01-23T08:00:00 | Auctioned        | 0.00      | 
| P239381        | 2012-06-20T10:14:00 | Trailer     | 91          | B/M         | Haul Rite    | Silver       |           | City                       | 140.00    | 600 Baltic Ave    | Front            | No        | No        | No           | No        | No          | Yes       | No      | 2012-06-20T10:14:00 | Pulaski              | 6700 Pulaski Highway Baltimore, Maryland 21237 | (410) 396-9958   | 0                  |            |                     |                           |              |                      |                        |                     | 0                 |           |                     |                  | 0.00      | 
| P282221        |                     | Car         | 03          | Honda       | Civic        | Silver       | 6BN7039   |                            | 0.00      | 0                 |                  | No        | No        | No           | No        | No          | No        | No      | 2014-08-18T04:44:45 | Pulaski              | 6700 Pulaski Highway Baltimore, Maryland 21237 | (410) 396-9958   | 0                  |            |                     |                           |              |                      |                        |                     |                   |           |                     |                  |           | 
| P239380        | 2012-06-20T10:13:00 | Boat        | 73          | Unknown     |              | Red/White    | MD1978W   | City                       | 140.00    | 600 Baltic Ave    | Front            | No        | No        | No           | No        | No          | Yes       | No      | 2012-06-20T10:13:00 | Pulaski              | 6700 Pulaski Highway Baltimore, Maryland 21237 | (410) 396-9958   | 0                  |            |                     |                           |              |                      |                        |                     | 0                 |           |                     |                  | 0.00      | 
| F103976        | 2011-05-03T07:41:00 |             |             | FORD        | EXPLORER     |              | 76WV90    | Frankford Towing           | 140.00    | 4566 N CHARLES ST | Partial/Multiple | No        |           | No           |           |             | No        |         | 2011-05-03T08:11:00 | Fallsway Impound Lot | 410 Fallsway Baltimore, Maryland 21202         | (410) 396-4639   |                    |            |                     |                           |              |                      |                        |                     |                   |           | 2011-05-03T17:03:00 | Release to Owner | 282.00    | 
| F103975        | 2011-05-03T07:46:00 |             | 01          | TOYOTA      | COROLLA      |              | KYA390    | Aarons Automotive Services | 140.00    | 4565 N CHARLES ST | Partial/Multiple | No        |           | No           |           |             | No        |         | 2011-05-03T08:11:00 | Fallsway Impound Lot | 410 Fallsway Baltimore, Maryland 21202         | (410) 396-4639   |                    |            |                     |                           |              |                      |                        |                     |                   |           | 2011-05-04T14:02:00 | Release to Owner | 282.00    | 
| F406427        | 2014-07-12T17:07:00 | Van         |             | DODGE       |              |              | 6BG7516   | City                       | 130.00    | 500 SCOTT ST      | Front            | No        |           | No           |           |             | Yes       |         | 2014-07-12T17:16:00 | Fallsway Impound Lot | 410 Fallsway Baltimore, Maryland 21202         | (410) 396-4639   |                    |            |                     |                           |              |                      |                        |                     |                   |           |                     |                  | 0.00      | 
| F500199        | 2015-01-09T17:25:00 |             |             | 1           |              |              |           |                            | 130.00    |                   | Partial/Multiple | No        |           | No           |           |             | No        |         | 2015-01-09T17:25:00 | Fallsway Impound Lot | 410 Fallsway Baltimore, Maryland 21202         | (410) 396-4639   |                    |            |                     |                           |              |                      |                        |                     |                   |           |                     |                  | 0.00      | 
| F104079        | 2011-05-05T09:25:00 |             |             | VOLKSWAGEN  |              |              | 1CCX78    | City                       | 130.00    | 500 S LUZERNE AVE | Partial/Multiple | No        |           | No           |           |             | No        |         | 2011-05-05T09:37:00 | Fallsway Impound Lot | 410 Fallsway Baltimore, Maryland 21202         | (410) 396-4639   |                    |            |                     |                           |              |                      |                        |                     |                   |           | 2011-05-05T11:08:00 | Release to Owner | 272.00    | 
```