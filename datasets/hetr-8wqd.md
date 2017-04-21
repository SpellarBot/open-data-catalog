# Carbon Intensity

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/carbon-intensity) |
| Metadata | [Link](https://data.austintexas.gov/api/views/hetr-8wqd) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/hetr-8wqd/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/hetr-8wqd/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | hetr-8wqd |
| Name | Carbon Intensity |
| Attribution | Austin Energy |
| Category | Utility |
| Tags | carbon, carbon intensity, carbon dioxide, emissions |
| Created | 2015-08-04T21:45:35Z |
| Publication Date | 2016-05-12T19:20:34Z |

## Description

The Austin Energy system average carbon intensity is calculated as total greenhouse gas emissions at the point of combustion in pounds of CO2-equivalents divided by net generation in kWh from all Austin Energy resources. Generation resources include natural gas, coal and nuclear-powered units owned by Austin Energy, renewable resources owned by Austin Energy and all purchased power from renewable and non-renewable resources. Sales of GreenChoice? energy are subtracted from the net generation total since GreenChoice? customers can claim their carbon intensity to be 0 lbs of CO2-equivalents/kWh. Carbon dioxide equivalent is a measure used to compare the emissions of different greenhouse gases based on their global warming potential (GWP). Austin Energy?s system average carbon intensity is shown in pounds of CO2-eq/kWh per calendar year.

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                 | Data Type | Render Type |
| ======== | ============== | ==================== | ==================== | ========= | =========== |
| Yes      | numeric metric | pounds_of_co2_eq_kwh | pounds of CO2-eq/kWh | number    | number      |
| Yes      | time           | calendar_year        | calendar year        | number    | number      |
```

## Time Field

```ls
Value = calendar_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:hetr-8wqd d:2005-01-01T00:00:00.000Z m:pounds_of_co2_eq_kwh=1.17

series e:hetr-8wqd d:2006-01-01T00:00:00.000Z m:pounds_of_co2_eq_kwh=1.14

series e:hetr-8wqd d:2007-01-01T00:00:00.000Z m:pounds_of_co2_eq_kwh=1.18
```

## Meta Commands

```ls
metric m:pounds_of_co2_eq_kwh p:float l:"pounds of CO2-eq/kWh" t:dataTypeName=number

entity e:hetr-8wqd l:"Carbon Intensity" t:attribution="Austin Energy" t:url=https://data.austintexas.gov/api/views/hetr-8wqd

property e:hetr-8wqd t:meta.view v:id=hetr-8wqd v:category=Utility v:averageRating=0 v:name="Carbon Intensity" v:attribution="Austin Energy"

property e:hetr-8wqd t:meta.view.license v:name="Public Domain"

property e:hetr-8wqd t:meta.view.owner v:id=fxfz-wsmq v:profileImageUrlMedium=/api/users/fxfz-wsmq/profile_images/THUMB v:profileImageUrlLarge=/api/users/fxfz-wsmq/profile_images/LARGE v:screenName="Shannon Wisner" v:profileImageUrlSmall=/api/users/fxfz-wsmq/profile_images/TINY v:displayName="Shannon Wisner"

property e:hetr-8wqd t:meta.view.tableauthor v:id=fxfz-wsmq v:profileImageUrlMedium=/api/users/fxfz-wsmq/profile_images/THUMB v:profileImageUrlLarge=/api/users/fxfz-wsmq/profile_images/LARGE v:screenName="Shannon Wisner" v:profileImageUrlSmall=/api/users/fxfz-wsmq/profile_images/TINY v:roleName=publisher v:displayName="Shannon Wisner"
```

## Top Records

```ls
| pounds_of_co2_eq_kwh | calendar_year | 
| ==================== | ============= | 
| 1.17                 | 2005          | 
| 1.14                 | 2006          | 
| 1.18                 | 2007          | 
| 1.16                 | 2008          | 
| 1.1                  | 2009          | 
| 1.1                  | 2010          | 
| 1.18                 | 2011          | 
| 1.03                 | 2012          | 
| 1.05                 | 2013          | 
| 0.87                 | 2015          | 
```