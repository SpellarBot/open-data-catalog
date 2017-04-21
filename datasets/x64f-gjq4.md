# 2015 Spring Festival Applications

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2015-spring-festival-applications) |
| Metadata | [Link](https://data.austintexas.gov/api/views/x64f-gjq4) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/x64f-gjq4/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/x64f-gjq4/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | x64f-gjq4 |
| Name | 2015 Spring Festival Applications |
| Attribution | City of Austin, Austin Center for Events |
| Category | Permitting |
| Tags | temporary permit, temporary event permit, 2015 spring, spring festival, special events, transportation, austin center for events, event, events |
| Created | 2015-02-23T19:46:13Z |
| Publication Date | 2015-02-23T20:23:26Z |

## Description

List of all applications received for temporary events during the 2015 Spring Festival Season (March 9 - 22, 2015).  This list only includes applications and details known at time of submission. It does not reflect if any adjustments or if application has been approved, denied, or withdrawn.

## Columns

```ls
| Included | Schema Type | Field Name       | Name             | Data Type     | Render Type   |
| ======== | =========== | ================ | ================ | ============= | ============= |
| Yes      | series tag  | event_venue_name | Event/Venue Name | text          | text          |
| Yes      | time        | start_date       | Start Date       | calendar_date | calendar_date |
| No       |             | end_date         | End Date         | calendar_date | calendar_date |
| Yes      | series tag  | sxsw             | SXSW             | text          | text          |
| Yes      | series tag  | comments         | COMMENTS         | text          | text          |
```

## Time Field

```ls
Value = start_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = end_date
```

## Data Commands

```ls
series e:x64f-gjq4 d:2015-03-12T17:00:00.000Z t:event_venue_name="ATX Startup Crawl" t:sxsw=NO t:comments="Submitted Application Only - does not reflect if it has been approved, denied or withdrawn." m:row_number.x64f-gjq4=1

series e:x64f-gjq4 d:2015-03-13T12:00:00.000Z t:event_venue_name="SXSW 2015 - Film/Interactive Taco Meetup" t:sxsw=YES t:comments="Submitted Application Only - does not reflect if it has been approved, denied or withdrawn." m:row_number.x64f-gjq4=2

series e:x64f-gjq4 d:2015-03-19T11:00:00.000Z t:event_venue_name="Rooftop Private Event" t:sxsw=NO t:comments="Submitted Application Only - does not reflect if it has been approved, denied or withdrawn." m:row_number.x64f-gjq4=3
```

## Meta Commands

```ls
metric m:row_number.x64f-gjq4 p:long l:"Row Number"

entity e:x64f-gjq4 l:"2015 Spring Festival Applications" t:attribution="City of Austin, Austin Center for Events" t:url=https://data.austintexas.gov/api/views/x64f-gjq4

property e:x64f-gjq4 t:meta.view v:id=x64f-gjq4 v:category=Permitting v:averageRating=0 v:name="2015 Spring Festival Applications" v:attribution="City of Austin, Austin Center for Events"

property e:x64f-gjq4 t:meta.view.owner v:id=jsyn-mk6f v:screenName=jhrncir v:displayName=jhrncir

property e:x64f-gjq4 t:meta.view.tableauthor v:id=jsyn-mk6f v:screenName=jhrncir v:roleName=editor v:displayName=jhrncir
```

## Top Records

```ls
| event_venue_name                         | start_date          | end_date            | sxsw | comments                                                                                    | 
| ======================================== | =================== | =================== | ==== | =========================================================================================== | 
| ATX Startup Crawl                        | 2015-03-12T17:00:00 | 2015-03-12T22:00:00 | NO   | Submitted Application Only - does not reflect if it has been approved, denied or withdrawn. | 
| SXSW 2015 - Film/Interactive Taco Meetup | 2015-03-13T12:00:00 | 2015-03-13T14:00:00 | YES  | Submitted Application Only - does not reflect if it has been approved, denied or withdrawn. | 
| Rooftop Private Event                    | 2015-03-19T11:00:00 | 2015-03-22T22:30:00 | NO   | Submitted Application Only - does not reflect if it has been approved, denied or withdrawn. | 
| SXSWedu Compass Learning Official Party  | 2015-03-10T15:00:00 | 2015-03-10T22:30:00 | YES  | Submitted Application Only - does not reflect if it has been approved, denied or withdrawn. | 
| Gibson Guitar Showroom Events            | 2015-03-12T10:00:00 | 2015-03-21T00:00:00 | NO   | Submitted Application Only - does not reflect if it has been approved, denied or withdrawn. | 
| HI - Austin's Backyard Bash              | 2015-03-21T10:00:00 | 2015-03-21T21:00:00 | NO   | Submitted Application Only - does not reflect if it has been approved, denied or withdrawn. | 
| Mouth By Mouthwest                       | 2015-03-18T18:00:00 | 2015-03-19T22:00:00 | NO   | Submitted Application Only - does not reflect if it has been approved, denied or withdrawn. | 
| Dub Academy Events - SXSW 2015           | 2015-03-18T10:00:00 | 2015-03-22T22:00:00 | NO   | Submitted Application Only - does not reflect if it has been approved, denied or withdrawn. | 
| Yard Dog Parties                         | 2015-03-19T12:00:00 | 2015-03-21T19:00:00 | NO   | Submitted Application Only - does not reflect if it has been approved, denied or withdrawn. | 
| Cenote                                   | 2015-03-14T10:00:00 | 2015-03-17T20:00:00 | NO   | Submitted Application Only - does not reflect if it has been approved, denied or withdrawn. | 
```