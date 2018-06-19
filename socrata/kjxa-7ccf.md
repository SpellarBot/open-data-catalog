# SCOUT Conditions

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/scout-conditions-98b9c) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/kjxa-7ccf) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/kjxa-7ccf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/kjxa-7ccf/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | kjxa-7ccf |
| Name | SCOUT Conditions |
| Attribution | Office of the Mayor (OTM) |
| Category | City Government |
| Tags | scout conditions, inspector, office of the mayor, otm |
| Created | 2014-03-06T16:04:56Z |
| Publication Date | 2014-03-06T16:07:30Z |

## Description

Quality of life conditions reported by city inspectors.

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type | Render Type |
| ======== | ============== | =============== | =============== | ========= | =========== |
| No       | time           | :updated_at     | updated_at      | meta_data | meta_data   |
| Yes      | series tag     | created_month   | Created Month   | text      | text        |
| Yes      | series tag     | borough         | Borough         | text      | text        |
| Yes      | series tag     | community_board | Community Board | text      | text        |
| Yes      | series tag     | agency          | Agency          | text      | text        |
| Yes      | series tag     | complaint_type  | Complaint Type  | text      | text        |
| Yes      | series tag     | descriptor_1    | Descriptor 1    | text      | text        |
| Yes      | numeric metric | of_srs          | # of SRs        | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:kjxa-7ccf d:2014-03-06T08:04:59.000Z t:complaint_type="Street Condition" t:created_month="2014 / 01" t:agency=DOT t:borough=BRONX t:descriptor_1="Failed Street Repair" t:community_board="01 BRONX" m:of_srs=1

series e:kjxa-7ccf d:2014-03-06T08:04:59.000Z t:complaint_type="Street Condition" t:created_month="2014 / 01" t:agency=DOT t:borough=BRONX t:descriptor_1=Pothole t:community_board="01 BRONX" m:of_srs=41

series e:kjxa-7ccf d:2014-03-06T08:04:59.000Z t:complaint_type="Street Sign - Damaged" t:created_month="2014 / 01" t:agency=DOT t:borough=BRONX t:descriptor_1=Other/Unknown t:community_board="01 BRONX" m:of_srs=1
```

## Meta Commands

```ls
metric m:of_srs p:integer l:"# of SRs" t:dataTypeName=number

entity e:kjxa-7ccf l:"SCOUT Conditions" t:attribution="Office of the Mayor (OTM)" t:url=https://data.cityofnewyork.us/api/views/kjxa-7ccf

property e:kjxa-7ccf t:meta.view v:id=kjxa-7ccf v:category="City Government" v:averageRating=0 v:name="SCOUT Conditions" v:attribution="Office of the Mayor (OTM)"

property e:kjxa-7ccf t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:kjxa-7ccf t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | created_month | borough | community_board | agency | complaint_type         | descriptor_1                     | of_srs | 
| =========== | ============= | ======= | =============== | ====== | ====================== | ================================ | ====== | 
| 1394093099  | 2014 / 01     | BRONX   | 01 BRONX        | DOT    | Street Condition       | Failed Street Repair             | 1      | 
| 1394093099  | 2014 / 01     | BRONX   | 01 BRONX        | DOT    | Street Condition       | Pothole                          | 41     | 
| 1394093099  | 2014 / 01     | BRONX   | 01 BRONX        | DOT    | Street Sign - Damaged  | Other/Unknown                    | 1      | 
| 1394093099  | 2014 / 01     | BRONX   | 01 BRONX        | DOT    | Street Sign - Dangling | Other/Unknown                    | 1      | 
| 1394093099  | 2014 / 01     | BRONX   | 01 BRONX        | DSNY   | Dirty Conditions       | E15 Illegal Postering            | 26     | 
| 1394093099  | 2014 / 01     | BRONX   | 01 BRONX        | DSNY   | Sanitation Condition   | 15 Street Cond/Dump-Out/Drop-Off | 2      | 
| 1394093099  | 2014 / 01     | BRONX   | 01 BRONX        | DSNY   | Vacant Lot             | 8 Request to Clean Vacant Lot    | 1      | 
| 1394093099  | 2014 / 01     | BRONX   | 03 BRONX        | DOT    | Street Condition       | Failed Street Repair             | 1      | 
| 1394093099  | 2014 / 01     | BRONX   | 03 BRONX        | DSNY   | Dirty Conditions       | E15 Illegal Postering            | 1      | 
| 1394093099  | 2014 / 01     | BRONX   | 04 BRONX        | DOT    | Street Condition       | Cave-in                          | 1      | 
```