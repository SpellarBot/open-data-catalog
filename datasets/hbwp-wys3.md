# Iowa Motor Fuel Sales by County and Year

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/iowa-motor-fuel-sales-by-county-and-year) |
| Metadata | [Link](https://data.iowa.gov/api/views/hbwp-wys3) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/hbwp-wys3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/hbwp-wys3/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | hbwp-wys3 |
| Name | Iowa Motor Fuel Sales by County and Year |
| Attribution | Iowa Department of Revenue, Annual Iowa Motor Fuel Sales |
| Category | Economy |
| Tags | motor fuel, fuel, gas, revenue, taxes, biofuel, biofuel distribution percentage |
| Created | 2014-12-04T19:48:45Z |
| Publication Date | 2016-04-08T20:19:50Z |

## Description

This dataset provides total non-ethanol gasoline gallons, ethanol blends E10-E85, diesel, and biodiesel gallons sold by county for all retail locations that completed the Retailers Motor Fuel Gallons Annual Report.  The State of Iowa has a goal to replace 25 percent of petroleum in Iowa with biofuel by 2020. The biofuel distribution percentage measures how the state is doing toward meeting that goal. The formula for determining the biofuel distribution percentage is as follows:  Biofuel Distribution Percentage = (Pure Ethanol Gallons + Pure Biodiesel Gallons) / Total Gasoline Gallons .

## Columns

```ls
| Included | Schema Type    | Field Name                  | Name                                     | Data Type | Render Type |
| ======== | ============== | =========================== | ======================================== | ========= | =========== |
| Yes      | time           | calendar_year               | Calendar Year                            | number    | number      |
| Yes      | series tag     | county                      | County                                   | text      | text        |
| Yes      | numeric metric | number_of_retail_locations  | Number of Retail Locations               | number    | number      |
| Yes      | numeric metric | non_ethanol_gas_sales       | Non-Ethanol Gas Sales (in gallons)       | number    | number      |
| Yes      | numeric metric | ethanol_gas_sales           | Ethanol Gas Sales (in gallons)           | number    | number      |
| Yes      | numeric metric | clear_and_dyed_diesel_sales | Clear and Dyed Diesel Sales (in gallons) | number    | number      |
| Yes      | numeric metric | biodiesel_sales             | Biodiesel Sales (in gallons)             | number    | number      |
| Yes      | numeric metric | biofuel_distribution        | Biofuel Distribution Percentage          | percent   | percent     |
```

## Time Field

```ls
Value = calendar_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:hbwp-wys3 d:2015-01-01T00:00:00.000Z t:county=Adair m:number_of_retail_locations=12 m:biofuel_distribution=9.62 m:clear_and_dyed_diesel_sales=4653234 m:ethanol_gas_sales=7520613 m:biodiesel_sales=252780 m:non_ethanol_gas_sales=1810782

series e:hbwp-wys3 d:2015-01-01T00:00:00.000Z t:county=Allamakee m:number_of_retail_locations=17 m:biofuel_distribution=8.38 m:clear_and_dyed_diesel_sales=5367840 m:ethanol_gas_sales=6099959 m:biodiesel_sales=244533 m:non_ethanol_gas_sales=1343499

series e:hbwp-wys3 d:2015-01-01T00:00:00.000Z t:county=Appanoose m:number_of_retail_locations=15 m:biofuel_distribution=9.35 m:clear_and_dyed_diesel_sales=2356279 m:ethanol_gas_sales=4868178 m:biodiesel_sales=403749 m:non_ethanol_gas_sales=654927
```

## Meta Commands

```ls
metric m:number_of_retail_locations p:integer l:"Number of Retail Locations" d:"Number of retail fuel locations within the county" t:dataTypeName=number

metric m:non_ethanol_gas_sales p:integer l:"Non-Ethanol Gas Sales (in gallons)" d:"Gallons of non-ethanol gas sold" t:dataTypeName=number

metric m:ethanol_gas_sales p:integer l:"Ethanol Gas Sales (in gallons)" d:"Gallons of ethanol gas sold" t:dataTypeName=number

metric m:clear_and_dyed_diesel_sales p:integer l:"Clear and Dyed Diesel Sales (in gallons)" d:"Gallons of clear and dyed diesel sold" t:dataTypeName=number

metric m:biodiesel_sales p:integer l:"Biodiesel Sales (in gallons)" d:"Gallons of biodiesel sold" t:dataTypeName=number

metric m:biofuel_distribution p:float l:"Biofuel Distribution Percentage" d:"Biofuel Distribution Percentage = (Pure Ethanol Gallons + Pure Biodiesel Gallons) / Total Gasoline Gallons" t:dataTypeName=percent

entity e:hbwp-wys3 l:"Iowa Motor Fuel Sales by County and Year" t:attribution="Iowa Department of Revenue, Annual Iowa Motor Fuel Sales" t:url=https://data.iowa.gov/api/views/hbwp-wys3

property e:hbwp-wys3 t:meta.view v:id=hbwp-wys3 v:category=Economy v:averageRating=0 v:name="Iowa Motor Fuel Sales by County and Year" v:attribution="Iowa Department of Revenue, Annual Iowa Motor Fuel Sales"

property e:hbwp-wys3 t:meta.view.license v:name="Public Domain"

property e:hbwp-wys3 t:meta.view.owner v:id=y22p-i8y2 v:profileImageUrlMedium=/api/users/y22p-i8y2/profile_images/THUMB v:profileImageUrlLarge=/api/users/y22p-i8y2/profile_images/LARGE v:screenName="Revenue, Research and Analysis" v:profileImageUrlSmall=/api/users/y22p-i8y2/profile_images/TINY v:displayName="Revenue, Research and Analysis"

property e:hbwp-wys3 t:meta.view.tableauthor v:id=y22p-i8y2 v:profileImageUrlMedium=/api/users/y22p-i8y2/profile_images/THUMB v:profileImageUrlLarge=/api/users/y22p-i8y2/profile_images/LARGE v:screenName="Revenue, Research and Analysis" v:profileImageUrlSmall=/api/users/y22p-i8y2/profile_images/TINY v:roleName=editor v:displayName="Revenue, Research and Analysis"
```

## Top Records

```ls
| calendar_year | county      | number_of_retail_locations | non_ethanol_gas_sales | ethanol_gas_sales | clear_and_dyed_diesel_sales | biodiesel_sales | biofuel_distribution | 
| ============= | =========== | ========================== | ===================== | ================= | =========================== | =============== | ==================== | 
| 2015          | Adair       | 12                         | 1810782               | 7520613           | 4653234                     | 252780          | 9.62                 | 
| 2015          | Allamakee   | 17                         | 1343499               | 6099959           | 5367840                     | 244533          | 8.38                 | 
| 2015          | Appanoose   | 15                         | 654927                | 4868178           | 2356279                     | 403749          | 9.35                 | 
| 2015          | Audubon     | 7                          | 188819                | 1770154           | 1735839                     | 375979          | 11.18                | 
| 2015          | Benton      | 23                         | 1222760               | 9105211           | 3529864                     | 171230          | 10.03                | 
| 2015          | Black Hawk  | 67                         | 9296676               | 47990028          | 8041775                     | 14510649        | 11.75                | 
| 2015          | Boone       | 14                         | 1260377               | 9259121           | 2084018                     | 332672          | 9.09                 | 
| 2015          | Bremer      | 15                         | 2158638               | 9677843           | 2720216                     | 26776           | 8.19                 | 
| 2015          | Buchanan    | 17                         | 1276589               | 8019066           | 1928789                     | 86804           | 8.70                 | 
| 2015          | Buena Vista | 23                         | 1155246               | 8409080           | 1866166                     | 112875          | 9.54                 | 
```