# DBEDT HECO Ranks Third In 2010 Annual Solar Watts Per Customer

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dbedt-heco-ranks-third-in-2010-annual-solar-watts-per-customer-bf5dd) |
| Metadata | [Link](https://data.hawaii.gov/api/views/jyvh-hvkp) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/jyvh-hvkp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/jyvh-hvkp/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | jyvh-hvkp |
| Name | DBEDT HECO Ranks Third In 2010 Annual Solar Watts Per Customer |
| Attribution | Department of Economic Development and Tourism |
| Category | Economic Development |
| Tags | electricity |
| Created | 2012-08-28T20:29:40Z |
| Publication Date | 2012-08-29T01:33:54Z |
| Rows Updated | 2012-08-28T20:29:42Z |

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                      | Data Type | Render Type |
| ======== | ============== | ======================= | ========================= | ========= | =========== |
| Yes      | series tag     | utility                 | Utility                   | text      | text        |
| Yes      | numeric metric | annual_solar_wac_person | Annual Solar (WAC/person) | number    | number      |
```

## Time Field

```ls
Value = 
Format & Zone = yyyy
```

## Data Commands

```ls
series e:jyvh-hvkp d:2010-01-01T00:00:00.000Z t:utility="1. Silicon Valley Power (CA)" m:annual_solar_wac_person=40

series e:jyvh-hvkp d:2010-01-01T00:00:00.000Z t:utility="2. Public Service Electric & Gas Co. (NJ)" m:annual_solar_wac_person=35.2

series e:jyvh-hvkp d:2010-01-01T00:00:00.000Z t:utility="3. Hawaiian Electric Co., Inc. (HI)" m:annual_solar_wac_person=33.2
```

## Meta Commands

```ls
metric m:annual_solar_wac_person p:float l:"Annual Solar (WAC/person)" t:dataTypeName=number

entity e:jyvh-hvkp l:"DBEDT HECO Ranks Third In 2010 Annual Solar Watts Per Customer" t:attribution="Department of Economic Development and Tourism" t:url=https://data.hawaii.gov/api/views/jyvh-hvkp

property e:jyvh-hvkp t:meta.view v:id=jyvh-hvkp v:category="Economic Development" v:attributionLink=http://hawaii.gov/dbedt v:averageRating=0 v:name="DBEDT HECO Ranks Third In 2010 Annual Solar Watts Per Customer" v:attribution="Department of Economic Development and Tourism"

property e:jyvh-hvkp t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:jyvh-hvkp t:meta.view.owner v:id=uaqq-pakk v:screenName="Douglas Oshiro" v:displayName="Douglas Oshiro"

property e:jyvh-hvkp t:meta.view.tableauthor v:id=uaqq-pakk v:screenName="Douglas Oshiro" v:displayName="Douglas Oshiro"
```