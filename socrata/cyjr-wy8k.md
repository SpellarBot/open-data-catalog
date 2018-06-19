# IHDA - Illinois Housing Dev Auth - FY1970 - FY2011 Units by County

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ihda-illinois-housing-dev-auth-fy1970-fy2011-units-by-county-7099f) |
| Metadata | [Link](https://data.illinois.gov/api/views/cyjr-wy8k) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/cyjr-wy8k/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/cyjr-wy8k/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | cyjr-wy8k |
| Name | IHDA - Illinois Housing Dev Auth - FY1970 - FY2011 Units by County |
| Category | Housing |
| Tags | ihda, illinois housing development authority |
| Created | 2011-11-21T21:49:46Z |
| Publication Date | 2011-12-02T17:30:31Z |

## Description

FY1970 - FY2011 Units by County

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type | Render Type |
| ======== | ============== | ================== | ================== | ========= | =========== |
| Yes      | series tag     | county             | COUNTY             | text      | text        |
| Yes      | series tag     | mf_ho_ta           | MF/HO/TA           | text      | text        |
| Yes      | numeric metric | total_units        | TOTAL UNITS        | number    | number      |
| Yes      | numeric metric | total_ihda_dollars | TOTAL IHDA DOLLARS | money     | money       |
| Yes      | series tag     | fiscal_years       | FISCAL YEARS       | text      | text        |
```

## Time Field

```ls
Value = 1970
Format & Zone = yyyy
```

## Data Commands

```ls
series e:cyjr-wy8k d:1970-01-01T00:00:00.000Z t:fiscal_years="FY 1970 THROUGH FY 2011" t:county=ADAMS t:mf_ho_ta=MF m:total_ihda_dollars=59549703 m:total_units=1406

series e:cyjr-wy8k d:1970-01-01T00:00:00.000Z t:fiscal_years="FY 1970 THROUGH FY 2011" t:county=ADAMS t:mf_ho_ta=HO m:total_ihda_dollars=70660581 m:total_units=1624

series e:cyjr-wy8k d:1970-01-01T00:00:00.000Z t:fiscal_years="FY 1970 THROUGH FY 2011" t:county=ALEXANDER t:mf_ho_ta=HO m:total_ihda_dollars=814670 m:total_units=287
```

## Meta Commands

```ls
metric m:total_units p:integer l:"TOTAL UNITS" t:dataTypeName=number

metric m:total_ihda_dollars p:long l:"TOTAL IHDA DOLLARS" t:dataTypeName=money

entity e:cyjr-wy8k l:"IHDA - Illinois Housing Dev Auth  - FY1970 - FY2011 Units by County" t:url=https://data.illinois.gov/api/views/cyjr-wy8k

property e:cyjr-wy8k t:meta.view v:id=cyjr-wy8k v:category=Housing v:averageRating=0 v:name="IHDA - Illinois Housing Dev Auth  - FY1970 - FY2011 Units by County"

property e:cyjr-wy8k t:meta.view.owner v:id=i46z-zq8e v:screenName="Larry Michalski" v:displayName="Larry Michalski"

property e:cyjr-wy8k t:meta.view.tableauthor v:id=i46z-zq8e v:screenName="Larry Michalski" v:roleName=publisher v:displayName="Larry Michalski"
```

## Top Records

```ls
| county    | mf_ho_ta | total_units | total_ihda_dollars | fiscal_years            | 
| ========= | ======== | =========== | ================== | ======================= | 
| ADAMS     | MF       | 1406        | 59549703           | FY 1970 THROUGH FY 2011 | 
| ADAMS     | HO       | 1624        | 70660581           | FY 1970 THROUGH FY 2011 | 
| ALEXANDER | HO       | 287         | 814670             | FY 1970 THROUGH FY 2011 | 
| ALEXANDER | MF       | 59          | 2127435            | FY 1970 THROUGH FY 2011 | 
| BOND      | MF       | 54          | 3587716            | FY 1970 THROUGH FY 2011 | 
| BOND      | HO       | 410         | 9205237            | FY 1970 THROUGH FY 2011 | 
| BOONE     | HO       | 169         | 10738303           | FY 1970 THROUGH FY 2011 | 
| BOONE     | MF       | 345         | 17563294           | FY 1970 THROUGH FY 2011 | 
| BROWN     | HO       | 10          | 617563             | FY 1970 THROUGH FY 2011 | 
| BUREAU    | HO       | 137         | 4815828            | FY 1970 THROUGH FY 2011 | 
```