# ACCD :: Discarded Materials ? Fiscal Year 2015

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/accd-discarded-materials-fiscal-year-2015) |
| Metadata | [Link](https://data.austintexas.gov/api/views/bvdj-b937) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/bvdj-b937/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/bvdj-b937/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | bvdj-b937 |
| Name | ACCD :: Discarded Materials ? Fiscal Year 2015 |
| Attribution | Austin Convention Center Department |
| Category | Environmental |
| Tags | accd, convention center, recycle, recycling |
| Created | 2016-01-25T21:19:26Z |
| Publication Date | 2016-01-25T21:23:16Z |

## Description

This dataset shows the Convention Center recycling efforts during fiscal year 2015. Data includes fiscal year, quarter and month of collection, the category (Recycling or waste), sub-category (recycled material, reused material and material sent to the landfill) and the weight in pounds for each.

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                       | Data Type | Render Type |
| ======== | ============== | ========================== | ========================== | ========= | =========== |
| No       |                | fiscalyear                 | FiscalYear                 | number    | number      |
| No       |                | quarter                    | Quarter                    | text      | text        |
| Yes      | series tag     | month                      | Month                      | text      | text        |
| Yes      | series tag     | category                   | Category                   | text      | text        |
| Yes      | series tag     | sub_category               | Sub-Category               | text      | text        |
| Yes      | series tag     | material_source_donated_to | Material-Source-Donated To | text      | text        |
| Yes      | numeric metric | weight_in_pounds           | Weight in Pounds           | number    | number      |
```

## Time Field

```ls
Value = fiscalyear-quarter
Format & Zone = yyyy-q
```

## Series Fields

```ls
Excluded Fields = fiscalyear,quarter
```

## Data Commands

```ls
series e:bvdj-b937 d:2014-10-01T00:00:00.000Z t:category=Recycling t:material_source_donated_to="Cardboard (Lbs)" t:month=10-Oct t:sub_category=Recycled m:weight_in_pounds=13517

series e:bvdj-b937 d:2014-10-01T00:00:00.000Z t:category=Recycling t:material_source_donated_to="Cardboard (Lbs)" t:month=11-Nov t:sub_category=Recycled m:weight_in_pounds=16250

series e:bvdj-b937 d:2014-10-01T00:00:00.000Z t:category=Recycling t:material_source_donated_to="Cardboard (Lbs)" t:month=12-Dec t:sub_category=Recycled m:weight_in_pounds=7720
```

## Meta Commands

```ls
metric m:weight_in_pounds p:integer l:"Weight in Pounds" t:dataTypeName=number

entity e:bvdj-b937 l:"ACCD :: Discarded Materials ? Fiscal Year 2015" t:attribution="Austin Convention Center Department" t:url=https://data.austintexas.gov/api/views/bvdj-b937

property e:bvdj-b937 t:meta.view v:id=bvdj-b937 v:category=Environmental v:averageRating=0 v:name="ACCD :: Discarded Materials ? Fiscal Year 2015" v:attribution="Austin Convention Center Department"

property e:bvdj-b937 t:meta.view.license v:name="Public Domain U.S. Government" v:termsLink=https://www.usa.gov/government-works

property e:bvdj-b937 t:meta.view.owner v:id=mepj-zp7g v:screenName="Chris G Hernandez" v:displayName="Chris G Hernandez"

property e:bvdj-b937 t:meta.view.tableauthor v:id=mepj-zp7g v:screenName="Chris G Hernandez" v:roleName=publisher v:displayName="Chris G Hernandez"
```

## Top Records

```ls
| fiscalyear | quarter   | month  | category  | sub_category | material_source_donated_to | weight_in_pounds | 
| ========== | ========= | ====== | ========= | ============ | ========================== | ================ | 
| 2015       | Quarter 1 | 10-Oct | Recycling | Recycled     | Cardboard (Lbs)            | 13517            | 
| 2015       | Quarter 1 | 11-Nov | Recycling | Recycled     | Cardboard (Lbs)            | 16250            | 
| 2015       | Quarter 1 | 12-Dec | Recycling | Recycled     | Cardboard (Lbs)            | 7720             | 
| 2015       | Quarter 2 | 2-Feb  | Recycling | Recycled     | Cardboard (Lbs)            | 12925            | 
| 2015       | Quarter 2 | 3-Mar  | Recycling | Recycled     | Cardboard (Lbs)            | 13800            | 
| 2015       | Quarter 2 | 3-Mar  | Recycling | Recycled     | Cardboard (Lbs)            | 5440             | 
| 2015       | Quarter 4 | 9-Sep  | Recycling | Recycled     | Cardboard (Lbs)            | 11678            | 
| 2015       | Quarter 2 | 3-Mar  | Recycling | Recycled     | Cardboard (Lbs)            | 4100             | 
| 2015       | Quarter 2 | 3-Mar  | Recycling | Recycled     | Cardboard (Lbs)            | 4080             | 
| 2015       | Quarter 3 | 4-Apr  | Recycling | Recycled     | Cardboard (Lbs)            | 13200            | 
```