# Iowa Seasonally Adjusted Non-Farm Employment by Month and Industry

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/iowa-seasonally-adjusted-non-farm-employment-by-month-and-industry) |
| Metadata | [Link](https://data.iowa.gov/api/views/sxz8-4swt) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/sxz8-4swt/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/sxz8-4swt/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | sxz8-4swt |
| Name | Iowa Seasonally Adjusted Non-Farm Employment by Month and Industry |
| Attribution | U.S. Department of Labor, Bureau of Labor Statistics, State and Metro Area Employment, Hours & Earnings |
| Category | Economy |
| Tags | employment, non-farm, seasonally adjusted, government, goods-producing, service-providing |
| Created | 2014-11-12T15:08:03Z |
| Publication Date | 2015-08-10T18:28:06Z |

## Description

This dataset provides final seasonally adjusted employment estimates for the State of Iowa. Iowa's estimate contained in this dataset is broken into the following "expanded" supersectors:

    Goods-Producing: Construction, Manufacturing, and Mining and Logging
    Service-Providing: Education and Health Services, Financial Activities, Information, Leisure and Hospitality, Other Services, Professional and Business Services, Retail Trade, Transportation and Utilities, and Wholesale Trade
    Government: Federal Government, State Government, and Local Government

Seasonal adjusted estimates help eliminate sharp fluctuations in employment levels due to such seasonal events as changes in weather, reduced or expanded production, harvests, major holidays, and the opening and closing of schools. Adjusting the estimates to eliminate the seasonal events that tend to follow a regular pattern each year, make it easier to observe cyclical and other nonseasonal movements in the data. More information on the seasonal adjustment process can be found on the Bureau of Labor Statistics website: http://www.bls.gov/sae/790faq2.htm#Ques3.

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                      | Data Type     | Render Type   |
| ======== | ============== | ======================= | ========================= | ============= | ============= |
| Yes      | time           | month_ending            | Month Ending              | calendar_date | calendar_date |
| No       |                | month                   | Month                     | text          | text          |
| No       |                | year                    | Year                      | number        | number        |
| Yes      | series tag     | category                | Category                  | text          | text          |
| Yes      | series tag     | supersector_or_industry | Supersector or Industry   | text          | text          |
| Yes      | numeric metric | employment_in_thousands | Employment (in thousands) | number        | number        |
```

## Time Field

```ls
Value = month_ending
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = year,month
```

## Data Commands

```ls
series e:sxz8-4swt d:2002-01-31T00:00:00.000Z t:category=Service-Providing t:supersector_or_industry="Wholesale Trade" m:employment_in_thousands=67.5

series e:sxz8-4swt d:2005-05-31T00:00:00.000Z t:category=Service-Providing t:supersector_or_industry="Wholesale Trade" m:employment_in_thousands=67.4

series e:sxz8-4swt d:2007-09-30T00:00:00.000Z t:category=Service-Providing t:supersector_or_industry="Wholesale Trade" m:employment_in_thousands=68.3
```

## Meta Commands

```ls
metric m:employment_in_thousands p:float l:"Employment (in thousands)" d:"Monthly employment estimate (in thousands)" t:dataTypeName=number

entity e:sxz8-4swt l:"Iowa Seasonally Adjusted Non-Farm Employment by Month and Industry" t:attribution="U.S. Department of Labor, Bureau of Labor Statistics, State and Metro Area Employment, Hours & Earnings" t:url=https://data.iowa.gov/api/views/sxz8-4swt

property e:sxz8-4swt t:meta.view v:id=sxz8-4swt v:category=Economy v:attributionLink="http://data.bls.gov/pdq/querytool.jsp?survey=sm" v:averageRating=0 v:name="Iowa Seasonally Adjusted Non-Farm Employment by Month and Industry" v:attribution="U.S. Department of Labor, Bureau of Labor Statistics, State and Metro Area Employment, Hours & Earnings"

property e:sxz8-4swt t:meta.view.license v:name="Public Domain"

property e:sxz8-4swt t:meta.view.owner v:id=38m8-5nrq v:profileImageUrlMedium=/api/users/38m8-5nrq/profile_images/THUMB v:profileImageUrlLarge=/api/users/38m8-5nrq/profile_images/LARGE v:screenName="Iowa Workforce Development" v:profileImageUrlSmall=/api/users/38m8-5nrq/profile_images/TINY v:displayName="Iowa Workforce Development"

property e:sxz8-4swt t:meta.view.tableauthor v:id=38m8-5nrq v:profileImageUrlMedium=/api/users/38m8-5nrq/profile_images/THUMB v:profileImageUrlLarge=/api/users/38m8-5nrq/profile_images/LARGE v:screenName="Iowa Workforce Development" v:profileImageUrlSmall=/api/users/38m8-5nrq/profile_images/TINY v:roleName=editor v:displayName="Iowa Workforce Development"
```

## Top Records

```ls
| month_ending        | month | year | category          | supersector_or_industry | employment_in_thousands | 
| =================== | ===== | ==== | ================= | ======================= | ======================= | 
| 2002-01-31T00:00:00 | Jan   | 2002 | Service-Providing | Wholesale Trade         | 67.5                    | 
| 2005-05-31T00:00:00 | May   | 2005 | Service-Providing | Wholesale Trade         | 67.4                    | 
| 2007-09-30T00:00:00 | Sep   | 2007 | Service-Providing | Wholesale Trade         | 68.3                    | 
| 1997-01-31T00:00:00 | Jan   | 1997 | Service-Providing | Wholesale Trade         | 68                      | 
| 2008-12-31T00:00:00 | Dec   | 2008 | Service-Providing | Wholesale Trade         | 68.3                    | 
| 2005-01-31T00:00:00 | Jan   | 2005 | Service-Providing | Wholesale Trade         | 66.8                    | 
| 2004-12-31T00:00:00 | Dec   | 2004 | Service-Providing | Wholesale Trade         | 67                      | 
| 2004-11-30T00:00:00 | Nov   | 2004 | Service-Providing | Wholesale Trade         | 66.9                    | 
| 2004-10-31T00:00:00 | Oct   | 2004 | Service-Providing | Wholesale Trade         | 66.7                    | 
| 2007-11-30T00:00:00 | Nov   | 2007 | Service-Providing | Wholesale Trade         | 68.5                    | 
```