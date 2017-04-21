# King County Elections Vietnamese Master Calendar

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/king-county-elections-vietnamese-master-calendar) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/yhm4-4y8s) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/yhm4-4y8s/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/yhm4-4y8s/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | yhm4-4y8s |
| Name | King County Elections Vietnamese Master Calendar |
| Attribution | King County Elections |
| Category | Elections |
| Created | 2015-12-10T17:00:49Z |
| Publication Date | 2017-03-08T18:38:06Z |

## Columns

```ls
| Included | Schema Type | Field Name                   | Name                         | Data Type | Render Type |
| ======== | =========== | ============================ | ============================ | ========= | =========== |
| Yes      | time        | start_time                   | Start time                   | date      | date        |
| No       |             | end_time                     | End time                     | date      | date        |
| Yes      | series tag  | english_event_name           | English event name           | text      | text        |
| Yes      | series tag  | event_name                   | Event name                   | text      | text        |
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
series e:yhm4-4y8s d:2016-01-20T08:00:00.000Z t:english_event_name="Ballots mailed for February election" t:contact_email=elections@kingcounty.gov t:contact_name="King County Elections" t:contact_phone=206-296-8683 t:display_on_election_calendar=true t:event_name="L? phi?u ???c g?i ?i qua ???ng b?u ?i?n cho cu?c b?u c? th?ng Hai" t:host_contact_department="King County Elections" t:url=http://kingcounty.gov/depts/elections/elections/vietnamese m:row_number.yhm4-4y8s=1

series e:yhm4-4y8s d:2016-01-21T08:00:00.000Z t:english_event_name="Ballot drop-off locations open" t:contact_email=elections@kingcounty.gov t:contact_name="King County Elections" t:contact_phone=206-296-8683 t:display_on_election_calendar=true t:event_name="??a ?i?m b? phi?u m? c?a" t:host_contact_department="King County Elections" t:url=http://kingcounty.gov/depts/elections/vietnamese/how-to-vote/ballots/returning-my-ballot/ballot-dropoff-locations.aspx m:row_number.yhm4-4y8s=2

series e:yhm4-4y8s d:2016-02-09T08:00:00.000Z t:english_event_name="Election Day" t:contact_email=elections@kingcounty.gov t:contact_name="King County Elections" t:contact_phone=206-296-8683 t:display_on_election_calendar=true t:event_name="Ng?y b?u c?" t:host_contact_department="King County Elections" t:url=http://kingcounty.gov/depts/elections/elections/vietnamese m:row_number.yhm4-4y8s=3
```

## Meta Commands

```ls
metric m:row_number.yhm4-4y8s p:long l:"Row Number"

entity e:yhm4-4y8s l:"King County Elections Vietnamese Master Calendar" t:attribution="King County Elections" t:url=https://data.kingcounty.gov/api/views/yhm4-4y8s

property e:yhm4-4y8s t:meta.view v:id=yhm4-4y8s v:category=Elections v:attributionLink=http://kingcounty.gov/elections v:averageRating=0 v:name="King County Elections Vietnamese Master Calendar" v:attribution="King County Elections"

property e:yhm4-4y8s t:meta.view.license v:name="Public Domain U.S. Government" v:termsLink=https://www.usa.gov/government-works

property e:yhm4-4y8s t:meta.view.owner v:id=dqgp-vryk v:screenName=Janice v:displayName=Janice

property e:yhm4-4y8s t:meta.view.tableauthor v:id=dqgp-vryk v:screenName=Janice v:roleName=publisher v:displayName=Janice
```

## Top Records

