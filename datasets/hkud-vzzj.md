# Office Locations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/office-locations-3603a) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/hkud-vzzj) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/hkud-vzzj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/hkud-vzzj/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | hkud-vzzj |
| Name | Office Locations |
| Attribution | Department of Probation (DOP) |
| Category | City Government |
| Tags | dop, probation, law, borough, contact, address, program |
| Created | 2013-02-12T17:17:26Z |
| Publication Date | 2014-05-05T18:19:47Z |

## Description

Department Of Probation Office Address

## Columns

```ls
| Included | Schema Type | Field Name       | Name             | Data Type | Render Type |
| ======== | =========== | ================ | ================ | ========= | =========== |
| No       | time        | :updated_at      | updated_at       | meta_data | meta_data   |
| Yes      | series tag  | area             | Area             | text      | text        |
| Yes      | series tag  | disposition_type | Disposition Type | text      | text        |
| No       |             | address          | Address          | text      | text        |
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
series e:hkud-vzzj d:2013-02-12T09:17:49.000Z t:area=Bronx t:disposition_type="Adult Operations" m:row_number.hkud-vzzj=1

series e:hkud-vzzj d:2013-02-12T09:17:49.000Z t:area=Bronx t:disposition_type="Adult Operations" m:row_number.hkud-vzzj=2

series e:hkud-vzzj d:2013-02-12T09:17:49.000Z t:area=Bronx t:disposition_type="Adult Operations" m:row_number.hkud-vzzj=3
```

## Meta Commands

```ls
metric m:row_number.hkud-vzzj p:long l:"Row Number"

entity e:hkud-vzzj l:"Office Locations" t:attribution="Department of Probation (DOP)" t:url=https://data.cityofnewyork.us/api/views/hkud-vzzj

property e:hkud-vzzj t:meta.view v:id=hkud-vzzj v:category="City Government" v:attributionLink=http://www.nyc.gov/html/prob/html/contact/locations.shtml v:averageRating=0 v:name="Office Locations" v:attribution="Department of Probation (DOP)"

property e:hkud-vzzj t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:hkud-vzzj t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | area      | disposition_type    | address                   | 
| =========== | ========= | =================== | ========================= | 
| 1360660669  | Bronx     | Adult Operations    | 215 East 161st Street     | 
| 1360660669  | Bronx     | Adult Operations    | 198 East 161st Street     | 
| 1360660669  | Bronx     | Adult Operations    | 265 East 161st Street     | 
| 1360660669  | Bronx     | Juvenile Operations | 900 Sheridan Avenue       | 
| 1360660669  | Brooklyn  | Adult Operations    | 345 Adams Street          | 
| 1360660669  | Brooklyn  | Adult Operations    | 210 Joralemon Street      | 
| 1360660669  | Brooklyn  | Brownsville NeON    | 444 Thomas Boyland Street | 
| 1360660669  | Brooklyn  | Juvenile Operations | 330 Jay Street            | 
| 1360660669  | Manhattan | Adult Operations    | 100 Centre Street         | 
| 1360660669  | Manhattan | Juvenile Operations | 60 Lafayette Stree        | 
```