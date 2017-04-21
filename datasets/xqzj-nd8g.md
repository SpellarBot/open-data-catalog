# Residential Water Use

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/residential-water-use-0adc9) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/xqzj-nd8g) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/xqzj-nd8g/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/xqzj-nd8g/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | xqzj-nd8g |
| Name | Residential Water Use |
| Attribution | Department of Environmental Protection (DEP) |
| Category | Environment |
| Tags | dep, department of environmental protection, environment, water, residential, water use, residential water use, healthy living |
| Created | 2013-02-01T03:26:07Z |
| Publication Date | 2013-06-21T19:45:02Z |

## Description

Residential Water Use Fact Sheet

## Columns

```ls
| Included | Schema Type | Field Name        | Name              | Data Type | Render Type |
| ======== | =========== | ================= | ================= | ========= | =========== |
| No       | time        | :updated_at       | updated_at        | meta_data | meta_data   |
| Yes      | series tag  | item_description  | Item Description  | text      | text        |
| Yes      | series tag  | water_use_details | Water Use Details | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:xqzj-nd8g d:2013-01-31T19:26:09.000Z t:item_description="Combined water and sewer rate in New York City is:" t:water_use_details="$8.21 per 100 cubic feet of water* (07/01/11-06/30/12)" m:row_number.xqzj-nd8g=1

series e:xqzj-nd8g d:2013-01-31T19:26:09.000Z t:item_description="National average indoor residential water use per day per person is:" t:water_use_details="60 - 70 gallons" m:row_number.xqzj-nd8g=2

series e:xqzj-nd8g d:2013-01-31T19:26:09.000Z t:item_description="50 - 75% of all residential water use occurs:" t:water_use_details="In the bathroom" m:row_number.xqzj-nd8g=3
```

## Meta Commands

```ls
metric m:row_number.xqzj-nd8g p:long l:"Row Number"

entity e:xqzj-nd8g l:"Residential Water Use" t:attribution="Department of Environmental Protection (DEP)" t:url=https://data.cityofnewyork.us/api/views/xqzj-nd8g

property e:xqzj-nd8g t:meta.view v:id=xqzj-nd8g v:category=Environment v:attributionLink=http://www.nyc.gov/html/dep/html/residents/wateruse.shtml v:averageRating=0 v:name="Residential Water Use" v:attribution="Department of Environmental Protection (DEP)"

property e:xqzj-nd8g t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:xqzj-nd8g t:meta.view.tableauthor v:id=ya7g-926w v:screenName="Aakash Dalwani" v:displayName="Aakash Dalwani"
```

## Top Records

```ls
| :updated_at | item_description                                                     | water_use_details                                       | 
| =========== | ==================================================================== | ======================================================= | 
| 1359660369  | Combined water and sewer rate in New York City is:                   |  $8.21 per 100 cubic feet of water* (07/01/11-06/30/12) | 
| 1359660369  | National average indoor residential water use per day per person is: |  60 - 70 gallons                                        | 
| 1359660369  | 50 - 75% of all residential water use occurs:                        |  In the bathroom                                        | 
| 1359660369  | A standard (pre-1980) toilet uses:                                   |  4.5 - 7.0 gallons per flush                            | 
| 1359660369  | 1980s vintage toilet (1980 - 1992) uses:                             |  3.5 gallons per flush                                  | 
| 1359660369  | A low-consumption toilet uses:                                       |  1.6 gallons per flush (or less)                        | 
| 1359660369  | Displacement bags save:                                              |  0.6 gallons per flush                                  | 
| 1359660369  | Flush valve retrofit kits save:                                      |  1.0 - 1.5 gallons per flush                            | 
| 1359660369  | The average faucet uses:                                             |  0.5 - 5 gallons per minute                             | 
| 1359660369  | Faucet aerators reduce flow by:                                      |  1 gallon per minute                                    | 
```