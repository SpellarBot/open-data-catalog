# Solar- Related Construction Expenditures (value of solar projects as percentage of total building permit value) (Source: DBEDT)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/solar-related-construction-projects-based-on-percent-of-total-construction-expenditures-so-54d17) |
| Metadata | [Link](https://data.hawaii.gov/api/views/7cps-5y5m) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/7cps-5y5m/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/7cps-5y5m/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | 7cps-5y5m |
| Name | Solar- Related Construction Expenditures (value of solar projects as percentage of total building permit value) (Source: DBEDT) |
| Attribution | DBEDT |
| Created | 2012-11-20T21:26:00Z |
| Publication Date | 2016-09-27T21:48:06Z |

## Columns

```ls
| Included | Schema Type    | Field Name                        | Name                                | Data Type | Render Type |
| ======== | ============== | ================================= | =================================== | ========= | =========== |
| Yes      | time           | year                              | Year                                | number    | number      |
| Yes      | numeric metric | solar_projects                    | Solar Projects                      | percent   | percent     |
| Yes      | numeric metric | solar_projects_in_million_dollars | Solar Projects (in million dollars) | money     | money       |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:7cps-5y5m d:2009-01-01T00:00:00.000Z m:solar_projects_in_million_dollars=93.2 m:solar_projects=4.7

series e:7cps-5y5m d:2010-01-01T00:00:00.000Z m:solar_projects_in_million_dollars=176.8 m:solar_projects=8.9

series e:7cps-5y5m d:2011-01-01T00:00:00.000Z m:solar_projects_in_million_dollars=418.8 m:solar_projects=22.5
```

## Meta Commands

```ls
metric m:solar_projects p:float l:"Solar Projects" t:dataTypeName=percent

metric m:solar_projects_in_million_dollars p:double l:"Solar Projects (in million dollars)" t:dataTypeName=money

entity e:7cps-5y5m l:"Solar- Related Construction Expenditures (value of solar projects as percentage of total building permit value)    (Source: DBEDT)" t:attribution=DBEDT t:url=https://data.hawaii.gov/api/views/7cps-5y5m

property e:7cps-5y5m t:meta.view d:2017-09-25T07:28:19.634Z v:averageRating=0 v:name="Solar- Related Construction Expenditures (value of solar projects as percentage of total building permit value)    (Source: DBEDT)" v:attribution=DBEDT v:id=7cps-5y5m

property e:7cps-5y5m t:meta.view.owner d:2017-09-25T07:28:19.634Z v:displayName="Jerome Koehler" v:id=kpux-wcj8 v:screenName="Jerome Koehler"

property e:7cps-5y5m t:meta.view.tableauthor d:2017-09-25T07:28:19.634Z v:displayName="Jerome Koehler" v:roleName=publisher v:id=kpux-wcj8 v:screenName="Jerome Koehler"
```

## Top Records

```ls
| year | solar_projects | solar_projects_in_million_dollars | 
| ==== | ============== | ================================= | 
| 2009 | 4.7            | 93.2                              | 
| 2010 | 8.9            | 176.8                             | 
| 2011 | 22.5           | 418.8                             | 
| 2012 | 28.5           | 753.7                             | 
| 2013 | 20.2           | 549.6                             | 
| 2014 | 7.4            | 244.6                             | 
| 2015 | 14.4           | 570                               | 
| 2016 | 10.2           | 408.3                             | 
```