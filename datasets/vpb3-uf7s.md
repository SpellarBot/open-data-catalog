# Child health plus income levels

## Dataset

* [Dataset URL](https://data.cityofnewyork.us/api/views/vpb3-uf7s/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/child-health-plus-income-levels-2e8d3)
* [Metadata URL](https://data.cityofnewyork.us/api/views/vpb3-uf7s)
* Id = vpb3-uf7s
* Name = Child health plus income levels
* Attribution = Human Resources Administration (HRA)
* [Attribution Link](http://www.nyc.gov/html/hia/html/public_insurance/children.shtml)
* Category = City Government
* Tags = [jobs and economic mobility, human resources administration, hra, children, health, plus]
* Created = 2013-03-19T18:20:39Z
* Publication Date = 2016-03-02T20:15:34Z
* Rows Updated = 2016-03-02T20:14:55Z

## Description

This table represents details of CHP (Child Health Plus) insurance. Child Health Plus provides free or low-cost health insurance for children under the age of 19 who are not eligible for Medicaid, coverage for children. All children receive their health care through a managed care plan. There are no immigration requirements for Child Health Plus.

## Columns

```ls
| Name                                | Field Name                          | Data Type | Render Type | Schema Type    | Included | 
| =================================== | =================================== | ========= | =========== | ============== | ======== | 
| updated_at                          | :updated_at                         | meta_data | meta_data   | time           | No       | 
| Premium Categories                  | premium_categories                  | text      | text        | series tag     | Yes      | 
| Family Size (1 ind.) Monthly Income | family_size__1_ind___monthly_income | text      | text        | series tag     | Yes      | 
| Family Size (2 nos.) Monthly Income | family_size__2_nos___monthly_income | text      | text        | series tag     | Yes      | 
| Family Size (3 nos.) Monthly Income | family_size__3_nos___monthly_income | text      | text        | series tag     | Yes      | 
| Family Size (4 nos.) Monthly Income | family_size__4_nos___monthly_income | text      | text        | series tag     | Yes      | 
| Family Size (5 nos.) Monthly Income | family_size__5_nos___monthly_income | text      | text        | series tag     | Yes      | 
| Each Additional Person Add          | each_additional_person_add          | number    | text        | numeric metric | Yes      | 
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
series e:vpb3-uf7s d:2013-03-19T11:20:45.000Z t:premium_categories="Free Insurance" t:family_size_1_ind__monthly_income=1489 t:family_size_2_nos__monthly_income=2017 t:family_size_5_nos__monthly_income=3601 t:family_size_4_nos__monthly_income=3073 t:family_size_3_nos__monthly_income=2545 m:each_additional_person_add=528

series e:vpb3-uf7s d:2013-03-19T11:20:45.000Z t:premium_categories="$9 Per Child Per Month


```

## Meta Commands

```ls
metric m:each_additional_person_add p:integer l:"Each Additional Person Add" t:dataTypeName=number

entity e:vpb3-uf7s l:"Child health plus income levels" t:attribution="Human Resources Administration (HRA)" t:url=https://data.cityofnewyork.us/api/views/vpb3-uf7s

property e:vpb3-uf7s t:meta.view d:2017-03-08T01:25:06.950Z v:id=vpb3-uf7s v:category="City Government" v:attributionLink=http://www.nyc.gov/html/hia/html/public_insurance/children.shtml v:averageRating=0 v:name="Child health plus income levels" v:attribution="Human Resources Administration (HRA)"

property e:vpb3-uf7s t:meta.view.owner d:2017-03-08T01:25:06.950Z v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:displayName="NYC OpenData"

property e:vpb3-uf7s t:meta.view.tableauthor d:2017-03-08T01:25:06.950Z v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:displayName="NYC OpenData"
```