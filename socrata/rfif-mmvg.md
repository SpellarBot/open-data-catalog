# Recycling Schedules

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/recycling-schedules) |
| Metadata | [Link](https://data.austintexas.gov/api/views/rfif-mmvg) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/rfif-mmvg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/rfif-mmvg/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | rfif-mmvg |
| Name | Recycling Schedules |
| Attribution | City of Austin |
| Category | Government |
| Tags | recycle, resource, trash, brush collection, bulky, recycling |
| Created | 2012-07-18T14:09:39Z |
| Publication Date | 2013-03-07T22:12:31Z |

## Description

Listing of all recycling schedules city wide.

## Columns

```ls
| Included | Schema Type | Field Name      | Name            | Data Type | Render Type |
| ======== | =========== | =============== | =============== | ========= | =========== |
| No       | time        | :updated_at     | updated_at      | meta_data | meta_data   |
| Yes      | series tag  | house_no        | HOUSE_NO        | text      | text        |
| Yes      | series tag  | fraction        | FRACTION        | text      | text        |
| Yes      | series tag  | hse_suff        | HSE_SUFF        | text      | text        |
| Yes      | series tag  | street_nam      | STREET_NAM      | text      | text        |
| Yes      | series tag  | street_typ      | STREET_TYP      | text      | text        |
| Yes      | series tag  | st_dir          | ST_DIR          | text      | text        |
| Yes      | series tag  | unit_no         | UNIT_NO         | text      | text        |
| Yes      | series tag  | city            | CITY            | text      | text        |
| Yes      | series tag  | state           | STATE           | text      | text        |
| Yes      | series tag  | zip             | ZIP             | text      | number      |
| Yes      | series tag  | collection_day  | COLLECTION DAY  | text      | text        |
| No       |             | collection_week | COLLECTION WEEK | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = collection_week
```

## Data Commands

```ls
series e:rfif-mmvg d:2013-03-07T13:43:59.000Z t:hse_suff=B t:zip=78702 t:collection_day=FRIDAY t:street_nam=WILLOW t:house_no=1610 t:state=TX t:street_typ=ST t:city=AUSTIN m:row_number.rfif-mmvg=1

series e:rfif-mmvg d:2013-03-07T13:43:59.000Z t:zip=78702 t:collection_day=FRIDAY t:street_nam=ROSEWOOD t:house_no=1705 t:state=TX t:street_typ=AVE t:city=AUSTIN m:row_number.rfif-mmvg=2

series e:rfif-mmvg d:2013-03-07T13:43:59.000Z t:zip=78703 t:collection_day=FRIDAY t:street_nam=8TH t:st_dir=W t:house_no=1201 t:state=TX t:unit_no="UNIT 201" t:street_typ=ST t:city=AUSTIN m:row_number.rfif-mmvg=3
```

## Meta Commands

```ls
metric m:row_number.rfif-mmvg p:long l:"Row Number"

entity e:rfif-mmvg l:"Recycling Schedules" t:attribution="City of Austin" t:url=https://data.austintexas.gov/api/views/rfif-mmvg

property e:rfif-mmvg t:meta.view v:id=rfif-mmvg v:category=Government v:attributionLink=http://www.austintexas.gov v:averageRating=0 v:name="Recycling Schedules" v:attribution="City of Austin"

property e:rfif-mmvg t:meta.view.owner v:id=99uc-9byy v:screenName=opendataatx v:displayName=opendataatx

property e:rfif-mmvg t:meta.view.tableauthor v:id=99uc-9byy v:screenName=opendataatx v:roleName=administrator v:displayName=opendataatx
```

## Top Records

```ls
| :updated_at | house_no | fraction | hse_suff | street_nam | street_typ | st_dir | unit_no  | city   | state | zip   | collection_day | collection_week | 
| =========== | ======== | ======== | ======== | ========== | ========== | ====== | ======== | ====== | ===== | ===== | ============== | =============== | 
| 1362663839  | 1610     |          | B        | WILLOW     | ST         |        |          | AUSTIN | TX    | 78702 | FRIDAY         | A               | 
| 1362663839  | 1705     |          |          | ROSEWOOD   | AVE        |        |          | AUSTIN | TX    | 78702 | FRIDAY         | A               | 
| 1362663839  | 1201     |          |          | 8TH        | ST         | W      | UNIT 201 | AUSTIN | TX    | 78703 | FRIDAY         | A               | 
| 1362663839  | 1118     |          |          | DESIRABLE  | DR         |        |          | AUSTIN | TX    | 78721 | FRIDAY         | A               | 
| 1362663839  | 1305     |          |          | EXPOSITION | BLVD       |        | UNIT 4   | AUSTIN | TX    | 78703 | FRIDAY         | A               | 
| 1362663839  | 1807     |          |          | 16TH       | ST         | E      |          | AUSTIN | TX    | 78702 | FRIDAY         | A               | 
| 1362663839  | 704      |          |          | WALLER     | ST         |        |          | AUSTIN | TX    | 78702 | FRIDAY         | A               | 
| 1362663839  | 1610     |          | A        | WILLOW     | ST         |        |          | AUSTIN | TX    | 78702 | FRIDAY         | A               | 
| 1362663839  | 1412     |          |          | WILLOW     | ST         |        | UNIT 1   | AUSTIN | TX    | 78702 | FRIDAY         | A               | 
| 1362663839  | 1401     |          |          | HOLLY      | ST         |        |          | AUSTIN | TX    | 78702 | FRIDAY         | A               | 
```