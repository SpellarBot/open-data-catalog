# Special Waste Drop-off Sites

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/special-waste-drop-off-sites-5ab4e) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/a34j-ihvy) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/a34j-ihvy/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/a34j-ihvy/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | a34j-ihvy |
| Name | Special Waste Drop-off Sites |
| Attribution | Department of Sanitation (DSNY) |
| Category | Environment |
| Tags | sanitation, services, waste, drop off, drop-off, dispose, disposal, battery, batteries, oil, motor, filter, tire, transmission, fluid, light, bulb, latex, refuse |
| Created | 2011-10-08T20:13:20Z |
| Publication Date | 2013-06-21T19:43:37Z |

## Description

Addresses and coordinates of each of 5 special waste drop-off sites where New York City residents can dispose of automotive batteries, motor oil, oil filters, passenger car tires, transmission fluids, fluorescent light bulbs, thermostats, household batteries, and latex paint.

## Columns

```ls
| Included | Schema Type | Field Name             | Name                   | Data Type | Render Type |
| ======== | =========== | ====================== | ====================== | ========= | =========== |
| No       | time        | :updated_at            | updated_at             | meta_data | meta_data   |
| Yes      | series tag  | borough                | Borough                | text      | text        |
| Yes      | series tag  | drop_off_site_location | Drop-Off Site Location | text      | text        |
| No       |             | x_coordinate           | X_Coordinate           | number    | number      |
| No       |             | y_coordinate           | Y_Coordinate           | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = x_coordinate,y_coordinate
```

## Data Commands

```ls
series e:a34j-ihvy d:2011-10-08T13:13:21.000Z t:borough=Manhattan t:drop_off_site_location="605 West 30th Street, between 11th and 12th Avenues, opposite Manhattan 6 Garage" m:row_number.a34j-ihvy=1

series e:a34j-ihvy d:2011-10-08T13:13:21.000Z t:borough=Brooklyn t:drop_off_site_location="1824 Shore Parkway, between 25th Avenue and Bay 41st Street, adjacent to Brooklyn South 11 Garage" m:row_number.a34j-ihvy=2

series e:a34j-ihvy d:2011-10-08T13:13:21.000Z t:borough=Queens t:drop_off_site_location="120-15 31st Avenue, College Point, adjacent to Queens East 7 Garage" m:row_number.a34j-ihvy=3
```

## Meta Commands

```ls
metric m:row_number.a34j-ihvy p:long l:"Row Number"

entity e:a34j-ihvy l:"Special Waste Drop-off Sites" t:attribution="Department of Sanitation (DSNY)" t:url=https://data.cityofnewyork.us/api/views/a34j-ihvy

property e:a34j-ihvy t:meta.view v:id=a34j-ihvy v:category=Environment v:averageRating=0 v:name="Special Waste Drop-off Sites" v:attribution="Department of Sanitation (DSNY)"

property e:a34j-ihvy t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:a34j-ihvy t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | borough       | drop_off_site_location                                                                            | x_coordinate | y_coordinate | 
| =========== | ============= | ================================================================================================= | ============ | ============ | 
| 1318079601  | Manhattan     | 605 West 30th Street, between 11th and 12th Avenues, opposite Manhattan 6 Garage                  | 983130.4     | 213727.9     | 
| 1318079601  | Brooklyn      | 1824 Shore Parkway, between 25th Avenue and Bay 41st Street, adjacent to Brooklyn South 11 Garage | 985633.4     | 154770.8     | 
| 1318079601  | Queens        | 120-15 31st Avenue, College Point, adjacent to Queens East 7 Garage                               | 1026496.5    | 220158.6     | 
| 1318079601  | Bronx         | Farragut and Halleck Streets, opposite the Hunts Point Food Cooperative                           | 1018856.6    | 231988.9     | 
| 1318079601  | Staten Island | Foot of Muldoon Avenue, off the West Shore Expressway, adjacent to Staten Island 3 Garage         | 930589.5     | 145667.5     | 
```