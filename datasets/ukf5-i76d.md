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
| Category | Utility |
| Tags | emissions by plant, gas, greenhouse gas, carbon dioxide, energy |
| Created | 2016-09-12T15:33:02Z |
| Publication Date | 2016-10-25T19:31:04Z |
| Rows Updated | 2016-10-25T19:30:33Z |

## Description

Austin Energy has a goal to reduce CO2 emissions by 2020 to a level that is 20% below 2005 levels. CO2-equivalent is a measure used to compare the emissions of different greenhouse gases based on their global warming potential.This goal was approved by the Austin City Council in April 2010 as part of Austin Energy’s Generation Plan. From 2005 to 2012 Austin Energy stack emissions have declined by 16.5%. 

Total stack greenhouse gas emissions reported here include carbon dioxide (CO2) as well as the greenhouse gases methane and nitrous oxide, and are reported as metric tonnes of carbon dioxide equivalents (CO2-eq). Carbon dioxide equivalent is a measure used to compare the emissions of different greenhouse gases based on their global warming potential (GWP). Non-CO2 greenhouse gases make up less than 1% of Austin Energy’s stack emissions.

Plant gas emissions reported in the below table do not include CO2-equivalents and are reported in English dry tons. Austin Energy uses English dry tons for annual reporting to the Environmental Protection Agency (EPA).

FPP=Fayette Power Project

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
series e:ukf5-i76d d:2005-01-01T00:00:00.000Z t:emissions=SO2 t:location=Decker m:emissions_metric_tonnes=3

series e:ukf5-i76d d:2005-01-01T00:00:00.000Z t:emissions=SO2 t:location="Sand Hill" m:emissions_metric_tonnes=3

series e:ukf5-i76d d:2005-01-01T00:00:00.000Z t:emissions=SO2 t:location=Holly m:emissions_metric_tonnes=2
```

## Meta Commands

```ls
metric m:emissions_metric_tonnes p:integer l:"Emissions (Metric Tons)" t:dataTypeName=number

entity e:ukf5-i76d l:"Emissions By Plant" t:attribution="Austin Energy" t:url=https://data.austintexas.gov/api/views/ukf5-i76d

property e:ukf5-i76d t:meta.view v:id=ukf5-i76d v:category=Utility v:averageRating=0 v:name="Emissions By Plant" v:attribution="Austin Energy"

property e:ukf5-i76d t:meta.view.license v:name="Public Domain"

property e:ukf5-i76d t:meta.view.owner v:id=3qbr-w2gj v:screenName="Elaine Lee" v:displayName="Elaine Lee"

property e:ukf5-i76d t:meta.view.tableauthor v:id=3qbr-w2gj v:screenName="Elaine Lee" v:roleName=editor v:displayName="Elaine Lee"
```