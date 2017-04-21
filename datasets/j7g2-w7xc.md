# ATR Continuous Count Sites

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/atr-continuous-count-sites) |
| Metadata | [Link](https://data.iowa.gov/api/views/j7g2-w7xc) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/j7g2-w7xc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/j7g2-w7xc/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | j7g2-w7xc |
| Name | ATR Continuous Count Sites |
| Attribution | Iowa Department of Transportation - Office Of Systems Planning |
| Category | Transportation & Utilities |
| Tags | asset, inventory, traffic, atr, traffic counter, traffic recorder, iowa dot, iowa department of transportation |
| Created | 2016-06-08T21:06:30Z |
| Publication Date | 2016-06-08T21:07:47Z |

## Description

This REST service depicts the continuous count Automatic Traffic Recorder (ATR) location sites in the state of Iowa.

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                 | Data Type | Render Type |
| ======== | ============== | ==================== | ==================== | ========= | =========== |
| Yes      | series tag     | aadt_convfactor_type | AADT_CONVFACTOR_TYPE | text      | text        |
| Yes      | series tag     | atr_number           | ATR_NUMBER           | text      | text        |
| Yes      | series tag     | axle_factor          | AXLE_FACTOR          | text      | text        |
| Yes      | series tag     | county_fips          | COUNTY_FIPS          | text      | number      |
| Yes      | series tag     | county_name          | COUNTY_NAME          | text      | text        |
| Yes      | numeric metric | continuous           | CONTINUOUS           | number    | number      |
| Yes      | series tag     | daily_factor         | DAILY_FACTOR         | text      | text        |
| Yes      | series tag     | daily_factor_type    | DAILY_FACTOR_TYPE    | text      | text        |
| Yes      | series tag     | func_class_name      | FUNC_CLASS_NAME      | text      | text        |
| Yes      | series tag     | func_class_num       | FUNC_CLASS_NUM       | text      | number      |
| Yes      | series tag     | gps                  | GPS                  | text      | text        |
| No       |                | gps_latitude         | GPS_LATITUDE         | number    | text        |
| No       |                | gps_longitude        | GPS_LONGITUDE        | number    | text        |
| Yes      | series tag     | growth_factor        | GROWTH_FACTOR        | text      | text        |
| No       |                | latitude             | LATITUDE             | number    | number      |
| Yes      | series tag     | loctext              | LOCTEXT              | text      | text        |
| No       |                | longitude            | LONGITUDE            | number    | number      |
| Yes      | series tag     | name                 | NAME                 | text      | text        |
| Yes      | series tag     | negalias             | NEGALIAS             | text      | text        |
| Yes      | series tag     | negcompass           | NEGCOMPASS           | text      | text        |
| Yes      | numeric metric | pdirdir              | PDIRDIR              | number    | number      |
| Yes      | series tag     | posalias             | POSALIAS             | text      | text        |
| Yes      | series tag     | poscompass           | POSCOMPASS           | text      | text        |
| Yes      | series tag     | seasonal_factor      | SEASONAL_FACTOR      | text      | text        |
| Yes      | series tag     | seasonal_factor_type | SEASONAL_FACTOR_TYPE | text      | text        |
| Yes      | series tag     | sitefedid            | SITEFEDID            | text      | number      |
| Yes      | numeric metric | speed_limit          | SPEED_LIMIT          | number    | number      |
| Yes      | time           | status_effdttm       | STATUS_EFFDTTM       | date      | date        |
| No       |                | status_expdttm       | STATUS_EXPDTTM       | date      | date        |
| Yes      | series tag     | urban_rural          | URBAN_RURAL          | text      | text        |
| Yes      | series tag     | objectid             | OBJECTID             | text      | number      |
```

## Time Field

```ls
Value = status_effdttm
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = gps_latitude,gps_longitude,latitude,longitude,status_expdttm
```

## Data Commands

```ls
series e:j7g2-w7xc d:2016-02-11T14:37:05.000Z t:aadt_convfactor_type="Rural Interstate" t:seasonal_factor_type="Rural Interstate" t:daily_factor="Rural Interstate" t:urban_rural=R t:func_class_num=1 t:growth_factor="Rural Interstate" t:sitefedid=720 t:atr_number=100 t:seasonal_factor="Rural Interstate" t:county_fips=155 t:axle_factor="Rural Interstate" t:negalias=Neg t:func_class_name="Rural Principal Arterial - Interstate" t:name="ATR Number" t:loctext="I 29 2.0 MI N OF S JCT I 680 @MP# 64 HONEY CREEK" t:gps="GPS Location" t:daily_factor_type="Rural Interstate" t:objectid=1 t:negcompass=South t:county_name=Pottawattamie t:posalias=Pos t:poscompass=North m:continuous=1 m:speed_limit=70 m:pdirdir=1

series e:j7g2-w7xc d:2014-10-23T09:09:57.000Z t:aadt_convfactor_type="Rural Interstate" t:seasonal_factor_type="Rural Interstate" t:daily_factor="Rural Interstate" t:urban_rural=R t:func_class_num=1 t:growth_factor="Rural Interstate" t:sitefedid=723 t:atr_number=102 t:seasonal_factor="Rural Interstate" t:county_fips=129 t:axle_factor="Rural Interstate" t:negalias=Neg t:func_class_name="Rural Principal Arterial - Interstate" t:name="ATR Number" t:loctext="I 29 7.0 MI S OF US 34 PACIFIC JCT" t:gps="GPS Location" t:daily_factor_type="Rural Interstate" t:objectid=2 t:negcompass=South t:county_name=Mills t:posalias=Pos t:poscompass=North m:continuous=1 m:speed_limit=70 m:pdirdir=1

series e:j7g2-w7xc d:2012-04-25T12:40:04.000Z t:aadt_convfactor_type="Rural Interstate" t:seasonal_factor_type="Rural Interstate" t:daily_factor="Rural Interstate" t:urban_rural=R t:func_class_num=1 t:growth_factor="Rural Interstate" t:sitefedid=725 t:atr_number=103 t:seasonal_factor="Rural Interstate" t:county_fips=157 t:axle_factor="Rural Interstate" t:negalias=Neg t:func_class_name="Rural Principal Arterial - Interstate" t:name="ATR Number" t:loctext="I 80 1.0 MI W OF US 63 GRINNELL" t:gps="GPS Location" t:daily_factor_type="Rural Interstate" t:objectid=3 t:negcompass=West t:county_name=Poweshiek t:posalias=Pos t:poscompass=East m:continuous=1 m:speed_limit=70 m:pdirdir=3
```

## Meta Commands

```ls
metric m:continuous p:integer l:CONTINUOUS d:Countinuous? t:dataTypeName=number

metric m:pdirdir p:integer l:PDIRDIR d:"PDIR Direction" t:dataTypeName=number

metric m:speed_limit p:integer l:SPEED_LIMIT d:"Speed Limit (MPH)" t:dataTypeName=number

entity e:j7g2-w7xc l:"ATR Continuous Count Sites" t:attribution="Iowa Department of Transportation - Office Of Systems Planning" t:url=https://data.iowa.gov/api/views/j7g2-w7xc

property e:j7g2-w7xc t:meta.view v:id=j7g2-w7xc v:category="Transportation & Utilities" v:attributionLink=https://gis.iowadot.gov/public/rest/services/Traffic/ATR_Locations/MapServer/0 v:averageRating=0 v:name="ATR Continuous Count Sites" v:attribution="Iowa Department of Transportation - Office Of Systems Planning"

property e:j7g2-w7xc t:meta.view.owner v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:displayName="Iowa Department of Transportation"

property e:j7g2-w7xc t:meta.view.tableauthor v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:roleName=administrator v:displayName="Iowa Department of Transportation"
```

## Top Records

```ls
| aadt_convfactor_type | atr_number | axle_factor      | county_fips | county_name   | continuous | daily_factor     | daily_factor_type | func_class_name                       | func_class_num | gps          | gps_latitude | gps_longitude | growth_factor    | latitude                                           | loctext                                          | longitude                                          | name       | negalias | negcompass | pdirdir | posalias | poscompass | seasonal_factor  | seasonal_factor_type | sitefedid | speed_limit | status_effdttm | status_expdttm | urban_rural | objectid | 
| ==================== | ========== | ================ | =========== | ============= | ========== | ================ | ================= | ===================================== | ============== | ============ | ============ | ============= | ================ | ================================================== | ================================================ | ================================================== | ========== | ======== | ========== | ======= | ======== | ========== | ================ | ==================== | ========= | =========== | ============== | ============== | =========== | ======== | 
| Rural Interstate     | 100        | Rural Interstate | 155         | Pottawattamie | 1          | Rural Interstate | Rural Interstate  | Rural Principal Arterial - Interstate | 1              | GPS Location | 41.3836      | -95.8994      | Rural Interstate | 41.2300000000000039790393202565610408782958984375  | I 29 2.0 MI N OF S JCT I 680 @MP# 64 HONEY CREEK | -95.5357000000000056161297834478318691253662109375 | ATR Number | Neg      | South      | 1       | Pos      | North      | Rural Interstate | Rural Interstate     | 720       | 70          | 1455201425     | 64092124800    | R           | 1        | 
| Rural Interstate     | 102        | Rural Interstate | 129         | Mills         | 1          | Rural Interstate | Rural Interstate  | Rural Principal Arterial - Interstate | 1              | GPS Location | 40.9458      | -95.8006      | Rural Interstate | 40.94579999999999841975295566953718662261962890625 | I 29 7.0 MI S OF US 34 PACIFIC JCT               | -95.800600000000002864908310584723949432373046875  | ATR Number | Neg      | South      | 1       | Pos      | North      | Rural Interstate | Rural Interstate     | 723       | 70          | 1414055397     | 64092124800    | R           | 2        | 
| Rural Interstate     | 103        | Rural Interstate | 157         | Poweshiek     | 1          | Rural Interstate | Rural Interstate  | Rural Principal Arterial - Interstate | 1              | GPS Location | 41.6958      | -92.5783      | Rural Interstate | 41.6958000000000055251803132705390453338623046875  | I 80 1.0 MI W OF US 63 GRINNELL                  | -92.5782999999999987039700499735772609710693359375 | ATR Number | Neg      | West       | 3       | Pos      | East       | Rural Interstate | Rural Interstate     | 725       | 70          | 1335357604     | 64092124800    | R           | 3        | 
| Rural Interstate     | 104        | Rural Interstate | 79          | Hamilton      | 1          | Rural Interstate | Rural Interstate  | Rural Principal Arterial - Interstate | 1              | GPS Location | 42.3539      | -93.5706      | Rural Interstate | 42.35390000000000298996383207850158214569091796875 | I 35 3.0 MI N OF IA 175 JEWELL                   | -93.5705999999999988858689903281629085540771484375 | ATR Number | Neg      | South      | 1       | Pos      | North      | Rural Interstate | Rural Interstate     | 727       | 70          | 1167149243     | 64092124800    | R           | 4        | 
| Rural Interstate     | 105        | Rural Interstate | 133         | Monona        | 1          | Rural Interstate | Rural Interstate  | Rural Principal Arterial - Interstate | 1              | GPS Location | 41.9792      | -96.1047      | Rural Interstate | 41.97919999999999873807610129006206989288330078125 | I 29 3.8 MI S OF IA 175 ONAWA                    | -96.104700000000008230927051045000553131103515625  | ATR Number | Neg      | South      | 1       | Pos      | North      | Rural Interstate | Rural Interstate     | 728       | 70          | 1233321601     | 64092124800    | R           | 5        | 
| Rural Interstate     | 106        | Rural Interstate | 53          | Decatur       | 1          | Rural Interstate | Rural Interstate  | Rural Principal Arterial - Interstate | 1              | GPS Location | 40.7472      | -93.8402      | Rural Interstate | 40.75720000000000453610482509247958660125732421875 | I 35 0.6 MI N OF IA 2 LEON                       | -93.8368999999999999772626324556767940521240234375 | ATR Number | Neg      | South      | 1       | Pos      | North      | Rural Interstate | Rural Interstate     | 729       | 70          | 1448015482     | 64092124800    | R           | 6        | 
| Rural Interstate     | 109        | Rural Interstate | 33          | Cerro Gordo   | 1          | Rural Interstate | Rural Interstate  | Rural Principal Arterial - Interstate | 1              | GPS Location | 43.2422      | -93.3489      | Rural Interstate | 43.24220000000000396767063648439943790435791015625 | I 35 3.0 MI N OF CO B20 HANLONTOWN               | -93.3489000000000004320099833421409130096435546875 | ATR Number | Neg      | South      | 1       | Pos      | North      | Rural Interstate | Rural Interstate     | 730       | 70          | 1270629559     | 64092124800    | R           | 7        | 
| Rural Interstate     | 110        | Rural Interstate | 165         | Shelby        | 1          | Rural Interstate | Rural Interstate  | Rural Principal Arterial - Interstate | 1              | GPS Location | 41.4986      | -95.4792      | Rural Interstate | 41.49860000000000326281224261038005352020263671875 | I 80 1.5 MI W OF CO M16 SHELBY                   | -95.4792000000000058435034588910639286041259765625 | ATR Number | Neg      | West       | 3       | Pos      | East       | Rural Interstate | Rural Interstate     | 749       | 70          | 1167149324     | 64092124800    | R           | 8        | 
| Rural Interstate     | 111        | Rural Interstate | 95          | Iowa          | 1          | Rural Interstate | Rural Interstate  | Rural Principal Arterial - Interstate | 1              | GPS Location | 41.6867      | -91.9681      | Rural Interstate | 41.686700000000001864464138634502887725830078125   | I 80 2.0 MI E OF IA 149 WILLIAMSBURG             | -91.9681000000000068439476308412849903106689453125 | ATR Number | Neg      | West       | 3       | Pos      | East       | Rural Interstate | Rural Interstate     | 750       | 70          | 1404215765     | 64092124800    | R           | 9        | 
| Rural Interstate     | 113        | Rural Interstate | 11          | Benton        | 1          | Rural Interstate | Rural Interstate  | Rural Principal Arterial - Interstate | 1              | GPS Location | 42.2606      | -91.91        | Rural Interstate | 42.26060000000000371755959349684417247772216796875 | I 380 1.5 MI N OF IA 150 BRANDON                 | -91.909999999999996589394868351519107818603515625  | ATR Number | Neg      | South      | 1       | Pos      | North      | Rural Interstate | Rural Interstate     | 751       | 70          | 1455201453     | 64092124800    | R           | 10       | 
```