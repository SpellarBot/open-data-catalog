# IHDA - Illinois Housing Dev Auth - FY2010 Governor's Report - Closings.SF Home

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ihda-illinois-housing-dev-auth-fy2010-governors-report-closings-sf-home-1d570) |
| Metadata | [Link](https://data.illinois.gov/api/views/kdh8-qycw) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/kdh8-qycw/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/kdh8-qycw/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | kdh8-qycw |
| Name | IHDA - Illinois Housing Dev Auth - FY2010 Governor's Report - Closings.SF Home |
| Category | Housing |
| Tags | ihda, illinois housing development authority |
| Created | 2012-01-25T17:09:36Z |
| Publication Date | 2012-01-25T21:59:48Z |

## Description

FY2010 Governor's Report - Closings.SF Home

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                       | Data Type     | Render Type   |
| ======== | ============== | ========================== | ========================== | ============= | ============= |
| No       |                | fiscal_year                | FISCAL YEAR                | number        | text          |
| Yes      | series tag     | project_name_              | PROJECT NAME               | text          | text          |
| No       |                | project_address            | PROJECT ADDRESS            | text          | text          |
| Yes      | series tag     | project_state_subrecipient | PROJECT State/Subrecipient | text          | text          |
| Yes      | series tag     | type                       | TYPE                       | text          | text          |
| Yes      | time           | closing_date               | CLOSING DATE               | calendar_date | calendar_date |
| Yes      | numeric metric | home_funds_requested       | HOME FUNDS REQUESTED       | money         | money         |
| Yes      | numeric metric | home_                      | HOME $                     | money         | money         |
| Yes      | numeric metric | of_units                   | # OF UNITS                 | number        | number        |
```

## Time Field

```ls
Value = closing_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = project_address,fiscal_year
```

## Data Commands

```ls
series e:kdh8-qycw d:2010-05-27T00:00:00.000Z t:project_name_="Homebuyer Program" t:project_state_subrecipient="B.C.M.W. Community Services" t:type=Grant m:home_=331000 m:home_funds_requested=330000 m:of_units=8

series e:kdh8-qycw d:2010-05-27T00:00:00.000Z t:project_name_="Homebuyer Program" t:project_state_subrecipient="C.E.F.S. Economic Opportunity Corporation" t:type=Grant m:home_=169000 m:home_funds_requested=168000 m:of_units=4

series e:kdh8-qycw d:2010-05-27T00:00:00.000Z t:project_name_="Homebuyer Program" t:project_state_subrecipient="City of Carbondale" t:type=Grant m:home_=211000 m:home_funds_requested=210000 m:of_units=5
```

## Meta Commands

```ls
metric m:home_funds_requested p:integer l:"HOME FUNDS REQUESTED" t:dataTypeName=money

metric m:home_ p:integer l:"HOME $" t:dataTypeName=money

metric m:of_units p:integer l:"# OF UNITS" t:dataTypeName=number

entity e:kdh8-qycw l:"IHDA - Illinois Housing Dev Auth - FY2010 Governor's Report - Closings.SF Home" t:url=https://data.illinois.gov/api/views/kdh8-qycw

property e:kdh8-qycw t:meta.view v:id=kdh8-qycw v:category=Housing v:averageRating=0 v:name="IHDA - Illinois Housing Dev Auth - FY2010 Governor's Report - Closings.SF Home"

property e:kdh8-qycw t:meta.view.owner v:id=i46z-zq8e v:screenName="Larry Michalski" v:displayName="Larry Michalski"

property e:kdh8-qycw t:meta.view.tableauthor v:id=i46z-zq8e v:screenName="Larry Michalski" v:roleName=publisher v:displayName="Larry Michalski"
```

## Top Records

```ls
| fiscal_year | project_name_     | project_address                                                                                  | project_state_subrecipient                    | type  | closing_date        | home_funds_requested | home_  | of_units | 
| =========== | ================= | ================================================================================================ | ============================================= | ===== | =================== | ==================== | ====== | ======== | 
| 2010        | Homebuyer Program | Scattered Sites in Bond, Clinton, Jefferson and Marion Counties                                  | B.C.M.W. Community Services                   | Grant | 2010-05-27T00:00:00 | 330000               | 331000 | 8        | 
| 2010        | Homebuyer Program | Scattered Sites in Christian, Clay, Effingham, Fayette, Montgomery, Moultrie and Shelby Counties | C.E.F.S. Economic Opportunity Corporation     | Grant | 2010-05-27T00:00:00 | 168000               | 169000 | 4        | 
| 2010        | Homebuyer Program | Scattered Sites in the City of Carbondale                                                        | City of Carbondale                            | Grant | 2010-05-27T00:00:00 | 210000               | 211000 | 5        | 
| 2010        | Homebuyer Program | Scattered Sites in the City of Freeport                                                          | City of Freeport                              | Grant | 2010-05-27T00:00:00 | 210000               | 211000 | 5        | 
| 2010        | Homebuyer Program | Scattered Sites in the City of Kankakee                                                          | City of Kankakee                              | Grant | 2010-05-27T00:00:00 | 178875               | 179875 | 8        | 
| 2010        | Homebuyer Program | Scattered Sites in the City of Moline                                                            | City of Moline                                | Grant | 2010-05-27T00:00:00 | 510000               | 311000 | 12       | 
| 2010        | Homebuyer Program | Scattered Sites in McLean County                                                                 | Habitat for Humanity of McLean County, Inc.   | Grant | 2010-05-27T00:00:00 | 84000                | 84000  | 8        | 
| 2010        | Homebuyer Program | Scattered Sites in Christian, Logan, Macoupin, Menard, Montgomery and Sangamon Counties          | Illinois Assistive Technology Program         | Grant | 2010-05-27T00:00:00 | 155000               | 155000 | 15       | 
| 2010        | Homebuyer Program | Scattered Sites in Jo Daviess and Stephenson Counties                                            | Northwestern Illinois Community Action Agency | Grant | 2010-05-27T00:00:00 | 460000               | 411000 | 10       | 
| 2010        | Homebuyer Program | Scattered Sites in Henry, Mercer and Rock Island Counties                                        | Project NOW, Inc.                             | Grant | 2010-05-27T00:00:00 | 570000               | 491000 | 12       | 
```