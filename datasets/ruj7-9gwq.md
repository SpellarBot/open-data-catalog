# Address Changes

## Dataset

* [Dataset URL](https://data.austintexas.gov/api/views/ruj7-9gwq/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/address-changes-a788c)
* [Metadata URL](https://data.austintexas.gov/api/views/ruj7-9gwq)
* Id = ruj7-9gwq
* Name = Address Changes
* Created = 2016-09-30T20:18:41Z
* Publication Date = 2016-09-30T20:23:07Z
* Rows Updated = 2017-03-07T02:30:48Z

## Description



## Columns

```ls
| Name            | Field Name      | Data Type     | Render Type   | Schema Type    | Included | 
| =============== | =============== | ============= | ============= | ============== | ======== | 
| OLD HOUSE #     | old_house       | number        | text          | numeric metric | Yes      | 
| OLD FRACTION    | old_fraction    | text          | text          | series tag     | Yes      | 
| OLD DIR         | old_dir         | text          | text          | series tag     | Yes      | 
| OLD STREET NAME | old_street_name | text          | text          | series tag     | Yes      | 
| OLD TYPE        | old_type        | text          | text          | series tag     | Yes      | 
| OLD BLDG        | old_bldg        | number        | text          | numeric metric | Yes      | 
| OLD UNIT        | old_unit        | text          | text          | series tag     | Yes      | 
| NEW HOUSE #     | new_house       | number        | text          | numeric metric | Yes      | 
| NEW FRACTION    | new_fraction    | text          | text          | series tag     | Yes      | 
| NEW DIR         | new_dir         | text          | text          | series tag     | Yes      | 
| NEW STREET NAME | new_street_name | text          | text          | series tag     | Yes      | 
| NEW TYPE        | new_type        | text          | text          | series tag     | Yes      | 
| NEW BLDG        | new_bldg        | number        | text          | numeric metric | Yes      | 
| NEW UNIT        | new_unit        | text          | text          | series tag     | Yes      | 
| EFFECTIVE DATE  | effective_date  | calendar_date | calendar_date | time           | Yes      | 
| TAX ID          | tax_id          | text          | text          | series tag     | Yes      | 
| KEY NUMBER      | key_number      | number        | number        | numeric metric | Yes      | 
```

## Time Field

```ls
Value = effective_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = 
Annotation Fields = 
```

## Data Commands

```ls
series e:ruj7-9gwq d:2016-09-26T00:00:00.000Z t:new_type=LN t:old_type=LN t:old_street_name=WINSTED t:new_street_name=WINSTED t:tax_id=0115040605 m:key_number=14121 m:new_house=2400 m:new_bldg=2 m:old_house=2400

series e:ruj7-9gwq d:2016-09-12T00:00:00.000Z t:new_type=DR t:old_type=DR t:old_street_name="IVALENES HOPE" t:new_street_name="IVALENES HOPE" t:tax_id=R498117 m:key_number=13960 m:new_house=9200 m:old_house=9200

series e:ruj7-9gwq d:2016-09-06T00:00:00.000Z t:new_type=RD t:old_unit=25-B t:old_type=RD t:old_street_name=969 t:new_street_name=969 t:tax_id=0210310512 t:new_unit=31 m:key_number=13921 m:new_house=9308 m:old_house=9308
```

## Meta Commands

```ls
metric m:old_house p:integer l:"OLD HOUSE #" t:dataTypeName=number

metric m:new_house p:integer l:"NEW HOUSE #" t:dataTypeName=number

metric m:key_number p:integer l:"KEY NUMBER" t:dataTypeName=number

entity e:ruj7-9gwq l:"Address Changes" t:url=https://data.austintexas.gov/api/views/ruj7-9gwq

property e:ruj7-9gwq t:meta.view d:2017-03-08T02:15:03.288Z v:id=ruj7-9gwq v:averageRating=0 v:name="Address Changes"

property e:ruj7-9gwq t:meta.view.owner d:2017-03-08T02:15:03.288Z v:id=52wx-7e7j v:screenName="EGS Data Services" v:roleName=publisher v:displayName="EGS Data Services"

property e:ruj7-9gwq t:meta.view.tableauthor d:2017-03-08T02:15:03.288Z v:id=52wx-7e7j v:screenName="EGS Data Services" v:roleName=publisher v:displayName="EGS Data Services"
```