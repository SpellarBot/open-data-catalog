# DOT Parking Tickets

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dot-parking-tickets) |
| Metadata | [Link](https://data.montgomerycountymd.gov/api/views/uyb2-cfmc) |
| Data: JSON | [100 Rows](https://data.montgomerycountymd.gov/api/views/uyb2-cfmc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.montgomerycountymd.gov/api/views/uyb2-cfmc/rows.csv?max_rows=100) |
| Host | data.montgomerycountymd.gov |
| Id | uyb2-cfmc |
| Name | DOT Parking Tickets |
| Attribution | Montgomery County, MD |
| Category | Transportation |
| Tags | parking, ticket, citation, fee, no parking |
| Created | 2016-03-09T13:06:42Z |
| Publication Date | 2016-04-06T14:57:36Z |

## Description

All parking citations issued by Montgomery County Department of Transportation (MCDOT) enforcement personnel in the Montgomery County Parking Lot Districts and Transportation Management Districts of Bethesda, Montgomery Hills, Silver Spring, Wheaton, North Bethesda, Friendship Heights, Greater Seneca Science Center and the Residential Permit Parking areas. This includes all on-street metered parking, public surface lots and public garages. The parking citations list the following: date/time, location, vehicle information, and description of the violation.  

Update Frequency:  This data is updated annually.

## Columns

```ls
| Included | Schema Type    | Field Name            | Name                  | Data Type     | Render Type   |
| ======== | ============== | ===================== | ===================== | ============= | ============= |
| Yes      | series tag     | ticket_number         | Ticket Number         | text          | text          |
| Yes      | time           | date_time             | Date/Time             | calendar_date | calendar_date |
| Yes      | numeric metric | parking_division      | Parking Division      | number        | text          |
| Yes      | series tag     | ticket_location       | Ticket Location       | text          | text          |
| Yes      | series tag     | meter                 | Meter                 | text          | text          |
| Yes      | series tag     | violation_code        | Violation Code        | text          | text          |
| Yes      | series tag     | violation_description | Violation Description | text          | text          |
| Yes      | series tag     | plate_year            | Plate Year            | text          | text          |
| Yes      | series tag     | vehicle_make          | Vehicle Make          | text          | text          |
| Yes      | series tag     | plate_month           | Plate Month           | text          | text          |
| Yes      | series tag     | vehicle_type          | Vehicle Type          | text          | text          |
| Yes      | series tag     | vehicle_color         | Vehicle Color         | text          | text          |
| Yes      | series tag     | remarks               | Remarks               | text          | text          |
| Yes      | series tag     | issuing_agency        | Issuing Agency        | text          | text          |
```

## Time Field

```ls
Value = date_time
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:uyb2-cfmc d:2015-05-28T13:02:00.000Z t:plate_month=02 t:meter=3572380 t:vehicle_color=GY t:violation_code=050 t:vehicle_type=SU t:plate_year=2017 t:issuing_agency=DOT t:remarks="4 HR PARKING" t:ticket_location="G57-4841 BETHESDA AVE" t:violation_description="EXPIRED PRKG METER" t:ticket_number=400919153 t:vehicle_make=ACUR m:parking_division=2

series e:uyb2-cfmc d:2015-06-11T17:37:00.000Z t:plate_month=08 t:meter=3570021 t:vehicle_color=GY t:violation_code=050 t:vehicle_type=CV t:plate_year=2016 t:issuing_agency=DOT t:remarks="2 HR PARKING" t:ticket_location="G57-4841 BETHESDA AVE" t:violation_description="EXPIRED PRKG METER" t:ticket_number=400972084 t:vehicle_make=TOYT m:parking_division=2

series e:uyb2-cfmc d:2014-11-21T15:27:00.000Z t:plate_month=01 t:vehicle_color=BK t:violation_code=054 t:vehicle_type=SU t:plate_year=2015 t:issuing_agency=DOT t:remarks="WOODSIDE. 8AM-5PM MON-FRI. NO PERMIT" t:ticket_location="1400 BALLARD ST" t:violation_description="RES PRKG PERMIT ONLY" t:ticket_number=400277043 t:vehicle_make=MITS m:parking_division=9
```

## Meta Commands

```ls
metric m:parking_division p:integer l:"Parking Division" d:"Parking Division" t:dataTypeName=number

entity e:uyb2-cfmc l:"DOT Parking Tickets" t:attribution="Montgomery County, MD" t:url=https://data.montgomerycountymd.gov/api/views/uyb2-cfmc

property e:uyb2-cfmc t:meta.view v:id=uyb2-cfmc v:category=Transportation v:averageRating=0 v:name="DOT Parking Tickets" v:attribution="Montgomery County, MD"

property e:uyb2-cfmc t:meta.view.license v:name="Public Domain"

property e:uyb2-cfmc t:meta.view.owner v:id=ajn4-zy65 v:screenName="MCG ESB Service" v:lastNotificationSeenAt=1491401045 v:displayName="MCG ESB Service"

property e:uyb2-cfmc t:meta.view.tableauthor v:id=ajn4-zy65 v:screenName="MCG ESB Service" v:roleName=administrator v:lastNotificationSeenAt=1491401045 v:displayName="MCG ESB Service"
```

## Top Records

```ls
| ticket_number | date_time           | parking_division | ticket_location       | meter   | violation_code | violation_description | plate_year | vehicle_make | plate_month | vehicle_type | vehicle_color | remarks                                                                            | issuing_agency | 
| ============= | =================== | ================ | ===================== | ======= | ============== | ===================== | ========== | ============ | =========== | ============ | ============= | ================================================================================== | ============== | 
| 400919153     | 2015-05-28T13:02:00 | 2                | G57-4841 BETHESDA AVE | 3572380 | 050            | EXPIRED PRKG METER    | 2017       | ACUR         | 02          | SU           | GY            | 4 HR PARKING                                                                       | DOT            | 
| 400972084     | 2015-06-11T17:37:00 | 2                | G57-4841 BETHESDA AVE | 3570021 | 050            | EXPIRED PRKG METER    | 2016       | TOYT         | 08          | CV           | GY            | 2 HR PARKING                                                                       | DOT            | 
| 400277043     | 2014-11-21T15:27:00 | 9                | 1400 BALLARD ST       |         | 054            | RES PRKG PERMIT ONLY  | 2015       | MITS         | 01          | SU           | BK            | WOODSIDE. 8AM-5PM MON-FRI. NO PERMIT                                               | DOT            | 
| 400750431     | 2015-04-14T17:47:00 | 2                | 7700 WOODMONT AVE     | 1107302 | 050            | EXPIRED PRKG METER    | 2016       | HYUN         | 01          | 4D           | GY            | 1 HR PARKING                                                                       | DOT            | 
| 400436514     | 2015-01-12T11:07:00 | 2                | 7700 WOODMONT AVE     | 1107308 | 050            | EXPIRED PRKG METER    | 2016       | NISS         | 01          | SU           | MA            | 1 HR PARKING                                                                       | DOT            | 
| 400567845     | 2015-02-20T12:14:00 | 9                | 11307 ESTONA DR       |         | 054            | RES PRKG PERMIT ONLY  | 2016       | JEEP         | 06          | SU           | GR            | KENSINGTON-COLLEGE VIEW. 9AM/5PM MON/FRI. NO RESIDENTIAL/VISITOR PERMIT DISPLAYED. | DOT            | 
| 400284975     | 2014-11-22T15:51:00 | 2                | 4700 HAMPDEN LN       | 1103020 | 050            | EXPIRED PRKG METER    | 2014       | FORD         | 11          | PU           | WH            | 1 HR PARKING                                                                       | DOT            | 
| 400665915     | 2015-03-24T16:04:00 | 9                | 807 ISLINGTON ST      |         | 054            | RES PRKG PERMIT ONLY  | 2016       | TOYT         | 05          | 4D           | BK            | EAST SILVER SPRING. 8AM-10PM MON-FRI. NO RESIDENTIAL/VISITOR PERMIT                | DOT            | 
| 400452463     | 2015-01-15T10:57:00 | 9                | 10925 AMHERST AVE     |         | 054            | RES PRKG PERMIT ONLY  | 2015       | CHEV         | 02          | SU           | BK            | AMHERST/BUCKNELL. 9AM/5PM MON/FRI. NO PERMIT                                       | DOT            | 
| 400896543     | 2015-05-22T14:14:00 | 8                | 10400 AUTO PARK AVE   | 1501012 | 050            | EXPIRED PRKG METER    | 2016       | TOYT         | 09          | 4D           | GY            | 12 HR PARKING                                                                      | DOT            | 
```