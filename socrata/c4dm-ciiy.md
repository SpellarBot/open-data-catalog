# Bike Volume Manual Counts

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/bike-volume-manual-counts) |
| Metadata | [Link](https://data.sfgov.org/api/views/c4dm-ciiy) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/c4dm-ciiy/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/c4dm-ciiy/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | c4dm-ciiy |
| Name | Bike Volume Manual Counts |
| Category | Transportation |
| Tags | bike volume manual counts |
| Created | 2016-04-14T23:36:18Z |
| Publication Date | 2016-04-15T01:45:45Z |

## Description

This dataset was created to show the bike counts from 2009-2014 by observation location (not including the year of 2012). This dataset is manually updated annually. Note: A bicycle count value of ?-1? indicates a null value (bicycle count data was not collected at this location for that year). Bike counts for 2012 are not included in this file, as they are not available/unable to be located.

You can read more including manual count methodology in the latest annual report: https://www.sfmta.com/about-sfmta/reports/city-san-francisco-2015-bicycle-count-report

## Columns

```ls
| Included | Schema Type    | Field Name                | Name                      | Data Type | Render Type |
| ======== | ============== | ========================= | ========================= | ========= | =========== |
| No       | time           | :updated_at               | updated_at                | meta_data | meta_data   |
| Yes      | series tag     | object_id                 | Object ID                 | text      | number      |
| Yes      | series tag     | location_id               | Location ID               | text      | number      |
| Yes      | series tag     | location                  | Location                  | text      | text        |
| Yes      | series tag     | cnn_id                    | CNN ID                    | text      | number      |
| Yes      | numeric metric | bike_count_2006_afternoon | Bike Count 2006 Afternoon | number    | number      |
| Yes      | numeric metric | bike_count_2007_afternoon | Bike Count 2007 Afternoon | number    | number      |
| Yes      | numeric metric | bike_count_2008_afternoon | Bike Count 2008 Afternoon | number    | number      |
| Yes      | numeric metric | bike_count_2009_afternoon | Bike Count 2009 Afternoon | number    | number      |
| Yes      | numeric metric | bike_count_2010_afternoon | Bike Count 2010 Afternoon | number    | number      |
| Yes      | numeric metric | bike_count_2011_afternoon | Bike Count 2011 Afternoon | number    | number      |
| Yes      | numeric metric | bike_count_2013_afternoon | Bike Count 2013 Afternoon | number    | number      |
| Yes      | numeric metric | bike_count_2014_afternoon | Bike Count 2014 Afternoon | number    | number      |
| Yes      | numeric metric | change_2006_to_2007       | Change 2006 to 2007       | number    | number      |
| Yes      | numeric metric | change_2006_to_2008       | Change 2006 to 2008       | number    | number      |
| Yes      | numeric metric | change_2006_to_2009       | Change 2006 to 2009       | number    | number      |
| Yes      | numeric metric | change_2006_to_2010       | Change 2006 to 2010       | number    | number      |
| No       |                | last_edited_date          | Last Edited Date          | date      | date        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = last_edited_date
```

## Data Commands

```ls
series e:c4dm-ciiy d:2017-04-15T16:36:45.000Z t:location="Divisadero and Haight" t:object_id=1 t:cnn_id=26026000 t:location_id=71 m:bike_count_2010_afternoon=-1 m:bike_count_2011_afternoon=-1 m:bike_count_2006_afternoon=-1 m:bike_count_2013_afternoon=-1 m:bike_count_2007_afternoon=-1 m:bike_count_2008_afternoon=-1 m:bike_count_2014_afternoon=84 m:bike_count_2009_afternoon=-1

series e:c4dm-ciiy d:2017-04-15T16:36:45.000Z t:location="Divisadero and McAllister" t:object_id=2 t:cnn_id=26067000 t:location_id=72 m:bike_count_2010_afternoon=-1 m:bike_count_2011_afternoon=-1 m:bike_count_2006_afternoon=-1 m:bike_count_2013_afternoon=-1 m:bike_count_2007_afternoon=-1 m:bike_count_2008_afternoon=-1 m:bike_count_2014_afternoon=289 m:bike_count_2009_afternoon=-1

series e:c4dm-ciiy d:2017-04-15T16:36:45.000Z t:location="Church and Duboce Ave" t:object_id=3 t:cnn_id=25884000 t:location_id=70 m:bike_count_2010_afternoon=-1 m:bike_count_2011_afternoon=-1 m:bike_count_2006_afternoon=-1 m:bike_count_2013_afternoon=-1 m:bike_count_2007_afternoon=-1 m:bike_count_2008_afternoon=-1 m:bike_count_2014_afternoon=816 m:bike_count_2009_afternoon=-1
```

## Meta Commands

```ls
metric m:bike_count_2006_afternoon p:integer l:"Bike Count 2006 Afternoon" t:dataTypeName=number

metric m:bike_count_2007_afternoon p:integer l:"Bike Count 2007 Afternoon" t:dataTypeName=number

metric m:bike_count_2008_afternoon p:integer l:"Bike Count 2008 Afternoon" t:dataTypeName=number

metric m:bike_count_2009_afternoon p:integer l:"Bike Count 2009 Afternoon" t:dataTypeName=number

metric m:bike_count_2010_afternoon p:integer l:"Bike Count 2010 Afternoon" t:dataTypeName=number

metric m:bike_count_2011_afternoon p:integer l:"Bike Count 2011 Afternoon" t:dataTypeName=number

metric m:bike_count_2013_afternoon p:integer l:"Bike Count 2013 Afternoon" t:dataTypeName=number

metric m:bike_count_2014_afternoon p:integer l:"Bike Count 2014 Afternoon" t:dataTypeName=number

metric m:change_2006_to_2007 p:long l:"Change 2006 to 2007" t:dataTypeName=number

metric m:change_2006_to_2008 p:long l:"Change 2006 to 2008" t:dataTypeName=number

metric m:change_2006_to_2009 p:long l:"Change 2006 to 2009" t:dataTypeName=number

metric m:change_2006_to_2010 p:long l:"Change 2006 to 2010" t:dataTypeName=number

entity e:c4dm-ciiy l:"Bike Volume Manual Counts" t:url=https://data.sfgov.org/api/views/c4dm-ciiy

property e:c4dm-ciiy t:meta.view v:id=c4dm-ciiy v:category=Transportation v:averageRating=0 v:name="Bike Volume Manual Counts"

property e:c4dm-ciiy t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:c4dm-ciiy t:meta.view.owner v:id=dbag-6qd9 v:screenName=OpenData v:displayName=OpenData

property e:c4dm-ciiy t:meta.view.tableauthor v:id=dbag-6qd9 v:screenName=OpenData v:roleName=publisher v:displayName=OpenData
```

## Top Records

```ls
| :updated_at | object_id | location_id | location                           | cnn_id   | bike_count_2006_afternoon | bike_count_2007_afternoon | bike_count_2008_afternoon | bike_count_2009_afternoon | bike_count_2010_afternoon | bike_count_2011_afternoon | bike_count_2013_afternoon | bike_count_2014_afternoon | change_2006_to_2007 | change_2006_to_2008 | change_2006_to_2009 | change_2006_to_2010 | last_edited_date | 
| =========== | ========= | =========== | ================================== | ======== | ========================= | ========================= | ========================= | ========================= | ========================= | ========================= | ========================= | ========================= | =================== | =================== | =================== | =================== | ================ | 
| 1492274205  | 1         | 71          | Divisadero and Haight              | 26026000 | -1                        | -1                        | -1                        | -1                        | -1                        | -1                        | -1                        | 84                        |                     |                     |                     |                     |                  | 
| 1492274205  | 2         | 72          | Divisadero and McAllister          | 26067000 | -1                        | -1                        | -1                        | -1                        | -1                        | -1                        | -1                        | 289                       |                     |                     |                     |                     |                  | 
| 1492274205  | 3         | 70          | Church and Duboce Ave              | 25884000 | -1                        | -1                        | -1                        | -1                        | -1                        | -1                        | -1                        | 816                       |                     |                     |                     |                     |                  | 
| 1492274205  | 4         | 89          | Webster and Haight                 | 25898000 | -1                        | -1                        | -1                        | -1                        | -1                        | -1                        | -1                        | 54                        |                     |                     |                     |                     |                  | 
| 1492274205  | 5         | 73          | Fillmore and Haight                | 25899000 | -1                        | -1                        | -1                        | -1                        | -1                        | -1                        | -1                        | 78                        |                     |                     |                     |                     |                  | 
| 1492274205  | 6         | 86          | The Embarcadero North Point Kearny | 25474000 | -1                        | -1                        | -1                        | -1                        | -1                        | -1                        | -1                        | 678                       |                     |                     |                     |                     |                  | 
| 1492274205  | 7         | 82          | Polk and Broadway                  | 25315000 | -1                        | -1                        | -1                        | -1                        | -1                        | -1                        | -1                        | 249                       |                     |                     |                     |                     |                  | 
| 1492274205  | 8         | 88          | Van Ness Ave and Sutter            | 25219000 | -1                        | -1                        | -1                        | -1                        | -1                        | -1                        | -1                        | 96                        |                     |                     |                     |                     |                  | 
| 1492274205  | 9         | 75          | Fremont and Folsom                 | 24498000 | -1                        | -1                        | -1                        | -1                        | -1                        | -1                        | -1                        | 109                       |                     |                     |                     |                     |                  | 
| 1492274205  | 10        | 77          | Mission and 24th                   | 24088000 | -1                        | -1                        | -1                        | -1                        | -1                        | -1                        | -1                        | 144                       |                     |                     |                     |                     |                  | 
```