# ACRIS - Country Codes

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/acris-country-codes-e0490) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/j2iz-mwzu) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/j2iz-mwzu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/j2iz-mwzu/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | j2iz-mwzu |
| Name | ACRIS - Country Codes |
| Attribution | Department of Finance (DOF) |
| Category | City Government |
| Tags | dof, acris land records |
| Created | 2013-09-16T18:17:14Z |
| Publication Date | 2017-04-08T20:03:25Z |

## Description

ACRIS Countries mapping for Codes in the ACRIS Real and Personal Parties Property Datasets

## Columns

```ls
| Included | Schema Type | Field Name   | Name         | Data Type | Render Type |
| ======== | =========== | ============ | ============ | ========= | =========== |
| No       | time        | :updated_at  | updated_at   | meta_data | meta_data   |
| Yes      | series tag  | record_type  | RECORD TYPE  | text      | text        |
| Yes      | series tag  | country_code | COUNTRY CODE | text      | text        |
| Yes      | series tag  | description  | DESCRIPTION  | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:j2iz-mwzu d:2017-04-08T20:03:21.000Z t:record_type=T t:description=ARGENTINA t:country_code=AR m:row_number.j2iz-mwzu=1

series e:j2iz-mwzu d:2017-04-08T20:03:21.000Z t:record_type=T t:description=AUSTRALIA t:country_code=AU m:row_number.j2iz-mwzu=2

series e:j2iz-mwzu d:2017-04-08T20:03:21.000Z t:record_type=T t:description=AUSTRIA t:country_code=AT m:row_number.j2iz-mwzu=3
```

## Meta Commands

```ls
metric m:row_number.j2iz-mwzu p:long l:"Row Number"

entity e:j2iz-mwzu l:"ACRIS - Country Codes" t:attribution="Department of Finance (DOF)" t:url=https://data.cityofnewyork.us/api/views/j2iz-mwzu

property e:j2iz-mwzu t:meta.view v:id=j2iz-mwzu v:category="City Government" v:averageRating=0 v:name="ACRIS - Country Codes" v:attribution="Department of Finance (DOF)"

property e:j2iz-mwzu t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:j2iz-mwzu t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | record_type | country_code | description | 
| =========== | =========== | ============ | =========== | 
| 1491681801  | T           | AR           | ARGENTINA   | 
| 1491681801  | T           | AU           | AUSTRALIA   | 
| 1491681801  | T           | AT           | AUSTRIA     | 
| 1491681801  | T           | BS           | BAHAMAS     | 
| 1491681801  | T           | BE           | BELGIUM     | 
| 1491681801  | T           | BO           | BOLIVIA     | 
| 1491681801  | T           | BR           | BRAZIL      | 
| 1491681801  | T           | CA           | CANADA      | 
| 1491681801  | T           | CL           | CHILE       | 
| 1491681801  | T           | CN           | CHINA       | 
```