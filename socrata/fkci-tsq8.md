# Restricted Flavored Tobacco Flavor Terms

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/restricted-flavored-tobacco-flavor-terms) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/fkci-tsq8) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/fkci-tsq8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/fkci-tsq8/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | fkci-tsq8 |
| Name | Restricted Flavored Tobacco Flavor Terms |
| Attribution | Chicago Department of Public Health |
| Category | Health & Human Services |
| Tags | business, health, regulation, tobacco |
| Created | 2016-01-12T17:25:50Z |
| Publication Date | 2016-01-13T15:54:22Z |

## Description

A list of tobacco flavor terms. These terms may be considered, along with other evidence, to determine if a tobacco product is flavored. See http://www.cityofchicago.org/content/dam/city/depts/cdph/policy_planning/Board_of_Health/FlavoredTobaccoRules_Final_Dec112015.pdf for the specifics of the regulation regarding restrictions on the sale of flavored tobacco products within 500 feet of schools. A non-exhaustive list of restricted flavored tobacco products is available here: https://data.cityofchicago.org/d/5wce-bks2.

## Columns

```ls
| Included | Schema Type | Field Name  | Name        | Data Type | Render Type |
| ======== | =========== | =========== | =========== | ========= | =========== |
| No       | time        | :updated_at | updated_at  | meta_data | meta_data   |
| Yes      | series tag  | flavor_term | Flavor Term | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:fkci-tsq8 d:2016-01-12T09:35:40.000Z t:flavor_term="ACAI BERRY" m:row_number.fkci-tsq8=1

series e:fkci-tsq8 d:2016-01-12T09:35:40.000Z t:flavor_term=ALMOND m:row_number.fkci-tsq8=2

series e:fkci-tsq8 d:2016-01-12T09:35:40.000Z t:flavor_term="ALMOND COCONUT BAR" m:row_number.fkci-tsq8=3
```

## Meta Commands

```ls
metric m:row_number.fkci-tsq8 p:long l:"Row Number"

entity e:fkci-tsq8 l:"Restricted Flavored Tobacco Flavor Terms" t:attribution="Chicago Department of Public Health" t:url=https://data.cityofchicago.org/api/views/fkci-tsq8

property e:fkci-tsq8 t:meta.view v:id=fkci-tsq8 v:category="Health & Human Services" v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="Restricted Flavored Tobacco Flavor Terms" v:attribution="Chicago Department of Public Health"

property e:fkci-tsq8 t:meta.view.owner v:id=njxj-c7mb v:screenName="Natalie Raketich" v:displayName="Natalie Raketich"

property e:fkci-tsq8 t:meta.view.tableauthor v:id=njxj-c7mb v:screenName="Natalie Raketich" v:roleName=publisher v:displayName="Natalie Raketich"
```

## Top Records

```ls
| :updated_at | flavor_term        | 
| =========== | ================== | 
| 1452591340  | ACAI BERRY         | 
| 1452591340  | ALMOND             | 
| 1452591340  | ALMOND COCONUT BAR | 
| 1452591340  | AMARETTO           | 
| 1452591340  | ANISEED            | 
| 1452591340  | ANISETTE           | 
| 1452591340  | APPLE              | 
| 1452591340  | APPLE BLEND        | 
| 1452591340  | APPLE BROWN BETTY  | 
| 1452591340  | APPLE CINNAMON     | 
```