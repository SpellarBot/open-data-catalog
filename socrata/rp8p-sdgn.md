# ESD Wallowa REVENUE BY FUND AND SOURCE 2011 2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/esd-wallowa-revenue-by-fund-and-source-2011-2012-ff802) |
| Metadata | [Link](https://data.oregon.gov/api/views/rp8p-sdgn) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/rp8p-sdgn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/rp8p-sdgn/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | rp8p-sdgn |
| Name | ESD Wallowa REVENUE BY FUND AND SOURCE 2011 2012 |
| Attribution | Region 18 ESD |
| Category | Education |
| Tags | revenue, esd, wallowa, region 18, 2012 |
| Created | 2012-11-28T23:19:14Z |
| Publication Date | 2012-11-28T23:42:08Z |

## Description

ESD Wallowa REVENUE BY FUND AND SOURCE 2011 2012

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type     | Render Type   |
| ======== | ============== | ============== | ============== | ============= | ============= |
| Yes      | time           | schoolyear     | SchoolYear     | calendar_date | calendar_date |
| Yes      | series tag     | esdid          | ESDID          | text          | number        |
| Yes      | series tag     | esd            | ESD            | text          | text          |
| Yes      | series tag     | fund_code      | Fund Code      | text          | number        |
| Yes      | series tag     | fund           | Fund           | text          | text          |
| Yes      | series tag     | revenue_type   | Revenue Type   | text          | text          |
| Yes      | series tag     | source_code    | Source Code    | text          | number        |
| Yes      | series tag     | revenue_source | Revenue Source | text          | text          |
| Yes      | numeric metric | actualrevamt   | ActualRevAmt   | money         | money         |
| Yes      | numeric metric | none           | (none)         | money         | money         |
```

## Time Field

```ls
Value = schoolyear
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:rp8p-sdgn d:2011-12-01T00:00:00.000Z t:source_code=1110 t:fund_code=100 t:esdid=2218 t:revenue_type=Local t:esd="Region 18 ESD" t:fund="General Fund" t:revenue_source="Ad valorem taxes levied by district" m:none=2370789.45

series e:rp8p-sdgn d:2011-12-01T00:00:00.000Z t:source_code=1500 t:fund_code=100 t:esdid=2218 t:revenue_type=Local t:esd="Region 18 ESD" t:fund="General Fund" t:revenue_source="Earnings on Investments" m:none=19606.58

series e:rp8p-sdgn d:2011-12-01T00:00:00.000Z t:source_code=1990 t:fund_code=100 t:esdid=2218 t:revenue_type=Local t:esd="Region 18 ESD" t:fund="General Fund" t:revenue_source=Miscellaneous m:none=55258.37
```

## Meta Commands

```ls
metric m:actualrevamt p:double l:ActualRevAmt t:dataTypeName=money

metric m:none p:double l:(none) t:dataTypeName=money

entity e:rp8p-sdgn l:"ESD Wallowa REVENUE BY FUND AND SOURCE  2011  2012" t:attribution="Region 18 ESD" t:url=https://data.oregon.gov/api/views/rp8p-sdgn

property e:rp8p-sdgn t:meta.view v:id=rp8p-sdgn v:category=Education v:averageRating=0 v:name="ESD Wallowa REVENUE BY FUND AND SOURCE  2011  2012" v:attribution="Region 18 ESD"

property e:rp8p-sdgn t:meta.view.license v:name="Public Domain"

property e:rp8p-sdgn t:meta.view.owner v:id=ku36-3r9m v:screenName="Wallowa ESD Region 18" v:displayName="Wallowa ESD Region 18"

property e:rp8p-sdgn t:meta.view.tableauthor v:id=ku36-3r9m v:screenName="Wallowa ESD Region 18" v:roleName=editor v:displayName="Wallowa ESD Region 18"
```

## Top Records

```ls
| schoolyear          | esdid | esd           | fund_code | fund                  | revenue_type | source_code | revenue_source                                               | actualrevamt | none       | 
| =================== | ===== | ============= | ========= | ===================== | ============ | =========== | ============================================================ | ============ | ========== | 
| 2011-12-01T00:00:00 | 2218  | Region 18 ESD | 100       | General Fund          | Local        | 1110        | Ad valorem taxes levied by district                          |              | 2370789.45 | 
| 2011-12-01T00:00:00 | 2218  | Region 18 ESD | 100       | General Fund          | Local        | 1500        | Earnings on Investments                                      |              | 19606.58   | 
| 2011-12-01T00:00:00 | 2218  | Region 18 ESD | 100       | General Fund          | Local        | 1990        | Miscellaneous                                                |              | 55258.37   | 
| 2011-12-01T00:00:00 | 2218  | Region 18 ESD | 100       | General Fund          | State        | 3800        | Revenue in Lieu of Taxes                                     |              | 1504.46    | 
| 2011-12-01T00:00:00 | 2218  | Region 18 ESD | 100       | General Fund          | Federal      | 4500        | Restricted Revenue From the Federal Government Through the S |              | 202026.67  | 
| 2011-12-01T00:00:00 | 2218  | Region 18 ESD | 200       | Special Revenue Funds | Local        | 1940        | Services Provided Other Local Education Agencies             |              | 637737.47  | 
| 2011-12-01T00:00:00 | 2218  | Region 18 ESD | 200       | Special Revenue Funds | Local        | 1990        | Miscellaneous                                                |              | 11857.20   | 
| 2011-12-01T00:00:00 | 2218  | Region 18 ESD | 200       | Special Revenue Funds | State        | 3299        | Other Restricted Grants-In-Aid                               |              | 76149.98   | 
| 2011-12-01T00:00:00 | 2218  | Region 18 ESD | 200       | Special Revenue Funds | Federal      | 4200        | Unrestricted Revenue From the Federal Government Through the |              | 53909.20   | 
| 2011-12-01T00:00:00 | 2218  | Region 18 ESD | 200       | Special Revenue Funds | Federal      | 4500        | Restricted Revenue From the Federal Government Through the S |              | 28758.59   | 
```