```ls
| start_time | end_time   | english_event_name                                                      | event_name                                                                                              | event_description_details | location_name | url                                                                                                                            | contact_name          | contact_email            | contact_phone | host_contact_department | feed_keyword_s | display_on_election_calendar | outreach | registration | 
| ========== | ========== | ======================================================================= | ======================================================================================================= | ========================= | ============= | ============================================================================================================================== | ===================== | ======================== | ============= | ======================= | ============== | ============================ | ======== | ============ | 
| 1453276800 | 1453363140 | Ballots mailed for February election                                    | L? phi?u ???c g?i ?i qua ???ng b?u ?i?n cho cu?c b?u c? th?ng Hai                                       |                           |               | [http://kingcounty.gov/depts/elections/elections/vietnamese, null]                                                             | King County Elections | elections@kingcounty.gov | 206-296-8683  | King County Elections   |                | true                         |          |              | 
| 1453363200 | 1453449540 | Ballot drop-off locations open                                          | ??a ?i?m b? phi?u m? c?a                                                                                |                           |               | [http://kingcounty.gov/depts/elections/vietnamese/how-to-vote/ballots/returning-my-ballot/ballot-dropoff-locations.aspx, null] | King County Elections | elections@kingcounty.gov | 206-296-8683  | King County Elections   |                | true                         |          |              | 
| 1455004800 | 1455091140 | Election Day                                                            | Ng?y b?u c?                                                                                             |                           |               | [http://kingcounty.gov/depts/elections/elections/vietnamese, null]                                                             | King County Elections | elections@kingcounty.gov | 206-296-8683  | King County Elections   |                | true                         |          |              | 
| 1455868800 | 1455955140 | February election certified                                             | Cu?c b?u c? th?ng Hai ???c ch?ng nh?n                                                                   |                           |               | [http://kingcounty.gov/depts/elections/elections/vietnamese, null]                                                             | King County Elections | elections@kingcounty.gov | 206-296-8683  | King County Elections   |                | true                         |          |              | 
| 1458889200 | 1458975540 | Overseas and service ballots sent for the April election                | L? phi?u ???c g?i ??n c?c c? tri ? n??c ngo?i v? ?ang thi h?nh c?ng v? cho cu?c b?u c? th?ng T?         |                           |               | [http://kingcounty.gov/depts/elections/elections/vietnamese, null]                                                             | King County Elections | elections@kingcounty.gov | 206-296-8683  | King County Elections   |                | true                         |          |              | 
| 1459926000 | 1460012340 | Ballots mailed for April election                                       | L? phi?u ???c g?i ?i qua ???ng b?u ?i?n cho cu?c b?u c? th?ng T?                                        |                           |               | [http://kingcounty.gov/depts/elections/elections/vietnamese, null]                                                             | King County Elections | elections@kingcounty.gov | 206-296-8683  | King County Elections   |                | true                         |          |              | 
| 1460012400 | 1460098740 | Ballot drop-off locations open                                          | ??a ?i?m b? phi?u m? c?a                                                                                |                           |               | [http://kingcounty.gov/depts/elections/vietnamese/how-to-vote/ballots/returning-my-ballot/ballot-dropoff-locations.aspx, null] | King County Elections | elections@kingcounty.gov | 206-296-8683  | King County Elections   |                | true                         |          |              | 
| 1460098800 | 1460185140 | Overseas and service ballots sent for the Presidential Primary election | L? phi?u ???c g?i ??n c?c c? tri ? n??c ngo?i v? ?ang thi h?nh c?ng v? cho cu?c b?u c? T?ng th?ng S? b? |                           |               | [http://kingcounty.gov/depts/elections/elections/vietnamese, null]                                                             | King County Elections | elections@kingcounty.gov | 206-296-8683  | King County Elections   |                | true                         |          |              | 
| 1461654000 | 1461740340 | Election Day                                                            | Ng?y b?u c?                                                                                             |                           |               | [http://kingcounty.gov/depts/elections/elections/vietnamese, null]                                                             | King County Elections | elections@kingcounty.gov | 206-296-8683  | King County Elections   |                | true                         |          |              | 
| 1462345200 | 1462431540 | Ballots mailed for Presidential Primary election                        | L? phi?u ???c g?i ?i qua ???ng b?u ?i?n cho cu?c b?u c? T?ng th?ng S? b?                                |                           |               | [http://kingcounty.gov/depts/elections/elections/vietnamese, null]                                                             | King County Elections | elections@kingcounty.gov | 206-296-8683  | King County Elections   |                | true                         |          |              | 
```