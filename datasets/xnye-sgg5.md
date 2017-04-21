# CMS FY12 IL Procurement Bulletin Notices Through 8.10.2011

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cms-fy12-il-procurement-bulletin-notices-through-8-10-2011-1185d) |
| Metadata | [Link](https://data.illinois.gov/api/views/xnye-sgg5) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/xnye-sgg5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/xnye-sgg5/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | xnye-sgg5 |
| Name | CMS FY12 IL Procurement Bulletin Notices Through 8.10.2011 |
| Attribution | Central Management Services (CMS) |
| Tags | procurement |
| Created | 2011-09-01T14:16:41Z |
| Publication Date | 2012-01-26T17:36:52Z |

## Description

FY12 IL Procurement Bulletin Notices Through 8.10.2011

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type | Render Type |
| ======== | ============== | =============== | =============== | ========= | =========== |
| Yes      | series tag     | notice_type     | Notice Type     | text      | text        |
| Yes      | numeric metric | estimated_value | Estimated Value | money     | money       |
| Yes      | series tag     | title           | Title           | text      | text        |
| Yes      | time           | published_date  | Published Date  | date      | date        |
```

## Time Field

```ls
Value = published_date
Format & Zone = seconds
```

## Data Commands

```ls
series e:xnye-sgg5 d:2011-09-01T07:16:42.000Z t:title="Award to Other Than Lowest Responsible Bidder" m:estimated_value=1

series e:xnye-sgg5 d:2011-07-07T07:00:00.000Z t:title="FY11-13 Revenue Physical Security Consultant" t:notice_type="Award to Other Than Lowest Responsible Bidder" m:estimated_value=170146

series e:xnye-sgg5 d:2011-09-01T07:16:42.000Z t:title="Canceled Notice" m:estimated_value=3
```

## Meta Commands

```ls
metric m:estimated_value p:double l:"Estimated Value" t:dataTypeName=money

entity e:xnye-sgg5 l:"CMS FY12 IL Procurement Bulletin Notices Through 8.10.2011" t:attribution="Central Management Services (CMS)" t:url=https://data.illinois.gov/api/views/xnye-sgg5

property e:xnye-sgg5 t:meta.view v:id=xnye-sgg5 v:averageRating=0 v:name="CMS FY12 IL Procurement Bulletin Notices Through 8.10.2011" v:attribution="Central Management Services (CMS)"

property e:xnye-sgg5 t:meta.view.owner v:id=j5i3-tak9 v:screenName="Melissa Camille" v:displayName="Melissa Camille"

property e:xnye-sgg5 t:meta.view.tableauthor v:id=j5i3-tak9 v:screenName="Melissa Camille" v:roleName=publisher v:displayName="Melissa Camille"
```

## Top Records

```ls
| notice_type                                   | estimated_value | title                                                                            | published_date | 
| ============================================= | =============== | ================================================================================ | ============== | 
|                                               | 1               | Award to Other Than Lowest Responsible Bidder                                    |                | 
| Award to Other Than Lowest Responsible Bidder | 170146          | FY11-13 Revenue Physical Security Consultant                                     | 1310022000     | 
|                                               | 3               | Canceled Notice                                                                  |                | 
| Canceled Notice                               | 0               | Certified Public Accountant for Bureau of Warehouses                             | 1309935600     | 
| Canceled Notice                               | 60000           | District 2 Electrical Services                                                   | 1310108400     | 
| Canceled Notice                               | 29700           | Weather Forecasting Services for District 1                                      | 1310454000     | 
|                                               | 20              | Canceled Solicitation                                                            |                | 
| Canceled Solicitation                         | 0               | PSD AUTOMOTIVE DIAGNOSTICS SCANNING TOOLS                                        | 1310108400     | 
| Canceled Solicitation                         | 0               | PSD QUANTITATIVE FLUOROMETRIC TEST-P.H. CHICAGO, SPRINGFIELD, & CARBONDALE-REBID | 1310367600     | 
| Canceled Solicitation                         | 0               | PSD DISHWASHER, CONVEYOR TYPE-STERO MDL 64 OR EQUIVALENT QTY 1 SBSA              | 1310454000     | 
```