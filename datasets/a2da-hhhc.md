# 2014: ECAD Commercial Reported Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2014-ecad-commercial-reported-data) |
| Metadata | [Link](https://data.austintexas.gov/api/views/a2da-hhhc) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/a2da-hhhc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/a2da-hhhc/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | a2da-hhhc |
| Name | 2014: ECAD Commercial Reported Data |
| Attribution | Austin Energy |
| Category | Utility |
| Tags | ecad, commercial, audit, ordinance, building type, score, energy star score, eui, 20110421-002, austin, climate protection |
| Created | 2015-10-07T20:42:08Z |
| Publication Date | 2015-10-08T20:44:04Z |

## Description

This report is the result of the Austin City Code 6-7?s Energy Conservation Audit and Disclosure Ordinance approved in November 2008 (amended in April 2011) to improve the energy efficiency of homes and buildings that receive electricity from Austin Energy.  The ordinance meets one of the goals of the Austin Climate Protection Plan, which is to offset 800 megawatts of peak energy demand by 2020. This report contains information on commercial facilities that have reported the EPA?s Energy Star? Portfolio Manager benchmarking results in 2014 (*) to the City of Austin, as well as the calculated electric Energy Utilization Index (EUI). For information on ECAD exemptions and other requirements, see Austin City Code Chapter 6-7.  Note ? (*) Data reported by Commercial Customers

## Columns

```ls
| Included | Schema Type    | Field Name                          | Name                                | Data Type     | Render Type   |
| ======== | ============== | =================================== | =================================== | ============= | ============= |
| Yes      | series tag     | tcad_or_wcad_property_id_s          | TCAD or WCAD Property ID(s)         | html          | html          |
| Yes      | series tag     | facility_category                   | Facility Category                   | html          | html          |
| Yes      | series tag     | building_name                       | Building Name                       | html          | html          |
| Yes      | numeric metric | calculated_kwh_sqft                 | Calculated kWh/sqft                 | number        | number        |
| Yes      | numeric metric | portfolio_manager_energy_star_score | Portfolio Manager Energy Star Score | number        | number        |
| Yes      | time           | as_of                               | As of                               | calendar_date | calendar_date |
```

## Time Field

```ls
Value = as_of
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:a2da-hhhc d:2015-10-01T00:00:00.000Z t:building_name=101422_001 t:facility_category="RETAIL CENTER" t:tcad_or_wcad_property_id_s=101422 m:portfolio_manager_energy_star_score=81 m:calculated_kwh_sqft=10.002

series e:a2da-hhhc d:2015-10-01T00:00:00.000Z t:building_name=101496_001 t:facility_category=WAREHOUSE t:tcad_or_wcad_property_id_s=101496 m:calculated_kwh_sqft=0.157

series e:a2da-hhhc d:2015-10-01T00:00:00.000Z t:building_name=102904_Campus t:facility_category="OFFICE LG &gt; 35000 (W/sqft &gt; 5)" t:tcad_or_wcad_property_id_s=102904 m:calculated_kwh_sqft=18.394
```

## Meta Commands

```ls
metric m:calculated_kwh_sqft p:float l:"Calculated kWh/sqft" t:dataTypeName=number

metric m:portfolio_manager_energy_star_score p:double l:"Portfolio Manager Energy Star Score" t:dataTypeName=number

entity e:a2da-hhhc l:"2014: ECAD Commercial Reported Data" t:attribution="Austin Energy" t:url=https://data.austintexas.gov/api/views/a2da-hhhc

property e:a2da-hhhc t:meta.view v:id=a2da-hhhc v:category=Utility v:attributionLink=http://www.Austinenergy.com v:averageRating=0 v:name="2014: ECAD Commercial Reported Data" v:attribution="Austin Energy"

property e:a2da-hhhc t:meta.view.license v:name="Public Domain"

property e:a2da-hhhc t:meta.view.owner v:id=fqy8-r3v8 v:screenName="Michael McCarthy" v:displayName="Michael McCarthy"

property e:a2da-hhhc t:meta.view.tableauthor v:id=fqy8-r3v8 v:screenName="Michael McCarthy" v:roleName=editor v:displayName="Michael McCarthy"
```

## Top Records

```ls
| tcad_or_wcad_property_id_s | facility_category              | building_name | calculated_kwh_sqft | portfolio_manager_energy_star_score | as_of               | 
| ========================== | ============================== | ============= | =================== | =================================== | =================== | 
| 101422                     | RETAIL CENTER                  | 101422_001    | 10.002              | 81                                  | 2015-10-01T00:00:00 | 
| 101496                     | WAREHOUSE                      | 101496_001    | 0.157               |                                     | 2015-10-01T00:00:00 | 
| 102904                     | OFFICE LG > 35000 (W/sqft > 5) | 102904_Campus | 18.394              |                                     | 2015-10-01T00:00:00 | 
| 104321                     | RETAIL CENTER                  | 104321_001    | 12.289              | 83.5                                | 2015-10-01T00:00:00 | 
| 104322                     | OTHER                          | 104322_001    | 9.659               | 74                                  | 2015-10-01T00:00:00 | 
| 105806                     | RETAIL CENTER                  | 105806_005    | 25.067              |                                     | 2015-10-01T00:00:00 | 
| 105806                     | RETAIL CENTER                  | 105806_004    | 25.067              |                                     | 2015-10-01T00:00:00 | 
| 105806                     | RETAIL CENTER                  | 105806_003    | 25.067              |                                     | 2015-10-01T00:00:00 | 
| 105806                     | RETAIL CENTER                  | 105806_002    | 25.067              |                                     | 2015-10-01T00:00:00 | 
| 107726                     | OFFICE MED 10-35               | 107726_Campus | 30.131              |                                     | 2015-10-01T00:00:00 | 
```