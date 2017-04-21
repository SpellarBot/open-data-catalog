# Charitable Gift Annuity Registrants

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/charitable-gift-annuity-registrants) |
| Metadata | [Link](https://data.iowa.gov/api/views/8kcb-p2ep) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/8kcb-p2ep/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/8kcb-p2ep/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | 8kcb-p2ep |
| Name | Charitable Gift Annuity Registrants |
| Attribution | Iowa Insurance Division, Iowa Department of Commerce |
| Category | Government |
| Tags | charitable gifts, annuity |
| Created | 2016-11-16T21:52:35Z |
| Publication Date | 2017-01-11T17:07:30Z |

## Description

?Charitable gift annuity? means a transfer of property by a donor to a charitable organization in return for an annuity payable over one or two lives, if the actuarial value of the annuity is less than the value of the property transferred and the difference in value constitutes a charitable deduction for federal tax purposes.

## Columns

```ls
| Included | Schema Type | Field Name  | Name       | Data Type | Render Type |
| ======== | =========== | =========== | ========== | ========= | =========== |
| No       | time        | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag  | entity      | Entity     | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:8kcb-p2ep d:2017-01-11T17:07:19.000Z t:entity="ABWE Foundation, Inc." m:row_number.8kcb-p2ep=1

series e:8kcb-p2ep d:2017-01-11T17:07:19.000Z t:entity="AIB College of Business" m:row_number.8kcb-p2ep=2

series e:8kcb-p2ep d:2017-01-11T17:07:19.000Z t:entity="Alegent Health Foundation" m:row_number.8kcb-p2ep=3
```

## Meta Commands

```ls
metric m:row_number.8kcb-p2ep p:long l:"Row Number"

entity e:8kcb-p2ep l:"Charitable Gift Annuity Registrants" t:attribution="Iowa Insurance Division, Iowa Department of Commerce" t:url=https://data.iowa.gov/api/views/8kcb-p2ep

property e:8kcb-p2ep t:meta.view v:id=8kcb-p2ep v:category=Government v:averageRating=0 v:name="Charitable Gift Annuity Registrants" v:attribution="Iowa Insurance Division, Iowa Department of Commerce"

property e:8kcb-p2ep t:meta.view.owner v:id=ym8t-nug5 v:profileImageUrlMedium=/api/users/ym8t-nug5/profile_images/THUMB v:profileImageUrlLarge=/api/users/ym8t-nug5/profile_images/LARGE v:screenName="Iowa Insurance Division (Commerce)" v:profileImageUrlSmall=/api/users/ym8t-nug5/profile_images/TINY v:displayName="Iowa Insurance Division (Commerce)"

property e:8kcb-p2ep t:meta.view.tableauthor v:id=ym8t-nug5 v:profileImageUrlMedium=/api/users/ym8t-nug5/profile_images/THUMB v:profileImageUrlLarge=/api/users/ym8t-nug5/profile_images/LARGE v:screenName="Iowa Insurance Division (Commerce)" v:profileImageUrlSmall=/api/users/ym8t-nug5/profile_images/TINY v:roleName=publisher v:displayName="Iowa Insurance Division (Commerce)"
```

## Top Records

```ls
| :updated_at | entity                                                        | 
| =========== | ============================================================= | 
| 1484154439  | ABWE Foundation, Inc.                                         | 
| 1484154439  | AIB College of Business                                       | 
| 1484154439  | Alegent Health Foundation                                     | 
| 1484154439  | Allegheny College                                             | 
| 1484154439  | Allen Foundation                                              | 
| 1484154439  | Alzheimer's Disease and Related Disorders Association, Inc.   | 
| 1484154439  | America's Second Harvest                                      | 
| 1484154439  | American Associates, Ben-Gurion University of the Negev, Inc. | 
| 1484154439  | American Association of University Women, Inc.                | 
| 1484154439  | American Baptist Homes of the Midwest                         | 
```