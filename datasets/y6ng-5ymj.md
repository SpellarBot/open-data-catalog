# ACCD :: Discarded Materials ? Fiscal Year 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/accd-discarded-materials-fiscal-year-2013) |
| Metadata | [Link](https://data.austintexas.gov/api/views/y6ng-5ymj) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/y6ng-5ymj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/y6ng-5ymj/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | y6ng-5ymj |
| Name | ACCD :: Discarded Materials ? Fiscal Year 2013 |
| Attribution | Austin Convention Center Department |
| Category | Environmental |
| Tags | convention center, recycle, reuse, landfill, waste |
| Created | 2015-07-20T13:18:26Z |
| Publication Date | 2015-07-20T13:50:30Z |

## Description

This dataset shows the Convention Center recycling efforts during fiscal year 2013. Data includes fiscal year, quarter and month of collection, the category (Recycling or waste), sub-category (recycled material, reused material and material sent to the landfill) and the weight in pounds for each.

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                       | Data Type | Render Type |
| ======== | ============== | ========================== | ========================== | ========= | =========== |
| No       |                | fiscal_year                | Fiscal Year                | number    | number      |
| No       |                | quarter                    | Quarter                    | text      | text        |
| Yes      | series tag     | month                      | Month                      | text      | text        |
| Yes      | series tag     | category                   | Category                   | text      | text        |
| Yes      | series tag     | sub_category               | Sub-Category               | text      | text        |
| Yes      | series tag     | material_source_donated_to | Material-Source-Donated To | text      | text        |
| Yes      | numeric metric | weight_in_pounds           | Weight in Pounds           | number    | number      |
```

## Time Field

```ls
Value = fiscal_year-quarter
Format & Zone = yyyy-q
```

## Series Fields

```ls
Excluded Fields = fiscal_year,quarter
```

## Data Commands

```ls
series e:y6ng-5ymj d:2012-10-01T00:00:00.000Z t:category=Recycling t:material_source_donated_to="Alum Cans & Plastic (Lbs)" t:month=10-Oct t:sub_category=Recycled m:weight_in_pounds=3494

series e:y6ng-5ymj d:2012-10-01T00:00:00.000Z t:category=Recycling t:material_source_donated_to="Ballasts (Lbs)" t:month=10-Oct t:sub_category=Recycled m:weight_in_pounds=0

series e:y6ng-5ymj d:2012-10-01T00:00:00.000Z t:category=Recycling t:material_source_donated_to="Batteries (Lbs)" t:month=10-Oct t:sub_category=Recycled m:weight_in_pounds=0
```

## Meta Commands

```ls
metric m:weight_in_pounds p:integer l:"Weight in Pounds" t:dataTypeName=number

entity e:y6ng-5ymj l:"ACCD :: Discarded Materials ? Fiscal Year 2013" t:attribution="Austin Convention Center Department" t:url=https://data.austintexas.gov/api/views/y6ng-5ymj

property e:y6ng-5ymj t:meta.view v:id=y6ng-5ymj v:category=Environmental v:averageRating=0 v:name="ACCD :: Discarded Materials ? Fiscal Year 2013" v:attribution="Austin Convention Center Department"

property e:y6ng-5ymj t:meta.view.license v:name="Public Domain"

property e:y6ng-5ymj t:meta.view.owner v:id=mepj-zp7g v:screenName="Chris G Hernandez" v:displayName="Chris G Hernandez"

property e:y6ng-5ymj t:meta.view.tableauthor v:id=mepj-zp7g v:screenName="Chris G Hernandez" v:roleName=publisher v:displayName="Chris G Hernandez"
```

## Top Records

```ls
| fiscal_year | quarter   | month  | category  | sub_category | material_source_donated_to         | weight_in_pounds | 
| =========== | ========= | ====== | ========= | ============ | ================================== | ================ | 
| 2013        | Quarter 1 | 10-Oct | Recycling | Recycled     | Alum Cans & Plastic (Lbs)          | 3494             | 
| 2013        | Quarter 1 | 10-Oct | Recycling | Recycled     | Ballasts (Lbs)                     | 0                | 
| 2013        | Quarter 1 | 10-Oct | Recycling | Recycled     | Batteries (Lbs)                    | 0                | 
| 2013        | Quarter 1 | 10-Oct | Recycling | Recycled     | Cardboard (Lbs)                    | 15140            | 
| 2013        | Quarter 1 | 10-Oct | Recycling | Recycled     | Carpet (Lbs)                       | 0                | 
| 2013        | Quarter 1 | 10-Oct | Recycling | Recycled     | Ceiling Tiles (Lbs)                | 0                | 
| 2013        | Quarter 1 | 10-Oct | Recycling | Recycled     | Compost (Lbs)                      | 14660            | 
| 2013        | Quarter 1 | 10-Oct | Recycling | Recycled     | Donated food items (Lbs)           | 520              | 
| 2013        | Quarter 1 | 10-Oct | Recycling | Recycled     | Donated Items (Lbs)                | 0                | 
| 2013        | Quarter 1 | 10-Oct | Recycling | Recycled     | Fluorescent Lamps and U-Tube (Lbs) | 0                | 
```