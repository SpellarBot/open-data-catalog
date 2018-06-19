# Public Health Statistics- Life Expectancy By Community Area

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/public-health-statistics-life-expectancy-by-community-area-0a0c4) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/qjr3-bm53) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/qjr3-bm53/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/qjr3-bm53/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | qjr3-bm53 |
| Name | Public Health Statistics- Life Expectancy By Community Area |
| Attribution | Vital statistics files produced by the Illinois Department of Public Health (IDPH) |
| Category | Health & Human Services |
| Tags | health, life, death |
| Created | 2014-06-16T17:02:27Z |
| Publication Date | 2014-08-27T15:43:34Z |

## Description

This dataset gives the average life expectancy and corresponding confidence intervals for each Chicago community area for the years 1990, 2000 and 2010.  See the full description at: https://data.cityofchicago.org/api/views/qjr3-bm53/files/AAu4x8SCRz_bnQb8SVUyAXdd913TMObSYj6V40cR6p8?download=true&filename=P:\EPI\OEPHI\MATERIALS\REFERENCES\Life Expectancy\Dataset description - LE by community area.pdf

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                  | Data Type | Render Type |
| ======== | ============== | ==================== | ===================== | ========= | =========== |
| No       | time           | :updated_at          | updated_at            | meta_data | meta_data   |
| No       |                | ca                   | Community Area Number | text      | number      |
| Yes      | series tag     | community_area       | Community Area        | text      | text        |
| Yes      | numeric metric | 1990_life_expectancy | 1990 Life Expectancy  | number    | number      |
| Yes      | numeric metric | 1990_lower_95_ci     | 1990 Lower 95% CI     | number    | number      |
| Yes      | numeric metric | 1990_upper_95_ci     | 1990 Upper 95% CI     | number    | number      |
| Yes      | numeric metric | 2000_life_expectancy | 2000 Life Expectancy  | number    | number      |
| Yes      | numeric metric | 2000_lower_95_ci     | 2000 Lower 95% CI     | number    | number      |
| Yes      | numeric metric | 2000_upper_95_ci     | 2000 Upper 95% CI     | number    | number      |
| Yes      | numeric metric | 2010_life_expectancy | 2010 Life Expectancy  | number    | number      |
| Yes      | numeric metric | 2010_lower_95_ci     | 2010 Lower 95% CI     | number    | number      |
| Yes      | numeric metric | 2010_upper_95_ci     | 2010 Upper 95% CI     | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = ca
```

## Data Commands

```ls
series e:qjr3-bm53 d:2014-06-16T10:02:30.000Z t:community_area="Rogers Park" m:1990_lower_95_ci=69.9 m:2010_lower_95_ci=76.3 m:2000_upper_95_ci=74.1 m:2000_lower_95_ci=72.2 m:2010_upper_95_ci=78.2 m:1990_life_expectancy=70.9 m:2010_life_expectancy=77.3 m:1990_upper_95_ci=71.9 m:2000_life_expectancy=73.1

series e:qjr3-bm53 d:2014-06-16T10:02:30.000Z t:community_area="West Ridge" m:1990_lower_95_ci=76.1 m:2010_lower_95_ci=79.5 m:2000_upper_95_ci=78.8 m:2000_lower_95_ci=77.3 m:2010_upper_95_ci=81.1 m:1990_life_expectancy=76.9 m:2010_life_expectancy=80.3 m:1990_upper_95_ci=77.8 m:2000_life_expectancy=78.1

series e:qjr3-bm53 d:2014-06-16T10:02:30.000Z t:community_area=Uptown m:1990_lower_95_ci=63.1 m:2010_lower_95_ci=75.1 m:2000_upper_95_ci=72.7 m:2000_lower_95_ci=70.8 m:2010_upper_95_ci=76.9 m:1990_life_expectancy=64 m:2010_life_expectancy=76 m:1990_upper_95_ci=64.9 m:2000_life_expectancy=71.7
```

## Meta Commands

```ls
metric m:1990_life_expectancy p:float l:"1990 Life Expectancy" d:"Life expectancy for the year of 1990" t:dataTypeName=number

metric m:1990_lower_95_ci p:float l:"1990 Lower 95% CI" d:"Lower 95% confidence interval for the year of 1990" t:dataTypeName=number

