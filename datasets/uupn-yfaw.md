# Off-Street parking lots and parking garages

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/off-street-parking-lots-and-parking-garages-b9de4) |
| Metadata | [Link](https://data.sfgov.org/api/views/uupn-yfaw) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/uupn-yfaw/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/uupn-yfaw/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | uupn-yfaw |
| Name | Off-Street parking lots and parking garages |
| Attribution | SFMTA, SFpark |
| Category | Transportation |
| Tags | sfmta, sfpark, parking, parking garages, parking lots, garages |
| Created | 2012-04-30T06:17:32Z |
| Publication Date | 2012-04-30T06:21:59Z |

## Description

Publicly available off-street parking in San Francisco as of September 2011. Find attached a data dictionary, a version of the map as a PDF (symbolized to show garage type and capacity of garage), and a shapefile and CSV of the data. This dataset includes location, capacities, and related details of public parking garages and lots; four parking categories: paid, publicly available (PPA): drive up and pay, typically by the hour or by the day; customer parking only (CPO): typically for businesses or religious institutions; permit holder only (PHO, CGO): i.e. employees only, students only, monthly only; free publicly available (FPA): free off-street parking. The data does not contain off-street residential parking spaces or other unmarked ???private?? parking.

## Columns

```ls
| Included | Schema Type    | Field Name  | Name       | Data Type | Render Type |
| ======== | ============== | =========== | ========== | ========= | =========== |
| No       | time           | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag     | owner       | Owner      | text      | text        |
| No       |                | address     | Address    | text      | text        |
| Yes      | series tag     | primetype   | PrimeType  | text      | text        |
| Yes      | series tag     | secondtype  | SecondType | text      | text        |
| Yes      | series tag     | garorlot    | GarOrLot   | text      | text        |
| Yes      | numeric metric | regcap      | RegCap     | number    | number      |
| Yes      | numeric metric | valetcap    | ValetCap   | number    | number      |
| Yes      | numeric metric | mccap       | MCCap      | number    | number      |
| Yes      | series tag     | landusetyp  | LANDUSETYP | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address
```

## Data Commands

```ls
series e:uupn-yfaw d:2012-04-29T23:17:34.000Z t:primetype=PPA t:landusetyp=restaurant t:garorlot=L t:owner=Private m:mccap=0 m:regcap=13 m:valetcap=0

series e:uupn-yfaw d:2012-04-29T23:17:34.000Z t:primetype=PPA t:garorlot=L t:owner=SFMTA m:mccap=0 m:regcap=34 m:valetcap=0

series e:uupn-yfaw d:2012-04-29T23:17:34.000Z t:primetype=PPA t:garorlot=L t:owner="Port of SF" m:mccap=0 m:regcap=72 m:valetcap=0
```

## Meta Commands

```ls
metric m:regcap p:integer l:RegCap t:dataTypeName=number

metric m:valetcap p:integer l:ValetCap t:dataTypeName=number

metric m:mccap p:integer l:MCCap t:dataTypeName=number

entity e:uupn-yfaw l:"Off-Street parking lots and parking garages" t:attribution="SFMTA, SFpark" t:url=https://data.sfgov.org/api/views/uupn-yfaw

property e:uupn-yfaw t:meta.view v:id=uupn-yfaw v:category=Transportation v:attributionLink=http://sfpark.org/resources/off-street-parking-census-gis-data/ v:averageRating=0 v:name="Off-Street parking lots and parking garages" v:attribution="SFMTA, SFpark"

property e:uupn-yfaw t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:uupn-yfaw t:meta.view.owner v:id=zn8n-8wyr v:screenName="Leslie Bienenfeld" v:displayName="Leslie Bienenfeld"

property e:uupn-yfaw t:meta.view.tableauthor v:id=zn8n-8wyr v:screenName="Leslie Bienenfeld" v:roleName=editor v:displayName="Leslie Bienenfeld"
```

## Top Records

```ls
| :updated_at | owner      | address                   | primetype | secondtype | garorlot | regcap | valetcap | mccap | landusetyp | 
| =========== | ========== | ========================= | ========= | ========== | ======== | ====== | ======== | ===== | ========== | 
| 1335741454  | Private    | 2110 Market St            | PPA       |            | L        | 13     | 0        | 0     | restaurant | 
| 1335741454  | SFMTA      | 993 Potrero               | PPA       |            | L        | 34     | 0        | 0     |            | 
| 1335741454  | Port of SF | 601 Terry A Francois Blvd | PPA       |            | L        | 72     | 0        | 0     |            | 
| 1335741454  | Private    | 11 SOUTH VAN NESS         | PHO       | CPO        | G        | 130    | 0        | 0     |            | 
| 1335741454  | Private    | 101 CALIFORNIA ST         | PPA       |            | G        | 250    | 0        | 0     |            | 
| 1335741454  | Private    | 2000 POST ST              | PPA       |            | G        | 304    | 0        | 0     |            | 
| 1335741454  | Private    | 600 CALIFORNIA ST         | PPA       |            | G        | 197    | 0        | 0     |            | 
| 1335741454  | Private    | 35 GILBERT ST             | PPA       |            |          | 80     | 0        | 0     |            | 
| 1335741454  | Private    | 2355 POST ST              | PPA       |            | L        | 50     | 0        | 0     |            | 
| 1335741454  | RPD        | 801 STANYAN ST            | PPA       |            | L        | 324    | 0        | 0     |            | 
```