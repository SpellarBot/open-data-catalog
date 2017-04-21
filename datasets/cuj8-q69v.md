# 2015: ECAD Multi-Family Audit and EUI Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2015-ecad-multi-family-audit-and-eui-data) |
| Metadata | [Link](https://data.austintexas.gov/api/views/cuj8-q69v) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/cuj8-q69v/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/cuj8-q69v/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | cuj8-q69v |
| Name | 2015: ECAD Multi-Family Audit and EUI Data |
| Attribution | Austin Energy |
| Category | Utility |
| Tags | ecad, multifamily, audit, ordinance, building type, r-value, duct leakage, eui, 20110421-002, austin, climate protection |
| Created | 2016-02-26T17:51:13Z |
| Publication Date | 2016-02-26T18:58:17Z |

## Description

This report is the result of the Austin City Code 6-7?s Energy Conservation Audit and Disclosure Ordinance approved in November 2008 (amended in April 2011) to improve the energy efficiency of homes and buildings that receive electricity from Austin Energy.  The ordinance meets one of the goals of the Austin Climate Protection Plan, which is to offset 800 megawatts of peak energy demand by 2020. In addition, this report contains information on multi-family properties older than 10 years that are required to perform an energy audit and report the results to the City of Austin and all residents living in those communities. The Austin Energy report quantifies the 2015 energy efficiency findings and the progress towards meeting City Council goals of Resolution 20081106-048.

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                        | Data Type     | Render Type   |
| ======== | ============== | ========================== | =========================== | ============= | ============= |
| Yes      | series tag     | community_name             | Community Name              | text          | text          |
| Yes      | series tag     | tcad_or_wcad_property_id_s | TCAD or WCAD Property ID(s) | text          | text          |
| Yes      | time           | audit_date                 | Audit Date                  | calendar_date | calendar_date |
| Yes      | numeric metric | percent_duct_leakage       | Percent Duct Leakage        | percent       | percent       |
| Yes      | numeric metric | recommended_duct_leakage   | Recommended Duct Leakage    | percent       | percent       |
| Yes      | series tag     | attic_r_value              | Attic R-Value               | text          | text          |
| Yes      | series tag     | window_screens             | Window Screens              | text          | text          |
| No       |                | year_built                 | Year Built                  | number        | number        |
| Yes      | series tag     | common_laundry             | Common Laundry              | text          | text          |
| Yes      | series tag     | utilities                  | Utilities                   | text          | text          |
| Yes      | numeric metric | total_units                | Total Units                 | number        | number        |
| Yes      | numeric metric | community_eui_kwh_sqft_yr  | Community EUI (kWh/sqft/yr) | number        | number        |
| No       |                | as_of                      | As of                       | calendar_date | calendar_date |
```

## Time Field

```ls
Value = audit_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = as_of,year_built
```

## Data Commands

```ls
series e:cuj8-q69v d:2011-05-27T00:00:00.000Z t:window_screens=Complete t:community_name="Toscana Apartment Homes" t:attic_r_value=19 t:utilities=Electric t:common_laundry=Yes t:tcad_or_wcad_property_id_s=R413951 m:community_eui_kwh_sqft_yr=7.98 m:percent_duct_leakage=10.7 m:recommended_duct_leakage=15 m:total_units=358

series e:cuj8-q69v d:2010-12-28T00:00:00.000Z t:window_screens=Complete t:community_name="Broadstone Great Hills" t:attic_r_value=14 t:utilities="Gas and Electric" t:common_laundry=No t:tcad_or_wcad_property_id_s=439489 m:community_eui_kwh_sqft_yr=6.69 m:percent_duct_leakage=67 m:recommended_duct_leakage=15 m:total_units=256

series e:cuj8-q69v d:2012-05-31T00:00:00.000Z t:window_screens=Needed t:community_name="Riverlodge Apartments" t:attic_r_value=19 t:utilities=Electric t:common_laundry=Yes t:tcad_or_wcad_property_id_s=439201 m:community_eui_kwh_sqft_yr=6.78 m:percent_duct_leakage=13.7 m:recommended_duct_leakage=15 m:total_units=499
```

## Meta Commands

```ls
metric m:percent_duct_leakage p:integer l:"Percent Duct Leakage" t:dataTypeName=percent

metric m:recommended_duct_leakage p:integer l:"Recommended Duct Leakage" t:dataTypeName=percent

metric m:total_units p:integer l:"Total Units" t:dataTypeName=number

metric m:community_eui_kwh_sqft_yr p:float l:"Community EUI (kWh/sqft/yr)" t:dataTypeName=number

entity e:cuj8-q69v l:"2015: ECAD Multi-Family Audit and EUI Data" t:attribution="Austin Energy" t:url=https://data.austintexas.gov/api/views/cuj8-q69v

property e:cuj8-q69v t:meta.view v:id=cuj8-q69v v:category=Utility v:attributionLink=http://www.Austinenergy.com v:averageRating=0 v:name="2015: ECAD Multi-Family Audit and EUI Data" v:attribution="Austin Energy"

property e:cuj8-q69v t:meta.view.license v:name="Public Domain"

property e:cuj8-q69v t:meta.view.owner v:id=fqy8-r3v8 v:screenName="Michael McCarthy" v:displayName="Michael McCarthy"

property e:cuj8-q69v t:meta.view.tableauthor v:id=fqy8-r3v8 v:screenName="Michael McCarthy" v:roleName=editor v:displayName="Michael McCarthy"
```

## Top Records

```ls
| community_name                  | tcad_or_wcad_property_id_s | audit_date          | percent_duct_leakage | recommended_duct_leakage | attic_r_value | window_screens | year_built | common_laundry | utilities        | total_units | community_eui_kwh_sqft_yr | as_of               | 
| =============================== | ========================== | =================== | ==================== | ======================== | ============= | ============== | ========== | ============== | ================ | =========== | ========================= | =================== | 
| Toscana Apartment Homes         | R413951                    | 2011-05-27T00:00:00 | 10.7                 | 15                       | 19            | Complete       | 2001       | Yes            | Electric         | 358         | 7.98                      | 2016-02-26T00:00:00 | 
| Broadstone Great Hills          | 439489                     | 2010-12-28T00:00:00 | 67                   | 15                       | 14            | Complete       | 1998       | No             | Gas and Electric | 256         | 6.69                      | 2016-02-26T00:00:00 | 
| Riverlodge Apartments           | 439201                     | 2012-05-31T00:00:00 | 13.7                 | 15                       | 19            | Needed         | 2000       | Yes            | Electric         | 499         | 6.78                      | 2016-02-26T00:00:00 | 
| Hardrock Canyon                 | 375767                     | 2011-04-07T00:00:00 | 72                   | 10                       | 17            | Complete       | 1995       | Yes            | Gas and Electric | 145         | 7.79                      | 2016-02-26T00:00:00 | 
| Windwood Apartments             | 308166                     | 2011-01-24T00:00:00 | 59                   | 15                       | 24            | Needed         | 1985       | Yes            | Electric         | 32          | 14.56                     | 2016-02-26T00:00:00 | 
| Settler's Creek                 | 306469                     | 2011-06-21T00:00:00 | 56                   | 10                       | 10            | Needed         | 1987       | No             | Electric         | 75          | 11.98                     | 2016-02-26T00:00:00 | 
| Connection                      | 290469                     | 2010-12-16T00:00:00 | 18                   | 10                       | 26            | Needed         | 2000       | No             | Electric         | 192         | 13.23                     | 2016-02-26T00:00:00 | 
| Forest Creek Village Apartments | 289705                     | 2011-06-14T00:00:00 | 63                   | 10                       | N\A           | Needed         | 1969       | Yes            | Electric         | 166         | 8.37                      | 2016-02-26T00:00:00 | 
| South Cliff Apartments          | 285896                     | 2011-02-17T00:00:00 | 22                   | 10                       | N\A           | Needed         | 1980       | Yes            | Electric         | 60          | 10.43                     | 2016-02-26T00:00:00 | 
| The Brook in Travis Heights     | 284601                     | 2011-06-13T00:00:00 | 71                   | 10                       | N\A           | Needed         | 1972       | Yes            | Electric         | 175         | 8.65                      | 2016-02-26T00:00:00 | 
```