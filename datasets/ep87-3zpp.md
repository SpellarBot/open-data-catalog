# Energy Efficiency Program Expenditures

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/energy-efficiency-program-expenditures) |
| Metadata | [Link](https://data.austintexas.gov/api/views/ep87-3zpp) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/ep87-3zpp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/ep87-3zpp/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | ep87-3zpp |
| Name | Energy Efficiency Program Expenditures |
| Attribution | Austin Energy |
| Category | Utility |
| Tags | austin energy, rebate, interest rate, loans, energy efficiency, energy |
| Created | 2016-12-05T19:15:44Z |
| Publication Date | 2016-12-05T20:03:47Z |

## Description

Austin Energy funds dozens of programs to help customers pay for energy efficiency improvements. View the amount of program funds disbursed by year.

## Columns

```ls
| Included | Schema Type    | Field Name                      | Name                            | Data Type | Render Type |
| ======== | ============== | =============================== | =============================== | ========= | =========== |
| No       | time           | :updated_at                     | updated_at                      | meta_data | meta_data   |
| Yes      | series tag     | electric_rebates_and_incentives | Electric Rebates and Incentives | text      | text        |
| Yes      | numeric metric | fy_2006                         | FY 2006                         | money     | money       |
| Yes      | numeric metric | fy_2007                         | FY 2007                         | money     | money       |
| Yes      | numeric metric | fy_2008                         | FY 2008                         | money     | money       |
| Yes      | numeric metric | fy_2009                         | FY 2009                         | money     | money       |
| Yes      | numeric metric | fy_2010                         | FY 2010                         | money     | money       |
| Yes      | numeric metric | fy_2011                         | FY 2011                         | money     | money       |
| Yes      | numeric metric | fy_2012                         | FY 2012                         | money     | money       |
| Yes      | numeric metric | fy_2013                         | FY 2013                         | money     | money       |
| Yes      | numeric metric | fy_2014                         | FY 2014                         | money     | money       |
| Yes      | numeric metric | fy_2015                         | FY 2015                         | money     | money       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:ep87-3zpp d:2016-12-05T19:15:45.000Z t:electric_rebates_and_incentives="Free Weatherization" m:fy_2014=509566 m:fy_2013=999677 m:fy_2015=496998 m:fy_2010=513909 m:fy_2012=598003 m:fy_2011=6291 m:fy_2008=757545 m:fy_2009=752132 m:fy_2006=797134 m:fy_2007=175304

series e:ep87-3zpp d:2016-12-05T19:15:45.000Z t:electric_rebates_and_incentives="Multi-family Rebates" m:fy_2014=2507220 m:fy_2013=2524498 m:fy_2015=2612788 m:fy_2010=2098407 m:fy_2012=2734740 m:fy_2011=1784498 m:fy_2008=1461516 m:fy_2009=1143984 m:fy_2006=291108 m:fy_2007=629560

series e:ep87-3zpp d:2016-12-05T19:15:45.000Z t:electric_rebates_and_incentives="Loan Options" m:fy_2014=351576 m:fy_2013=6024 m:fy_2015=25724 m:fy_2010=86029 m:fy_2012=24137 m:fy_2011=34867 m:fy_2008=233380 m:fy_2009=228712 m:fy_2006=299224 m:fy_2007=277523
```

## Meta Commands

```ls
metric m:fy_2006 p:integer l:"FY 2006" t:dataTypeName=money

metric m:fy_2007 p:integer l:"FY 2007" t:dataTypeName=money

metric m:fy_2008 p:integer l:"FY 2008" t:dataTypeName=money

metric m:fy_2009 p:integer l:"FY 2009" t:dataTypeName=money

metric m:fy_2010 p:integer l:"FY 2010" t:dataTypeName=money

metric m:fy_2011 p:integer l:"FY 2011" t:dataTypeName=money

metric m:fy_2012 p:integer l:"FY 2012" t:dataTypeName=money

metric m:fy_2013 p:integer l:"FY 2013" t:dataTypeName=money

metric m:fy_2014 p:integer l:"FY 2014" t:dataTypeName=money

metric m:fy_2015 p:integer l:"FY 2015" t:dataTypeName=money

entity e:ep87-3zpp l:"Energy Efficiency Program Expenditures" t:attribution="Austin Energy" t:url=https://data.austintexas.gov/api/views/ep87-3zpp

property e:ep87-3zpp t:meta.view v:id=ep87-3zpp v:category=Utility v:averageRating=0 v:name="Energy Efficiency Program Expenditures" v:attribution="Austin Energy"

property e:ep87-3zpp t:meta.view.license v:name="Public Domain"

property e:ep87-3zpp t:meta.view.owner v:id=c433-zrb5 v:profileImageUrlMedium=/api/users/c433-zrb5/profile_images/THUMB v:profileImageUrlLarge=/api/users/c433-zrb5/profile_images/LARGE v:screenName="Sarah Lambert" v:profileImageUrlSmall=/api/users/c433-zrb5/profile_images/TINY v:displayName="Sarah Lambert"

property e:ep87-3zpp t:meta.view.tableauthor v:id=c433-zrb5 v:profileImageUrlMedium=/api/users/c433-zrb5/profile_images/THUMB v:profileImageUrlLarge=/api/users/c433-zrb5/profile_images/LARGE v:screenName="Sarah Lambert" v:profileImageUrlSmall=/api/users/c433-zrb5/profile_images/TINY v:roleName=publisher v:displayName="Sarah Lambert"
```

## Top Records

```ls
| :updated_at | electric_rebates_and_incentives   | fy_2006 | fy_2007 | fy_2008 | fy_2009 | fy_2010 | fy_2011 | fy_2012 | fy_2013 | fy_2014 | fy_2015 | 
| =========== | ================================= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | 
| 1480965345  | Free Weatherization               | 797134  | 175304  | 757545  | 752132  | 513909  | 6291    | 598003  | 999677  | 509566  | 496998  | 
| 1480965345  | Multi-family Rebates              | 291108  | 629560  | 1461516 | 1143984 | 2098407 | 1784498 | 2734740 | 2524498 | 2507220 | 2612788 | 
| 1480965345  | Loan Options                      | 299224  | 277523  | 233380  | 228712  | 86029   | 34867   | 24137   | 6024    | 351576  | 25724   | 
| 1480965345  | Home Performance w/ Energy Star   | 0       | 0       | 0       | 0       | 0       | 0       | 2140221 | 3163541 | 2754305 | 1755138 | 
| 1480965345  | Rebate Options                    | 2640260 | 2293274 | 3201580 | 4056167 | 5469084 | 5300279 | 41595   | -8450   | 0       | 0       | 
| 1480965345  | Clothes Washer Rebates            | 27250   | 44100   | 50495   | 50000   | 56600   | 30700   | 20750   | 15750   | 1100    | 0       | 
| 1480965345  | Duct Diagnostic/Sealing Rebates   | 197543  | 166103  | 80654   | 56918   | 37490   | 10205   | 3770    | 0       | 0       | 0       | 
| 1480965345  | Nexus-Home Audit CD               | 47500   | 53125   | 56123   | 60994   | 59051   | 57085   | 56550   | 80113   | 34637   | 0       | 
| 1480965345  | Compact Flourescent Distribution  | 70895   | 202709  | 101265  | 427230  | 0       | 0       | 0       | 0       | 6000    | 260095  | 
| 1480965345  | Municipal/ Loan Star Debt Service | 0       | 0       | 0       | 0       | 790     | 11247   | 58957   | 0       | 0       | 0       | 
```