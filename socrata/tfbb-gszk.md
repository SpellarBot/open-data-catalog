# Directory Of DOP Office Locations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/directory-of-dop-office-locations-29a9d) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/tfbb-gszk) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/tfbb-gszk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/tfbb-gszk/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | tfbb-gszk |
| Name | Directory Of DOP Office Locations |
| Attribution | Department of Probation (DOP) |
| Category | City Government |
| Tags | dop, probation, office, location, address |
| Created | 2013-02-07T14:40:21Z |
| Publication Date | 2014-05-05T18:20:59Z |

## Description

List of DOP Office locations by Borough

## Columns

```ls
| Included | Schema Type | Field Name       | Name             | Data Type | Render Type |
| ======== | =========== | ================ | ================ | ========= | =========== |
| No       | time        | :updated_at      | updated_at       | meta_data | meta_data   |
| Yes      | series tag  | borough          | Borough          | text      | text        |
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
series e:tfbb-gszk d:2013-02-07T06:40:22.000Z t:borough=Bronx t:disposition_type="Adult Operations" m:row_number.tfbb-gszk=1

series e:tfbb-gszk d:2013-02-07T06:40:22.000Z t:borough=Bronx t:disposition_type="Adult Operations" m:row_number.tfbb-gszk=2

series e:tfbb-gszk d:2013-02-07T06:40:22.000Z t:borough=Bronx t:disposition_type="Adult Operations" m:row_number.tfbb-gszk=3
```

## Meta Commands

```ls
metric m:row_number.tfbb-gszk p:long l:"Row Number"

entity e:tfbb-gszk l:"Directory Of DOP Office Locations" t:attribution="Department of Probation (DOP)" t:url=https://data.cityofnewyork.us/api/views/tfbb-gszk

property e:tfbb-gszk t:meta.view v:id=tfbb-gszk v:category="City Government" v:attributionLink=http://www.nyc.gov/html/prob/html/contact/locations.shtml v:averageRating=0 v:name="Directory Of DOP Office Locations" v:attribution="Department of Probation (DOP)"

property e:tfbb-gszk t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:tfbb-gszk t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | borough   | disposition_type    | address                   | 
| =========== | ========= | =================== | ========================= | 
| 1360219222  | Bronx     | Adult Operations    | 215 East 161st Street     | 
| 1360219222  | Bronx     | Adult Operations    | 198 East 161st Street     | 
| 1360219222  | Bronx     | Adult Operations    | 265 East 161st Street     | 
| 1360219222  | Bronx     | Juvenile Operations | 900 Sheridan Avenue       | 
| 1360219222  | Brooklyn  | Adult Operations    | 345 Adams Street          | 
| 1360219222  | Brooklyn  | Adult Operations    | 210 Joralemon Street      | 
| 1360219222  | Brooklyn  | Brownsville NeON    | 444 Thomas Boyland Street | 
| 1360219222  | Brooklyn  | Juvenile Operations | 330 Jay Street            | 
| 1360219222  | Manhattan | Adult Operations    | 100 Centre Street         | 
| 1360219222  | Manhattan | Juvenile Operations | 60 Lafayette Stree        | 
```