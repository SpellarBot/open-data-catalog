# King County Elections Chinese Master Calendar

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/king-county-elections-chinese-master-calendar) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/kw8e-ra5v) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/kw8e-ra5v/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/kw8e-ra5v/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | kw8e-ra5v |
| Name | King County Elections Chinese Master Calendar |
| Attribution | King County Elections |
| Category | Elections |
| Created | 2015-12-10T16:32:11Z |
| Publication Date | 2017-03-08T18:39:00Z |

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
series e:kw8e-ra5v d:2016-01-11T08:00:00.000Z t:english_event_name="Voter registration deadline" t:contact_email=elections@kingcounty.gov t:contact_name="King County Elections" t:contact_phone=206-296-8683 t:display_on_election_calendar=true t:registration=true t:event_name=???????? t:host_contact_department="King County Elections" t:url=http://kingcounty.gov/depts/elections/chinese/how-to-vote/register-to-vote.aspx m:row_number.kw8e-ra5v=1

series e:kw8e-ra5v d:2016-01-21T08:00:00.000Z t:english_event_name="Ballot drop-off locations open" t:contact_email=elections@kingcounty.gov t:contact_name="King County Elections" t:contact_phone=206-296-8683 t:display_on_election_calendar=true t:event_name=????????? t:host_contact_department="King County Elections" t:url=http://kingcounty.gov/depts/elections/chinese/how-to-vote/ballots/returning-my-ballot/ballot-dropoff-locations.aspx m:row_number.kw8e-ra5v=2

series e:kw8e-ra5v d:2016-02-01T08:00:00.000Z t:english_event_name="In-person voter registration deadline for new voters" t:contact_email=elections@kingcounty.gov t:contact_name="King County Elections" t:contact_phone=206-296-8683 t:display_on_election_calendar=true t:registration=true t:event_name=?????????????? t:host_contact_department="King County Elections" t:url=http://kingcounty.gov/depts/elections/chinese/how-to-vote/register-to-vote.aspx m:row_number.kw8e-ra5v=3
```

## Meta Commands

```ls
metric m:row_number.kw8e-ra5v p:long l:"Row Number"

entity e:kw8e-ra5v l:"King County Elections Chinese Master Calendar" t:attribution="King County Elections" t:url=https://data.kingcounty.gov/api/views/kw8e-ra5v

property e:kw8e-ra5v t:meta.view v:id=kw8e-ra5v v:category=Elections v:attributionLink=http://www.kingcounty.gov/elections v:averageRating=0 v:name="King County Elections Chinese Master Calendar" v:attribution="King County Elections"

property e:kw8e-ra5v t:meta.view.license v:name="Public Domain U.S. Government" v:termsLink=https://www.usa.gov/government-works

property e:kw8e-ra5v t:meta.view.owner v:id=dqgp-vryk v:screenName=Janice v:displayName=Janice

property e:kw8e-ra5v t:meta.view.tableauthor v:id=dqgp-vryk v:screenName=Janice v:roleName=publisher v:displayName=Janice
```

## Top Records

```ls
| start_time | end_time   | english_event_name                                                                     | event_name          | event_description_details | location_name | url                                                                                                                         | contact_name          | contact_email            | contact_phone | host_contact_department | feed_keyword_s | display_on_election_calendar | outreach | registration | 
| ========== | ========== | ====================================================================================== | =================== | ========================= | ============= | =========================================================================================================================== | ===================== | ======================== | ============= | ======================= | ============== | ============================ | ======== | ============ | 
| 1452499200 | 1452585540 | Voter registration deadline                                                            | ????????            |                           |               | [http://kingcounty.gov/depts/elections/chinese/how-to-vote/register-to-vote.aspx, null]                                     | King County Elections | elections@kingcounty.gov | 206-296-8683  | King County Elections   |                | true                         |          | true         | 
| 1453363200 | 1453449540 | Ballot drop-off locations open                                                         | ?????????           |                           |               | [http://kingcounty.gov/depts/elections/chinese/how-to-vote/ballots/returning-my-ballot/ballot-dropoff-locations.aspx, null] | King County Elections | elections@kingcounty.gov | 206-296-8683  | King County Elections   |                | true                         |          |              | 
| 1454313600 | 1454399940 | In-person voter registration deadline for new voters                                   | ??????????????      |                           |               | [http://kingcounty.gov/depts/elections/chinese/how-to-vote/register-to-vote.aspx, null]                                     | King County Elections | elections@kingcounty.gov | 206-296-8683  | King County Elections   |                | true                         |          | true         | 
| 1459148400 | 1459234740 | Voter registration deadline                                                            | ????????            |                           |               | [http://kingcounty.gov/depts/elections/chinese/how-to-vote/register-to-vote.aspx, null]                                     | King County Elections | elections@kingcounty.gov | 206-296-8683  | King County Elections   |                | true                         |          | true         | 
| 1460012400 | 1460098740 | Ballot drop-off locations open                                                         | ?????????           |                           |               | [http://kingcounty.gov/depts/elections/chinese/how-to-vote/ballots/returning-my-ballot/ballot-dropoff-locations.aspx, null] | King County Elections | elections@kingcounty.gov | 206-296-8683  | King County Elections   |                | true                         |          |              | 
| 1460962800 | 1461049140 | In-person voter registration deadline for new voters                                   | ??????????????      |                           |               | [http://kingcounty.gov/depts/elections/chinese/how-to-vote/register-to-vote.aspx, null]                                     | King County Elections | elections@kingcounty.gov | 206-296-8683  | King County Elections   |                | true                         |          | true         | 
| 1461567600 | 1461653940 | Voter registration deadline for Presidential Primary election                          | ?????????????       |                           |               | [http://kingcounty.gov/depts/elections/chinese/how-to-vote/register-to-vote.aspx, null]                                     | King County Elections | elections@kingcounty.gov | 206-296-8683  | King County Elections   |                | true                         |          | true         | 
| 1462431600 | 1462517940 | Ballot drop-off locations open                                                         | ?????????           |                           |               | [http://kingcounty.gov/depts/elections/chinese/how-to-vote/ballots/returning-my-ballot/ballot-dropoff-locations.aspx, null] | King County Elections | elections@kingcounty.gov | 206-296-8683  | King County Elections   |                | true                         |          |              | 
| 1463382000 | 1463468340 | In-person voter registration deadline for new voters for Presidential Primary election | ??????????????????? |                           |               | [http://kingcounty.gov/depts/elections/chinese/how-to-vote/register-to-vote.aspx, null]                                     | King County Elections | elections@kingcounty.gov | 206-296-8683  | King County Elections   |                | true                         |          | true         | 
| 1467615600 | 1467701940 | Voter registration deadline                                                            | ????????            |                           |               | [http://kingcounty.gov/depts/elections/chinese/how-to-vote/register-to-vote.aspx, null]                                     | King County Elections | elections@kingcounty.gov | 206-296-8683  | King County Elections   |                | true                         |          | true         | 
```