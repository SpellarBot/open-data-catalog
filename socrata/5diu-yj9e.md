# Agency Service Requests

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/agency-service-requests) |
| Metadata | [Link](https://data.montgomerycountymd.gov/api/views/5diu-yj9e) |
| Data: JSON | [100 Rows](https://data.montgomerycountymd.gov/api/views/5diu-yj9e/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.montgomerycountymd.gov/api/views/5diu-yj9e/rows.csv?max_rows=100) |
| Host | data.montgomerycountymd.gov |
| Id | 5diu-yj9e |
| Name | Agency Service Requests |
| Category | Community/Recreation |
| Tags | complains, investigation, enforcement, submitted to dps |
| Created | 2015-04-08T01:07:25Z |
| Publication Date | 2015-04-08T01:09:10Z |

## Description

Publish DPS Agency Service Requests Data on Open Data web site Update Frequency: Daily

## Columns

```ls
| Included | Schema Type | Field Name         | Name                         | Data Type     | Render Type   |
| ======== | =========== | ================== | ============================ | ============= | ============= |
| Yes      | series tag  | service_request_no | Service Request Number       | text          | text          |
| Yes      | series tag  | request_type       | Request Type                 | text          | text          |
| Yes      | series tag  | description        | Description                  | text          | text          |
| Yes      | time        | request_date       | Request Date                 | calendar_date | calendar_date |
| Yes      | series tag  | takenby            | Taken By                     | text          | text          |
| Yes      | series tag  | inspector          | Inspector                    | text          | text          |
| No       |             | inspect_date       | Inspection Date              | calendar_date | calendar_date |
| Yes      | series tag  | location           | Location                     | text          | text          |
| Yes      | series tag  | stno               | Street Number                | text          | text          |
| Yes      | series tag  | predir             | Pre-direction                | text          | text          |
| Yes      | series tag  | stname             | Street name of work location | text          | text          |
| Yes      | series tag  | suffix             | Street Suffix                | text          | text          |
| Yes      | series tag  | postdir            | Post-direction               | text          | text          |
| Yes      | series tag  | city               | City                         | text          | text          |
| Yes      | series tag  | state              | State                        | text          | text          |
| Yes      | series tag  | zip                | ZIP code                     | text          | text          |
```

## Time Field

```ls
Value = request_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = inspect_date
```

## Data Commands

```ls
series e:5diu-yj9e d:2017-02-13T00:00:00.000Z t:takenby=WEB t:stno=909 t:zip=20912 t:inspector=SACKE t:request_type=B11 t:description="RESIDENTIAL BUILDING VIOLATION" t:service_request_no=200055061 t:state=MD t:stname=PROSPECT t:suffix=ST t:city="TAKOMA PARK" m:row_number.5diu-yj9e=1

series e:5diu-yj9e d:2016-05-07T00:00:00.000Z t:takenby=WEB t:stno=7912 t:zip=20910 t:request_type=REFRD t:description="NOT A DPS ISSUE - REFERRED TO ANOTHER DEPT/AGENCY" t:service_request_no=200051212 t:state=MD t:stname=GEORGIA t:suffix=AVE t:city="SILVER SPRING" m:row_number.5diu-yj9e=2

series e:5diu-yj9e d:2017-02-13T00:00:00.000Z t:takenby=WEB t:stno=2919 t:zip=20895 t:inspector=SACKE t:request_type=B17 t:description="OTHER BUILDING VIOLATION" t:service_request_no=200055064 t:state=MD t:stname=BURTONHILL t:suffix=DR t:city=KENSINGTON m:row_number.5diu-yj9e=3
```

## Meta Commands

```ls
metric m:row_number.5diu-yj9e p:long l:"Row Number"

entity e:5diu-yj9e l:"Agency Service Requests" t:url=https://data.montgomerycountymd.gov/api/views/5diu-yj9e

property e:5diu-yj9e t:meta.view v:id=5diu-yj9e v:category=Community/Recreation v:averageRating=0 v:name="Agency Service Requests"

property e:5diu-yj9e t:meta.view.owner v:id=ajn4-zy65 v:screenName="MCG ESB Service" v:lastNotificationSeenAt=1491401045 v:displayName="MCG ESB Service"

property e:5diu-yj9e t:meta.view.tableauthor v:id=ajn4-zy65 v:screenName="MCG ESB Service" v:roleName=administrator v:lastNotificationSeenAt=1491401045 v:displayName="MCG ESB Service"
```

## Top Records

```ls
| service_request_no | request_type | description                                       | request_date        | takenby | inspector | inspect_date        | location                                                                                                                                                                                                                           | stno  | predir | stname        | suffix | postdir | city          | state | zip   | 
| ================== | ============ | ================================================= | =================== | ======= | ========= | =================== | ================================================================================================================================================================================================================================== | ===== | ====== | ============= | ====== | ======= | ============= | ===== | ===== | 
| 200055061          | B11          | RESIDENTIAL BUILDING VIOLATION                    | 2017-02-13T00:00:00 | WEB     | SACKE     |                     |                                                                                                                                                                                                                                    | 909   |        | PROSPECT      | ST     |         | TAKOMA PARK   | MD    | 20912 | 
| 200051212          | REFRD        | NOT A DPS ISSUE - REFERRED TO ANOTHER DEPT/AGENCY | 2016-05-07T00:00:00 | WEB     |           |                     |                                                                                                                                                                                                                                    | 7912  |        | GEORGIA       | AVE    |         | SILVER SPRING | MD    | 20910 | 
| 200055064          | B17          | OTHER BUILDING VIOLATION                          | 2017-02-13T00:00:00 | WEB     | SACKE     |                     |                                                                                                                                                                                                                                    | 2919  |        | BURTONHILL    | DR     |         | KENSINGTON    | MD    | 20895 | 
| 200051215          | REFRD        | NOT A DPS ISSUE - REFERRED TO ANOTHER DEPT/AGENCY | 2016-05-07T00:00:00 | WEB     |           |                     | 10605 dunkirk drive                                                                                                                                                                                                                | 10605 |        | DUNKIRK       | DR     |         | SILVER SPRING | MD    | 20902 | 
| 200051216          | Z99          | ZONING-OTHER-LAND USE OTHER                       | 2016-05-07T00:00:00 | WEB     |           |                     | Major renovation is being done with out permit. HVAC- Electric-Plumbing and structural changes including doors, garage bath room, etc. Basement and upper level. Blocking street. Trash is flying every where. Working late night. |       |        |               |        |         |               |       |       | 
| 200055076          | Z30          | FRONT YARD PARKING                                | 2017-02-13T00:00:00 | WEB     | CARMK     | 2017-02-14T00:00:00 |                                                                                                                                                                                                                                    | 12521 |        | GALWAY        | DR     |         | SILVER SPRING | MD    | 20904 | 
| 200051223          | REFRD        | NOT A DPS ISSUE - REFERRED TO ANOTHER DEPT/AGENCY | 2016-05-09T00:00:00 | WEB     |           |                     | 11345 Brandy Hall Lane. Gaithersburg MD 20878                                                                                                                                                                                      |       |        |               |        |         |               |       |       | 
| 200051224          | Z99          | ZONING-OTHER-LAND USE OTHER                       | 2016-05-09T00:00:00 | WEB     | SACKE     |                     |                                                                                                                                                                                                                                    | 3103  |        | CUMMINGS LANE | LN     |         | CHEVY CHASE   | MD    | 20815 | 
| 200055093          | B13          | SWIMMING POOLS                                    | 2017-02-14T00:00:00 | WEB     | SACKE     |                     | 14430 sugarland LN poolesville MD 20837                                                                                                                                                                                            | 14430 |        | SUGARLAND     | LN     |         | POOLESVILLE   | MD    | 20837 | 
| 200055094          | WR1          | SEDIMENT CONTROL ENVIRONMENTAL                    | 2017-02-14T00:00:00 | GANTH   | SACKE     |                     | 14430 sugarland LN poolesville MD 20837                                                                                                                                                                                            | 14430 |        | SUGARLAND     | LN     |         | POOLESVILLE   | MD    | 20837 | 
```