# Historic Clean Energy Grant Awards

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/historic-clean-energy-grant-awards) |
| Metadata | [Link](https://data.maryland.gov/api/views/4jem-ugpy) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/4jem-ugpy/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/4jem-ugpy/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | 4jem-ugpy |
| Name | Historic Clean Energy Grant Awards |
| Attribution | Maryland Energy Administration |
| Category | Energy and Environment |
| Tags | renewable energy, energy, clean energy, grants, maryland energy administration, mea, solar, solar pv, solar thermal, wind, wood burning stove |
| Created | 2013-05-06T20:22:14Z |
| Publication Date | 2015-04-28T21:16:34Z |

## Description

The goal of the Clean Energy Grant Program is to increase the amount of renewable energy generated in the Maryland. Grants are available for solar photovoltaic, solar water heating, geothermal heating & cooling, and wind technologies. For more information, see http://energy.maryland.gov/Residential/cleanenergygrants/index.html.

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                       | Data Type     | Render Type   |
| ======== | ============== | ========================== | ========================== | ============= | ============= |
| Yes      | series tag     | program_name               | Program Name               | text          | text          |
| Yes      | series tag     | technology                 | Technology                 | text          | text          |
| No       |                | application_received_date  | Application Received Date  | calendar_date | calendar_date |
| Yes      | time           | award_date                 | Award Date                 | calendar_date | calendar_date |
| Yes      | numeric metric | award_amount               | Award Amount               | money         | money         |
| No       |                | actual_start_date          | Actual Start Date          | calendar_date | calendar_date |
| No       |                | actual_end_date            | Actual End Date            | calendar_date | calendar_date |
| Yes      | series tag     | award_status               | Award Status               | text          | text          |
| No       |                | last_invoice_received_date | Last Invoice Received Date | calendar_date | calendar_date |
| Yes      | numeric metric | total_disbursed_amount     | Total Disbursed Amount     | money         | money         |
| Yes      | numeric metric | capacity                   | Capacity                   | number        | number        |
| Yes      | series tag     | capacity_units             | Capacity Units             | text          | text          |
| Yes      | numeric metric | total_project_cost         | Total Project Cost         | money         | money         |
| Yes      | series tag     | ownership                  | Ownership                  | text          | text          |
| Yes      | series tag     | city                       | City                       | text          | text          |
| Yes      | series tag     | zip_code                   | Zip Code                   | text          | number        |
| Yes      | series tag     | county                     | County                     | text          | text          |
```

## Time Field

```ls
Value = award_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = application_received_date,actual_start_date,actual_end_date,last_invoice_received_date
```

## Data Commands

```ls
series e:4jem-ugpy d:2011-04-04T00:00:00.000Z t:technology=Geothermal t:ownership=Purchased t:zip_code=21502 t:county=Allegany t:capacity_units=ton t:program_name="Residential Clean Energy Grant Program" t:city=LaVale t:award_status="Award Complete" m:award_amount=1500 m:total_project_cost=9525 m:capacity=3 m:total_disbursed_amount=1500

series e:4jem-ugpy d:2008-01-01T00:00:00.000Z t:technology=Geothermal t:ownership=Purchased t:zip_code=21505 t:county=Allegany t:capacity_units=ton t:program_name="Residential Clean Energy Grant Program" t:city=LaVale t:award_status="Award Complete" m:award_amount=1000 m:total_project_cost=32406 m:capacity=4.91 m:total_disbursed_amount=0

series e:4jem-ugpy d:2010-03-19T00:00:00.000Z t:technology="Solar Hot Water" t:ownership=Purchased t:zip_code=21740 t:county=Allegany t:capacity_units=sqft t:program_name="Residential Clean Energy Grant Program" t:city=Hagerstown t:award_status="Award Complete" m:award_amount=2500 m:total_project_cost=8500 m:capacity=47 m:total_disbursed_amount=2500
```

## Meta Commands

```ls
metric m:award_amount p:double l:"Award Amount" d:"The value of the grant based on the technology, capacity, and cost of the system." t:dataTypeName=money

metric m:total_disbursed_amount p:double l:"Total Disbursed Amount" d:"The value of the invoice that was sent to the State Finance Office." t:dataTypeName=money

metric m:capacity p:double l:Capacity t:dataTypeName=number

metric m:total_project_cost p:double l:"Total Project Cost" d:"The final invoice of the project as reported by the installing contractor." t:dataTypeName=money

entity e:4jem-ugpy l:"Historic Clean Energy Grant Awards" t:attribution="Maryland Energy Administration" t:url=https://data.maryland.gov/api/views/4jem-ugpy

property e:4jem-ugpy t:meta.view v:id=4jem-ugpy v:category="Energy and Environment" v:averageRating=0 v:name="Historic Clean Energy Grant Awards" v:attribution="Maryland Energy Administration"

property e:4jem-ugpy t:meta.view.owner v:id=rajf-egfu v:screenName=Dlauf v:displayName=Dlauf

property e:4jem-ugpy t:meta.view.tableauthor v:id=rajf-egfu v:screenName=Dlauf v:roleName=editor v:displayName=Dlauf
```

## Top Records

```ls
| program_name                           | technology      | application_received_date | award_date          | award_amount | actual_start_date   | actual_end_date     | award_status   | last_invoice_received_date | total_disbursed_amount | capacity | capacity_units | total_project_cost | ownership | city       | zip_code | county   | 
| ====================================== | =============== | ========================= | =================== | ============ | =================== | =================== | ============== | ========================== | ====================== | ======== | ============== | ================== | ========= | ========== | ======== | ======== | 
| Residential Clean Energy Grant Program | Geothermal      | 2010-11-29T00:00:00       | 2011-04-04T00:00:00 | 1500.00      | 2010-10-15T00:00:00 | 2010-10-15T00:00:00 | Award Complete | 2011-04-22T00:00:00        | 1500.00                | 3        | ton            | 9525               | Purchased | LaVale     | 21502    | Allegany | 
| Residential Clean Energy Grant Program | Geothermal      | 2008-01-01T00:00:00       | 2008-01-01T00:00:00 | 1000.00      |                     | 2008-01-01T00:00:00 | Award Complete |                            | 0.00                   | 4.91     | ton            | 32406              | Purchased | LaVale     | 21505    | Allegany | 
| Residential Clean Energy Grant Program | Solar Hot Water | 2009-12-11T00:00:00       | 2010-03-19T00:00:00 | 2500.00      | 2009-10-01T00:00:00 | 2009-10-21T00:00:00 | Award Complete | 2010-04-14T00:00:00        | 2500.00                | 47       | sqft           | 8500               | Purchased | Hagerstown | 21740    | Allegany | 
| Hist Residential Renewable Grants      | Solar PV        | 2008-05-01T00:00:00       | 2008-05-01T00:00:00 | 2965.80      |                     | 2008-05-01T00:00:00 | Award Complete |                            | 0.00                   | 1        | kW             | 12929              | Purchased | Cumberland | 21502    | Allegany | 
| Hist Residential Renewable Grants      | Solar PV        | 2008-05-01T00:00:00       | 2008-05-01T00:00:00 | 3000.00      |                     | 2008-05-01T00:00:00 | Award Complete |                            | 0.00                   | 2        | kW             | 18470              | Purchased | Frostburg  | 21532    | Allegany | 
| Residential Clean Energy Grant Program | Geothermal      | 2008-08-29T00:00:00       | 2009-08-03T00:00:00 | 3000.00      | 2008-08-29T00:00:00 | 2008-07-01T00:00:00 | Award Complete | 2009-08-03T00:00:00        | 3000.00                | 3        | ton            | 19987              | Purchased | Barton     | 21521    | Allegany | 
| Residential Clean Energy Grant Program | Geothermal      | 2013-12-04T00:00:00       | 2014-01-06T00:00:00 | 3000.00      | 2013-05-15T00:00:00 | 2013-09-01T00:00:00 | Award Complete | 2014-04-07T00:00:00        | 3000.00                | 5        | ton            | 35958              | Purchased | Frostburg  | 21532    | Allegany | 
| Residential Clean Energy Grant Program | Solar Hot Water | 2010-10-28T00:00:00       | 2010-10-28T00:00:00 | 2500.00      |                     |                     | Award Complete | 2010-10-28T00:00:00        | 2500.00                | 50       | sqft           |                    | Purchased | TRAPPE     | 21673    | Allegany | 
| Residential Clean Energy Grant Program | Geothermal      | 2010-02-16T00:00:00       | 2010-08-03T00:00:00 | 1500.00      | 2009-09-15T00:00:00 | 2009-09-30T00:00:00 | Award Complete | 2010-12-06T00:00:00        | 1500.00                | 3        | ton            | 29611              | Purchased | Flintstone | 21530    | Allegany | 
| Residential Clean Energy Grant Program | Solar PV        | 2009-05-19T00:00:00       | 2009-07-17T00:00:00 | 3000.00      | 2009-05-19T00:00:00 | 2009-07-27T00:00:00 | Award Complete | 2009-11-12T00:00:00        | 3000.00                | 2.4      | kW             | 20475              | Purchased | Frostburg  | 21532    | Allegany | 
```