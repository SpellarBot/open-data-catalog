# Notice of Medallion Transfers

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/notice-of-medallion-transfers) |
| Metadata | [Link](https://data.seattle.gov/api/views/rk6r-ehyv) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/rk6r-ehyv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/rk6r-ehyv/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | rk6r-ehyv |
| Name | Notice of Medallion Transfers |
| Attribution | City of Seattle, Consumer Protection Unit |
| Category | City Business |
| Tags | taxi, medallion, for-hire, tnc |
| Created | 2015-03-23T20:17:56Z |
| Publication Date | 2017-04-20T19:03:17Z |

## Description

This data set includes all transfer dates and values of taxicab and for-hire vehicle medallions.

## Columns

```ls
| Included | Schema Type | Field Name             | Name                   | Data Type | Render Type |
| ======== | =========== | ====================== | ====================== | ========= | =========== |
| No       | time        | :updated_at            | updated_at             | meta_data | meta_data   |
| Yes      | series tag  | medallion_number       | Medallion Number       | text      | text        |
| Yes      | series tag  | medallion_holder_name  | Medallion Holder Name  | text      | text        |
| No       |             | proposed_transfer_date | Proposed Transfer Date | text      | text        |
| No       |             | application_date       | Application Date       | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = proposed_transfer_date,application_date
```

## Data Commands

```ls
series e:rk6r-ehyv d:2015-04-15T16:43:29.000Z t:medallion_number=2049 t:medallion_holder_name="Fanaye Taye Debalke" m:row_number.rk6r-ehyv=1

series e:rk6r-ehyv d:2015-04-20T13:10:12.000Z t:medallion_number=2913 t:medallion_holder_name="Universal Transportation & Translation Inc" m:row_number.rk6r-ehyv=2

series e:rk6r-ehyv d:2015-04-20T13:10:37.000Z t:medallion_number=2408 t:medallion_holder_name="Universal Transportation & Translation Inc" m:row_number.rk6r-ehyv=3
```

## Meta Commands

```ls
metric m:row_number.rk6r-ehyv p:long l:"Row Number"

entity e:rk6r-ehyv l:"Notice of Medallion Transfers" t:attribution="City of Seattle, Consumer Protection Unit" t:url=https://data.seattle.gov/api/views/rk6r-ehyv

property e:rk6r-ehyv t:meta.view v:id=rk6r-ehyv v:category="City Business" v:averageRating=0 v:name="Notice of Medallion Transfers" v:attribution="City of Seattle, Consumer Protection Unit"

property e:rk6r-ehyv t:meta.view.owner v:id=a62b-aawc v:screenName="Consumer Protection Unit, FAS" v:displayName="Consumer Protection Unit, FAS"

property e:rk6r-ehyv t:meta.view.tableauthor v:id=a62b-aawc v:screenName="Consumer Protection Unit, FAS" v:roleName=publisher v:displayName="Consumer Protection Unit, FAS"
```

## Top Records

```ls
| :updated_at | medallion_number | medallion_holder_name                      | proposed_transfer_date | application_date | 
| =========== | ================ | ========================================== | ====================== | ================ | 
| 1429116209  | 2049             | Fanaye Taye Debalke                        | 04/29/15               | 04/15/15         | 
| 1429535412  | 2913             | Universal Transportation & Translation Inc | 04/17/15               | 04/03/15         | 
| 1429535437  | 2408             | Universal Transportation & Translation Inc | 04/17/15               | 04/03/15         | 
| 1429535560  | 868              | Bashir A Mohamed                           | 04/17/15               | 04/03/15         | 
| 1429535632  | 2070             | Sakariye O Salim                           | 04/20/15               | 04/06/15         | 
| 1429535672  | 2078             | Elhadj Diallo                              | 04/21/15               | 04/08/15         | 
| 1429535724  | 2474             | Issayas Berhe                              | 04/24/15               | 04/10/15         | 
| 1429535798  | 880              | Joginder Singh Bhandal                     | 04/24/15               | 04/10/15         | 
| 1429535874  | 2019             | Abdirizak Shiregaab                        | 04/24/15               | 04/10/15         | 
| 1429535910  | 2908             | Universal Transportation & Translation Inc | 04/27/15               | 04/13/15         | 
```