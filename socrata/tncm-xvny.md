# Water Well and Closed Loop Well Continuing Education Dates

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/water-well-and-closed-loop-well-continuing-education-dates-56bde) |
| Metadata | [Link](https://data.illinois.gov/api/views/tncm-xvny) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/tncm-xvny/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/tncm-xvny/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | tncm-xvny |
| Name | Water Well and Closed Loop Well Continuing Education Dates |
| Attribution | Illinois Department of Public Health - Division of Environmental Health |
| Category | Public Health |
| Tags | well, continuing education |
| Created | 2014-10-10T21:00:57Z |
| Publication Date | 2016-11-18T20:50:11Z |

## Description

Water Well and Closed Loop Contractors are required to acquire continuing education each year. This list provides continuing education opportunities. Last Updated November 2016

## Columns

```ls
| Included | Schema Type    | Field Name                    | Name                          | Data Type     | Render Type   |
| ======== | ============== | ============================= | ============================= | ============= | ============= |
| Yes      | series tag     | continuing_education          | CONTINUING EDUCATION          | text          | text          |
| Yes      | time           | continuing_education_dates    | CONTINUING EDUCATION DATES    | calendar_date | calendar_date |
| Yes      | numeric metric | continuing_education_hours    | CONTINUING EDUCATION HOURS    | number        | number        |
| Yes      | series tag     | continuing_education_sponsor  | CONTINUING EDUCATION SPONSOR  | text          | text          |
| Yes      | series tag     | event_fee                     | EVENT FEE                     | text          | text          |
| Yes      | series tag     | continuing_educati0n_location | CONTINUING EDUCATI0N LOCATION | text          | text          |
| No       |                | continuing_education_address  | CONTINUING EDUCATION ADDRESS  | text          | text          |
| Yes      | series tag     | continuing_education_city     | CONTINUING EDUCATION CITY     | text          | text          |
| Yes      | series tag     | continuing_education_state    | CONTINUING EDUCATION STATE    | text          | text          |
| Yes      | series tag     | continuing_education_zipcode  | CONTINUING EDUCATION ZIPCODE  | text          | number        |
| Yes      | series tag     | phone                         | PHONE                         | text          | text          |
| Yes      | series tag     | e_mail                        | E-MAIL                        | email         | email         |
| Yes      | series tag     | website                       | Website                       | url           | url           |
```

## Time Field

```ls
Value = continuing_education_dates
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = continuing_education_address
```

## Data Commands

```ls
series e:tncm-xvny d:2017-03-28T00:00:00.000Z t:continuing_education_state=IL t:phone=815-742-4755 t:continuing_education_zipcode=61111 t:continuing_education="Water Well and/or Pump Installation Contractor Continuing Education" t:event_fee=$50.00 t:continuing_educati0n_location="Forest Hills Lodge -   Old West Room" t:continuing_education_sponsor="Independent Water Well Contractors" t:continuing_education_city="Loves Park" m:continuing_education_hours=6

series e:tncm-xvny d:2017-02-10T00:00:00.000Z t:continuing_education_state=IL t:phone=815-973-3000 t:continuing_education_zipcode=61611 t:website=http://www.iagp.org t:continuing_education="Water Well and/or Pump Installation Contractor Continuing Education" t:event_fee="$115 -IAGP Member$145 Non IAGP Member" t:continuing_educati0n_location="Embassy Suites & Convention Center" t:e_mail=info@iagp.org t:continuing_education_sponsor="Illinois Asociation of Groundwater Professionals (IAGP)" t:continuing_education_city="East Peoria" m:continuing_education_hours=6

series e:tncm-xvny d:2017-04-22T00:00:00.000Z t:continuing_education_state=IL t:phone=815-973-3000 t:continuing_education_zipcode=62702 t:website=http://www.iagp.org t:continuing_education="Water Well and/or Pump Installation Contractor Continuing Education" t:event_fee="$115 -IAGP Member$145 Non IAGP Member" t:continuing_educati0n_location="Kiswaukee College" t:e_mail=info@iagp.org t:continuing_education_sponsor="Illinois Asociation of Groundwater Professionals (IAGP)" t:continuing_education_city=Malta m:continuing_education_hours=6
```

## Meta Commands

```ls
metric m:continuing_education_hours p:integer l:"CONTINUING EDUCATION HOURS" t:dataTypeName=number

entity e:tncm-xvny l:"Water Well and Closed Loop Well Continuing Education Dates" t:attribution="Illinois Department of Public Health - Division of Environmental Health" t:url=https://data.illinois.gov/api/views/tncm-xvny

property e:tncm-xvny t:meta.view v:id=tncm-xvny v:category="Public Health" v:attributionLink=http://dph.illinois.gov/topics-services/environmental-health-protection/private-water v:averageRating=0 v:name="Water Well and Closed Loop Well Continuing Education Dates" v:attribution="Illinois Department of Public Health - Division of Environmental Health"

property e:tncm-xvny t:meta.view.owner v:id=mkk8-dris v:screenName="Greg Matheny" v:displayName="Greg Matheny"

property e:tncm-xvny t:meta.view.tableauthor v:id=mkk8-dris v:screenName="Greg Matheny" v:roleName=publisher v:displayName="Greg Matheny"
```

## Top Records

```ls
| continuing_education                                                | continuing_education_dates | continuing_education_hours | continuing_education_sponsor                            | event_fee                                            | continuing_educati0n_location      | continuing_education_address                                             | continuing_education_city | continuing_education_state | continuing_education_zipcode | phone                   | e_mail        | website                     | 
| =================================================================== | ========================== | ========================== | ======================================================= | ==================================================== | ================================== | ======================================================================== | ========================= | ========================== | ============================ | ======================= | ============= | =========================== | 
| Water Well and/or Pump Installation Contractor Continuing Education | 2017-03-28T00:00:00        | 6                          | Independent Water Well Contractors                      | $50.00                                               | Forest Hills Lodge - Old West Room | 1601 West Lane Road (Rt 173 Forest Hills Road) West of Rockford Speedway | Loves Park                | IL                         | 61111                        | 815-742-4755            |               | [null, null]                | 
| Water Well and/or Pump Installation Contractor Continuing Education | 2017-02-10T00:00:00        | 6                          | Illinois Asociation of Groundwater Professionals (IAGP) | $115 -IAGP Member$145 Non IAGP Member                | Embassy Suites & Convention Center | 100 Conference Center                                                    | East Peoria               | IL                         | 61611                        | 815-973-3000            | info@iagp.org | [http://www.iagp.org, null] | 
| Water Well and/or Pump Installation Contractor Continuing Education | 2017-04-22T00:00:00        | 6                          | Illinois Asociation of Groundwater Professionals (IAGP) | $115 -IAGP Member$145 Non IAGP Member                | Kiswaukee College                  | 21193 Malta Rd                                                           | Malta                     | IL                         | 62702                        | 815-973-3000            | info@iagp.org | [http://www.iagp.org, null] | 
| Water Well and/or Pump Installation Contractor Continuing Education | 2017-03-17T00:00:00        | 6                          | Illinois Asociation of Groundwater Professionals (IAGP) | $115 -IAGP Member$145 Non IAGP Member                | Holiday Inn Convention Center      | 222 Potomac Blvd                                                         | Mt. Vernon                | IL                         | 62864                        | 815-973-3000            | info@iagp.org | [http://www.iagp.org, null] | 
| Closed Loop Well Installation Contractor Continuing Education       | 2017-02-10T00:00:00        | 6                          | Illinois Asociation of Groundwater Professionals (IAGP) | 115 -IAGP Member $145 Non IAGP Member                | Embassy Suites & Convention Center | 100 Conference Center                                                    | East Peoria               | IL                         | 61611                        | 815-973-3000            | info@iagp.org | [http://www.iagp.org, null] | 
| Closed Loop Well Installation Contractor Continuing Education       | 2017-03-17T00:00:00        | 6                          | Illinois Asociation of Groundwater Professionals (IAGP) | 115 -IAGP Member $145 Non IAGP Member                | Holiday Inn Convention Center      | 222 Potomac Blvd                                                         | Mt. Vernon                | IL                         | 62864                        | 815-973-3001            | info@iagp.org | [http://www.iagp.org, null] | 
| Closed Loop Well Installation Contractor Continuing Education       | 2017-04-22T00:00:00        | 6                          | Illinois Asociation of Groundwater Professionals (IAGP) | 115 -IAGP Member $145 Non IAGP Member                | Kiswaukee College                  | 21193 Malta Rd                                                           | Malta                     | IL                         | 62702                        | 815-973-3002            | info@iagp.org | [http://www.iagp.org, null] | 
| Water Well Continuing Education (Does not include Pump Installer)   | 2016-12-06T00:00:00        | 6                          | National Groundwater Association                        | http://www.ngwa.org/events-education/Pages/Home.aspx | Westgate Las Vegas Resort&Casino   | 3000 Paradise Road                                                       | Las Vegas                 | NV                         | 89109                        | Telephone: 800-551-7379 |               | [null, null]                | 
```