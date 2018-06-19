# Permit Inspections

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/permit-inspections) |
| Metadata | [Link](https://data.montgomerycountymd.gov/api/views/hyxh-ndxj) |
| Data: JSON | [100 Rows](https://data.montgomerycountymd.gov/api/views/hyxh-ndxj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.montgomerycountymd.gov/api/views/hyxh-ndxj/rows.csv?max_rows=100) |
| Host | data.montgomerycountymd.gov |
| Id | hyxh-ndxj |
| Name | Permit Inspections |
| Category | Licenses/Permits |
| Tags | inspections, issued permits |
| Created | 2015-02-24T21:41:00Z |
| Publication Date | 2015-04-24T15:10:15Z |

## Description

Inspections performed for issued permits. Update Frequency: Daily

## Columns

```ls
| Included | Schema Type    | Field Name     | Name            | Data Type     | Render Type   |
| ======== | ============== | ============== | =============== | ============= | ============= |
| Yes      | series tag     | permitno       | Permit Number   | text          | text          |
| Yes      | series tag     | permit_type    | Permit Type     | text          | text          |
| Yes      | numeric metric | inspectionkey  | Inspection Key  | number        | text          |
| Yes      | series tag     | inspectiontype | Inspection Type | text          | text          |
| Yes      | series tag     | assignto       | Started By      | text          | text          |
| No       |                | scheddttm      | Started Date    | calendar_date | calendar_date |
| Yes      | series tag     | inspby         | Completed By    | text          | text          |
| Yes      | time           | compdttm       | Completed Date  | calendar_date | calendar_date |
| Yes      | series tag     | result         | Result          | text          | text          |
```

## Time Field

```ls
Value = compdttm
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = scheddttm
```

## Data Commands

```ls
series e:hyxh-ndxj d:2016-07-01T02:40:59.000Z t:permit_type="ELECTRICAL PERMIT" t:inspectiontype=FINAL t:permitno=433806 t:assignto=HOWES m:inspectionkey=3582653

series e:hyxh-ndxj d:2016-07-01T02:40:59.000Z t:permit_type="BUILDING RESIDENTIAL PERMIT" t:inspectiontype=FINAL t:permitno=433820 t:assignto=CRIM m:inspectionkey=3667156

series e:hyxh-ndxj d:2016-07-01T02:40:59.000Z t:permit_type="BUILDING RESIDENTIAL PERMIT" t:inspectiontype="FRAMING OR CLOSE IN-NEW SFD/TH" t:permitno=433827 t:assignto=CRIM m:inspectionkey=3623427
```

## Meta Commands

```ls
metric m:inspectionkey p:integer l:"Inspection Key" d:"Inspection Key" t:dataTypeName=number

entity e:hyxh-ndxj l:"Permit Inspections" t:url=https://data.montgomerycountymd.gov/api/views/hyxh-ndxj

property e:hyxh-ndxj t:meta.view v:id=hyxh-ndxj v:category=Licenses/Permits v:averageRating=0 v:name="Permit Inspections"

property e:hyxh-ndxj t:meta.view.owner v:id=ajn4-zy65 v:screenName="MCG ESB Service" v:lastNotificationSeenAt=1491401045 v:displayName="MCG ESB Service"

property e:hyxh-ndxj t:meta.view.tableauthor v:id=ajn4-zy65 v:screenName="MCG ESB Service" v:roleName=administrator v:lastNotificationSeenAt=1491401045 v:displayName="MCG ESB Service"
```

## Top Records

```ls
| permitno | permit_type                 | inspectionkey | inspectiontype                 | assignto | scheddttm | inspby | compdttm | result | 
| ======== | =========================== | ============= | ============================== | ======== | ========= | ====== | ======== | ====== | 
| 433806   | ELECTRICAL PERMIT           | 3582653       | FINAL                          | HOWES    |           |        |          |        | 
| 433820   | BUILDING RESIDENTIAL PERMIT | 3667156       | FINAL                          | CRIM     |           |        |          |        | 
| 433827   | BUILDING RESIDENTIAL PERMIT | 3623427       | FRAMING OR CLOSE IN-NEW SFD/TH | CRIM     |           |        |          |        | 
| 433863   | ELECTRICAL PERMIT           | 3582960       | FINAL                          | CRIM     |           |        |          |        | 
| 433898   | BUILDING RESIDENTIAL PERMIT | 3583191       | FINAL                          | HOWES    |           |        |          |        | 
| 433983   | ELECTRICAL PERMIT           | 3583512       | FINAL                          | HOWES    |           |        |          |        | 
| 433995   | ELECTRICAL PERMIT           | 3586584       | TEMP PENDING FINAL (RES.)      | HOWES    |           |        |          |        | 
| 433995   | ELECTRICAL PERMIT           | 3597416       | CONCEALMENT(ROUGH WIRING,TRENC | HOWES    |           |        |          |        | 
| 434011   | BUILDING RESIDENTIAL PERMIT | 3583766       | FINAL                          | CRIM     |           |        |          |        | 
| 434011   | BUILDING RESIDENTIAL PERMIT | 3594979       | FRAMING OR CLOSE IN-ADD&ALTER  | CRIM     |           |        |          |        | 
```