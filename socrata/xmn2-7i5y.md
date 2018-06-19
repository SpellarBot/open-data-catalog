# Belleville Crime Blotter (updated 03.13.2013)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/belleville-crime-blotter-updated-03-13-2013-3a299) |
| Metadata | [Link](https://data.illinois.gov/api/views/xmn2-7i5y) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/xmn2-7i5y/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/xmn2-7i5y/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | xmn2-7i5y |
| Name | Belleville Crime Blotter (updated 03.13.2013) |
| Attribution | Belleville Police Department |
| Category | Public Safety |
| Tags | crime, belleville |
| Created | 2013-03-13T22:04:55Z |
| Publication Date | 2013-03-13T22:07:38Z |

## Columns

```ls
| Included | Schema Type | Field Name   | Name         | Data Type     | Render Type   |
| ======== | =========== | ============ | ============ | ============= | ============= |
| Yes      | series tag  | district     | District     | text          | text          |
| Yes      | series tag  | report       | Report #     | text          | text          |
| Yes      | series tag  | time         | Time         | text          | text          |
| Yes      | series tag  | crime        | Crime        | text          | text          |
| Yes      | series tag  | narrative    | Narrative    | text          | text          |
| Yes      | time        | blotter      | BLOTTER      | calendar_date | calendar_date |
| Yes      | series tag  | shift        | SHIFT        | text          | text          |
| No       |             | address_type | Address Type | text          | text          |
```

## Time Field

```ls
Value = blotter
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = address_type
```

## Data Commands

```ls
series e:xmn2-7i5y d:2012-12-10T00:00:00.000Z t:time="(0754 Hrs)" t:narrative="The victim (B/M/36) reported unknown person(s) stole property from his yard." t:crime="THEFT UNDER $500" t:report=12-11094 t:district="DISTRICT 4" t:shift="0600 - 1800" m:row_number.xmn2-7i5y=1

series e:xmn2-7i5y d:2012-12-10T00:00:00.000Z t:time="(1130 Hrs)" t:narrative="The victim (W/F/19) reported unknown suspect burglarized her vehicle by smashing her front and rear windows out of her car.  Property was stolen from the vehicle." t:crime="BURGLARY TO VEHICLE" t:report=12-11100 t:district="DISTRICT 3" t:shift="0600 - 1800" m:row_number.xmn2-7i5y=2

series e:xmn2-7i5y d:2012-12-10T00:00:00.000Z t:time="(1234 Hrs)" t:narrative="The victim (W/F/21) reported sometime between 1020-1210 hours, unknown suspect gained entry into her trunk while it was parked on the lot.  No property was reported missing." t:crime="BURGLARY TO VEHICLE" t:report=12-11102 t:district="DISTRICT 4" t:shift="0600 - 1800" m:row_number.xmn2-7i5y=3
```

## Meta Commands

```ls
metric m:row_number.xmn2-7i5y p:long l:"Row Number"

entity e:xmn2-7i5y l:"Belleville Crime Blotter (updated 03.13.2013)" t:attribution="Belleville Police Department" t:url=https://data.illinois.gov/api/views/xmn2-7i5y

property e:xmn2-7i5y t:meta.view v:id=xmn2-7i5y v:category="Public Safety" v:averageRating=0 v:name="Belleville Crime Blotter (updated 03.13.2013)" v:attribution="Belleville Police Department"

property e:xmn2-7i5y t:meta.view.license v:name="Public Domain"

property e:xmn2-7i5y t:meta.view.owner v:id=h3c8-jee5 v:screenName=Alya v:displayName=Alya

property e:xmn2-7i5y t:meta.view.tableauthor v:id=h3c8-jee5 v:screenName=Alya v:displayName=Alya
```

## Top Records

```ls
| district   | report   | time       | crime                                   | narrative                                                                                                                                                                                        | blotter             | shift       | address_type | 
| ========== | ======== | ========== | ======================================= | ================================================================================================================================================================================================ | =================== | =========== | ============ | 
| DISTRICT 4 | 12-11094 | (0754 Hrs) | THEFT UNDER $500                        | The victim (B/M/36) reported unknown person(s) stole property from his yard.                                                                                                                     | 2012-12-10T00:00:00 | 0600 - 1800 |              | 
| DISTRICT 3 | 12-11100 | (1130 Hrs) | BURGLARY TO VEHICLE                     | The victim (W/F/19) reported unknown suspect burglarized her vehicle by smashing her front and rear windows out of her car. Property was stolen from the vehicle.                                | 2012-12-10T00:00:00 | 0600 - 1800 |              | 
| DISTRICT 4 | 12-11102 | (1234 Hrs) | BURGLARY TO VEHICLE                     | The victim (W/F/21) reported sometime between 1020-1210 hours, unknown suspect gained entry into her trunk while it was parked on the lot. No property was reported missing.                     | 2012-12-10T00:00:00 | 0600 - 1800 |              | 
| DISTRICT 1 | 12-11104 | (1345 Hrs) | RESIDENTIAL BURGLARY                    | The victim (W/M/64) reported between 1100-1338 hours, unknown suspect(s) burglarized his residence. The suspect(s) rummaged through the residence and property was stolen, along with a handgun. | 2012-12-10T00:00:00 | 0600 - 1800 |              | 
| DISTRICT 6 | 12-11036 | (1630 Hrs) | SUPPLEMENTAL-RECOVERY OF STOLEN VEHICLE | Officers located a 2002 Dodge Caravan that had previously been reported stolen from Suburban Motors.                                                                                             | 2012-12-10T00:00:00 | 0600 - 1800 |              | 
| DISTRICT 4 | 12-11094 | (0754 Hrs) | THEFT UNDER $500                        | The victim (B/M/36) reported unknown person(s) stole property from his yard.                                                                                                                     | 2012-12-10T00:00:00 | 0600 - 1800 |              | 
| DISTRICT 3 | 12-11100 | (1130 Hrs) | BURGLARY TO VEHICLE                     | The victim (W/F/19) reported unknown suspect burglarized her vehicle by smashing her front and rear windows out of her car. Property was stolen from the vehicle.                                | 2012-12-10T00:00:00 | 0600 - 1800 |              | 
| DISTRICT 4 | 12-11102 | (1234 Hrs) | BURGLARY TO VEHICLE                     | The victim (W/F/21) reported sometime between 1020-1210 hours, unknown suspect gained entry into her trunk while it was parked on the lot. No property was reported missing.                     | 2012-12-10T00:00:00 | 0600 - 1800 |              | 
| DISTRICT 1 | 12-11104 | (1345 Hrs) | RESIDENTIAL BURGLARY                    | The victim (W/M/64) reported between 1100-1338 hours, unknown suspect(s) burglarized his residence. The suspect(s) rummaged through the residence and property was stolen, along with a handgun. | 2012-12-10T00:00:00 | 0600 - 1800 |              | 
| DISTRICT 6 | 12-11036 | (1630 Hrs) | SUPPLEMENTAL-RECOVERY OF STOLEN VEHICLE | Officers located a 2002 Dodge Caravan that had previously been reported stolen from Suburban Motors.                                                                                             | 2012-12-10T00:00:00 | 0600 - 1800 |              | 
```