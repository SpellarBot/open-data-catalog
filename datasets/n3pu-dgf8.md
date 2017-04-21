# PED_OverTheCounterPermitsDetail

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ped-overthecounterpermitsdetail) |
| Metadata | [Link](https://data.srcity.org/api/views/n3pu-dgf8) |
| Data: JSON | [100 Rows](https://data.srcity.org/api/views/n3pu-dgf8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.srcity.org/api/views/n3pu-dgf8/rows.csv?max_rows=100) |
| Host | data.srcity.org |
| Id | n3pu-dgf8 |
| Name | PED_OverTheCounterPermitsDetail |
| Created | 2017-01-20T21:22:49Z |
| Publication Date | 2017-01-20T21:22:57Z |

## Columns

```ls
| Included | Schema Type | Field Name         | Name               | Data Type     | Render Type   |
| ======== | =========== | ================== | ================== | ============= | ============= |
| Yes      | series tag  | permitnum          | PermitNum          | text          | text          |
| Yes      | time        | opndt              | OpnDt              | calendar_date | calendar_date |
| Yes      | series tag  | rescomm            | ResComm            | text          | text          |
| Yes      | series tag  | rectype            | RecType            | text          | text          |
| Yes      | series tag  | recsubtype         | RecSubType         | text          | text          |
| No       |             | applctnaccpteddttm | ApplctnAccptedDTTM | calendar_date | calendar_date |
| No       |             | planscoorddttm     | PlansCoordDTTM     | calendar_date | calendar_date |
| Yes      | series tag  | recstat            | RecStat            | text          | text          |
| No       |             | refresheddttm      | RefreshedDTTM      | calendar_date | calendar_date |
```

## Time Field

```ls
Value = opndt
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = applctnaccpteddttm,planscoorddttm,refresheddttm
```

## Data Commands

```ls
series e:n3pu-dgf8 d:2015-08-27T00:00:00.000Z t:recsubtype=Mechanical t:recstat=Finaled t:rectype="Residential Mechanical" t:rescomm=Residential t:permitnum=B15-3840 m:row_number.n3pu-dgf8=1

series e:n3pu-dgf8 d:2016-03-28T00:00:00.000Z t:recsubtype=Plumbing t:recstat=Finaled t:rectype="Residential Plumbing" t:rescomm=Residential t:permitnum=B16-1177 m:row_number.n3pu-dgf8=2

series e:n3pu-dgf8 d:2017-03-28T00:00:00.000Z t:recsubtype=Addition-Alteration t:recstat=Issued t:rectype="Residential Addition-Alteration" t:rescomm=Residential t:permitnum=B17-1141 m:row_number.n3pu-dgf8=3
```

## Meta Commands

```ls
metric m:row_number.n3pu-dgf8 p:long l:"Row Number"

entity e:n3pu-dgf8 l:PED_OverTheCounterPermitsDetail t:url=https://data.srcity.org/api/views/n3pu-dgf8

property e:n3pu-dgf8 t:meta.view v:id=n3pu-dgf8 v:averageRating=0 v:name=PED_OverTheCounterPermitsDetail

property e:n3pu-dgf8 t:meta.view.owner v:id=v4p4-re39 v:screenName="OpenData, RO" v:displayName="OpenData, RO"

property e:n3pu-dgf8 t:meta.view.tableauthor v:id=v4p4-re39 v:screenName="OpenData, RO" v:roleName=administrator v:displayName="OpenData, RO"
```

## Top Records

```ls
| permitnum | opndt               | rescomm     | rectype                         | recsubtype          | applctnaccpteddttm  | planscoorddttm      | recstat | refresheddttm       | 
| ========= | =================== | =========== | =============================== | =================== | =================== | =================== | ======= | =================== | 
| B15-3840  | 2015-08-27T00:00:00 | Residential | Residential Mechanical          | Mechanical          | 2015-08-27T11:32:40 | 2015-08-27T11:32:42 | Finaled | 2017-04-09T23:35:01 | 
| B16-1177  | 2016-03-28T00:00:00 | Residential | Residential Plumbing            | Plumbing            | 2016-03-28T16:05:43 | 2016-03-28T16:05:44 | Finaled | 2017-04-09T23:35:01 | 
| B17-1141  | 2017-03-28T00:00:00 | Residential | Residential Addition-Alteration | Addition-Alteration | 2017-03-28T13:54:11 | 2017-03-28T13:54:11 | Issued  | 2017-04-09T23:35:01 | 
| B17-0744  | 2017-02-27T00:00:00 | Residential | Residential Addition-Alteration | Addition-Alteration | 2017-02-27T15:27:34 | 2017-02-27T15:27:35 | Finaled | 2017-04-09T23:35:01 | 
| B15-3576  | 2015-08-11T00:00:00 | Residential | Residential Addition-Alteration | Addition-Alteration | 2015-08-17T11:15:04 | 2015-08-17T11:15:18 | Finaled | 2017-04-09T23:35:01 | 
| B16-4394  | 2016-10-17T00:00:00 | Residential | Residential Addition-Alteration | Addition-Alteration | 2016-10-17T15:15:48 | 2016-10-17T15:15:49 | Finaled | 2017-04-09T23:35:01 | 
| B17-0571  | 2017-02-15T00:00:00 | Residential | Residential Addition-Alteration | Addition-Alteration | 2017-02-15T10:44:46 | 2017-02-15T10:44:47 | Finaled | 2017-04-09T23:35:01 | 
| B16-3918  | 2016-09-15T00:00:00 | Residential | Residential Addition-Alteration | Addition-Alteration | 2016-09-19T09:17:04 | 2016-09-19T09:17:15 | Issued  | 2017-04-09T23:35:01 | 
| B15-4724  | 2015-10-14T00:00:00 | Residential | Residential Mechanical          | Mechanical          | 2015-10-14T12:30:02 | 2015-10-14T12:30:03 | Issued  | 2017-04-09T23:35:01 | 
| B17-1271  | 2017-04-06T00:00:00 | Residential | Residential Addition-Alteration | Addition-Alteration | 2017-04-06T11:07:36 | 2017-04-06T11:07:36 | Issued  | 2017-04-09T23:35:01 | 
```