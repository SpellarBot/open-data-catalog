# Santa Rosa Police Department Calls For Service

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/santa-rosa-police-department-calls-for-service) |
| Metadata | [Link](https://data.srcity.org/api/views/vagc-esxy) |
| Data: JSON | [100 Rows](https://data.srcity.org/api/views/vagc-esxy/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.srcity.org/api/views/vagc-esxy/rows.csv?max_rows=100) |
| Host | data.srcity.org |
| Id | vagc-esxy |
| Name | Santa Rosa Police Department Calls For Service |
| Category | Police |
| Created | 2015-11-16T23:55:31Z |
| Publication Date | 2017-04-04T23:43:55Z |

## Description

Calls for Service refers to assignments that are distributed to law enforcement professionals that require their presence to resolve, correct, or assist a particular situation.

## Columns

```ls
| Included | Schema Type | Field Name         | Name               | Data Type     | Render Type   |
| ======== | =========== | ================== | ================== | ============= | ============= |
| Yes      | series tag  | agency             | agency             | text          | text          |
| Yes      | series tag  | agency_name        | agency_name        | text          | text          |
| Yes      | time        | date_time          | date_time          | calendar_date | calendar_date |
| Yes      | series tag  | event_num          | event_num          | text          | number        |
| Yes      | series tag  | incident_num       | incident_num       | text          | number        |
| Yes      | series tag  | nature_code        | nature_code        | text          | text          |
| Yes      | series tag  | nature_description | nature_description | text          | text          |
| Yes      | series tag  | beat_zone          | beat_zone          | text          | text          |
| Yes      | series tag  | event_source       | event_source       | text          | text          |
| Yes      | series tag  | disposition_code   | disposition_code   | text          | text          |
| Yes      | series tag  | disposition        | disposition        | text          | text          |
| Yes      | series tag  | location           | location           | text          | text          |
| No       |             | id                 | id                 | text          | number        |
```

## Time Field

```ls
Value = date_time
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = id
```

## Data Commands

```ls
series e:vagc-esxy d:2017-03-06T09:57:00.000Z t:location=na t:event_num=170650118 t:agency=SRP t:agency_name="Santa Rosa Police Department" t:nature_code=T t:event_source=OFFICER t:nature_description="TRAFFIC STOP" m:row_number.vagc-esxy=1

series e:vagc-esxy d:2017-03-09T19:01:00.000Z t:location=na t:event_num=170680327 t:disposition_code=COM t:agency=SRP t:agency_name="Santa Rosa Police Department" t:disposition=COMPLETED t:nature_code=1021 t:event_source=OFFICER t:nature_description=TELEPHONE m:row_number.vagc-esxy=2

series e:vagc-esxy d:2017-03-10T16:36:00.000Z t:location=na t:event_num=170690278 t:disposition_code=CIT t:agency=SRP t:agency_name="Santa Rosa Police Department" t:disposition=CITE t:nature_code=T t:event_source=OFFICER t:nature_description="TRAFFIC STOP" m:row_number.vagc-esxy=3
```

## Meta Commands

```ls
metric m:row_number.vagc-esxy p:long l:"Row Number"

entity e:vagc-esxy l:"Santa Rosa Police Department Calls For Service" t:url=https://data.srcity.org/api/views/vagc-esxy

property e:vagc-esxy t:meta.view v:id=vagc-esxy v:category=Police v:averageRating=0 v:name="Santa Rosa Police Department Calls For Service"

property e:vagc-esxy t:meta.view.owner v:id=u2re-x7kp v:screenName="Petri, Jerry" v:displayName="Petri, Jerry"

property e:vagc-esxy t:meta.view.tableauthor v:id=u2re-x7kp v:screenName="Petri, Jerry" v:roleName=administrator v:displayName="Petri, Jerry"
```

## Top Records

```ls
| agency | agency_name                  | date_time           | event_num | incident_num | nature_code | nature_description      | beat_zone | event_source | disposition_code | disposition | location | id      | 
| ====== | ============================ | =================== | ========= | ============ | =========== | ======================= | ========= | ============ | ================ | =========== | ======== | ======= | 
| SRP    | Santa Rosa Police Department | 2017-03-06T09:57:00 | 170650118 |              | T           | TRAFFIC STOP            |           | OFFICER      |                  |             | na       | 5695165 | 
| SRP    | Santa Rosa Police Department | 2017-03-09T19:01:00 | 170680327 |              | 1021        | TELEPHONE               |           | OFFICER      | COM              | COMPLETED   | na       | 5699156 | 
| SRP    | Santa Rosa Police Department | 2017-03-10T16:36:00 | 170690278 |              | T           | TRAFFIC STOP            |           | OFFICER      | CIT              | CITE        | na       | 5700130 | 
| SRP    | Santa Rosa Police Department | 2017-03-10T17:20:00 | 170690297 |              | 1021        | TELEPHONE               |           | OFFICER      | COM              | COMPLETED   | na       | 5700196 | 
| SRP    | Santa Rosa Police Department | 2017-03-15T09:31:00 | 170740087 |              | OWS         | OUT WITH SUBJECT        |           | OFFICER      | CIT              | CITE        | na       | 5704997 | 
| SRP    | Santa Rosa Police Department | 2017-03-11T16:39:00 | 170700237 |              | T           | TRAFFIC STOP            |           | OFFICER      | CIT              | CITE        | na       | 5701288 | 
| SRP    | Santa Rosa Police Department | 2017-03-15T08:14:00 | 170740071 |              | 1125        | TRAFFIC HAZARD          |           | OFFICER      | COM              | COMPLETED   | na       | 5704948 | 
| SRP    | Santa Rosa Police Department | 2017-03-17T10:19:00 | 170760136 |              | T           | TRAFFIC STOP            |           | OFFICER      |                  |             | na       | 5707406 | 
| SRP    | Santa Rosa Police Department | 2017-03-18T20:09:00 | 170770312 |              | FU          | FOLLOW UP / INVESTIGATE |           | OFFICER      | COM              | COMPLETED   | na       | 5709110 | 
| SRP    | Santa Rosa Police Department | 2017-03-01T15:42:00 | 170600227 |              | FU          | FOLLOW UP / INVESTIGATE |           | OFFICER      |                  |             | (0,0)    | 5690281 | 
```