# Public Building Commission - Event Permits

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/public-building-commission-event-permits-69f94) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/knv6-r5ad) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/knv6-r5ad/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/knv6-r5ad/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | knv6-r5ad |
| Name | Public Building Commission - Event Permits |
| Attribution | Public Building Commission |
| Category | Events |
| Tags | permits |
| Created | 2012-01-14T02:56:23Z |
| Publication Date | 2017-04-19T20:47:56Z |

## Description

This dataset includes applications for use of Daley Center Plaza, starting in 2012. The data includes the name of the requesting organization, the date each permit was requested and its status.  A copy of the Regulations and Procedures for the Daley Plaza can be downloaded at: http://www.pbcchicago.com/content/contact/location_map.asp.

## Columns

```ls
| Included | Schema Type | Field Name         | Name               | Data Type     | Render Type   |
| ======== | =========== | ================== | ================== | ============= | ============= |
| Yes      | time        | date_received      | Date Received      | calendar_date | calendar_date |
| Yes      | series tag  | requestor          | Requestor          | text          | text          |
| Yes      | series tag  | event_location     | Event Location     | text          | text          |
| No       |             | event_date         | Event Start Date   | calendar_date | calendar_date |
| No       |             | event_end_date     | Event End Date     | calendar_date | calendar_date |
| Yes      | series tag  | permit_status      | Permit Status      | text          | text          |
| Yes      | series tag  | approved_or_denied | Approved or Denied | text          | text          |
```

## Time Field

```ls
Value = date_received
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = event_date,event_end_date
```

## Data Commands

```ls
series e:knv6-r5ad d:2012-01-01T00:00:00.000Z t:approved_or_denied=Withdrew t:event_location="Daley Center" t:requestor="Coalition Against NATO/G8 War & Poverty Agenda" m:row_number.knv6-r5ad=1

series e:knv6-r5ad d:2012-01-04T00:00:00.000Z t:approved_or_denied=Approved t:event_location="Daley Center" t:requestor="National Nurses United" m:row_number.knv6-r5ad=2

series e:knv6-r5ad d:2012-01-05T00:00:00.000Z t:approved_or_denied=Withdrew t:event_location="Daley Center" t:requestor="Illinois Policy Institute" m:row_number.knv6-r5ad=3
```

## Meta Commands

```ls
metric m:row_number.knv6-r5ad p:long l:"Row Number"

entity e:knv6-r5ad l:"Public Building Commission - Event Permits" t:attribution="Public Building Commission" t:url=https://data.cityofchicago.org/api/views/knv6-r5ad

property e:knv6-r5ad t:meta.view v:id=knv6-r5ad v:category=Events v:attributionLink=http://www.thedaleycenter.com/events.asp v:averageRating=0 v:name="Public Building Commission - Event Permits" v:attribution="Public Building Commission"

property e:knv6-r5ad t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:knv6-r5ad t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```

## Top Records

```ls
| date_received       | requestor                                      | event_location | event_date          | event_end_date      | permit_status | approved_or_denied | 
| =================== | ============================================== | ============== | =================== | =================== | ============= | ================== | 
| 2012-01-01T00:00:00 | Coalition Against NATO/G8 War & Poverty Agenda | Daley Center   | 2012-05-19T00:00:00 | 2012-05-19T00:00:00 |               | Withdrew           | 
| 2012-01-04T00:00:00 | National Nurses United                         | Daley Center   | 2012-05-18T00:00:00 | 2012-05-18T00:00:00 |               | Approved           | 
| 2012-01-05T00:00:00 | Illinois Policy Institute                      | Daley Center   | 2012-01-11T00:00:00 | 2012-01-11T00:00:00 |               | Withdrew           | 
| 2012-01-09T00:00:00 | Tribeca Flashpoint Media Arts Academy          | Daley Center   | 2012-01-12T00:00:00 | 2012-01-12T00:00:00 |               | Withdrew           | 
| 2012-01-09T00:00:00 | Northern Illinois United Methodist Women       | Daley Center   | 2012-01-30T00:00:00 | 2012-01-30T00:00:00 |               | Approved           | 
| 2012-01-18T00:00:00 | City Year Chicago                              | Daley Center   | 2012-01-20T00:00:00 | 2012-01-20T00:00:00 |               | Approved           | 
| 2012-01-31T00:00:00 | Navy Pier, Inc.                                | Daley Center   | 2012-02-02T00:00:00 | 2012-03-16T00:00:00 |               | Approved           | 
| 2012-01-31T00:00:00 | NBC/Shed Media USA                             | Daley Center   | 2012-02-22T00:00:00 | 2012-02-22T00:00:00 |               | Withdrew           | 
| 2012-02-02T00:00:00 | Citizen's Official Services                    | Daley Center   | 2012-03-30T00:00:00 | 2012-03-31T00:00:00 |               | Approved           | 
| 2012-02-02T00:00:00 | Rape Victim Advocates                          | Daley Center   | 2012-04-27T00:00:00 | 2012-04-27T00:00:00 |               | Approved           | 
```