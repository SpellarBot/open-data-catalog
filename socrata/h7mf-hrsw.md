# NYC School meals income levels

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nyc-school-meals-income-levels-457bd) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/h7mf-hrsw) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/h7mf-hrsw/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/h7mf-hrsw/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | h7mf-hrsw |
| Name | NYC School meals income levels |
| Attribution | Human Resources Administration (HRA) |
| Category | Health |
| Tags | hra, human resources administration, jobs and economic mobility, nyc school meals income levels |
| Created | 2013-03-19T17:31:32Z |
| Publication Date | 2013-03-19T17:31:42Z |

## Description

The National School Lunch Program (NSLP), School Breakfast Program (SBP) and Summer Food Service Program (SFSP) provide nutritious meals to children in New York City Public Schools. All children attending schools that offer these programs can receive breakfast and lunch. Breakfast is free for all students. Some children will qualify for free or reduced price lunch, and others pay the full cost of meals, depending on family and income. This income chart sets forth the different meal costs.This chart is only a guide. Individuals should see school office personnel for assistance. 
NOTE: Chart effective July 1, 2012 to June 30, 2013. Subject to annual income updates.

## Columns

```ls
| Included | Schema Type    | Field Name                       | Name                             | Data Type | Render Type |
| ======== | ============== | ================================ | ================================ | ========= | =========== |
| No       | time           | :updated_at                      | updated_at                       | meta_data | meta_data   |
| Yes      | series tag     | meal_cost                        | Meal Cost                        | text      | text        |
| Yes      | series tag     | monthly_income_for_family_size_1 | Monthly Income For Family Size 1 | text      | text        |
| Yes      | series tag     | monthly_income_for_family_size_2 | Monthly Income For Family Size 2 | text      | text        |
| Yes      | series tag     | monthly_income_for_family_size_3 | Monthly Income For Family Size 3 | text      | text        |
| Yes      | series tag     | monthly_income_for_family_size_4 | Monthly Income For Family Size 4 | text      | text        |
| Yes      | series tag     | monthly_income_for_family_size_5 | Monthly Income For Family Size 5 | text      | text        |
| Yes      | numeric metric | each_extra_person_add_           | Each Extra Person, Add:          | money     | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:h7mf-hrsw d:2013-03-19T10:31:38.000Z t:monthly_income_for_family_size_5=$2,927 t:meal_cost="Free Lunch" t:monthly_income_for_family_size_2=$1,640 t:monthly_income_for_family_size_1=$1,211 t:monthly_income_for_family_size_4=$2,498 t:monthly_income_for_family_size_3=$2,069 m:each_extra_person_add_=429

series e:h7mf-hrsw d:2013-03-19T10:31:38.000Z t:monthly_income_for_family_size_5=$4,165 t:meal_cost="Reduced Price Lunch (25?) paid by family" t:monthly_income_for_family_size_2=$2,333 t:monthly_income_for_family_size_1=$1,723 t:monthly_income_for_family_size_4=$3,554 t:monthly_income_for_family_size_3=$2,944 m:each_extra_person_add_=611

series e:h7mf-hrsw d:2013-03-19T10:31:38.000Z t:monthly_income_for_family_size_5="Over $4,165" t:meal_cost="Full Price Lunch ($1.50) paid by family" t:monthly_income_for_family_size_2="Over $2,333" t:monthly_income_for_family_size_1="Over $1,723" t:monthly_income_for_family_size_4="Over $3,554" t:monthly_income_for_family_size_3="Over $2,944" m:each_extra_person_add_=611
```

## Meta Commands

```ls
metric m:each_extra_person_add_ p:long l:"Each Extra Person, Add:" t:dataTypeName=money

entity e:h7mf-hrsw l:"NYC School meals income levels" t:attribution="Human Resources Administration (HRA)" t:url=https://data.cityofnewyork.us/api/views/h7mf-hrsw

property e:h7mf-hrsw t:meta.view v:id=h7mf-hrsw v:category=Health v:attributionLink=http://www.nyc.gov/html/hia/html/other/benefits_child_nut.shtml v:averageRating=0 v:name="NYC School meals income levels" v:attribution="Human Resources Administration (HRA)"

property e:h7mf-hrsw t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:h7mf-hrsw t:meta.view.tableauthor v:id=ya7g-926w v:screenName="Aakash Dalwani" v:displayName="Aakash Dalwani"
```

## Top Records

```ls
| :updated_at | meal_cost                                | monthly_income_for_family_size_1 | monthly_income_for_family_size_2 | monthly_income_for_family_size_3 | monthly_income_for_family_size_4 | monthly_income_for_family_size_5 | each_extra_person_add_ | 
| =========== | ======================================== | ================================ | ================================ | ================================ | ================================ | ================================ | ====================== | 
| 1363689098  | Free Lunch                               | $1,211                           | $1,640                           | $2,069                           | $2,498                           | $2,927                           | $429                   | 
| 1363689098  | Reduced Price Lunch (25?) paid by family | $1,723                           | $2,333                           | $2,944                           | $3,554                           | $4,165                           | $611                   | 
| 1363689098  | Full Price Lunch ($1.50) paid by family  | Over $1,723                      | Over $2,333                      | Over $2,944                      | Over $3,554                      | Over $4,165                      | $611                   | 
```