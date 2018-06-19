# Better Brakes - List of Manufacturers Reporting

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/better-brakes-list-of-manufacturers-reporting-4ebfd) |
| Metadata | [Link](https://data.wa.gov/api/views/2dwu-pywu) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/2dwu-pywu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/2dwu-pywu/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | 2dwu-pywu |
| Name | Better Brakes - List of Manufacturers Reporting |
| Attribution | The Washington State Department of Ecology |
| Category | Natural Resources & Environment |
| Tags | better brakes, baseline report |
| Created | 2013-06-24T17:02:11Z |
| Publication Date | 2013-07-23T22:01:00Z |

## Description

Manufacturers are required to report certain information to Ecology by Chapter 70.285 RCW and Chapter 173-901 WAC. This dataset contains a list of manufacturers that have meet these requirements.

## Columns

```ls
| Included | Schema Type | Field Name       | Name             | Data Type | Render Type |
| ======== | =========== | ================ | ================ | ========= | =========== |
| No       | time        | :updated_at      | updated_at       | meta_data | meta_data   |
| Yes      | series tag  | manufacturername | ManufacturerName | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:2dwu-pywu d:2016-07-22T13:49:18.000Z t:manufacturername="OE Quality Friction" m:row_number.2dwu-pywu=1

series e:2dwu-pywu d:2016-07-22T13:49:18.000Z t:manufacturername="Danaher Auto Spare Parts Co., Ltd." m:row_number.2dwu-pywu=2

series e:2dwu-pywu d:2016-07-22T13:49:18.000Z t:manufacturername="ABS Friction Inc." m:row_number.2dwu-pywu=3
```

## Meta Commands

```ls
metric m:row_number.2dwu-pywu p:long l:"Row Number"

entity e:2dwu-pywu l:"Better Brakes - List of Manufacturers Reporting" t:attribution="The Washington State Department of Ecology" t:url=https://data.wa.gov/api/views/2dwu-pywu

property e:2dwu-pywu t:meta.view v:id=2dwu-pywu v:category="Natural Resources & Environment" v:attributionLink=http://www.ecy.wa.gov/programs/hwtr/betterbrakes.html v:averageRating=0 v:name="Better Brakes - List of Manufacturers Reporting" v:attribution="The Washington State Department of Ecology"

property e:2dwu-pywu t:meta.view.license v:name="Public Domain"

property e:2dwu-pywu t:meta.view.owner v:id=a9ty-dhvu v:screenName="ECY-Wesley, Ian" v:displayName="ECY-Wesley, Ian"

property e:2dwu-pywu t:meta.view.tableauthor v:id=a9ty-dhvu v:screenName="ECY-Wesley, Ian" v:roleName=publisher v:displayName="ECY-Wesley, Ian"
```

## Top Records

```ls
| :updated_at | manufacturername                           | 
| =========== | ========================================== | 
| 1469195358  | OE Quality Friction                        | 
| 1469195358  | Danaher Auto Spare Parts Co., Ltd.         | 
| 1469195358  | ABS Friction Inc.                          | 
| 1469195358  | REMSA of America                           | 
| 1469195358  | Shandong Gold Phoenix Co., Ltd.            | 
| 1469195358  | FRAS-LE North America, INC.                | 
| 1469195358  | Advics North America, Inc.                 | 
| 1469195358  | Pujiang Winsafe Friction Material Co., Ltd | 
| 1469195358  | Brake Parts Inc., LLC                      | 
| 1469195358  | Nisshinbo Automotive Manufacturing Inc.    | 
```