# LeanCT Project Categories

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/leanct-project-categories) |
| Metadata | [Link](https://data.ct.gov/api/views/ygtj-23ju) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/ygtj-23ju/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/ygtj-23ju/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | ygtj-23ju |
| Name | LeanCT Project Categories |
| Tags | leanct, lean, process improvement, kaizen |
| Created | 2016-03-29T13:52:01Z |
| Publication Date | 2016-03-29T13:55:12Z |

## Description

A simple list of diiferent project categories for LeanCT intitiative

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type | Render Type |
| ======== | ============== | ================== | ================== | ========= | =========== |
| No       | time           | :updated_at        | updated_at         | meta_data | meta_data   |
| Yes      | series tag     | project_category   | Project Category   | text      | text        |
| Yes      | numeric metric | number_of_projects | Number of Projects | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:ygtj-23ju d:2016-03-29T06:53:24.000Z t:project_category="Cost Savings/Increased Revenue" m:number_of_projects=47

series e:ygtj-23ju d:2016-03-29T06:53:35.000Z t:project_category="Customer Experience" m:number_of_projects=69

series e:ygtj-23ju d:2016-03-29T06:54:53.000Z t:project_category="Increased Efficiency/ Productivity" m:number_of_projects=105
```

## Meta Commands

```ls
metric m:number_of_projects p:integer l:"Number of Projects" t:dataTypeName=number

entity e:ygtj-23ju l:"LeanCT Project Categories" t:url=https://data.ct.gov/api/views/ygtj-23ju

property e:ygtj-23ju t:meta.view v:id=ygtj-23ju v:averageRating=0 v:name="LeanCT Project Categories"

property e:ygtj-23ju t:meta.view.license v:name="Public Domain"

property e:ygtj-23ju t:meta.view.owner v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"

property e:ygtj-23ju t:meta.view.tableauthor v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:roleName=administrator v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"
```

## Top Records

```ls
| :updated_at | project_category                   | number_of_projects | 
| =========== | ================================== | ================== | 
| 1459234404  | Cost Savings/Increased Revenue     | 47                 | 
| 1459234415  | Customer Experience                | 69                 | 
| 1459234493  | Increased Efficiency/ Productivity | 105                | 
| 1459234498  | Interagency                        | 25                 | 
| 1459234501  | Other                              | 1                  | 
| 1459234503  | Processing Steps                   | 78                 | 
| 1459234507  | Processing Time                    | 81                 | 
| 1459234509  | Response Time                      | 54                 | 
```