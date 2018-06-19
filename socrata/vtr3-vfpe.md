# Underlying Credit Ratings for DBF

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/underlying-credit-ratings-for-dbf-5d5bc) |
| Metadata | [Link](https://data.hawaii.gov/api/views/vtr3-vfpe) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/vtr3-vfpe/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/vtr3-vfpe/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | vtr3-vfpe |
| Name | Underlying Credit Ratings for DBF |
| Attribution | State of Hawaii, Department of Budget and Finance |
| Category | Economic Development |
| Tags | investor relations |
| Created | 2013-12-05T20:55:02Z |
| Publication Date | 2013-12-05T21:02:12Z |

## Description

Underlying Credit Ratings for State of Hawaii, Department of Budget and Finance

## Columns

```ls
| Included | Schema Type | Field Name   | Name         | Data Type | Render Type |
| ======== | =========== | ============ | ============ | ========= | =========== |
| No       | time        | :updated_at  | updated_at   | meta_data | meta_data   |
| Yes      | series tag  | type_of_debt | Type of Debt | text      | text        |
| Yes      | series tag  | fitch        | Fitch        | text      | text        |
| Yes      | series tag  | moody_s      | Moody's      | text      | text        |
| Yes      | series tag  | s_p          | S&P          | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:vtr3-vfpe d:2013-12-05T12:59:35.000Z t:type_of_debt="General Obligation Bonds" t:s_p=AA t:fitch=AA t:moody_s=Aa2 m:row_number.vtr3-vfpe=1

series e:vtr3-vfpe d:2013-12-05T12:59:55.000Z t:type_of_debt="Certificates of Participation" t:s_p=AA- t:fitch=AA- t:moody_s=Aa3 m:row_number.vtr3-vfpe=2
```

## Meta Commands

```ls
metric m:row_number.vtr3-vfpe p:long l:"Row Number"

entity e:vtr3-vfpe l:"Underlying Credit Ratings for DBF" t:attribution="State of Hawaii, Department of Budget and Finance" t:url=https://data.hawaii.gov/api/views/vtr3-vfpe

property e:vtr3-vfpe t:meta.view v:id=vtr3-vfpe v:category="Economic Development" v:attributionLink=http://budget.hawaii.gov v:averageRating=0 v:name="Underlying Credit Ratings for DBF" v:attribution="State of Hawaii, Department of Budget and Finance"

property e:vtr3-vfpe t:meta.view.license v:name="Public Domain"

property e:vtr3-vfpe t:meta.view.owner v:id=jwwb-qd4m v:screenName=dtakashima v:displayName=dtakashima

property e:vtr3-vfpe t:meta.view.tableauthor v:id=jwwb-qd4m v:screenName=dtakashima v:roleName=publisher v:displayName=dtakashima
```

## Top Records

```ls
| :updated_at | type_of_debt                  | fitch | moody_s | s_p | 
| =========== | ============================= | ===== | ======= | === | 
| 1386248375  | General Obligation Bonds      | AA    | Aa2     | AA  | 
| 1386248395  | Certificates of Participation | AA-   | Aa3     | AA- | 
```