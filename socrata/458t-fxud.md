# PED_NewCommercialPermitsIssuedDetail

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ped-newcommercialpermitsissueddetail) |
| Metadata | [Link](https://data.srcity.org/api/views/458t-fxud) |
| Data: JSON | [100 Rows](https://data.srcity.org/api/views/458t-fxud/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.srcity.org/api/views/458t-fxud/rows.csv?max_rows=100) |
| Host | data.srcity.org |
| Id | 458t-fxud |
| Name | PED_NewCommercialPermitsIssuedDetail |
| Created | 2017-01-23T14:08:11Z |
| Publication Date | 2017-01-23T14:08:49Z |

## Columns

```ls
| Included | Schema Type    | Field Name         | Name                | Data Type     | Render Type   |
| ======== | ============== | ================== | =================== | ============= | ============= |
| Yes      | series tag     | permittype         | PermitType          | text          | text          |
| Yes      | numeric metric | sqrft              | SqrFt               | number        | number        |
| Yes      | series tag     | record_id          | RECORD_ID           | text          | text          |
| Yes      | series tag     | record_type        | RECORD_TYPE         | text          | text          |
| Yes      | time           | date_opened        | DATE_OPENED         | calendar_date | calendar_date |
| Yes      | series tag     | record_type_4level | RECORD_TYPE_4LEVEL# | text          | text          |
| Yes      | series tag     | record_status      | RECORD_STATUS       | text          | text          |
| Yes      | series tag     | historystatus      | HistoryStatus       | text          | text          |
| No       |                | historystatusdate  | HistoryStatusDate   | calendar_date | calendar_date |
```

## Time Field

```ls
Value = date_opened
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = historystatusdate
```

## Data Commands

```ls
series e:458t-fxud d:2014-01-28T00:00:00.000Z t:record_type="Non-Residential New" t:permittype="New Commercial" t:record_status=Finaled t:record_type_4level=Building/Non-Residential/New/NA t:historystatus=Issued t:record_id=B14-0366 m:sqrft=0

series e:458t-fxud d:2014-02-20T00:00:00.000Z t:record_type="Non-Residential Addition-Alteration" t:permittype=Miscellaneous t:record_status=Issued t:record_type_4level=Building/Non-Residential/Addition-Alteration/NA t:historystatus=Issued t:record_id=B14-0621 m:sqrft=0

series e:458t-fxud d:2014-04-23T00:00:00.000Z t:record_type="Non-Residential Addition-Alteration" t:permittype=Addition-Alteration t:record_status=Finaled t:record_type_4level=Building/Non-Residential/Addition-Alteration/NA t:historystatus=Issued t:record_id=B14-1411 m:sqrft=0
```

## Meta Commands

```ls
metric m:sqrft p:integer l:SqrFt t:dataTypeName=number

entity e:458t-fxud l:PED_NewCommercialPermitsIssuedDetail t:url=https://data.srcity.org/api/views/458t-fxud

property e:458t-fxud t:meta.view v:id=458t-fxud v:averageRating=0 v:name=PED_NewCommercialPermitsIssuedDetail

property e:458t-fxud t:meta.view.owner v:id=v4p4-re39 v:screenName="OpenData, RO" v:displayName="OpenData, RO"

property e:458t-fxud t:meta.view.tableauthor v:id=v4p4-re39 v:screenName="OpenData, RO" v:roleName=administrator v:displayName="OpenData, RO"
```

## Top Records

```ls
| permittype          | sqrft | record_id | record_type                         | date_opened         | record_type_4level                              | record_status | historystatus | historystatusdate   | 
| =================== | ===== | ========= | =================================== | =================== | =============================================== | ============= | ============= | =================== | 
| New Commercial      | 0     | B14-0366  | Non-Residential New                 | 2014-01-28T00:00:00 | Building/Non-Residential/New/NA                 | Finaled       | Issued        | 2015-08-25T00:00:00 | 
| Miscellaneous       | 0     | B14-0621  | Non-Residential Addition-Alteration | 2014-02-20T00:00:00 | Building/Non-Residential/Addition-Alteration/NA | Issued        | Issued        | 2015-10-20T00:00:00 | 
| Addition-Alteration | 0     | B14-1411  | Non-Residential Addition-Alteration | 2014-04-23T00:00:00 | Building/Non-Residential/Addition-Alteration/NA | Finaled       | Issued        | 2015-08-18T00:00:00 | 
| Miscellaneous       | 0     | B14-1778  | Non-Residential Addition-Alteration | 2014-05-15T00:00:00 | Building/Non-Residential/Addition-Alteration/NA | Issued        | Issued        | 2015-12-03T00:00:00 | 
| Addition-Alteration | 0     | B14-2115  | Non-Residential Addition-Alteration | 2014-06-05T00:00:00 | Building/Non-Residential/Addition-Alteration/NA | Issued        | Issued        | 2015-10-14T00:00:00 | 
| Tenant Improvement  | 500   | B14-2827  | Non-Residential Addition-Alteration | 2014-07-21T00:00:00 | Building/Non-Residential/Addition-Alteration/NA | Finaled       | Issued        | 2016-03-16T00:00:00 | 
| Miscellaneous       | 0     | B14-4144  | Non-Residential Addition-Alteration | 2014-10-14T00:00:00 | Building/Non-Residential/Addition-Alteration/NA | Issued        | Issued        | 2016-04-13T00:00:00 | 
| Miscellaneous       | 0     | B14-4203  | Non-Residential Addition-Alteration | 2014-10-20T00:00:00 | Building/Non-Residential/Addition-Alteration/NA | Finaled       | Issued        | 2016-04-13T00:00:00 | 
| Tenant Improvement  | 0     | B14-4234  | Non-Residential Addition-Alteration | 2014-10-20T00:00:00 | Building/Non-Residential/Addition-Alteration/NA | Issued        | Issued        | 2015-10-29T00:00:00 | 
| Tenant Improvement  | 1924  | B14-4637  | Non-Residential Addition-Alteration | 2014-11-17T00:00:00 | Building/Non-Residential/Addition-Alteration/NA | Finaled       | Issued        | 2015-07-20T00:00:00 | 
```