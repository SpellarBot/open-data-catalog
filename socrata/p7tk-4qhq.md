# Cook County Assessor - Homeowner Exemptions, by Town Number/Township - 2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cook-county-assessor-homeowner-exemptions-by-town-number-township-2010-c6b79) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/p7tk-4qhq) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/p7tk-4qhq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/p7tk-4qhq/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | p7tk-4qhq |
| Name | Cook County Assessor - Homeowner Exemptions, by Town Number/Township - 2010 |
| Attribution | Cook County Assessor |
| Category | Property & Taxation |
| Created | 2011-09-01T17:51:49Z |
| Publication Date | 2014-10-09T20:55:10Z |

## Description

Homeowner Exceptions by Town Number/Township in Tax Year 2010.

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type | Render Type |
| ======== | ============== | ================ | ================ | ========= | =========== |
| Yes      | series tag     | town_number      | Town Number      | text      | number      |
| Yes      | series tag     | township_name    | Township Name    | text      | text        |
| Yes      | numeric metric | class            | Class            | number    | number      |
| Yes      | series tag     | class_decription | Class Decription | text      | text        |
| Yes      | numeric metric | count            | Count            | number    | number      |
```

## Time Field

```ls
Value = 2010
Format & Zone = yyyy
```

## Data Commands

```ls
series e:p7tk-4qhq d:2010-01-01T00:00:00.000Z t:town_number=10 t:class_decription="One Story Residence, Any Age, up to 999 Sq. Ft." t:township_name=Barrington m:count=112 m:class=202

series e:p7tk-4qhq d:2010-01-01T00:00:00.000Z t:town_number=10 t:class_decription="One Story Residence, Any Age, 1,000 to 1,800 Sq. Ft." t:township_name=Barrington m:count=739 m:class=203

series e:p7tk-4qhq d:2010-01-01T00:00:00.000Z t:town_number=10 t:class_decription="One Story Residence, Any Age, 1,801 Sq Ft. and Over" t:township_name=Barrington m:count=844 m:class=204
```

## Meta Commands

```ls
metric m:class p:integer l:Class t:dataTypeName=number

metric m:count p:integer l:Count t:dataTypeName=number

entity e:p7tk-4qhq l:"Cook County Assessor - Homeowner Exemptions, by Town Number/Township - 2010" t:attribution="Cook County Assessor" t:url=https://datacatalog.cookcountyil.gov/api/views/p7tk-4qhq

property e:p7tk-4qhq t:meta.view v:id=p7tk-4qhq v:category="Property & Taxation" v:attributionLink=http://www.cookcountyassessor.com/ v:averageRating=0 v:name="Cook County Assessor - Homeowner Exemptions, by Town Number/Township - 2010" v:attribution="Cook County Assessor"

property e:p7tk-4qhq t:meta.view.license v:name="Public Domain"

property e:p7tk-4qhq t:meta.view.owner v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"

property e:p7tk-4qhq t:meta.view.tableauthor v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"
```

## Top Records

```ls
| town_number | township_name | class | class_decription                                                               | count | 
| =========== | ============= | ===== | ============================================================================== | ===== | 
| 10          | Barrington    | 202   | One Story Residence, Any Age, up to 999 Sq. Ft.                                | 112   | 
| 10          | Barrington    | 203   | One Story Residence, Any Age, 1,000 to 1,800 Sq. Ft.                           | 739   | 
| 10          | Barrington    | 204   | One Story Residence, Any Age, 1,801 Sq Ft. and Over                            | 844   | 
| 10          | Barrington    | 205   | Two or More Story Residence, Over 62 Years, up to 2,200 Sq. Ft.                | 171   | 
| 10          | Barrington    | 206   | Two or More Story Residence, Over 62 Years, 2,201 to 4,999 Sq. Ft.             | 152   | 
| 10          | Barrington    | 207   | Two or More Story Residence, Up to 62 Years, up to 2,000 Ft.                   | 206   | 
| 10          | Barrington    | 208   | Two or More Story Residence, Up to 62 Years, 3,801 to 4,999 Sq. Ft.            | 599   | 
| 10          | Barrington    | 209   | Two or More Story Residence, Any Age, 5,000 Sq. Ft. & Over                     | 813   | 
| 10          | Barrington    | 211   | Two to Six Apartments, Over 62 Years                                           | 42    | 
| 10          | Barrington    | 212   | Mixed commercial/residential building, 6 units or less, sq ft less than 20,000 | 10    | 
```