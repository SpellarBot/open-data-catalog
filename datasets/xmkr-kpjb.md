# Levy Authority Rates By Fiscal Year

## Dataset

* [Dataset URL](https://data.iowa.gov/api/views/xmkr-kpjb/rows.json?accessType=DOWNLOAD)
* [Catalog URL](https://catalog.data.gov/dataset/levy-authority-rates-by-fiscal-year)
* Id = xmkr-kpjb
* Name = Levy Authority Rates By Fiscal Year
* Attribution = Iowa Department of Management, Local Budget and Finance
* Category = Government
* Tags = [taxes, property taxes, rates, levy authorities, tif]
* Created = 2014-11-14T19:11:41Z
* Publication Date = 2016-12-22T21:12:35Z
* Rows Updated = 2016-12-22T21:12:08Z

## Description

This dataset contains property tax rates for all levy authorities within the State of Iowa by fiscal year.  Property tax rates are the dollars collected per $1,000 in a property's taxable value. The state fiscal year runs from July 1 to the following June 30 and is numbered for the calendar year in which it ends.  Rates for a fiscal year are based on the taxable property valuations for the preceding calendar year (e.g. FY 2014 rates are based on 2012 taxable property valuations).

## Columns

```ls
| Name               | Field Name         | Data Type | Render Type | Schema Type    | Included | 
| ================== | ================== | ========= | =========== | ============== | ======== | 
| Fiscal Year        | fiscal_year        | number    | number      | time           | Yes      | 
| Type               | type               | text      | text        | series tag     | Yes      | 
| Levy Authority #   | levy_authority_1   | text      | text        | series tag     | Yes      | 
| Levy Authority     | levy_authority_2   | text      | text        | series tag     | Yes      | 
| County FIP         | county_fip         | number    | text        | numeric metric | Yes      | 
| County Name        | county_name        | text      | text        | series tag     | Yes      | 
| City FIPS          | city_fips          | number    | text        | numeric metric | Yes      | 
| City Name          | city_name          | text      | text        | series tag     | Yes      | 
| Co Subdivision FIP | co_subdivision_fip | number    | text        | numeric metric | Yes      | 
| Urban Rate         | urban_rate         | number    | number      | numeric metric | Yes      | 
| Rural Rate         | rural_rate         | number    | number      | numeric metric | Yes      | 
| Debt Rate          | debt_rate          | number    | number      | numeric metric | Yes      | 
| TIF Rate (Urban)   | tif_rate_urban     | number    | number      | numeric metric | Yes      | 
| TIF Rate (Rural)   | tif_rate_rural     | number    | number      | numeric metric | Yes      | 
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy
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
series e:xmkr-kpjb d:2002-01-01T00:00:00.000Z t:levy_authority_2=ADAIR t:levy_authority_1=01 t:type=COUNTY t:county_name=ADAIR m:tif_rate_rural=7.99067 m:debt_rate=0 m:tif_rate_urban=4.36725 m:county_fip=19001 m:rural_rate=7.99067 m:urban_rate=4.36725

series e:xmkr-kpjb d:2002-01-01T00:00:00.000Z t:levy_authority_2=ADAMS t:levy_authority_1=02 t:type=COUNTY t:county_name=ADAMS m:tif_rate_rural=9.20615 m:debt_rate=0.14119 m:tif_rate_urban=5.96817 m:county_fip=19003 m:rural_rate=9.34734 m:urban_rate=6.10936

series e:xmkr-kpjb d:2002-01-01T00:00:00.000Z t:levy_authority_2=ALLAMAKEE t:levy_authority_1=03 t:type=COUNTY t:county_name=ALLAMAKEE m:tif_rate_rural=8.2671 m:debt_rate=0 m:tif_rate_urban=6.04643 m:county_fip=19005 m:rural_rate=8.2671 m:urban_rate=6.04643
```

## Meta Commands

```ls
metric m:county_fip p:integer l:"County FIP" d:"A five-digit Federal Information Processing Series code to ensure uniform identification of counties" t:dataTypeName=number

metric m:city_fips p:integer l:"City FIPS" d:"A seven-digit Federal Information Processing Series code to ensure uniform identification of cities and other populated places" t:dataTypeName=number

metric m:co_subdivision_fip p:integer l:"Co Subdivision FIP" d:"A ten-digit Federal Information Processing Series code to ensure uniform identification of county subdivisions" t:dataTypeName=number

metric m:urban_rate p:integer l:"Urban Rate" d:"Rate applied to property considered urban" t:dataTypeName=number

metric m:rural_rate l:"Rural Rate" d:"Rate applied to property considered rural" t:dataTypeName=number

metric m:debt_rate l:"Debt Rate" d:"Rate applied to the levy authority's debt" t:dataTypeName=number

metric m:tif_rate_urban l:"TIF Rate (Urban)" t:dataTypeName=number

metric m:tif_rate_rural l:"TIF Rate (Rural)" t:dataTypeName=number

entity e:xmkr-kpjb l:"Levy Authority Rates By Fiscal Year" t:attribution="Iowa Department of Management, Local Budget and Finance" t:url=https://data.iowa.gov/api/views/xmkr-kpjb

property e:xmkr-kpjb t:meta.view d:2017-03-03T14:31:18.293Z v:id=xmkr-kpjb v:category=Government v:averageRating=0 v:name="Levy Authority Rates By Fiscal Year" v:attribution="Iowa Department of Management, Local Budget and Finance"

property e:xmkr-kpjb t:meta.view.license d:2017-03-03T14:31:18.293Z v:name="Public Domain"

property e:xmkr-kpjb t:meta.view.owner d:2017-03-03T14:31:18.293Z v:id=58aa-5akg v:profileImageUrlMedium=/api/users/58aa-5akg/profile_images/THUMB v:profileImageUrlLarge=/api/users/58aa-5akg/profile_images/LARGE v:screenName="IDOM, Local Budget & Finance" v:profileImageUrlSmall=/api/users/58aa-5akg/profile_images/TINY v:roleName=editor v:displayName="IDOM, Local Budget & Finance"

property e:xmkr-kpjb t:meta.view.tableauthor d:2017-03-03T14:31:18.293Z v:id=58aa-5akg v:profileImageUrlMedium=/api/users/58aa-5akg/profile_images/THUMB v:profileImageUrlLarge=/api/users/58aa-5akg/profile_images/LARGE v:screenName="IDOM, Local Budget & Finance" v:profileImageUrlSmall=/api/users/58aa-5akg/profile_images/TINY v:roleName=editor v:displayName="IDOM, Local Budget & Finance"
```