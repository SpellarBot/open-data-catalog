# PED_PlanReviewMeasures_BuildingDetail

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ped-planreviewmeasures-buildingdetail) |
| Metadata | [Link](https://data.srcity.org/api/views/qxnn-4j28) |
| Data: JSON | [100 Rows](https://data.srcity.org/api/views/qxnn-4j28/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.srcity.org/api/views/qxnn-4j28/rows.csv?max_rows=100) |
| Host | data.srcity.org |
| Id | qxnn-4j28 |
| Name | PED_PlanReviewMeasures_BuildingDetail |
| Created | 2017-01-20T21:29:53Z |
| Publication Date | 2017-01-20T21:42:26Z |

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type     | Render Type   |
| ======== | ============== | ================== | ================== | ============= | ============= |
| Yes      | series tag     | permitnum          | PermitNum          | text          | text          |
| Yes      | time           | opndt              | OpnDt              | calendar_date | calendar_date |
| Yes      | series tag     | rescomm            | ResComm            | text          | text          |
| Yes      | series tag     | rectype            | RecType            | text          | text          |
| Yes      | series tag     | recsubtype         | RecSubType         | text          | text          |
| No       |                | applctnaccpteddttm | ApplctnAccptedDTTM | calendar_date | calendar_date |
| No       |                | planscoorddttm     | PlansCoordDTTM     | calendar_date | calendar_date |
| Yes      | numeric metric | numdays            | NumDays            | number        | number        |
| Yes      | series tag     | recstat            | RecStat            | text          | text          |
| No       |                | refresheddttm      | RefreshedDTTM      | calendar_date | calendar_date |
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
series e:qxnn-4j28 d:2016-09-27T00:00:00.000Z t:recsubtype=New t:recstat="Approved - Deferred" t:rectype="Residential New" t:rescomm=Residential t:permitnum=B16-4107 m:numdays=22

series e:qxnn-4j28 d:2016-12-14T00:00:00.000Z t:recsubtype=Addition-Alteration t:recstat=Approved t:rectype="Residential Addition-Alteration" t:rescomm=Residential t:permitnum=B16-5440 m:numdays=27

series e:qxnn-4j28 d:2016-12-13T00:00:00.000Z t:recsubtype=Addition-Alteration t:recstat=Finaled t:rectype="Residential Addition-Alteration" t:rescomm=Residential t:permitnum=B16-5370 m:numdays=2
```

## Meta Commands

```ls
metric m:numdays p:integer l:NumDays t:dataTypeName=number

entity e:qxnn-4j28 l:PED_PlanReviewMeasures_BuildingDetail t:url=https://data.srcity.org/api/views/qxnn-4j28

property e:qxnn-4j28 t:meta.view v:id=qxnn-4j28 v:averageRating=0 v:name=PED_PlanReviewMeasures_BuildingDetail

property e:qxnn-4j28 t:meta.view.owner v:id=v4p4-re39 v:screenName="OpenData, RO" v:displayName="OpenData, RO"

property e:qxnn-4j28 t:meta.view.tableauthor v:id=v4p4-re39 v:screenName="OpenData, RO" v:roleName=administrator v:displayName="OpenData, RO"
```

## Top Records

```ls
| permitnum | opndt               | rescomm         | rectype                             | recsubtype          | applctnaccpteddttm  | planscoorddttm      | numdays | recstat             | refresheddttm       | 
| ========= | =================== | =============== | =================================== | =================== | =================== | =================== | ======= | =================== | =================== | 
| B16-4107  | 2016-09-27T00:00:00 | Residential     | Residential New                     | New                 | 2016-09-28T15:51:25 | 2016-10-21T14:21:46 | 22      | Approved - Deferred | 2017-04-09T23:35:01 | 
| B16-5440  | 2016-12-14T00:00:00 | Residential     | Residential Addition-Alteration     | Addition-Alteration | 2017-01-12T10:29:38 | 2017-02-08T15:17:06 | 27      | Approved            | 2017-04-09T23:35:01 | 
| B16-5370  | 2016-12-13T00:00:00 | Residential     | Residential Addition-Alteration     | Addition-Alteration | 2016-12-13T12:07:43 | 2016-12-15T13:40:46 | 2       | Finaled             | 2017-04-09T23:35:01 | 
| B15-5021  | 2015-11-03T00:00:00 | Residential     | Residential New                     | New                 | 2015-11-04T07:09:55 | 2015-12-18T15:04:05 | 44      | Issued              | 2017-04-09T23:35:01 | 
| B16-5275  | 2016-12-12T00:00:00 | Residential     | Residential Addition-Alteration     | Addition-Alteration | 2017-01-12T08:56:26 | 2017-02-15T16:27:51 | 34      | Approved            | 2017-04-09T23:35:01 | 
| B16-5666  | 2016-12-22T00:00:00 | Residential     | Residential New                     | New                 | 2017-01-19T10:31:59 | 2017-01-31T10:02:34 | 11      | In Plan Review      | 2017-04-09T23:35:01 | 
| B16-5316  | 2016-12-12T00:00:00 | Residential     | Residential Addition-Alteration     | Addition-Alteration | 2017-01-12T08:57:33 | 2017-02-15T16:28:50 | 34      | Approved            | 2017-04-09T23:35:01 | 
| B16-0509  | 2016-02-10T00:00:00 | Residential     | Residential Addition-Alteration     | Addition-Alteration | 2016-02-10T09:59:46 | 2016-03-10T11:16:22 | 29      | Issued              | 2017-04-09T23:35:01 | 
| B15-3291  | 2015-07-27T00:00:00 | Non-Residential | Non-Residential Addition-Alteration | Addition-Alteration | 2015-07-27T15:01:29 | 2015-08-25T16:33:08 | 29      | Finaled             | 2017-04-09T23:35:01 | 
| B16-5833  | 2016-12-22T00:00:00 | Residential     | Residential New                     | New                 | 2017-01-03T13:39:30 | 2017-01-31T09:37:24 | 27      | In Plan Review      | 2017-04-09T23:35:01 | 
```