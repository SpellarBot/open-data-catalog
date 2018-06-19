# Air Quality (2003 - Present)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/air-quality-2003-present) |
| Metadata | [Link](https://data.nola.gov/api/views/8zjg-mpeq) |
| Data: JSON | [100 Rows](https://data.nola.gov/api/views/8zjg-mpeq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.nola.gov/api/views/8zjg-mpeq/rows.csv?max_rows=100) |
| Host | data.nola.gov |
| Id | 8zjg-mpeq |
| Name | Air Quality (2003 - Present) |
| Attribution | U.S. Environmental Protection Agency (EPA), Air Quality Index (AQI) Report |
| Category | Environment |
| Created | 2015-04-28T21:26:30Z |
| Publication Date | 2016-01-25T21:48:20Z |

## Description

This data comes from the U.S. Environmental Protection Agency and is reported annually beginning in 2003. It includes data for New Orleans and several benchmark cities, including: Atlanta, Baton Rouge, Louisville, Memphis, Miami, Nashville, Oklahoma City, Raleigh, and Tampa.

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type     | Render Type   |
| ======== | ============== | ============== | ============== | ============= | ============= |
| Yes      | series tag     | rowid          | RowID          | text          | text          |
| Yes      | series tag     | county_parish  | County-Parish  | text          | text          |
| Yes      | series tag     | state          | State          | text          | text          |
| Yes      | series tag     | indicator      | Indicator      | text          | text          |
| Yes      | time           | date           | Date           | calendar_date | calendar_date |
| No       |                | year           | Year           | number        | number        |
| Yes      | numeric metric | indicatorvalue | IndicatorValue | number        | number        |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = year
```

## Data Commands

```ls
series e:8zjg-mpeq d:2003-01-01T00:00:00.000Z t:indicator="Percent of days with ""good"" or ""moderate"" air quality" t:county_parish="Wake County" t:state=NC t:rowid="Wake County2003" m:indicatorvalue=95.6

series e:8zjg-mpeq d:2003-01-01T00:00:00.000Z t:indicator="Percent of days with ""good"" or ""moderate"" air quality" t:county_parish="Shelby County" t:state=TN t:rowid="Shelby County2003" m:indicatorvalue=86.9

series e:8zjg-mpeq d:2003-01-01T00:00:00.000Z t:indicator="Percent of days with ""good"" or ""moderate"" air quality" t:county_parish="Orleans Parish" t:state=LA t:rowid="Orleans Parish2003" m:indicatorvalue=99.5
```

## Meta Commands

```ls
metric m:indicatorvalue p:double l:IndicatorValue t:dataTypeName=number

entity e:8zjg-mpeq l:"Air Quality (2003 - Present)" t:attribution="U.S. Environmental Protection Agency (EPA), Air Quality Index (AQI) Report" t:url=https://data.nola.gov/api/views/8zjg-mpeq

property e:8zjg-mpeq t:meta.view v:id=8zjg-mpeq v:category=Environment v:attributionLink=http://www.epa.gov/airdata/ad_rep_aqi.html v:averageRating=0 v:name="Air Quality (2003 - Present)" v:attribution="U.S. Environmental Protection Agency (EPA), Air Quality Index (AQI) Report"

property e:8zjg-mpeq t:meta.view.owner v:id=ii98-542e v:screenName=mschigoda v:displayName=mschigoda

property e:8zjg-mpeq t:meta.view.tableauthor v:id=ii98-542e v:screenName=mschigoda v:roleName=publisher v:displayName=mschigoda

property e:8zjg-mpeq t:meta.view.metadata.custom_fields.common_core v:Contact_Email=data@nola.gov
```

## Top Records

```ls
| rowid                       | county_parish           | state | indicator                                             | date                | year | indicatorvalue | 
| =========================== | ======================= | ===== | ===================================================== | =================== | ==== | ============== | 
| Wake County2003             | Wake County             | NC    | Percent of days with "good" or "moderate" air quality | 2003-01-01T00:00:00 | 2003 | 95.6           | 
| Shelby County2003           | Shelby County           | TN    | Percent of days with "good" or "moderate" air quality | 2003-01-01T00:00:00 | 2003 | 86.9           | 
| Orleans Parish2003          | Orleans Parish          | LA    | Percent of days with "good" or "moderate" air quality | 2003-01-01T00:00:00 | 2003 | 99.5           | 
| Oklahoma County2003         | Oklahoma County         | OK    | Percent of days with "good" or "moderate" air quality | 2003-01-01T00:00:00 | 2003 | 95.1           | 
| Miami-Dade County2003       | Miami-Dade County       | LF    | Percent of days with "good" or "moderate" air quality | 2003-01-01T00:00:00 | 2003 | 99.2           | 
| Jefferson County2003        | Jefferson County        | KY    | Percent of days with "good" or "moderate" air quality | 2003-01-01T00:00:00 | 2003 | 81.6           | 
| Hillsborough County2003     | Hillsborough County     | FL    | Percent of days with "good" or "moderate" air quality | 2003-01-01T00:00:00 | 2003 | 75.3           | 
| Fulton County2003           | Fulton County           | GA    | Percent of days with "good" or "moderate" air quality | 2003-01-01T00:00:00 | 2003 | 88.2           | 
| East Baton Rouge Parish2003 | East Baton Rouge Parish | LA    | Percent of days with "good" or "moderate" air quality | 2003-01-01T00:00:00 | 2003 | 93.4           | 
| Davidson County2003         | Davidson County         | TN    | Percent of days with "good" or "moderate" air quality | 2003-01-01T00:00:00 | 2003 | 92.6           | 
```