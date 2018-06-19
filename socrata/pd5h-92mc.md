# GED Plus Locations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ged-plus-locations-4164c) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/pd5h-92mc) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/pd5h-92mc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/pd5h-92mc/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | pd5h-92mc |
| Name | GED Plus Locations |
| Attribution | Department of Education (DOE) |
| Category | Social Services |
| Tags | ged plus locations, doe, education, jobs and economic mobility |
| Created | 2013-03-19T20:38:38Z |
| Publication Date | 2013-03-19T20:41:16Z |

## Description

Listing of GED Plus locations. GED plus helps students earn their GED and prepares them for college and career options.

## Columns

```ls
| Included | Schema Type | Field Name        | Name              | Data Type | Render Type |
| ======== | =========== | ================= | ================= | ========= | =========== |
| No       | time        | :updated_at       | updated_at        | meta_data | meta_data   |
| Yes      | series tag  | program_site_name | Program Site name | text      | text        |
| No       |             | address           | Address           | text      | text        |
| Yes      | series tag  | borough           | Borough           | text      | text        |
| Yes      | series tag  | contact_number    | Contact Number    | text      | text        |
| Yes      | series tag  | notes             | Notes             | text      | text        |
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
series e:pd5h-92mc d:2013-03-19T13:38:40.000Z t:contact_number=718-842-9200 t:program_site_name="Bronx GED Plus Hub/Referral Center at Bronx Regional High School" t:borough=Bronx m:row_number.pd5h-92mc=1

series e:pd5h-92mc d:2013-03-19T13:38:40.000Z t:contact_number=718-289-5852 t:program_site_name="GED Plus at Bronx Community College Future Now" t:borough=Bronx m:row_number.pd5h-92mc=2

series e:pd5h-92mc d:2013-03-19T13:38:40.000Z t:contact_number="718-584-9000, ext. 5059" t:program_site_name="GED Plus at Bronx VA Medical Center" t:borough=Bronx m:row_number.pd5h-92mc=3
```

## Meta Commands

```ls
metric m:row_number.pd5h-92mc p:long l:"Row Number"

entity e:pd5h-92mc l:"GED Plus Locations" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/pd5h-92mc

property e:pd5h-92mc t:meta.view v:id=pd5h-92mc v:category="Social Services" v:averageRating=0 v:name="GED Plus Locations" v:attribution="Department of Education (DOE)"

property e:pd5h-92mc t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:pd5h-92mc t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | program_site_name                                                | address                          | borough | contact_number          | notes                                           | 
| =========== | ================================================================ | ================================ | ======= | ======================= | =============================================== | 
| 1363700320  | Bronx GED Plus Hub/Referral Center at Bronx Regional High School | 1010 Rev. James Polite Avenue    | Bronx   | 718-842-9200            |                                                 | 
| 1363700320  | GED Plus at Bronx Community College Future Now                   | 2155 University Avenue           | Bronx   | 718-289-5852            |                                                 | 
| 1363700320  | GED Plus at Bronx VA Medical Center                              | 130 West Kingsbridge Road Bronx, | Bronx   | 718-584-9000, ext. 5059 |                                                 | 
| 1363700320  | GED Plus at Davidson Avenue                                      | 1732 Davidson Avenue             | Bronx   | 718-299-5926            |                                                 | 
| 1363700320  | GED Plus at DeWitt Clinton High School                           | 100 West Mosholu Parkway South   | Bronx   | 718-543-1000            | x ELL Services: ESL, Bilingual Program: Spanish | 
| 1363700320  | GED Plus at Mary Mitchell Family & Children's Center             | 2007 Mapes Avenue                | Bronx   | 718-583-1765            |                                                 | 
| 1363700320  | GED Plus at North Central Bronx Hospital                         | 3424 Kossuth Avenue, 14          | Bronx   | 718-519-4816            | 14th floor                                      | 
| 1363700320  | GED Plus at New Settlement Apartments I                          | 1525 Walton Avenue               | Bronx   | 718-716-8000, ext. 232  |                                                 | 
| 1363700320  | GED Plus at New Settlement Apartments II                         | 1614 Walton Avenue               | Bronx   | 718-450-8466            |                                                 | 
| 1363700320  | GED Plus at Project Ready                                        | 55 East 175th Street             | Bronx   | 718-466-3600            |                                                 | 
```