# 2013: ECAD Multi-Family Energy Audit and EUI Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2013-ecad-multi-family-energy-audit-and-eui-data) |
| Metadata | [Link](https://data.austintexas.gov/api/views/askx-pbnh) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/askx-pbnh/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/askx-pbnh/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | askx-pbnh |
| Name | 2013: ECAD Multi-Family Energy Audit and EUI Data |
| Attribution | Austin Energy |
| Category | Utility |
| Tags | ecad, multi-family, multifamily, audit, ordinance, duct leakage, attic insulation, eui, 20110421-002, austin |
| Created | 2014-03-14T18:16:28Z |
| Publication Date | 2014-03-14T18:21:33Z |

## Description

The following information will allow you to understand the intent of data provided.  This report is in conjunction with Austin City Code 6-7?s Energy Conservation Audit and Disclosure Ordinance approved in November 2008 (amended in April 2011) to improve the energy efficiency of homes and buildings that receive electricity from Austin Energy. The ordinance meets one of the primary goals of the Austin Climate Protection Plan which is to offset 800 megawatts of peak energy demand by 2020 to help reduce Austin's carbon footprint.  In addition, this report contains information on multi-family properties older than 10 years that are required to perform an energy audit and report the results to the City of Austin and all residents living in those communities. The Austin Energy report quantifies the 2013 energy efficiency findings and the progress towards meeting City Council goals of Resolution 20081106-048.

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                        | Data Type     | Render Type   |
| ======== | ============== | ========================== | =========================== | ============= | ============= |
| Yes      | series tag     | community_name             | Community Name              | text          | text          |
| Yes      | series tag     | tcad_or_wcad_property_id_s | TCAD or WCAD Property ID(s) | text          | text          |
| Yes      | time           | audit_date                 | Audit Date                  | calendar_date | calendar_date |
| Yes      | numeric metric | percent_duct_leakage       | Percent Duct Leakage        | number        | number        |
| Yes      | series tag     | recommend_duct_leakage     | Recommend Duct Leakage      | text          | text          |
| Yes      | numeric metric | attic_r_value              | Attic R-Value               | number        | number        |
| Yes      | series tag     | window_screens             | Window Screens              | text          | text          |
| No       |                | year_built                 | Year Built                  | number        | number        |
| Yes      | series tag     | common_wash_dryer          | Common Wash Dryer           | text          | text          |
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
series e:askx-pbnh d:2011-02-22T00:00:00.000Z t:window_screens=Needed t:common_wash_dryer=Yes t:recommend_duct_leakage=10% t:community_name="Diplomat Apartments" t:utilities="Gas and Electric" t:tcad_or_wcad_property_id_s=203752 m:community_eui_kwh_sqft_yr=7.66 m:attic_r_value=22 m:percent_duct_leakage=29 m:total_units=13

series e:askx-pbnh d:2011-04-08T00:00:00.000Z t:window_screens=Needed t:common_wash_dryer=Yes t:recommend_duct_leakage=10% t:community_name="New Yorker" t:utilities=Electric t:tcad_or_wcad_property_id_s=312543 m:community_eui_kwh_sqft_yr=13.58 m:attic_r_value=9 m:percent_duct_leakage=22 m:total_units=28

series e:askx-pbnh d:2011-06-14T00:00:00.000Z t:window_screens=Needed t:common_wash_dryer=Yes t:recommend_duct_leakage=10% t:community_name="Landry Place" t:utilities=Electric t:tcad_or_wcad_property_id_s=287935 m:community_eui_kwh_sqft_yr=10.78 m:attic_r_value=19 m:percent_duct_leakage=19 m:total_units=284
```

## Meta Commands

```ls
metric m:percent_duct_leakage p:integer l:"Percent Duct Leakage" t:dataTypeName=number

metric m:attic_r_value p:integer l:"Attic R-Value" t:dataTypeName=number

metric m:total_units p:integer l:"Total Units" t:dataTypeName=number

metric m:community_eui_kwh_sqft_yr p:float l:"Community EUI (kWh/sqft/yr)" t:dataTypeName=number

entity e:askx-pbnh l:"2013: ECAD Multi-Family Energy Audit and EUI Data" t:attribution="Austin Energy" t:url=https://data.austintexas.gov/api/views/askx-pbnh

property e:askx-pbnh t:meta.view v:id=askx-pbnh v:category=Utility v:attributionLink=http://austinenergy.com v:averageRating=0 v:name="2013: ECAD Multi-Family Energy Audit and EUI Data" v:attribution="Austin Energy"

property e:askx-pbnh t:meta.view.license v:name="Public Domain"

property e:askx-pbnh t:meta.view.owner v:id=fqy8-r3v8 v:screenName="Michael McCarthy" v:displayName="Michael McCarthy"

property e:askx-pbnh t:meta.view.tableauthor v:id=fqy8-r3v8 v:screenName="Michael McCarthy" v:roleName=editor v:displayName="Michael McCarthy"
```

## Top Records

```ls
| community_name                  | tcad_or_wcad_property_id_s | audit_date          | percent_duct_leakage | recommend_duct_leakage | attic_r_value | window_screens | year_built | common_wash_dryer | utilities        | total_units | community_eui_kwh_sqft_yr | as_of               | 
| =============================== | ========================== | =================== | ==================== | ====================== | ============= | ============== | ========== | ================= | ================ | =========== | ========================= | =================== | 
| Diplomat Apartments             | 203752                     | 2011-02-22T00:00:00 | 29                   | 10%                    | 22            | Needed         | 1964       | Yes               | Gas and Electric | 13          | 7.66                      | 2014-02-10T00:00:00 | 
| New Yorker                      | 312543                     | 2011-04-08T00:00:00 | 22                   | 10%                    | 9             | Needed         | 1983       | Yes               | Electric         | 28          | 13.58                     | 2014-02-10T00:00:00 | 
| Landry Place                    | 287935                     | 2011-06-14T00:00:00 | 19                   | 10%                    | 19            | Needed         | 1987       | Yes               | Electric         | 284         | 10.78                     | 2014-02-10T00:00:00 | 
| Mark Embers                     | 210208, 210209, 210207     | 2011-01-06T00:00:00 | 46                   | 10%                    |               | Needed         | 1964       | No                | Gas and Electric | 38          | 8.59                      | 2014-02-10T00:00:00 | 
| Park Plaza Apartments           | 211811                     | 2011-01-24T00:00:00 | 22                   | 10%                    | 7             | Needed         | 1980       | Yes               | Electric         | 30          | 9.42                      | 2014-02-10T00:00:00 | 
| 24 Flats                        | 109020                     | 2011-01-07T00:00:00 | 70                   | 15%                    |               | Needed         | 1972       | Yes               | Electric         | 24          | 8.45                      | 2014-02-10T00:00:00 | 
| 505 West 18th Street Apartments | 199772                     | 2011-04-27T00:00:00 | 19                   | 10%                    |               | Needed         | 1983       | Yes               | Electric         | 10          | 9.98                      | 2014-02-10T00:00:00 | 
| Spring Hollow                   | 217295, 219437             | 2011-04-01T00:00:00 | 12                   | 10%                    | 11            | Needed         | 1985       | Yes               | Electric         | 96          | 18.4                      | 2014-02-10T00:00:00 | 
|                                 | 114187                     | 2012-11-16T00:00:00 | 28.4                 | 10%                    | 22.4          | Needed         | 1948       | Yes               | Gas and Electric | 6           | 6.38                      | 2014-02-10T00:00:00 | 
| GATEWAYS                        | 250294                     | 2011-04-19T00:00:00 | 9                    | 10%                    | 11            | Needed         | 1980       | Yes               | Electric         | 118         | 14.23                     | 2014-02-10T00:00:00 | 
```