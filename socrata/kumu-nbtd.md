# 911 Addressing - Street Name Master List

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/911-addressing-street-name-master-list) |
| Metadata | [Link](https://data.austintexas.gov/api/views/kumu-nbtd) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/kumu-nbtd/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/kumu-nbtd/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | kumu-nbtd |
| Name | 911 Addressing - Street Name Master List |
| Attribution | CTM - 911 Addressing |
| Category | Public Safety |
| Tags | street name, address, active, reserved, reservation |
| Created | 2015-03-13T15:52:40Z |
| Publication Date | 2016-04-28T15:56:11Z |

## Description

Street Name Master List - contains all the reserved and active street names.

## Columns

```ls
| Included | Schema Type | Field Name  | Name        | Data Type | Render Type |
| ======== | =========== | =========== | =========== | ========= | =========== |
| No       | time        | :updated_at | updated_at  | meta_data | meta_data   |
| Yes      | series tag  | direction   | PRE DIR     | text      | text        |
| Yes      | series tag  | pre_type    | PRE TYPE    | text      | text        |
| Yes      | series tag  | street_name | STREET NAME | text      | text        |
| Yes      | series tag  | street_type | STREET TYPE | text      | text        |
| Yes      | series tag  | status      | STATUS      | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:kumu-nbtd d:2016-04-28T08:55:26.000Z t:status=ACTIVE t:direction=W t:street_name="WELLS BRANCH" t:street_type=PKWY m:row_number.kumu-nbtd=1

series e:kumu-nbtd d:2016-04-28T08:55:26.000Z t:status=ACTIVE t:direction=W t:street_name="WELLS BRANCH" t:street_type=PKWY m:row_number.kumu-nbtd=2

series e:kumu-nbtd d:2016-04-28T08:55:26.000Z t:status=ACTIVE t:direction=W t:street_name="CARRIE MANOR" t:street_type=ST m:row_number.kumu-nbtd=3
```

## Meta Commands

```ls
metric m:row_number.kumu-nbtd p:long l:"Row Number"

entity e:kumu-nbtd l:"911 Addressing - Street Name Master List" t:attribution="CTM - 911 Addressing" t:url=https://data.austintexas.gov/api/views/kumu-nbtd

property e:kumu-nbtd t:meta.view v:id=kumu-nbtd v:category="Public Safety" v:averageRating=0 v:name="911 Addressing - Street Name Master List" v:attribution="CTM - 911 Addressing"

property e:kumu-nbtd t:meta.view.owner v:id=rt4g-ttsy v:screenName=jjmoczygemba v:displayName=jjmoczygemba

property e:kumu-nbtd t:meta.view.tableauthor v:id=rt4g-ttsy v:screenName=jjmoczygemba v:roleName=editor v:displayName=jjmoczygemba
```

## Top Records

```ls
| :updated_at | direction | pre_type | street_name  | street_type | status | 
| =========== | ========= | ======== | ============ | =========== | ====== | 
| 1461833726  | W         |          | WELLS BRANCH | PKWY        | ACTIVE | 
| 1461833726  | W         |          | WELLS BRANCH | PKWY        | ACTIVE | 
| 1461833726  | W         |          | CARRIE MANOR | ST          | ACTIVE | 
| 1461833726  | W         |          | CESAR CHAVEZ | ST          | ACTIVE | 
| 1461833726  | W         |          | CROSLIN      | ST          | ACTIVE | 
| 1461833726  | W         |          | ELLIOTT      | ST          | ACTIVE | 
| 1461833726  | W         |          | FIRST        | ST          | ACTIVE | 
| 1461833726  | W         |          | GIBSON       | ST          | ACTIVE | 
| 1461833726  | W         |          | GUADALUPE    | ST          | ACTIVE | 
| 1461833726  | W         |          | HALL         | ST          | ACTIVE | 
```