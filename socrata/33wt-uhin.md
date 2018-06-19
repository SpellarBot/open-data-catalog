# IDFPR Count Of Illinois State Banks In Active Status By County as of Jan 2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idfpr-count-of-illinois-state-banks-in-active-status-by-county-as-of-jan-2012-7323b) |
| Metadata | [Link](https://data.illinois.gov/api/views/33wt-uhin) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/33wt-uhin/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/33wt-uhin/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | 33wt-uhin |
| Name | IDFPR Count Of Illinois State Banks In Active Status By County as of Jan 2012 |
| Created | 2012-01-24T19:09:14Z |
| Publication Date | 2012-01-24T19:11:20Z |

## Columns

```ls
| Included | Schema Type    | Field Name   | Name         | Data Type | Render Type |
| ======== | ============== | ============ | ============ | ========= | =========== |
| Yes      | series tag     | division     | Division     | text      | text        |
| Yes      | series tag     | license_type | License Type | text      | text        |
| Yes      | series tag     | county       | County       | text      | text        |
| Yes      | numeric metric | count        | Count        | number    | number      |
```

## Time Field

```ls
Value = 2012
Format & Zone = yyyy
```

## Data Commands

```ls
series e:33wt-uhin d:2012-01-01T00:00:00.000Z t:license_type="ISB Banks & Trust Charter - Commercial/Illinois State Bank" t:division="Banks and Trust" t:county=Adams m:count=27

series e:33wt-uhin d:2012-01-01T00:00:00.000Z t:license_type="ISB Banks & Trust Charter - Commercial/Illinois State Bank" t:division="Banks and Trust" t:county=Boone m:count=3

series e:33wt-uhin d:2012-01-01T00:00:00.000Z t:license_type="ISB Banks & Trust Charter - Commercial/Illinois State Bank" t:division="Banks and Trust" t:county=Brown m:count=6
```

## Meta Commands

```ls
metric m:count p:integer l:Count t:dataTypeName=number

entity e:33wt-uhin l:"IDFPR Count Of Illinois State Banks In Active Status By County as of Jan 2012" t:url=https://data.illinois.gov/api/views/33wt-uhin

property e:33wt-uhin t:meta.view v:id=33wt-uhin v:averageRating=0 v:name="IDFPR Count Of Illinois State Banks In Active Status By County as of Jan 2012"

property e:33wt-uhin t:meta.view.license v:name="Public Domain"

property e:33wt-uhin t:meta.view.owner v:id=2jwj-ihvp v:screenName=Dfee v:displayName=Dfee

property e:33wt-uhin t:meta.view.tableauthor v:id=2jwj-ihvp v:screenName=Dfee v:displayName=Dfee
```

## Top Records

```ls
| division        | license_type                                               | county    | count | 
| =============== | ========================================================== | ========= | ===== | 
| Banks and Trust | ISB Banks & Trust Charter - Commercial/Illinois State Bank | Adams     | 27    | 
| Banks and Trust | ISB Banks & Trust Charter - Commercial/Illinois State Bank | Boone     | 3     | 
| Banks and Trust | ISB Banks & Trust Charter - Commercial/Illinois State Bank | Brown     | 6     | 
| Banks and Trust | ISB Banks & Trust Charter - Commercial/Illinois State Bank | Bureau    | 12    | 
| Banks and Trust | ISB Banks & Trust Charter - Commercial/Illinois State Bank | Calhoun   | 6     | 
| Banks and Trust | ISB Banks & Trust Charter - Commercial/Illinois State Bank | Carroll   | 12    | 
| Banks and Trust | ISB Banks & Trust Charter - Commercial/Illinois State Bank | Cass      | 6     | 
| Banks and Trust | ISB Banks & Trust Charter - Commercial/Illinois State Bank | Champaign | 21    | 
| Banks and Trust | ISB Banks & Trust Charter - Commercial/Illinois State Bank | Christian | 9     | 
| Banks and Trust | ISB Banks & Trust Charter - Commercial/Illinois State Bank | Clark     | 6     | 
```