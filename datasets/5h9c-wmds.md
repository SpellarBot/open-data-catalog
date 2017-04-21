# Austin Water - Commercial Water Consumption

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/austin-water-commercial-water-consumption) |
| Metadata | [Link](https://data.austintexas.gov/api/views/5h9c-wmds) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/5h9c-wmds/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/5h9c-wmds/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | 5h9c-wmds |
| Name | Austin Water - Commercial Water Consumption |
| Attribution | Austin Water |
| Category | Utility |
| Tags | aw, water, commerical, consumption |
| Created | 2015-08-31T18:19:23Z |
| Publication Date | 2016-11-21T15:52:57Z |

## Description

Monthly commercial water consumption by zip code and customer class.

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type | Render Type |
| ======== | ============== | ============== | ============== | ========= | =========== |
| No       | time           | :updated_at    | updated_at     | meta_data | meta_data   |
| Yes      | numeric metric | year_month     | Year Month     | number    | text        |
| Yes      | series tag     | postal_code    | Postal Code    | text      | text        |
| Yes      | series tag     | customer_class | Customer Class | text      | text        |
| Yes      | numeric metric | total_gallons  | Total Gallons  | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:5h9c-wmds d:2016-11-21T15:52:38.000Z t:customer_class="Irrigation - Commercial" t:postal_code=78613 m:year_month=201201 m:total_gallons=855400

series e:5h9c-wmds d:2016-11-21T15:52:38.000Z t:customer_class=Commercial t:postal_code=78613 m:year_month=201201 m:total_gallons=2880800

series e:5h9c-wmds d:2016-11-21T15:52:38.000Z t:customer_class="Austin Water Utility" t:postal_code=78617 m:year_month=201201 m:total_gallons=438700
```

## Meta Commands

```ls
metric m:year_month p:integer l:"Year Month" t:dataTypeName=number

metric m:total_gallons p:integer l:"Total Gallons" t:dataTypeName=number

entity e:5h9c-wmds l:"Austin Water - Commercial Water Consumption" t:attribution="Austin Water" t:url=https://data.austintexas.gov/api/views/5h9c-wmds

property e:5h9c-wmds t:meta.view v:id=5h9c-wmds v:category=Utility v:attributionLink=http://www.austintexas.gov/department/water v:averageRating=0 v:name="Austin Water - Commercial Water Consumption" v:attribution="Austin Water"

property e:5h9c-wmds t:meta.view.license v:name="Public Domain"

property e:5h9c-wmds t:meta.view.owner v:id=4786-56ku v:screenName="Patricia Genty Andrade" v:displayName="Patricia Genty Andrade"

property e:5h9c-wmds t:meta.view.tableauthor v:id=4786-56ku v:screenName="Patricia Genty Andrade" v:roleName=editor v:displayName="Patricia Genty Andrade"
```

## Top Records

```ls
| :updated_at | year_month | postal_code | customer_class              | total_gallons | 
| =========== | ========== | =========== | =========================== | ============= | 
| 1479743558  | 201201     | 78613       | Irrigation - Commercial     | 855400        | 
| 1479743558  | 201201     | 78613       | Commercial                  | 2880800       | 
| 1479743558  | 201201     | 78617       | Austin Water Utility        | 438700        | 
| 1479743558  | 201201     | 78617       | City of Austin              | 6500300       | 
| 1479743558  | 201201     | 78617       | Commercial                  | 9120500       | 
| 1479743558  | 201201     | 78617       | Irrigation - City of Austin | 0             | 
| 1479743558  | 201201     | 78617       | Irrigation - Commercial     | 566800        | 
| 1479743558  | 201201     | 78652       | Commercial                  | 153700        | 
| 1479743558  | 201201     | 78653       | Wholesale                   | 0             | 
| 1479743558  | 201201     | 78653       | Commercial                  | 251100        | 
```