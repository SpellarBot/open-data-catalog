# Prequalified Firms

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/prequalified-firms-cb0fa) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/szkz-syh6) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/szkz-syh6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/szkz-syh6/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | szkz-syh6 |
| Name | Prequalified Firms |
| Attribution | School Construction Authority (SCA) |
| Category | Housing & Development |
| Tags | school, construction, authority, sca, firm, company, companies, work, trade, qualification, qualify, qualified, education |
| Created | 2013-07-02T19:05:05Z |
| Publication Date | 2017-04-14T19:17:35Z |

## Description

List of firms qualified to perform work for the School Construction Authority, their trades, and the end date of their qualification.

## Columns

```ls
| Included | Schema Type | Field Name                                                | Name                                                      | Data Type     | Render Type   |
| ======== | =========== | ========================================================= | ========================================================= | ============= | ============= |
| Yes      | series tag  | prequalified_vendor_master_trade_code                     | Prequalified Vendor Master Trade Code                     | text          | text          |
| Yes      | series tag  | prequalified_vendor_trade_description                     | Prequalified Vendor Trade Description                     | text          | text          |
| Yes      | series tag  | prequalified_vendor_name                                  | Prequalified Vendor Name                                  | text          | text          |
| No       |             | prequalified_vendor_address                               | Prequalified Vendor Address                               | text          | text          |
| Yes      | series tag  | prequalified_vendor_city_name                             | Prequalified Vendor City Name                             | text          | text          |
| Yes      | series tag  | prequalified_vendor_state_code                            | Prequalified Vendor State Code                            | text          | text          |
| Yes      | series tag  | prequalified_vendor_zip_code                              | Prequalified Vendor Zip Code                              | text          | text          |
| Yes      | series tag  | prequalified_vendor_phone_number                          | Prequalified Vendor Phone Number                          | text          | text          |
| Yes      | series tag  | prequalified_vendor_fax_number                            | Prequalified Vendor Fax Number                            | text          | text          |
| Yes      | series tag  | prequalified_vendor_contact_person                        | Prequalified Vendor Contact Person                        | text          | text          |
| Yes      | series tag  | prequalified_vendor_minority_business_indicator           | Prequalified Vendor Minority Business Indicator           | text          | text          |
| Yes      | series tag  | prequalified_vendor_women_business_indicator              | Prequalified Vendor Women Business Indicator              | text          | text          |
| Yes      | series tag  | prequalified_vendor_local_business_indicator              | Prequalified Vendor Local Business Indicator              | text          | text          |
| Yes      | series tag  | prequalified_vendor_over_million_dollar_revenue_indicator | Prequalified Vendor Over Million Dollar Revenue Indicator | text          | text          |
| Yes      | time        | prequalified_vendor_date                                  | Prequalified Vendor Date                                  | calendar_date | calendar_date |
```

## Time Field

```ls
Value = prequalified_vendor_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = prequalified_vendor_address
```

## Data Commands

```ls
series e:szkz-syh6 d:2018-01-23T00:00:00.000Z t:prequalified_vendor_over_million_dollar_revenue_indicator=N t:prequalified_vendor_local_business_indicator=N t:prequalified_vendor_zip_code=10705 t:prequalified_vendor_state_code=NY t:prequalified_vendor_master_trade_code=15080 t:prequalified_vendor_phone_number=914-774-3258 t:prequalified_vendor_fax_number=914-457-8835 t:prequalified_vendor_women_business_indicator=N t:prequalified_vendor_contact_person="MAREK MAJ" t:prequalified_vendor_trade_description="MECHANICAL INSULATION" t:prequalified_vendor_minority_business_indicator=N t:prequalified_vendor_name="INSAREN, INC." t:prequalified_vendor_city_name=Yonkers m:row_number.szkz-syh6=1

series e:szkz-syh6 d:2020-03-16T00:00:00.000Z t:prequalified_vendor_over_million_dollar_revenue_indicator=Y t:prequalified_vendor_local_business_indicator=N t:prequalified_vendor_zip_code=11209 t:prequalified_vendor_state_code=NY t:prequalified_vendor_master_trade_code=35000 t:prequalified_vendor_phone_number=347-578-7191 t:prequalified_vendor_women_business_indicator=N t:prequalified_vendor_contact_person="Michael Urtnowski" t:prequalified_vendor_trade_description="CONSTRUCTION MANAGERS" t:prequalified_vendor_minority_business_indicator=N t:prequalified_vendor_name="INSTITUTE FOR BUILDING TECHNOLOGY AND SAFETY" t:prequalified_vendor_city_name=Brooklyn m:row_number.szkz-syh6=2

series e:szkz-syh6 d:2020-03-16T00:00:00.000Z t:prequalified_vendor_over_million_dollar_revenue_indicator=Y t:prequalified_vendor_local_business_indicator=N t:prequalified_vendor_zip_code=11209 t:prequalified_vendor_state_code=NY t:prequalified_vendor_master_trade_code=37015 t:prequalified_vendor_phone_number=347-578-7191 t:prequalified_vendor_women_business_indicator=N t:prequalified_vendor_contact_person="Michael Urtnowski" t:prequalified_vendor_trade_description="BUILDING CODES/STANDARDS/ORDINANCES" t:prequalified_vendor_minority_business_indicator=N t:prequalified_vendor_name="INSTITUTE FOR BUILDING TECHNOLOGY AND SAFETY" t:prequalified_vendor_city_name=Brooklyn m:row_number.szkz-syh6=3
```

