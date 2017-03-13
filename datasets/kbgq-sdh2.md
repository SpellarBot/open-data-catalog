# DBEDT Hawaii Utility Companies Rank Among The Top In Cumulative Solar Watts Per Customer

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dbedt-hawaii-utility-companies-rank-among-the-top-in-cumulative-solar-watts-per-customer-1b934) |
| Metadata | [Link](https://data.hawaii.gov/api/views/kbgq-sdh2) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/kbgq-sdh2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/kbgq-sdh2/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | kbgq-sdh2 |
| Name | DBEDT Hawaii Utility Companies Rank Among The Top In Cumulative Solar Watts Per Customer |
| Attribution | Department of Economic Development and Tourism |
| Category | Economic Development |
| Tags | energy, utility |
| Created | 2012-08-28T20:24:10Z |
| Publication Date | 2012-08-29T01:32:40Z |
| Rows Updated | 2012-08-28T20:24:29Z |

## Columns

```ls
| Included | Schema Type    | Field Name                           | Name                                   | Data Type | Render Type |
| ======== | ============== | ==================================== | ====================================== | ========= | =========== |
| No       | time           | :updated_at                          | updated_at                             | meta_data | meta_data   |
| Yes      | series tag     | utility                              | Utility                                | text      | text        |
| Yes      | numeric metric | cumulative_through_2010_wac_customer | Cumulative Through 2010 (WAC/customer) | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:kbgq-sdh2 d:2012-08-28T13:24:11.000Z t:utility="1. Southern California Edison (CA)" m:cumulative_through_2010_wac_customer=119.1

series e:kbgq-sdh2 d:2012-08-28T13:24:11.000Z t:utility="3. City of Palo Alto Utilities (CA)" m:cumulative_through_2010_wac_customer=97

series e:kbgq-sdh2 d:2012-08-28T13:24:11.000Z t:utility="4. Hawaii Electric Light Co. (HI)" m:cumulative_through_2010_wac_customer=93.6
```

## Meta Commands

```ls
metric m:cumulative_through_2010_wac_customer p:float l:"Cumulative Through 2010 (WAC/customer)" t:dataTypeName=number

entity e:kbgq-sdh2 l:"DBEDT Hawaii Utility Companies Rank Among The Top In Cumulative Solar Watts Per Customer" t:attribution="Department of Economic Development and Tourism" t:url=https://data.hawaii.gov/api/views/kbgq-sdh2

property e:kbgq-sdh2 t:meta.view v:id=kbgq-sdh2 v:category="Economic Development" v:attributionLink=http://hawaii.gov/dbedt v:averageRating=0 v:name="DBEDT Hawaii Utility Companies Rank Among The Top In Cumulative Solar Watts Per Customer" v:attribution="Department of Economic Development and Tourism"

property e:kbgq-sdh2 t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:kbgq-sdh2 t:meta.view.owner v:id=uaqq-pakk v:screenName="Douglas Oshiro" v:displayName="Douglas Oshiro"

property e:kbgq-sdh2 t:meta.view.tableauthor v:id=uaqq-pakk v:screenName="Douglas Oshiro" v:displayName="Douglas Oshiro"
```