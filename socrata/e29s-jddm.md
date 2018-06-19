# Parking Facilities

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/parking-facilities-4351d) |
| Metadata | [Link](https://data.baltimorecity.gov/api/views/e29s-jddm) |
| Data: JSON | [100 Rows](https://data.baltimorecity.gov/api/views/e29s-jddm/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.baltimorecity.gov/api/views/e29s-jddm/rows.csv?max_rows=100) |
| Host | data.baltimorecity.gov |
| Id | e29s-jddm |
| Name | Parking Facilities |
| Attribution | Parking Authority of Baltimore City |
| Category | Transportation |
| Tags | parking |
| Created | 2012-02-21T20:57:26Z |
| Publication Date | 2014-04-03T23:43:44Z |

## Description

Parking Facilities throughout the City of Baltimore.

## Columns

```ls
| Included | Schema Type | Field Name       | Name             | Data Type | Render Type |
| ======== | =========== | ================ | ================ | ========= | =========== |
| No       | time        | :updated_at      | updated_at       | meta_data | meta_data   |
| Yes      | series tag  | operator         | operator         | text      | text        |
| Yes      | series tag  | phone            | phone            | text      | text        |
| No       |             | address          | address          | text      | text        |
| Yes      | series tag  | street           | street           | text      | text        |
| Yes      | series tag  | hoursofoperation | hoursOfOperation | text      | text        |
| Yes      | series tag  | dailymaximumrate | dailyMaximumRate | text      | text        |
| Yes      | series tag  | earlybird        | earlyBird        | text      | text        |
| Yes      | series tag  | eveningweekend   | eveningWeekend   | text      | text        |
| Yes      | series tag  | weekendrate      | weekendRate      | text      | text        |
| Yes      | series tag  | monthlyrate      | monthlyRate      | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address
```

## Data Commands

```ls
series e:e29s-jddm d:2012-02-21T12:57:32.000Z t:eveningweekend=N/A t:hoursofoperation=N/A t:phone="(410) 625-0604" t:dailymaximumrate=N/A t:street="Between Linden Avenue and North Eutaw Street near Madison Street" t:earlybird=N/A t:monthlyrate="Tenants $40  Regular $55" t:operator="Alpha Development" t:weekendrate=N/A m:row_number.e29s-jddm=1

series e:e29s-jddm d:2012-02-21T12:57:32.000Z t:eveningweekend=N/A t:hoursofoperation=24hrs t:phone="(410) 727-6661" t:dailymaximumrate=$18 t:street="East Lee Street" t:earlybird=N/A t:monthlyrate=N/A t:operator=Arrow t:weekendrate=N/A m:row_number.e29s-jddm=2

series e:e29s-jddm d:2012-02-21T12:57:32.000Z t:eveningweekend="evening after 5pm 0-1hr $5;  >1hr til 6am $10" t:hoursofoperation=24hrs t:phone="(410) 727-6661" t:dailymaximumrate=$19 t:street="East Lombard Street" t:earlybird=$9 t:monthlyrate=$180 t:operator=Arrow t:weekendrate=N/A m:row_number.e29s-jddm=3
```

## Meta Commands

```ls
metric m:row_number.e29s-jddm p:long l:"Row Number"

entity e:e29s-jddm l:"Parking Facilities" t:attribution="Parking Authority of Baltimore City" t:url=https://data.baltimorecity.gov/api/views/e29s-jddm

property e:e29s-jddm t:meta.view v:id=e29s-jddm v:category=Transportation v:attributionLink=http://www.baltimorecity.gov/Government/QuasiAgencies/ParkingAuthority.aspx v:averageRating=0 v:name="Parking Facilities" v:attribution="Parking Authority of Baltimore City"

property e:e29s-jddm t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:e29s-jddm t:meta.view.owner v:id=6r9a-dfdj v:screenName="Open Baltimore" v:displayName="Open Baltimore"

property e:e29s-jddm t:meta.view.tableauthor v:id=6r9a-dfdj v:screenName="Open Baltimore" v:roleName=administrator v:displayName="Open Baltimore"
```

## Top Records

```ls
| :updated_at | operator          | phone          | address                                                | street                                                           | hoursofoperation                                                                                  | dailymaximumrate | earlybird | eveningweekend                               | weekendrate | monthlyrate             | 
| =========== | ================= | ============== | ====================================================== | ================================================================ | ================================================================================================= | ================ | ========= | ============================================ | =========== | ======================= | 
| 1329829052  | Alpha Development | (410) 625-0604 | Several Lot Addresses, used to be location of rowhomes | Between Linden Avenue and North Eutaw Street near Madison Street | N/A                                                                                               | N/A              | N/A       | N/A                                          | N/A         | Tenants $40 Regular $55 | 
| 1329829052  | Arrow             | (410) 727-6661 | 11                                                     | East Lee Street                                                  | 24hrs                                                                                             | $18              | N/A       | N/A                                          | N/A         | N/A                     | 
| 1329829052  | Arrow             | (410) 727-6661 | 204                                                    | East Lombard Street                                              | 24hrs                                                                                             | $19              | $9        | evening after 5pm 0-1hr $5; >1hr til 6am $10 | N/A         | $180                    | 
| 1329829052  | Arrow             | (410) 727-6661 | 210                                                    | West Baltimore Street                                            | 24hrs                                                                                             | $14              | $10       | N/A                                          | N/A         | $179                    | 
| 1329829052  | Arrow             | (410) 727-6669 | 309                                                    | North Howard Street                                              | 24hrs                                                                                             | $8               | No        | N/A                                          | N/A         | N/A                     | 
| 1329829052  | Arrow             | (410) 385-2975 | 220                                                    | West Franklin Street                                             | 24hrs attendant on duty 6am-4pm                                                                   | $7               | No        | N/A                                          | N/A         | $132                    | 
| 1329829052  | Arrow             | (410) 727-1583 | 213                                                    | West Fayette Street                                              | M-F 6am-8pm Closed Weekends                                                                       | $10              | No        | N/A                                          | Closed      | $132                    | 
| 1329829052  | Arrow             | (410) 727-6812 | 16                                                     | South Charles Street                                             | M-F 6:30am-10pm Closed Weekends                                                                   | $15              | $10       | $5                                           | Closed      | $150                    | 
| 1329829052  | Arrow             | (410) 727-6661 | 229                                                    | West Saratoga Street                                             | M-Sat 6am-7pm Closed Sunday                                                                       | $8               | N/A       | N/A                                          | N/A         | $137                    | 
| 1329829052  | Broadway Services | (410) 234-4568 | 606                                                    | St. Paul Street                                                  | M-F 6:30am-9:30pm, Sat 7:30am-5:30pm, Sun 12:30pm-5:30pm *Summer Session, 6/1-8/20, closes at 7pm | $8               | N/A       | $5                                           | $4          | $135                    | 
```