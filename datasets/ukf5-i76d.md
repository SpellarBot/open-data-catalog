# Emissions By Plant

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/emissions-by-plant) |
| Metadata | [Link](https://data.austintexas.gov/api/views/ukf5-i76d) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/ukf5-i76d/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/ukf5-i76d/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | ukf5-i76d |
| Name | Emissions By Plant |
| Attribution | Austin Energy |
| Category | Utilities and City Services |
| Tags | emissions by plant, gas, greenhouse gas, carbon dioxide, energy |
| Created | 2016-09-12T15:33:02Z |
| Publication Date | 2016-10-25T19:31:04Z |

## Description

Austin Energy has a goal to reduce CO2 emissions by 2020 to a level that is 20% below 2005 levels. View the type of gas and emissions in metric tons per location starting in 2005. Go to austinenergy.com/go/environment and  austinenergy.com/go/corporatereports to learn more about Austin Energy's commitment to the environment.

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type     | Render Type   |
| ======== | ============== | ======================= | ======================= | ============= | ============= |
| Yes      | time           | calendar_year_2         | Calendar Year           | calendar_date | calendar_date |
| Yes      | series tag     | emissions               | Gas                     | text          | text          |
| Yes      | series tag     | location                | Location                | text          | text          |
| Yes      | numeric metric | emissions_metric_tonnes | Emissions (Metric Tons) | number        | number        |
```

## Time Field

```ls
Value = calendar_year_2
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:ukf5-i76d d:2005-01-01T00:00:00.000Z t:location=Decker t:emissions=SO2 m:emissions_metric_tonnes=3

series e:ukf5-i76d d:2005-01-01T00:00:00.000Z t:location="Sand Hill" t:emissions=SO2 m:emissions_metric_tonnes=3

series e:ukf5-i76d d:2005-01-01T00:00:00.000Z t:location=Holly t:emissions=SO2 m:emissions_metric_tonnes=2
```

## Meta Commands

```ls
metric m:emissions_metric_tonnes p:integer l:"Emissions (Metric Tons)" t:dataTypeName=number

entity e:ukf5-i76d l:"Emissions By Plant" t:attribution="Austin Energy" t:url=https://data.austintexas.gov/api/views/ukf5-i76d

property e:ukf5-i76d t:meta.view d:2017-09-25T07:28:21.780Z v:averageRating=0 v:name="Emissions By Plant" v:attribution="Austin Energy" v:id=ukf5-i76d v:category="Utilities and City Services"

property e:ukf5-i76d t:meta.view.license d:2017-09-25T07:28:21.780Z v:name="Public Domain"

property e:ukf5-i76d t:meta.view.owner d:2017-09-25T07:28:21.780Z v:displayName="Sarah Lambert" v:profileImageUrlLarge=/api/users/c433-zrb5/profile_images/LARGE v:profileImageUrlSmall=/api/users/c433-zrb5/profile_images/TINY v:id=c433-zrb5 v:screenName="Sarah Lambert" v:profileImageUrlMedium=/api/users/c433-zrb5/profile_images/THUMB

property e:ukf5-i76d t:meta.view.tableauthor d:2017-09-25T07:28:21.780Z v:displayName="Elaine Lee" v:roleName=editor v:id=3qbr-w2gj v:screenName="Elaine Lee"
```

## Top Records

```ls
| calendar_year_2     | emissions | location   | emissions_metric_tonnes | 
| =================== | ========= | ========== | ======================= | 
| 2005-01-01T00:00:00 | SO2       | Decker     | 3                       | 
| 2005-01-01T00:00:00 | SO2       | Sand Hill  | 3                       | 
| 2005-01-01T00:00:00 | SO2       | Holly      | 2                       | 
| 2005-01-01T00:00:00 | SO2       | FPP Unit 1 | 6684                    | 
| 2005-01-01T00:00:00 | SO2       | FPP Unit 2 | 6884                    | 
| 2005-01-01T00:00:00 | NOx       | Decker     | 751                     | 
| 2005-01-01T00:00:00 | NOx       | Sand Hill  | 228                     | 
| 2005-01-01T00:00:00 | NOx       | Holly      | 254                     | 
| 2005-01-01T00:00:00 | NOx       | FPP Unit 1 | 1056                    | 
| 2005-01-01T00:00:00 | NOx       | FPP Unit 2 | 1068                    | 
```