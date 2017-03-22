# 2013 Housing Inventory

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2013-housing-inventory-b6675) |
| Metadata | [Link](https://data.sfgov.org/api/views/e7d3-dxh5) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/e7d3-dxh5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/e7d3-dxh5/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | e7d3-dxh5 |
| Name | 2013 Housing Inventory |
| Attribution | San Francisco Planning Department |
| Category | Housing and Buildings |
| Tags | 2013, housing, new housing construction, housing units, net new units, demolition, merger, conversion, alteration, housing stock, housing inventory, illegal units removed |
| Created | 2014-05-06T22:32:11Z |
| Publication Date | 2015-09-23T22:35:01Z |
| Rows Updated | 2015-09-23T22:28:43Z |

## Description

Excel workbook of all housing construction from the 2013 Housing Inventory.

## Columns

```ls
| Included | Schema Type    | Field Name      | Name       | Data Type     | Render Type   |
| ======== | ============== | =============== | ========== | ============= | ============= |
| No       |                | standardaddress | STDADDRESS | text          | text          |
| Yes      | series tag     | name            | PRJ_NAME   | text          | text          |
| Yes      | series tag     | block           | BLOCK      | text          | text          |
| Yes      | series tag     | lot             | LOT        | text          | number        |
| Yes      | numeric metric | units           | UNITS      | number        | number        |
| Yes      | numeric metric | netunits        | NETUNITS   | number        | number        |
| Yes      | numeric metric | aff_hsg         | AFF_HSG    | number        | number        |
| Yes      | series tag     | aff_cat         | AFF_TARGET | text          | text          |
| Yes      | series tag     | change_type     | CNG_TYPE   | text          | text          |
| Yes      | series tag     | existuse        | EXISTUSE   | text          | text          |
| Yes      | series tag     | propuse         | PROPUSE    | text          | text          |
| Yes      | time           | actdate         | ACTDATE    | calendar_date | calendar_date |
| Yes      | series tag     | zoning          | Zoning     | text          | text          |
| Yes      | series tag     | pd_no           | PD_NO      | text          | number        |
| Yes      | series tag     | supervisor      | SD_NO      | text          | number        |
| Yes      | series tag     | planarea        | PLANAREA   | text          | text          |
```

## Time Field

```ls
Value = actdate
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = standardaddress
```

## Data Commands

```ls
series e:e7d3-dxh5 d:2013-07-30T00:00:00.000Z t:aff_cat=LI t:supervisor=9 t:lot=52 t:block=3702 t:change_type=Demolition t:zoning="RH-1 (D)" t:pd_no=12 m:netunits=-418 m:units=-418

series e:e7d3-dxh5 d:2013-07-18T00:00:00.000Z t:aff_cat=VLI t:supervisor=5 t:lot=9 t:block=4624 t:propuse=APARTMENTS t:change_type="New Construction" t:zoning=RH-2 t:pd_no=14 m:aff_hsg=54 m:netunits=54 m:units=54

series e:e7d3-dxh5 d:2013-10-02T00:00:00.000Z t:existuse="TOURIST HOTEL/MOTEL" t:aff_cat=LI t:supervisor=5 t:lot=8 t:block=3753 t:propuse=APARTMENTS t:change_type=Conversion t:zoning=RH-2 t:pd_no=14 m:aff_hsg=44 m:netunits=44 m:units=44
```

## Meta Commands

```ls
metric m:units p:integer l:UNITS t:dataTypeName=number

metric m:netunits p:integer l:NETUNITS t:dataTypeName=number

metric m:aff_hsg p:integer l:AFF_HSG t:dataTypeName=number

entity e:e7d3-dxh5 l:"2013 Housing Inventory" t:attribution="San Francisco Planning Department" t:url=https://data.sfgov.org/api/views/e7d3-dxh5

property e:e7d3-dxh5 t:meta.view v:id=e7d3-dxh5 v:category="Housing and Buildings" v:attributionLink=http://www.sf-planning.org/ftp/files/publications_reports/Housing_Inventory_2013.pdf v:averageRating=0 v:name="2013 Housing Inventory" v:attribution="San Francisco Planning Department"

property e:e7d3-dxh5 t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:e7d3-dxh5 t:meta.view.owner v:id=hwt3-twww v:screenName="Information & Analysis Group (IAG) - SFPlanning" v:displayName="Information & Analysis Group (IAG) - SFPlanning"

property e:e7d3-dxh5 t:meta.view.tableauthor v:id=hwt3-twww v:screenName="Information & Analysis Group (IAG) - SFPlanning" v:roleName=editor v:displayName="Information & Analysis Group (IAG) - SFPlanning"
```