## Meta Commands

```ls
metric m:row_number.szkz-syh6 p:long l:"Row Number"

entity e:szkz-syh6 l:"Prequalified Firms" t:attribution="School Construction Authority (SCA)" t:url=https://data.cityofnewyork.us/api/views/szkz-syh6

property e:szkz-syh6 t:meta.view v:id=szkz-syh6 v:category="Housing & Development" v:attributionLink=http://www.nycsca.org/Business/GettingStarted/Pages/PrequalifiedFirms.aspx v:averageRating=0 v:name="Prequalified Firms" v:attribution="School Construction Authority (SCA)"

property e:szkz-syh6 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:szkz-syh6 t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| prequalified_vendor_master_trade_code | prequalified_vendor_trade_description          | prequalified_vendor_name                     | prequalified_vendor_address | prequalified_vendor_city_name | prequalified_vendor_state_code | prequalified_vendor_zip_code | prequalified_vendor_phone_number | prequalified_vendor_fax_number | prequalified_vendor_contact_person | prequalified_vendor_minority_business_indicator | prequalified_vendor_women_business_indicator | prequalified_vendor_local_business_indicator | prequalified_vendor_over_million_dollar_revenue_indicator | prequalified_vendor_date | 
| ===================================== | ============================================== | ============================================ | =========================== | ============================= | ============================== | ============================ | ================================ | ============================== | ================================== | =============================================== | ============================================ | ============================================ | ========================================================= | ======================== | 
| 15080                                 | MECHANICAL INSULATION                          | INSAREN, INC.                                | 185 Devoe Avenue            | Yonkers                       | NY                             | 10705                        | 914-774-3258                     | 914-457-8835                   | MAREK MAJ                          | N                                               | N                                            | N                                            | N                                                         | 2018-01-23T00:00:00      | 
| 35000                                 | CONSTRUCTION MANAGERS                          | INSTITUTE FOR BUILDING TECHNOLOGY AND SAFETY | 9201 4th Ave.               | Brooklyn                      | NY                             | 11209                        | 347-578-7191                     |                                | Michael Urtnowski                  | N                                               | N                                            | N                                            | Y                                                         | 2020-03-16T00:00:00      | 
| 37015                                 | BUILDING CODES/STANDARDS/ORDINANCES            | INSTITUTE FOR BUILDING TECHNOLOGY AND SAFETY | 9201 4th Ave.               | Brooklyn                      | NY                             | 11209                        | 347-578-7191                     |                                | Michael Urtnowski                  | N                                               | N                                            | N                                            | Y                                                         | 2020-03-16T00:00:00      | 
| 37023                                 | COST ESTIMATING                                | INSTITUTE FOR BUILDING TECHNOLOGY AND SAFETY | 9201 4th Ave.               | Brooklyn                      | NY                             | 11209                        | 347-578-7191                     |                                | Michael Urtnowski                  | N                                               | N                                            | N                                            | Y                                                         | 2020-03-16T00:00:00      | 
| 99960                                 | GENL CONTR - INTERIOR MODIFICATIONS            | Integrated Construction Enterprises, Inc.    | 259 Stephens Street         | Belleville                    | NJ                             | 07109                        | 973-450-5161                     | 973-445-1661                   | Lori Harmon                        | Y                                               | N                                            | N                                            | Y                                                         | 2017-09-12T00:00:00      | 
| 16100                                 | WIRING METHODS                                 | Interface Cable Assembles and Services Corp  | 42-19 23rd Avenue           | Long Island City              | NY                             | 11105                        | 718-278-1100                     | 631-672-7673                   | Yasha Katz                         | N                                               | N                                            | N                                            | N                                                         | 2019-08-09T00:00:00      | 
| 16700                                 | COMMUNICATIONS                                 | Interface Cable Assembles and Services Corp  | 42-19 23rd Avenue           | Long Island City              | NY                             | 11105                        | 718-278-1100                     | 631-672-7673                   | Yasha Katz                         | N                                               | N                                            | N                                            | N                                                         | 2019-08-09T00:00:00      | 
| 16810                                 | DIVISION 16 - SURVEILLANCE CAMERAS/CAT 5/CAT 6 | Interface Cable Assembles and Services Corp  | 42-19 23rd Avenue           | Long Island City              | NY                             | 11105                        | 718-278-1100                     | 631-672-7673                   | Yasha Katz                         | N                                               | N                                            | N                                            | N                                                         | 2019-08-09T00:00:00      | 
| 12490                                 | WINDOW TREATMENT                               | INTERNATIONAL BLIND CONTRACTORS, LTD.        | 274 MADISON AVENUE          | NEW YORK                      | NY                             | 10016                        | 212-473-2000                     | 212-353-3400                   | Michael Berkowitz                  | N                                               | N                                            | N                                            | N                                                         | 2019-10-11T00:00:00      | 
| 86080                                 | SECURITY SERVICES - WATCHGUARD/PATROL          | International Security Institute Inc.        | 86-32 55th Avenue           | Elmhurst                      | NY                             | 11373                        | 718-505-0486                     | 917-446-1946                   | Abdul Rashid Zafar                 | Y                                               | N                                            | N                                            | N                                                         | 2018-04-24T00:00:00      | 
```