# NYCHA Citywide Special Events

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nycha-citywide-special-events-af2da) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/7iqz-npua) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/7iqz-npua/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/7iqz-npua/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 7iqz-npua |
| Name | NYCHA Citywide Special Events |
| Attribution | New York City Housing Authority (NYCHA) |
| Category | Recreation |
| Tags | nycha, nyc housing, events for residents, childrens events, senior events, community events |
| Created | 2013-03-28T19:31:00Z |
| Publication Date | 2016-08-16T22:23:56Z |

## Description

It contains the special events hosted by NYCHA

## Columns

```ls
| Included | Schema Type    | Field Name | Name       | Data Type     | Render Type   |
| ======== | ============== | ========== | ========== | ============= | ============= |
| Yes      | numeric metric | recurrence | Recurrence | number        | text          |
| Yes      | series tag     | title      | Title      | text          | text          |
| Yes      | series tag     | location   | Location   | text          | text          |
| Yes      | time           | start_time | Start Time | calendar_date | calendar_date |
```

## Time Field

```ls
Value = start_time
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:7iqz-npua d:2013-12-18T18:00:00.000Z t:title="NYCHA's 2013 Holiday Party" t:location="Surrogate's Court" m:recurrence=0

series e:7iqz-npua d:2014-01-08T00:00:00.000Z t:title="NYCHA Resident Training Academy Janitorial Session" t:location="REES Offices, 787 Atlantic Ave., Brooklyn" m:recurrence=0

series e:7iqz-npua d:2014-01-14T11:00:00.000Z t:title="REES/Green City Force Information Session" t:location="REES Offices, 787 Atlantic Ave., Brooklyn" m:recurrence=0
```

## Meta Commands

```ls
metric m:recurrence p:integer l:Recurrence t:dataTypeName=number

entity e:7iqz-npua l:"NYCHA Citywide Special Events" t:attribution="New York City Housing Authority (NYCHA)" t:url=https://data.cityofnewyork.us/api/views/7iqz-npua

property e:7iqz-npua t:meta.view v:id=7iqz-npua v:category=Recreation v:averageRating=0 v:name="NYCHA Citywide Special Events" v:attribution="New York City Housing Authority (NYCHA)"

property e:7iqz-npua t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:7iqz-npua t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| recurrence | title                                                  | location                                            | start_time          | 
| ========== | ====================================================== | =================================================== | =================== | 
| 0          | NYCHA's 2013 Holiday Party                             | Surrogate's Court                                   | 2013-12-18T18:00:00 | 
| 0          | NYCHA Resident Training Academy Janitorial Session     | REES Offices, 787 Atlantic Ave., Brooklyn           | 2014-01-08T00:00:00 | 
| 0          | REES/Green City Force Information Session              | REES Offices, 787 Atlantic Ave., Brooklyn           | 2014-01-14T11:00:00 | 
| 0          | NYCHA Resident Training Academy Janitorial Session     | REES Offices, 787 Atlantic Ave., Brooklyn           | 2014-02-05T08:30:00 | 
| 0          | NYCHA's Black History Month                            | 90 Church Street-5th floor Ceremonial Room          | 2014-02-11T17:30:00 | 
| 0          | NYCHA Resident Training Academy Janitorial Session     | REES Offices, 787 Atlantic Ave., Brooklyn           | 2014-02-12T08:30:00 | 
| 0          | Presidents Day & Washington's Birthday (Office Closed) |                                                     | 2014-02-17T00:00:00 | 
| 0          | Talent Show Rehearsal                                  | Straus Performing Arts Center, 225 E. 27th St., NYC | 2014-03-18T16:00:00 | 
| 0          | Talent Show Rehearsals                                 | Straus Performing Arts Center, 225 E. 27th St., NYC | 2014-03-20T16:00:00 | 
| 0          | City Council Hearing on NYCHA Budget                   | City Hall Committee Room, NYC                       | 2014-03-21T10:00:00 | 
```