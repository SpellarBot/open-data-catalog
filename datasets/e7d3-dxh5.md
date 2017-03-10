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
| Yes      | series tag     | standardaddress | STDADDRESS | text          | text          |
| Yes      | series tag     | name            | PRJ_NAME   | text          | text          |
| Yes      | numeric metric | block           | BLOCK      | number        | text          |
| Yes      | numeric metric | lot             | LOT        | number        | number        |
| Yes      | numeric metric | units           | UNITS      | number        | number        |
| Yes      | numeric metric | netunits        | NETUNITS   | number        | number        |
| Yes      | numeric metric | aff_hsg         | AFF_HSG    | number        | number        |
| Yes      | series tag     | aff_cat         | AFF_TARGET | text          | text          |
| Yes      | series tag     | change_type     | CNG_TYPE   | text          | text          |
| Yes      | series tag     | existuse        | EXISTUSE   | text          | text          |
| Yes      | series tag     | propuse         | PROPUSE    | text          | text          |
| Yes      | time           | actdate         | ACTDATE    | calendar_date | calendar_date |
| Yes      | series tag     | zoning          | Zoning     | text          | text          |
| Yes      | numeric metric | pd_no           | PD_NO      | number        | number        |
| Yes      | numeric metric | supervisor      | SD_NO      | number        | number        |
| Yes      | series tag     | planarea        | PLANAREA   | text          | text          |
```

## Time Field

```ls
Value = actdate
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:e7d3-dxh5 d:2013-07-30T00:00:00.000Z t:aff_cat=LI t:change_type=Demolition t:standardaddress="1190 MISSION ST" t:zoning="RH-1 (D)" m:supervisor=9 m:block=3702 m:lot=52 m:netunits=-418 m:units=-418 m:pd_no=12

series e:e7d3-dxh5 d:2013-07-18T00:00:00.000Z t:aff_cat=VLI t:propuse=APARTMENTS t:change_type="New Construction" t:standardaddress="60 WEST POINT RD" t:zoning=RH-2 m:aff_hsg=54 m:supervisor=5 m:block=4624 m:lot=9 m:netunits=54 m:units=54 m:pd_no=14

series e:e7d3-dxh5 d:2013-10-02T00:00:00.000Z t:existuse="TOURIST HOTEL/MOTEL" t:aff_cat=LI t:propuse=APARTMENTS t:change_type=Conversion t:standardaddress="374 05TH ST" t:zoning=RH-2 m:aff_hsg=44 m:supervisor=5 m:block=3753 m:lot=8 m:netunits=44 m:units=44 m:pd_no=14
```

## Meta Commands

```ls
metric m:block p:integer l:BLOCK t:dataTypeName=number

metric m:lot p:integer l:LOT t:dataTypeName=number

metric m:units l:UNITS t:dataTypeName=number

metric m:netunits l:NETUNITS t:dataTypeName=number

metric m:aff_hsg p:integer l:AFF_HSG t:dataTypeName=number

metric m:pd_no p:integer l:PD_NO t:dataTypeName=number

metric m:supervisor p:integer l:SD_NO t:dataTypeName=number

entity e:e7d3-dxh5 l:"2013 Housing Inventory" t:attribution="San Francisco Planning Department" t:url=https://data.sfgov.org/api/views/e7d3-dxh5

property e:e7d3-dxh5 t:meta.view d:2017-03-10T16:01:02.581Z v:id=e7d3-dxh5 v:category="Housing and Buildings" v:attributionLink=http://www.sf-planning.org/ftp/files/publications_reports/Housing_Inventory_2013.pdf v:averageRating=0 v:name="2013 Housing Inventory" v:attribution="San Francisco Planning Department"

property e:e7d3-dxh5 t:meta.view.license d:2017-03-10T16:01:02.581Z v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:e7d3-dxh5 t:meta.view.owner d:2017-03-10T16:01:02.581Z v:id=hwt3-twww v:screenName="Information & Analysis Group (IAG) - SFPlanning" v:roleName=editor v:displayName="Information & Analysis Group (IAG) - SFPlanning"

property e:e7d3-dxh5 t:meta.view.tableauthor d:2017-03-10T16:01:02.581Z v:id=hwt3-twww v:screenName="Information & Analysis Group (IAG) - SFPlanning" v:roleName=editor v:displayName="Information & Analysis Group (IAG) - SFPlanning"
```