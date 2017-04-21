# Carver Events 2017

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/carver-events-2017) |
| Metadata | [Link](https://data.austintexas.gov/api/views/su5u-tfet) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/su5u-tfet/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/su5u-tfet/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | su5u-tfet |
| Name | Carver Events 2017 |
| Attribution | City of Austin |
| Created | 2016-12-22T15:42:37Z |
| Publication Date | 2017-03-09T14:21:35Z |

## Description

Event Calendar for Carver Museum

## Columns

```ls
| Included | Schema Type | Field Name        | Name              | Data Type     | Render Type   |
| ======== | =========== | ================= | ================= | ============= | ============= |
| Yes      | time        | date              | Date              | calendar_date | calendar_date |
| Yes      | series tag  | event_or_activity | Event or Activity | text          | text          |
| Yes      | series tag  | location_name     | Location Name     | text          | text          |
| No       |             | time_of_event     | Time of Event     | text          | text          |
| Yes      | series tag  | event_description | Event Description | text          | text          |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = time_of_event
```

## Data Commands

```ls
series e:su5u-tfet d:2016-11-01T00:00:00.000Z t:location_name="Dance Studio" t:event_or_activity="Capoeira for Youth" t:event_description="Every Tuesday, Thursday, and Friday Ages 6-13yrs 4:30pm-5:30pm  $55 per month  For more information call (512) 636-8665;  to register online austintexas.gov/parksonline" m:row_number.su5u-tfet=1

series e:su5u-tfet d:2016-11-03T00:00:00.000Z t:location_name="Dance Studio" t:event_or_activity="Capoeira for Youth" t:event_description="Every Tuesday, Thursday, and Friday Ages 6-13yrs 4:30pm-5:30pm  $55 per month  For more information call (512) 636-8665;  to register online austintexas.gov/parksonline" m:row_number.su5u-tfet=2

series e:su5u-tfet d:2016-11-04T00:00:00.000Z t:location_name="Dance Studio" t:event_or_activity="Capoeira for Youth" t:event_description="Every Tuesday, Thursday, and Friday Ages 6-13yrs 4:30pm-5:30pm  $55 per month  For more information call (512) 636-8665;  to register online austintexas.gov/parksonline" m:row_number.su5u-tfet=3
```

## Meta Commands

```ls
metric m:row_number.su5u-tfet p:long l:"Row Number"

entity e:su5u-tfet l:"Carver Events 2017" t:attribution="City of Austin" t:url=https://data.austintexas.gov/api/views/su5u-tfet

property e:su5u-tfet t:meta.view v:id=su5u-tfet v:attributionLink=http://www.austintexas.gov/page/carver-museum-programs v:averageRating=0 v:name="Carver Events 2017" v:attribution="City of Austin"

property e:su5u-tfet t:meta.view.license v:name="Public Domain"

property e:su5u-tfet t:meta.view.owner v:id=wpqw-45f6 v:screenName=Betty v:displayName=Betty

property e:su5u-tfet t:meta.view.tableauthor v:id=wpqw-45f6 v:screenName=Betty v:roleName=editor v:displayName=Betty
```

## Top Records

```ls
| date                | event_or_activity                    | location_name      | time_of_event  | event_description                                                                                                                                                                                                                                                                                                                                                                  | 
| =================== | ==================================== | ================== | ============== | ================================================================================================================================================================================================================================================================================================================================================================================== | 
| 2016-11-01T00:00:00 | Capoeira for Youth                   | Dance Studio       | 4:30pm-5:30pm  | Every Tuesday, Thursday, and Friday Ages 6-13yrs 4:30pm-5:30pm $55 per month For more information call (512) 636-8665; to register online austintexas.gov/parksonline                                                                                                                                                                                                              | 
| 2016-11-03T00:00:00 | Capoeira for Youth                   | Dance Studio       | 4:30pm-5:30pm  | Every Tuesday, Thursday, and Friday Ages 6-13yrs 4:30pm-5:30pm $55 per month For more information call (512) 636-8665; to register online austintexas.gov/parksonline                                                                                                                                                                                                              | 
| 2016-11-04T00:00:00 | Capoeira for Youth                   | Dance Studio       | 4:30pm-5:30pm  | Every Tuesday, Thursday, and Friday Ages 6-13yrs 4:30pm-5:30pm $55 per month For more information call (512) 636-8665; to register online austintexas.gov/parksonline                                                                                                                                                                                                              | 
| 2016-11-07T00:00:00 | Capoeira for Youth                   | Dance Studio       | 4:30pm-5:30pm  | Every Tuesday, Thursday, and Friday Ages 6-13yrs 4:30pm-5:30pm $55 per month For more information call (512) 636-8665; to register online austintexas.gov/parksonline                                                                                                                                                                                                              | 
| 2016-11-08T00:00:00 | Capoeira for Youth                   | Dance Studio       | 4:30pm-5:30pm  | Every Tuesday, Thursday, and Friday Ages 6-13yrs 4:30pm-5:30pm $55 per month For more information call (512) 636-8665; to register online austintexas.gov/parksonline                                                                                                                                                                                                              | 
| 2016-11-10T00:00:00 | Capoeira for Youth                   | Dance Studio       | 4:30pm-5:30pm  | Every Tuesday, Thursday, and Friday Ages 6-13yrs 4:30pm-5:30pm $55 per month For more information call (512) 636-8665; to register online austintexas.gov/parksonline                                                                                                                                                                                                              | 
| 2016-11-10T00:00:00 | Afterworld Equations Exhibit Opening | Carver Museum      | 6:30pm-8:30pm  | Afterworld Equations Exhibit opening artist Kel Brown. Kel Brown produces works with rare sonic texture that explores the relationship between sound and art. Exhibit run November 10th, 2016-January 21, 2017                                                                                                                                                                     | 
| 2016-11-11T00:00:00 | Carver Museum Closed                 | Carver Museum      | 10:00am-6:00pm | Closed for Veteran's Day                                                                                                                                                                                                                                                                                                                                                           | 
| 2016-11-12T00:00:00 | 2nd Sunday Playing for Keeps         | Boyd Vance Theatre | 6pm            | Based on the novel written by Author Tanisha Smith. 2nd Sunday Playing for Keeps, takes you on a roller coaster ride of a tale of friends, betrayal, lies, lies and more lies. How far would you go to keep the love of your life from leaving you? Stage play written, directed and produced by Ms. Tawanna I. Jackson. Tickets $20; tickets available from www.shesmilesent.com. | 
| 2016-11-13T00:00:00 | 3rd Sunday Playing for Keeps         | Boyd Vance Theatre | 4pm            | Based on the novel written by Author Tanisha Smith. 2nd Sunday Playing for Keeps, takes you on a roller coaster ride of a tale of friends, betrayal, lies, lies and more lies. How far would you go to keep the love of your life from leaving you? Stage play written, directed and produced by Ms. Tawanna I. Jackson. Tickets $20; tickets available from www.shesmilesent.com. | 
```