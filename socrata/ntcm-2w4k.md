# Directory Of Homebase Locations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/directory-of-homebase-locations-09a13) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/ntcm-2w4k) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/ntcm-2w4k/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/ntcm-2w4k/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | ntcm-2w4k |
| Name | Directory Of Homebase Locations |
| Attribution | Department of Homeless Services (DHS) |
| Category | Social Services |
| Tags | dhs, homeless, service, homebase, location, contact, prevention, office |
| Created | 2013-01-31T16:01:05Z |
| Publication Date | 2015-11-23T20:09:32Z |

## Description

Locations of Homebase (Homeless Prevention Network) offices

## Columns

```ls
| Included | Schema Type | Field Name         | Name               | Data Type | Render Type |
| ======== | =========== | ================== | ================== | ========= | =========== |
| No       | time        | :updated_at        | updated_at         | meta_data | meta_data   |
| Yes      | series tag  | neighborhood       | Neighborhood       | text      | text        |
| No       |             | address            | Address            | text      | text        |
| Yes      | series tag  | phone_number       | Phone Number       | text      | text        |
| Yes      | series tag  | borough            | Borough            | text      | text        |
| Yes      | series tag  | community_district | Community District | text      | text        |
| Yes      | series tag  | homebase_office    | Homebase Office    | text      | text        |
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
series e:ntcm-2w4k d:2015-11-23T12:08:41.000Z t:phone_number=917-492-1019 t:homebase_office=SUS t:neighborhood="East Harlem" t:borough=Manhattan t:community_district=Manhattan m:row_number.ntcm-2w4k=1

series e:ntcm-2w4k d:2015-11-23T12:08:41.000Z t:phone_number=917-492-1019 t:homebase_office=SUS t:neighborhood="Lower East Side" t:borough=Manhattan t:community_district=Manhattan m:row_number.ntcm-2w4k=2

series e:ntcm-2w4k d:2015-11-23T12:08:41.000Z t:phone_number=718-299-8473 t:homebase_office="Help USA I" t:neighborhood=Crotona t:borough=Bronx t:community_district="203, 206" m:row_number.ntcm-2w4k=3
```

## Meta Commands

```ls
metric m:row_number.ntcm-2w4k p:long l:"Row Number"

entity e:ntcm-2w4k l:"Directory Of Homebase Locations" t:attribution="Department of Homeless Services (DHS)" t:url=https://data.cityofnewyork.us/api/views/ntcm-2w4k

property e:ntcm-2w4k t:meta.view v:id=ntcm-2w4k v:category="Social Services" v:attributionLink=http://www.nyc.gov/html/dhs/downloads/pdf/homebase_map.pdf v:averageRating=0 v:name="Directory Of Homebase Locations" v:attribution="Department of Homeless Services (DHS)"

property e:ntcm-2w4k t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:ntcm-2w4k t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | neighborhood    | address                       | phone_number | borough   | community_district | homebase_office | 
| =========== | =============== | ============================= | ============ | ========= | ================== | =============== | 
| 1448280521  | East Harlem     | 2276 Third Avenue             | 917-492-1019 | Manhattan | Manhattan          | SUS             | 
| 1448280521  | Lower East Side | 265 Henry Street              | 917-492-1019 | Manhattan | Manhattan          | SUS             | 
| 1448280521  | Crotona         | 775 Crotona Park North        | 718-299-8473 | Bronx     | 203, 206           | Help USA I      | 
| 1448280521  | Claremont       | 3593 East 169th Street        | 917-801-4512 | Bronx     | 203, 206           | Help USA I      | 
| 1448280521  | Grand Concourse | 1130 Grand Concourse          | 718-508-3100 | Bronx     | 201, 204           | Bronxworks      | 
| 1448280521  | Mott Haven      | 630 Jackson Avenue            | 718-993-2032 | Bronx     | 201, 204           | Bronxworks      | 
| 1448280521  | Mount Hope      | 1780 Grand Concourse, Level I | 347-226-4540 | Bronx     | 205, 207, 208      | Help USA II     | 
| 1448280521  | Morris Heights  | 1981 Sedgwick Avenue          | 718-215-6453 | Bronx     | 205, 207, 208      | Help USA II     | 
| 1448280521  | Unionport       | 2155 Blackrock Avenue         | 718-414-1050 | Bronx     | 202, 209           | ARCHNY I        | 
| 1448280521  | Hunts Point     | 890 Garrison Avenue           | 929-259-9430 | Bronx     | 202, 209           | ARCHNY I        | 
```