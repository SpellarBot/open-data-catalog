# Better Brakes - Baseline Dataset

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/better-brakes-baseline-dataset-a6c28) |
| Metadata | [Link](https://data.wa.gov/api/views/i7iu-f74k) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/i7iu-f74k/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/i7iu-f74k/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | i7iu-f74k |
| Name | Better Brakes - Baseline Dataset |
| Attribution | The Washington State Department of Ecology |
| Category | Natural Resources & Environment |
| Tags | better brakes, baseline report, copper, nickel, zinc, antimony |
| Created | 2013-06-24T17:08:09Z |
| Publication Date | 2013-07-23T22:02:05Z |

## Description

Manufacturers are required to report certain information to Ecology by Chapter 70.285 RCW and Chapter 173-901 WAC.  This dataset contains information on the concentrations of copper, nickel, zinc, and antimony in brake friction materials sold in Washington State. Each row represents one formula.

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type | Render Type |
| ======== | ============== | ================= | ================= | ========= | =========== |
| No       | time           | :updated_at       | updated_at        | meta_data | meta_data   |
| Yes      | numeric metric | copperwtpercent   | CopperWtPercent   | percent   | percent     |
| Yes      | numeric metric | zincwtpercent     | ZincWtPercent     | percent   | percent     |
| Yes      | numeric metric | nickelwtpercent   | NickelWtPercent   | percent   | percent     |
| Yes      | numeric metric | antimonywtpercent | AntimonyWtPercent | percent   | percent     |
| Yes      | series tag     | lightvechicleflag | LightVechicleFlag | text      | text        |
| Yes      | series tag     | heavyvechicleflag | HeavyVechicleFlag | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:i7iu-f74k d:2016-07-22T13:49:33.000Z t:lightvechicleflag=Y m:antimonywtpercent=4.15 m:zincwtpercent=0 m:nickelwtpercent=0 m:copperwtpercent=11.29

series e:i7iu-f74k d:2016-07-22T13:49:33.000Z t:lightvechicleflag=Y t:heavyvechicleflag=Y m:antimonywtpercent=0 m:zincwtpercent=0 m:nickelwtpercent=0 m:copperwtpercent=0

series e:i7iu-f74k d:2016-07-22T13:49:33.000Z t:lightvechicleflag=Y m:antimonywtpercent=0 m:zincwtpercent=0 m:nickelwtpercent=0 m:copperwtpercent=0
```

## Meta Commands

```ls
metric m:copperwtpercent p:double l:CopperWtPercent t:dataTypeName=percent

metric m:zincwtpercent p:double l:ZincWtPercent t:dataTypeName=percent

metric m:nickelwtpercent p:float l:NickelWtPercent t:dataTypeName=percent

metric m:antimonywtpercent p:float l:AntimonyWtPercent t:dataTypeName=percent

entity e:i7iu-f74k l:"Better Brakes - Baseline Dataset" t:attribution="The Washington State Department of Ecology" t:url=https://data.wa.gov/api/views/i7iu-f74k

property e:i7iu-f74k t:meta.view v:id=i7iu-f74k v:category="Natural Resources & Environment" v:attributionLink=http://www.ecy.wa.gov/programs/hwtr/betterbrakes.html v:averageRating=0 v:name="Better Brakes - Baseline Dataset" v:attribution="The Washington State Department of Ecology"

property e:i7iu-f74k t:meta.view.license v:name="Public Domain"

property e:i7iu-f74k t:meta.view.owner v:id=a9ty-dhvu v:screenName="ECY-Wesley, Ian" v:displayName="ECY-Wesley, Ian"

property e:i7iu-f74k t:meta.view.tableauthor v:id=a9ty-dhvu v:screenName="ECY-Wesley, Ian" v:roleName=publisher v:displayName="ECY-Wesley, Ian"
```

## Top Records

```ls
| :updated_at | copperwtpercent | zincwtpercent | nickelwtpercent | antimonywtpercent | lightvechicleflag | heavyvechicleflag | 
| =========== | =============== | ============= | =============== | ================= | ================= | ================= | 
| 1469195373  | 11.29           | 0             | 0               | 4.15              | Y                 |                   | 
| 1469195373  | 0               | 0             | 0               | 0                 | Y                 | Y                 | 
| 1469195373  | 0               | 0             | 0               | 0                 | Y                 |                   | 
| 1469195373  | 0               | 0             | 0               | 0                 | Y                 |                   | 
| 1469195373  | 3.61            | 1.29          | 0               | 2.81              | Y                 |                   | 
| 1469195373  | 0               | 0             | 0               | 1.24              |                   | Y                 | 
| 1469195373  | 15.05           | 0             | 0               | 4.61              | Y                 |                   | 
| 1469195373  | 0               | 0             | 0               | 0                 | Y                 |                   | 
| 1469195373  | 0               | 0             | 0               | 0.79              | Y                 | Y                 | 
| 1469195373  | 0               | 0             | 0               | 1.24              |                   | Y                 | 
```