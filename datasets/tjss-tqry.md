# Multifamily LIHTC Recipient 2013 Approved 2 03 14

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/multifamily-lihtc-recipient-2013-approved-2-03-14-7598e) |
| Metadata | [Link](https://data.maryland.gov/api/views/tjss-tqry) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/tjss-tqry/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/tjss-tqry/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | tjss-tqry |
| Name | Multifamily LIHTC Recipient 2013 Approved 2 03 14 |
| Attribution | MD DHCD CDA |
| Category | Housing |
| Tags | rental, housing, round, competitive, multi-family, lihtc, fy 2013 |
| Created | 2014-03-14T18:01:08Z |
| Publication Date | 2014-03-24T19:03:23Z |

## Description

The fourteen (14) projects that received reservations of 9% Low Income Housing Tax Credits from the Maryland Department of Housing and Community Development (DHCD) in the 2013 Competitive Funding Round.

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                   | Data Type | Render Type |
| ======== | ============== | ====================== | ====================== | ========= | =========== |
| Yes      | series tag     | sponsor                | Sponsor                | text      | text        |
| Yes      | series tag     | sponsor_type           | Sponsor Type           | text      | text        |
| Yes      | series tag     | project                | Project                | text      | text        |
| Yes      | series tag     | project_street_address | Project Street Address | text      | text        |
| Yes      | series tag     | county                 | County                 | text      | text        |
| Yes      | numeric metric | amount                 | Amount                 | money     | money       |
| Yes      | series tag     | type                   | Type                   | text      | text        |
| Yes      | numeric metric | housing_units          | Housing Units          | number    | number      |
| Yes      | series tag     | occupancy              | Occupancy              | text      | text        |
| Yes      | series tag     | construction           | Construction           | text      | text        |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Data Commands

```ls
series e:tjss-tqry d:2013-01-01T00:00:00.000Z t:project="Chapel Springs Senior" t:project_street_address="Chapel Road" t:county=Baltimore t:sponsor_type=Profit t:occupancy=Elderly t:type=Competitive t:sponsor="Rellim Development LLC/Stavrou Assoicates" t:construction="New Construction" m:amount=1422865 m:housing_units=127

series e:tjss-tqry d:2013-01-01T00:00:00.000Z t:project="Parklands at Cecilton (The)" t:project_street_address="203 El. Main Street" t:county=Cecil t:sponsor_type="Non Profit" t:occupancy=Families t:type=Competitive t:sponsor="Ingerman Affordable Housing" t:construction="New Construction" m:amount=970455 m:housing_units=62

series e:tjss-tqry d:2013-01-01T00:00:00.000Z t:project="Manor South" t:project_street_address="3617 Fords Lane" t:county="Baltimore City" t:sponsor_type="Non Profit" t:occupancy=Elderly t:type=Competitive t:sponsor="CHAI Baltimore, Inc." t:construction="New Construction" m:amount=1318017 m:housing_units=90
```

## Meta Commands

```ls
metric m:amount p:integer l:Amount t:dataTypeName=money

metric m:housing_units p:integer l:"Housing Units" t:dataTypeName=number

entity e:tjss-tqry l:"Multifamily LIHTC Recipient 2013 Approved 2 03 14" t:attribution="MD DHCD CDA" t:url=https://data.maryland.gov/api/views/tjss-tqry

property e:tjss-tqry t:meta.view v:id=tjss-tqry v:category=Housing v:attributionLink=http://www.dhcd.state.md.us v:averageRating=0 v:name="Multifamily LIHTC Recipient 2013 Approved 2 03 14" v:attribution="MD DHCD CDA"

property e:tjss-tqry t:meta.view.license v:name="Public Domain"

property e:tjss-tqry t:meta.view.owner v:id=akrp-bunm v:screenName="Kristen J. Robinson" v:displayName="Kristen J. Robinson"

property e:tjss-tqry t:meta.view.tableauthor v:id=akrp-bunm v:screenName="Kristen J. Robinson" v:roleName=editor v:displayName="Kristen J. Robinson"
```

## Top Records

```ls
| sponsor                                   | sponsor_type | project                              | project_street_address  | county          | amount  | type        | housing_units | occupancy | construction     | 
| ========================================= | ============ | ==================================== | ======================= | =============== | ======= | =========== | ============= | ========= | ================ | 
| Rellim Development LLC/Stavrou Assoicates | Profit       | Chapel Springs Senior                | Chapel Road             | Baltimore       | 1422865 | Competitive | 127           | Elderly   | New Construction | 
| Ingerman Affordable Housing               | Non Profit   | Parklands at Cecilton (The)          | 203 El. Main Street     | Cecil           | 970455  | Competitive | 62            | Families  | New Construction | 
| CHAI Baltimore, Inc.                      | Non Profit   | Manor South                          | 3617 Fords Lane         | Baltimore City  | 1318017 | Competitive | 90            | Elderly   | New Construction | 
| National Housing Development Partners     | Profit       | Poppleton Phase III                  | 858 W. Fayette Street   | Baltimore City  | 691044  | Competitive | 32            | Families  | New Construction | 
| Osprey Property Company LLC               | Profit       | Rivers Edge                          | 670 Fitzwater Street    | Wicomico        | 1524429 | Competitive | 90            | Families  | New Construction | 
| Enterprise Housing Corporation, Inc.      | Non Profit   | Riverwoods at Northeast              | 125 Railroad Lane       | Cecil           | 1224663 | Competitive | 76            | Families  | New Construction | 
| Shelter Group                             | Profit       | Residences at Woodland Springs (The) | Atwood Street           | Prince George's | 758595  | Competitive | 36            | Families  | New Construction | 
| Enterprise Housing Corporation, Inc.      | Non Profit   | Hollins Place                        | 4374 Hollins Ferry Road | Baltimore       | 1328688 | Competitive | 54            | Families  | New Construction | 
| The Woda Group LLC                        | Profit       | Mary Harvin                          | 1600 N Chester Street   | Baltimore City  | 1174776 | Conpetitive | 57            | Elderly   | New Construction | 
| Telesis Baltimore Corporation             | Profit       | Barclay Squae Phase II               | East 20th & Worsley     | Baltimore City  | 46606   | Competitive | 67            | Families  | New Construction | 
```