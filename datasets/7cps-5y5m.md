# Solar- Related Construction Expenditures (value of solar projects as percentage of total building permit value) (Source: DBEDT)

## Dataset

* [Dataset URL](https://data.hawaii.gov/api/views/7cps-5y5m/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/solar-related-construction-projects-based-on-percent-of-total-construction-expenditures-so-54d17)
* [Metadata URL](https://data.hawaii.gov/api/views/7cps-5y5m)
* Id = 7cps-5y5m
* Name = Solar- Related Construction Expenditures (value of solar projects as percentage of total building permit value) (Source: DBEDT)
* Attribution = DBEDT
* Created = 2012-11-20T21:26:00Z
* Publication Date = 2016-09-27T21:48:06Z
* Rows Updated = 2016-09-27T21:47:08Z

## Description



## Columns

```ls
| Name                                | Field Name                        | Data Type | Render Type | Schema Type    | Included | 
| =================================== | ================================= | ========= | =========== | ============== | ======== | 
| Year                                | year                              | number    | number      | time           | Yes      | 
| Solar Projects                      | solar_projects                    | percent   | percent     | numeric metric | Yes      | 
| Solar Projects (in million dollars) | solar_projects_in_million_dollars | money     | money       | numeric metric | Yes      | 
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = 
Annotation Fields = 
```

## Data Commands

```ls
series e:7cps-5y5m d:2009-01-01T00:00:00.000Z m:solar_projects=4.7 m:solar_projects_in_million_dollars=93.2

series e:7cps-5y5m d:2010-01-01T00:00:00.000Z m:solar_projects=8.9 m:solar_projects_in_million_dollars=176.8

series e:7cps-5y5m d:2011-01-01T00:00:00.000Z m:solar_projects=22.5 m:solar_projects_in_million_dollars=418.8
```

## Meta Commands

```ls
entity e:7cps-5y5m l:"Solar- Related Construction Expenditures (value of solar projects as percentage of total building permit value)    (Source: DBEDT)" t:attribution=DBEDT t:url=https://data.hawaii.gov/api/views/7cps-5y5m

property e:7cps-5y5m t:meta.view d:2017-03-07T22:42:05.585Z v:id=7cps-5y5m v:averageRating=0 v:name="Solar- Related Construction Expenditures (value of solar projects as percentage of total building permit value)    (Source: DBEDT)" v:attribution=DBEDT

property e:7cps-5y5m t:meta.view.owner d:2017-03-07T22:42:05.585Z v:id=kpux-wcj8 v:screenName="Jerome Koehler" v:roleName=publisher v:displayName="Jerome Koehler"

property e:7cps-5y5m t:meta.view.tableauthor d:2017-03-07T22:42:05.585Z v:id=kpux-wcj8 v:screenName="Jerome Koehler" v:roleName=publisher v:displayName="Jerome Koehler"
```