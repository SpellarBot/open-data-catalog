# Belleville Spotcrime 2010-2013 REPORTS

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/belleville-spotcrime-2010-2013-reports-f1dcc) |
| Metadata | [Link](https://data.illinois.gov/api/views/a2nx-jhgj) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/a2nx-jhgj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/a2nx-jhgj/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | a2nx-jhgj |
| Name | Belleville Spotcrime 2010-2013 REPORTS |
| Attribution | Belleville Police Department & SpotCrime |
| Created | 2013-03-05T19:10:43Z |
| Publication Date | 2013-03-06T19:11:14Z |

## Columns

```ls
| Included | Schema Type | Field Name | Name      | Data Type     | Render Type   |
| ======== | =========== | ========== | ========= | ============= | ============= |
| Yes      | series tag  | district   | District  | text          | text          |
| Yes      | series tag  | report     | Report #  | text          | text          |
| Yes      | series tag  | time       | Time      | text          | text          |
| Yes      | series tag  | crime      | Crime     | text          | text          |
| Yes      | series tag  | narrative  | Narrative | text          | text          |
| Yes      | time        | blotter    | BLOTTER   | calendar_date | calendar_date |
| Yes      | series tag  | shift      | SHIFT     | text          | text          |
| Yes      | series tag  | previous   | PREVIOUS  | text          | text          |
```

## Time Field

```ls
Value = blotter
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:a2nx-jhgj d:2012-12-10T00:00:00.000Z t:time="(0754 Hrs)" t:narrative="The victim (B/M/36) reported unknown person(s) stole property from his yard." t:crime="THEFT UNDER $500" t:report=12-11094 t:district="DISTRICT 4" t:shift="0600 - 1800" m:row_number.a2nx-jhgj=1

series e:a2nx-jhgj d:2012-12-10T00:00:00.000Z t:time="(1130 Hrs)" t:narrative="The victim (W/F/19) reported unknown suspect burglarized her vehicle by smashing her front and rear windows out of her car.  Property was stolen from the vehicle." t:crime="BURGLARY TO VEHICLE" t:report=12-11100 t:district="DISTRICT 3" t:shift="0600 - 1800" m:row_number.a2nx-jhgj=2

series e:a2nx-jhgj d:2012-12-10T00:00:00.000Z t:time="(1234 Hrs)" t:narrative="The victim (W/F/21) reported sometime between 1020-1210 hours, unknown suspect gained entry into her trunk while it was parked on the lot.  No property was reported missing." t:crime="BURGLARY TO VEHICLE" t:report=12-11102 t:district="DISTRICT 4" t:shift="0600 - 1800" m:row_number.a2nx-jhgj=3
```

## Meta Commands

```ls
metric m:row_number.a2nx-jhgj p:long l:"Row Number"

entity e:a2nx-jhgj l:"Belleville Spotcrime 2010-2013 REPORTS" t:attribution="Belleville Police Department & SpotCrime" t:url=https://data.illinois.gov/api/views/a2nx-jhgj

property e:a2nx-jhgj t:meta.view v:id=a2nx-jhgj v:attributionLink=http://www.spotcrime.com v:averageRating=0 v:name="Belleville Spotcrime 2010-2013 REPORTS" v:attribution="Belleville Police Department & SpotCrime"

property e:a2nx-jhgj t:meta.view.owner v:id=6f5e-eqp6 v:screenName="Rich Peppers" v:displayName="Rich Peppers"

property e:a2nx-jhgj t:meta.view.tableauthor v:id=6f5e-eqp6 v:screenName="Rich Peppers" v:roleName=publisher v:displayName="Rich Peppers"
```

## Top Records

```ls
| district                          | report   | time       | crime                                   | narrative                                                                                                                                                                                        | blotter             | shift       | previous | 
| ================================= | ======== | ========== | ======================================= | ================================================================================================================================================================================================ | =================== | =========== | ======== | 
| DISTRICT 4                        | 12-11094 | (0754 Hrs) | THEFT UNDER $500                        | The victim (B/M/36) reported unknown person(s) stole property from his yard.                                                                                                                     | 2012-12-10T00:00:00 | 0600 - 1800 |          | 
| DISTRICT 3                        | 12-11100 | (1130 Hrs) | BURGLARY TO VEHICLE                     | The victim (W/F/19) reported unknown suspect burglarized her vehicle by smashing her front and rear windows out of her car. Property was stolen from the vehicle.                                | 2012-12-10T00:00:00 | 0600 - 1800 |          | 
| DISTRICT 4                        | 12-11102 | (1234 Hrs) | BURGLARY TO VEHICLE                     | The victim (W/F/21) reported sometime between 1020-1210 hours, unknown suspect gained entry into her trunk while it was parked on the lot. No property was reported missing.                     | 2012-12-10T00:00:00 | 0600 - 1800 |          | 
| DISTRICT 1                        | 12-11104 | (1345 Hrs) | RESIDENTIAL BURGLARY                    | The victim (W/M/64) reported between 1100-1338 hours, unknown suspect(s) burglarized his residence. The suspect(s) rummaged through the residence and property was stolen, along with a handgun. | 2012-12-10T00:00:00 | 0600 - 1800 |          | 
| DISTRICT 6                        | 12-11036 | (1630 Hrs) | SUPPLEMENTAL-RECOVERY OF STOLEN VEHICLE | Officers located a 2002 Dodge Caravan that had previously been reported stolen from Suburban Motors.                                                                                             | 2012-12-10T00:00:00 | 0600 - 1800 |          | 
| Total number of calls for service | 105      |            |                                         |                                                                                                                                                                                                  | 2012-12-10T00:00:00 | 0600 - 1800 |          | 
| DISTRICT 4                        | 12-11094 | (0754 Hrs) | THEFT UNDER $500                        | The victim (B/M/36) reported unknown person(s) stole property from his yard.                                                                                                                     | 2012-12-10T00:00:00 | 0600 - 1800 |          | 
| DISTRICT 3                        | 12-11100 | (1130 Hrs) | BURGLARY TO VEHICLE                     | The victim (W/F/19) reported unknown suspect burglarized her vehicle by smashing her front and rear windows out of her car. Property was stolen from the vehicle.                                | 2012-12-10T00:00:00 | 0600 - 1800 |          | 
| DISTRICT 4                        | 12-11102 | (1234 Hrs) | BURGLARY TO VEHICLE                     | The victim (W/F/21) reported sometime between 1020-1210 hours, unknown suspect gained entry into her trunk while it was parked on the lot. No property was reported missing.                     | 2012-12-10T00:00:00 | 0600 - 1800 |          | 
| DISTRICT 1                        | 12-11104 | (1345 Hrs) | RESIDENTIAL BURGLARY                    | The victim (W/M/64) reported between 1100-1338 hours, unknown suspect(s) burglarized his residence. The suspect(s) rummaged through the residence and property was stolen, along with a handgun. | 2012-12-10T00:00:00 | 0600 - 1800 |          | 
```