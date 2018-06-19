# Maryland Adult Cigarette Smoking Status, 1995-2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/maryland-adult-cigarette-smoking-status-1995-2010-eebdc) |
| Metadata | [Link](https://data.maryland.gov/api/views/ycny-6riz) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/ycny-6riz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/ycny-6riz/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | ycny-6riz |
| Name | Maryland Adult Cigarette Smoking Status, 1995-2010 |
| Attribution | Behavioral Risk Factor Surveillance System (BRFSS) |
| Category | Health and Human Services |
| Tags | tobacco, smoking, cigarettes, risk behavior, brfss |
| Created | 2012-12-18T20:41:08Z |
| Publication Date | 2012-12-18T20:47:24Z |

## Description

Adults are defined as 18 years of age and older. The CDC defines a "Current Smoker" as an adult who has smoked at least 100 cigarettes (5 packs) in their lifetime and currently smokes either "Every Day" or "Some Days." BRFSS data methodology changed in 2011; therefore, 2011 and after is not comparable to 2010 data and before.

## Columns

```ls
| Included | Schema Type    | Field Name                                      | Name                                              | Data Type | Render Type |
| ======== | ============== | =============================================== | ================================================= | ========= | =========== |
| Yes      | time           | calendar_year                                   | Calendar Year                                     | number    | number      |
| Yes      | numeric metric | current_smoker_every_day                        | Current Smoker (Every Day)                        | number    | number      |
| Yes      | numeric metric | current_smoker_some_days                        | Current Smoker (Some Days)                        | number    | number      |
| Yes      | numeric metric | current_smoker_every_day_and_some_days_combined | Current Smoker (Every Day and Some Days Combined) | number    | number      |
| Yes      | numeric metric | former_smoker                                   | Former Smoker                                     | number    | number      |
| Yes      | numeric metric | never_smoked                                    | Never Smoked                                      | number    | number      |
```

## Time Field

```ls
Value = calendar_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:ycny-6riz d:1995-01-01T00:00:00.000Z m:current_smoker_every_day=18 m:former_smoker=20.6 m:current_smoker_some_days=3.1 m:current_smoker_every_day_and_some_days_combined=21.1 m:never_smoked=58.3

series e:ycny-6riz d:1996-01-01T00:00:00.000Z m:current_smoker_every_day=17.9 m:former_smoker=23.4 m:current_smoker_some_days=3 m:current_smoker_every_day_and_some_days_combined=20.9 m:never_smoked=55.7

series e:ycny-6riz d:1997-01-01T00:00:00.000Z m:current_smoker_every_day=17.6 m:former_smoker=22.8 m:current_smoker_some_days=2.9 m:current_smoker_every_day_and_some_days_combined=20.4 m:never_smoked=56.8
```

## Meta Commands

```ls
metric m:current_smoker_every_day p:float l:"Current Smoker (Every Day)" t:dataTypeName=number

metric m:current_smoker_some_days p:float l:"Current Smoker (Some Days)" t:dataTypeName=number

metric m:current_smoker_every_day_and_some_days_combined p:float l:"Current Smoker (Every Day and Some Days Combined)" t:dataTypeName=number

metric m:former_smoker p:float l:"Former Smoker" t:dataTypeName=number

metric m:never_smoked p:float l:"Never Smoked" t:dataTypeName=number

entity e:ycny-6riz l:"Maryland Adult Cigarette Smoking Status, 1995-2010" t:attribution="Behavioral Risk Factor Surveillance System (BRFSS)" t:url=https://data.maryland.gov/api/views/ycny-6riz

property e:ycny-6riz t:meta.view v:id=ycny-6riz v:category="Health and Human Services" v:attributionLink=http://marylandbrfss.org v:averageRating=0 v:name="Maryland Adult Cigarette Smoking Status, 1995-2010" v:attribution="Behavioral Risk Factor Surveillance System (BRFSS)"

property e:ycny-6riz t:meta.view.owner v:id=e5tx-wz6d v:screenName="Andrea Bankoski" v:displayName="Andrea Bankoski"

property e:ycny-6riz t:meta.view.tableauthor v:id=e5tx-wz6d v:screenName="Andrea Bankoski" v:roleName=editor v:displayName="Andrea Bankoski"
```

## Top Records

```ls
| calendar_year | current_smoker_every_day | current_smoker_some_days | current_smoker_every_day_and_some_days_combined | former_smoker | never_smoked | 
| ============= | ======================== | ======================== | =============================================== | ============= | ============ | 
| 1995          | 18.0                     | 3.1                      | 21.1                                            | 20.6          | 58.3         | 
| 1996          | 17.9                     | 3.0                      | 20.9                                            | 23.4          | 55.7         | 
| 1997          | 17.6                     | 2.9                      | 20.4                                            | 22.8          | 56.8         | 
| 1998          | 16.7                     | 5.7                      | 22.4                                            | 24.2          | 53.4         | 
| 1999          | 15.5                     | 4.8                      | 20.3                                            | 24.2          | 55.5         | 
| 2000          | 15.2                     | 5.3                      | 20.5                                            | 23.5          | 56.0         | 
| 2001          | 15.3                     | 5.8                      | 21.1                                            | 24.7          | 54.2         | 
| 2002          | 16.3                     | 5.6                      | 21.9                                            | 23.7          | 54.4         | 
| 2003          | 15.2                     | 4.9                      | 20.1                                            | 23.7          | 56.2         | 
| 2004          | 14.6                     | 5.0                      | 19.5                                            | 23.0          | 57.5         | 
```