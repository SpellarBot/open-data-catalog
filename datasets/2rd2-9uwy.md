# Local Law 50 New York State Food Purchasing FY15

## Dataset

* [Dataset URL](https://data.cityofnewyork.us/api/views/2rd2-9uwy/rows.json?accessType=DOWNLOAD)
* [Catalog URL](https://catalog.data.gov/dataset/local-law-50-new-york-state-food-purchasing-fy15)
* Id = 2rd2-9uwy
* Name = Local Law 50 New York State Food Purchasing FY15
* Attribution = Mayor's Office of Contract Services (MOCS)
* Category = City Government
* Created = 2015-12-17T16:37:58Z
* Publication Date = 2015-12-17T16:41:11Z
* Rows Updated = 2015-12-17T16:38:05Z

## Description

Local Law 50 of 2011 required MOCS to establish guidelines for City agencies that assist in increasing the purchase of New York State food through food purchase and food-related services contracts. City agencies use the New York State Department of Agriculture and Markets (NYSDAM) list of food items available from New York State sources.

## Columns

```ls
| Name                                                      | Field Name                                              | Data Type | Render Type | Schema Type    | Included | 
| ========================================================= | ======================================================= | ========= | =========== | ============== | ======== | 
| updated_at                                                | :updated_at                                             | meta_data | meta_data   | time           | Yes      | 
| Food Type                                                 | food_type                                               | text      | text        | series tag     | Yes      | 
| From New York State Source                                | from_new_york_state_source                              | money     | money       | numeric metric | Yes      | 
| Other Source - During New York State Availability Period  | other_source_during_new_york_state_availability_period  | money     | money       | numeric metric | Yes      | 
| Other Source - Outside New York State Availability Period | other_source_outside_new_york_state_availability_period | money     | money       | numeric metric | Yes      | 
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
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
series e:2rd2-9uwy d:2015-12-17T08:38:00.000Z t:food_type="Apple Cider" m:other_source_outside_new_york_state_availability_period=0 m:from_new_york_state_source=158 m:other_source_during_new_york_state_availability_period=0

series e:2rd2-9uwy d:2015-12-17T08:38:00.000Z t:food_type=Apples m:other_source_outside_new_york_state_availability_period=2429 m:from_new_york_state_source=42896 m:other_source_during_new_york_state_availability_period=8106

series e:2rd2-9uwy d:2015-12-17T08:38:00.000Z t:food_type=Asparagus m:other_source_outside_new_york_state_availability_period=143 m:from_new_york_state_source=292 m:other_source_during_new_york_state_availability_period=791
```

## Meta Commands

```ls
entity e:2rd2-9uwy l:"Local Law 50 New York State Food Purchasing FY15" t:attribution="Mayor's Office of Contract Services (MOCS)" t:url=https://data.cityofnewyork.us/api/views/2rd2-9uwy

property e:2rd2-9uwy t:meta.view d:2017-03-03T13:49:26.236Z v:id=2rd2-9uwy v:category="City Government" v:averageRating=0 v:name="Local Law 50 New York State Food Purchasing FY15" v:attribution="Mayor's Office of Contract Services (MOCS)"

property e:2rd2-9uwy t:meta.view.owner d:2017-03-03T13:49:26.236Z v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:displayName="NYC OpenData"

property e:2rd2-9uwy t:meta.view.tableauthor d:2017-03-03T13:49:26.236Z v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:displayName="NYC OpenData"
```