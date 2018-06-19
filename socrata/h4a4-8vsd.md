# Table A1: Actual and Forecast of Key Economic Indicators for Hawaii: 2010 TO 2015

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/table-a1-actual-and-forecast-of-key-economic-indicators-for-hawaii-2010-to-2015-83eb4) |
| Metadata | [Link](https://data.hawaii.gov/api/views/h4a4-8vsd) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/h4a4-8vsd/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/h4a4-8vsd/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | h4a4-8vsd |
| Name | Table A1: Actual and Forecast of Key Economic Indicators for Hawaii: 2010 TO 2015 |
| Attribution | DOH |
| Category | Health |
| Tags | key, economic, indicators |
| Created | 2012-08-01T00:31:24Z |
| Publication Date | 2012-08-01T00:33:25Z |

## Description

DOH Environmental Indicators

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type | Render Type |
| ======== | ============== | =================== | =================== | ========= | =========== |
| Yes      | series tag     | economic_indicators | Economic Indicators | text      | text        |
| No       |                | _1                  | 2010                | number    | number      |
| No       |                | _2                  | 2011                | number    | number      |
| Yes      | numeric metric | forecast_1          | 2012 (Forecast)     | number    | number      |
| Yes      | numeric metric | forecast_2          | 2013 (Forecast)     | number    | number      |
| Yes      | numeric metric | forecast_3          | 2014 (Forecast)     | number    | number      |
| Yes      | numeric metric | forecast_4          | 2015 (Forecast)     | number    | number      |
```

## Time Field

```ls
Value = 2010
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = _1,_2
```

## Data Commands

```ls
series e:h4a4-8vsd d:2010-01-01T00:00:00.000Z t:economic_indicators="Total population (thousands)" m:forecast_4=1431 m:forecast_3=1416 m:forecast_2=1402 m:forecast_1=1389

series e:h4a4-8vsd d:2010-01-01T00:00:00.000Z t:economic_indicators="Honolulu CPI-U (1982-84=100)" m:forecast_4=271 m:forecast_3=264.4 m:forecast_2=258 m:forecast_1=250.9

series e:h4a4-8vsd d:2010-01-01T00:00:00.000Z t:economic_indicators="Personal income (million dollars)" m:forecast_4=72083 m:forecast_3=68520 m:forecast_2=65133 m:forecast_1=62031
```

## Meta Commands

```ls
metric m:forecast_1 p:double l:"2012 (Forecast)" t:dataTypeName=number

metric m:forecast_2 p:double l:"2013 (Forecast)" t:dataTypeName=number

metric m:forecast_3 p:double l:"2014 (Forecast)" t:dataTypeName=number

metric m:forecast_4 p:double l:"2015 (Forecast)" t:dataTypeName=number

entity e:h4a4-8vsd l:"Table A1: Actual and Forecast of Key Economic Indicators for Hawaii: 2010 TO 2015" t:attribution=DOH t:url=https://data.hawaii.gov/api/views/h4a4-8vsd

property e:h4a4-8vsd t:meta.view v:id=h4a4-8vsd v:category=Health v:attributionLink=http://hawaii.gov/doh v:averageRating=0 v:name="Table A1: Actual and Forecast of Key Economic Indicators for Hawaii: 2010 TO 2015" v:attribution=DOH

property e:h4a4-8vsd t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:h4a4-8vsd t:meta.view.owner v:id=8c9u-vteh v:screenName=lorrink v:displayName=lorrink

property e:h4a4-8vsd t:meta.view.tableauthor v:id=8c9u-vteh v:screenName=lorrink v:roleName=editor v:displayName=lorrink
```

## Top Records

```ls
| economic_indicators                  | _1                 | _2    | forecast_1         | forecast_2 | forecast_3         | forecast_4 | 
| ==================================== | ================== | ===== | ================== | ========== | ================== | ========== | 
| Total population (thousands)         | 1363               | 1375  | 1389               | 1402       | 1416               | 1431       | 
| Honolulu CPI-U (1982-84=100)         | 234.9              | 243.6 | 250.9              | 258        | 264.39999999999998 | 271        | 
| Personal income (million dollars)    | 56647              | 59190 | 62031              | 65133      | 68520              | 72083      | 
| Total wage & salary jobs (thousands) | 593.20000000000005 | 599   | 608.29999999999995 | 618.9      | 628.20000000000005 | 636.4      | 
| Annual Percentage Change             |                    |       |                    |            |                    |            | 
| Total population                     | 1.2                | 0.8   | 1                  | 1          | 1                  | 1          | 
| Honolulu CPI-U                       | 2.1                | 3.7   | 3                  | 2.8        | 2.5                | 2.5        | 
| Personal income                      | 3.7                | 4.5   | 4.8                | 5          | 5.2                | 5.2        | 
| Total wage & salary jobs             | -0.8               | 1     | 1.5                | 1.7        | 1.5                | 1.3        | 
| Visitor arrivals (thousands)         | 7018               | 7284  | 7754               | 7923       | 8115               | 8305       | 
```