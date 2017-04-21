# Austin Code Complaint Case Events

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/austin-code-complaint-case-events) |
| Metadata | [Link](https://data.austintexas.gov/api/views/afwp-v695) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/afwp-v695/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/afwp-v695/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | afwp-v695 |
| Name | Austin Code Complaint Case Events |
| Attribution | Austin Code Department |
| Category | Government |
| Created | 2015-04-29T18:20:18Z |
| Publication Date | 2017-01-11T13:19:03Z |

## Description

This data represents Austin Code Department complaint case events.

## Columns

```ls
| Included | Schema Type | Field Name   | Name         | Data Type     | Render Type   |
| ======== | =========== | ============ | ============ | ============= | ============= |
| Yes      | series tag  | event_id     | EVENT_ID     | text          | number        |
| Yes      | series tag  | case_id      | CASE_ID      | text          | text          |
| Yes      | series tag  | name         | NAME         | text          | text          |
| Yes      | time        | status_date  | STATUS_DATE  | calendar_date | calendar_date |
| Yes      | series tag  | status       | STATUS       | text          | text          |
| Yes      | series tag  | notes        | NOTES        | text          | text          |
| Yes      | series tag  | contact      | CONTACT      | text          | text          |
| No       |             | date_updated | DATE_UPDATED | calendar_date | calendar_date |
```

## Time Field

```ls
Value = status_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = date_updated
```

## Data Commands

```ls
series e:afwp-v695 d:2015-07-02T00:00:00.000Z t:status="Follow-up Inspection" t:name="Case Management" t:case_id="2008-076675 CC" t:event_id=10023954195 t:contact="Rowdy Salazar|512-974-3134" m:row_number.afwp-v695=1

series e:afwp-v695 d:2015-07-22T00:00:00.000Z t:status="Information Update" t:name="Case Management" t:case_id="2012-086606 CC" t:event_id=10031034779 t:contact="Edgar Hinojosa|512-974-3577" m:row_number.afwp-v695=2

series e:afwp-v695 d:2002-11-12T00:00:00.000Z t:status="Follow-up Inspection" t:name="Case Management" t:case_id="2002-010858 CC" t:event_id=1005729961 t:contact="Irma Ybarra|512-974-3612" m:row_number.afwp-v695=3
```

## Meta Commands

```ls
metric m:row_number.afwp-v695 p:long l:"Row Number"

entity e:afwp-v695 l:"Austin Code Complaint Case Events" t:attribution="Austin Code Department" t:url=https://data.austintexas.gov/api/views/afwp-v695

property e:afwp-v695 t:meta.view v:id=afwp-v695 v:category=Government v:averageRating=0 v:name="Austin Code Complaint Case Events" v:attribution="Austin Code Department"

property e:afwp-v695 t:meta.view.license v:name="Public Domain"

property e:afwp-v695 t:meta.view.owner v:id=99uc-9byy v:screenName=opendataatx v:displayName=opendataatx

property e:afwp-v695 t:meta.view.tableauthor v:id=99uc-9byy v:screenName=opendataatx v:roleName=administrator v:displayName=opendataatx
```

## Top Records

```ls
| event_id    | case_id        | name            | status_date         | status               | notes | contact                       | date_updated        | 
| =========== | ============== | =============== | =================== | ==================== | ===== | ============================= | =================== | 
| 10023954195 | 2008-076675 CC | Case Management | 2015-07-02T00:00:00 | Follow-up Inspection |       | Rowdy Salazar|512-974-3134    | 2015-07-06T08:36:46 | 
| 10031034779 | 2012-086606 CC | Case Management | 2015-07-22T00:00:00 | Information Update   |       | Edgar Hinojosa|512-974-3577   | 2015-09-14T13:57:27 | 
| 1005729961  | 2002-010858 CC | Case Management | 2002-11-12T00:00:00 | Follow-up Inspection |       | Irma Ybarra|512-974-3612      | 2006-12-08T14:40:17 | 
| 1005729962  | 2002-010859 CC | Case Management | 2002-11-01T00:00:00 | Information Update   |       | Irma Ybarra|512-974-3612      | 2006-12-08T14:40:17 | 
| 10131034779 | 2012-086606 CC | Case Management | 2015-09-14T00:00:00 | Follow-up Inspection |       | Edgar Hinojosa|512-974-3577   | 2015-09-14T14:17:38 | 
| 1015729961  | 2002-010858 CC | Case Management | 2002-12-27T00:00:00 | Follow-up Inspection |       | Irma Ybarra|512-974-3612      | 2006-12-08T14:40:17 | 
| 1015729962  | 2002-010859 CC | Case Management | 2002-11-12T00:00:00 | Follow-up Inspection |       | Irma Ybarra|512-974-3612      | 2006-12-08T14:40:17 | 
| 1022624516  | 2008-013318 CC | Inspections     | 2008-03-27T00:00:00 | Cancelled            |       | Troy Collins|512-974-9064     | 2008-03-27T07:21:49 | 
| 1022652109  | 2008-011806 CC | Case Management | 2008-03-13T00:00:00 | Information Update   |       | Aurelio Martinez|512-974-9054 | 2008-03-14T08:18:52 | 
| 1022902652  | 2008-026146 CC | Case Management | 2008-05-20T00:00:00 | Owner Contacted      |       | Moses Rodriguez|512-974-3594  | 2008-05-20T08:35:35 | 
```