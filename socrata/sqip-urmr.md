# Post Offices

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/post-offices-2aec7) |
| Metadata | [Link](https://data.montgomerycountymd.gov/api/views/sqip-urmr) |
| Data: JSON | [100 Rows](https://data.montgomerycountymd.gov/api/views/sqip-urmr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.montgomerycountymd.gov/api/views/sqip-urmr/rows.csv?max_rows=100) |
| Host | data.montgomerycountymd.gov |
| Id | sqip-urmr |
| Name | Post Offices |
| Attribution | Montgomery County, MD |
| Category | Community/Recreation |
| Tags | mail, post office, usps |
| Created | 2012-02-28T21:11:16Z |
| Publication Date | 2012-09-13T19:47:49Z |

## Description

Address and Locations for Post Offices in Montgomery County, MD.

## Columns

```ls
| Included | Schema Type | Field Name  | Name       | Data Type | Render Type |
| ======== | =========== | =========== | ========== | ========= | =========== |
| No       | time        | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag  | name        | NAME       | text      | text        |
| No       |             | address     | ADDRESS    | text      | text        |
| Yes      | series tag  | city        | CITY       | text      | text        |
| Yes      | series tag  | zip_code    | ZIP CODE   | text      | number      |
| Yes      | series tag  | phone       | PHONE      | text      | text        |
| Yes      | series tag  | url         | URL        | text      | text        |
| No       |             | longitude   | LONGITUDE  | number    | number      |
| No       |             | latitude    | LATITUDE   | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address,longitude,latitude
```

## Data Commands

```ls
series e:sqip-urmr d:2012-02-28T13:11:23.000Z t:phone=301-253-3781 t:zip_code=20872 t:name="Damascus Post Office" t:url="http://usps.whitepages.com/service/post_office/25180?p=1&s=md&service_name=post_office&z=damascus" t:city=Damascus m:row_number.sqip-urmr=1

series e:sqip-urmr d:2012-02-28T13:11:23.000Z t:phone=301-428-8243 t:zip_code=20842 t:name="Dickerson Post Office" t:url="http://usps.whitepages.com/service/post_office/34855?p=1&s=md&service_name=post_office&z=dickerson" t:city=Dickerson m:row_number.sqip-urmr=2

series e:sqip-urmr d:2012-02-28T13:11:23.000Z t:phone=301-972-8153 t:zip_code=20838 t:name="Barnesville Post Office" t:url="http://usps.whitepages.com/service/post_office/50116?p=1&s=md&service_name=post_office&z=barnesville" t:city=Barnesville m:row_number.sqip-urmr=3
```

## Meta Commands

```ls
metric m:row_number.sqip-urmr p:long l:"Row Number"

entity e:sqip-urmr l:"Post Offices" t:attribution="Montgomery County, MD" t:url=https://data.montgomerycountymd.gov/api/views/sqip-urmr

property e:sqip-urmr t:meta.view v:id=sqip-urmr v:category=Community/Recreation v:averageRating=0 v:name="Post Offices" v:attribution="Montgomery County, MD"

property e:sqip-urmr t:meta.view.license v:name="Public Domain"

property e:sqip-urmr t:meta.view.owner v:id=yr5d-z7h2 v:screenName="John Gillick" v:displayName="John Gillick"

property e:sqip-urmr t:meta.view.tableauthor v:id=yr5d-z7h2 v:screenName="John Gillick" v:roleName=administrator v:displayName="John Gillick"
```

## Top Records

```ls
| :updated_at | name                           | address                    | city               | zip_code | phone        | url                                                                                                                | longitude      | latitude      | 
| =========== | ============================== | ========================== | ================== | ======== | ============ | ================================================================================================================== | ============== | ============= | 
| 1330434683  | Damascus Post Office           | 26400 Woodfield Rd         | Damascus           | 20872    | 301-253-3781 | http://usps.whitepages.com/service/post_office/25180?p=1&s=md&service_name=post_office&z=damascus                  | -77.2036788974 | 39.2879885628 | 
| 1330434683  | Dickerson Post Office          | 22145 Dickerson Rd         | Dickerson          | 20842    | 301-428-8243 | http://usps.whitepages.com/service/post_office/34855?p=1&s=md&service_name=post_office&z=dickerson                 | -77.4243450455 | 39.2190394952 | 
| 1330434683  | Barnesville Post Office        | 22110 Beallsville Rd       | Barnesville        | 20838    | 301-972-8153 | http://usps.whitepages.com/service/post_office/50116?p=1&s=md&service_name=post_office&z=barnesville               | -77.3781123871 | 39.2184742711 | 
| 1330434683  | Laytonsville Post Office       | 6830 Olney Laytonsville Rd | Laytonsville       | 20882    | 301-208-3736 | http://usps.whitepages.com/service/post_office/73830?p=1&s=md&service_name=post_office&z=Laytonsville              | -77.1400195797 | 39.2036461636 | 
| 1330434683  | Beallsville Post Office        | 19800 Darnestown Rd        | Beallsville        | 20839    | 301-349-2140 | http://usps.whitepages.com/service/post_office/50156?p=1&s=md&service_name=post_office&z=beallsville               | -77.4131905048 | 39.1792235313 | 
| 1330434683  | Boyds Post Office              | 15300 Barnsville Rd        | Boyds              | 20841    | 301-972-9527 | http://usps.whitepages.com/service/post_office/1483?p=1&s=md&service_name=post_office&z=boyds                      | -77.3167831549 | 39.1858234797 | 
| 1330434683  | Brookeville Post Office        | 22311 Georgia Ave          | Brookeville        | 20833    | 301-260-2975 | http://usps.whitepages.com/service/post_office/50472?a=22311+georgia+ave&p=1&s=md&service_name=post_office&z=olney | -77.0591895233 | 39.2214732292 | 
| 1330434683  | Germantown Post Office         | 12774 Wisteria Dr          | Germantown         | 20874    | 301-428-0460 | http://usps.whitepages.com/service/post_office/44592?p=1&s=md&service_name=post_office&z=germantown                | -77.2675694567 | 39.1745678055 | 
| 1330434683  | Montgomery Village Post Office | 10079 Stedwick Rd          | Montgomery Village | 20886    | 301-208-3716 | http://usps.whitepages.com/service/post_office/71401?p=1&s=md&service_name=post_office&z=Montgomery+Village        | -77.208194117  | 39.1709169889 | 
| 1330434683  | Olney Post Office              | 3570 Olney Laytonsville Rd | Olney              | 20832    | 301-260-9013 | http://usps.whitepages.com/service/post_office/2771?p=1&s=md&service_name=post_office&z=Olney                      | -77.0712682943 | 39.1552009807 | 
```