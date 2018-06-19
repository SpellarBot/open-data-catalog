# Event Waivers

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/event-waivers) |
| Metadata | [Link](https://data.austintexas.gov/api/views/fytz-zuei) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/fytz-zuei/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/fytz-zuei/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | fytz-zuei |
| Name | Event Waivers |
| Attribution | City of Austin |
| Category | Permitting |
| Tags | event, waiver |
| Created | 2015-08-06T19:43:16Z |
| Publication Date | 2015-08-06T20:00:38Z |

## Description

List of deadline and rule waivers related to special events occurring in the Right of Way.

## Columns

```ls
| Included | Schema Type | Field Name | Name       | Data Type     | Render Type   |
| ======== | =========== | ========== | ========== | ============= | ============= |
| Yes      | time        | start_time | Start Time | calendar_date | calendar_date |
| Yes      | series tag  | title      | Title      | text          | text          |
| Yes      | series tag  | waiver_1   | Waiver (1) | text          | text          |
| Yes      | series tag  | waiver_2   | Waiver (2) | text          | text          |
```

## Time Field

```ls
Value = start_time
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:fytz-zuei d:2011-10-02T00:00:00.000Z t:title="Be Well Walk" t:waiver_1=Deadline t:waiver_2=Rule m:row_number.fytz-zuei=1

series e:fytz-zuei d:2011-10-07T00:00:00.000Z t:title="Mediterranean Fest" t:waiver_1=Deadline m:row_number.fytz-zuei=2

series e:fytz-zuei d:2011-10-08T00:00:00.000Z t:title="NAMI Walk" t:waiver_1=Deadline m:row_number.fytz-zuei=3
```

## Meta Commands

```ls
metric m:row_number.fytz-zuei p:long l:"Row Number"

entity e:fytz-zuei l:"Event Waivers" t:attribution="City of Austin" t:url=https://data.austintexas.gov/api/views/fytz-zuei

property e:fytz-zuei t:meta.view v:id=fytz-zuei v:category=Permitting v:averageRating=0 v:name="Event Waivers" v:attribution="City of Austin"

property e:fytz-zuei t:meta.view.license v:name="Public Domain"

property e:fytz-zuei t:meta.view.owner v:id=jsyn-mk6f v:screenName=jhrncir v:displayName=jhrncir

property e:fytz-zuei t:meta.view.tableauthor v:id=jsyn-mk6f v:screenName=jhrncir v:roleName=editor v:displayName=jhrncir
```

## Top Records

```ls
| start_time          | title                  | waiver_1 | waiver_2 | 
| =================== | ====================== | ======== | ======== | 
| 2011-10-02T00:00:00 | Be Well Walk           | Deadline | Rule     | 
| 2011-10-07T00:00:00 | Mediterranean Fest     | Deadline |          | 
| 2011-10-08T00:00:00 | NAMI Walk              | Deadline |          | 
| 2011-10-13T00:00:00 | La Dolce Vita          | Deadline | Rule     | 
| 2011-10-14T00:00:00 | Capital to Coast Relay | Deadline |          | 
| 2011-10-15T00:00:00 | LIVESTRONG Challenge   | Rule     |          | 
| 2011-10-22T00:00:00 | Texas Book Festival    | Deadline |          | 
| 2011-10-22T00:00:00 | Gypsy Picnic           | Deadline |          | 
| 2011-10-22T00:00:00 | Viva La Vida           | Rule     |          | 
| 2011-10-22T00:00:00 | Light the Night        | Deadline |          | 
```