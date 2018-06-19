# Iowa Gross Domestic Product by Quarter and Industry

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/iowa-gross-domestic-product-by-quarter-and-industry) |
| Metadata | [Link](https://data.iowa.gov/api/views/f2xe-wr7z) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/f2xe-wr7z/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/f2xe-wr7z/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | f2xe-wr7z |
| Name | Iowa Gross Domestic Product by Quarter and Industry |
| Attribution | U.S. Department of Commerce, Bureau of Economic Analysis, GDP in current dollars |
| Category | Economy |
| Tags | gross domestic product |
| Created | 2016-03-10T20:48:01Z |
| Publication Date | 2016-08-30T16:18:42Z |

## Description

Gross domestic product (GDP) is the measure of the market value of all final goods and services produced within Iowa in a particular period of time.  In concept, an industry's GDP by state, referred to as its "value added", is equivalent to its gross output (sales or receipts and other operating income, commodity taxes, and inventory change) minus its intermediate inputs (consumption of goods and services purchased from other U.S. industries or imported). The Iowa GDP a state counterpart to the Nation's GDP, the Bureau's featured and most comprehensive measure of U.S. economic activity. Iowa GDP differs from national GDP for the following reasons: Iowa GDP excludes and national GDP includes the compensation of federal civilian and military personnel stationed abroad and government consumption of fixed capital for military structures located abroad and for military equipment, except office equipment; and Iowa GDP and national GDP have different revision schedules.

Iowa Gross Domestic Product available starting in 2005.  Millions of dollars, seasonally adjusted at annual rates.

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                              | Data Type     | Render Type   |
| ======== | ============== | ====================== | ================================= | ============= | ============= |
| Yes      | time           | quarter_ending         | Date Quarter Ended                | calendar_date | calendar_date |
| No       |                | quarter                | Quarter                           | text          | text          |
| Yes      | series tag     | ind_code               | Industry Code                     | text          | text          |
| Yes      | series tag     | industry_type          | Industry Type                     | text          | text          |
| Yes      | series tag     | industry               | Industry                          | text          | text          |
| Yes      | numeric metric | gross_domestic_product | GDP (millions of current dollars) | money         | money         |
```

## Time Field

```ls
Value = quarter_ending
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = quarter
```

## Data Commands

```ls
series e:f2xe-wr7z d:2005-03-31T00:00:00.000Z t:industry_type="Private Industries" t:industry="Management of companies and enterprises" t:ind_code=64 m:gross_domestic_product=990

series e:f2xe-wr7z d:2005-06-30T00:00:00.000Z t:industry_type="Private Industries" t:industry="Management of companies and enterprises" t:ind_code=64 m:gross_domestic_product=1018

series e:f2xe-wr7z d:2011-03-31T00:00:00.000Z t:industry_type="Private Industries" t:industry=Manufacturing t:ind_code=12 m:gross_domestic_product=25127
```

## Meta Commands

```ls
metric m:gross_domestic_product p:integer l:"GDP (millions of current dollars)" d:"Iowa Gross Domestic Product, Millions of dollars, seasonally adjusted at annual rates." t:dataTypeName=money

entity e:f2xe-wr7z l:"Iowa Gross Domestic Product by Quarter and Industry" t:attribution="U.S. Department of Commerce, Bureau of Economic Analysis, GDP in current dollars" t:url=https://data.iowa.gov/api/views/f2xe-wr7z

property e:f2xe-wr7z t:meta.view v:id=f2xe-wr7z v:category=Economy v:attributionLink=http://www.bea.gov/itable/index.cfm v:averageRating=0 v:name="Iowa Gross Domestic Product by Quarter and Industry" v:attribution="U.S. Department of Commerce, Bureau of Economic Analysis, GDP in current dollars"

property e:f2xe-wr7z t:meta.view.license v:name="Public Domain U.S. Government" v:termsLink=https://www.usa.gov/government-works

property e:f2xe-wr7z t:meta.view.owner v:id=hqmd-ehvn v:profileImageUrlMedium=/api/users/hqmd-ehvn/profile_images/THUMB v:profileImageUrlLarge=/api/users/hqmd-ehvn/profile_images/LARGE v:screenName="State Data Administrator" v:profileImageUrlSmall=/api/users/hqmd-ehvn/profile_images/TINY v:lastNotificationSeenAt=1492549701 v:displayName="State Data Administrator"

property e:f2xe-wr7z t:meta.view.tableauthor v:id=hqmd-ehvn v:profileImageUrlMedium=/api/users/hqmd-ehvn/profile_images/THUMB v:profileImageUrlLarge=/api/users/hqmd-ehvn/profile_images/LARGE v:screenName="State Data Administrator" v:profileImageUrlSmall=/api/users/hqmd-ehvn/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1492549701 v:displayName="State Data Administrator"
```

## Top Records

```ls
| quarter_ending      | quarter | ind_code | industry_type      | industry                                | gross_domestic_product | 
| =================== | ======= | ======== | ================== | ======================================= | ====================== | 
| 2005-03-31T00:00:00 | 2005Q1  | 64       | Private Industries | Management of companies and enterprises | 990                    | 
| 2005-06-30T00:00:00 | 2005Q2  | 64       | Private Industries | Management of companies and enterprises | 1018                   | 
| 2011-03-31T00:00:00 | 2011Q1  | 12       | Private Industries | Manufacturing                           | 25127                  | 
| 2005-09-30T00:00:00 | 2005Q3  | 64       | Private Industries | Management of companies and enterprises | 1067                   | 
| 2005-12-31T00:00:00 | 2005Q4  | 64       | Private Industries | Management of companies and enterprises | 1130                   | 
| 2012-09-30T00:00:00 | 2012Q3  | 51       | Private Industries | Finance and insurance                   | 17950                  | 
| 2006-03-31T00:00:00 | 2006Q1  | 64       | Private Industries | Management of companies and enterprises | 1145                   | 
| 2006-06-30T00:00:00 | 2006Q2  | 64       | Private Industries | Management of companies and enterprises | 1180                   | 
| 2011-12-31T00:00:00 | 2011Q4  | 69       | Private Industries | Educational services                    | 1338                   | 
| 2006-09-30T00:00:00 | 2006Q3  | 64       | Private Industries | Management of companies and enterprises | 1215                   | 
```