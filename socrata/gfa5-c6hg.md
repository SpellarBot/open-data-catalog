# King County Elections Spanish Master Calendar

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/king-county-elections-spanish-master-calendar) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/gfa5-c6hg) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/gfa5-c6hg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/gfa5-c6hg/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | gfa5-c6hg |
| Name | King County Elections Spanish Master Calendar |
| Attribution | King County Elections |
| Category | Elections |
| Tags | elections, election results, voter registration, vote |
| Created | 2016-08-26T15:50:01Z |
| Publication Date | 2017-03-08T18:37:06Z |

## Description

Spanish Master Calendar dataset

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
series e:gfa5-c6hg d:2016-11-29T08:00:00.000Z t:english_event_name="General election certified" t:contact_email=elections@kingcounty.gov t:contact_name="King County Elections" t:contact_phone=206-296-8683 t:display_on_election_calendar=true t:event_name="Certificaci?n de la Elecci?n General" t:host_contact_department="King County Elections" t:url=http://www.kingcounty.gov/depts/elections/spanish/election-dates.aspx m:row_number.gfa5-c6hg=1

series e:gfa5-c6hg d:2016-09-05T07:00:00.000Z t:english_event_name="Labor Day holiday closure" t:display_on_election_calendar=true t:registration=true t:event_name="Cierre por d?a festivo - D?a del Trabajo" t:outreach=true t:url=http://www.kingcounty.gov/depts/elections/spanish/election-dates.aspx m:row_number.gfa5-c6hg=2

series e:gfa5-c6hg d:2016-08-16T07:00:00.000Z t:english_event_name="Primary election certified" t:contact_email=elections@kingcounty.gov t:contact_name="King County Elections" t:contact_phone=206-296-8683 t:display_on_election_calendar=true t:event_name="Certificaci?n de Elecci?n Primaria" t:host_contact_department="King County Elections" t:url=http://www.kingcounty.gov/depts/elections/spanish/election-dates.aspx m:row_number.gfa5-c6hg=3
```

## Meta Commands

```ls
metric m:row_number.gfa5-c6hg p:long l:"Row Number"

entity e:gfa5-c6hg l:"King County Elections Spanish Master Calendar" t:attribution="King County Elections" t:url=https://data.kingcounty.gov/api/views/gfa5-c6hg

property e:gfa5-c6hg t:meta.view v:id=gfa5-c6hg v:category=Elections v:attributionLink=http://www.kingcounty.gov/depts/elections.aspx v:averageRating=0 v:name="King County Elections Spanish Master Calendar" v:attribution="King County Elections"

property e:gfa5-c6hg t:meta.view.license v:name="Public Domain U.S. Government" v:termsLink=https://www.usa.gov/government-works

property e:gfa5-c6hg t:meta.view.owner v:id=dqgp-vryk v:screenName=Janice v:displayName=Janice

property e:gfa5-c6hg t:meta.view.tableauthor v:id=dqgp-vryk v:screenName=Janice v:roleName=publisher v:displayName=Janice
```

## Top Records

```ls
| start_time | end_time   | english_event_name                                         | event_name                                                                                          | event_description_details | location_name | url                                                                                                            | contact_name          | contact_email            | contact_phone | host_contact_department | feed_keyword_s | display_on_election_calendar | outreach | registration | 
| ========== | ========== | ========================================================== | =================================================================================================== | ========================= | ============= | ============================================================================================================== | ===================== | ======================== | ============= | ======================= | ============== | ============================ | ======== | ============ | 
| 1480406400 | 1480492740 | General election certified                                 | Certificaci?n de la Elecci?n General                                                                |                           |               | [http://www.kingcounty.gov/depts/elections/spanish/election-dates.aspx, null]                                  | King County Elections | elections@kingcounty.gov | 206-296-8683  | King County Elections   |                | true                         |          |              | 
| 1473058800 | 1473145140 | Labor Day holiday closure                                  | Cierre por d?a festivo - D?a del Trabajo                                                            |                           |               | [http://www.kingcounty.gov/depts/elections/spanish/election-dates.aspx, null]                                  |                       |                          |               |                         |                | true                         | true     | true         | 
| 1471330800 | 1471417140 | Primary election certified                                 | Certificaci?n de Elecci?n Primaria                                                                  |                           |               | [http://www.kingcounty.gov/depts/elections/spanish/election-dates.aspx, null]                                  | King County Elections | elections@kingcounty.gov | 206-296-8683  | King County Elections   |                | true                         |          |              | 
| 1470121200 | 1470207540 | Election Day                                               | D?a de la Elecci?n                                                                                  |                           |               | [http://www.kingcounty.gov/depts/elections/spanish/election-dates.aspx, null]                                  | King County Elections | elections@kingcounty.gov | 206-296-8683  | King County Elections   |                | true                         |          |              | 
| 1469430000 | 1469516340 | In-person voter registration deadline for new voters       | Fecha l?mite para que nuevos(as) electores(as) se inscriban en persona para votar                   |                           |               | [http://kingcounty.gov/depts/elections/spanish/how-to-vote/register-to-vote.aspx, null]                        | King County Elections | elections@kingcounty.gov | 206-296-8683  | King County Elections   |                | true                         |          | true         | 
| 1482652800 | 1482739140 | Christmas Day                                              | Navidad                                                                                             |                           |               | [http://www.kingcounty.gov/depts/elections/spanish/election-dates.aspx, null]                                  |                       |                          |               |                         |                | true                         | true     | true         | 
| 1451030400 | 1451116740 | Christmas holiday closure                                  | Cierre por festividades navide?as                                                                   |                           |               | [http://www.kingcounty.gov/depts/elections/spanish/election-dates.aspx, null]                                  |                       |                          |               |                         |                | true                         | true     | true         | 
| 1479974400 | 1480060740 | Thanksgiving holiday closure                               | Cierre por d?a festivo - D?a de Acci?n de Gracias                                                   |                           |               | [http://www.kingcounty.gov/depts/elections/spanish/election-dates.aspx, null]                                  |                       |                          |               |                         |                | true                         | true     | true         | 
| 1474614000 | 1474700340 | Overseas and service ballots sent for the general election | Env?o de boletas para la Elecci?n General para electores(as) en el extranjero y al servicio federal |                           |               | [http://www.kingcounty.gov/depts/elections/spanish/how-to-vote/ballots/overseas-and-service-voters.aspx, null] | King County Elections | elections@kingcounty.gov | 206-296-8683  | King County Elections   |                | true                         |          |              | 
| 1474959600 | 1472713200 | National Voter Registration Day                            | D?a Nacional de Inscripci?n para Votar                                                              |                           |               | [http://kingcounty.gov/depts/elections/spanish/how-to-vote/register-to-vote.aspx, null]                        | King County Elections | elections@kingcounty.gov | 206-296-8683  | King County Elections   |                | true                         |          | true         | 
```