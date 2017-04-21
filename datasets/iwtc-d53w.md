# Public Safety: Q3 Performance Management Goal Assessment

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/public-safety-q3-performance-management-goal-assessment-235d2) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/iwtc-d53w) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/iwtc-d53w/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/iwtc-d53w/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | iwtc-d53w |
| Name | Public Safety: Q3 Performance Management Goal Assessment |
| Category | Public Safety |
| Created | 2012-10-18T03:04:22Z |
| Publication Date | 2014-10-27T16:40:05Z |

## Columns

```ls
| Included | Schema Type | Field Name                             | Name                                    | Data Type | Render Type |
| ======== | =========== | ====================================== | ======================================= | ========= | =========== |
| No       | time        | :updated_at                            | updated_at                              | meta_data | meta_data   |
| Yes      | series tag  | goal_1_reduce_jail_population_and_cost | Goal 1: Reduce Jail Population And Cost | text      | text        |
| Yes      | series tag  | reporting_office                       | Reporting Office                        | text      | text        |
| Yes      | series tag  | actual                                 | 2011 Actual                             | text      | text        |
| Yes      | series tag  | target                                 | 2012 Target                             | text      | text        |
| Yes      | series tag  | q3_ytd_actual                          | Q3 YTD Actual                           | text      | text        |
| Yes      | series tag  | q3_ytd_target                          | Q3 YTD Target                           | text      | text        |
| Yes      | series tag  | q3_ytd_variance                        | Q3 YTD Variance                         | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:iwtc-d53w d:2012-10-17T20:04:23.000Z t:q3_ytd_target=7,800 t:goal_1_reduce_jail_population_and_cost="Average daily jail population - adult" t:q3_ytd_variance=20% t:target=7,800 t:actual=8,800 t:reporting_office=Countywide t:q3_ytd_actual=9,322 m:row_number.iwtc-d53w=1

series e:iwtc-d53w d:2012-10-17T20:04:23.000Z t:q3_ytd_target=- t:goal_1_reduce_jail_population_and_cost="Average daily jail cost per inmate - adult" t:q3_ytd_variance=- t:target=- t:actual="$143 *" t:reporting_office=Countywide t:q3_ytd_actual=N/A m:row_number.iwtc-d53w=2

series e:iwtc-d53w d:2012-10-17T20:04:23.000Z t:q3_ytd_target=250 t:goal_1_reduce_jail_population_and_cost="Average daily population - youth (Juvenile Temporary Detention Center)" t:q3_ytd_variance=0% t:target=250 t:actual=292 t:reporting_office=Countywide t:q3_ytd_actual=251 m:row_number.iwtc-d53w=3
```

## Meta Commands

```ls
metric m:row_number.iwtc-d53w p:long l:"Row Number"

entity e:iwtc-d53w l:"Public Safety: Q3 Performance Management Goal Assessment" t:url=https://datacatalog.cookcountyil.gov/api/views/iwtc-d53w

property e:iwtc-d53w t:meta.view v:id=iwtc-d53w v:category="Public Safety" v:averageRating=0 v:name="Public Safety: Q3 Performance Management Goal Assessment"

property e:iwtc-d53w t:meta.view.license v:name="Public Domain"

property e:iwtc-d53w t:meta.view.owner v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"

property e:iwtc-d53w t:meta.view.tableauthor v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"
```

## Top Records

```ls
| :updated_at | goal_1_reduce_jail_population_and_cost                                                                  | reporting_office | actual | target | q3_ytd_actual | q3_ytd_target | q3_ytd_variance | 
| =========== | ======================================================================================================= | ================ | ====== | ====== | ============= | ============= | =============== | 
| 1350504263  | Average daily jail population - adult                                                                   | Countywide       | 8,800  | 7,800  | 9,322         | 7,800         | 20%             | 
| 1350504263  | Average daily jail cost per inmate - adult                                                              | Countywide       | $143 * | -      | N/A           | -             | -               | 
| 1350504263  | Average daily population - youth (Juvenile Temporary Detention Center)                                  | Countywide       | 292    | 250    | 251           | 250           | 0%              | 
| 1350504263  | % of orders at Central Bond Court resulting in EM or I-Bond                                             | Countywide       | 18%    | 30%    | 30%           | 30%           | 0%              | 
| 1350504263  | # of homeless individuals on EM placed in temporary housing                                             | Sheriff          | 0      | 34     | 34            | 34            | 0%              | 
| 1350504263  | Goal 2: Increase Public Safety                                                                          |                  |        |        |               |               |                 | 
| 1350504263  | Neighborhoods, streets and schools safe from violence are essential to a healthy and productive County. |                  |        |        |               |               |                 | 
| 1350504263  | # of violent crimes in all of Cook County                                                               | Countywide       | N/A    | -      | TBD           | -             | -               | 
| 1350504263  | # of violent crimes in unincorporated Cook County                                                       | Sheriff          | 262    | -      | 69            | -             | -               | 
| 1350504263  | Action: Working to collect crime data for all of Cook County                                            |                  |        |        |               |               |                 | 
```