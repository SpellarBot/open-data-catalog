# King County Elections Korean Master Calendar

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/king-county-elections-korean-master-calendar) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/urb2-daph) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/urb2-daph/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/urb2-daph/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | urb2-daph |
| Name | King County Elections Korean Master Calendar |
| Attribution | King County Elections |
| Category | Elections |
| Tags | elections; register to vote; vote; voting |
| Created | 2016-08-16T21:24:32Z |
| Publication Date | 2017-03-08T18:37:35Z |

## Columns

```ls
| Included | Schema Type | Field Name                   | Name                         | Data Type | Render Type |
| ======== | =========== | ============================ | ============================ | ========= | =========== |
| Yes      | time        | start_time                   | Start time                   | date      | date        |
| No       |             | end_time                     | End time                     | date      | date        |
| Yes      | series tag  | english_event_name           | English Event Name           | text      | text        |
| Yes      | series tag  | event_name                   | Event Name                   | text      | text        |
| Yes      | series tag  | event_description_details    | Event description/details    | text      | text        |
| Yes      | series tag  | location_name                | Location name                | text      | text        |
| Yes      | series tag  | url                          | URL                          | url       | url         |
| Yes      | series tag  | contact_name                 | Contact name                 | text      | text        |
| Yes      | series tag  | contact_email                | Contact email                | email     | email       |
| Yes      | series tag  | contact_phone                | Contact phone                | text      | text        |
| Yes      | series tag  | host_contact_department      | Host/Contact Department      | text      | text        |
| Yes      | series tag  | feed_keyword_s               | Feed Keyword(s):             | text      | text        |
| Yes      | series tag  | display_on_election_calendar | Display on Election calendar | checkbox  | checkbox    |
| Yes      | series tag  | outreach                     | Outreach                     | checkbox  | checkbox    |
| Yes      | series tag  | registration                 | Registration                 | checkbox  | checkbox    |
```

## Time Field

```ls
Value = start_time
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = end_time
```

## Data Commands

```ls
series e:urb2-daph d:2016-01-01T00:00:00.000Z t:english_event_name="New Years Day holiday closure" t:display_on_election_calendar=true t:registration=true t:event_name="?? ?????" t:outreach=true t:url=http://www.kingcounty.gov/depts/elections/korean/election-dates.aspx m:row_number.urb2-daph=1

series e:urb2-daph d:2016-01-08T08:00:00.000Z t:english_event_name="Overseas and service ballots sent for the February election" t:contact_email=elections@kingcounty.gov t:contact_name="King County Elections" t:contact_phone=206-296-8683 t:display_on_election_calendar=true t:event_name="?? ??? ? ??? ??? 2? ?? ???? ??" t:host_contact_department="King County Elections" t:url=http://www.kingcounty.gov/depts/elections/korean/how-to-vote/ballots/overseas-and-service-voters.aspx m:row_number.urb2-daph=2

series e:urb2-daph d:2016-01-11T08:00:00.000Z t:english_event_name="Voter registration deadline" t:contact_email=elections@kingcounty.gov t:contact_name="King County Elections" t:contact_phone=206-296-8683 t:display_on_election_calendar=true t:registration=true t:event_name="??? ?? ???" t:host_contact_department="King County Elections" t:url=http://kingcounty.gov/depts/elections/korean/how-to-vote/register-to-vote.aspx m:row_number.urb2-daph=3
```

## Meta Commands

```ls
metric m:row_number.urb2-daph p:long l:"Row Number"

entity e:urb2-daph l:"King County Elections Korean Master Calendar" t:attribution="King County Elections" t:url=https://data.kingcounty.gov/api/views/urb2-daph

property e:urb2-daph t:meta.view v:id=urb2-daph v:category=Elections v:attributionLink=http://www.kingcounty.gov/depts/elections.aspx v:averageRating=0 v:name="King County Elections Korean Master Calendar" v:attribution="King County Elections"

property e:urb2-daph t:meta.view.license v:name="Public Domain"

property e:urb2-daph t:meta.view.owner v:id=dqgp-vryk v:screenName=Janice v:displayName=Janice

property e:urb2-daph t:meta.view.tableauthor v:id=dqgp-vryk v:screenName=Janice v:roleName=publisher v:displayName=Janice
```

