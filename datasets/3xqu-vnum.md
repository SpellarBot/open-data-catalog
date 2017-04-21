# Seattle Crime Stats by Police Precinct 2008-Present

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/seattle-crime-stats-by-police-precinct-2008-present-01721) |
| Metadata | [Link](https://data.seattle.gov/api/views/3xqu-vnum) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/3xqu-vnum/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/3xqu-vnum/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | 3xqu-vnum |
| Name | Seattle Crime Stats by Police Precinct 2008-Present |
| Attribution | City of Seattle, Department of Information Technology |
| Category | Public Safety |
| Tags | crime, violent, seattle, police |
| Created | 2009-11-23T20:11:34Z |
| Publication Date | 2014-07-21T21:43:31Z |

## Description

Seattle Part 1 Crime stats by precinct The precinct and beat data can be found at http://data.seattle.gov/Government/Seattle-Police-Department-Beats/nnxn-434b

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type     | Render Type   |
| ======== | ============== | ================= | ================= | ============= | ============= |
| Yes      | series tag     | police_beat       | Police Beat       | text          | text          |
| Yes      | series tag     | crime_type        | CRIME_TYPE        | text          | text          |
| Yes      | series tag     | crime_description | CRIME_DESCRIPTION | text          | text          |
| Yes      | numeric metric | stat_value        | STAT_VALUE        | number        | number        |
| Yes      | time           | report_date       | REPORT_DATE       | calendar_date | calendar_date |
| Yes      | series tag     | sector            | Sector            | text          | text          |
| Yes      | series tag     | precinct          | Precinct          | text          | text          |
| Yes      | series tag     | row_value_id      | Row_Value_ID      | text          | number        |
```

## Time Field

```ls
Value = report_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:3xqu-vnum d:2008-01-01T00:00:00.000Z t:precinct=N t:sector=B t:crime_type=Homicide t:police_beat=B1 t:row_value_id=1 t:crime_description=Homicide m:stat_value=0

series e:3xqu-vnum d:2008-01-01T00:00:00.000Z t:precinct=N t:sector=B t:crime_type=Rape t:police_beat=B1 t:row_value_id=2 t:crime_description=Rape m:stat_value=0

series e:3xqu-vnum d:2008-01-01T00:00:00.000Z t:precinct=N t:sector=B t:crime_type=Robbery t:police_beat=B1 t:row_value_id=3 t:crime_description=Robbery m:stat_value=5
```

## Meta Commands

```ls
metric m:stat_value p:integer l:STAT_VALUE d:"Number of times crime occurred in a beat for reported month" t:dataTypeName=number

entity e:3xqu-vnum l:"Seattle Crime Stats by Police Precinct 2008-Present" t:attribution="City of Seattle, Department of Information Technology" t:url=https://data.seattle.gov/api/views/3xqu-vnum

property e:3xqu-vnum t:meta.view v:id=3xqu-vnum v:category="Public Safety" v:attributionLink=http://seattle.gov/police/crime/default.htm v:averageRating=0 v:name="Seattle Crime Stats by Police Precinct 2008-Present" v:attribution="City of Seattle, Department of Information Technology"

property e:3xqu-vnum t:meta.view.license v:name="Public Domain"

property e:3xqu-vnum t:meta.view.owner v:id=pfbu-yuv5 v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:screenName="Seattle IT" v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:displayName="Seattle IT"

property e:3xqu-vnum t:meta.view.tableauthor v:id=pfbu-yuv5 v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:screenName="Seattle IT" v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:roleName=administrator v:displayName="Seattle IT"
```

## Top Records

```ls
| police_beat | crime_type          | crime_description                                                        | stat_value | report_date         | sector | precinct | row_value_id | 
| =========== | =================== | ======================================================================== | ========== | =================== | ====== | ======== | ============ | 
| B1          | Homicide            | Homicide                                                                 | 0          | 2008-01-01T00:00:00 | B      | N        | 1            | 
| B1          | Rape                | Rape                                                                     | 0          | 2008-01-01T00:00:00 | B      | N        | 2            | 
| B1          | Robbery             | Robbery                                                                  | 5          | 2008-01-01T00:00:00 | B      | N        | 3            | 
| B1          | Assault             | Assault                                                                  | 1          | 2008-01-01T00:00:00 | B      | N        | 4            | 
| B1          | Larceny-Theft       | Larceny-Theft                                                            | 35         | 2008-01-01T00:00:00 | B      | N        | 5            | 
| B1          | Motor Vehicle Theft | Vehicle Theft is theft of a car, truck, motorcycle or any motor vehicle. | 4          | 2008-01-01T00:00:00 | B      | N        | 6            | 
| B1          | Burglary            | Burglary                                                                 | 15         | 2008-01-01T00:00:00 | B      | N        | 7            | 
| B2          | Homicide            | Homicide                                                                 | 0          | 2008-01-01T00:00:00 | B      | N        | 8            | 
| B2          | Rape                | Rape                                                                     | 0          | 2008-01-01T00:00:00 | B      | N        | 9            | 
| B2          | Robbery             | Robbery                                                                  | 2          | 2008-01-01T00:00:00 | B      | N        | 10           | 
```