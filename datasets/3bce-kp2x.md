# Property and Taxation: Q3 2012 Performance Management Goal Assessment

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/property-and-taxation-q3-2012-performance-management-goal-assessment-d6592) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/3bce-kp2x) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/3bce-kp2x/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/3bce-kp2x/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | 3bce-kp2x |
| Name | Property and Taxation: Q3 2012 Performance Management Goal Assessment |
| Category | Property & Taxation |
| Created | 2012-10-18T03:11:01Z |
| Publication Date | 2014-10-27T16:38:55Z |

## Columns

```ls
| Included | Schema Type | Field Name                                                       | Name                                                                    | Data Type | Render Type |
| ======== | =========== | ================================================================ | ======================================================================= | ========= | =========== |
| Yes      | series tag  | goal_1_ensure_a_fair_accurate_property_valuation_appeals_process | Goal 1: Ensure A Fair & Accurate Property Valuation & Appeals Process * | text      | text        |
| Yes      | series tag  | reporting_office                                                 | Reporting Office                                                        | text      | text        |
| Yes      | series tag  | tax_year_2009                                                    | Tax Year 2009                                                           | text      | text        |
| Yes      | series tag  | tax_year_2011                                                    | Tax Year 2011                                                           | text      | text        |
| Yes      | series tag  | ty2012_ytd                                                       | TY2012 YTD                                                              | text      | text        |
| Yes      | series tag  | ty2012_target                                                    | TY2012 Target                                                           | text      | text        |
| Yes      | series tag  | ty2012_variance                                                  | TY2012 Variance                                                         | text      | text        |
```

## Time Field

```ls
Value = 2012
Format & Zone = yyyy
```

## Data Commands

```ls
series e:3bce-kp2x d:2012-01-01T00:00:00.000Z t:ty2012_variance=- t:ty2012_target=TBD t:tax_year_2011=527,490 t:ty2012_ytd=875,000 t:reporting_office=Assessor t:goal_1_ensure_a_fair_accurate_property_valuation_appeals_process="# of parcels reassessed" t:tax_year_2009=869,663 m:row_number.3bce-kp2x=1

series e:3bce-kp2x d:2012-01-01T00:00:00.000Z t:ty2012_variance=- t:ty2012_target=TBD t:tax_year_2011=1,093,220 t:ty2012_ytd=1,101,000 t:reporting_office=Assessor t:goal_1_ensure_a_fair_accurate_property_valuation_appeals_process="# of property tax exemptions received" t:tax_year_2009=1,101,937 m:row_number.3bce-kp2x=2

series e:3bce-kp2x d:2012-01-01T00:00:00.000Z t:ty2012_variance=- t:ty2012_target=TBD t:tax_year_2011=109,860 t:ty2012_ytd=135,000 t:reporting_office=Assessor t:goal_1_ensure_a_fair_accurate_property_valuation_appeals_process="# of appeals filed" t:tax_year_2009=134,975 m:row_number.3bce-kp2x=3
```

## Meta Commands

```ls
metric m:row_number.3bce-kp2x p:long l:"Row Number"

entity e:3bce-kp2x l:"Property and Taxation: Q3 2012 Performance Management Goal Assessment" t:url=https://datacatalog.cookcountyil.gov/api/views/3bce-kp2x

property e:3bce-kp2x t:meta.view v:id=3bce-kp2x v:category="Property & Taxation" v:averageRating=0 v:name="Property and Taxation: Q3 2012 Performance Management Goal Assessment"

property e:3bce-kp2x t:meta.view.license v:name="Public Domain"

property e:3bce-kp2x t:meta.view.owner v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"

property e:3bce-kp2x t:meta.view.tableauthor v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"
```