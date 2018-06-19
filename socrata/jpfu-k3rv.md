# Snow Alerts

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/snow-alerts-15726) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/jpfu-k3rv) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/jpfu-k3rv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/jpfu-k3rv/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | jpfu-k3rv |
| Name | Snow Alerts |
| Category | Environment & Sustainable Development |
| Created | 2011-12-28T22:47:39Z |
| Publication Date | 2012-01-25T18:23:18Z |

## Columns

```ls
| Included | Schema Type | Field Name | Name    | Data Type     | Render Type   |
| ======== | =========== | ========== | ======= | ============= | ============= |
| Yes      | time        | date       | Date    | calendar_date | calendar_date |
| Yes      | series tag  | message    | Message | text          | text          |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:jpfu-k3rv d:2012-01-25T00:00:00.000Z t:message="There are no snow alerts at this time." m:row_number.jpfu-k3rv=1
```

## Meta Commands

```ls
metric m:row_number.jpfu-k3rv p:long l:"Row Number"

entity e:jpfu-k3rv l:"Snow Alerts" t:url=https://data.cityofchicago.org/api/views/jpfu-k3rv

property e:jpfu-k3rv t:meta.view v:id=jpfu-k3rv v:category="Environment & Sustainable Development" v:averageRating=0 v:name="Snow Alerts"

property e:jpfu-k3rv t:meta.view.owner v:id=7jj6-h75i v:screenName=Eve v:displayName=Eve

property e:jpfu-k3rv t:meta.view.tableauthor v:id=7jj6-h75i v:screenName=Eve v:displayName=Eve
```

## Top Records

```ls
| date                | message                                | 
| =================== | ====================================== | 
| 2012-01-25T00:00:00 | There are no snow alerts at this time. | 
```