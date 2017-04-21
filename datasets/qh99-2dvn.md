# Cook County Assessor - Assessment Appeals by Town and Class - 2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cook-county-assessor-assessment-appeals-by-town-and-class-2010-0ec18) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/qh99-2dvn) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/qh99-2dvn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/qh99-2dvn/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | qh99-2dvn |
| Name | Cook County Assessor - Assessment Appeals by Town and Class - 2010 |
| Attribution | Cook County Assessor |
| Category | Property & Taxation |
| Created | 2011-09-01T16:04:52Z |
| Publication Date | 2014-10-09T20:52:59Z |

## Description

Assessment Appeals by Town and Class from Tax Year 2010.

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type | Render Type |
| ======== | ============== | ================= | ================= | ========= | =========== |
| Yes      | numeric metric | town              | Town              | number    | number      |
| Yes      | series tag     | township_name     | Township Name     | text      | text        |
| Yes      | numeric metric | class             | Class             | number    | number      |
| Yes      | series tag     | class_description | Class Description | text      | text        |
| Yes      | numeric metric | count             | Count             | number    | number      |
```

## Time Field

```ls
Value = 2010
Format & Zone = yyyy
```

## Data Commands

```ls
series e:qh99-2dvn d:2010-01-01T00:00:00.000Z t:class_description="Vacant Land" t:township_name=Barrington m:count=137 m:class=100 m:town=10

series e:qh99-2dvn d:2010-01-01T00:00:00.000Z t:class_description="Other minor improvement which does not add value" t:township_name=Barrington m:count=6 m:class=190 m:town=10

series e:qh99-2dvn d:2010-01-01T00:00:00.000Z t:class_description="Residential garage" t:township_name=Barrington m:count=2 m:class=201 m:town=10
```

## Meta Commands

```ls
metric m:town p:integer l:Town t:dataTypeName=number

metric m:class p:integer l:Class t:dataTypeName=number

metric m:count p:integer l:Count t:dataTypeName=number

entity e:qh99-2dvn l:"Cook County Assessor - Assessment Appeals by Town and Class - 2010" t:attribution="Cook County Assessor" t:url=https://datacatalog.cookcountyil.gov/api/views/qh99-2dvn

property e:qh99-2dvn t:meta.view v:id=qh99-2dvn v:category="Property & Taxation" v:attributionLink=http://www.cookcountyassessor.com/ v:averageRating=0 v:name="Cook County Assessor - Assessment Appeals by Town and Class - 2010" v:attribution="Cook County Assessor"

property e:qh99-2dvn t:meta.view.license v:name="Public Domain"

property e:qh99-2dvn t:meta.view.owner v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"

property e:qh99-2dvn t:meta.view.tableauthor v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"
```

## Top Records

```ls
| town | township_name | class | class_description                                                   | count | 
| ==== | ============= | ===== | =================================================================== | ===== | 
| 10   | Barrington    | 100   | Vacant Land                                                         | 137   | 
| 10   | Barrington    | 190   | Other minor improvement which does not add value                    | 6     | 
| 10   | Barrington    | 201   | Residential garage                                                  | 2     | 
| 10   | Barrington    | 202   | One Story Residence, Any Age, up to 999 Sq. Ft.                     | 10    | 
| 10   | Barrington    | 203   | One Story Residence, Any Age, 1,000 to 1,800 Sq. Ft.                | 77    | 
| 10   | Barrington    | 204   | One Story Residence, Any Age, 1,801 Sq Ft. and Over                 | 230   | 
| 10   | Barrington    | 205   | Two or More Story Residence, Over 62 Years, up to 2,200 Sq. Ft.     | 17    | 
| 10   | Barrington    | 206   | Two or More Story Residence, Over 62 Years, 2,201 to 4,999 Sq. Ft.  | 43    | 
| 10   | Barrington    | 207   | Two or More Story Residence, Up to 62 Years, up to 2,000 Ft.        | 29    | 
| 10   | Barrington    | 208   | Two or More Story Residence, Up to 62 Years, 3,801 to 4,999 Sq. Ft. | 222   | 
```