metric m:1990_upper_95_ci p:float l:"1990 Upper 95% CI" d:"Upper 95% confidence interval for the year of 1990" t:dataTypeName=number

metric m:2000_life_expectancy p:float l:"2000 Life Expectancy" d:"Life expectancy for the year of 2000" t:dataTypeName=number

metric m:2000_lower_95_ci p:float l:"2000 Lower 95% CI" d:"Lower 95% confidence interval for the year of 2000" t:dataTypeName=number

metric m:2000_upper_95_ci p:float l:"2000 Upper 95% CI" d:"Upper 95% confidence interval for the year of 2000" t:dataTypeName=number

metric m:2010_life_expectancy p:float l:"2010 Life Expectancy" d:"Life expectancy for the year of 2010" t:dataTypeName=number

metric m:2010_lower_95_ci p:float l:"2010 Lower 95% CI" d:"Lower 95% confidence interval for the year of 2010" t:dataTypeName=number

metric m:2010_upper_95_ci p:float l:"2010 Upper 95% CI" d:"Upper 95% confidence interval for the year of 2010" t:dataTypeName=number

entity e:qjr3-bm53 l:"Public Health Statistics- Life Expectancy By Community Area" t:attribution="Vital statistics files produced by the Illinois Department of Public Health (IDPH)" t:url=https://data.cityofchicago.org/api/views/qjr3-bm53

property e:qjr3-bm53 t:meta.view v:id=qjr3-bm53 v:category="Health & Human Services" v:averageRating=0 v:name="Public Health Statistics- Life Expectancy By Community Area" v:attribution="Vital statistics files produced by the Illinois Department of Public Health (IDPH)"

property e:qjr3-bm53 t:meta.view.owner v:id=is6y-5c5n v:screenName=Jamyia v:displayName=Jamyia

property e:qjr3-bm53 t:meta.view.tableauthor v:id=is6y-5c5n v:screenName=Jamyia v:displayName=Jamyia
```

## Top Records

```ls
| :updated_at | ca | community_area  | 1990_life_expectancy | 1990_lower_95_ci | 1990_upper_95_ci | 2000_life_expectancy | 2000_lower_95_ci | 2000_upper_95_ci | 2010_life_expectancy | 2010_lower_95_ci | 2010_upper_95_ci | 
| =========== | == | =============== | ==================== | ================ | ================ | ==================== | ================ | ================ | ==================== | ================ | ================ | 
| 1402912950  | 1  | Rogers Park     | 70.9                 | 69.9             | 71.9             | 73.1                 | 72.2             | 74.1             | 77.3                 | 76.3             | 78.2             | 
| 1402912950  | 2  | West Ridge      | 76.9                 | 76.1             | 77.8             | 78.1                 | 77.3             | 78.8             | 80.3                 | 79.5             | 81.1             | 
| 1402912950  | 3  | Uptown          | 64.0                 | 63.1             | 64.9             | 71.7                 | 70.8             | 72.7             | 76.0                 | 75.1             | 76.9             | 
| 1402912950  | 4  | Lincoln Square  | 74.2                 | 73.1             | 75.4             | 76.8                 | 75.8             | 77.8             | 80.5                 | 79.3             | 81.6             | 
| 1402912950  | 5  | North Center    | 73.4                 | 72.1             | 74.7             | 77.9                 | 76.6             | 79.1             | 81.5                 | 80.1             | 82.8             | 
| 1402912950  | 6  | Lakeview        | 73.9                 | 73.0             | 74.8             | 79.2                 | 78.3             | 80.2             | 81.9                 | 81.1             | 82.7             | 
| 1402912950  | 7  | Lincoln Park    | 73.9                 | 72.9             | 74.9             | 76.5                 | 75.6             | 77.4             | 81.3                 | 80.4             | 82.3             | 
| 1402912950  | 8  | Near North Side | 74.9                 | 73.7             | 76.0             | 79.6                 | 78.7             | 80.5             | 85.2                 | 84.5             | 86.0             | 
| 1402912950  | 9  | Edison Park     | 77.6                 | 75.9             | 79.4             | 79.4                 | 77.6             | 81.2             | 81.0                 | 78.9             | 83.0             | 
| 1402912950  | 10 | Norwood Park    | 76.7                 | 75.6             | 77.8             | 78.4                 | 77.4             | 79.3             | 80.9                 | 79.8             | 82.0             | 
```