# Unemployment Compensation Fund Status - Fund Balance and Solvency

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/unemployment-compensation-fund-status-fund-balance-and-solvency) |
| Metadata | [Link](https://data.iowa.gov/api/views/csji-bia6) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/csji-bia6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/csji-bia6/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | csji-bia6 |
| Name | Unemployment Compensation Fund Status - Fund Balance and Solvency |
| Attribution | Iowa Workforce Development - Labor Market Information Division |
| Category | Economy |
| Tags | unemployment insurance, ui trust fund, ui trust fund solvency |
| Created | 2015-05-05T13:46:47Z |
| Publication Date | 2017-02-27T21:05:26Z |

## Description

This dataset contains annual Unemployment Insurance Trust Fund Balance and Solvency data. This data is analyzed in the "Status Report on the Iowa Unemployment Compensation Trust Fund" report.

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                  | Data Type | Render Type |
| ======== | ============== | =================== | ===================== | ========= | =========== |
| Yes      | time           | year                | Year                  | number    | number      |
| Yes      | numeric metric | ui_trust_fund       | UI Trust Fund         | money     | money       |
| Yes      | numeric metric | iowa_reserve_fund   | Reserve Fund          | money     | money       |
| Yes      | numeric metric | combined_ui_fund    | Combined UI Fund      | money     | money       |
| Yes      | numeric metric | cpi_adjusted_tf     | CPI Adjusted TF       | money     | money       |
| Yes      | numeric metric | tf_percent_of_wages | Reserve Ratio         | percent   | percent     |
| Yes      | numeric metric | months_current      | Months Current        | number    | number      |
| Yes      | numeric metric | months_high_year    | Months High Cost      | number    | number      |
| Yes      | numeric metric | months_average_high | Months Average High   | number    | number      |
| Yes      | numeric metric | high_benefit_cost   | Highest Benefit Level | money     | money       |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:csji-bia6 d:1980-01-01T00:00:00.000Z m:months_current=6.7 m:ui_trust_fund=110.2 m:combined_ui_fund=110.2 m:cpi_adjusted_tf=127.7 m:high_benefit_cost=196.5 m:iowa_reserve_fund=0 m:tf_percent_of_wages=0.98 m:months_high_year=6.7 m:months_average_high=8.4

series e:csji-bia6 d:1981-01-01T00:00:00.000Z m:months_current=6.7 m:ui_trust_fund=96.5 m:combined_ui_fund=96.5 m:cpi_adjusted_tf=102.6 m:high_benefit_cost=219.6 m:iowa_reserve_fund=0 m:tf_percent_of_wages=0.81 m:months_high_year=5.3 m:months_average_high=7

series e:csji-bia6 d:1982-01-01T00:00:00.000Z m:months_current=-2.4 m:ui_trust_fund=-63.3 m:combined_ui_fund=-63.3 m:cpi_adjusted_tf=-64.9 m:high_benefit_cost=302.5 m:iowa_reserve_fund=0 m:months_high_year=-2.5 m:months_average_high=-3.4
```

## Meta Commands

```ls
metric m:ui_trust_fund p:double l:"UI Trust Fund" d:"UI Trust Fund Balance (millions): The Unemployment Trust Fund is a fund established in the Treasury of the United States which contains all monies deposited by state agencies to the credit of their unemployment fund accounts and federal unemployment taxes (FUTA) collected by the Internal Revenue Service. In this dataset this term refers to the balance in Iowa?s individual account in the Unemployment Trust Fund which is available to pay UI benefits." t:dataTypeName=money

metric m:iowa_reserve_fund p:double l:"Reserve Fund" d:"Iowa Reserve Fund (millions) - This refers to the principal in the Unemployment Compensation Reserve Fund created in the state treasury under S. F. 458 in 2003. Monies in the reserve fund shall be used to pay benefits to the extent moneys in the unemployment compensation fund are insufficient to pay benefits during a calendar quarter." t:dataTypeName=money

metric m:combined_ui_fund p:double l:"Combined UI Fund" d:"Combined UI Fund (millions) - This report uses this term to refer to the combined balances of the UI Trust Fund and the Iowa Reserve Fund. The term ?fund balance? refers this Combined Trust Fund balance in the ""Status Report on the Iowa Unemployment Compensation Trust Fund""." t:dataTypeName=money

metric m:cpi_adjusted_tf p:double l:"CPI Adjusted TF" d:"CPI Adjusted Trust Fund Balance (millions) - Combined UI fund balance adjusted by the Consumer Price Index [CPI-U 1982-1984=100]" t:dataTypeName=money

metric m:tf_percent_of_wages p:float l:"Reserve Ratio" d:"Trust Fund as a Percent of UI Covered Wages (Reserve Ratio) - Combined Trust Fund balance as a percentage of UI covered wages for contributory employers. The fund is expressed as a percentage of covered wages in order to control for employment and wage growth. The contribution rate table formulas use 2.0 percent of covered wages as a minimum safety factor." t:dataTypeName=percent

metric m:months_current p:float l:"Months Current" d:"Months of Benefits in Trust Fund (Current Benefit Level) - Combined Trust Fund Balance divided by average monthly UI Benefits paid for each year." t:dataTypeName=number

metric m:months_high_year p:float l:"Months High Cost" d:"Months of Benefits in Trust Fund at Highest Benefit Cost Level - The number of months of benefits in the combined trust fund at the historic highest benefit level adjusted for covered wage growth." t:dataTypeName=number

metric m:months_average_high p:float l:"Months Average High" d:"Months of Benefits in Trust Fund at Three Year Average High Benefit Cost Level - The number of months of benefits in the combined trust fund at the historic highest three year average benefit level adjusted for covered wage growth. The U. S. Department of Labor recommends a solvency standard of 12 months." t:dataTypeName=number

metric m:high_benefit_cost p:double l:"Highest Benefit Level" d:"Highest Benefit Level Adjusted for Wage and Employment Growth (millions) - The amount of benefits that would be paid out at the historic highest benefit level adjusted for covered wage growth for contributory employers. Iowa's highest benefit cost level is based on the 12-month period ending April 1983. Fund expenditures totaled $317 million and contributory wages totaled $11.6 billion. Total expenditures for the 12-month period equaled 2.746 percent of contributory wages." t:dataTypeName=money

entity e:csji-bia6 l:"Unemployment Compensation Fund Status - Fund Balance and Solvency" t:attribution="Iowa Workforce Development - Labor Market Information Division" t:url=https://data.iowa.gov/api/views/csji-bia6

property e:csji-bia6 t:meta.view v:id=csji-bia6 v:category=Economy v:attributionLink=https://www.iowaworkforcedevelopment.gov/sites/search.iowaworkforcedevelopment.gov/files/unemploymentcomp_trustfund_statusreport_1.pdf v:averageRating=0 v:name="Unemployment Compensation Fund Status - Fund Balance and Solvency" v:attribution="Iowa Workforce Development - Labor Market Information Division"

property e:csji-bia6 t:meta.view.owner v:id=fipn-jtty v:profileImageUrlMedium=/api/users/fipn-jtty/profile_images/THUMB v:profileImageUrlLarge=/api/users/fipn-jtty/profile_images/LARGE v:screenName="Unemployment Insurance Statistics" v:profileImageUrlSmall=/api/users/fipn-jtty/profile_images/TINY v:lastNotificationSeenAt=1491494200 v:displayName="Unemployment Insurance Statistics"

property e:csji-bia6 t:meta.view.tableauthor v:id=fipn-jtty v:profileImageUrlMedium=/api/users/fipn-jtty/profile_images/THUMB v:profileImageUrlLarge=/api/users/fipn-jtty/profile_images/LARGE v:screenName="Unemployment Insurance Statistics" v:profileImageUrlSmall=/api/users/fipn-jtty/profile_images/TINY v:roleName=editor v:lastNotificationSeenAt=1491494200 v:displayName="Unemployment Insurance Statistics"
```

## Top Records

```ls
| year | ui_trust_fund | iowa_reserve_fund | combined_ui_fund | cpi_adjusted_tf | tf_percent_of_wages | months_current | months_high_year | months_average_high | high_benefit_cost | 
| ==== | ============= | ================= | ================ | =============== | =================== | ============== | ================ | =================== | ================= | 
| 1980 | 110.2         | 0.0               | 110.2            | 127.7           | 0.98                | 6.7            | 6.7              | 8.4                 | 196.5             | 
| 1981 | 96.5          | 0.0               | 96.5             | 102.6           | 0.81                | 6.7            | 5.3              | 7.0                 | 219.6             | 
| 1982 | -63.3         | 0.0               | -63.3            | -64.9           |                     | -2.4           | -2.5             | -3.4                | 302.5             | 
| 1983 | -126.3        | 0.0               | -126.3           | -124.7          |                     | -6.0           | -4.7             | -6.0                | 323.6             | 
| 1984 | -37.4         | 0.0               | -37.4            | -35.5           |                     | -2.9           | -1.3             | -1.6                | 346.3             | 
| 1985 | 49.3          | 0.0               | 49.3             | 45.1            | 0.38                | 3.3            | 1.7              | 2.1                 | 352.5             | 
| 1986 | 142.5         | 0.0               | 142.5            | 129.0           | 1.08                | 10.4           | 4.7              | 6.0                 | 361.6             | 
| 1987 | 276.9         | 0.0               | 276.9            | 239.9           | 1.95                | 26.3           | 8.5              | 10.8                | 389.5             | 
| 1988 | 418.6         | 0.0               | 418.6            | 347.4           | 2.72                | 44.0           | 11.9             | 15.1                | 422.6             | 
| 1989 | 506.7         | 0.0               | 506.7            | 401.8           | 3.08                | 49.3           | 13.5             | 17.1                | 451.3             | 
```