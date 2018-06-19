# King County Elections Master Calendar

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/king-county-elections-master-calendar) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/wkud-5sdw) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/wkud-5sdw/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/wkud-5sdw/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | wkud-5sdw |
| Name | King County Elections Master Calendar |
| Attribution | King County Elections |
| Category | Elections |
| Tags | elections, election results, voter registration, vote |
| Created | 2015-12-07T23:22:49Z |
| Publication Date | 2017-04-19T16:18:08Z |

## Description

King County Elections master calendar

## Columns

```ls
| Included | Schema Type | Field Name                   | Name                         | Data Type | Render Type |
| ======== | =========== | ============================ | ============================ | ========= | =========== |
| Yes      | time        | start_time                   | Start time                   | date      | date        |
| No       |             | end_time                     | End time                     | date      | date        |
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
| Yes      | series tag  | candidates                   | Candidates                   | checkbox  | checkbox    |
| Yes      | series tag  | canvassing_board             | Canvassing Board             | checkbox  | checkbox    |
| Yes      | series tag  | jurisdictions                | Jurisdictions                | checkbox  | checkbox    |
| Yes      | series tag  | observation                  | Observation                  | checkbox  | checkbox    |
| Yes      | series tag  | outreach                     | Outreach                     | checkbox  | checkbox    |
| Yes      | series tag  | registration                 | Registration                 | checkbox  | checkbox    |
| Yes      | series tag  | results                      | Results                      | checkbox  | checkbox    |
| Yes      | series tag  | february_election            | February election            | checkbox  | checkbox    |
| Yes      | series tag  | april_election               | April election               | checkbox  | checkbox    |
| Yes      | series tag  | other_election               | Other election               | checkbox  | checkbox    |
| Yes      | series tag  | primary_election             | Primary election             | checkbox  | checkbox    |
| Yes      | series tag  | general_election             | General election             | checkbox  | checkbox    |
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
series e:wkud-5sdw d:2016-01-11T08:00:00.000Z t:contact_email=elections@kingcounty.gov t:february_election=true t:contact_phone=206-296-8683 t:contact_name="King County Elections" t:display_on_election_calendar=true t:registration=true t:event_name="Voter registration deadline" t:url=http://kingcounty.gov/depts/elections/how-to-vote/register-to-vote.aspx t:host_contact_department="King County Elections" m:row_number.wkud-5sdw=1

series e:wkud-5sdw d:2016-02-01T08:00:00.000Z t:contact_email=elections@kingcounty.gov t:february_election=true t:contact_phone=206-296-8683 t:contact_name="King County Elections" t:display_on_election_calendar=true t:registration=true t:event_name="In-person voter registration deadline for new voters" t:url=http://kingcounty.gov/depts/elections/how-to-vote/register-to-vote.aspx t:host_contact_department="King County Elections" m:row_number.wkud-5sdw=2

series e:wkud-5sdw d:2016-03-28T07:00:00.000Z t:contact_email=elections@kingcounty.gov t:contact_phone=206-296-8683 t:contact_name="King County Elections" t:display_on_election_calendar=true t:registration=true t:event_name="Voter registration deadline" t:url=http://kingcounty.gov/depts/elections/how-to-vote/register-to-vote.aspx t:host_contact_department="King County Elections" t:april_election=true m:row_number.wkud-5sdw=3
```

## Meta Commands

```ls
metric m:row_number.wkud-5sdw p:long l:"Row Number"

entity e:wkud-5sdw l:"King County Elections Master Calendar" t:attribution="King County Elections" t:url=https://data.kingcounty.gov/api/views/wkud-5sdw

property e:wkud-5sdw t:meta.view v:id=wkud-5sdw v:category=Elections v:attributionLink=http://www.kingcounty.gov/elections v:averageRating=0 v:name="King County Elections Master Calendar" v:attribution="King County Elections"

property e:wkud-5sdw t:meta.view.license v:name="Public Domain U.S. Government" v:termsLink=https://www.usa.gov/government-works

property e:wkud-5sdw t:meta.view.owner v:id=dqgp-vryk v:screenName=Janice v:displayName=Janice

property e:wkud-5sdw t:meta.view.tableauthor v:id=dqgp-vryk v:screenName=Janice v:roleName=publisher v:displayName=Janice
```

## Top Records

