# Developers Featured Content

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/developers-featured-content-1e363) |
| Metadata | [Link](https://data.oregon.gov/api/views/bgs4-pj98) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/bgs4-pj98/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/bgs4-pj98/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | bgs4-pj98 |
| Name | Developers Featured Content |
| Created | 2014-07-08T13:13:13Z |
| Publication Date | 2015-03-23T18:27:16Z |

## Columns

```ls
| Included | Schema Type    | Field Name  | Name        | Data Type | Render Type |
| ======== | ============== | =========== | =========== | ========= | =========== |
| No       | time           | :updated_at | updated_at  | meta_data | meta_data   |
| Yes      | series tag     | title       | Title       | text      | text        |
| Yes      | series tag     | description | Description | text      | text        |
| Yes      | series tag     | link        | Link        | text      | text        |
| Yes      | numeric metric | order       | Order       | number    | number      |
| Yes      | series tag     | show        | Show        | checkbox  | checkbox    |
| Yes      | series tag     | image       | Image       | photo     | photo       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:bgs4-pj98 d:2014-07-15T13:08:37.000Z t:title="Clear Gasoline Locator" t:description="Build an app that helps motorists find ""clear"" gasoline locations throughout the state of Oregon." t:link=/Recreation/-Clear-Gasoline-locations/qwux-prpy t:image=ePwbmftyGBpdWWnE0_7OuA9yN47YvyxXkmcX0fBz9PU t:show=true m:order=2

series e:bgs4-pj98 d:2014-07-15T13:25:30.000Z t:title="Have a great idea?" t:description="If you have an idea for a great app that needs a specific dataset from an Oregon agency or entity, please suggest a dataset!" t:link=/nominate t:image=e7SEPmRhA-El3hDsdoeeGE5hZcCZCMMC5lGKxcArTfs t:show=true m:order=3

series e:bgs4-pj98 d:2015-03-23T11:27:14.000Z t:title="Bills signed by Governor" t:description="Use this dataset and others for previous years to build an for an app that tracks Oregon bills signed by the Governor" t:link=https://data.oregon.gov/dataset/Bills-Signed-By-Governor-Brown-2015/kiyy-dbi3 t:image=UpskuviYy6H-IJY2cqeVmwaMQsaqcnLxFcjbibedPS0 t:show=true m:order=1
```

## Meta Commands

```ls
metric m:order p:integer l:Order t:dataTypeName=number

entity e:bgs4-pj98 l:"Developers Featured Content" t:url=https://data.oregon.gov/api/views/bgs4-pj98

property e:bgs4-pj98 t:meta.view v:id=bgs4-pj98 v:averageRating=0 v:name="Developers Featured Content"

property e:bgs4-pj98 t:meta.view.owner v:id=yr5y-ep82 v:profileImageUrlMedium=/api/users/yr5y-ep82/profile_images/THUMB v:profileImageUrlLarge=/api/users/yr5y-ep82/profile_images/LARGE v:screenName="Jason Rood" v:profileImageUrlSmall=/api/users/yr5y-ep82/profile_images/TINY v:displayName="Jason Rood"

property e:bgs4-pj98 t:meta.view.tableauthor v:id=yr5y-ep82 v:profileImageUrlMedium=/api/users/yr5y-ep82/profile_images/THUMB v:profileImageUrlLarge=/api/users/yr5y-ep82/profile_images/LARGE v:screenName="Jason Rood" v:profileImageUrlSmall=/api/users/yr5y-ep82/profile_images/TINY v:roleName=publisher v:displayName="Jason Rood"
```

## Top Records

```ls
| :updated_at | title                    | description                                                                                                                  | link                                                                          | order | show | image                                       | 
| =========== | ======================== | ============================================================================================================================ | ============================================================================= | ===== | ==== | =========================================== | 
| 1405429717  | Clear Gasoline Locator   | Build an app that helps motorists find "clear" gasoline locations throughout the state of Oregon.                            | /Recreation/-Clear-Gasoline-locations/qwux-prpy                               | 2     | true | ePwbmftyGBpdWWnE0_7OuA9yN47YvyxXkmcX0fBz9PU | 
| 1405430730  | Have a great idea?       | If you have an idea for a great app that needs a specific dataset from an Oregon agency or entity, please suggest a dataset! | /nominate                                                                     | 3     | true | e7SEPmRhA-El3hDsdoeeGE5hZcCZCMMC5lGKxcArTfs | 
| 1427110034  | Bills signed by Governor | Use this dataset and others for previous years to build an for an app that tracks Oregon bills signed by the Governor        | https://data.oregon.gov/dataset/Bills-Signed-By-Governor-Brown-2015/kiyy-dbi3 | 1     | true | UpskuviYy6H-IJY2cqeVmwaMQsaqcnLxFcjbibedPS0 | 
```