## Top Records

```ls
| start_time | end_time   | english_event_name                                          | event_name                                     | event_description_details | location_name | url                                                                                                                        | contact_name          | contact_email            | contact_phone | host_contact_department | feed_keyword_s | display_on_election_calendar | outreach | registration | 
| ========== | ========== | =========================================================== | ============================================== | ========================= | ============= | ========================================================================================================================== | ===================== | ======================== | ============= | ======================= | ============== | ============================ | ======== | ============ | 
| 1451606400 | 1451694600 | New Years Day holiday closure                               | ?? ?????                                       |                           |               | [http://www.kingcounty.gov/depts/elections/korean/election-dates.aspx, null]                                               |                       |                          |               |                         |                | true                         | true     | true         | 
| 1452240000 | 1452326340 | Overseas and service ballots sent for the February election | ?? ??? ? ??? ??? 2? ?? ???? ??                 |                           |               | [http://www.kingcounty.gov/depts/elections/korean/how-to-vote/ballots/overseas-and-service-voters.aspx, null]              | King County Elections | elections@kingcounty.gov | 206-296-8683  | King County Elections   |                | true                         |          |              | 
| 1452499200 | 1452585540 | Voter registration deadline                                 | ??? ?? ???                                     |                           |               | [http://kingcounty.gov/depts/elections/korean/how-to-vote/register-to-vote.aspx, null]                                     | King County Elections | elections@kingcounty.gov | 206-296-8683  | King County Elections   |                | true                         |          | true         | 
| 1453104000 | 1453190340 | Martin Luther King, Jr. Day holiday closure                 | ??? ?? ? ??? (Martin Luther King Jr.)?? ??? ?? |                           |               | [http://www.kingcounty.gov/depts/elections/korean/election-dates.aspx, null]                                               |                       |                          |               |                         |                | true                         | true     | true         | 
| 1453276800 | 1453363140 | Ballots mailed for February election                        | 2? ?? ???? ??                                  |                           |               | [http://www.kingcounty.gov/depts/elections/korean/election-dates.aspx, null]                                               | King County Elections | elections@kingcounty.gov | 206-296-8683  | King County Elections   |                | true                         |          |              | 
| 1453363200 | 1453449540 | Ballot drop-off locations open                              | ??? ??                                         |                           |               | [http://kingcounty.gov/depts/elections/korean/how-to-vote/ballots/returning-my-ballot/ballot-dropoff-locations.aspx, null] | King County Elections | elections@kingcounty.gov | 206-296-8683  | King County Elections   |                | true                         |          |              | 
| 1454313600 | 1454399940 | In-person voter registration deadline for new voters        | ??? ??? ?? ?? ???                              |                           |               | [http://kingcounty.gov/depts/elections/korean/how-to-vote/register-to-vote.aspx, null]                                     | King County Elections | elections@kingcounty.gov | 206-296-8683  | King County Elections   |                | true                         |          | true         | 
| 1455004800 | 1455091140 | Election Day                                                | ???                                            |                           |               | [http://www.kingcounty.gov/depts/elections/korean/election-dates.aspx, null]                                               | King County Elections | elections@kingcounty.gov | 206-296-8683  | King County Elections   |                | true                         |          |              | 
| 1455523200 | 1455609540 | President's Day holiday closure                             | ??? ? ? (President's Day)??? ??                |                           |               | [http://www.kingcounty.gov/depts/elections/korean/election-dates.aspx, null]                                               |                       |                          |               |                         |                | true                         | true     | true         | 
| 1455868800 | 1455955140 | February election certified                                 | 2? ?? ??                                       |                           |               | [http://www.kingcounty.gov/depts/elections/korean/election-dates.aspx, null]                                               | King County Elections | elections@kingcounty.gov | 206-296-8683  | King County Elections   |                | true                         |          |              | 
```