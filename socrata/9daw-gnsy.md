# Solar Rebate Program

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/solar-rebate-program) |
| Metadata | [Link](https://data.austintexas.gov/api/views/9daw-gnsy) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/9daw-gnsy/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/9daw-gnsy/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | 9daw-gnsy |
| Name | Solar Rebate Program |
| Attribution | Austin Energy |
| Category | Utility |
| Tags | rebate, solar, solar rebate program, home performance, energy star, energy |
| Created | 2016-11-07T23:02:56Z |
| Publication Date | 2016-11-14T21:44:12Z |

## Description

Austin Energy has provided solar incentives to help residential and commercial customers install solar energy systems. View the number of rebates, average rebate per customer, and average size since the program?s start in fiscal year 2004. Go to austinenergy.com/go/solar and austinenergy.com/go/solarincentives to learn more about solar solutions and incentives from Austin Energy.

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                 | Data Type | Render Type |
| ======== | ============== | ==================== | ==================== | ========= | =========== |
| No       | time           | :updated_at          | updated_at           | meta_data | meta_data   |
| Yes      | series tag     | solar_rebate_program | Solar Rebate Program | text      | text        |
| Yes      | series tag     | customer_class       | Customer Class       | text      | text        |
| Yes      | numeric metric | fy_2004              | FY 2004              | number    | number      |
| Yes      | numeric metric | fy_2005              | FY 2005              | number    | number      |
| Yes      | numeric metric | fy_2006              | FY 2006              | number    | number      |
| Yes      | numeric metric | fy_2007              | FY 2007              | number    | number      |
| Yes      | numeric metric | fy_2008              | FY 2008              | number    | number      |
| Yes      | numeric metric | fy_2009              | FY 2009              | number    | number      |
| Yes      | numeric metric | fy_2010              | FY 2010              | number    | number      |
| Yes      | numeric metric | fy_2011              | FY 2011              | number    | number      |
| Yes      | numeric metric | fy_2012              | FY 2012              | number    | number      |
| Yes      | numeric metric | fy_2013              | FY 2013              | number    | number      |
| Yes      | numeric metric | fy_2014              | FY 2014              | number    | number      |
| Yes      | numeric metric | fy_2015              | FY 2015              | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:9daw-gnsy d:2016-11-14T15:51:50.000Z t:solar_rebate_program="Rebate Dollars" t:customer_class="Residential (Capacity Based Incentive)" m:fy_2014=6581495 m:fy_2013=7877289 m:fy_2015=6746963 m:fy_2010=3216535.05 m:fy_2005=1782183.13 m:fy_2004=117450.7 m:fy_2012=5721412.02 m:fy_2011=4711101.25 m:fy_2008=2823539.78 m:fy_2009=4228791.48 m:fy_2006=2074101.49 m:fy_2007=1712579.57

series e:9daw-gnsy d:2016-11-14T15:51:50.000Z t:solar_rebate_program="# Rebates" t:customer_class="Residential (Capacity Based Incentive)" m:fy_2014=762 m:fy_2013=719 m:fy_2015=969 m:fy_2010=213 m:fy_2005=129 m:fy_2004=9 m:fy_2012=458 m:fy_2011=328 m:fy_2008=222 m:fy_2009=255 m:fy_2006=163 m:fy_2007=133

series e:9daw-gnsy d:2016-11-14T15:51:50.000Z t:solar_rebate_program=kW-AC t:customer_class="Residential (Capacity Based Incentive)" m:fy_2014=3777 m:fy_2013=3503 m:fy_2015=5227 m:fy_2010=793.26 m:fy_2005=295.4 m:fy_2004=19.22 m:fy_2012=1913.26 m:fy_2011=1352.65 m:fy_2008=532.48 m:fy_2009=803.07 m:fy_2006=395.7 m:fy_2007=311.84
```

## Meta Commands

```ls
metric m:fy_2004 p:float l:"FY 2004" t:dataTypeName=number

metric m:fy_2005 p:double l:"FY 2005" t:dataTypeName=number

metric m:fy_2006 p:double l:"FY 2006" t:dataTypeName=number

metric m:fy_2007 p:double l:"FY 2007" t:dataTypeName=number

metric m:fy_2008 p:double l:"FY 2008" t:dataTypeName=number

metric m:fy_2009 p:double l:"FY 2009" t:dataTypeName=number

metric m:fy_2010 p:double l:"FY 2010" t:dataTypeName=number

metric m:fy_2011 p:double l:"FY 2011" t:dataTypeName=number

metric m:fy_2012 p:double l:"FY 2012" t:dataTypeName=number

metric m:fy_2013 p:float l:"FY 2013" t:dataTypeName=number

metric m:fy_2014 p:float l:"FY 2014" t:dataTypeName=number

metric m:fy_2015 p:float l:"FY 2015" t:dataTypeName=number

entity e:9daw-gnsy l:"Solar Rebate Program" t:attribution="Austin Energy" t:url=https://data.austintexas.gov/api/views/9daw-gnsy

property e:9daw-gnsy t:meta.view v:id=9daw-gnsy v:category=Utility v:averageRating=0 v:name="Solar Rebate Program" v:attribution="Austin Energy"

property e:9daw-gnsy t:meta.view.license v:name="Public Domain"

property e:9daw-gnsy t:meta.view.owner v:id=c433-zrb5 v:profileImageUrlMedium=/api/users/c433-zrb5/profile_images/THUMB v:profileImageUrlLarge=/api/users/c433-zrb5/profile_images/LARGE v:screenName="Sarah Lambert" v:profileImageUrlSmall=/api/users/c433-zrb5/profile_images/TINY v:displayName="Sarah Lambert"

property e:9daw-gnsy t:meta.view.tableauthor v:id=c433-zrb5 v:profileImageUrlMedium=/api/users/c433-zrb5/profile_images/THUMB v:profileImageUrlLarge=/api/users/c433-zrb5/profile_images/LARGE v:screenName="Sarah Lambert" v:profileImageUrlSmall=/api/users/c433-zrb5/profile_images/TINY v:roleName=publisher v:displayName="Sarah Lambert"
```

## Top Records

```ls
| :updated_at | solar_rebate_program     | customer_class                         | fy_2004   | fy_2005    | fy_2006    | fy_2007    | fy_2008    | fy_2009    | fy_2010    | fy_2011    | fy_2012    | fy_2013    | fy_2014    | fy_2015    | 
| =========== | ======================== | ====================================== | ========= | ========== | ========== | ========== | ========== | ========== | ========== | ========== | ========== | ========== | ========== | ========== | 
| 1479138710  | Rebate Dollars           | Residential (Capacity Based Incentive) | 117450.70 | 1782183.13 | 2074101.49 | 1712579.57 | 2823539.78 | 4228791.48 | 3216535.05 | 4711101.25 | 5721412.02 | 7877289.00 | 6581495.00 | 6746963.00 | 
| 1479138710  | # Rebates                | Residential (Capacity Based Incentive) | 9         | 129        | 163        | 133        | 222        | 255        | 213        | 328        | 458        | 719        | 762        | 969        | 
| 1479138710  | kW-AC                    | Residential (Capacity Based Incentive) | 19.22     | 295.4      | 395.7      | 311.84     | 532.48     | 803.07     | 793.26     | 1352.65    | 1913.26    | 3503.00    | 3777.00    | 5227.00    | 
| 1479138710  | Avg. Rebate per customer | Residential (Capacity Based Incentive) | 13050.08  | 13815.37   | 12724.55   | 12876.54   | 12718.65   | 16583.50   | 15101.10   | 14363.11   | 12492.17   | 10956.00   | 8637.00    | 6963.00    | 
| 1479138710  | Avg. System Size kW-AC   | Residential (Capacity Based Incentive) | 2.14      | 2.29       | 2.43       | 2.34       | 2.4        | 3.15       | 3.72       | 4.12       | 4.18       | 4.87       | 4.95       | 5.39       | 
| 1479138710  | $/kW-AC                  | Residential (Capacity Based Incentive) | 6112.13   | 6033.06    | 5241.57    | 5491.91    | 5302.67    | 5265.76    | 4054.81    | 3482.86    | 2990.41    | 2249.00    | 1743.00    | 1291.00    | 
| 1479138710  | Rebate Dollars           | Commercial (Capacity Based Incentive)  | 11478.40  | 1028044.04 | 305206.49  | 700478.59  | 1455069.01 | 2086482.78 | 556648.87  | 0.00       | 0.00       | 0.00       | 0.00       | 0.00       | 
| 1479138710  | # Rebates                | Commercial (Capacity Based Incentive)  | 1         | 12         | 5          | 13         | 25         | 37         | 10         | 0          | 0          | 0.00       | 0.00       | 0.00       | 
| 1479138710  | kW-AC                    | Commercial (Capacity Based Incentive)  | 2.06      | 169.41     | 53.98      | 127.85     | 262.72     | 376.62     | 106.28     | 0          | 0          | 0.00       | 0.00       | 0.00       | 
| 1479138710  | Avg. Rebate per customer | Commercial (Capacity Based Incentive)  | 11478.40  | 85670.34   | 61041.30   | 53882.97   | 58202.76   | 56391.43   | 55664.89   | 0.00       | 0.00       | 0.00       | 0.00       | 0.00       | 
```