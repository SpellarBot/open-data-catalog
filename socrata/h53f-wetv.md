# Table 9: Percentage of Population served Safe Drinking Water

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/table-9-percentage-of-population-served-safe-drinking-water-daba6) |
| Metadata | [Link](https://data.hawaii.gov/api/views/h53f-wetv) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/h53f-wetv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/h53f-wetv/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | h53f-wetv |
| Name | Table 9: Percentage of Population served Safe Drinking Water |
| Attribution | DOH |
| Category | Health |
| Tags | percentage, population, safe, drinking, water |
| Created | 2012-07-31T23:50:33Z |
| Publication Date | 2012-07-31T23:51:19Z |

## Description

DOH Environmental Indicators

## Columns

```ls
| Included | Schema Type    | Field Name                                                  | Name                                                         | Data Type | Render Type |
| ======== | ============== | =========================================================== | ============================================================ | ========= | =========== |
| No       | time           | :updated_at                                                 | updated_at                                                   | meta_data | meta_data   |
| No       |                | _                                                           | #                                                            | number    | number      |
| Yes      | numeric metric | calendar_year_fy                                            | Calendar Year/FY                                             | number    | text        |
| Yes      | numeric metric | total_population_served_drinking_water                      | Total Population Served Drinking Water                       | number    | number      |
| Yes      | numeric metric | population_served_water_below_mcl_s                         | Population Served Water Below MCL*s                          | number    | number      |
| Yes      | numeric metric | percentage_population_served_water_in_compliance_with_mcl_s | Percentage Population Served Water in Compliance with MCL**s | percent   | percent     |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = _
```

## Data Commands

```ls
series e:h53f-wetv d:2012-07-31T16:50:34.000Z m:total_population_served_drinking_water=1341430 m:population_served_water_below_mcl_s=1335929 m:percentage_population_served_water_in_compliance_with_mcl_s=99.59 m:calendar_year_fy=2006

series e:h53f-wetv d:2012-07-31T16:50:34.000Z m:total_population_served_drinking_water=1341430 m:population_served_water_below_mcl_s=1329748 m:percentage_population_served_water_in_compliance_with_mcl_s=99.13 m:calendar_year_fy=2007

series e:h53f-wetv d:2012-07-31T16:50:34.000Z m:total_population_served_drinking_water=1416384 m:population_served_water_below_mcl_s=1411729 m:percentage_population_served_water_in_compliance_with_mcl_s=99.67 m:calendar_year_fy=2008
```

## Meta Commands

```ls
metric m:calendar_year_fy p:integer l:"Calendar Year/FY" t:dataTypeName=number

metric m:total_population_served_drinking_water p:integer l:"Total Population Served Drinking Water" t:dataTypeName=number

metric m:population_served_water_below_mcl_s p:integer l:"Population Served Water Below MCL*s" t:dataTypeName=number

metric m:percentage_population_served_water_in_compliance_with_mcl_s p:float l:"Percentage Population Served Water in Compliance with MCL**s" t:dataTypeName=percent

entity e:h53f-wetv l:"Table 9: Percentage of Population served Safe Drinking Water" t:attribution=DOH t:url=https://data.hawaii.gov/api/views/h53f-wetv

property e:h53f-wetv t:meta.view v:id=h53f-wetv v:category=Health v:attributionLink=http://hawaii.gov/doh v:averageRating=0 v:name="Table 9: Percentage of Population served Safe Drinking Water" v:attribution=DOH

property e:h53f-wetv t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:h53f-wetv t:meta.view.owner v:id=8c9u-vteh v:screenName=lorrink v:displayName=lorrink

property e:h53f-wetv t:meta.view.tableauthor v:id=8c9u-vteh v:screenName=lorrink v:roleName=editor v:displayName=lorrink
```

## Top Records

```ls
| :updated_at | _ | calendar_year_fy | total_population_served_drinking_water | population_served_water_below_mcl_s | percentage_population_served_water_in_compliance_with_mcl_s | 
| =========== | = | ================ | ====================================== | =================================== | =========================================================== | 
| 1343753434  | 1 | 2006             | 1341430                                | 1335929                             | 99.59                                                       | 
| 1343753434  | 2 | 2007             | 1341430                                | 1329748                             | 99.13                                                       | 
| 1343753434  | 4 | 2008             | 1416384                                | 1411729                             | 99.67                                                       | 
| 1343753434  | 5 | 2009             | 1440715                                | 1432116                             | 99.40                                                       | 
| 1343753434  | 6 | 2010             | 1471887                                | 1470664                             | 99.92                                                       | 
```