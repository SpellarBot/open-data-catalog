# Levy Authority Rates By Fiscal Year

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/levy-authority-rates-by-fiscal-year) |
| Metadata | [Link](https://data.iowa.gov/api/views/xmkr-kpjb) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/xmkr-kpjb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/xmkr-kpjb/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | xmkr-kpjb |
| Name | Levy Authority Rates By Fiscal Year |
| Attribution | Iowa Department of Management, Local Budget and Finance |
| Category | Government |
| Tags | taxes, property taxes, rates, levy authorities, tif |
| Created | 2014-11-14T19:11:41Z |
| Publication Date | 2016-12-22T21:12:35Z |

## Description

This dataset contains property tax rates for all levy authorities within the State of Iowa by fiscal year.  Property tax rates are the dollars collected per $1,000 in a property's taxable value. The state fiscal year runs from July 1 to the following June 30 and is numbered for the calendar year in which it ends.  Rates for a fiscal year are based on the taxable property valuations for the preceding calendar year (e.g. FY 2014 rates are based on 2012 taxable property valuations).

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type | Render Type |
| ======== | ============== | ================== | ================== | ========= | =========== |
| Yes      | time           | fiscal_year        | Fiscal Year        | number    | number      |
| Yes      | series tag     | type               | Type               | text      | text        |
| Yes      | series tag     | levy_authority_1   | Levy Authority #   | text      | text        |
| Yes      | series tag     | levy_authority_2   | Levy Authority     | text      | text        |
| Yes      | series tag     | county_fip         | County FIP         | text      | text        |
| Yes      | series tag     | county_name        | County Name        | text      | text        |
| Yes      | series tag     | city_fips          | City FIPS          | text      | text        |
| Yes      | series tag     | city_name          | City Name          | text      | text        |
| Yes      | series tag     | co_subdivision_fip | Co Subdivision FIP | text      | text        |
| Yes      | numeric metric | urban_rate         | Urban Rate         | number    | number      |
| Yes      | numeric metric | rural_rate         | Rural Rate         | number    | number      |
| Yes      | numeric metric | debt_rate          | Debt Rate          | number    | number      |
| Yes      | numeric metric | tif_rate_urban     | TIF Rate (Urban)   | number    | number      |
| Yes      | numeric metric | tif_rate_rural     | TIF Rate (Rural)   | number    | number      |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:xmkr-kpjb d:2002-01-01T00:00:00.000Z t:county_fip=19001 t:type=COUNTY t:levy_authority_2=ADAIR t:county_name=ADAIR t:levy_authority_1=01 m:urban_rate=4.36725 m:tif_rate_urban=4.36725 m:tif_rate_rural=7.99067 m:debt_rate=0 m:rural_rate=7.99067

series e:xmkr-kpjb d:2002-01-01T00:00:00.000Z t:county_fip=19003 t:type=COUNTY t:levy_authority_2=ADAMS t:county_name=ADAMS t:levy_authority_1=02 m:urban_rate=6.10936 m:tif_rate_urban=5.96817 m:tif_rate_rural=9.20615 m:debt_rate=0.14119 m:rural_rate=9.34734

series e:xmkr-kpjb d:2002-01-01T00:00:00.000Z t:county_fip=19005 t:type=COUNTY t:levy_authority_2=ALLAMAKEE t:county_name=ALLAMAKEE t:levy_authority_1=03 m:urban_rate=6.04643 m:tif_rate_urban=6.04643 m:tif_rate_rural=8.2671 m:debt_rate=0 m:rural_rate=8.2671
```

## Meta Commands

```ls
metric m:urban_rate p:double l:"Urban Rate" d:"Rate applied to property considered urban" t:dataTypeName=number

metric m:rural_rate p:float l:"Rural Rate" d:"Rate applied to property considered rural" t:dataTypeName=number

metric m:debt_rate p:float l:"Debt Rate" d:"Rate applied to the levy authority's debt" t:dataTypeName=number

metric m:tif_rate_urban p:double l:"TIF Rate (Urban)" t:dataTypeName=number

metric m:tif_rate_rural p:float l:"TIF Rate (Rural)" t:dataTypeName=number

entity e:xmkr-kpjb l:"Levy Authority Rates By Fiscal Year" t:attribution="Iowa Department of Management, Local Budget and Finance" t:url=https://data.iowa.gov/api/views/xmkr-kpjb

property e:xmkr-kpjb t:meta.view d:2017-09-25T07:28:12.221Z v:averageRating=0 v:name="Levy Authority Rates By Fiscal Year" v:attribution="Iowa Department of Management, Local Budget and Finance" v:id=xmkr-kpjb v:category=Government

property e:xmkr-kpjb t:meta.view.license d:2017-09-25T07:28:12.221Z v:name="Public Domain"

property e:xmkr-kpjb t:meta.view.owner d:2017-09-25T07:28:12.221Z v:displayName="IDOM, Local Budget & Finance" v:profileImageUrlLarge=/api/users/58aa-5akg/profile_images/LARGE v:profileImageUrlSmall=/api/users/58aa-5akg/profile_images/TINY v:id=58aa-5akg v:screenName="IDOM, Local Budget & Finance" v:profileImageUrlMedium=/api/users/58aa-5akg/profile_images/THUMB

property e:xmkr-kpjb t:meta.view.tableauthor d:2017-09-25T07:28:12.221Z v:displayName="IDOM, Local Budget & Finance" v:profileImageUrlLarge=/api/users/58aa-5akg/profile_images/LARGE v:roleName=editor v:profileImageUrlSmall=/api/users/58aa-5akg/profile_images/TINY v:id=58aa-5akg v:screenName="IDOM, Local Budget & Finance" v:profileImageUrlMedium=/api/users/58aa-5akg/profile_images/THUMB
```

## Top Records

```ls
| fiscal_year | type   | levy_authority_1 | levy_authority_2 | county_fip | county_name | city_fips | city_name | co_subdivision_fip | urban_rate | rural_rate | debt_rate | tif_rate_urban | tif_rate_rural | 
| =========== | ====== | ================ | ================ | ========== | =========== | ========= | ========= | ================== | ========== | ========== | ========= | ============== | ============== | 
| 2002        | COUNTY | 01               | ADAIR            | 19001      | ADAIR       |           |           |                    | 4.36725    | 7.99067    | 0         | 4.36725        | 7.99067        | 
| 2002        | COUNTY | 02               | ADAMS            | 19003      | ADAMS       |           |           |                    | 6.10936    | 9.34734    | 0.14119   | 5.96817        | 9.20615        | 
| 2002        | COUNTY | 03               | ALLAMAKEE        | 19005      | ALLAMAKEE   |           |           |                    | 6.04643    | 8.2671     | 0         | 6.04643        | 8.2671         | 
| 2002        | COUNTY | 04               | APPANOOSE        | 19007      | APPANOOSE   |           |           |                    | 7.6362     | 10.68595   | 0         | 7.6362         | 10.68595       | 
| 2002        | COUNTY | 05               | AUDUBON          | 19009      | AUDUBON     |           |           |                    | 6.87524    | 11.46341   | 0.95077   | 5.92447        | 10.51264       | 
| 2002        | COUNTY | 06               | BENTON           | 19011      | BENTON      |           |           |                    | 4.16758    | 7.47983    | 0.09535   | 4.07223        | 7.38448        | 
| 2002        | COUNTY | 07               | BLACK HAWK       | 19013      | BLACK HAWK  |           |           |                    | 7.68891    | 7.68891    | 0.47949   | 7.20942        | 7.20942        | 
| 2002        | COUNTY | 08               | BOONE            | 19015      | BOONE       |           |           |                    | 4.54651    | 6.58385    | 0.50169   | 4.04482        | 6.08216        | 
| 2002        | COUNTY | 09               | BREMER           | 19017      | BREMER      |           |           |                    | 3.78584    | 7.04584    | 0.07584   | 3.71           | 6.97           | 
| 2002        | COUNTY | 10               | BUCHANAN         | 19019      | BUCHANAN    |           |           |                    | 5.37775    | 8.72179    | 0.34606   | 5.03169        | 8.37573        | 
```