# CTA - Ridership - Avg. Weekday Bus Stop Boardings in October 2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cta-ridership-avg-weekday-bus-stop-boardings-in-october-2012-e800b) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/mq3i-nnqe) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/mq3i-nnqe/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/mq3i-nnqe/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | mq3i-nnqe |
| Name | CTA - Ridership - Avg. Weekday Bus Stop Boardings in October 2012 |
| Attribution | Chicago Transit Authority |
| Category | Transportation |
| Tags | cta, public transit, ridership, sustainability, chicago transit authority |
| Created | 2011-08-11T21:22:31Z |
| Publication Date | 2012-12-20T16:25:40Z |

## Description

This dataset shows approximate, average, weekday boardings by bus stop from the month of October 2012.

## Columns

```ls
| Included | Schema Type    | Field Name   | Name            | Data Type     | Render Type   |
| ======== | ============== | ============ | =============== | ============= | ============= |
| Yes      | series tag     | stop_id      | stop_id         | text          | number        |
| Yes      | series tag     | on_street    | on_street       | text          | text          |
| Yes      | series tag     | cross_street | cross_street    | text          | text          |
| Yes      | series tag     | routes       | routes          | text          | text          |
| Yes      | numeric metric | boardings    | boardings       | number        | number        |
| Yes      | numeric metric | alightings   | alightings      | number        | number        |
| Yes      | time           | month        | month_beginning | calendar_date | calendar_date |
| Yes      | series tag     | daytype      | daytype         | text          | text          |
```

## Time Field

```ls
Value = month
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:mq3i-nnqe d:2012-10-01T00:00:00.000Z t:stop_id=1 t:routes=126 t:cross_street=AUSTIN t:daytype=Weekday t:on_street=JACKSON m:alightings=150 m:boardings=183.4

series e:mq3i-nnqe d:2012-10-01T00:00:00.000Z t:stop_id=2 t:routes=126 t:cross_street="MAYFIELD (EXTENDED)" t:daytype=Weekday t:on_street=JACKSON m:alightings=0.2 m:boardings=5.3

series e:mq3i-nnqe d:2012-10-01T00:00:00.000Z t:stop_id=3 t:routes=126 t:cross_street=MENARD t:daytype=Weekday t:on_street=JACKSON m:alightings=0.7 m:boardings=8.3
```

## Meta Commands

```ls
metric m:boardings p:float l:boardings t:dataTypeName=number

metric m:alightings p:float l:alightings t:dataTypeName=number

entity e:mq3i-nnqe l:"CTA - Ridership - Avg. Weekday Bus Stop Boardings in October 2012" t:attribution="Chicago Transit Authority" t:url=https://data.cityofchicago.org/api/views/mq3i-nnqe

property e:mq3i-nnqe t:meta.view v:id=mq3i-nnqe v:category=Transportation v:attributionLink=http://www.transitchicago.com v:averageRating=0 v:name="CTA - Ridership - Avg. Weekday Bus Stop Boardings in October 2012" v:attribution="Chicago Transit Authority"

property e:mq3i-nnqe t:meta.view.owner v:id=6bsn-5494 v:profileImageUrlMedium=/api/users/6bsn-5494/profile_images/THUMB v:profileImageUrlLarge=/api/users/6bsn-5494/profile_images/LARGE v:screenName="cta web" v:profileImageUrlSmall=/api/users/6bsn-5494/profile_images/TINY v:displayName="cta web"

property e:mq3i-nnqe t:meta.view.tableauthor v:id=6bsn-5494 v:profileImageUrlMedium=/api/users/6bsn-5494/profile_images/THUMB v:profileImageUrlLarge=/api/users/6bsn-5494/profile_images/LARGE v:screenName="cta web" v:profileImageUrlSmall=/api/users/6bsn-5494/profile_images/TINY v:roleName=designer v:displayName="cta web"
```

## Top Records

```ls
| stop_id | on_street | cross_street        | routes | boardings | alightings | month               | daytype | 
| ======= | ========= | =================== | ====== | ========= | ========== | =================== | ======= | 
| 1       | JACKSON   | AUSTIN              | 126    | 183.4     | 150.0      | 2012-10-01T00:00:00 | Weekday | 
| 2       | JACKSON   | MAYFIELD (EXTENDED) | 126    | 5.3       | 0.2        | 2012-10-01T00:00:00 | Weekday | 
| 3       | JACKSON   | MENARD              | 126    | 8.3       | 0.7        | 2012-10-01T00:00:00 | Weekday | 
| 4       | JACKSON   | 5700 WEST           | 126    | 17.9      | 3.0        | 2012-10-01T00:00:00 | Weekday | 
| 6       | JACKSON   | LOTUS               | 126    | 74.0      | 11.2       | 2012-10-01T00:00:00 | Weekday | 
| 7       | JACKSON   | 5351 WEST           | 126    | 14.3      | 2.5        | 2012-10-01T00:00:00 | Weekday | 
| 8       | JACKSON   | LOCKWOOD            | 126    | 62.4      | 14.1       | 2012-10-01T00:00:00 | Weekday | 
| 9       | JACKSON   | LARAMIE             | 126    | 0.1       | 0.0        | 2012-10-01T00:00:00 | Weekday | 
| 12      | JACKSON   | LAVERGNE            | 126    | 0.0       | 0.0        | 2012-10-01T00:00:00 | Weekday | 
| 13      | JACKSON   | 4849 WEST           | 126    | 0.0       | 0.0        | 2012-10-01T00:00:00 | Weekday | 
```