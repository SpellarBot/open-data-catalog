# Multifamily Energy Fund Recipients 2013 Approved

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/multifamily-energy-fund-recipients-2013-approved-b9670) |
| Metadata | [Link](https://data.maryland.gov/api/views/yjxi-zyut) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/yjxi-zyut/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/yjxi-zyut/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | yjxi-zyut |
| Name | Multifamily Energy Fund Recipients 2013 Approved |
| Attribution | MD DHCD CDA |
| Category | Housing |
| Tags | housing, energy, empower, mmeha2, besmart, rental, multi-family, fy 2013 |
| Created | 2014-03-14T18:09:15Z |
| Publication Date | 2014-03-24T19:05:41Z |

## Description

Multifamily Rental Projects Energy Fund Recipients from FY 2013.

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                   | Data Type | Render Type |
| ======== | ============== | ====================== | ====================== | ========= | =========== |
| Yes      | series tag     | sponsor                | Sponsor                | text      | text        |
| Yes      | series tag     | program                | Program                | text      | text        |
| Yes      | series tag     | project                | Project                | text      | text        |
| Yes      | series tag     | project_street_address | Project Street Address | text      | text        |
| Yes      | series tag     | county                 | County                 | text      | text        |
| Yes      | numeric metric | amount                 | Amount                 | money     | money       |
| Yes      | series tag     | utility_territory      | Utility Territory      | text      | text        |
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
series e:yjxi-zyut d:2013-01-01T00:00:00.000Z t:project="St. Luke's Apartments" t:project_street_address="2825 Lodge Farm Road" t:utility_territory=BGE t:county=Baltimore t:program=EmPOWER t:occupancy=Elderly t:sponsor="Catholic Charities" t:construction=Rehabilitation m:amount=70273 m:housing_units=125

series e:yjxi-zyut d:2013-01-01T00:00:00.000Z t:project="Spring Valley Apartments" t:project_street_address="46533 Valley Court" t:utility_territory=SMECO t:county="St. Mary's" t:program=EmPOWER t:occupancy=Families t:sponsor="Humphrey Development" t:construction=Rehabilitation m:amount=281250 m:housing_units=128

series e:yjxi-zyut d:2013-01-01T00:00:00.000Z t:project="Basilica Place" t:project_street_address="124 W. Franklin Street" t:utility_territory=BGE t:county="Baltimore City" t:program=EmPOWER t:occupancy=Elderly t:sponsor="Catholic Charities" t:construction=Rehabilitation m:amount=76528 m:housing_units=200
```

## Meta Commands

```ls
metric m:amount p:integer l:Amount t:dataTypeName=money

metric m:housing_units p:integer l:"Housing Units" t:dataTypeName=number

entity e:yjxi-zyut l:"Multifamily Energy Fund Recipients 2013 Approved" t:attribution="MD DHCD CDA" t:url=https://data.maryland.gov/api/views/yjxi-zyut

property e:yjxi-zyut t:meta.view v:id=yjxi-zyut v:category=Housing v:attributionLink=http://www.dhcd.md.us v:averageRating=0 v:name="Multifamily Energy Fund Recipients 2013 Approved" v:attribution="MD DHCD CDA"

property e:yjxi-zyut t:meta.view.license v:name="Public Domain"

property e:yjxi-zyut t:meta.view.owner v:id=akrp-bunm v:screenName="Kristen J. Robinson" v:displayName="Kristen J. Robinson"

property e:yjxi-zyut t:meta.view.tableauthor v:id=akrp-bunm v:screenName="Kristen J. Robinson" v:roleName=editor v:displayName="Kristen J. Robinson"
```

## Top Records

```ls
| sponsor                                            | program | project                  | project_street_address | county         | amount | utility_territory | housing_units | occupancy | construction   | 
| ================================================== | ======= | ======================== | ====================== | ============== | ====== | ================= | ============= | ========= | ============== | 
| Catholic Charities                                 | EmPOWER | St. Luke's Apartments    | 2825 Lodge Farm Road   | Baltimore      | 70273  | BGE               | 125           | Elderly   | Rehabilitation | 
| Humphrey Development                               | EmPOWER | Spring Valley Apartments | 46533 Valley Court     | St. Mary's     | 281250 | SMECO             | 128           | Families  | Rehabilitation | 
| Catholic Charities                                 | EmPOWER | Basilica Place           | 124 W. Franklin Street | Baltimore City | 76528  | BGE               | 200           | Elderly   | Rehabilitation | 
| Homes for America, Inc.                            | BeSMART | Leonard Apartments       | 800 Booth Street       | Wicomico       | 974931 | Delmarva          | 66            | Familes   | Rehabilitation | 
| Homes for America, Inc.                            | EmPOWER | Leonard Apartments       | 800 Booth Street       | Wicomico       | 523191 | Delmarva          | 66            | Familes   | Rehabilitation | 
| Catholic Charities                                 | EmPOWER | Arundel Woods            | 403 W. Ordnance Road   | Anne Arundel   | 60186  | BGE               | 72            | Elderly   | Rehabilitation | 
| Conifer Realty LLC                                 | EmPOWER | Richmond Hill Pointe     | 302 Mansion Drive      | Cecil          | 221807 | Delmarva          | 48            | Families  | Rehabilitation | 
| Community Preservation and Development Corporation | BeSMART | Essex House              | 7777 Maple Avenue      | Montgomery     | 570736 | PEPCO             | 45            | Familes   | Rehabilitation | 
| Episcopal Housing Corp.                            | EmPOWER | Ashburton Apartments     | 3401 Oakfield Avenue   | Baltimore City | 113585 | BGE               | 24            | Elderly   | Rehabilitation | 
| Catholic Charities                                 | EmPOWER | Reisters View            | 306 Cantana Court      | Baltimore      | 7055   | BGE               | 72            | Elderly   | Rehabilitation | 
```