# HDOA TEST Dataset

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/hdoa-test-dataset-660be) |
| Metadata | [Link](https://data.hawaii.gov/api/views/mx7k-fnvb) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/mx7k-fnvb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/mx7k-fnvb/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | mx7k-fnvb |
| Name | HDOA TEST Dataset |
| Created | 2014-12-11T01:09:39Z |
| Publication Date | 2015-03-10T02:27:35Z |

## Description

Updated HDOA Registered Livestock brand with brand picture included in the dataset.

## Columns

```ls
| Included | Schema Type | Field Name  | Name       | Data Type | Render Type |
| ======== | =========== | =========== | ========== | ========= | =========== |
| No       | time        | :updated_at | updated_at | meta_data | meta_data   |
| No       |             | addressid   | AddressID  | text      | number      |
| Yes      | series tag  | ranchname   | RanchName  | text      | text        |
| Yes      | series tag  | firstname   | FirstName  | text      | text        |
| Yes      | series tag  | lastname    | LastName   | text      | text        |
| Yes      | series tag  | brand_type  | Brand Type | text      | text        |
| Yes      | series tag  | reg_number  | reg_number | text      | number      |
| Yes      | series tag  | island      | Island     | text      | text        |
| Yes      | series tag  | image       | Image      | photo     | photo       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = addressid
```

## Data Commands

```ls
series e:mx7k-fnvb d:2014-12-10T17:09:44.000Z t:ranchname="ACKERMAN RANCH" t:island=H m:row_number.mx7k-fnvb=1

series e:mx7k-fnvb d:2014-12-10T17:09:44.000Z t:lastname=AGUIAR t:ranchname=KIPAPA t:firstname="LEROY K." t:island=K m:row_number.mx7k-fnvb=2

series e:mx7k-fnvb d:2014-12-10T17:09:44.000Z t:lastname=ABREU t:firstname="MICHAEL JOHN" t:island=M m:row_number.mx7k-fnvb=3
```

## Meta Commands

```ls
metric m:row_number.mx7k-fnvb p:long l:"Row Number"

entity e:mx7k-fnvb l:"HDOA TEST Dataset" t:url=https://data.hawaii.gov/api/views/mx7k-fnvb

property e:mx7k-fnvb t:meta.view v:id=mx7k-fnvb v:averageRating=0 v:name="HDOA TEST Dataset"

property e:mx7k-fnvb t:meta.view.owner v:id=g4by-tkv4 v:screenName=CHUN-JU v:displayName=CHUN-JU

property e:mx7k-fnvb t:meta.view.tableauthor v:id=g4by-tkv4 v:screenName=CHUN-JU v:roleName=publisher v:displayName=CHUN-JU
```

## Top Records

```ls
| :updated_at | addressid | ranchname      | firstname    | lastname   | brand_type | reg_number | island | image | 
| =========== | ========= | ============== | ============ | ========== | ========== | ========== | ====== | ===== | 
| 1418231384  | 6         | ACKERMAN RANCH |              |            |            |            | H      |       | 
| 1418231384  | 10        | KIPAPA         | LEROY K.     | AGUIAR     |            |            | K      |       | 
| 1418231384  | 11        |                | MICHAEL JOHN | ABREU      |            |            | M      |       | 
| 1418231384  | 12        | KIPAPA         | LEROY K.     | AGUIAR     |            |            | K      |       | 
| 1418231384  | 17        |                | ANDREW A.    | AKAU, SR   |            |            | H      |       | 
| 1418231384  | 22        | SUNSHINE RANCH | JAMES P.     | AKIONA     |            |            | H      |       | 
| 1418231384  | 23        |                | LESLIE KELII | ALAPAI     |            |            | K      |       | 
| 1418231384  | 25        |                | HELEN MARIE  | ALENCASTRE |            |            | M      |       | 
| 1418231384  | 33        | ANDRADE RANCH  | ALFRED       | ANDRADE    |            |            | H      |       | 
| 1418231384  | 34        | ANDRADE RANCH  | ALFRED       | ANDRADE    |            |            | H      |       | 
```