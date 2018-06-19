# MCFRS Incidents by Station

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/mcfrs-incidents-by-station) |
| Metadata | [Link](https://data.montgomerycountymd.gov/api/views/mf5d-mtzf) |
| Data: JSON | [100 Rows](https://data.montgomerycountymd.gov/api/views/mf5d-mtzf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.montgomerycountymd.gov/api/views/mf5d-mtzf/rows.csv?max_rows=100) |
| Host | data.montgomerycountymd.gov |
| Id | mf5d-mtzf |
| Name | MCFRS Incidents by Station |
| Category | Public Safety |
| Tags | fire, emergency, incidents, station |
| Created | 2013-10-23T15:53:29Z |
| Publication Date | 2015-12-23T18:07:16Z |

## Description

This dataset contains the monthly summary data indicating incident occurred in each fire station response area.  The summary data is the incident count broken down by call type group for each fire station response area. Update Frequency - Twice a month on the 1st and 15th date each month.

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type | Render Type |
| ======== | ============== | =================== | =================== | ========= | =========== |
| Yes      | series tag     | fire_station        | Fire Station        | text      | text        |
| Yes      | series tag     | fire_station_number | Fire Station Number | text      | text        |
| Yes      | series tag     | nature_of_911_call  | Nature of 911 call  | text      | text        |
| Yes      | numeric metric | monthly_total       | Monthly Total       | number    | number      |
| No       |                | year                | Year                | number    | number      |
| No       |                | month               | Month               | text      | text        |
| Yes      | series tag     | month_num           | Month Num           | text      | number      |
| No       |                | station_address     | Station address     | text      | text        |
```

## Time Field

```ls
Value = year-month
Format & Zone = yyyy-MMMM
```

## Series Fields

```ls
Excluded Fields = station_address,year,month
```

## Data Commands

```ls
series e:mf5d-mtzf d:2013-06-01T00:00:00.000Z t:month_num=6 t:nature_of_911_call=SICK t:fire_station_number=13 t:fire_station="Damascus Volunteer Fire Department (Station 13)" m:monthly_total=9

series e:mf5d-mtzf d:2013-03-01T00:00:00.000Z t:month_num=3 t:nature_of_911_call=SICK t:fire_station_number=13 t:fire_station="Damascus Volunteer Fire Department (Station 13)" m:monthly_total=12

series e:mf5d-mtzf d:2013-05-01T00:00:00.000Z t:month_num=5 t:nature_of_911_call=SICK t:fire_station_number=13 t:fire_station="Damascus Volunteer Fire Department (Station 13)" m:monthly_total=16
```

## Meta Commands

```ls
metric m:monthly_total p:integer l:"Monthly Total" d:"The monthly total of calls per call type group, per fire station." t:dataTypeName=number

entity e:mf5d-mtzf l:"MCFRS Incidents by Station" t:url=https://data.montgomerycountymd.gov/api/views/mf5d-mtzf

property e:mf5d-mtzf t:meta.view v:id=mf5d-mtzf v:category="Public Safety" v:averageRating=0 v:name="MCFRS Incidents by Station"

property e:mf5d-mtzf t:meta.view.owner v:id=ajn4-zy65 v:screenName="MCG ESB Service" v:lastNotificationSeenAt=1491401045 v:displayName="MCG ESB Service"

property e:mf5d-mtzf t:meta.view.tableauthor v:id=ajn4-zy65 v:screenName="MCG ESB Service" v:roleName=administrator v:lastNotificationSeenAt=1491401045 v:displayName="MCG ESB Service"
```

## Top Records

```ls
| fire_station                                           | fire_station_number | nature_of_911_call | monthly_total | year | month    | month_num | station_address                   | 
| ====================================================== | =================== | ================== | ============= | ==== | ======== | ========= | ================================= | 
| Damascus Volunteer Fire Department (Station 13)        | 13                  | SICK               | 9             | 2013 | JUNE     | 6         | 26334 Ridge Rd Damascus, MD 20750 | 
| Damascus Volunteer Fire Department (Station 13)        | 13                  | SICK               | 12            | 2013 | MARCH    | 3         | 26334 Ridge Rd Damascus, MD 20750 | 
| Damascus Volunteer Fire Department (Station 13)        | 13                  | SICK               | 16            | 2013 | MAY      | 5         | 26334 Ridge Rd Damascus, MD 20750 | 
| Damascus Volunteer Fire Department (Station 13)        | 13                  | TRAUMA             | 5             | 2012 | JULY     | 7         | 26334 Ridge Rd Damascus, MD 20750 | 
| Damascus Volunteer Fire Department (Station 13)        | 13                  | TRAUMA             | 1             | 2012 | JUNE     | 6         | 26334 Ridge Rd Damascus, MD 20750 | 
| Damascus Volunteer Fire Department (Station 13)        | 13                  | ALLERGIC           | 3             | 2012 | MAY      | 5         | 26334 Ridge Rd Damascus, MD 20750 | 
| Cabin John Park Volunteer Fire Department (Station 10) | 10                  | ABDOMINAL PAIN     | 2             | 2012 | AUGUST   | 8         | 8001 River Rd Bethesda, MD 20817  | 
| Cabin John Park Volunteer Fire Department (Station 10) | 10                  | ABDOMINAL PAIN     | 1             | 2012 | DECEMBER | 12        | 8001 River Rd Bethesda, MD 20817  | 
| Cabin John Park Volunteer Fire Department (Station 10) | 10                  | ABDOMINAL PAIN     | 1             | 2012 | JULY     | 7         | 8001 River Rd Bethesda, MD 20817  | 
| Cabin John Park Volunteer Fire Department (Station 10) | 10                  | ABDOMINAL PAIN     | 3             | 2012 | MAY      | 5         | 8001 River Rd Bethesda, MD 20817  | 
```