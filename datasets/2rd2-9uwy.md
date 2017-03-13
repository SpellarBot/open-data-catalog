# Local Law 50 New York State Food Purchasing FY15

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/local-law-50-new-york-state-food-purchasing-fy15) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/2rd2-9uwy) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/2rd2-9uwy/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/2rd2-9uwy/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 2rd2-9uwy |
| Name | Local Law 50 New York State Food Purchasing FY15 |
| Attribution | Mayor's Office of Contract Services (MOCS) |
| Category | City Government |
| Created | 2015-12-17T16:37:58Z |
| Publication Date | 2015-12-17T16:41:11Z |
| Rows Updated | 2015-12-17T16:38:05Z |

## Description

Local Law 50 of 2011 required MOCS to establish guidelines for City agencies that assist in increasing the purchase of New York State food through food purchase and food-related services contracts. City agencies use the New York State Department of Agriculture and Markets (NYSDAM) list of food items available from New York State sources.

## Columns

```ls
| Included | Schema Type    | Field Name                                              | Name                                                      | Data Type | Render Type |
| ======== | ============== | ======================================================= | ========================================================= | ========= | =========== |
| No       | time           | :updated_at                                             | updated_at                                                | meta_data | meta_data   |
| Yes      | series tag     | food_type                                               | Food Type                                                 | text      | text        |
| Yes      | numeric metric | from_new_york_state_source                              | From New York State Source                                | money     | money       |
| Yes      | numeric metric | other_source_during_new_york_state_availability_period  | Other Source - During New York State Availability Period  | money     | money       |
| Yes      | numeric metric | other_source_outside_new_york_state_availability_period | Other Source - Outside New York State Availability Period | money     | money       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:2rd2-9uwy d:2015-12-17T08:38:00.000Z t:food_type="Apple Cider" m:other_source_outside_new_york_state_availability_period=0 m:from_new_york_state_source=158 m:other_source_during_new_york_state_availability_period=0

series e:2rd2-9uwy d:2015-12-17T08:38:00.000Z t:food_type=Apples m:other_source_outside_new_york_state_availability_period=2429 m:from_new_york_state_source=42896 m:other_source_during_new_york_state_availability_period=8106

series e:2rd2-9uwy d:2015-12-17T08:38:00.000Z t:food_type=Asparagus m:other_source_outside_new_york_state_availability_period=143 m:from_new_york_state_source=292 m:other_source_during_new_york_state_availability_period=791
```

## Meta Commands

```ls
metric m:from_new_york_state_source p:integer l:"From New York State Source" t:dataTypeName=money

metric m:other_source_during_new_york_state_availability_period p:integer l:"Other Source - During New York State Availability Period" t:dataTypeName=money

metric m:other_source_outside_new_york_state_availability_period p:integer l:"Other Source - Outside New York State Availability Period" t:dataTypeName=money

entity e:2rd2-9uwy l:"Local Law 50 New York State Food Purchasing FY15" t:attribution="Mayor's Office of Contract Services (MOCS)" t:url=https://data.cityofnewyork.us/api/views/2rd2-9uwy

property e:2rd2-9uwy t:meta.view v:id=2rd2-9uwy v:category="City Government" v:averageRating=0 v:name="Local Law 50 New York State Food Purchasing FY15" v:attribution="Mayor's Office of Contract Services (MOCS)"

property e:2rd2-9uwy t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:displayName="NYC OpenData"

property e:2rd2-9uwy t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:displayName="NYC OpenData"
```