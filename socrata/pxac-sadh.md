# San Francisco Municipal Greenhouse Gas Inventory

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/san-francisco-municipal-greenhouse-gas-inventory) |
| Metadata | [Link](https://data.sfgov.org/api/views/pxac-sadh) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/pxac-sadh/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/pxac-sadh/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | pxac-sadh |
| Name | San Francisco Municipal Greenhouse Gas Inventory |
| Category | Energy and Environment |
| Created | 2016-01-01T00:28:28Z |
| Publication Date | 2016-01-21T22:38:27Z |

## Description

The purpose of the San Francisco Municipal Greenhouse Gas Inventory is to measure and track departmental greenhouse gas emissions as part of the City's climate action strategy. Per Environment Code Chapter 9, this data is collected and calculated by the Department of the Environment.

Note: Data as of 12/21/2015. San Francisco municipal greenhouse gas inventory for Fiscal Years 2012 per the California Air Resources Board's Local Government Operations Protocol Version 1.1 (May 2010).  Third-party verification of Fiscal Year 2012 which was completed in March 2015 is available at http://sfenvironment.org/download/fiscal-year-2012-municipal-ghg-inventory-memo  Since the third-party verification was conducted, the following minor edits were made to the dataset: - The CH4/N2O scaling factor applied to SFMTA gasoline changed from 1.025 to 1.022 and SFMTA CNG changed from 1.032 to 1.022 - More up to date wastewater emission data was obtained

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type | Render Type |
| ======== | ============== | ================= | ================= | ========= | =========== |
| Yes      | series tag     | department        | Department        | text      | text        |
| Yes      | series tag     | source_type       | Source_Type       | text      | text        |
| No       |                | fiscal_year       | Fiscal_Year       | number    | number      |
| No       |                | quarter           | Quarter           | text      | text        |
| Yes      | numeric metric | emissions_mtco2e  | Emissions_mtCO2e  | number    | number      |
| Yes      | numeric metric | consumption       | Consumption       | number    | number      |
| Yes      | series tag     | consumption_units | Consumption_Units | text      | text        |
```

## Time Field

```ls
Value = fiscal_year-quarter
Format & Zone = yyyy-q
```

## Series Fields

```ls
Excluded Fields = fiscal_year,quarter
```

## Data Commands

```ls
series e:pxac-sadh d:2011-10-01T00:00:00.000Z t:department="311 Customer Service Center" t:source_type=Electric t:consumption_units="Electric (kWh)" m:consumption=87717.259736902 m:emissions_mtco2e=0

series e:pxac-sadh d:2011-10-01T00:00:00.000Z t:department="311 Customer Service Center" t:source_type="Natural Gas" t:consumption_units="Natural Gas (therms)" m:consumption=500.419844161 m:emissions_mtco2e=2.664078639

series e:pxac-sadh d:2011-10-01T00:00:00.000Z t:department="311 Customer Service Center" t:source_type=Electric t:consumption_units="Electric (kWh)" m:consumption=86972.812518788 m:emissions_mtco2e=0
```

## Meta Commands

```ls
metric m:emissions_mtco2e p:decimal l:Emissions_mtCO2e d:"Total GHG emissions accounted for in metric tons of carbon dioxide equivalents (mtCO2e)" t:dataTypeName=number

metric m:consumption p:double l:Consumption d:"Total quantity of each source type. Note that consumption can also mean quantity purchased." t:dataTypeName=number

entity e:pxac-sadh l:"San Francisco Municipal Greenhouse Gas Inventory" t:url=https://data.sfgov.org/api/views/pxac-sadh

property e:pxac-sadh t:meta.view v:id=pxac-sadh v:category="Energy and Environment" v:averageRating=0 v:name="San Francisco Municipal Greenhouse Gas Inventory"

property e:pxac-sadh t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:pxac-sadh t:meta.view.owner v:id=dbag-6qd9 v:screenName=OpenData v:displayName=OpenData

property e:pxac-sadh t:meta.view.tableauthor v:id=dbag-6qd9 v:screenName=OpenData v:roleName=publisher v:displayName=OpenData
```

## Top Records

```ls
| department                  | source_type | fiscal_year | quarter | emissions_mtco2e   | consumption        | consumption_units    | 
| =========================== | =========== | =========== | ======= | ================== | ================== | ==================== | 
| 311 Customer Service Center | Electric    | 2012        | Q1      | 0                  | 87717.259736901993 | Electric (kWh)       | 
| 311 Customer Service Center | Natural Gas | 2012        | Q1      | 2.664078639        | 500.41984416100001 | Natural Gas (therms) | 
| 311 Customer Service Center | Electric    | 2012        | Q2      | 0                  | 86972.812518788007 | Electric (kWh)       | 
| 311 Customer Service Center | Natural Gas | 2012        | Q2      | 2.63207535         | 494.40835467699998 | Natural Gas (therms) | 
| 311 Customer Service Center | Electric    | 2012        | Q3      | 0                  | 85772.713947308002 | Electric (kWh)       | 
| 311 Customer Service Center | Natural Gas | 2012        | Q3      | 5.3297184140000002 | 1001.132931712     | Natural Gas (therms) | 
| 311 Customer Service Center | Electric    | 2012        | Q4      | 0                  | 87920.086414631995 | Electric (kWh)       | 
| 311 Customer Service Center | Natural Gas | 2012        | Q4      | 3.284109833        | 616.88634368600003 | Natural Gas (therms) | 
| Adult Probation Department  | B20         | 2012        | Q1      | 0                  | 0                  | B20 (gallons)        | 
| Adult Probation Department  | B5          | 2012        | Q1      | 0                  | 0                  | B5 (gallons)         | 
```