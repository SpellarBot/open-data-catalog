# Performance Metrics - Procurement Services - City Auctions

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/performance-metrics-procurement-services-city-auctions-266f8) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/s9wg-6is6) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/s9wg-6is6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/s9wg-6is6/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | s9wg-6is6 |
| Name | Performance Metrics - Procurement Services - City Auctions |
| Attribution | City of Chicago |
| Category | Administration & Finance |
| Tags | performance metrics, revenue |
| Created | 2011-09-21T00:02:53Z |
| Publication Date | 2017-04-19T11:10:24Z |

## Description

The City of Chicago auctions surplus equipment, vehicles, furniture, office equipment, and other goods and materials online in order to raise funds. The below graph provides weekly updates on progress toward the fundraising target of $4.6 million.

## Columns

```ls
| Included | Schema Type    | Field Name                               | Name                                          | Data Type | Render Type |
| ======== | ============== | ======================================== | ============================================= | ========= | =========== |
| No       | time           | :updated_at                              | updated_at                                    | meta_data | meta_data   |
| No       |                | week                                     | Week                                          | text      | text        |
| Yes      | series tag     | year                                     | Year                                          | text      | text        |
| Yes      | numeric metric | revenue_from_city_auctions_year_to_date_ | Revenue from City Auctions (Year to Date ($)) | money     | money       |
| Yes      | numeric metric | percent_toward_yearly_goal_2_2_million_  | Percent Toward Yearly Goal                    | percent   | percent     |
| Yes      | numeric metric | yearly_goal_                             | Yearly Goal ($)                               | money     | money       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = week
```

## Data Commands

```ls
series e:s9wg-6is6 d:2017-04-19T11:10:21.000Z t:year=2011 m:percent_toward_yearly_goal_2_2_million_=40.56 m:revenue_from_city_auctions_year_to_date_=892231.95 m:yearly_goal_=2200000

series e:s9wg-6is6 d:2017-04-19T11:10:21.000Z t:year=2011 m:percent_toward_yearly_goal_2_2_million_=41.35 m:revenue_from_city_auctions_year_to_date_=909761.07 m:yearly_goal_=2200000

series e:s9wg-6is6 d:2017-04-19T11:10:21.000Z t:year=2011 m:percent_toward_yearly_goal_2_2_million_=42.65 m:revenue_from_city_auctions_year_to_date_=938249.06 m:yearly_goal_=2200000
```

## Meta Commands

```ls
metric m:revenue_from_city_auctions_year_to_date_ p:double l:"Revenue from City Auctions (Year to Date ($))" t:dataTypeName=money

metric m:percent_toward_yearly_goal_2_2_million_ p:float l:"Percent Toward Yearly Goal" t:dataTypeName=percent

metric m:yearly_goal_ p:integer l:"Yearly Goal ($)" t:dataTypeName=money

entity e:s9wg-6is6 l:"Performance Metrics - Procurement Services - City Auctions" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/s9wg-6is6

property e:s9wg-6is6 t:meta.view v:id=s9wg-6is6 v:category="Administration & Finance" v:attributionLink=http://www.cityofchicago.org/performance v:averageRating=0 v:name="Performance Metrics - Procurement Services - City Auctions" v:attribution="City of Chicago"

property e:s9wg-6is6 t:meta.view.owner v:id=vi9p-p863 v:screenName="Eric Phillips" v:displayName="Eric Phillips"

property e:s9wg-6is6 t:meta.view.tableauthor v:id=vi9p-p863 v:screenName="Eric Phillips" v:displayName="Eric Phillips"
```

## Top Records

```ls
| :updated_at | week                 | year | revenue_from_city_auctions_year_to_date_ | percent_toward_yearly_goal_2_2_million_ | yearly_goal_ | 
| =========== | ==================== | ==== | ======================================== | ======================================= | ============ | 
| 1492600221  | Week                 | Year |                                          |                                         |              | 
| 1492600221  | Apr 11-17, 2011      | 2011 | 892231.95                                | 40.56                                   | 2200000      | 
| 1492600221  | Apr 18-24, 2011      | 2011 | 909761.07                                | 41.35                                   | 2200000      | 
| 1492600221  | Apr 25 - May 1, 2011 | 2011 | 938249.06                                | 42.65                                   | 2200000      | 
| 1492600221  | May 2-8, 2011        | 2011 | 1081067.13                               | 49.14                                   | 2200000      | 
| 1492600221  | May 9-15, 2011       | 2011 | 1115828.89                               | 50.72                                   | 2200000      | 
| 1492600221  | May 16-22, 2011      | 2011 | 1183818.48                               | 53.81                                   | 2200000      | 
| 1492600221  | May 23-29, 2011      | 2011 | 1280352.74                               | 58.20                                   | 2200000      | 
| 1492600221  | May 30 - Jun 5       | 2011 | 1284759.41                               | 58.40                                   | 2200000      | 
| 1492600221  | Jun 6-12, 2011       | 2011 | 1448487.68                               | 65.84                                   | 2200000      | 
```