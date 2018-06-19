# DEPRECATED Elections master schedule

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/elections-master-schedule-df255) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/exin-fncj) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/exin-fncj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/exin-fncj/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | exin-fncj |
| Name | DEPRECATED Elections master schedule |
| Attribution | King County Elections |
| Category | Election operations |
| Tags | elections, vote, voter, voting, results, canvass board, meeting |
| Created | 2011-09-22T22:59:27Z |
| Publication Date | 2012-05-08T20:41:15Z |

## Description

Master schedule for King County Elections calendar

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type     | Render Type   |
| ======== | ============== | ================== | ================== | ============= | ============= |
| Yes      | time           | date               | Date               | calendar_date | calendar_date |
| Yes      | series tag     | time               | Time               | text          | text          |
| No       |                | end_date           | End date           | text          | text          |
| Yes      | series tag     | scheduleid         | ScheduleID         | text          | text          |
| Yes      | numeric metric | election           | Election           | number        | number        |
| Yes      | series tag     | schedule           | Schedule           | text          | text          |
| Yes      | series tag     | location_name      | Location name      | text          | text          |
| No       |                | location_address   | Location address   | text          | text          |
| Yes      | series tag     | location_city      | Location city      | text          | text          |
| Yes      | series tag     | election_activity  | Election activity  | html          | html          |
| Yes      | series tag     | purpose_of_meeting | Purpose of Meeting | html          | html          |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = end_date,location_address
```

## Data Commands

```ls
series e:exin-fncj d:2011-11-15T16:30:00.000Z t:schedule="Results schedule" t:time="4:30 PM" t:election_activity="Results posted" t:scheduleid=201111results m:election=201111

series e:exin-fncj d:2011-11-29T12:00:00.000Z t:schedule="Results schedule" t:time="12:00 PM" t:election_activity="Final results posted" t:scheduleid=201111results m:election=201111

series e:exin-fncj d:2011-12-16T10:45:00.000Z t:schedule="Canvass board" t:time="10:45 AM" t:election_activity="Canvass Board Meeting" t:location_name="King County Elections" t:scheduleid=201111canvassboard t:purpose_of_meeting="<p><strong>Canvass Board Meeting</strong>: <em>Meeting time changed</em>.Certification of Election Recount</p>" t:location_city=Renton m:election=201111
```

## Meta Commands

```ls
metric m:election p:integer l:Election t:dataTypeName=number

entity e:exin-fncj l:"DEPRECATED Elections master schedule" t:attribution="King County Elections" t:url=https://data.kingcounty.gov/api/views/exin-fncj

property e:exin-fncj t:meta.view v:id=exin-fncj v:category="Election operations" v:attributionLink=http://www.kingcounty.gov/elections v:averageRating=0 v:name="DEPRECATED Elections master schedule" v:attribution="King County Elections"

property e:exin-fncj t:meta.view.license v:name="Public Domain"

property e:exin-fncj t:meta.view.owner v:id=2gzv-6b6z v:profileImageUrlMedium=/api/users/2gzv-6b6z/profile_images/THUMB v:profileImageUrlLarge=/api/users/2gzv-6b6z/profile_images/LARGE v:screenName="King County Webteam" v:profileImageUrlSmall=/api/users/2gzv-6b6z/profile_images/TINY v:displayName="King County Webteam"

property e:exin-fncj t:meta.view.tableauthor v:id=2gzv-6b6z v:profileImageUrlMedium=/api/users/2gzv-6b6z/profile_images/THUMB v:profileImageUrlLarge=/api/users/2gzv-6b6z/profile_images/LARGE v:screenName="King County Webteam" v:profileImageUrlSmall=/api/users/2gzv-6b6z/profile_images/TINY v:roleName=administrator v:displayName="King County Webteam"
```

## Top Records

```ls
| date                | time     | end_date | scheduleid           | election | schedule         | location_name         | location_address | location_city | election_activity                                                       | purpose_of_meeting                                                            | 
| =================== | ======== | ======== | ==================== | ======== | ================ | ===================== | ================ | ============= | ======================================================================= | ============================================================================= | 
| 2011-11-15T16:30:00 | 4:30 PM  |          | 201111results        | 201111   | Results schedule |                       |                  |               | Results posted                                                          |                                                                               | 
| 2011-11-29T12:00:00 | 12:00 PM |          | 201111results        | 201111   | Results schedule |                       |                  |               | Final results posted                                                    |                                                                               | 
| 2011-12-16T10:45:00 | 10:45 AM |          | 201111canvassboard   | 201111   | Canvass board    | King County Elections | 919 SW Grady Way | Renton        | Canvass Board Meeting                                                   | Canvass Board Meeting: Meeting time changed.Certification of Election Recount | 
| 2011-05-14T00:00:00 |          |          |                      |          | Important dates  |                       |                  |               | Last day to publish notice of the May 17 Special Election               |                                                                               | 
| 2011-03-12T00:00:00 |          |          |                      |          | Important dates  |                       |                  |               | Deadline to file a resolution for the April 26 Special Election         |                                                                               | 
| 2011-04-23T00:00:00 |          |          |                      |          | Important dates  |                       |                  |               | Last day to publish notice of the April 26 Special Election             |                                                                               | 
| 2011-05-17T00:00:00 |          |          |                      |          | Important dates  |                       |                  |               | SPECIAL ELECTION                                                        |                                                                               | 
| 2011-09-24T00:00:00 |          |          | 201111importantdates | 201111   | Important dates  |                       |                  |               | Overseas and service ballots mailed for the November 8 General Election |                                                                               | 
| 2011-11-08T00:00:00 |          |          | 201111importantdates | 201111   | Important dates  |                       |                  |               | GENERAL ELECTION                                                        |                                                                               | 
| 2011-09-05T00:00:00 |          |          |                      | 201111   | Important dates  |                       |                  |               | LABOR DAY                                                               |                                                                               | 
```