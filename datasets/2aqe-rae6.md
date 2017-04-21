# Seattle Center Utility Use Details 2013 - 2015

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/seattle-center-utility-use-details-2013-2105) |
| Metadata | [Link](https://data.seattle.gov/api/views/2aqe-rae6) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/2aqe-rae6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/2aqe-rae6/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | 2aqe-rae6 |
| Name | Seattle Center Utility Use Details 2013 - 2015 |
| Attribution | Seattle Center |
| Category | City Business |
| Tags | seattle center, utility, keyarena, mccaw hall, armory |
| Created | 2017-02-01T21:48:54Z |
| Publication Date | 2017-02-01T21:51:33Z |

## Description

This dataset provides total monthly utility consumption off all non-tenant occupied facilities at Seattle Center. This includes KeyArena, McCaw Hall, Armory, Campus Grounds, Garages, and other small facilities.

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                     | Data Type     | Render Type   |
| ======== | ============== | ====================== | ======================== | ============= | ============= |
| Yes      | time           | month                  | Month                    | calendar_date | calendar_date |
| Yes      | numeric metric | electricity_kwh        | Electricity (kWh)        | number        | number        |
| Yes      | numeric metric | natural_gas_therms     | Natural Gas (Therms)     | number        | number        |
| Yes      | numeric metric | other_fuels_mbtu       | Other Fuels (MBtu)       | number        | number        |
| Yes      | numeric metric | total_fossil_fuel_mbtu | Total Fossil Fuel (MBtu) | number        | number        |
| Yes      | numeric metric | fuel_percent_change    | Fuel Percent Change      | percent       | percent       |
| Yes      | numeric metric | total_energy_mbtu      | Total Energy (MBtu)      | number        | number        |
| Yes      | numeric metric | energy_percent_change  | Energy Percent Change    | percent       | percent       |
| Yes      | numeric metric | water_ccf              | Water (ccf)              | number        | number        |
| Yes      | numeric metric | sewer_ccf              | Sewer (ccf)              | number        | number        |
| Yes      | numeric metric | refuse_cu_yds          | Refuse (Cu Yds)          | number        | number        |
```

## Time Field

```ls
Value = month
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:2aqe-rae6 d:2013-01-01T00:00:00.000Z m:other_fuels_mbtu=3831 m:energy_percent_change=-2.7 m:water_ccf=1578 m:electricity_kwh=1466412 m:natural_gas_therms=64152 m:total_fossil_fuel_mbtu=10246 m:sewer_ccf=1561 m:refuse_cu_yds=63 m:total_energy_mbtu=15250 m:fuel_percent_change=-6.1

series e:2aqe-rae6 d:2013-02-01T00:00:00.000Z m:other_fuels_mbtu=2624 m:energy_percent_change=-10.9 m:water_ccf=1256 m:electricity_kwh=1292195 m:natural_gas_therms=47279 m:total_fossil_fuel_mbtu=7352 m:sewer_ccf=1240 m:refuse_cu_yds=59 m:total_energy_mbtu=11761 m:fuel_percent_change=-16.4

series e:2aqe-rae6 d:2013-03-01T00:00:00.000Z m:other_fuels_mbtu=2744 m:energy_percent_change=3.5 m:water_ccf=1339 m:electricity_kwh=1445693 m:natural_gas_therms=57402 m:total_fossil_fuel_mbtu=8484 m:sewer_ccf=1302 m:refuse_cu_yds=67 m:total_energy_mbtu=13416 m:fuel_percent_change=3.5
```

## Meta Commands

```ls
metric m:electricity_kwh p:integer l:"Electricity (kWh)" t:dataTypeName=number

metric m:natural_gas_therms p:integer l:"Natural Gas (Therms)" t:dataTypeName=number

metric m:other_fuels_mbtu p:integer l:"Other Fuels (MBtu)" t:dataTypeName=number

metric m:total_fossil_fuel_mbtu p:integer l:"Total Fossil Fuel (MBtu)" t:dataTypeName=number

metric m:fuel_percent_change p:float l:"Fuel Percent Change" t:dataTypeName=percent

metric m:total_energy_mbtu p:integer l:"Total Energy (MBtu)" t:dataTypeName=number

metric m:energy_percent_change p:float l:"Energy Percent Change" t:dataTypeName=percent

metric m:water_ccf p:integer l:"Water (ccf)" t:dataTypeName=number

metric m:sewer_ccf p:integer l:"Sewer (ccf)" t:dataTypeName=number

metric m:refuse_cu_yds p:integer l:"Refuse (Cu Yds)" t:dataTypeName=number

entity e:2aqe-rae6 l:"Seattle Center Utility Use Details 2013 - 2015" t:attribution="Seattle Center" t:url=https://data.seattle.gov/api/views/2aqe-rae6

property e:2aqe-rae6 t:meta.view v:id=2aqe-rae6 v:category="City Business" v:attributionLink=http://www.seattlecenter.com v:averageRating=0 v:name="Seattle Center Utility Use Details 2013 - 2015" v:attribution="Seattle Center"

property e:2aqe-rae6 t:meta.view.license v:name="Public Domain"

property e:2aqe-rae6 t:meta.view.owner v:id=wy9h-7767 v:screenName="Wells, Denise" v:displayName="Wells, Denise"

property e:2aqe-rae6 t:meta.view.tableauthor v:id=wy9h-7767 v:screenName="Wells, Denise" v:roleName=publisher v:displayName="Wells, Denise"
```

## Top Records

```ls
| month               | electricity_kwh | natural_gas_therms | other_fuels_mbtu | total_fossil_fuel_mbtu | fuel_percent_change | total_energy_mbtu | energy_percent_change | water_ccf | sewer_ccf | refuse_cu_yds | 
| =================== | =============== | ================== | ================ | ====================== | =================== | ================= | ===================== | ========= | ========= | ============= | 
| 2013-01-01T00:00:00 | 1466412         | 64152              | 3831             | 10246                  | -6.10               | 15250             | -2.70                 | 1578      | 1561      | 63            | 
| 2013-02-01T00:00:00 | 1292195         | 47279              | 2624             | 7352                   | -16.40              | 11761             | -10.90                | 1256      | 1240      | 59            | 
| 2013-03-01T00:00:00 | 1445693         | 57402              | 2744             | 8484                   | 3.50                | 13416             | 3.50                  | 1339      | 1302      | 67            | 
| 2013-04-01T00:00:00 | 1341944         | 42723              | 2303             | 6575                   | 29.70               | 11154             | 16.30                 | 1019      | 961       | 35            | 
| 2013-05-01T00:00:00 | 1317986         | 26592              | 2232             | 4891                   | -9.10               | 9388              | -6.40                 | 2176      | 1610      | 104           | 
| 2013-06-01T00:00:00 | 1308943         | 20963              | 3090             | 5187                   | 22.80               | 9653              | 10.60                 | 3643      | 2582      | 58            | 
| 2013-07-01T00:00:00 | 1444089         | 19297              | 5099             | 7029                   | 12.70               | 11956             | 8.80                  | 4713      | 3513      | 100           | 
| 2013-08-01T00:00:00 | 1511683         | 18751              | 7717             | 9592                   | 52.60               | 14750             | 29.60                 | 4789      | 3572      | 66            | 
| 2013-09-01T00:00:00 | 1379183         | 20593              | 2953             | 5012                   | 20.10               | 9718              | 7.30                  | 3105      | 2418      | 70            | 
| 2013-10-01T00:00:00 | 1337244         | 35325              | 1891             | 5423                   | -0.10               | 9986              | -1.50                 | 2034      | 1902      | 75            | 
```