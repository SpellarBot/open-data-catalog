# NYCHA Facilities and Service Centers

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nycha-facilities-and-service-centers-9f43a) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/d4iy-9uh7) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/d4iy-9uh7/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/d4iy-9uh7/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | d4iy-9uh7 |
| Name | NYCHA Facilities and Service Centers |
| Attribution | New York City Housing Authority (NYCHA) |
| Category | Housing & Development |
| Tags | nycha, nyc housing, developments, buildings, community centers, senior centers, day care centers, 5 boroughs |
| Created | 2013-03-20T14:50:48Z |
| Publication Date | 2016-09-15T22:47:37Z |

## Description

Contains all occupied and vacant facilities portfolio from Facility Planning (commercial spaces) and Community Operations (community centers, senior centers, day care centers, health centers, etc) It includes the 5 Community Operations borough offices.  The source data is our latest Property Directory as December 2012.  The field ?Comments? contains summary codes to distinguish the type of facility (BO ? NYCHA Community Operations Borough Offices, CO ? Community Operations, FP ? Facility Planning).  Please note that there are two commercial spaces (not coded under field ?comments?)recorded in our property directory which are not part of the portfolio for Facility Planning.

## Columns

```ls
| Included | Schema Type | Field Name   | Name             | Data Type | Render Type |
| ======== | =========== | ============ | ================ | ========= | =========== |
| No       | time        | :updated_at  | updated_at       | meta_data | meta_data   |
| Yes      | series tag  | borough_code | BOROUGH_CODE     | text      | text        |
| Yes      | series tag  | development  | DEVELOPMENT NAME | text      | text        |
| No       |             | address      | ADDRESS          | text      | text        |
| Yes      | series tag  | status       | STATUS           | text      | text        |
| Yes      | series tag  | sponsor      | SPONSOR          | text      | text        |
| Yes      | series tag  | zip_code     | ZIP CODE         | text      | number      |
| Yes      | series tag  | type         | TYPE             | text      | text        |
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
series e:d4iy-9uh7 d:2016-09-15T22:47:10.000Z t:zip_code=10460 t:development="(Murphy Consolidated) 1010 East 178th Street" t:status=Occupied t:borough_code=Bronx t:type="Other - Education / GED" t:sponsor="Phipps Community Development" m:row_number.d4iy-9uh7=1

series e:d4iy-9uh7 d:2016-09-15T22:47:10.000Z t:zip_code=10459 t:development="1162 Washington" t:status="Reserved - application on file" t:borough_code=Bronx t:type="Child Care" t:sponsor=NYCHA m:row_number.d4iy-9uh7=2

series e:d4iy-9uh7 d:2016-09-15T22:47:10.000Z t:zip_code=10026 t:development="131 Saint Nicholas Avenue" t:status=Occupied t:borough_code=Manhattan t:type="Child Care - Early Learn" t:sponsor="Citizen's Care Day Care Center, Inc" m:row_number.d4iy-9uh7=3
```

## Meta Commands

```ls
metric m:row_number.d4iy-9uh7 p:long l:"Row Number"

entity e:d4iy-9uh7 l:"NYCHA Facilities and Service Centers" t:attribution="New York City Housing Authority (NYCHA)" t:url=https://data.cityofnewyork.us/api/views/d4iy-9uh7

property e:d4iy-9uh7 t:meta.view v:id=d4iy-9uh7 v:category="Housing & Development" v:attributionLink=http://www.nyc.gov/html/nycha/html/resources/propertyguide.shtml v:averageRating=0 v:name="NYCHA Facilities and Service Centers" v:attribution="New York City Housing Authority (NYCHA)"

property e:d4iy-9uh7 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:d4iy-9uh7 t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | borough_code | development                                  | address                   | status                         | sponsor                                                | zip_code | type                     | 
| =========== | ============ | ============================================ | ========================= | ============================== | ====================================================== | ======== | ======================== | 
| 1473979630  | Bronx        | (Murphy Consolidated) 1010 East 178th Street | 1030 East 178th Street    | Occupied                       | Phipps Community Development                           | 10460    | Other - Education / GED  | 
| 1473979630  | Bronx        | 1162 Washington                              | 1162 Washington Avenue    | Reserved - application on file | NYCHA                                                  | 10459    | Child Care               | 
| 1473979630  | Manhattan    | 131 Saint Nicholas Avenue                    | 131 Saint Nicholas Avenue | Occupied                       | Citizen's Care Day Care Center, Inc                    | 10026    | Child Care - Early Learn | 
| 1473979630  | Manhattan    | 131 Saint Nicholas Avenue                    | 131 Saint Nicholas Avenue | NYCHA HOLD                     | NYCHA                                                  | 10026    | Vacant                   | 
| 1473979630  | Manhattan    | 335 East 111th St (managed by Jefferson)     | 335 East 111th Street     | Occupied                       | Research Foundation of CUNY (Hostos Community College) | 10029    | Other - Jobs Plus        | 
| 1473979630  | Brooklyn     | 572 Warren St                                | 565 Baltic Street         | Occupied                       | Alonzo A. Daughtry Memorial DCC Inc.                   | 11217    | Child Care - UPK 2014    | 
| 1473979630  | Bronx        | Adams                                        | 690 Westchester Avenue    | Occupied                       | Philip Michaels Child Care Center, Inc.                | 10456    | Child Care               | 
| 1473979630  | Bronx        | Adams                                        | 735 East 152nd Street     | Occupied                       | Neighborhood SHOPP                                     | 10455    | Senior Center            | 
| 1473979630  | Bronx        | Adams                                        | 755 East 152nd Street     | Vacant                         | NYCHA                                                  | 10455    | Vacant                   | 
| 1473979630  | Brooklyn     | Albany                                       | 1185 Park Place           | Occupied                       | Brooklyn Kindergarten Society, Inc.                    | 11213    | Child Care - Early Learn | 
```