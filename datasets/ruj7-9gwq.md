# Address Changes

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/address-changes-a788c) |
| Metadata | [Link](https://data.austintexas.gov/api/views/ruj7-9gwq) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/ruj7-9gwq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/ruj7-9gwq/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | ruj7-9gwq |
| Name | Address Changes |
| Created | 2016-09-30T20:18:41Z |
| Publication Date | 2016-09-30T20:23:07Z |
| Rows Updated | 2017-03-23T01:30:36Z |

## Columns

```ls
| Included | Schema Type | Field Name      | Name            | Data Type     | Render Type   |
| ======== | =========== | =============== | =============== | ============= | ============= |
| Yes      | series tag  | old_house       | OLD HOUSE #     | text          | text          |
| Yes      | series tag  | old_fraction    | OLD FRACTION    | text          | text          |
| Yes      | series tag  | old_dir         | OLD DIR         | text          | text          |
| Yes      | series tag  | old_street_name | OLD STREET NAME | text          | text          |
| Yes      | series tag  | old_type        | OLD TYPE        | text          | text          |
| Yes      | series tag  | old_bldg        | OLD BLDG        | text          | text          |
| Yes      | series tag  | old_unit        | OLD UNIT        | text          | text          |
| Yes      | series tag  | new_house       | NEW HOUSE #     | text          | text          |
| Yes      | series tag  | new_fraction    | NEW FRACTION    | text          | text          |
| Yes      | series tag  | new_dir         | NEW DIR         | text          | text          |
| Yes      | series tag  | new_street_name | NEW STREET NAME | text          | text          |
| Yes      | series tag  | new_type        | NEW TYPE        | text          | text          |
| Yes      | series tag  | new_bldg        | NEW BLDG        | text          | text          |
| Yes      | series tag  | new_unit        | NEW UNIT        | text          | text          |
| Yes      | time        | effective_date  | EFFECTIVE DATE  | calendar_date | calendar_date |
| Yes      | series tag  | tax_id          | TAX ID          | text          | text          |
| Yes      | series tag  | key_number      | KEY NUMBER      | text          | number        |
```

## Time Field

```ls
Value = effective_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:ruj7-9gwq d:2016-09-26T00:00:00.000Z t:new_type=LN t:old_type=LN t:old_street_name=WINSTED t:key_number=14121 t:new_street_name=WINSTED t:new_house=2400 t:new_bldg=2 t:tax_id=0115040605 t:old_house=2400 m:row_number.ruj7-9gwq=1

series e:ruj7-9gwq d:2016-09-12T00:00:00.000Z t:new_type=DR t:old_type=DR t:old_street_name="IVALENES HOPE" t:key_number=13960 t:new_street_name="IVALENES HOPE" t:new_house=9200 t:tax_id=R498117 t:old_house=9200 m:row_number.ruj7-9gwq=2

series e:ruj7-9gwq d:2016-09-06T00:00:00.000Z t:new_type=RD t:old_unit=25-B t:old_type=RD t:old_street_name=969 t:key_number=13921 t:new_street_name=969 t:new_house=9308 t:tax_id=0210310512 t:new_unit=31 t:old_house=9308 m:row_number.ruj7-9gwq=3
```

## Meta Commands

```ls
metric m:row_number.ruj7-9gwq p:long l:"Row Number"

entity e:ruj7-9gwq l:"Address Changes" t:url=https://data.austintexas.gov/api/views/ruj7-9gwq

property e:ruj7-9gwq t:meta.view v:id=ruj7-9gwq v:averageRating=0 v:name="Address Changes"

property e:ruj7-9gwq t:meta.view.owner v:id=52wx-7e7j v:screenName="EGS Data Services" v:displayName="EGS Data Services"

property e:ruj7-9gwq t:meta.view.tableauthor v:id=52wx-7e7j v:screenName="EGS Data Services" v:roleName=publisher v:displayName="EGS Data Services"
```