```ls
| start_time | end_time   | event_name                                                                             | event_description_details | location_name | url                                                                             | contact_name          | contact_email            | contact_phone | host_contact_department | feed_keyword_s | display_on_election_calendar | candidates | canvassing_board | jurisdictions | observation | outreach | registration | results | february_election | april_election | other_election | primary_election | general_election | 
| ========== | ========== | ====================================================================================== | ========================= | ============= | =============================================================================== | ===================== | ======================== | ============= | ======================= | ============== | ============================ | ========== | ================ | ============= | =========== | ======== | ============ | ======= | ================= | ============== | ============== | ================ | ================ | 
| 1452499200 | 1452585540 | Voter registration deadline                                                            |                           |               | [http://kingcounty.gov/depts/elections/how-to-vote/register-to-vote.aspx, null] | King County Elections | elections@kingcounty.gov | 206-296-8683  | King County Elections   |                | true                         |            |                  |               |             |          | true         |         | true              |                |                |                  |                  | 
| 1454313600 | 1454399940 | In-person voter registration deadline for new voters                                   |                           |               | [http://kingcounty.gov/depts/elections/how-to-vote/register-to-vote.aspx, null] | King County Elections | elections@kingcounty.gov | 206-296-8683  | King County Elections   |                | true                         |            |                  |               |             |          | true         |         | true              |                |                |                  |                  | 
| 1459148400 | 1459234740 | Voter registration deadline                                                            |                           |               | [http://kingcounty.gov/depts/elections/how-to-vote/register-to-vote.aspx, null] | King County Elections | elections@kingcounty.gov | 206-296-8683  | King County Elections   |                | true                         |            |                  |               |             |          | true         |         |                   | true           |                |                  |                  | 
| 1460962800 | 1461049140 | In-person voter registration deadline for new voters                                   |                           |               | [http://kingcounty.gov/depts/elections/how-to-vote/register-to-vote.aspx, null] | King County Elections | elections@kingcounty.gov | 206-296-8683  | King County Elections   |                | true                         |            |                  |               |             |          | true         |         |                   | true           |                |                  |                  | 
| 1461567600 | 1461653940 | Voter registration deadline for Presidential Primary election                          |                           |               | [http://kingcounty.gov/depts/elections/how-to-vote/register-to-vote.aspx, null] | King County Elections | elections@kingcounty.gov | 206-296-8683  | King County Elections   |                | true                         |            |                  |               |             |          | true         |         |                   |                | true           |                  |                  | 
| 1463382000 | 1463468340 | Candidate filing begins                                                                |                           |               | [http://kingcounty.gov/depts/elections/for-candidates/running-for-office, null] | King County Elections | elections@kingcounty.gov | 206-296-8683  | King County Elections   |                | true                         | true       |                  |               |             |          |              |         |                   |                |                |                  |                  | 
| 1463727600 | 1463813940 | Candidate filing ends                                                                  |                           |               | [http://kingcounty.gov/depts/elections/for-candidates/running-for-office, null] | King County Elections | elections@kingcounty.gov | 206-296-8683  | King County Elections   |                | true                         | true       |                  |               |             |          |              |         |                   |                |                |                  |                  | 
| 1463986800 | 1464073140 | Last day for candidates to withdraw                                                    |                           |               | [http://kingcounty.gov/depts/elections/for-candidates/running-for-office, null] | King County Elections | elections@kingcounty.gov | 206-296-8683  | King County Elections   |                | true                         | true       |                  |               |             |          |              |         |                   |                |                |                  |                  | 
| 1463382000 | 1463468340 | In-person voter registration deadline for new voters for Presidential Primary election |                           |               | [http://kingcounty.gov/depts/elections/how-to-vote/register-to-vote.aspx, null] | King County Elections | elections@kingcounty.gov | 206-296-8683  | King County Elections   |                | true                         |            |                  |               |             |          | true         |         |                   |                | true           |                  |                  | 
| 1467615600 | 1467701940 | Voter registration deadline                                                            |                           |               | [http://kingcounty.gov/depts/elections/how-to-vote/register-to-vote.aspx, null] | King County Elections | elections@kingcounty.gov | 206-296-8683  | King County Elections   |                | true                         |            |                  |               |             |          | true         |         |                   |                |                | true             |                  | 
```