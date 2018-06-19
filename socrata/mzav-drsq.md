# Map Points - Location By Separate Latitutde Longitude Columns

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/map-points-location-by-separate-latitutde-longitude-columns-5997a) |
| Metadata | [Link](https://data.medicare.gov/api/views/mzav-drsq) |
| Data: JSON | [100 Rows](https://data.medicare.gov/api/views/mzav-drsq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.medicare.gov/api/views/mzav-drsq/rows.csv?max_rows=100) |
| Host | data.medicare.gov |
| Id | mzav-drsq |
| Name | Map Points - Location By Separate Latitutde Longitude Columns |
| Created | 2012-09-07T15:03:57Z |
| Publication Date | 2012-09-07T15:05:07Z |

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                 | Data Type | Render Type |
| ======== | ============== | ==================== | ==================== | ========= | =========== |
| No       | time           | :updated_at          | updated_at           | meta_data | meta_data   |
| Yes      | series tag     | department_name      | Department Name      | text      | text        |
| Yes      | series tag     | data_center_name     | Data Center Name     | text      | text        |
| No       |                | data_center_location | Data Center Location | text      | text        |
| Yes      | series tag     | status               | Status               | text      | text        |
| Yes      | numeric metric | point_size           | Point Size           | number    | number      |
| Yes      | numeric metric | point_color          | Point Color          | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = data_center_location
```

## Data Commands

```ls
series e:mzav-drsq d:2012-09-07T08:03:58.000Z t:status="Closed between Initiative Kickoff 2/26/2010 and Report 8/3/2012" t:data_center_name="DOJ - 253" t:department_name="Department of Justice" m:point_color=15 m:point_size=5

series e:mzav-drsq d:2012-09-07T08:03:58.000Z t:status="Closed between Initiative Kickoff 2/26/2010 and Report 8/3/2012" t:data_center_name="DOJ - 365" t:department_name="Department of Justice" m:point_color=20 m:point_size=10

series e:mzav-drsq d:2012-09-07T08:03:58.000Z t:status="Closed between Initiative Kickoff 2/26/2010 and Report 8/3/2012" t:data_center_name="DOJ - 433" t:department_name="Department of Justice" m:point_color=5 m:point_size=15
```

## Meta Commands

```ls
metric m:point_size p:integer l:"Point Size" t:dataTypeName=number

metric m:point_color p:integer l:"Point Color" t:dataTypeName=number

entity e:mzav-drsq l:"Map Points - Location By Separate Latitutde Longitude Columns" t:url=https://data.medicare.gov/api/views/mzav-drsq

property e:mzav-drsq t:meta.view v:id=mzav-drsq v:averageRating=0 v:name="Map Points - Location By Separate Latitutde Longitude Columns"

property e:mzav-drsq t:meta.view.owner v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:displayName=cms

property e:mzav-drsq t:meta.view.tableauthor v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:roleName=administrator v:displayName=cms
```

## Top Records

```ls
| :updated_at | department_name       | data_center_name | data_center_location                                          | status                                                          | point_size | point_color | 
| =========== | ===================== | ================ | ============================================================= | =============================================================== | ========== | =========== | 
| 1347005038  | Department of Justice | DOJ - 253        | Ft. Worth, TX 76177 (32.94332999987978, -97.31222999981446)   | Closed between Initiative Kickoff 2/26/2010 and Report 8/3/2012 | 5          | 15          | 
| 1347005038  | Department of Justice | DOJ - 365        | Atlanta, GA 30303 (33.755400000010184, -84.39011999973803)    | Closed between Initiative Kickoff 2/26/2010 and Report 8/3/2012 | 10         | 20          | 
| 1347005038  | Department of Justice | DOJ - 433        | Washington, DC 20530 (38.91858000036689, -76.96069000004331)  | Closed between Initiative Kickoff 2/26/2010 and Report 8/3/2012 | 15         | 5           | 
| 1347005038  | Department of Justice | DOJ - 486        | Boston, MA 02203 (42.36135000000269, -71.06050999993641)      | Closed between Initiative Kickoff 2/26/2010 and Report 8/3/2012 | 20         | 10          | 
| 1347005038  | Department of Justice | DOJ - 608        | Chicago, IL 60604 (41.87826000019902, -87.62919000001835)     | Closed between Initiative Kickoff 2/26/2010 and Report 8/3/2012 | 5          | 15          | 
| 1347005038  | Department of Justice | DOJ - 718        | Dallas, TX 75201 (32.78752000024798, -96.79979000000833)      | To be closed between 10/1/2012 and 9/30/2013                    | 10         | 20          | 
| 1347005038  | Department of Justice | DOJ - 719        | Dallas, TX 75220 (32.866700000404876, -96.8668099996816)      | Closed between Initiative Kickoff 2/26/2010 and Report 8/3/2012 | 15         | 5           | 
| 1347005038  | Department of Justice | DOJ - 815        | Arlington, VA 22202 (38.856990000188546, -77.05637000027514)  | Closed between Initiative Kickoff 2/26/2010 and Report 8/3/2012 | 20         | 10          | 
| 1347005038  | Department of Justice | DOJ - 826        | Johnstown, PA 15901 (40.32574999996268, -78.91509999986494)   | Closed between Initiative Kickoff 2/26/2010 and Report 8/3/2012 | 5          | 15          | 
| 1347005038  | Department of Justice | DOJ - 834        | Centennial, CO 80112 (39.57855000018253, -104.87204000004584) | Closed between Initiative Kickoff 2/26/2010 and Report 8/3/2012 | 10         | 20          | 
```