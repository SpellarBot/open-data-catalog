# DBEDT HECO Ranks Third In 2010 Annual Solar Watts Per Customer

## Dataset

* [Dataset URL](https://data.hawaii.gov/api/views/jyvh-hvkp/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/dbedt-heco-ranks-third-in-2010-annual-solar-watts-per-customer-bf5dd)
* [Metadata URL](https://data.hawaii.gov/api/views/jyvh-hvkp)
* Id = jyvh-hvkp
* Name = DBEDT HECO Ranks Third In 2010 Annual Solar Watts Per Customer
* Attribution = Department of Economic Development and Tourism
* [Attribution Link](http://hawaii.gov/dbedt)
* Category = Economic Development
* Tags = [electricity]
* Created = 2012-08-28T20:29:40Z
* Publication Date = 2012-08-29T01:33:54Z
* Rows Updated = 2012-08-28T20:29:42Z

## Description



## Columns

```ls
| Name                      | Field Name              | Data Type | Render Type | Schema Type    | Included | 
| ========================= | ======================= | ========= | =========== | ============== | ======== | 
| updated_at                | :updated_at             | meta_data | meta_data   | time           | No       | 
| Utility                   | utility                 | text      | text        | series tag     | Yes      | 
| Annual Solar (WAC/person) | annual_solar_wac_person | number    | number      | numeric metric | Yes      | 
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
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
series e:jyvh-hvkp d:2012-08-28T13:29:41.000Z t:utility="1. Silicon Valley Power (CA)" m:annual_solar_wac_person=40

series e:jyvh-hvkp d:2012-08-28T13:29:41.000Z t:utility="2. Public Service Electric & Gas Co. (NJ)" m:annual_solar_wac_person=35.2

series e:jyvh-hvkp d:2012-08-28T13:29:41.000Z t:utility="3. Hawaiian Electric Co., Inc. (HI)" m:annual_solar_wac_person=33.2
```

## Meta Commands

```ls
metric m:annual_solar_wac_person l:"Annual Solar (WAC/person)" t:dataTypeName=number

entity e:jyvh-hvkp l:"DBEDT HECO Ranks Third In 2010 Annual Solar Watts Per Customer" t:attribution="Department of Economic Development and Tourism" t:url=https://data.hawaii.gov/api/views/jyvh-hvkp

property e:jyvh-hvkp t:meta.view d:2017-03-08T00:18:01.098Z v:id=jyvh-hvkp v:category="Economic Development" v:attributionLink=http://hawaii.gov/dbedt v:averageRating=0 v:name="DBEDT HECO Ranks Third In 2010 Annual Solar Watts Per Customer" v:attribution="Department of Economic Development and Tourism"

property e:jyvh-hvkp t:meta.view.license d:2017-03-08T00:18:01.098Z v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:jyvh-hvkp t:meta.view.owner d:2017-03-08T00:18:01.098Z v:id=uaqq-pakk v:screenName="Douglas Oshiro" v:displayName="Douglas Oshiro"

property e:jyvh-hvkp t:meta.view.tableauthor d:2017-03-08T00:18:01.098Z v:id=uaqq-pakk v:screenName="Douglas Oshiro" v:displayName="Douglas Oshiro"
```